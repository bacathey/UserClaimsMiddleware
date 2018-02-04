# UserClaimsMiddleware
Middleware used to easily fetch claims about the User from various providers and deliver them into your ClaimsPrincipal for further usage in an ASP.Net Web application.

This middleware allows you to add arbitrary Claims Providers and a number of options for exception handling, caching, etc. Multiple provider calls are invoked in parallel. Claims Providers can be written (by you) and wired up to privide claims data from ANY source.

Available as OWIN middleware, and later for ASP.Net Core.

Documentation and a sample project will be made available soon.
