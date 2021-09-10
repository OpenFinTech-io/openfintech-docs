
# Ethereum (service) 
![ethereum_eur](https://static.openfintech.io/payout_methods/ethereum_eur/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `ethereum_eur` 
 
**Method:** `ethereum` [show -->](/payout-methods/ethereum/) 
 
**Currency:** `EUR` [show -->](/currencies/EUR/) 
 
**Name:** 
 
:	[EN] Ethereum 
:	[RU] Ethereum 
:	[UK] Ethereum 
 
**Amount limits:** from `1` to `500000` EUR 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`wallet_id`|✔|`string`|`/^0x[a-fA-F0-9]{40}$/`| 
 

### Details 
 
1. **`wallet_id`** 
 
	Type: `string` 
 
	Regexp: `/^0x[a-fA-F0-9]{40}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Ethereum wallet 
	: [RU] Ethereum кошелек 
	: [UK] Ethereum гаманець 
 
	Hint:  
	: [EN] Enter Ethereum wallet 
	: [RU] Введите Ethereum кошелек 
	: [UK] Введіть Ethereum гаманець 
 

## JSON Object 

```json
{
  "code":"ethereum_eur",
  "method":"ethereum",
  "currency":"EUR",
  "fields":[
    {
      "key":"wallet_id",
      "type":"string",
      "label":{
        "en":"Ethereum wallet",
        "ru":"Ethereum \u043a\u043e\u0448\u0435\u043b\u0435\u043a",
        "uk":"Ethereum \u0433\u0430\u043c\u0430\u043d\u0435\u0446\u044c"
      },
      "hint":{
        "en":"Enter Ethereum wallet",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 Ethereum \u043a\u043e\u0448\u0435\u043b\u0435\u043a",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c Ethereum \u0433\u0430\u043c\u0430\u043d\u0435\u0446\u044c"
      },
      "regexp":"\/^0x[a-fA-F0-9]{40}$\/",
      "required":true,
      "position":1
    }
  ],
  "amount_min":"1",
  "amount_max":"500000"
}
```  