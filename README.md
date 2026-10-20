# Windows Device Specification

A lightweight Windows desktop application built with **C# and Windows
Forms (WinForms)** to display a computer's basic device specifications.

This repository contains a public, simplified version of an application
originally developed for a client in the Netherlands. The original
product included client-specific computer-maintenance subscription and
advertising workflows. Those proprietary business features have been
removed from this release; the published code focuses on the
device-specification display.


<img width="444" height="297" alt="windows-specification-software" src="https://github.com/user-attachments/assets/2d26685f-517b-4c04-80a2-b1cba0ff0193" />


## Overview

The application presents key information about the Windows computer on
which it runs, in a simple desktop interface. It is shared so other
developers can inspect the implementation, learn from the WinForms UI,
and adapt the available code for their own projects.

## Executable File

-   Go To Action In Repository
-   Select Build WinForms App Workflow
-   Select Any Workflow That Has Green Tick
-   Scroll Down To The Artifacts Section
-   Download The Final-WinForm-App Folder
-   You Can Find The .exe file in this folder , Run it and you will have App Preview.
    
## Features in this public version

-   Displays basic Windows device information in a desktop window.
-   Uses **C#** and **Windows Forms**.
-   Provides a straightforward UI that developers can customize.
-   Makes the available source code accessible for learning and further
    development.

> **Scope note:** This public version is a device-specification viewer.
> It does not include the original client's subscription management,
> maintenance tracking, purchase flows, or advertising functionality.

## Technology

-   **Language:** C#
-   **Desktop UI:** Windows Forms (WinForms)
-   **Platform:** Windows

The exact .NET target and build requirements depend on the project
configuration included in the source. Check the project file (`.csproj`)
in Visual Studio before building.

## Getting started

### Requirements

-   A Windows computer.
-   [Visual Studio](https://visualstudio.microsoft.com/) with the **.NET
    desktop development** workload.
-   The .NET version or targeting pack required by the project's
    `.csproj` file.

### Download the source

Clone the repository:

``` bash
git clone https://github.com/uzairmalik-uzii/Windows-Device-Specification.git
cd Windows-Device-Specification
```

Alternatively, use GitHub's **Code → Download ZIP** option and extract
the archive.

### Open, build, and run

1.  Open the solution (`.sln`) or C# project (`.csproj`) in Visual
    Studio.
2.  Allow Visual Studio to restore any required dependencies, if
    applicable.
3.  Check the target framework and install the matching developer pack
    if prompted.
4.  Select the project as the startup project.
5.  Build the solution, then run it with **F5** or **Ctrl+F5**.

If the repository does not contain a solution file, open the `.csproj`
directly. The precise steps may vary with the project structure and
target framework.

## Ideas for extending it

You can use the existing application as a starting point for experiments
such as:

-   Improving the layout and accessibility of the specification screen.
-   Adding additional system-information fields.
-   Separating device-information collection from UI code.
-   Adding error handling for unavailable or restricted system
    properties.
-   Introducing tests and a clearer application structure.
-   Connecting a backend service in a separate project, where
    appropriate.

Any new subscription, payment, advertising, or maintenance-management
functionality would need to be implemented independently; it is not
included in this repository.

## Contributing

Contributions and learning-focused improvements are welcome.

1.  Fork the repository.
2.  Create a branch for your change.
3.  Make a focused update and test it on Windows.
4.  Submit a pull request describing the change and how it was tested.

For larger changes, consider opening an issue first to discuss the
proposed direction.

## Important notes

-   This is a simplified public code sample, not the complete original
    client product.
-   Client-specific business logic and workflows have intentionally been
    excluded.
-   The repository is provided for developers to explore and adapt the
    available code. Review the repository's license, if present, before
    redistributing or using the code in another project.
-   Do not assume the application includes remote monitoring,
    maintenance scheduling, subscription validation, payment processing,
    or advertising services.

## Author

**Uzair Malik**

GitHub: [@uzairmalik-uzii](https://github.com/uzairmalik-uzii)

## Acknowledgement

This repository is shared to make the non-proprietary
device-specification portion of a real-world WinForms project available
to the developer community.
