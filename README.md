# Couch Community Compat Table

Many Couch-esque clients and servers claim to be "CouchDB" compatible. But compatibility is a fuzzy thing.

The point of this table is to cut through the BS and make an honest assessment of how we're doing as a community to interop with each other.

Please open a pull request to add your own sync pair.

## Servers

* CouchDB 1.x
* CouchDB 2.x
* Couchbase Sync Gateway (CSG)
* Cloudant
* rcouch
* PouchDB Server

## Clients

* PouchDB
* Couchbase Lite Android
* Couchbase Lite iOS
* Cloudant Sync Android
* Cloudant Sync iOS

Click the &#10003;, &#10007;, or ? to see notes.

| &nbsp; | CouchDB 1.x | CouchDB 2.x | CSG | Cloudant | rcouch | PouchDB Server |
| --- | --- | --- | --- | --- | --- | --- |
| *PouchDB* | [&#10003;](#pouchdb--couchdb-1x) | [&#10003;](#pouchdb--couchdb-2x) | [&#10007;](#pouchdb--couchbase-sync-gateway) | [?](#pouchdb--cloudant) | [?](#pouchdb--rcouch) | [&#10003;](#pouchdb--pouchdb-server)
| *Couchbase Lite Android* | [?](#couchbase-lite-android--couchdb-1x) | [?](#couchbase-lite-android--couchdb-2x) | [?](#couchbase-lite-android--couchbase-sync-gateway) | [?](#couchbase-lite-android--cloudant) | [?](#couchbase-lite-android--rcouch) | [?](#couchbase-lite-android--pouchdb-server) |

## Notes

### PouchDB &#8596; CouchDB 1.x

Fully tested in the [PouchDB test suite](https://travis-ci.org/pouchdb/pouchdb).

### PouchDB &#8596; CouchDB 2.x

Fully tested in the [PouchDB test suite](https://travis-ci.org/pouchdb/pouchdb).

### PouchDB &#8596; Couchbase Sync Gateway

Untested, [many known issues](https://github.com/pouchdb/pouchdb/issues/3490). In particular, attachments are not replicated due to PouchDB not supporting the `multipart/mixed` style and CSG not supporting the older JSON style.

### PouchDB &#8596; Cloudant

Mostly works, but there may be issues. PouchDB is tested against CouchDB 2.x, which is largely compatible with Cloudant. No big known issues.

### PouchDB &#8596; rcouch

Untested.

### PouchDB &#8596; PouchDB Server

Fully tested in the [PouchDB test suite](https://travis-ci.org/pouchdb/pouchdb).


### Couchbase Lite Android &#8596; CouchDB 1.x

Your info here

### Couchbase Lite Android &#8596; CouchDB 2.x

Your info here

### Couchbase Lite Android &#8596; Couchbase Sync Gateway

Your info here

### Couchbase Lite Android &#8596; Cloudant

Your info here

### Couchbase Lite Android &#8596; rcouch

Your info here

### Couchbase Lite Android &#8596; PouchDB Server

Your info here

