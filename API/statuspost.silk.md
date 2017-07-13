# Status
## POST /vending/status/{terminalId}

Status

* Content-Type: "application/json"
* Accept:  "application/json"

Include the `terminalid`, `form` and `request`

```
{
	"terminalid": "123",
	"form": {
			  "limit": "2",
			  "offset": "1"
			},
	"request": HttpServletRequest
}
```

--

### Example Result

* Status: 200
* Content-Type: "application/json"

```
{
	"message": "success",
	"lists": [{
		"terminalId": "0023",
		"serialno": "S120",
		"firmware": "FW222",
		"state": "0",
		"created": "12/11/2017"
	}]
}
```
[Back](../index.md)