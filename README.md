## *** this is a work-in-progress ***

# SpreadsheetGear code samples for Visual Studio Code

This repository contains SpreadsheetGear code samples for .NET6 WPF, .NET6 Windows Forms, ASP.NET Core, and Jupyter Notebook applications. 

[Visual Studio Code (VSCode)](https://code.visualstudio.com/) is a source code editor for Windows, Linux and MacOS. This repository is based on a fork of [SpreadsheetGear/SpreadsheetGearExplorerSamples](https://github.com/SpreadsheetGear/SpreadsheetGearExplorerSamples) which was developed using Visual Studio 2022 on Windows. Code samples have been simplified for VSCode with one solution file (.sln) per folder, only one possible startup project (.csproj) per solution, and VSCode workspace (.code-workspace) files.

**These SpreadsheetGear code samples will run in Visual Studio Code on Windows, MacOS and Linux unless *"Windows only"* is indicated.**

* [Samples_WPF](/Samples_WPF) - Contains .NET 6.0 C# sample code for WPF ***(Windows only)***
* [Samples_WindowsForms](/Samples_WindowsForms) - Contains .NET 6.0 C# sample code for Windows Forms ***(Windows only)***
* [Samples_Web](/Samples_Web) - Contains sample code for ASP.NET Core Razor Pages
* Samples_JupyterCSharp - Contains Jupyter notebook C# sample code
* Samples_JupyterPython - Contains Jupyter notebook Python sample code

# Get Started #
  1. [SpreadsheetGear Nuget packages used in these demos](#spreadsheetgear-nuget-packages-used-in-these-demos)
  2. [Install Visual Studio Code on Windows, Linux or MacOS](#visual-studio-code-installation)
  3. [Open and run SpreadsheetGear code samples in Visual Studio Code](#open-and-run-spreadsheetgear-code-samples-in-visual-studio-code)

# SpreadsheetGear Nuget packages used in these demos
The code samples in this repository demonstrates a wide variety of APIs and features from these SpreadsheetGear Nuget packages:
*   **[SpreadsheetGear Engine for .NET](https://www.nuget.org/packages/SpreadsheetGear/9.1.19-beta)** - the primary SpreadsheetGear library that provides a core set of APIs to read, write, manipulate and calculate workbooks, build charts, format worksheets and cells, and more.
*   **[SpreadsheetGear for Windows](https://www.nuget.org/packages/SpreadsheetGear.Windows/9.1.19-beta)** - builds on SpreadsheetGear Engine for .NET to add powerful Excel-compatible image rendering, viewing, editing, formatting, calculating, filtering, sorting, charting, printing and more to your Windows Forms and WPF applications with the easy-to-use WorkbookView and FormulaBar controls.

Learn more about these products on our [Features Page](https://www.spreadsheetgear.com/Products/Features) and more details on their diffences on our [Comparison Page](https://www.spreadsheetgear.com/Products/Compare).

# Visual Studio Code installation
**For Windows:**
1. Install the [.NET SDK](https://dotnet.microsoft.com/en-us/download) 
    - Choose .NET 7.0 which will support the .NET 6.0 code samples. The Jupyter Notebook code samples require .NET 7.0 to support the Polygot Notebook extension (an extension installed by the .NET Extension Pack in step 3 below).
2. Install [Visual Studio Code](https://code.visualstudio.com/)
3. Install [.NET Extension Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-pack)
    - At the finish of installing .NET Extension Pack you might see a "Install .NET SDK" button. Ignore this as .NET SDK was already installed in the above step 1.
4. Install [Git for Windows](https://git-scm.com/download/win)
5. *Optional* - Install [GitLens to "Supercharge Git within VS Code"](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

**For MacOS:**
* work-in-progress

**For Linux:**
* work-in-progress

# Open and run SpreadsheetGear code samples in Visual Studio Code
1. **Clone this repo into your target folder**

```
Windows command line example:
C:\temp>git clone https://github.com/tracktownsoftware/SpreadsheetGearCodeSamples_VSCode.git
```
2. **Run Visual Studio Code and select "File | Open workspace from File..." to open a code workspace file (.code-workspace) from your local SpreadsheetGearCodeSamples_VSCode folder:**
    - Samples_WindowsForms.code-workspace
    - Samples_WPF.code-workspace
    - Samples_Web.code-workspace
    - Samples_JupyterCSharp.code-workspace
    - Samples_JupyterPython.code-workspace

3. **For additional instructions specific to a code workspace, click on its link in Step 2**
