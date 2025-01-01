# VATSIM Radar data

## Airlines List

```typescript
interface RadarDataAirline {
    icao: string
    name: string
    callsign: string
    country: string
    virtual: boolean
}
```

https://data.vatsim-radar.com/airlines

Source: https://gng.aero-nav.com/

- When making a PR, use /data/custom-list.json to propose your changes
- Other files in data are auto-generated
