
# Taxi Economy 7000 (Zaporizhia) (service) 
![taksi-ekonom-7000-zaporozhe_uah](https://static.openfintech.io/payout_methods/taksi-ekonom-7000-zaporozhe_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `taksi-ekonom-7000-zaporozhe_uah` 
 
**Method:** `taksi-ekonom-7000-zaporozhe` [show -->](/payout-methods/taksi-ekonom-7000-zaporozhe/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] Taxi Economy 7000 (Zaporizhia) 
:	[RU] Такси Эконом 7000 (Запорожье) 
:	[UK] Таксі Економ 7000 (Запоріжжя) 
 
**Amount limits:** from `2` to `5000` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`client_id`|✔|`string`|`/^\d{1,128}$/`| 
 

### Details 
 
1. **`client_id`** 
 
	Type: `string` 
 
	Regexp: `/^\d{1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Caller ID 
	: [UK] Номер позивного 
	: [RU] Номер позывного 
 
	Hint:  
	: [EN] Caller ID 
	: [UK] Номер позивного 
	: [RU] Номер позывного 
 

## JSON Object 

```json
{
  "code":"taksi-ekonom-7000-zaporozhe_uah",
  "method":"taksi-ekonom-7000-zaporozhe",
  "currency":"UAH",
  "fields":[
    {
      "key":"client_id",
      "type":"string",
      "label":{
        "en":"Caller ID",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u043f\u043e\u0437\u0438\u0432\u043d\u043e\u0433\u043e",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u043f\u043e\u0437\u044b\u0432\u043d\u043e\u0433\u043e"
      },
      "regexp":"\/^\\d{1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"Caller ID",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u043f\u043e\u0437\u0438\u0432\u043d\u043e\u0433\u043e",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u043f\u043e\u0437\u044b\u0432\u043d\u043e\u0433\u043e"
      },
      "example":"12700"
    }
  ],
  "amount_min":2,
  "amount_max":5000
}
```  