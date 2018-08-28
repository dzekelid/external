---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: Entertainment Express Returns list of all MovieId, Gracenote Id pairs.
  description: Not accessible with a Demo account.  **Special permissions needed**
    for access to this operation.  Contact [Sales](mailto:sales@internetvideoarchive.com).
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ExternalIds/GracenoteMovie:
    get:
      summary: Returns list of all MovieId, Gracenote Id pairs.
      description: Not accessible with a Demo account.  **Special permissions needed**
        for access to this operation.  Contact [Sales](mailto:sales@internetvideoarchive.com).
      operationId: GetGracenoteMovieIds
      x-api-path-slug: externalidsgracenotemovie-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - ExternalIds
      - GracenoteMovie
  /ExternalIds/GracenoteShow:
    get:
      summary: Returns list of all ShowId, Gracenote Id pairs.
      description: Not accessible with a Demo account. **Special permissions needed**
        for access to this operation. Contact [Sales](mailto:sales@internetvideoarchive.com).
      operationId: GetGracenoteShowIds
      x-api-path-slug: externalidsgracenoteshow-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - ExternalIds
      - GracenoteShow
  /ExternalIds/ImdbMovie:
    get:
      summary: Returns list of all MovieId, IMDB Id pairs.
      description: Ingest this ID map to create connections between the objects in
        your existing database with an IMDB ID to the IVA Movie objects.
      operationId: GetImdbMovieIds
      x-api-path-slug: externalidsimdbmovie-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - ExternalIds
      - ImdbMovie
  /ExternalIds/ImdbShow:
    get:
      summary: Returns list of all MovieId, Tmdb Id pairs.
      description: ngest this ID map to create connections between the objects in
        your existing database with an IMDB ID to the IVA Show objects.
      operationId: GetImdbShowIds
      x-api-path-slug: externalidsimdbshow-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - ExternalIds
      - ImdbShow
  /ExternalIds/RoviMovie:
    get:
      summary: Returns list of all MovieId, Tivo Id pairs.
      description: Not accessible with a Demo account. **Special permissions needed**
        for access to this operation. Contact [Sales](mailto:sales@internetvideoarchive.com).
      operationId: GetTivoMovieIds
      x-api-path-slug: externalidsrovimovie-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - ExternalIds
      - RoviMovie
  /ExternalIds/RoviShow:
    get:
      summary: Returns list of all ShowId, Tivo Id pairs.
      description: Not accessible with a Demo account. **Special permissions needed**
        for access to this operation. Contact [Sales](mailto:sales@internetvideoarchive.com).
      operationId: GetTivoShowIds
      x-api-path-slug: externalidsrovishow-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - ExternalIds
      - RoviShow
  /ExternalIds/TmdbMovie:
    get:
      summary: Returns list of all MovieId, Tmdb Id pairs.
      description: Use to link a TMDB ID to an IVA Movie ID.
      operationId: GetTmdbMovieIds
      x-api-path-slug: externalidstmdbmovie-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - ExternalIds
      - TmdbMovie
  /ExternalIds/TmdbShow:
    get:
      summary: Returns list of all ShowId, TMDB Id pairs.
      description: Use to link a TMDB ID to an IVA Show ID.
      operationId: GetTmdbShowIds
      x-api-path-slug: externalidstmdbshow-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - ExternalIds
      - TmdbShow
  /ExternalIds/Webedia:
    get:
      summary: Returns list of all MovieId, Webedia Id pairs.
      description: Not accessible with a Demo account. **Special permissions needed**
        for access to this operation. Contact [Sales](mailto:sales@internetvideoarchive.com).
      operationId: GetWebediaMovieIds
      x-api-path-slug: externalidswebedia-get
      parameters:
      - in: query
        name: Skip
        description: Determines where to start page
      - in: query
        name: Take
        description: Determines the page size
      responses:
        200:
          description: OK
      tags:
      - ExternalIds
      - Webedia
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---