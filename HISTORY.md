# KJess Changlog

## Version 1.2.0 - 2013-07-08

* Allow for setting a socket factory on the Connection (eric)
* Connections only raise Connection::Error (eric)
* Refactor Error hierarchy [#19]

## Version 1.1.0 - 2013-01-08

* Allow the setting of the kestrel server processes ports for testing (eric)
* Update development dependencies, new version and missing gems
* Re-wrap all network errors with KJess Errors (eric)
* Ensure clients are not shared across fork() (eric)
* Enforce boolean return value from KJess::Client#set (eric)
* Added socket timeout feature (eric)
* Added support for tcp keepalive

## Version 1.0.0 - 2012-10-31

* Initial Release - Yeah!

