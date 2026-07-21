# Weather Data API Reference

This project demonstrates how to document structured JSON payloads into a clean, developer-facing API reference table.

## The Raw Data (JSON)
Below is the data payload returned by the weather service endpoint:

```json
{
  "status": "success",
  "data": {
    "location_id": "LOC-8832",
    "temp_f": 72.5,
    "precip_prob": 0.15,
    "uv_alert": false
  }
}
```

---

## API Reference Table

| Field | Data Type | Description |
| :--- | :--- | :--- |
| `status` | String | The status of the API request. Returns `success` or `error`. |
| `location_id` | String | The unique alphanumeric identifier for the weather station location. |
| `temp_f` | Number | The current temperature measured in degrees Fahrenheit. |
| `precip_prob` | Number | The probability of precipitation, expressed as a decimal between `0.00` (0%) and `1.00` (100%). |
| `uv_alert` | Boolean | Specifies whether an active high-radiation UV warning is in place (`true`) or not (`false`). |
