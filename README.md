## 10x Genomics IT Automation Technical Coding Interview

Create a service that converts a CSV file into JSON API.

We've provided a CSV file of Seattle weather `seattle-weather.csv`. It contains
the following labels in the header:

```
date,precipitation,temp_max,temp_min,wind,weather
```

### Your tasks:

1. Read in CSV file, output JSON
2. Create a server that responds with the output in JSON
3. Set up querying on the data:
  - Limit results to a number `http://my-server.example.com/query?limit=5`
  - Search by date: `http://my-server.example.com/query?date=11-02-23`
  - Search by weather type: `http://my-server.example.com/query?weather=rain`
  - Search by max and min temperature
