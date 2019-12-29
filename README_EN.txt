* README_EN.txt
* 2018.03.31
* googletest

1. DESCRIPTION
2. LICENSE
3. AUTHOR EMAIL

-------------------------------------------------------------------------------
1. DESCRIPTION
-------------------------------------------------------------------------------
googletest patched sources fork from:
https://github.com/google/googletest

Based on version 1.8.1.

From authors:

  We are working on a large refactoring that would make it hard to accept
  external PRs. Really Soon Now we will not be accepting new PRs until the
  refactoring has been completed.

  Future Plans:

  * 1.8.x Release - the 1.8.x is the last release that works with pre-C++11
    compilers. The 1.8.x will not accept any requests for any new features and
    any bugfix requests will only be accepted if proven "critical"
  * Post 1.8.x - work to improve/cleanup/pay technical debt. When this work is
    completed there will be a 1.9.x tagged release
  * Post 1.9.x googletest will follow `Abseil Live at Head philosophy`

  This repository is a merger of the formerly separate GoogleTest and
  GoogleMock projects. These were so closely related that it makes sense to
  maintain and release them together.

  Features
    * An xUnit test framework.
    * Test discovery.
    * A rich set of assertions.
    * User-defined assertions.
    * Death tests.
    * Fatal and non-fatal failures.
    * Value-parameterized tests.
    * Type-parameterized tests.
    * Various options for running the tests.
    * XML test report generation.

  Platforms
  Google test has been used on a variety of platforms:

    * Linux
    * Mac OS X
    * Windows
    * Cygwin
    * MinGW
    * Windows Mobile
    * Symbian
    * PlatformIO

The original library patched to fix these issues:

1. Ability to add test case predicate functions to be called at print results
   phase (currently only fail results printing has implemented).

-------------------------------------------------------------------------------
2. LICENSE
-------------------------------------------------------------------------------
The MIT license (see included text file "license.txt" or
https://github.com/google/googletest/blob/master/LICENSE ) 

-------------------------------------------------------------------------------
3. AUTHOR EMAIL
-------------------------------------------------------------------------------
Andrey Dibrov (andry at inbox dot ru)
