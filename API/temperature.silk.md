# Temperature
## POST /temperature

Temperature

* Content-Type: "application/json"
* Accept:  "application/json"

Include the `terminalid`, `temperature`, `timestamp` and `request`

```
{
	"terminalid": "123",
	"temperature": "40",
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
[Back] (../index.md)