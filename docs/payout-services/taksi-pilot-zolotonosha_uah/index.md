
# Taxi Pilot (Zolotonosha) (service) 
![taksi-pilot-zolotonosha_uah](https://static.openfintech.io/payout_methods/taksi-pilot-zolotonosha_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `taksi-pilot-zolotonosha_uah` 
 
**Method:** `taksi-pilot-zolotonosha` 
[show -->](#) 
 
**Currency:** `UAH`[show -->](#) 
 
**Name:** 
 
:	[EN] Taxi Pilot (Zolotonosha) 
:	[RU] Такси Пилот (Золотоноша) 
:	[UK] Таксі Пілот (Золотоноша) 
 
**Amount limits:** from `2` to `14999` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`client_id`|✔|`string`|`/^\d{1,128}$/`| 
 

### Details 
 
0. **`client_id`** 
 
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
  "code":"taksi-pilot-zolotonosha_uah",
  "method":"taksi-pilot-zolotonosha",
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
      "example":"888"
    }
  ],
  "amount_min":2,
  "amount_max":14999
}
```  