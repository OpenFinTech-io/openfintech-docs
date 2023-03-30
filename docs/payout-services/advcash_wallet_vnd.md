
# AdvCash (service) 
![advcash_wallet_vnd](https://static.openfintech.io/payout_methods/advcash_wallet_vnd/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `advcash_wallet_vnd` 
 
**Method:** `advcash_wallet` [show -->](/payout-methods/advcash_wallet/) 
 
**Currency:** `VND` [show -->](/currencies/VND/) 
 
**Name:** 
 
:	[EN] AdvCash 
 
**Amount limits:** from `30000` to `1000000000` VND 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`wallet_id`|✔|`string`|`/^.{1,50}$/`| 
 

### Details 
 
1. **`wallet_id`** 
 
	Type: `string` 
 
	Regexp: `/^.{1,50}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Wallet ID 
	: [RU] Номер кошелька 
	: [UK] Номер гаманця 
 
	Hint:  
	: [EN] Enter wallet ID 
	: [RU] Введите номер кошелька 
	: [UK] Введіть номер гаманця 
 

## JSON Object 

```json
{
  "code":"advcash_wallet_vnd",
  "method":"advcash_wallet",
  "currency":"VND",
  "fields":[
    {
      "key":"wallet_id",
      "type":"string",
      "label":{
        "en":"Wallet ID",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u043a\u043e\u0448\u0435\u043b\u044c\u043a\u0430",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0433\u0430\u043c\u0430\u043d\u0446\u044f"
      },
      "hint":{
        "en":"Enter wallet ID",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043d\u043e\u043c\u0435\u0440 \u043a\u043e\u0448\u0435\u043b\u044c\u043a\u0430",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043d\u043e\u043c\u0435\u0440 \u0433\u0430\u043c\u0430\u043d\u0446\u044f"
      },
      "regexp":"\/^.{1,50}$\/",
      "required":true,
      "position":1
    }
  ],
  "amount_min":"30000",
  "amount_max":"1000000000"
}
```  