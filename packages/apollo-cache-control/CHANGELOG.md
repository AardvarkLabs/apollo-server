# Changelog

### v0.1.1

* Fix `defaultMaxAge` feature (introduced in 0.1.0) so that `maxAge: 0` overrides the default, as previously documented.

### v0.1.0

* **New feature**: New `defaultMaxAge` constructor option. (`apollo-server-*` will be updated to allow you to pass constructor options to the extension.)


### v0.0.10

* Update peer dependencies to support `graphql@0.13`.
* Expose `context.cacheControl.cacheHint` to resolvers.

(Older versions exist but have no CHANGELOG entries.)
