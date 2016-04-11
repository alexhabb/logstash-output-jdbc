# Change Log
All notable changes to this project will be documented in this file, from 0.2.0.

## [0.2.4] - 2016-04-11
### Added
  - Basic tests running against DerbyDB
  - Fix for converting Logstash::Timestamp to iso8601 from @hordijk

## [0.2.3] - 2016-04-07
  - Documentation fixes from @hordijk

## [0.2.2] - 2015-12-30
  - Added support for non-autoloading JDBC drivers through

## [0.2.1] -  2015-12-22
  - Support for connection pooling support added through HikariCP
  - Support for unsafe statement handling (allowing dynamic queries)
  - Altered exception handling to now count sequential flushes with exceptions thrown