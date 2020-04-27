# dnetcoreWasmMime

Click `test.wasm`, start download! Good job.

It work well in dotnet core 3.1.

If you want it work in dotnet core 2.1, you need specific the mmimetype.

https://docs.microsoft.com/en-us/aspnet/core/fundamentals/static-files?view=aspnetcore-2.1&tabs=aspnetcore2x#fileextensioncontenttypeprovider

```C#
provider.Mappings[".wasm"] = "application/wasm";
```
 
