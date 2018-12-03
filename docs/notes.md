# Notes

## On the timestamp

Timestamp is given in Unix time ("epoch"), with 1h earlier than the reported date and time. This delay corresponds to `82800` in Unix time. So the real local time in Unix time should be `timestamp + delay` where `delay = 82800`.

## Data sources

Weather: https://montreal.weatherstats.ca/download.html
