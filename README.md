XP: RFC README
========================================================================

This document describes the RFC procedure.

What is an RFC?
---------------
RFC stands for Request For Comments, but you knew that:)


When is an RFC needed?
----------------------
An RFC is needed when changes are made that affect one of the following:

* Core functionality (e.g., in `lang.base.php`)
* Classes in the `lang` package or subpackages thereof
* Wherever it affects a lot of places, e.g. `xml.Node`
* When **BC** (backwards compatibility) is broken

Changes include any type of change except for QA work or bug fixes.


Who can write RFCs?
-------------------
Short answer: Anybody. Simply open an issue [here](https://github.com/xp-framework/rfc/issues)


What does an RFC look like?
---------------------------
An RFC is a GitHub issue with a special inline format defined by the 
following template:

```
Scope of Change
==


Rationale
==


Functionality
==


Security considerations
==


Speed impact
==


Dependencies
==


Related documents
==
```
