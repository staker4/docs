---
title: "Developing Windows Service Applications"
ms.date: "03/30/2017"
helpviewer_keywords: 
  - "ServiceInstaller class, Windows Service applications"
  - "Service class, Windows Service applications"
  - "Windows Service applications"
  - "Windows NT services"
  - "ServiceProcessInstaller class, Windows Service applications"
  - "services"
  - ".NET applications, Windows applications"
ms.assetid: ba72d648-9553-4849-b829-069ad5ea014b
author: "ghogen"
---
# Develop Windows service apps

Using Visual Studio or the .NET Framework SDK, you can easily create services by creating an application that is installed as a service. This type of application is called a Windows service. With framework features, you can create services, install them, and start, stop, and otherwise control their behavior.

> [!NOTE]
> In Visual Studio you can create a service in managed code in Visual C# or Visual Basic, which can interoperate with existing C++ code if required. Or, you can create a Windows service in native C++ by using the [ATL Project Wizard](/cpp/atl/reference/atl-project-wizard).

## In this section

[Introduction to Windows Service Applications](../../../docs/framework/windows-services/introduction-to-windows-service-applications.md)

Provides an overview of Windows service applications, the lifetime of a service, and how service applications differ from other common project types.

[Walkthrough: Creating a Windows Service Application in the Component Designer](../../../docs/framework/windows-services/walkthrough-creating-a-windows-service-application-in-the-component-designer.md)

Provides an example of creating a service in Visual Basic and Visual C#.

[Service Application Programming Architecture](../../../docs/framework/windows-services/service-application-programming-architecture.md)

Explains the language elements used in service programming.

[How to: Create Windows Services](../../../docs/framework/windows-services/how-to-create-windows-services.md)

Describes the process of creating and configuring Windows services using the Windows service project template.

## Related sections

<xref:System.ServiceProcess.ServiceBase> - Describes the major features of the <xref:System.ServiceProcess.ServiceBase> class, which is used to create services.

<xref:System.ServiceProcess.ServiceProcessInstaller> - Describes the features of the <xref:System.ServiceProcess.ServiceProcessInstaller> class, which is used along with the <xref:System.ServiceProcess.ServiceInstaller> class to install and uninstall your services.

<xref:System.ServiceProcess.ServiceInstaller> - Describes the features of the <xref:System.ServiceProcess.ServiceInstaller> class, which is used along with the <xref:System.ServiceProcess.ServiceProcessInstaller> class to install and uninstall your service.

[Create Projects from Templates](https://msdn.microsoft.com/library/7c36d86a-6b79-4480-8228-0f925f1204b2) -  Describes the projects types used in this chapter and how to choose between them.
