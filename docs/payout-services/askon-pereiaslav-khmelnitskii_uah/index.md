
# ASCON (Pereyaslav-Khmelnitsky) (service) 
![askon-pereiaslav-khmelnitskii_uah](https://static.openfintech.io/payout_methods/askon-pereiaslav-khmelnitskii_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `askon-pereiaslav-khmelnitskii_uah` 
 
**Method:** `askon-pereiaslav-khmelnitskii` 
[show -->](#) 
 
**Currency:** `UAH`[show -->](#) 
 
**Name:** 
 
:	[EN] ASCON (Pereyaslav-Khmelnitsky) 
:	[RU] АСКОН (Переяслав-Хмельницький) 
:	[UK] АСКОН (Переяслав-Хмельницький) 
 
**Amount limits:** from `2` to `14999` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`client_id`|✔|`string`|`/^(\w|\.| |\-|\+|@){1,128}$/`| 
 

### Details 
 
0. **`client_id`** 
 
	Type: `string` 
 
	Regexp: `/^(\w|\.| |\-|\+|@){1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Contract number 
	: [UK] Номер договору 
	: [RU] Номер договора 
 
	Hint:  
	: [EN] Contract number 
	: [UK] Номер договору 
	: [RU] Номер договора 
 

## JSON Object 

```json
{
  "code":"askon-pereiaslav-khmelnitskii_uah",
  "method":"askon-pereiaslav-khmelnitskii",
  "currency":"UAH",
  "fields":[
    {
      "key":"client_id",
      "type":"string",
      "label":{
        "en":"Contract number",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0434\u043e\u0433\u043e\u0432\u043e\u0440\u0443",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u0434\u043e\u0433\u043e\u0432\u043e\u0440\u0430"
      },
      "regexp":"\/^(\\w|\\.| |\\-|\\+|@){1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"Contract number",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0434\u043e\u0433\u043e\u0432\u043e\u0440\u0443",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u0434\u043e\u0433\u043e\u0432\u043e\u0440\u0430"
      },
      "example":"1480"
    }
  ],
  "amount_min":2,
  "amount_max":14999
}
```  