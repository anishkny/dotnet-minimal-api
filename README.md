# .NET Minimal API Example

[![CI](https://github.com/anishkny/dotnet-minimal-api-example/actions/workflows/ci.yml/badge.svg)](https://github.com/anishkny/dotnet-minimal-api-example/actions/workflows/ci.yml)
[![codecov](https://codecov.io/gh/anishkny/dotnet-minimal-api-example/graph/badge.svg)](https://codecov.io/gh/anishkny/dotnet-minimal-api-example)

This repository follows along and implements this tutorial: [Create a minimal API with ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-7.0&tabs=visual-studio-code).

> Minimal APIs are architected to create HTTP APIs with minimal dependencies. They are ideal for microservices and apps that want to include only the minimum files, features, and dependencies in ASP.NET Core.

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (Version 7 or later)
- [Node.js](https://nodejs.org/en/) (Version 18 or later)

### Installation

1. Clone this repository

```bash
git clone https://github.com/anishkny/dotnet-minimal-api-example.git
```

2. Install dependencies

```bash
cd dotnet-minimal-api-example
npm install
```

### Usage

1. Run the application

```bash
npm run build
npm run start
```

2. Open a browser and navigate to [http://localhost:5000/todoitems](http://localhost:5000/todoitems)

### Running Tests

```bash
npm run start-and-test
```

### Postman Collection

Included is a Postman collection that can be used to test the API. You can import the collection by opening Postman and clicking on `File > Import...` and selecting the [`api-tests.postman_collection.json`](./api-tests.postman_collection.json) file.

![Postman Collection](./postman.png)

It is also used for automated testing via the `newman` tool.

### Coverage

After running the test suite, you can view the code coverage report by opening the `coveragereport/index.htm` file in a web browser.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/) - see the [LICENSE](LICENSE) file for details.
