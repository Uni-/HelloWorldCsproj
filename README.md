# MSBuild example by hand: C\# Hello World

This example include cs and csproj files, which are all handwritten.

See commit log for details.

## Building

You can build this project in the following ways.

* **Using Visual Studio**, with its bundled MSBuild feature, if using Windows.
* **Microsoft Build Tools 2013/2015 installer** is downloadable [here](https://www.microsoft.com/en-us/download/details.aspx?id=48159). It's required for Xamarin Studio for Windows (formerly MonoDevelop), or to use msbuild in command line.
* **Getting MSBuild via NuGet**: MSBuild.exe is available via `nuget install MSBuild`. NuGet also works on Unix platform.
* **Building MSBuild from the source**: [Microsoft open-sourced it.](https://github.com/Microsoft/msbuild)
* **Getting MSBuild via Mono installation**; or using **xbuild**, the previous Mono implementation of msbuild. Mono is downloadable [here](http://www.mono-project.com/download) and it's required for Xamarin Studio for OS X or for MonoDevelop for Linux. Currently Mono package provides Micosoft's open-source MSBuild and xbuild is deprecated.

## References

* \[MSDN/dd576348\] [Walkthrough: Creating an MSBuild Project File from Scratch][MSDN/dd576348]

[MSDN/dd576348]: https://msdn.microsoft.com/en-us/library/dd576348.aspx
