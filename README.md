# Title

Replace Default Navigation with Syncfusion Blazor Sidebar

## Overview

This sample demonstrates how to replace the default Blazor navigation menu with the Syncfusion [Blazor Sidebar](https://www.syncfusion.com/forums) component. The application uses a Sidebar-based layout to provide a responsive and customizable navigation experience within a Blazor Server application.

The implementation shows how the built-in Blazor navigation menu can be replaced with a Sidebar component that supports collapsible navigation and a modern application layout. It serves as a practical reference for developers who want to introduce Sidebar-based navigation patterns into Blazor applications.

## Key Features

- Uses the Syncfusion Blazor Sidebar component as the primary application navigation element.
- Registers Syncfusion Blazor services using `builder.Services.AddSyncfusionBlazor()` in `Program.cs`.
- Configures a Blazor Server application using `builder.Services.AddServerSideBlazor()`.
- Replaces the default navigation structure with a Sidebar-based layout.
- Supports responsive and collapsible application navigation.
- Demonstrates integration of Syncfusion components within the Blazor layout architecture.
- [VERIFY: Sidebar-specific properties, methods, and event handlers used in Razor files could not be fully inspected from the repository.]

## Prerequisites

- Visual Studio 2022
- .NET SDK compatible with Blazor
- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file:

   `SidebarDockNavigation.sln`

3. Restore the NuGet packages.
4. Set the startup project to:

   `SidebarDockNavigation`

5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
cd SidebarDockNavigation
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

[VERIFY: Exact launch profile URL could not be confirmed from the repository.]

## Project Structure

`App.razor` — Root application component that configures routing.

`Program.cs` — Configures dependency injection, Syncfusion Blazor services, routing, and application startup.

`SidebarDockNavigation.csproj` — Project file containing target framework and package references.

`SidebarDockNavigation.sln` — Visual Studio solution file.

`_Imports.razor` — Shared Razor imports used throughout the application.

`appsettings.json` — Application configuration settings.

`appsettings.Development.json` — Development environment configuration.

`Pages/` — Contains the Razor pages used by the sample application.  
[VERIFY: Individual page files could not be fully inspected.]

`Shared/` — Contains layout and navigation-related Razor components.  
[VERIFY: Individual shared files could not be fully inspected.]

`Data/` — Contains supporting data models and service classes used by the sample.  
[VERIFY: Individual data files could not be fully inspected.]

`Properties/launchSettings.json` — Launch profile and development configuration.

`wwwroot/` — Contains static assets such as stylesheets, images, and scripts used by the application.

`.github/workflows/` — GitHub Actions workflow configurations.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the https://blazor.syncfusion.com/documentation/sidebar/getting-started.

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.