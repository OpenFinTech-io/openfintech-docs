
# Banco de Chile (service) 
![banco_de_chile_clp_hpp](https://static.openfintech.io/payment_methods/banco_de_chile_clp_hpp/logo.svg?w=400&c=v0.59.26#w200)  

## General 
 
**Code:** `banco_de_chile_clp_hpp` 
 
**Method:** `banco_de_chile` 
 [show -->](/payment-methods/banco_de_chile/) 
 
**Currency:** `CLP` [show -->](/currencies/CLP/) 
 
**Name:** 
 
:	[EN] Banco de Chile 
:	[RU] Banco de Chile 
:	[UK] Banco de Chile 
 
**Amount limits:** from `1` to `90340000` CLP 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`personal_id`|✔|`string`|`/^.{1,128}$/`| 
|`document_type`|✗|`string`|`/^[A-Z]{2,3}$/`| 
|`document_id`|✗|`string`|`/^[a-zA-Z0-9]{8,9}$/`| 
 

### Details 
 
1. **`personal_id`** 
 
	Type: `string` 
 
	Regexp: `/^.{1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Personal ID 
	: [RU] Личный идентификатор клиента 
	: [UK] Особистий ідентифікатор клієнту 
 
	Hint:  
	: [EN] Enter personal ID 
	: [RU] Введите личный идентификатор клиента 
	: [UK] Введіть особистий ідентифікатор клієнту 
 
2. **`document_type`** 
 
	Type: `string` 
 
	Regexp: `/^[A-Z]{2,3}$/` 
 
	Required: `` 
 
	Label:  
	: [EN] Document Type 
	: [RU] Тип документа 
	: [UK] Тип документу 
 
	Hint:  
	: [EN] Enter Document Type (ID, RUN, RUT) 
	: [RU] Введите тип документа (ID, RUN, RUT) 
	: [UK] Введіть тип документу (ID, RUN, RUT) 
 
3. **`document_id`** 
 
	Type: `string` 
 
	Regexp: `/^[a-zA-Z0-9]{8,9}$/` 
 
	Required: `` 
 
	Label:  
	: [EN] Payer personal identification number 
	: [RU] Номер документа плательщика 
	: [UK] Номер документа платника 
 
	Hint:  
	: [EN] Enter payer personal identification number 
	: [RU] Введите номер документа плательщика 
	: [UK] Введіть номер документа платника 
 

## JSON Object 

```json
{
  "code":"banco_de_chile_clp_hpp",
  "flow":"hpp",
  "method":"banco_de_chile",
  "currency":"CLP",
  "fields":[
    {
      "key":"personal_id",
      "type":"string",
      "regexp":"\/^.{1,128}$\/",
      "required":true,
      "position":1,
      "label":{
        "en":"Personal ID",
        "ru":"\u041b\u0438\u0447\u043d\u044b\u0439 \u0438\u0434\u0435\u043d\u0442\u0438\u0444\u0438\u043a\u0430\u0442\u043e\u0440 \u043a\u043b\u0438\u0435\u043d\u0442\u0430",
        "uk":"\u041e\u0441\u043e\u0431\u0438\u0441\u0442\u0438\u0439 \u0456\u0434\u0435\u043d\u0442\u0438\u0444\u0456\u043a\u0430\u0442\u043e\u0440 \u043a\u043b\u0456\u0454\u043d\u0442\u0443"
      },
      "hint":{
        "en":"Enter personal ID",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043b\u0438\u0447\u043d\u044b\u0439 \u0438\u0434\u0435\u043d\u0442\u0438\u0444\u0438\u043a\u0430\u0442\u043e\u0440 \u043a\u043b\u0438\u0435\u043d\u0442\u0430",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043e\u0441\u043e\u0431\u0438\u0441\u0442\u0438\u0439 \u0456\u0434\u0435\u043d\u0442\u0438\u0444\u0456\u043a\u0430\u0442\u043e\u0440 \u043a\u043b\u0456\u0454\u043d\u0442\u0443"
      }
    },
    {
      "key":"document_type",
      "type":"string",
      "regexp":"\/^[A-Z]{2,3}$\/",
      "required":false,
      "position":2,
      "label":{
        "en":"Document Type",
        "ru":"\u0422\u0438\u043f \u0434\u043e\u043a\u0443\u043c\u0435\u043d\u0442\u0430",
        "uk":"\u0422\u0438\u043f \u0434\u043e\u043a\u0443\u043c\u0435\u043d\u0442\u0443"
      },
      "hint":{
        "en":"Enter Document Type (ID, RUN, RUT)",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u0442\u0438\u043f \u0434\u043e\u043a\u0443\u043c\u0435\u043d\u0442\u0430 (ID, RUN, RUT)",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u0442\u0438\u043f \u0434\u043e\u043a\u0443\u043c\u0435\u043d\u0442\u0443 (ID, RUN, RUT)"
      }
    },
    {
      "key":"document_id",
      "type":"string",
      "regexp":"\/^[a-zA-Z0-9]{8,9}$\/",
      "required":false,
      "position":3,
      "label":{
        "en":"Payer personal identification number",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u0434\u043e\u043a\u0443\u043c\u0435\u043d\u0442\u0430 \u043f\u043b\u0430\u0442\u0435\u043b\u044c\u0449\u0438\u043a\u0430",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0434\u043e\u043a\u0443\u043c\u0435\u043d\u0442\u0430 \u043f\u043b\u0430\u0442\u043d\u0438\u043a\u0430"
      },
      "hint":{
        "en":"Enter payer personal identification number",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043d\u043e\u043c\u0435\u0440 \u0434\u043e\u043a\u0443\u043c\u0435\u043d\u0442\u0430 \u043f\u043b\u0430\u0442\u0435\u043b\u044c\u0449\u0438\u043a\u0430",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043d\u043e\u043c\u0435\u0440 \u0434\u043e\u043a\u0443\u043c\u0435\u043d\u0442\u0430 \u043f\u043b\u0430\u0442\u043d\u0438\u043a\u0430"
      }
    }
  ],
  "amount_min":1,
  "amount_max":90340000
}
```  
