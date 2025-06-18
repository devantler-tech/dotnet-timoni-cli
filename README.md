# .NET Template

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Test](https://github.com/devantler-tech/dotnet-template/actions/workflows/test.yaml/badge.svg)](https://github.com/devantler-tech/dotnet-template/actions/workflows/test.yaml)
[![codecov](https://codecov.io/gh/devantler-tech/dotnet-template/graph/badge.svg?token=RhQPb4fE7z)](https://codecov.io/gh/devantler-tech/dotnet-template)

A simple .NET template for new projects.

## 🚀 Getting Started

### Prerequisites

- .NET 9.0 or later
- [Timoni CLI](https://timoni.sh/install/) installed and available in your system's PATH

### Installation

To get started, you can install the package from NuGet.

```bash
dotnet add package <package-name>
```

## 📝 Usage

### Add a solution

```sh
dotnet new sln --name <name-of-solution>
```

### Add a project

```sh
dotnet new <project-type> --output folder1/folder2/<name-of-project>
```

### Add project to solution

```sh
dotnet sln add folder1/folder2/<name-of-project>
```

### Building your solution

```sh
dotnet build
```

### Running a project in your solution

```sh
dotnet run folder1/folder2/<name-of-project>
```

### Testing your solution

```sh
dotnet test
```
