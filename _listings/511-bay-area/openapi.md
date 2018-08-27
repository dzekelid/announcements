swagger: "2.0"
x-collection-name: 511 Bay Area
x-complete: 1
info:
  title: San Francisco 511
  description: open511-aims-to-create-simple-uniform-and-resource-driven-apis-that-can-be-easily-used-by-consumers-to-retrieve-data-from-511-org--using-the-new-api-is-designed-to-be-as-simple-as-possible-and-is-available-to-all--users-of-the-api-are-required-to-obtain-access-tokens-and-must-send-those-tokens-as-part-of-their-request-
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: api.511.org
basePath: /transit
paths:
  /GeneralAnnouncements:
    get:
      summary: San Francisco 511 General Announcements API
      description: San francisco 511 general announcements api.
      operationId: GeneralAnnouncementsGet
      x-api-path-slug: generalannouncements-get
      parameters:
      - in: query
        name: api_key
      responses:
        200:
          description: OK
      tags:
      - "511"
      - San
      - Francisco
      - "511"
      - General
      - Announcements
      - API