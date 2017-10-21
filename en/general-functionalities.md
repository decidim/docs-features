# 5	General functionalities 

Below, we will outline a series of the platform’s general functions and features which do not appear in the spaces or components, or in the functions directly associated with participants.

## 5.1	Installation and settings

Decidim **can be easily installed **using the command prompt in any GNU/Linux server with the following installed services: PostgreSQL 9.4+, Ruby 2.4.1, NodeJS with yarn (JavaScript dependency manage), ImageMagick and PhantomJS. An automatic installation script allows you to deploy the whole dependency system, libraries, databases and other automatically required services in Heroku or Docker [function expected for 2018].

The portal’s **settings** are **customisable **in the following fields that are filled out on a form from the administration panel: Name of the portal, social network profiles (Twitter, Facebook, Instagram, YouTube, Github); brief description; welcome text; default language; home image; the organisation’s logo; favicon, reference prefix (unique identifier that will apply to the portal’s elements) and the organisation’s URL.

## 5.2	Integration with other services and compatibility/creation of additional services

Decidim can be easily integrated with the following services that can be installed or configured with Decidim:

* **OpenStreetMap**: to show events and proposals with geo-location

* **Piwik**: website traffic analysis

* **Pad**: collaborative real-time writing boards (technology to be determined) [Function expected for 2018Q1-3 AjB-Lote1]

* **Digital identity and signature**: integration with OAuth2 digital-identity management system, systems based on blockchain and recognised institutional digital identity and signature management systems [Function expected for 2018Q1-3 AjB-Lote1].

* **Distributed filing system**: Disseminating or copying proposals or other elements from the platform in a distributed filing system (blockchain or IPFS type) [Function expected for 2018Q1-3, AjB-Lote1].

* **Microblogging**: integration/compatibility with a standardised and open GNU Social or StatusNet type microblogging protocol/service for participants’ activities (proposals, observations and messages) [Function expected for 2018Q1-3, AjB-Lote1].

Decidim automatically generates the following services besides the ones that can be browsed on the website or accessed through an API: 

* **SMTP**: sending emails.

* **Calendar**: integration and compatibility with calendar-management systems and automatic creation and updating of events calendars, etc. [Function expected for 2018Q1-3, AjB-Lote1].

## 5.3	Multitenancy 

The multitenancy of the platform** **can be used on the basis of a single installation. In other words, a single installation of Decidim allows you to deploy as many portals as you want under specific settings for each of the levels. That way an organisation can create participatory portals for its sub-organisations or various organisations can share a server and reduce the maintenance costs of its portals.

## 5.4	Multi-language

Decidim is a **multi-language** platform. Its available languages will be configured during its installation. Menus, administrative forms and, generally, the platform's fixed texts are available in several languages (Spanish, Catalan, Basque, Italian, French, Dutch and Finnish). A **collaborative translation **system in [https://crowdin.com/project/decidim](https://crowdin.com/project/decidim) enables new languages to be incorporated into the platform. 

As for content, once the official languages of the level have been set during the installation, all the content that is created from the administration panel has the option of being generated in these languages. The administration panel allows **content to be managed in several languages** through tabs. The content generated by users is displayed on the platform in a single language (the one chosen by the participant through the language selector in the upper part of the menus or automatically through its browser's language settings).

## 5.5	Statistics, open data and downloads

Besides the application programming interface (API) which automatically provides access to public data, Decidim’s home page features a **general statistics table** with the following fields: number of participants, processes, proposals, results, meetings, observations and votes.

Another **statistics table for each participatory process** shows the number of meetings, proposals, votes and results of a specific process.

The administration panel lets you **export the proposals, results and observations **of a participatory process in CSV and JSON format and responses to surveys for processing and/or integration with other management systems. Participants can **download the results of a participatory process and the extent of its implementation **through a CSV file.

Decidim also has a **data-display component **at its disposal on the platform’s general level and on a specific level (showing data from a specific Participatory Space ) [function expected for 2018Q1, AjB-Lote2Mod4]. The following are included among the graphics that are displayed:

* **Interactive graphics **in the form of a time line showing the development of the various components’ counters.

* **Heat map** of all the meetings, proposals or other content with geo-location tags.

* **Interactive diagrams **(bar or pie charts) with the results of a process (amounts of each of the participatory budget projects, filter by category and status of the proposals - whether selected or not, etc.)

All of these displays are accompanied by an **option for downloading data **in CSV format [function expected for 2018Q1, AjB-Lote2Mod4]. 

## 5.6	API, adaptable website design and mobile app

Decidim has an application programming interface or API which is a series of independent service calls and data from Decidim's website interface. This allows third parties to develop services on the platform, automatically release data or develop new interfaces, or integrate other services with decidim.

The API comes with **documents** and a **formal participatory ontology** [function expected for 2018Q1-3, AjB-Lote1]

Decidim's website **design** is completely **adaptable** (*responsive*), using *mobile-first* design philosophy (designed first for mobiles and later extended to desktop systems and tablets).

Both the website's design and the API enable the development of mobile apps for Decidim, and a **Mobile App** is expected to be developed for the end of 2018 [AjB].

## 5.7	Content-classification systems

As for content classification, the following to be distinguished and adjusted in Decidim: fields, categories and labels (or tags).

**Fields** are generic throughout the platform and divided up into **territorial** and **topic **types. Territorial areas, once defined, allow the spaces’ elements to be classified by territory (e.g. if a process or a body or an initiative affects a district or two, the entire city, a region or country, depending on the organisation). Topic areas are likewise defined for the entire platform and allow classification of the various elements of the participatory spaces [function expected for 2017Q4, Gencat].

**Categories and subcategories** are used for classifying content within the various spaces and are defined for each of the levels of the spaces. So, for example, a participatory process may include several categories and subcategories (the process administrator defines them) whereas the process’ meetings, surveys, proposals and other components can be classed under these categories.

In contrast to fields and categories, **labels** or tags are cross-cutting and freely defined by participants and can apply to any level or component. Labels can be created, embedded and defined in the administration panel. A label-suggestion system allows the people taking part to choose labels similar to the ones that are they are suggesting for labelling any of the platform's elements. Elements can be browsed by labels and the most popular labels displayed [function expected for 2017Q4, AjB-Lote2Mod1].

## 5.8	Contextual help system, usability and evaluation tests

Decidim includes **editable contextual help** for guiding individual and administrative participants in using the platform. It also includes a system that allows **usability experiments **to be carried out with tests and usage statistics, as well as **automatic evaluation surveys **to be conducted on participants for the purposes of identifying usability and participatory-procedure errors and improving the democratic quality experience of the software [Function expected for 2018Q1-3, AjB-Lote1].

