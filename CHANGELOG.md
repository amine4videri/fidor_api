# Changelog

## v2.0.6

* Support for Standing Orders
* Allow injection of custom headers for Generic Transfers
* Support endpoints with path prefix
* Support for Confirmable v2 on Generic Transfers

## v2.0.5

* Add `instant` flag to `FPS` routing-type in generic-transfer model

## v2.0.4

* Add `FOS_P2P_ACCOUNT_NUMBER` routing-type to generic-transfer model
* Add DSL to fetch transactions for specific account
* Add `instant` flag to `SEPA` routing-type in generic-transfer model

## v2.0.3

* Add support for `bank_*` and `contact_*` attributes in generic-transfer model
* Add `state` attribute to generic-transfer model

## v2.0.2

* Allow passing custom `headers` to internal `update` DSL method

## v2.0.1

* Support for seperate URL used by oAuth2 redirect flow
* Fix handling of empty `Location` header for confirmable actions

## v2.0.0

* Complete rewrite of the gem
* Switched (back) to
* Fixed design issue regarding concurrency / thread safety

---

## v1.x.x

See changelog in `v1` branch.

## v0.x.x

See changelog in `v1` branch.
