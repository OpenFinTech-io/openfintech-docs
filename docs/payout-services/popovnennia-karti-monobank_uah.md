
# Поповнення карти Монобанк (service) 
![popovnennia-karti-monobank_uah](https://static.openfintech.io/payout_methods/popovnennia-karti-monobank_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `popovnennia-karti-monobank_uah` 
 
**Method:** `popovnennia-karti-monobank` [show -->](/payout-methods/popovnennia-karti-monobank/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] Поповнення карти Монобанк 
:	[RU] Поповнення карти Монобанк 
:	[UK] Поповнення карти Монобанк 
 
**Amount limits:** from `2.00` to `14999.00` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`client_id`|✔|`string`|`/^[\w\|\.\| \|\-\|\+\|@\|\#]{1,128}$/`| 
 

### Details 
 
1. **`client_id`** 
 
	Type: `string` 
 
	Regexp: `/^[\w|\.| |\-|\+|@|\#]{1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Номер картки#Телефон 
	: [RU] Номер картки#Телефон 
	: [UK] Номер картки#Телефон 
 
	Hint:  
	: [EN] Номер картки#Телефон 
	: [RU] Номер картки#Телефон 
	: [UK] Номер картки#Телефон 
 

## JSON Object 

```json
{
  "code":"popovnennia-karti-monobank_uah",
  "method":"popovnennia-karti-monobank",
  "currency":"UAH",
  "fields":[
    {
      "key":"client_id",
      "type":"string",
      "label":{
        "en":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u043a\u0438#\u0422\u0435\u043b\u0435\u0444\u043e\u043d",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u043a\u0438#\u0422\u0435\u043b\u0435\u0444\u043e\u043d",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u043a\u0438#\u0422\u0435\u043b\u0435\u0444\u043e\u043d"
      },
      "regexp":"\/^[\\w|\\.| |\\-|\\+|@|\\#]{1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u043a\u0438#\u0422\u0435\u043b\u0435\u0444\u043e\u043d",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u043a\u0438#\u0422\u0435\u043b\u0435\u0444\u043e\u043d",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u043a\u0438#\u0422\u0435\u043b\u0435\u0444\u043e\u043d"
      },
      "example":"1234567898765432#380123456789"
    }
  ],
  "amount_min":"2.00",
  "amount_max":"14999.00"
}
```  