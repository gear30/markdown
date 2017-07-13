# Register
## POST /register

Register

* Content-Type: "application/json"
* Accept:  "application/json"

Include the `terminalid` and `otp`

```
{
	"terminalid": "123",
	"otp": "3456"
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
		"clientid": "0098",
		"merchantid": "0092",
		"terminalid": "123",
		"token": "AEEWAA211",
		"created": "12/11/2017"
	}
}
```
[Back](../index.md)