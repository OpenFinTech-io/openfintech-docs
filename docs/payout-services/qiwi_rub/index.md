
# Qiwi (service) 
![qiwi_rub](https://static.openfintech.io/payout_methods/qiwi_rub/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `qiwi_rub` 
 
**Method:** `qiwi` 
[show -->](#) 
 
**Currency:** `RUB`[show -->](#) 
 
**Name:** 
 
:	[EN] Qiwi 
:	[RU] Qiwi 
:	[UK] Qiwi 
 
**Amount limits:** from `50` to `60000` RUB 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`wallet_id`|✔|`string`|`/^\+\d{1,15}$/`| 
 

### Details 
 
0. **`wallet_id`** 
 
	Type: `string` 
 
	Regexp: `/^\+\d{1,15}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Phone number 
	: [RU] Номер телефона 
	: [UK] Номер телеофу 
 
	Hint:  
	: [EN] Enter phone number 
	: [RU] Введите номер телефона Qiwi кошелька 
	: [UK] Введіть номер телефону Qiwi гаманця 
 

## JSON Object 

```json
{
  "code":"qiwi_rub",
  "method":"qiwi",
  "currency":"RUB",
  "fields":[
    {
      "key":"wallet_id",
      "type":"string",
      "label":{
        "en":"Phone number",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0430",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u043e\u0444\u0443"
      },
      "hint":{
        "en":"Enter phone number",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0430 Qiwi \u043a\u043e\u0448\u0435\u043b\u044c\u043a\u0430",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0443 Qiwi \u0433\u0430\u043c\u0430\u043d\u0446\u044f"
      },
      "regexp":"\/^\\+\\d{1,15}$\/",
      "required":true,
      "position":1
    }
  ],
  "amount_min":50,
  "amount_max":60000
}
```  