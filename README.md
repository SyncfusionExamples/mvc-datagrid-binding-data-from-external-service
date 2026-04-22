# MVC DataGrid Binding Data from External Service

## Repository Description

This repository demonstrates how to bind the Syncfusion ASP.NET MVC DataGrid to data retrieved from an external service, such as a Web API, enabling clean separation between the UI layer and remote data sources.

## Overview
The sample shows an ASP.NET MVC application that integrates the Syncfusion EJ2 DataGrid and consumes data from an external service endpoint. Instead of binding the grid directly to local collections or databases, the application fetches data through HTTP requests, making it suitable for service-oriented and enterprise-scale applications.

## Key Features
- Integration of Syncfusion EJ2 DataGrid in an ASP.NET MVC project  
- Data binding using an external service or API endpoint  
- Server-side handling of data requests  
- Clean and maintainable MVC architecture  

## Prerequisites
- Visual Studio with ASP.NET MVC support  
- .NET Framework compatible with ASP.NET MVC  
- Syncfusion EJ2 ASP.NET MVC components  

## Installation
1. Clone the repository from GitHub.
2. Open the solution file in Visual Studio.
3. Restore NuGet packages if required.
4. Ensure the external service endpoint is accessible.
5. Build and run the application.

## Usage
When the application runs, the DataGrid sends requests to the configured external service. The service responds with structured data, which is then rendered in the grid with standard DataGrid features such as columns and data formatting.

## Resources
- https://ej2.syncfusion.com/aspnetmvc/documentation/grid/data-binding/remote-data