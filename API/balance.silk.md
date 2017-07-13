# Balance
## POST /balance

Get balance

* Content-Type: "application/json"
* Accept:  "application/json"

Include the `terminalid` and `cardid`

```
{
	"terminalid": "123",
	"cardid": "1234-5678-9012-3456"
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
		"clientid": "0023",
		"merchantid": "0098",
		"terminalid": "123",
		"cardid": "1234-5678-9012-3456",
		"balance": "10.00",
		"created": "12/11/2017"
	}
}
```
[Back](../index.md)