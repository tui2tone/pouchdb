[PouchDB](https://pouchdb.com/) – The Database that Syncs!
=========

[![Build Status](https://travis-ci.org/pouchdb/pouchdb.svg)](https://travis-ci.org/pouchdb/pouchdb) [![Coverage Status](https://s3.amazonaws.com/assets.coveralls.io/badges/coveralls_100.svg)](https://coveralls.io/github/pouchdb/pouchdb?branch=master) [![Greenkeeper badge](https://badges.greenkeeper.io/pouchdb/pouchdb.svg)](https://greenkeeper.io/) [![npm version](https://img.shields.io/npm/v/pouchdb.svg)](https://www.npmjs.com/package/pouchdb) [![jsDelivr Hits](https://data.jsdelivr.com/v1/package/npm/pouchdb/badge?style=rounded)](https://www.jsdelivr.com/package/npm/pouchdb)

PouchDB is an open-source JavaScript database inspired by [Apache CouchDB](http://couchdb.apache.org/) that is designed to run well within the browser.

PouchDB was created to help web developers build applications that work as well offline as they do online.

Using PouchDB
-------------

To get started using PouchDB, check out the [web site](https://pouchdb.com) and [API documentation](https://pouchdb.com/api.html).

Getting Help
------------

The PouchDB community is active [on Libera IRC](ircs://irc.libera.chat:6697) [(web)](https://web.libera.chat/#pouchdb), in [the Google Groups mailing list](https://groups.google.com/forum/#!forum/pouchdb), and [on StackOverflow](http://stackoverflow.com/questions/tagged/pouchdb). Or you can [tweet @pouchdb](http://twitter.com/pouchdb)!

If you think you've found a bug in PouchDB, please write a reproducible test case and file [a Github issue](https://github.com/pouchdb/pouchdb/issues). You can start with a [template we have built on glitch](https://glitch.com/~pouchdb-bug-helper).

Prerelease builds
----

If you like to live on the bleeding edge, you can build PouchDB from source using these steps:

    git clone https://github.com/pouchdb/pouchdb.git
    cd pouchdb
    npm install

After running these steps, the browser build can be found in `packages/node_modules/pouchdb/dist/pouchdb.js`.

Changelog
----

PouchDB follows [semantic versioning](http://semver.org/). To see a changelog with all PouchDB releases, check out the [Github releases page](https://github.com/pouchdb/pouchdb/releases).

For a concise list of breaking changes, there's the [wiki list of breaking changes](https://github.com/pouchdb/pouchdb/wiki/Breaking-changes).

Keep in mind that PouchDB is auto-migrating, so a database created in 1.0.0 will still work if you open it in 4.0.0+. Any release containing a migration is clearly marked in the release notes.

Contributing
------------

We're always looking for new contributors! If you'd like to try your hand at writing code, writing documentation, designing the website, writing a blog post, or answering [questions on StackOverflow](http://stackoverflow.com/search?tab=newest&q=pouchdb), then we'd love to have your input.

If you have a pull request that you'd like to submit, please read the [contributing guide](https://github.com/pouchdb/pouchdb/blob/master/CONTRIBUTING.md) for info on style, commit message format, and other (slightly!) nitpicky things like that. PouchDB is heavily tested, so you'll also want to check out the [testing guide](https://github.com/pouchdb/pouchdb/blob/master/TESTING.md).
