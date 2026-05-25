# Blazor DataForm Localization

A compact example showing how to localize data-annotation labels, validation messages, and component strings in a Blazor WebAssembly app.

## Overview

A compact Blazor WebAssembly sample demonstrating how to localize data-annotation labels and validation messages using .resx resource files, and how to provide localized strings to components.

## Features

- Localized display names for model properties (data annotations)
- Localized validation messages using `ErrorMessageResourceName` / `ErrorMessageResourceType`

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting started

### Clone the repository:

```bash
git clone https://github.com/SyncfusionExamples/blazor-dataform-localization.git
cd blazor-dataform-localization
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References


- Blazor Localization (official documentation):
https://learn.microsoft.com/aspnet/core/blazor/globalization-localization
- Data Annotations Localization in .NET:
https://learn.microsoft.com/aspnet/core/fundamentals/localization