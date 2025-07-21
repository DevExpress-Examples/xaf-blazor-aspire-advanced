<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1290233)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# XAF Blazor — .NET Aspire Support — Custom Telemetry, Service Orchestration, Database Dependency

This example outlines the following features for .NET Aspire integration with an XAF Blazor application:

* **Custom Telemetry with OpenTelemetry**. Log custom activities and metrics with OpenTelemetry, which are then visualized in the Aspire Dashboard. This integration lets you monitor and analyze application performance and behavior.
* **Database Dependency Management**. Run SQL Server as a dependency inside a container coordinated by Aspire. This approach simplifies database management and deployment in your application.
* **Service Orchestration**. Configure the Blazor application as part of Aspire orchestration. This configuration lets you manage and coordinate multiple services in your application ecosystem.

These features improve observability, modularity, and deployment flexibility in XAF Blazor applications using .NET Aspire.

For a detailed walkthrough, refer to the following blog post: [.NET Aspire Support For An XAF Blazor Project — Custom Telemetry, Service Orchestration, Database Dependency](https://community.devexpress.com/Blogs/news/archive/2025/04/21/net-aspire-xaf-blazor-custom-telemetry-service-orchestration-database-dependency.aspx)

## Files to Review

- [XafAspireDemo.Blazor.Server/Controllers/ImportantBusinessOperationsController.cs](CS/XafAspireDemo.Blazor.Server/Controllers/ImportantBusinessOperationsController.cs)
- [XafAspireDemo.Blazor.Server/Telemetry.cs](CS/XafAspireDemo.Blazor.Server/Telemetry.cs)
- [XafAspireDemo.Blazor.Server/Startup.cs](CS/XafAspireDemo.Blazor.Server/Startup.cs)
- [XafAspireDemo.Blazor.Server/BlazorApplication.cs](CS/XafAspireDemo.Blazor.Server/BlazorApplication.cs)
- [XafAspireDemo.AppHost/Program.cs](CS/XafAspireDemo.AppHost/Program.cs)
- [XAFAspireDemo.DemoService/Program.cs](CS/XAFAspireDemo.DemoService/Program.cs)

## More Examples

- [XAF Blazor — .NET Aspire Support — Introduction](https://github.com/DevExpress-Examples/xaf-blazor-aspire-support)

<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=xaf-blazor-aspire-advanced&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=xaf-blazor-aspire-advanced&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
