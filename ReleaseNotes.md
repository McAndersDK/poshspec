# Version 2.2.1

* Added PropertyExpression to `Get-PoshspecParams`
* Support added to Website and AppPool for accessing property values through dot notation.
See [#52](https://github.com/Ticketmaster/poshspec/pull/52) for details. Thanks [Jesse Gigler](https://github.com/jgigler).

# Version 2.1.19

* Expanded functionality for WebSite and AppPool [#49](https://github.com/Ticketmaster/poshspec/pull/49) [#50](https://github.com/Ticketmaster/poshspec/pull/50)

# Version 2.1.16

* Improved handling of single quotes in Package function

# Version 2.1.15

* Improved handling of single quotes  in Package function
* Added Functions for
  * LocalUser
  * AuditPolicy
  * Volume
  * ServerFeature
  * Share
  * UserRightsAssignment

# Version 2.1.6
* Added Functions for
  * Firewall

# Version 2.1.0

* Broke Down PSM1 to Many Different Functions in their own files [No change in functionality]
* Added Functions for
  * CheckSite
  * CheckAppPool
  * WebSite
  * SoftwareProduct


# Version 1.2.2

* Merged PR including 5 new functions
  * Package
  * LocalGroup
  * Interface
  * Folder
  * DnsHost

# Version 1.1.0

* Public release.

# Version 1.0

* Complete refactor to improve unit testing.
* Build unit tests.

# Version 0.3

* Better Help
* A bug fix

# Version 0.2

Reworked all functions.
 * Now using Cmdlet syntax to provider better Parameter handling.
 * Assertions are now defined in the test script for better flexibility.

# Version 0.1

Initial 6 functions