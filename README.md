# lombre
Experimenting with RSS

* Frontend
  - Nuxt 
* Backend
  - Endpoints
    - /api/sources : Get all the sources the server has
    - /api/news/:source : Get the news from the source
    - /api/news : Get all the news from all the sources
  - Fetches data from the DB that the RSS server also uses
* RSS Server
  - Timer (1 hour?)
  - Download the lastest RSS Feed from a list of servers
  - Process them to a more usable format (JSON)
  - Write them to DB (Redis)
    - Handle duplicates