---
title: "HTTP Fetch Search Schema"
description: ""
project: "riak_kv"
project_version: 2.9.9
menu:
  riak_kv-2.9.9:
    name: "Fetch Search Schema"
    identifier: "http_fetch_search_schema"
    weight: 116
    parent: "apis_http"
toc: true
aliases:
  - /riak/2.9.9/dev/references/http/fetch-search-schema
  - /riak/kv/2.9.9/dev/references/http/fetch-search-schema
---

Retrieves a Riak KV [search schema]({{<baseurl>}}riak/kv/2.9.9/developing/usage/search-schemas).

## Request

```
GET /search/schema/<schema_name>
```

## Normal Response Codes

* `200 OK`

## Typical Error Codes

* `404 Object Not Found`
* `503 Service Unavailable`
  - /riak/latest/developing/api/http/fetch-search-schema/
  - /riak/kv/latest/developing/api/http/fetch-search-schema/
  - /riakkv/latest/developing/api/http/fetch-search-schema/
---
The request timed out internally

## Response

If the schema is found, Riak will return the contents of the schema as
XML (all Riak Search schemas are XML).



