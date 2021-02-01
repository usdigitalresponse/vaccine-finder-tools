# COVID-19 Vaccine Finder Tools

This is a list of community projects designed to help people find available COVID-19 vaccines and get appointments. Because vaccination is handled differently and implemented by different organizations across the U.S., it can be hard for people get a clear sense of where they can get vaccinated and where to sign up; these projects aim to fill that gap.

Our goals here are to:

1. Help people find good tools to get appointments.

2. Get technologists working together and collaborating on these tools (or just sharing patterns) where possible. Ideally we can have as few tools in any given geographic area as possible to reduce load on official services.

3. Identify common patterns or needs we can encourage public health officials and government technologists to support. Could their sites take cues from community projects? Could they implement markup patterns on pages or simple APIs that reduce their servers’ load and make their data easier to scrape or parse?

**If you know of a project that’s not listed or have built one yourself, please file a PR to add it to the list!**


## Projects by State

### Alaska

**[anchoragecovidvaccine.org](https://anchoragecovidvaccine.org/)** lists available appointments in Alaska.
- Data source: The state’s PrepMod system.
- Developed by: [Muncipality of Anchorage’s Innovation Team](https://medium.com/anchorage-i-team/about-us-574f8ac4d839)
- Source repo: https://github.com/MunicipalityOfAnchorage/prepmod-scrape
- Social Media: -


### California

**[VaccinateCA](https://www.vaccinateca.com/)** lists sites with and without available vaccines by region and county, and zip code.
- Data source: Manual volunteer legwork and phone banking.
- Developed by: [Ad-hoc community group](https://www.vaccinateca.com/about-us)
- Social Media: [Twitter @ca_covid](https://twitter.com/ca_covid)


### Massachusetts

**[VaccinateMA](https://vaccinatema.com/)** lists sites with available vaccines and allows filtering by zip code.
- Data source: Manual volunteer legwork and phone banking.
- Developed by: [Ad-hoc community group](https://vaccinatema.com/FAQ)
- Social Media: -
- Source Repo: https://github.com/codeforboston/vaccinatema


### New York

**[TurboVax](https://www.turbovax.info/)** lists sites and availablity in **New York City**.
- Data source: Scraping NYC Vaccine Hub, NYC Health & Hospitals, NYS Vaccination Centers
- Developed by: [Huge Ma](https://hugema.com)
- Social Media: [Twitter @turbovax](https://twitter.com/turbovax)

**[NYC Vaccine List](https://nycvaccinelist.com/)** lists covers **New York City**.
- Data source: Scraping (no full list published, but at least includes New York State Department of Health, Vaccinepod, and Statcare) and *possibly* phone banking (but needs confirmation).
- Developed by: [Ad-hoc community group](https://nycvaccinelist.com/about)
- Social Media: [Twitter @ny_covid](https://twitter.com/ny_covid)

**[NYC Health COVID-19 vaccine appointment availability](https://paulschreiber.github.io/nyc-vaccine-appointments/)** charts out availability over time in **New York City**.
- Data Source: Scraping Vaccinepod
- Source Repo: https://github.com/paulschreiber/nyc-vaccine-appointments/
- Social Media: -


## Thanks and Inspiration

This project is inspired by others who have led the way:

- @vykster’s [Civic Tech Events List](https://github.com/compilerla/civic-tech-events)
- @codeforamerica’s [Civic Tech Patterns](https://github.com/codeforamerica/civic-tech-patterns)
- [Awesome Lists](https://github.com/topics/awesome-lists)


## License

This is an information directory for all to use, and is published in the public domain. See the [`LICENSE` file](./LICENSE) for details.
