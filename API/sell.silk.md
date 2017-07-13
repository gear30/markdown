# Sell
## POST /vending/sell

Sale item

* Content-Type: "application/json"
* Accept:  "application/json"

Include the `total`, `payment`, `change`, `type`, `sale_pay` and `sale_subs`

```
{
  "total": "1",
  "payment": "1", 
  "change": "1", 
  "type": "Can", 
  "sale_pay": "20",
  "sale_subs": "5"
}
```

--

### Example Result

* Status: 200
* Content-Type: "application/json"

```
{
  "message":"success"
}
```
[Back] (../index.md)