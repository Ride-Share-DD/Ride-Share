# Updating the AADD schedule

Edit `events.json` on the website's main branch. Add one object for each event:

```json
[
  {
    "date": "2027-05-15",
    "time": "10:00 AM–2:00 PM Central",
    "title": "Community event",
    "location": "Community center",
    "description": "Visit the AADD table."
  }
]
```

Use a real date in `YYYY-MM-DD` format. Include the time zone in `time`. The
`date`, `time`, `title`, and `location` fields are required; `description` is
optional. Separate multiple objects with commas, and remove events that should
no longer appear. An empty list (`[]`) shows that no events are scheduled.
