
0.1.34 / 2014-06-21
==================

 * create model without new keyword

0.1.32 / 2014-04-27
==================

 * fixed pgherveou/modelfactory/issues/4 (make setter work with object and dot notation)
 * update read me

0.1.31 / 2014-04-27
==================

 * fixed pgherveou/modelfactory/issues/6 add mixed types and support Array constructor as type

0.1.29 / 2014-03-05
==================

 * use Object.create(null) instead of {} to initialize schema properties
 * hide private indexes from store

0.1.28 / 2014-01-16
==================

 * update store indexing
 * keep indexes in sync

0.1.25 / 2014-01-06
==================

 * fix type resolution after mangling for non standard types
 * fix test for latest component build

0.1.24 / 2013-12-28
==================

 * add set null scenario

0.1.22 / 2013-11-29
==================

 * add collection method

0.1.21 / 2013-11-26
==================

 * automatically add id key to schema

0.1.20 / 2013-11-26
==================

 * make property  writable

0.1.9 / 2013-11-25
==================

 * fix bug isNew

0.1.8 / 2013-11-09
==================

 * add pick method
 * allow array option in validate

0.1.7 / 2013-11-02
==================

 * add store options

0.1.6 / 2013-10-30
==================

 * add plugins

0.1.5 / 2013-10-30
==================

 * add embedded model, fix schema array defs

0.1.4 / 2013-10-26
==================

  * add schema ppty to model

0.1.3 / 2013-10-17
==================

  * fix proxy array event bug

0.1.2 / 2013-10-17
==================

  * proxy event on array

0.1.1 / 2013-10-17
==================

  * Update Readme.md
  * add parent and parentArray methods on model

0.1.0 / 2013-10-17
==================

  * use modelArray for documentArray
  * refactor model / get / set and event propagation
  * remove backbone deps

0.0.18 / 2013-08-29
==================

  * add test for deeply nested field

0.0.17 / 2013-07-20
==================

  * fixed dummy objectid type

0.0.16 / 2013-07-19
==================

  * add ObjectId alias to String in types

0.0.15 / 2013-07-18
==================

  * use setter when use with key and value
  * add testing node package config

0.0.14 / 2013-07-14
==================

  * add getValue to get raw data

0.0.13 / 2013-07-14
==================

  * return this from set instead of null

0.0.12 / 2013-07-14
==================

  * fix validators context

0.0.11 / 2013-07-14
==================

  * expose Error object

0.0.10 / 2013-07-14
==================

  * fix enum validator bug

0.0.9 / 2013-07-14
==================

  * fix validation bug add string/array format for specific path validation

0.0.8 / 2013-07-14
==================

  * expose Schema.Types

0.0.7 / 2013-07-14
==================

  * use Backbone.Model instead of Backbone in model function

0.0.6 / 2013-07-13
==================

  * support type: [...] and [...] array def in shchema

0.0.5 / 2013-07-13
==================

  * add basic array support

0.0.4 / 2013-07-13
==================

  * add virtual and path getter support
  * add statics and methods

0.0.3 / 2013-07-13
==================

  * use reduce for getPath
  * add virtual support
  * add path get accessor support

0.0.2 / 2013-07-13
==================

  * fix consturctor name creation function
  * update doc
