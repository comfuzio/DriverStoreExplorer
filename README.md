Driver Store Explorer [RAPR]
===================================================

[![Build Status](https://ci.appveyor.com/api/projects/status/kqtvhfq23am2gq26/branch/master?svg=true)](https://ci.appveyor.com/project/lostindark/driverstoreexplorer/branch/master)

## Overview
Driver Store Explorer [RAPR] makes it easier to deal with Windows [driver store](https://msdn.microsoft.com/en-us/library/ff544868(VS.85).aspx). Supported operations include list/add/install/delete/export third-party driver packages.

## Features
* Support online (local machine) and offline driver store.
* Enumerate / list all third-party driver packages in the driver store. Showing device associated with drivers. Export the driver package list as CSV.
* Add a driver package to the driver store.
* Delete one or multiple driver packages from the store.
* Detect old and not used driver packages (best effort).
* Export all / selected driver packages.
* Full-fledged GUI Supports grouping / sorting on any column. Supports re-arranging of / selecting specific columns.

## Screenshots
![Screenshot of DriverStoreExplorer](https://github.com/user-attachments/assets/2d7df896-494d-4bcd-b064-5f05696cd0d3)

## Requirements
This tool requires:
* .NET Framework 4.6.2 or newer
* Windows 7 or newer

To build the code yourself, open Rapr.sln in Visual Studio 2022. Older Visual Studio versions may also work but it is not guaranteed.

## Releases
Download the latest version here: https://github.com/lostindark/DriverStoreExplorer/releases/latest.

## History
The project was originally hosted on https://driverstoreexplorer.codeplex.com/.

## Credits
* [ObjectListView](http://objectlistview.sourceforge.net/)
* [Managed DismApi Wrapper](https://github.com/jeffkl/ManagedDism)
* [FlexibleMessageBox](https://www.codeproject.com/Articles/601900/FlexibleMessageBox-A-Flexible-Replacement-for-the)
* [Resource Embedder](https://github.com/0xced/resource-embedder)
* [PortableSettingsProvider](https://github.com/bluegrams/SettingsProviders)
* [Strong Namer](https://github.com/dsplaisted/strongnamer)

## Sponsors
Free code signing on Windows provided by [SignPath.io], certificate by [SignPath Foundation].

[SignPath.io]: https://signpath.io
[SignPath Foundation]: https://signpath.org
