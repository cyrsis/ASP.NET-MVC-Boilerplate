# TODO List

A list of improvements and new features to be added. Feel free to submit your own.

## General Improvements

Improvements that can be made to all project templates.

- Add [Google Structured Data](https://developers.google.com/structured-data/).
- Add a maintenance page.

## ASP.NET 4.6 MVC 5

- Change Boilerplate.Web.Mvc5 to use an ASP.NET Core class library project to build the NuGet package.

## ASP.NET Core MVC 6

- Add Glimpse and Prefix.io as an optional feature (https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate/issues/94).
- Add the Serilog logging framework as a feature.
- Upgrade to Gulp 4.0 when it is released.
  - Use [gulp plugin](https://github.com/gulpjs/gulp#incremental-builds) to cache which images have already been optimized.
- Build a localization feature (See [docs](https://docs.asp.net/en/1.0.0-rc2/fundamentals/localization.html)).
- Add a CORS feature.
- Add an option to remove Font-Awesome.
- Add a CSS vs SCSS (SASS) option.
- Add an option to add a Docker file.
- If Bootstrap 4 includes LESS support, add @ChrisOMetz's [pull request](https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate/pulls).
- Add an example form controller with [RequestFormSizeLimit](https://github.com/aspnet/Entropy/blob/dd60ba088cadb5bd82bddd3f22ed76069b4b5639/samples/Mvc.FileUpload/Controllers/RequestFormLimitsController.cs) attribute and [autofill](http://blog.cloudfour.com/autofill-what-web-devs-should-know-but-dont/) support.
- Improve social tag helpers to include child elements for images and other objects (See [this](https://channel9.msdn.com/Series/aspnetmonsters/Episode-19-Building-Advanced-Tag-Helpers?ocid=player)).
- Provide better TypeScript support with [typings](https://github.com/DefinitelyTyped/tsd/issues/269) and a default .ts file instead of .js.
- Implement a CDN Version TagHelper as described [here](https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate/issues/111#issuecomment-233343619).
- Implement an ASP.NET Identity 3 feature (See [Brock Allen](https://vimeo.com/172009501)'s video).

Wait for Microsoft to finish MVC 6 before adding these features:

- Add [Subresource Integrity](https://scotthelme.co.uk/subresource-integrity/) to scripts provided by Microsoft's CDN when they add the Access-Control-Allow-Origin HTTP header.
- CacheProfile.VaryByParam in Startup.CacheProfiles.cs.
- System.ServiceModel.SyndicationFeed does not exist on .NET Core. See [this](https://github.com/dotnet/wcf/issues/76#issuecomment-111420491) GitHub issue.
- Use the [HTTP Compression middle-ware](https://github.com/aspnet/BasicMiddleware/issues/34) instead of IIS compression.
- Use the [RequireHttps middle-ware](https://github.com/aspnet/BasicMiddleware/issues/31) instead of a filter.

## ASP.NET Core MVC 6 API

- Update project template and release it.
- Add Produces attributes.
- Add [JsonPatch](https://github.com/aspnet/JsonPatch).
