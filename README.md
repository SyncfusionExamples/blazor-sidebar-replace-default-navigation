# Replace Default Navigation with Syncfusion Blazor Sidebar

## Overview

This sample demonstrates how to replace the default Blazor navigation menu with the Syncfusion [Blazor Sidebar](https://www.syncfusion.com/blazor-components/blazor-sidebar) component. The application uses a Sidebar based layout to provide a responsive and customizable navigation experience within a Blazor Server application.

The implementation shows how the built in Blazor navigation menu can be replaced with a Sidebar component that supports collapsible navigation and a modern application layout. It serves as a practical reference for developers who want to introduce Sidebar based navigation patterns into Blazor applications.

## Key Features

- Uses the Syncfusion Blazor Sidebar component to replace the default Blazor navigation menu.
- Integrates `SfSidebar` into the application layout to provide a custom navigation experience.
- Supports collapsible Sidebar navigation for improved screen space utilization.
- Demonstrates Sidebar-based navigation within a Blazor Server application.
- Configures Syncfusion Blazor components through `builder.Services.AddSyncfusionBlazor()` in `Program.cs`.
- Uses Blazor routing together with Sidebar navigation to switch between application views.
- Provides a responsive navigation layout that adapts to different screen sizes.
- Shows how custom navigation content can be hosted inside the Sidebar component instead of the default `NavMenu`.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the `SidebarDockNavigation.sln` solution file:
3. Restore the NuGet packages.
4. Set the startup project to `SidebarDockNavigation`.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```
4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `SidebarDockNavigation.sln` — Visual Studio solution file containing the sample projects.

- `Pages/Index.razor` — Main sample page that demonstrates replacing the default Blazor navigation menu with the Syncfusion Sidebar component.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the https://blazor.syncfusion.com/documentation/sidebar/getting-started.

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.