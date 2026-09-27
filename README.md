# Utility.Standard

A .NET Standard 2.0 / .NET 5 compatible utility library providing extension methods for serialization, type conversion, reflection, and general-purpose .NET development.

**Source last updated:** 2021-06-14
**Initiated:** 2019-04-04 · **Target Frameworks:** .NET Standard 2.0, .NET 5

---

## Overview

The .NET Standard targeting build of the Utility extensions library. Consumable from .NET Framework 4.6.1+, .NET Core 2.0+, .NET 5+, Xamarin, and Unity.

---

## Features

| Category | Description |
|----------|-------------|
| Generic serialization | `DeepCopy<T>()`, `Save<T>()`, `SaveToFile<T>()`, `LoadFromFile<T>()` |
| Binary serialization | `ToSerialisedByteArray()`, `ToObject<T>(byte[])` |
| Reflection | `ClearEventInvocations()`, `GetEventField()` |
| String conversion | `As<T>()`, `As<T>(T default)`, `LengthOf()` |

---

## Relationship to Other Libraries

| Library | Relationship |
|---------|-------------|
| `Utility` | Core source - same API, targets .NET Core 2.0-3.1 |
| `Utilities` | Full-featured library with WinForms controls, DB helpers, serial comms |
| `Utilities.Standard` | Cross-platform build of Utilities for .NET Core |

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Utility.Standard` (`Utility.Standard.csproj`) | C# | Project stub (ToolsVersion Current, empty PropertyGroup) | Placeholder for the .NET Standard build; no source files are in this tree |

The working copy holds only the project stub plus `Utilities.Core.csproj.user` / `.vspscc` leftovers. The extension methods described above live in the sibling [Utility](https://github.com/VaderConsulting/Utility) repo.

## How to open

Open `Utility.Standard.csproj` in Visual Studio 2019 or later. To build the library, use the sibling `Utility` project (`Utility.Core.csproj`, netstandard2.0).

## Requirements

- Visual Studio 2019 or later (ToolsVersion Current)
- .NET Standard 2.0 / .NET 5 SDK

## Attribution and provenance

Working copy from my Historical Dev folder.

Working copy from my Development folder `Utility.Standard`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.

