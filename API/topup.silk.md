# Topup
## POST /topup

Topup payment

* Content-Type: "application/json"
* Accept:  "application/json"

Include the `terminalid`, `amount`, `cardid` and `topupsting`

```
{
	"terminalid": "123",
	"amount": "1000.00",
	"cardid": "1234-5678-9012-3456",
	"topupsting": "Topup"
}
```

--

### Example Result

* Status: 200
* Content-Type: "application/json"

```
{
	"message": "success",
	"model": {
		"txnid": "0023",
		"clientid": "0098",
		"merchantid": "0092",
		"terminalid": "123",
		"cardid": "1234-5678-9012-3456",
		"amount": "1000.00",
		"balance": "1000.00",		
		"created": "12/11/2017"
	}
}
```
[Back] (../index.md)