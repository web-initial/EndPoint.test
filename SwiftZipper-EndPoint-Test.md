# Test endpoint SwiftZipper

---

### Qr and Short link (Status 200)

> **https://run.mocky.io/v3/bb92c5f0-6f87-4d81-b5c2-4eb507846337** 

___Response Format:___

```JSON
{
  "qr-code-link": "http://qrcoder.ru/code/?%CD%E0%F1%F2%FF%2C+%FF+%F2%E5%E1%FF+%EB%FE%E1%EB%FE%21&6&0",
  "short-link": "http://qrcoder.ru"
}
```

---


### Not found (Status 404)

> **https://run.mocky.io/v3/b0ef3773-c8c9-45af-9bc1-863d283edc38** 

___Response Format:___

```JSON
{
	"message": "No such link exists"
}
```

---

### Server error (Status 500)

> **https://run.mocky.io/v3/7803f407-71ce-4d94-9381-4e1d81adfb60** 

___Response Format:___

```JSON
{
	"message": "Server error"
}
```

---
