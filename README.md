# Getting Started with the Blazor Breadcrumb Component

## Overview

This sample demonstrates the Syncfusion [Blazor Breadcrumb](https://www.syncfusion.com/blazor-components/blazor-breadcrumb) component in a hosted Blazor WebAssembly application. The application showcases how to build hierarchical navigation paths using breadcrumb items, icons, URL based navigation, overflow handling, hidden item rendering, and custom templates. The sample provides a practical reference for implementing intuitive navigation experiences that help users understand their current location within an application's structure.

## Key Features

- Uses the `SfBreadcrumb` component from the `Syncfusion.Blazor.Navigations` namespace.
- Demonstrates hierarchical navigation using multiple `BreadcrumbItem` definitions.
- Configures breadcrumb items through the `Text` property to represent navigation paths.
- Uses the `Url` property to enable route based navigation.
- Enables navigation for the active breadcrumb item using the EnableActiveItemNavigation property.
- Customizes breadcrumb item rendering through the ItemTemplate template.
- Integrates the Syncfusion SfButton component within breadcrumb item templates.
- Customizes breadcrumb separator rendering through the SeparatorTemplate template.
- Uses a custom CSS-based icon for breadcrumb separators.
- Demonstrates template-based customization for creating a personalized breadcrumb navigation experience.
- Shows navigation patterns commonly used in web applications to help users understand their current location within the application hierarchy.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone the repository.
2. Open the `GettingStarted.sln` solution.
3. Restore all NuGet packages.
4. Ensure the appropriate startup project is selected for the hosted Blazor WebAssembly application.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the `Server` project directory:

```bash
cd Server 
```

4. Restore project dependencies:

```bash
dotnet restore
```

5. Run the application:

```bash
dotnet run
```

6. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Solution file for the sample application.

- `Client/` — Contains the Blazor WebAssembly client application.

- `Client/Pages/Index.razor` — Main page demonstrating breadcrumb navigation, URL navigation, active item navigation, custom item templates, and custom separator templates.

- `Server/` — Hosts and serves the Blazor WebAssembly application.

- `Shared/` — Contains shared models and resources used by both the Client and Server projects.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/breadcrumb/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion
