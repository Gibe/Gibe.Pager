# Gibe Pager

Some reusable utilities and models for creating pagers

`install-package Gibe.Pager`

or for >= .NET 5.0 

`dotnet add package Gibe.Pager`

You'll need to implement the `ICurrentUrlService`.

Then, you'll need to init the DI via

`services.AddGibePager<T>()` where T is your `ICurrentUrlService` implementation
