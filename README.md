## *** this is a work-in-progress ***

# SpreadsheetGear code samples for Visual Studio Code

This repository contains SpreadsheetGear code samples for .NET6 WPF, .NET6 Windows Forms, ASP.NET Core, and Jupyter Notebook applications. 

[Visual Studio Code (VSCode)](https://code.visualstudio.com/) is a source code editor for Windows, Linux and MacOS. This repository is based on a fork of [SpreadsheetGear/SpreadsheetGearExplorerSamples](https://github.com/SpreadsheetGear/SpreadsheetGearExplorerSamples) which was developed using Visual Studio 2022 on Windows. Code samples have been simplified for VSCode with one solution file (.sln) per folder, only one possible startup project (.csproj) per solution, and VSCode workspace (.code-workspace) files.

* **SpreadsheetGear code samples in Visual Studio Code on Windows:**
  *   [Samples_WPF](/Samples_WPF) - Contains C# sample code for WPF.
  *   [Samples_WindowsForms](/Samples_WindowsForms) - Contains C# sample code for Windows Forms.
* **SpreadsheetGear code samples in Visual Studio Code on Windows, Linux and MacOS:**
  *   [Samples_Web](/Samples_Web) - Contains sample code for ASP.NET Core Razor Pages.
  *   Samples_JupyterCSharp - Contains Jupyter notebook C# sample code
  *   Samples_JupyterPython - Contains Jupyter notebook Python sample code

## Get Started ##
* [SpreadsheetGear Nuget packages used in these demos](#spreadsheetgear-nuget-packages-used-in-these-demos)
* [Install Visual Studio Code on Windows, Linux or MacOS](#visual-studio-code-installation)
* [Open and run SpreadsheetGear code samples in Visual Studio Code](#open-and-run-spreadsheetgear-code-samples-in-visual-studio-code)

## SpreadsheetGear Nuget packages used in these demos
The code samples in this repository demonstrates a wide variety of APIs and features from these SpreadsheetGear Nuget packages:
*   **[SpreadsheetGear Engine for .NET](https://www.nuget.org/packages/SpreadsheetGear/9.1.19-beta)** - the primary SpreadsheetGear library that provides a core set of APIs to read, write, manipulate and calculate workbooks, build charts, format worksheets and cells, and more.
*   **[SpreadsheetGear for Windows](https://www.nuget.org/packages/SpreadsheetGear.Windows/9.1.19-beta)** - builds on SpreadsheetGear Engine for .NET to add powerful Excel-compatible image rendering, viewing, editing, formatting, calculating, filtering, sorting, charting, printing and more to your Windows Forms and WPF applications with the easy-to-use WorkbookView and FormulaBar controls.

Learn more about these products on our [Features Page](https://www.spreadsheetgear.com/Products/Features) and more details on their diffences on our [Comparison Page](https://www.spreadsheetgear.com/Products/Compare).

## Visual Studio Code installation
**For Windows:**
* Install the [.NET SDK](https://dotnet.microsoft.com/en-us/download) (version .NET 6.0 or greater will work)
* Install [Visual Studio Code](https://code.visualstudio.com/)
* Install [.NET Extension Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-pack)
  * The .NET Extension pack includes:
    * [C# for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
    * Jupyter Notebooks
* Install [Git for Windows](https://git-scm.com/download/win)
* *Optional* - Install [GitLens to "Supercharge Git within VS Code"](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

**For MacOS:**
* work-in-progress

**For Linux:**
* work-in-progress

## Open and run SpreadsheetGear code samples in Visual Studio Code
**1. Clone this repo into your target folder**

```
Windows command line example:
C:\temp>git clone https://github.com/tracktownsoftware/SpreadsheetGearCodeSamples_VSCode.git
```
**2. Your local SpreadsheetGearCodeSamples_VSCode folder will contain these workspace (.code-workspace) files:**

- **Code sample workspaces for Windows only**
  - Samples_WindowsForms.code-workspace
  - Samples_WPF.code-workspace
- **Code sample workspaces for Windows, Linux and MacOS**
  - Samples_Web.code-workspace
  - Samples_JupyterCSharp.code-workspace
  - Samples_JupyterPython.code-workspace

**3. Run Visual Studio Code and select "File | Open workspace from File..." to open the code sample workspace you want to see**
