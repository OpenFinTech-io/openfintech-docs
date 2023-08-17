
# Pay4Fun (service) 
![pay4fun_brl_hpp](https://static.openfintech.io/payment_methods/pay4fun_brl_hpp/logo.svg?w=400&c=v0.59.26#w200)  

## General 
 
**Code:** `pay4fun_brl_hpp` 
 
**Method:** `pay4fun` 
 [show -->](/payment-methods/pay4fun/) 
 
**Currency:** `BRL` [show -->](/currencies/BRL/) 
 
**Name:** 
 
:	[EN] Pay4Fun 
 
**Amount limits:** from `0.01` to `500000` BRL 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`account_id`|✗|`string`|`/^[\w]{1,64}$/`| 
 

### Details 
 
1. **`account_id`** 
 
	Type: `string` 
 
	Regexp: `/^[\w]{1,64}$/` 
 
	Required: `` 
 
	Label:  
	: [EN] Account Id 
	: [RU] Номер счета 
	: [UK] Номер рахунку 
 
	Hint:  
	: [EN] Enter account id 
	: [RU] Введите номер счета 
	: [UK] Введіть номер рахунку 
 

## JSON Object 

```json
{
  "code":"pay4fun_brl_hpp",
  "flow":"hpp",
  "method":"pay4fun",
  "currency":"BRL",
  "fields":[
    {
      "key":"account_id",
      "type":"string",
      "label":{
        "en":"Account Id",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u0441\u0447\u0435\u0442\u0430",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0440\u0430\u0445\u0443\u043d\u043a\u0443"
      },
      "regexp":"\/^[\\w]{1,64}$\/",
      "required":false,
      "position":1,
      "hint":{
        "en":"Enter account id",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043d\u043e\u043c\u0435\u0440 \u0441\u0447\u0435\u0442\u0430",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043d\u043e\u043c\u0435\u0440 \u0440\u0430\u0445\u0443\u043d\u043a\u0443"
      },
      "example":"GB97BARC20031877565489"
    }
  ],
  "amount_min":0.01,
  "amount_max":500000
}
```  