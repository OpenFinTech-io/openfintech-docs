
# Oriental Wallet (service) 
![oriental_wallet_jpy](https://static.openfintech.io/payout_methods/oriental_wallet_jpy/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `oriental_wallet_jpy` 
 
**Method:** `oriental_wallet` [show -->](/payout-methods/oriental_wallet/) 
 
**Currency:** `JPY` [show -->](/currencies/JPY/) 
 
**Name:** 
 
:	[EN] Oriental Wallet 
:	[RU] Oriental Wallet 
:	[UK] Oriental Wallet 
 
**Amount limits:** from `1` to `14300000` JPY 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`account_number`|✗|`string`|`/^[0-9]{2,100}$/`| 
 

### Details 
 
1. **`account_number`** 
 
	Type: `string` 
 
	Regexp: `/^[0-9]{2,100}$/` 
 
	Required: `` 
 
	Label:  
	: [EN] Account number 
	: [RU] Номер счета 
	: [UK] Номер рахунку 
 
	Hint:  
	: [EN] Enter account number 
	: [RU] Введите номер счета 
	: [UK] Введіть номер рахунку 
 

## JSON Object 

```json
{
  "code":"oriental_wallet_jpy",
  "method":"oriental_wallet",
  "currency":"JPY",
  "fields":[
    {
      "key":"account_number",
      "type":"string",
      "regexp":"\/^[0-9]{2,100}$\/",
      "label":{
        "en":"Account number",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u0441\u0447\u0435\u0442\u0430",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0440\u0430\u0445\u0443\u043d\u043a\u0443"
      },
      "hint":{
        "en":"Enter account number",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043d\u043e\u043c\u0435\u0440 \u0441\u0447\u0435\u0442\u0430",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043d\u043e\u043c\u0435\u0440 \u0440\u0430\u0445\u0443\u043d\u043a\u0443"
      },
      "required":false,
      "position":1
    }
  ],
  "amount_min":1,
  "amount_max":14300000
}
```  