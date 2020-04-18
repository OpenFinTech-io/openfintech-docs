
# Airtel Money (service) 
![airtel_money_tzs](https://static.openfintech.io/payout_methods/airtel_money_tzs/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `airtel_money_tzs` 
 
**Method:** `airtel_money` [show -->](/payout-methods/airtel_money/) 
 
**Currency:** `TZS` [show -->](/currencies/TZS/) 
 
**Name:** 
 
:	[EN] Airtel Money 
:	[RU] Airtel Money 
:	[UK] Airtel Money 
 
**Amount limits:** from `100` to `999999` TZS 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`phone`|✔|`string`|`/^\+\d{10,14}$/`| 
 

### Details 
 
1. **`phone`** 
 
	Type: `string` 
 
	Regexp: `/^\+\d{10,14}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Phone number 
	: [RU] Номер телефона 
	: [UK] Номер телефону 
 
	Hint:  
	: [EN] Enter phone number 
	: [RU] Введите номер телефона 
	: [UK] Введіть номер телефону 
 

## JSON Object 

```json
{
  "code":"airtel_money_tzs",
  "method":"airtel_money",
  "currency":"TZS",
  "fields":[
    {
      "key":"phone",
      "type":"string",
      "label":{
        "en":"Phone number",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0430",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0443"
      },
      "hint":{
        "en":"Enter phone number",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0430",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0443"
      },
      "example":"06534567891",
      "regexp":"\/^\\+\\d{10,14}$\/",
      "required":true,
      "position":1
    }
  ],
  "amount_min":"100",
  "amount_max":"999999"
}
```  