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
- Data source: The state’s PrepMod system and Anchorage's Visit Health vaccine provider via JSON endpoint.
- Developed by: [Muncipality of Anchorage’s Innovation Team](https://medium.com/anchorage-i-team/about-us-574f8ac4d839)
- Source repo: https://github.com/MunicipalityOfAnchorage/prepmod-scrape
- Social Media: [Twitter @ANCInnovation](https://twitter.com/ANCInnovation)


### California

**[VaccinateCA](https://www.vaccinateca.com/)** lists sites with and without available vaccines by region and county, and zip code.
- Data source: Manual volunteer legwork and phone banking.
- Developed by: [Ad-hoc community group](https://www.vaccinateca.com/about-us)
- Social Media: [Twitter @ca_covid](https://twitter.com/ca_covid)
- Source Repo: -


### Illinois

**[ILVaccine](https://www.ilvaccine.org)** lists location, eligibility and availablity for the COVID-19 vaccine in the Chicagoland area.
- Data source: A combination of scraping and manual updates by volunteers.
- Social Media: [Twitter @ILVaccine](https://twitter.com/ILVaccine)
- Source Repo: -


### Indiana

**[IndyVax](https://indyvax.com/)** lists sites with available appointments in the near future across the entire state.
- Data source: Scraping the [state appointment portal](https://vaccine.coronavirus.in.gov/).
- Developed by: [A shy individual](mailto:contact@indyvax.com)


### Massachusetts

**[VaccinateMA](https://vaccinatema.com/)** lists sites with available vaccines and allows filtering by zip code.
- Data source: Manual volunteer legwork and phone banking.
- Developed by: [Ad-hoc community group](https://vaccinatema.com/FAQ)
- Social Media: -
- Source Repo: https://github.com/codeforboston/vaccinatema

**[MA Covid Vaccine Appointments](https://www.macovidvaccines.com/)** lists appointment availability in Massachussetts.
- Data source: Scraping (both gov and private web sites)
- Developed by: [Olivia Adams](https://www.oliviaadams.dev/)
- Source Repo:
    - Web site: https://github.com/livgust/macovidvaccines.com
    - Scrapers: https://github.com/livgust/covid-vaccine-scrapers
- Social Media: -


### New Jersey

**[VaccinateNJ](https://vaccinatenj.com/)** shows a spreadsheet of what clinics have vaccines are available.
- Data source: Manual volunteer legwork and phone banking.
- Developed by: [Ad-hoc community group](https://vaccinatenj.com/FAQ)
- Social Media: [Twitter @nj_covid](https://twitter.com/nj_covid)
- Source Repo: https://github.com/LWprogramming/COVID-19-Vaccine-Eligibility-Explainer-NJ


### New York

**[TurboVax](https://www.turbovax.info/)** lists sites and availablity in **New York City**.
- Data source: Scraping NYC Vaccine Hub, NYC Health & Hospitals, NYS Vaccination Centers
- Developed by: [Huge Ma](https://hugema.com)
- Social Media: [Twitter @turbovax](https://twitter.com/turbovax)
- Source Repo: -

**[NYC Vaccine List](https://nycvaccinelist.com/)** covers **New York City**.
- Data source: Scraping (no full list published, but at least includes New York State Department of Health, Vaccinepod, and Statcare) and *possibly* phone banking (but needs confirmation).
- Developed by: [Ad-hoc community group](https://nycvaccinelist.com/about)
- Social Media: [Twitter @ny_covid](https://twitter.com/ny_covid)
- Source Repo: -

**[NYC Health COVID-19 vaccine appointment availability](https://paulschreiber.github.io/nyc-vaccine-appointments/)** charts out availability over time in **New York City**.
- Data Source: Scraping Vaccinepod
- Source Repo: https://github.com/paulschreiber/nyc-vaccine-appointments/
- Social Media: -


### Texas

**[Covid 19 Vaccine TX](https://www.covid19vaccinetx.com/)** lists sites and appointment availability or waitlist availability throughout Texas. It also includes notifications and crowdsourced information about vaccination experiences at individual locations.
- Data Source: Crowdsourced
- Developed by: [Carri Craver](https://github.com/carricraver)
- Source Repo: -
- Social Media: -


### Washington State

**[CovidWA](https://www.covidwa.com/)** lists sites with and without availability across the entire state.
- Data Source: A bevy of scrapers
- Developed by: A bunch of volunteers
- Social Media: https://www.facebook.com/WACovidVaccineFinder


## General Projects

**[COVID-19 Vaccine Tracker](https://github.com/jwoglom/covid19-vaccine-tracker)** is a self-hosted, configurable system for sending notifications when there are vaccine sign-up slots available. It contains several backends which get data from public vaccination sign-up websites, primarily in the Massachusetts area, but is also extensible and can be configured to scrape any website.
- Data Source: Scraping (currently supports Curative, RxTouch, CVS Pharmacy, and MAImmunizations websites)
- Developed By: [James Woglom](https://github.com/jwoglom)
- Source Repo: https://github.com/jwoglom/covid19-vaccine-tracker

**[VacFind](https://vacfind.org)** is working to create an open, nationwide database of COVID-19 Vaccine availability data, build an open-source user-friendly portal to allow easy access, and bring together a community of developers working on COVID response projects to facilitate resource sharing and improve efficiency and project re-use.
- Data Sources: scraping, aggregating already-scraped results from other sites, [GISCorps vaccination site data](https://covid-19-giscorps.hub.arcgis.com/) from [https://findcovidtesting.com/](https://findcovidtesting.com/).
- Source Repo: https://github.com/VacFind


## Thanks and Inspiration

This project is inspired by others who have led the way:

- [@vykster](https://github.com/vykster)’s [Civic Tech Events List](https://github.com/compilerla/civic-tech-events)
- [@codeforamerica](https://github.com/codeforamerica)’s [Civic Tech Patterns](https://github.com/codeforamerica/civic-tech-patterns)
- [Awesome Lists](https://github.com/topics/awesome-lists)


## License

This is an information directory for all to use, and is published in the public domain. See the [`LICENSE` file](./LICENSE) for details.
