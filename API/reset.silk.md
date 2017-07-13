# Reset
## POST /reset

Reset

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
	"message": "success"
}
```
[Back] (../index.md)