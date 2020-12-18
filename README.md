# Introduction

Real Edge Consulting online presence.

## Getting Started

You will need to use the .NET Core command-line interface to build and run the code.

## Install Prerequisites

Download and install the [latest .NET Core SDK.](https://dotnet.microsoft.com/download/dotnet-core)

## Build and Run

1. Open a command line shell and navigate to the root folder.

2. Enter the following command to trust the HTTPS development certificate:

```cli
    dotnet dev-certs https --trust
```

3. Run the app

```cli
    cd src\webapp
    dotnet run
```

After the command shell indicates that the app has started, browse to <https://localhost:5001>

Click **Accept** to accept the privacy and cookie policy. This app doesn't keep personal information.
