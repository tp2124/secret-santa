# secret-santa
A website to help people do secret santa.

# Requirements
`dotnet --version` >= 3.1.301

Latest versions of the following as of 6/1/2020
* VSCode
* C# Extension in VSCode
* JavaScript Debugger Extension in VS Code from Microsoft 
* Enable Beta debugging for JavaScript debugging.

# How to Build
in `src/SecretSanta.App` run `dotnet build`

# How to Test
## Locally
Use VSCode to run the launch.json configurations setup for Blazor.

## Remotely
Not available.

# How to Deploy
Not available.

# Notes
* The `@page <name>` at the top of `.razor` files makes the files an endpoint for the website. This si neow required for components as you can make re-useable pieces that are not their own endpoint without this declaration.
  * https://docs.microsoft.com/en-us/aspnet/core/tutorials/build-your-first-blazor-app?view=aspnetcore-3.1

