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

**[VaccinateCA](http://web.archive.org/web/20210721042855/https://www.vaccinateca.com/) (🚫 Retired)** lists sites with and without available vaccines by region and county, and zip code.
- Data source: Manual volunteer legwork and phone banking.
- Developed by: [Ad-hoc community group](https://www.vaccinateca.com/about-us)
- Social Media: [Twitter @ca_covid](https://twitter.com/ca_covid)
- Source Repo: -
- Original URL: https://www.vaccinateca.com/


### Illinois

**[ILVaccine](http://web.archive.org/web/20211204124817/https://www.ilvaccine.org/) (🚫 Retired)** lists locations, eligibility and availablity for the COVID-19 vaccine across Illinois.
- Data source: A combination of scraping and manual updates by volunteers.
- Social Media: [Twitter @ILVaccine](https://twitter.com/ILVaccine)
- Source Repo: -
- Original URL: https://www.ilvaccine.org/


### Indiana

**[IndyVax](http://web.archive.org/web/20211204171733/https://storage.googleapis.com/indyvax.com/index.html) (🚫 Retired)** lists sites with available appointments in the near future across the entire state.
- Data source: Scraping the [state appointment portal](https://vaccine.coronavirus.in.gov/).
- Developed by: [A shy individual](mailto:contact@indyvax.com)
- Original URL: https://indyvax.com/


### Massachusetts

**[VaccinateMA](http://web.archive.org/web/20210803034612/https://vaccinatema.com/) (🚫 Retired)** lists sites with available vaccines and allows filtering by zip code.
- Data source: Manual volunteer legwork and phone banking.
- Developed by: [Ad-hoc community group](https://vaccinatema.com/FAQ)
- Social Media: -
- Source Repo: https://github.com/codeforboston/vaccinatema
- Original URL: https://vaccinatema.com/

**[MA Covid Vaccine Appointments](http://web.archive.org/web/20211208230543/https://www.macovidvaccines.com/) (🚫 Retired)** lists appointment availability in Massachussetts.
- Data source: Scraping (both gov and private web sites)
- Developed by: [Olivia Adams](https://www.oliviaadams.dev/)
- Source Repo:
    - Web site: https://github.com/livgust/macovidvaccines.com
    - Scrapers: https://github.com/livgust/covid-vaccine-scrapers
- Social Media: -
- Original URL: https://www.macovidvaccines.com/


### New Jersey

**[VaccinateNJ](http://web.archive.org/web/20210901215103/https://vaccinatenj.com/) (🚫 Retired)** shows a spreadsheet of what clinics have vaccines are available.
- Data source: Manual volunteer legwork and phone banking.
- Developed by: [Ad-hoc community group](https://vaccinatenj.com/FAQ)
- Social Media: [Twitter @nj_covid](https://twitter.com/nj_covid)
- Source Repo: https://github.com/LWprogramming/COVID-19-Vaccine-Eligibility-Explainer-NJ
- Original URL: https://vaccinatenj.com/


### New York

**[TurboVax](http://web.archive.org/web/20211210140207/https://www.turbovax.info/) (🚫 Retired)** lists sites and availablity in **New York City**.
- Data source: Scraping NYC Vaccine Hub, NYC Health & Hospitals, NYS Vaccination Centers
- Developed by: [Huge Ma](https://hugema.com)
- Social Media: [Twitter @turbovax](https://twitter.com/turbovax)
- Source Repo: -
- Original URL: https://www.turbovax.info/

**[NYC Vaccine List](http://web.archive.org/web/20211210215540/https://nycvaccinelist.com/) (🚫 Retired)** covers **New York City**.
- Data source: Scraping (no full list published, but at least includes New York State Department of Health, Vaccinepod, and Statcare) and *possibly* phone banking (but needs confirmation).
- Developed by: [Ad-hoc community group](https://nycvaccinelist.com/about)
- Social Media: [Twitter @ny_covid](https://twitter.com/ny_covid)
- Source Repo: -
- Original URL: https://nycvaccinelist.com/

**[NYC Health COVID-19 vaccine appointment availability](http://web.archive.org/web/20221122180741/https://paulschreiber.github.io/nyc-vaccine-appointments/) (🚫 Retired)** charts out availability over time in **New York City**.
- Data Source: Scraping Vaccinepod
- Source Repo: https://github.com/paulschreiber/nyc-vaccine-appointments/
- Social Media: -
- Original URL: https://paulschreiber.github.io/nyc-vaccine-appointments/


### Texas

**[Covid 19 Vaccine TX](http://web.archive.org/web/20210303222330/https://www.covid19vaccinetx.com/) (🚫 Retired)** lists sites and appointment availability or waitlist availability throughout Texas. It also includes notifications and crowdsourced information about vaccination experiences at individual locations.
- Data Source: Crowdsourced
- Developed by: [Carri Craver](https://github.com/carricraver)
- Source Repo: -
- Social Media: -
- Original URL: https://www.covid19vaccinetx.com/


### Washington State

**[CovidWA](https://www.covidwa.com/)** lists sites with and without availability across the entire state.
- Data Source: A bevy of scrapers
- Developed by: A bunch of volunteers
- Social Media: https://www.facebook.com/WACovidVaccineFinder


## General Projects

**[COVID-19 Vaccine Tracker](http://web.archive.org/web/20221122174948/https://github.com/jwoglom/covid19-vaccine-tracker) (🚫 Retired)** is a self-hosted, configurable system for sending notifications when there are vaccine sign-up slots available. It contains several backends which get data from public vaccination sign-up websites, primarily in the Massachusetts area, but is also extensible and can be configured to scrape any website.
- Data Source: Scraping (currently supports Curative, RxTouch, CVS Pharmacy, and MAImmunizations websites)
- Developed By: [James Woglom](https://github.com/jwoglom)
- Source Repo: https://github.com/jwoglom/covid19-vaccine-tracker

**[VacFind](http://web.archive.org/web/20220128170136/https://vacfind.github.io/VacFind-site/) (🚫 Retired)** is working to create an open, nationwide database of COVID-19 Vaccine availability data, build an open-source user-friendly portal to allow easy access, and bring together a community of developers working on COVID response projects to facilitate resource sharing and improve efficiency and project re-use.
- Data Sources: scraping, aggregating already-scraped results from other sites, [GISCorps vaccination site data](https://covid-19-giscorps.hub.arcgis.com/) from [https://findcovidtesting.com/](https://findcovidtesting.com/).
- Source Repo: https://github.com/VacFind
- Original URL: https://vacfind.org


## Thanks and Inspiration

This project is inspired by others who have led the way:

- [@vykster](https://github.com/vykster)’s [Civic Tech Events List](https://github.com/compilerla/civic-tech-events)
- [@codeforamerica](https://github.com/codeforamerica)’s [Civic Tech Patterns](https://github.com/codeforamerica/civic-tech-patterns)
- [Awesome Lists](https://github.com/topics/awesome-lists)


## License

This is an information directory for all to use, and is published in the public domain. See the [`LICENSE` file](./LICENSE) for details.
