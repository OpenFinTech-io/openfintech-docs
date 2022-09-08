
# TRON (service) 
![tron_trx](https://static.openfintech.io/payout_methods/tron_trx/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `tron_trx` 
 
**Method:** `tron` [show -->](/payout-methods/tron/) 
 
**Currency:** `TRX` [show -->](/currencies/TRX/) 
 
**Name:** 
 
:	[EN] TRON 
:	[RU] TRON 
:	[UK] TRON 
 
**Amount limits:** from `0.000001` to `1000000` TRX 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`wallet_id`|✔|`string`|`/^.{10,64}$/`| 
 

### Details 
 
1. **`wallet_id`** 
 
	Type: `string` 
 
	Regexp: `/^.{10,64}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Wallet Address 
	: [RU] Адрес кошелька 
	: [UK] Адреса гаманця 
 
	Hint:  
	: [EN] Enter wallet address 
	: [RU] Введите адрес кошелька 
	: [UK] Введіть адресу гаманця 
 

## JSON Object 

```json
{
  "code":"tron_trx",
  "method":"tron",
  "currency":"TRX",
  "fields":[
    {
      "key":"wallet_id",
      "type":"string",
      "label":{
        "en":"Wallet Address",
        "ru":"\u0410\u0434\u0440\u0435\u0441 \u043a\u043e\u0448\u0435\u043b\u044c\u043a\u0430",
        "uk":"\u0410\u0434\u0440\u0435\u0441\u0430 \u0433\u0430\u043c\u0430\u043d\u0446\u044f"
      },
      "hint":{
        "en":"Enter wallet address",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u0430\u0434\u0440\u0435\u0441 \u043a\u043e\u0448\u0435\u043b\u044c\u043a\u0430",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u0430\u0434\u0440\u0435\u0441\u0443 \u0433\u0430\u043c\u0430\u043d\u0446\u044f"
      },
      "regexp":"\/^.{10,64}$\/",
      "required":true,
      "position":1
    }
  ],
  "amount_min":"0.000001",
  "amount_max":"1000000"
}
```  
