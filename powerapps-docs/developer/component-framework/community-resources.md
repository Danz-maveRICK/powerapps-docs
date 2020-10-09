---
title: Community resources (Power Apps Component Framework) | Microsoft Docs
description: Access to community resources
keywords:
author: Nkrb
ms.author: nabuthuk
manager: kvivek
ms.date: 12/09/2019
ms.service: "powerapps"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
---

# Community resources for Power Apps component framework

The following is a list of some community resources created by the Power Apps community that you can use to create code components in model-driven and canvas apps using Power Apps component framework and Power Apps CLI. 

> [!NOTE]
> Resources created by the community are not supported by Microsoft. If you have questions or issues with community resources, contact the publisher of the resource. Before using these resources, you must ensure that these community resources meet the Power Apps component framework guidelines and should only be used for reference purpose. 

## Code components gallery

The Power Apps component framework gallery (<https://pcf.gallery/>) is a collection of code components created by the Power Apps community. It has a wide range of code components that may fit in for your business case. 

Make sure that you review the licensing terms and the source code before you download. See, [How to run the samples](use-sample-components.md) article on how to create a solution package and import into Common Data Service.

> [!WARNING]
> Code component run in the context of the end user who is using the component and can perform any action that may include accessing, capturing, and modifying the data. 

> [!div class="mx-imgBorder"]
> ![Component gallery](media/pcf-gallery.PNG "Components gallery")

## Videos

The following is the list of videos created by Power Apps community.

|Name|Description|
|------|-------|
|[Build your own code components](https://www.youtube.com/watch?v=S3Z_IUf1ncg)| Learn how to build code components in model-driven and canvas apps using the Power Apps component framework.| 
|[Code components for canvas apps](https://www.youtube.com/watch?v=bMSCkcb4xAQ&feature=emb_logo)| Learn how to develop and use code components in canvas apps.|
|[Develop code components](https://www.youtube.com/watch?v=FxWF-LCCB4g&feature=youtu.be)| This video shows the requirements for developing code components using Power Apps component framework and demonstrates a step-by-step approach for creating your first code component.|
|[Easier debugging with source maps and Fiddler](https://www.youtube.com/watch?v=Ov-m5FBUj9g&feature=youtu.be)|Learn how to debug minified production code using Fiddler and source maps.|
|[Getting started with code components](https://www.youtube.com/watch?v=ylhVZUlGgQw)| Introductory video on Power Apps component framework and basics of building code components.|
|[Power Apps component framework Academy: Getting started](https://www.youtube.com/watch?v=YJ9hrKxAhTU)| Introductory video on how to build your first code component.|
|[Power Apps component framework: Deep dive manifest file for dataset template](https://www.youtube.com/watch?v=TsTrYaOGaGo&feature=youtu.be)| Learn how to define a manifest file for dataset type code components.|
|[Power Apps component framework Academy: Deep dive manifest file for field template](https://www.youtube.com/watch?time_continue=522&v=w40zqSsYEy0)| Learn how to define a manifest file for field type code components.|
|[Power Apps component framework Academy: Dataset components](https://www.youtube.com/watch?v=OEiM97nTD0w)| Learn more detail about dataset components and how different methods of dataset API are used.|
|[Power Apps component framework Academy: Importing into your organization](https://www.youtube.com/watch?v=2uO2L2xTPkc)| Learn how to package and import code components into Common Data Service.|
|[Power Apps component framework revolution](https://youtu.be/_SjEQ-7LK_Q)|Learn how component framework has enhanced the visualization in model-driven and canvas apps|
|[Power Apps component framework Academy: Using React and Office UI fabric](https://www.youtube.com/watch?v=e7JNgGlI3nE)| Learn how to use React and UI fabric in code components.|
|[Power Apps component framework Academy: Usage of additional frameworks](https://www.youtube.com/watch?v=cOPyyDdsEjQ)| Learn how to use additional frameworks in building code components.|
[Power Apps component framework Academy: Working with manifest file](https://www.youtube.com/watch?v=qbSpDVTxt7U&t=5s)| Introductory video on manifest file and various methods that need to be defined for developing code components in the manifest file.|
|[Power Apps component framework: What it is for Dynamics 365](https://youtu.be/3LnPaKtfKhw)|If you have ever lamented over the limitations of custom form components in Microsoft Dynamics 365, this tutorial will open your eyes to a whole new world of possibilities.|

## Blogs

The following is the list of blogs created by Power Apps community.

- [Add style to code component in Power Apps component framework](https://nishantrana.me/2019/06/06/how-to-add-style-to-custom-component-in-powerapps-component-framework/)
- [Beyond the Power Apps component framework](https://www.itaintboring.com/dynamics-crm/beyond-the-powerapps-component-framework)
- [Beyond the citizen developer: Why pros see promise in Microsoft's Power Apps component framework](https://msdynamicsworld.com/story/beyond-citizen-developer-why-pros-see-promise-microsofts-powerapps-component-framework)
- [Create code components](https://debajmecrm.com/2019/04/26/in-depth-end-end-walkthrough-develop-your-custom-controls-using-power-apps-component-framework-and-use-it-on-your-crm-interface/)
- [Editing the DOM with supported code components](https://www.magnetismsolutions.com/blog/adammurchison/2019/05/29/editing-the-dom-with-supported-dynamics-365-custom-controls)
- [How to configure Node.js and Typescript into your environment](https://capuanodanilo.com/2019/06/11/how-to-configure-node-js-and-typescript-into-your-environment-to-develop-powerapps-component-frameworks-pcf)
- [Localization of code components](https://dynamicsninja.blog/2020/01/21/pcf-localization)
- [Power Apps component framework – Frosting on the Cake](https://stevemordue.com/powerapps-component-framework-frosting-on-the-cake/)
- [Public availability of Power Apps component framework – An important milestone](https://crmindian.com/2019/04/24/public-availability-of-powerapps-component-framework-an-important-milestone-for-powerapps-and-d365/)
- [Work with code components using Power Apps component framework](https://powermaverick.dev/2019/05/18/create-custom-controls-using-powerapp-component-framework)
- [What happens when a web resource calls setVisible/setDisabled for that component](https://www.itaintboring.com/dynamics-crm/pcf-components-and-setvisible-setdisabled)

## Tools

The [Code component builder](https://www.xrmtoolbox.com/plugins/Maverick.PCF.Builder/) is a tool from XrmToolBox that lets you create code components in visual manner using the Power Apps CLI.

### Initialization

When you first load the plugin, you need to select your working directory. This working directory will be saved if you plan to reuse the same in future.

> [!NOTE]
> Currently only one working directory can host only one Custom Control project

Next populate Visual Studio Developer Command Prompt location (VsDevCmd.bat). This is only needed for building the solution (MSBUILD commands) and is a one-time setup. Path can be changed later from the Settings menu.

### Toolbar

| Item | Sub-Item | Description |
|--|--|--|
| New PCF Control | New from Blank | This would setup the plugin to guide you through the process of creating a custom control from scratch. |
| New PCF Control | New from Template | The plugin would present you with various community built custom controls published on PCF Gallery. Once you download any of the custom control, a script would try to download the code from GitHub repo and load the control details for you. |
| Edit PCF Control | - | Based on the selected working directory, plugin will try to identify any existing PCF project and CDS Project. It will then load the details for you so you don’t have to type those details again. |
| Authentication Profiles | Create Profile | This option will prompt user to enter Common Data Service URL and would authenticate and create an [authentication profile](https://docs.microsoft.com/en-us/powerapps/developer/component-framework/import-custom-controls#connecting-to-your-environment). |
| Authentication Profiles | List Profiles | You can view all the existing profiles that were created on that machine. You can manage your profiles by either changing the default or deleting them from the machine. |
| PCF Gallery | - | A community build custom control store. You will find lot of good custom controls built by the community. |
| Sample Controls | - | A downloadable zip file that contains sample controls for your learning. |
| PowerApps CLI | Download PowerApps CLI | This will take you to the download page of PowerApps CLI. |
| PowerApps CLI | Update PowerApps CLI | This will run the CLI command to update itself to the latest version available. |
| Help | PowerApps Component Framework | Navigates you to Microsoft’s PowerApps Component Framework Overview documentation. |
| Help | Microsoft Docs for Custom Component | Navigates you to the documentation on building Custom Controls. |
| Help | PCF Limitations | Navigates you to the documentation that lists limitations of PowerApps Component Framework. |
| More Links | Demos | Links to [community content page](https://aka.ms/PCFDemos). |
| More Links | Blogs | Links to [Power Apps Blog page](https://aka.ms/PCFBlog). |
| More Links | Forums | Links to community forums for [Power Apps Pro Dev & ISV page](https://aka.ms/PCFForum). |
| More Links | Ideas | Links to new [Ideas page](https://aka.ms/PCFIdeas). |
| Settings | - | To change your preferred working directory or your Visual Studio Command Prompt location. |

### Component Details

If you are building a new or updating an existing custom control then you need to work within the "Component Details" section of the tool.

| Buttons | Function |
|--|--|
| Create | This button will initialize a new PCF project and install all required references |
| Open in VS Code | It will open the current PCF project in Visual Studio Code |
| Build | This will run the build command on the current PCF project |
| Test | If "No Watch" checkbox is not checked then it will run the current custom control in PCF Test Harness with [watch mode](https://docs.microsoft.com/en-us/powerapps/developer/component-framework/debugging-custom-controls#watch-mode-in-test-harness) enabled and if "No Watch" was checked then [watch mode](https://docs.microsoft.com/en-us/powerapps/developer/component-framework/debugging-custom-controls#watch-mode-in-test-harness) will be disabled. |
| Quick Deploy | 