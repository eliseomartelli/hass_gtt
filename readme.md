# HASS GTT

GTT Custom Component for Home Assistant
---

This component integrates a GTT timetable in Home Assistant so you can use GTT's data to trigger automations, send notifications and do other things inside Home Assistant. 


## Configuration

```
sensor:
  - platform: gtt
    stop: 1130
    bus_name: 10
```

| Option | Default | Optional |
|---|---|---|
| stop | none | no |
| bus_name | none | yes |

