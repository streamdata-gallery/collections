---
swagger: "2.0"
x-collection-name: eMuseum API docs
x-complete: 1
info:
  title: eMuseum API
  description: developed-in-partnership-with-museums-the-museum-system-makes-capturing-managing-and-accessing-collection-information-quick-and-easy-emuseum-is-a-webbased-software-program-that-integrates-seamlessly-with-tms-and-other-collection-management-systems-to-dynamically-publish-information-to-your-website-intranet-and-kiosks-this-api-delivers-search-information-and-images-from-tms--emuseum-to-gsagov
  version: 1.0.0
host: gsafinearts.pbs.gsa.gov
basePath: /emuseum/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /collections/all:
    get:
      summary: Collections
      description: Get Collections
      operationId: getCollections
      x-api-path-slug: collectionsall-get
      responses:
        200:
          description: OK
      tags:
      - Collections
  /collections/{id}:
    get:
      summary: Collections
      description: Get Collection
      operationId: getCollection
      x-api-path-slug: collectionsid-get
      responses:
        200:
          description: OK
      tags:
      - Collections
---