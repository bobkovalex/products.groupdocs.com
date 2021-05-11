---
############################# Static ############################
layout: "auto-gen"
date: 2021-04-27T09:31:06+03:00
draft: false

############################# Head ############################
head_title: "View PDF files in C# .NET Applications | Document Viewer APIs"
head_description: "Render and view PDF files in .NET applications. Also display a wide range of business documents, images, diagrams, web and other formats using native .NET APIs."

############################# Header ############################
title: "View PDF Files in C#"
description: "‎Cross-platform PDF files viewing solution using server side GroupDocs.Viewer for .NET APIs, without depending on any third party software, pre-installed on your system.‎"
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer"

############################# SubMenu ############################
submenu:
  enable: true
  
  left:
      img_alt: "GroupDocs.Viewer for .NET"
      image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
      product: "GroupDocs.Viewer"
      platform: ".NET"

  middle:
      button:
          # button loop
          - link: "https://apireference.groupdocs.com/viewer/net"
            text: "API Reference"

          # button loop
          - link: "https://github.com/groupdocs-viewer"
            text: "Code Examples"

          # button loop
          - link: "https://products.groupdocs.app/viewer/family"
            text: "Live Demos"

          # button loop
          - link: "https://purchase.groupdocs.com/pricing/viewer/net"
            text: "Pricing"

  right:
      link_download: "https://downloads.groupdocs.com/viewer"
      link_learn: "https://docs.groupdocs.com/viewer/net/"
      link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
  enable: true
  title: "About GroupDocs.Viewer for .NET API"
  content: |
    Start viewing [170+ popular document formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/) in your .NET applications using [GroupDocs.Viewer for .NET](https://products.groupdocs.com/viewer/net) APIs by adding a few lines of code. Developers can easily display PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook and many other popular document formats in HTML5, image or PDF modes. The document rendering is fast, identical to the original source file, and it does not require installing Microsoft Office or any other external libraries.

############################# Steps ############################
steps:
  enable: true
  title_left: "Steps for Viewing PDF File in C#"
  content_left: |
    [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net) makes it easy for .NET developers to add PDF file viewing feature in their applications by implementing a few easy steps.
    * Create an instance of Viewer class and load the PDF file with full path.
    * Set options for rendering PDF file into PNG format.
    * Create view for rendered output file.
  title_right: "System Requirements"
  content_right: |
    GroupDocs.Viewer for .NET APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installed on your system.
    * Operating Systems: Microsoft Windows, Linux, MacOS
    * Development Environments: Microsoft Visual Studio, Xamarin, MonoDevelop
    * Frameworks: .NET Framework, .NET Standard, .NET Core, Mono
    * Get the latest version of GroupDocs.Viewer for .NET downloaded from [Nuget](https://www.nuget.org/packages/groupdocs.viewer)
  code: |
    ```cs
      // Instantiate viewer
      using (Viewer viewer = new Viewer("sample.pdf"))
      {
        ViewOptions viewOptions = new PngViewOptions();
        viewer.View(viewOptions);
      }
    ```

############################# Demos ############################
demos:
  enable: true
  title: "PDF Viewer Live Demos"
  content: |
    Display PDF file right now by visiting [GroupDocs.Viewer Live Demos](https://products.groupdocs.app/viewer/family) website.  
    The live demo has the following benefits

############################# About Formats ############################
about_formats:
  enable: true
  format:
    # format loop
    - icon: "far fa-file-pdf"
      title: "About PDF File Format"
      content: |
       Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. PDF files can be opened in Adobe Acrobat Reader/Writer as well in most modern browsers like Chrome, Safari, Firefox via extensions/plug-ins. Most of the commercially available software suites also offer conversion of their documents to PDF file format without the requirement of any additional software component. Thus, PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, digital signatures, attachments, metadata, Geospatial features and 3D objects in it that can become as part of source document.
      link: "https://docs.fileformat.com/view/pdf/"

############################# More Formats ############################
more_formats:
  enable: true
  title: "Other File Formats Rendering & Viewing"
  content: |
    Multi format documents and images viewer API for .NET. View some of the popular file formats below without any external viewers.
  format:
    # format loop
    - name: "DOC Viewer"
      link: "https://products.groupdocs.com/viewer/net/doc"
      description: "Microsoft Word Document"

    # format loop
    - name: "DOCM Viewer"
      link: "https://products.groupdocs.com/viewer/net/docm"
      description: "Microsoft Word Macro-Enabled Document"

    # format loop
    - name: "DOCX Viewer"
      link: "https://products.groupdocs.com/viewer/net/docx"
      description: "Microsoft Word Open XML Document"

    # format loop
    - name: "DOT Viewer"
      link: "https://products.groupdocs.com/viewer/net/dot"
      description: "Microsoft Word Document Template"

############################# Back to top ###############################
back_to_top:
  enable: true
---