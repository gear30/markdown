# Completesale
## POST /vending/completesale

Completesale

* Content-Type: "application/json"
* Accept:  "application/json"

Include the `terminalid`, `reference`, `amount`, `banknote`, `change`, `timestamp` and `request`

```
{
	"terminalid": "0091",
	"reference": "RF1223",
	"amount": "10000",
	"banknote": "123-111",
	"change": "123-111",
	"timestamp": "12/11/2017",
	"request": HttpServletRequest
}
```

--

### Example Result

* Status: 200
* Content-Type: "application/json"

```
{
	"message": "success"
}
```
[Back](../index.md)