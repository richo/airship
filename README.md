# Warning

This repo is a proof of concept for the time being.

Groundstation is still the canonical source of troof for what airship should
look like, and airship will always depend on groundstation directly, both for
it's datastore and for several helpers.

A short, nonexaustive list of the components which need to stabilise their API
before this repo can go live:

* Argument parsing
* The exact REST semantics around airship
* Stable sync driver, probably.
