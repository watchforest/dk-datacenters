# Danish Datacenters

A community-maintained dataset of datacenters in Denmark.

## Dataset

The dataset is stored in [`datacenters.csv`](datacenters.csv) and currently contains 88 entries.

### Columns

| Column | Description |
|--------|-------------|
| `market` | City or region (e.g. `Copenhagen`, `Aarhus`) |
| `name` | Facility name or identifier |
| `status` | Operational status (`Operational`, `Under Construction`, `Planned`, `Decommissioned`) |
| `operator` | Company operating the facility |
| `address` | Street address |
| `google_maps_url` | Google Maps link to the facility |
| `website` | Operator's page for the facility |
| `description` | Free-text description of the facility |
| `services_overview` | High-level service offerings (e.g. `Suites; Cages; Remote Hands`) |
| `services_specs` | Detailed service specifications |
| `power_mw` | Total IT power capacity in megawatts |
| `whitespace_sqm` | Raised floor / white space in square metres |
| `building_size_sqm` | Total building size in square metres |
| `ups_redundancy` | UPS redundancy level (e.g. `N+1`, `2N`) |
| `cooling_redundancy` | Cooling redundancy level |
| `standby_power_redundancy` | Generator / standby power redundancy |
| `tier_design` | Uptime Institute Tier design level (I–IV) |
| `iso27001` | ISO 27001 certification (`Yes` / `No` / blank if unknown) |
| `iso22301` | ISO 22301 certification |
| `soc2` | SOC 2 certification |
| `mantrap_entry` | Mantrap / airlock entry present |
| `cctv` | CCTV surveillance present |
| `biometric_access` | Biometric access control present |
| `card_access` | Card-based access control present |
| `fire_suppression` | Fire suppression system present |
| `onsite_security_staff` | Onsite security staffing (e.g. `Yes, 24/7`) |
| `onsite_technical_staff` | Onsite technical staffing |
| `construction_type` | Building type (e.g. `Purpose-built`, `Converted`) |
| `meet_me_room` | Meet-me room available |
| `office_space` | Customer office space available |
| `ixp_count` | Number of internet exchange points accessible |
| `network_providers` | Number of network providers present |
| `url` | Source URL (e.g. datacentermap.com listing) |

## Contributing

Contributions are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md) for how to add or update entries, and [SOURCES.md](SOURCES.md) for the list of sources used to build and maintain the dataset.

## License

The data is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt it for any purpose, provided you give appropriate credit.
