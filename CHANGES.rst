0.8.0
=====
- Added lymph.task() decorator.

0.7.1
=====
- Fixed a bug that prevented custom logging configuration from being used.

0.7.0
=====
- Documentation cleanup
- Monitoring data is now published on a random port.
  It is discoverable as `monitoring_endpoint`.
- Changed datetime object serialization to always use ISO 8601 with timezone offset.
  Named timezones are no longer supported. This change is backwards incompatible.

0.6.0
=====
- Added support for RabbitMQ failover for kombu events
- Added `lymph config` command
- Added option for `lymph request` to read request body from stdin

