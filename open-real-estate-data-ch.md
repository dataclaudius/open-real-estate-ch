# Open Real Estate API and Data List in Switzerland

This repository contains a curated list of Open Real Estate APIs, data sources, and PropTech ecosystems available in Switzerland. It aims to provide developers, PropTech companies, real estate professionals, asset managers, and institutional investors with a comprehensive resource for integrating real estate data and services.

## Table of Contents

1. [Public Open Real Estate Data and Ecosystems in Switzerland](#1-public-open-real-estate-data-and-ecosystems-in-switzerland)
2. [Other Relevant Real Estate APIs](#2-other-relevant-real-estate-apis)
3. [Contributing](#3-contributing)
4. [License](#4-license)

## 1. Public Open Real Estate Data and Ecosystems in Switzerland

> **Note:** This list includes APIs and data sources that have publicly available information. Some providers offer APIs on a case-by-case basis or for partners only without public documentation. Many Swiss real estate platforms participate in standardised interfaces such as **SwissRETS** (the Swiss real estate transaction standard) for property listing data exchange.

### 1.1 Federal Open Data Portals

- [opendata.swiss](https://opendata.swiss/) – Central portal for open government data, including hundreds of real-estate, construction, rent, and vacancy datasets.
- [opendata.swiss CKAN API Handbook](https://handbook.opendata.swiss/de/content/nutzen/api-nutzen.html) – Documentation for accessing opendata.swiss metadata via the CKAN API (base URL `https://ckan.opendata.swiss/api/3/action/`).
- [data.bfs.admin.ch](https://www.data.bfs.admin.ch/) – Overview of all BFS-published datasets (tables, machine-readable files, and APIs) across the 21 statistical themes, including theme "09 Construction and housing".
- [BFS PXWEB API](https://www.pxweb.bfs.admin.ch/) – PX-Web API of the Federal Statistical Office for STAT-TAB tables (rents, vacancy rates, building permits, dwellings).
- [LINDAS – Linked Data Service of the Swiss Federal Administration](https://lindas.admin.ch/) – SPARQL endpoint for federal linked open data, including building and territory data.

### 1.2 Building, Dwelling, and Address Registers

- [Federal Register of Buildings and Dwellings (GWR / RegBL / RegEdi)](https://www.bfs.admin.ch/bfs/en/home/registers/federal-register-buildings-dwellings.html) – Official BFS register containing buildings, dwellings, entrances, addresses, construction projects (EGID, EWID, EDID identifiers).
- [housing-stat.ch (GWR portal)](https://www.housing-stat.ch/) – Public GWR portal with online access for authorised users and Level A (public) data.
- [GWR public eCH-0206 XML endpoint](https://madd.bfs.admin.ch/eCH-0206) – Public XML endpoint to retrieve GWR Level A data by EGID (example: `https://madd.bfs.admin.ch/eCH-0206?egid=20`).
- [GWR on opendata.swiss](https://opendata.swiss/de/dataset/eidg-gebaude-und-wohnungsregister-gebaudestatus) – Publicly available GWR Level A data (building status, addresses, geometries).
- [Swiss Official Commune Register](https://www.agvchapp.bfs.admin.ch/) – Register of all Swiss commune names, numbers, and historic mutations.

### 1.3 Cadastre, Land Register, and Geodata

- [swisstopo geo.admin.ch API REST Services](https://api3.geo.admin.ch/services/sdiservices.html) – REST API for federal geodata: identify, search, height, profile, and feature services.
- [geo.admin.ch WMS / WMTS Services](https://www.geo.admin.ch/en/programming-interface-api) – Map and tile services for all federal geodata layers.
- [swisstopo REFRAME REST Web API](https://www.swisstopo.admin.ch/en/rest-api-geoservices-reframe-web) – Free coordinate transformation services between WGS84, LV03 (CH1903), and LV95 (CH1903+).
- [Cadastre.ch – Swiss Cadastral System](https://www.cadastre.ch/) – Official portal for the Swiss cadastral system (official survey, land register, ÖREB/RDPPF cadastre).
- [Cadastre of Public-Law Restrictions on Landownership (ÖREB / RDPPF)](https://opendata.swiss/de/dataset/cadastre-rdppf) – Federal cadastre of public-law restrictions (zoning, building lines, noise levels, groundwater protection).
- [Terravis (SIX)](https://www.six-group.com/en/site/terravis.html) – Inter-cantonal electronic portal for land registers, ÖREB cadastre, cadastral survey, and GWR data (for authorised users; B2B).
- [geocat.ch](https://www.geocat.ch/) – Federal geo-metadata catalogue.

### 1.4 Statistical Atlases and Geostatistics

- [Federal Statistical Office FSO/BFS](https://www.bfs.admin.ch/bfs/en/home.html) – Federal Statistical Office homepage, with all statistical publications and dataset catalogues.
- [Housing in Switzerland (FSO)](https://www.bfs.admin.ch/bfs/en/home/statistics/cross-sectional-topics/housing-switzerland.html) – Cross-sectional dataset on housing stock, rents, energy sources, and housing quality.
- [BFS GEOSTAT](https://www.bfs.admin.ch/bfs/en/home/services/geostat.html) – Federal geostatistical data on buildings, dwellings, households, persons (hectare grid).

### 1.5 Energy and Sustainability

- [GEAK / CECB – Cantonal Building Energy Certificate](https://www.geak.ch/) – Official Swiss energy efficiency certificate (classes A–G) for buildings, with public registry.
- [Minergie](https://www.minergie.ch/) – Swiss standard for sustainable, energy-efficient buildings and certification database.
- [SNBS – Standard Nachhaltiges Bauen Schweiz](https://nnbs.ch/snbs/) – Swiss Sustainable Building Standard.
- [SFOE / BFE – Swiss Federal Office of Energy](https://www.bfe.admin.ch/) – Federal Office of Energy: statistics, geodata, and building-relevant energy datasets.
- [KBOB Plattform Ökobilanzdaten im Baubereich](https://www.kbob.admin.ch/kbob/de/home/themen-leistungen/nachhaltiges-bauen/oekobilanzdaten_baubereich.html) – KBOB life-cycle assessment data (eco-indicators) for construction materials and building systems.

### 1.6 Public Procurement (Construction Tenders)

- [SIMAP.ch](https://www.simap.ch/) – Joint federal/cantonal/communal e-procurement platform for public tenders.
- [SIMAP API Documentation](https://www.simap.ch/api/specifications/changelog.html) – Official SIMAP API for projects, publications, tenders, awards, and code lists (CPV, BKP, NPK).
- [SIMAP MCP Server (Digilac)](https://github.com/Digilac/simap-mcp) – Open-source Model Context Protocol server for AI-driven SIMAP tender search.

### 1.7 Swiss Real Estate Standards and Industry Initiatives

- [SwissRETS API Definition (GitHub)](https://github.com/scout24ch/swissrets-api-definition) – REST API definition co-maintained by Homegate and ImmoScout24 for the SwissRETS import gateway.
- [eCH-0129 Objektwesen](https://www.ech.ch/de/ech/ech-0129) – Swiss e-government standard for the base data model of object/property messaging.
- [eCH-0206 GWR-Daten an Dritte](https://www.ech.ch/de/ech/ech-0206) – Swiss e-government standard for GWR data access (basis for the public madd endpoint).
- [eCH Fachgruppe Objektwesen](https://www.ech.ch/de/der-verein/fachgruppen/objektwesen) – eCH working group for standards in real estate, land register, official survey, building insurance, and valuation.
- [INTERLIS](https://www.interlis.ch/) – Swiss conceptual modelling language and standard for geodata exchange (SN 612031).
- [SIA – Swiss Society of Engineers and Architects](https://www.sia.ch/) – Issuer of SIA norms (e.g. SIA 416 floor areas, SIA 380 energy, SIA 2051 BIM).
- [CRB – Centre for Standardisation in Construction](https://www.crb.ch/) – Maintainer of construction nomenclatures: BKP, eBKP-H, NPK, EKG.
- [Bauen digital Schweiz / buildingSMART Switzerland](https://bauen-digital.ch/) – BIM / openBIM standards and digital construction in Switzerland.
- [KBOB](https://www.kbob.admin.ch/) – Coordination Conference of Construction and Property Bodies of Public Clients.

### 1.8 Industry Associations and Ecosystem

- [SVIT – Schweizerischer Verband der Immobilienwirtschaft](https://svit.ch/) – Umbrella association for Swiss real estate professionals.
- [HEV Schweiz – Hauseigentümerverband](https://www.hev-schweiz.ch/) – Association of Swiss homeowners.
- [Mieterverband – Swiss Tenants' Association](https://www.mieterverband.ch/) – Association of Swiss tenants.
- [SIV – Swiss Association of Real Estate Appraisers](https://siv.ch/)
- [USPI – Union Suisse des Professionnels de l'Immobilier](https://uspi.ch/)
- [Swiss PropTech](https://swissproptech.ch/) – Network for PropTech start-ups and innovation in Swiss real estate.
- [Swiss Circle](https://swisscircle.swiss/) – Network of 250+ Swiss real estate companies, architects, investors, and banks.
- [Swiss Real Estate Institute (SwissREI)](https://www.swissrei.ch/) – Research institute of HWZ and SVIT; publishes the Online-Wohnungsindex (OWI), OHMA, and SRED indices.
- [SRED – Swiss Real Estate Datapool](https://www.sred.ch/) – Datapool of Swiss real estate transactions for academic and applied research.
- [REIDA – Real Estate Investment Data Association](https://www.reida.ch/) – Swiss non-profit benchmarking association; runs the CO₂-Benchmark and transaction database.

### 1.9 Digital Benchmarks

- [pom+ Digital Real Estate Index (DRE-i)](https://www.digitalrealestate.ch) - Swiss PropTech platform, publisher of the Digital Real Estate Index (DRE-i) and host of the Digital Real Estate Summit.

## 2. Other Relevant Real Estate APIs

### 2.1 Property Listing Portals (Marketplaces)

- [Homegate](https://www.homegate.ch/) – Largest Swiss real estate marketplace (SMG Swiss Marketplace Group); imports via SwissRETS.
- [ImmoScout24 Switzerland](https://www.immoscout24.ch/) – Major Swiss real estate portal (SMG); imports via SwissRETS.
- [Flatfox](https://flatfox.ch/) – Free Swiss real estate marketplace with digital rental process; offers ERP/CRM connectors.
- [newhome.ch](https://www.newhome.ch/) – Swiss real estate portal jointly owned by cantonal banks; import interface for ERP/marketing software.
- [Comparis – Real Estate](https://en.comparis.ch/immobilien/marktplatz) – Real estate listings within the Comparis comparison platform.
- [ImmoStreet.ch](https://www.immostreet.ch/) – Real estate portal (SMG Swiss Marketplace Group).
- [acheter-louer.ch](https://www.acheter-louer.ch/) – Romandie-focused real estate portal (SMG).
- [home.ch](https://www.home.ch/) – Swiss rental and ownership portal.
- [alle-immobilien.ch](https://www.alle-immobilien.ch/) – Real estate meta-search.
- [Properstar.ch](https://www.properstar.ch/) – International and Swiss listings with investment-oriented analysis.

### 2.2 Property Valuation and Market Analytics APIs

- [PriceHubble API Documentation](https://docs.pricehubble.com/) – Property valuation, market analytics, ESG, and forecast APIs (Switzerland and 11 countries).
- [IAZI – CIFI Hedonic Valuation](https://www.iazicifi.ch/en/software-solutions/hedonic-valuation/) – Hedonic valuation models for SFH, condos, and MFH, used by most Swiss banks; avai
- [Wüest Partner – Online Services](https://www.wuest.io/) – Online platform for hedonic valuation, transaction price indices, and market data.
- [FPRE – Fahrländer Partner Real Estate](https://en.fpre.ch/marktdaten/api/) – Market data, location analysis, hedonic models, and construction cost service via API.
- [Novalytica](https://novalytica.com/en/real-estate-3/) – Swiss real estate market data, indicators, and forecasts via Excel add-in, API, or MarketAnalyzer.

### 2.3 Mortgage and Financing APIs

- [UBS key4 Developer Portal](https://developer.ubs.com/key4) – Real-time indicative mortgage offer API from multiple Swiss financing providers.
- [UBS Mortgage Offer API](https://developer.ubs.com/custom-product-page/mortgage-offer-api) – API reference for the key4 mortgage offer API.

### 2.4 Property Management Software (ERP) APIs

- [GARAIO REM](https://www.garaio-rem.ch/) – Modern web-based property management software with documented interfaces (CRM, accounting, portfolio, workflow).
- [immopac](https://www.immopac.ch/en) – Cloud-based platform for direct/indirect real estate investment management and valuation.
- [Abacus AbaImmo / AbaRealEstate](https://www.abacus.ch/en/industry-solutions/real-estate/property-management/overview) – Integrated Swiss property management module within the Abacus ERP suite.
- [W&W Immo Informatik – ImmoTop2 / Rimo R5](https://www.wwimmo.ch/) – Established Swiss property management software for small to large administrations.
- [Fairwalter](https://www.fairwalter.com/) – Cloud-based property management for private landlords and small administrations (W&W subsidiary).
- [emonitor / MiMo](https://emonitor.ch/) – Digital rental application and tenant selection; API for ERP and marketing platforms.
- [imofix.io](https://imofix.io/) – Digital tenant request and order management (partnered with GARAIO REM).

### 2.5 Real Estate CRM and Marketing APIs

- [CASASOFT – CASAONE](https://casasoft.ch/) – Real estate CRM and marketing software with portal interfaces (Homegate, ImmoScout24, newhome, Flatfox) and public API/iFrame/WordPress plug-in.
- [Immomig](https://www.immomig.ch/) – Real estate CRM with portal integrations.
- [Publimmo](https://www.publimmo.ch/) – Real estate broker software (Romandie focus).
- [Beyonity Navigator](https://www.beyonity.com/) – 360° building visualisation and marketing ecosystem with CASAONE integration.
- [Backbone](https://www.backbone.ag/) – Real estate visualisation, photography, virtual tours, and virtual staging.

### 2.6 Tenant, Lease, and Rental Deposit APIs

- [Evorest](https://www.evorest.ch/) – Digital rental deposit service with integrations to ImmoTop2, GARAIO REM, AbaImmo, Rimo R5, PROPbase, and emonitor.
- [Flatfox Business](https://flatfox.ch/c/en/business-rent-digitally/) – End-to-end digital rental process platform.
- [CRIF Switzerland](https://www.crif.ch/) – Tenant credit checks and identity verification used in Swiss letting workflows.

### 2.7 Construction Cost, Benchmarking, and Building Data

- [pom+ Digital Real Estate Index](https://www.digitalrealestate.ch/)) – Annual benchmark study on real estate digitalisation in Switzerland.
- [CRB – Construction Standards](https://www.crb.ch/) – Standardised construction cost catalogues used across Swiss construction (BKP, eBKP-H, NPK).

## 3. Contributing

We welcome contributions to this list! If you know of an API, data source, standard, or resource that should be included or have updates to existing entries, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b add-new-entry`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new entry'`)
5. Push to the branch (`git push origin add-new-entry`)
6. Create a new Pull Request

Please ensure your pull request adheres to the following guidelines:

- Use the format: `[Name](link) - Description`
- Make sure the entry is relevant to Open Real Estate data, APIs, or PropTech in Switzerland
- Check your spelling and grammar
- Make sure your text editor is set to remove trailing whitespace

## 4. License

This project is licensed under the Creative Commons licence - see the LICENSE file for details.
