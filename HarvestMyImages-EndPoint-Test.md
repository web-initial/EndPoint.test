# Test endpoint HarvestMyImages

---

### Single photo (Status 200)

> **https://run.mocky.io/v3/70b45165-0024-4871-a265-c85206108eb8** 

___Response Format:___

```JSON
{
  "images-link": [
    {
    "img-link": "https://images.unsplash.com/"
    }
  ]
}
```

---

### Photo set (Status 200)

> **https://run.mocky.io/v3/398926ee-39d6-4f85-9f87-0bde00bd7cab** 

___Response Format:___

```JSON
{
  "images-link": [
    {
      "img-link": "https://images.unsplash.com/photo/"
    },
    {
      "img-link": "https://images.pexels.com/photos/"
    },
    {
      "img-link": "https://images.pexels.com/photos/"
    }
  ]
}
```

---

### Single video (Status 200)

> **https://run.mocky.io/v3/d527ec2a-dabb-446c-9b84-66113d7273f1** 

___Response Format:___

```JSON
{
  "video-items": [
    {
      "video-link": "https://images.unsplash.com/video"
    }
  ]
}
```

---

### Video set (Status 200)

> **https://run.mocky.io/v3/398926ee-39d6-4f85-9f87-0bde00bd7cab** 

___Response Format:___

```JSON
{
    "video-item": [
        {
            "video-link": "https://www.shutterstock.com/shutterstock/videos"
        },
        {
            "video-link": "https://www.shutterstock.com/shutterstock/videos"
        },
        {
            "video-link": "https://www.shutterstock.com/shutterstock/videos"
        }
    ]
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
