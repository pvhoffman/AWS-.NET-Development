# Porting Assistant for .NET

Migrating .NET Framework applications to .NET Core enables you to harness its performance enhancements, cost efficiencies, and thriving Linux ecosystem. Assessing the complexity of porting applications to .NET Core involves identifying dependencies and APIs that are incompatible with the platform.

The Porting Assistant for .NET serves as an analysis tool designed to scan .NET Framework applications, producing a compatibility assessment for migration to .NET Core, particularly for deployment on Linux. It identifies incompatibilities between .NET Framework and .NET Core, suggests viable replacements, and generates a comprehensive compatibility report. By automating this process, the Porting Assistant minimizes the manual labor involved in modernizing applications for Linux environments.

Porting Assistant for .NET enables scanning of your complete .NET Framework application lineup, producing compatibility assessment reports for .NET Core. These reports aid in prioritizing applications for porting by gauging the effort needed.

Porting Assistant for .NET supports .NET 6 as a target framework and ports certain ASP.NET Web Forms application configurations to ASP.NET Core Blazor framework.

Porting Assistant for .NET translates select Web Forms view or UI layer files, page lifecycle events, and application lifecycle events to the cross-platform Blazor framework. You can use the Porting Assistant for .NET standalone tool or Porting Assistant for .NET Visual Studio IDE extension to modernize your Web Forms applications. You can also port applications to the latest long-term support (LTS) release .NET 6 version, in addition to .NET Core 3.1 and .NET 5 target versions.

## Using Porting Assistant for .NET process

Porting Assistant for .NET provides insight and assistance for porting from .NET Framework to .NET Core.

You start by scanning the solution and choosing the path to the application solution source.

### Scan

You can also scan the entire .NET Framework application portfolio to generate compatibility assessment reports so that you can prioritize applications for porting based on the amount of effort required.

Porting Assistant for .NET creates a graphical user interface to help you visualize project dependencies within a solution file. This interface helps you to assess the impact of changes at the solution level.

### Assessment

Porting Assistant for .NET scans the source code and NuGet packages of your .NET applications at the solution (.sln) level. Then, it generates a compatibility assessment report.

The assessment overview and detailed reports show the most referenced projects, available updated packages, and API compatibility.


### Porting assistance

Porting Assistant for .NET updates the packages and project references to use .NET Core compatible formats.

Porting Assistant for .NET identifies incompatible packages and APIs in the source code. If there are known replacements, Porting Assistant for .NET applies them.

The API replacement engine of the Porting Assistant for .NET continuously improves as it learns more about the incompatible packages and APIs.


[Porting Assistant for .NET download](https://aws.amazon.com/porting-assistant-dotnet/)


