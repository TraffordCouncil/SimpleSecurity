SimpleSecurity
==============

This project provides a library and reference application for ASP.NET MVC 4 (SimpleMembership) and MVC 5 (ASP.NET Identity) that illustrates:

- How to customize the user profile to include new properties.
- How to enable migrations
- How to seed the database.
- How to decouple the identity provider from the main ASP.NET MVC project providing a layered approach that hides the storage mechanism from the models, views and controllers.
- How to add email confirmation using a token.
- How to add password reset using a token.
- How to add basic authentication to Web API's.
- How to decouple your security model from your application domain.

Unit tests
----------

Unit tests do correctly clean up after each test, so data connection is not in valid state for next test.
For now, all tests will have to be run individually.

Release Notes
-------------

### v3.0.0 ###

- Tidy solutions (promote SimpleSecurityMVC5 to top level project)
- Fix Bootstrap XSS vulnerability

### v2.0.1 ###

- Remove OData insecurity
- Remove MobileExample project

### v2.0.0 ###

Configure .nuspec and package output(s) correctly this time.

### v1.0.0 ###

Initial release.

---
Forked from Kevin Junghans's original source at http://simplesecurity.codeplex.com/
