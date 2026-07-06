# Blazor DataGrid with Multiple Foreign Key Columns

This sample explains about how to display the multiple columns with foreign key relation in [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

When building data-driven applications, you often need to display related information from other data sources. This sample shows how to configure the Blazor DataGrid to bind multiple columns to the same foreign key data source, enabling you to display different properties from related entities.

The sample includes a working example of an order management interface that displays:

- **Order ID**: Primary key for the order
- **First Name**: Employee first name from a related employee data source
- **Last Name**: Employee last name from the same employee data source  
- **Joined Date**: Order date information

## Features

- **Multiple Foreign Key Columns** - Configure and display multiple related data columns from the same or different data sources in a single grid
- **Unified Data Source Binding** - Bind multiple columns to the same foreign key data source using different display properties
- **Full CRUD Operations** - Add, edit, and delete records while maintaining foreign key relationships and data integrity
- **Real-time Data Updates** - Immediately display changes in foreign key columns as data is modified in the grid
- **Inline Editing** - Edit foreign key column values directly in the grid with automatic validation
- **Responsive Grid Layout** - Seamlessly adapts to different screen sizes with optimized column widths and scrolling

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-enable-multiple-foreignkey-columns.git
cd blazor-datagrid-enable-multiple-foreignkey-columns
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

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/editing#edit-foreign-key-column

**Online example**: https://blazor.syncfusion.com/demos/datagrid/foreign-key-column?theme=fluent2
