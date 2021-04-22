---
title: "Service"
description: "this is meta description"
bg_image: "images/feature-bg.jpg"
layout: "service"
draft: false

########################### about service #############################
about:
  enable : false
  title : "Creative UX/UI Design Agency"
  content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptate soluta corporis odit, optio
          cum! Accusantium numquam ab, natus excepturi architecto earum ipsa aliquam, illum, omnis rerum, eveniet
          officia nihil. Eum quod iure nulla, soluta architecto distinctio. Nesciunt odio ullam expedita, neque fugit
          maiores sunt perferendis placeat autem animi, nihil quis suscipit quibusdam ut reiciendis doloribus natus nemo
          id quod illum aut culpa perspiciatis consequuntur tempore? Facilis nam vitae iure quisquam eius harum
          consequatur sapiente assumenda, officia voluptas quas numquam placeat, alias molestias nisi laudantium
          nesciunt perspiciatis suscipit hic voluptate corporis id distinctio earum. Dolor reprehenderit fuga dolore
          officia adipisci neque!"
  image : "images/company/company-group-pic.jpg"


########################## featured service ############################
featured_service:
  enable : false
  service_item:
    # featured service item loop
    - name : "Interface Design"
      icon : "ion-erlenmeyer-flask"
      color : "primary"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."
      
    # featured service item loop
    - name : "Product Branding"
      icon : "ion-leaf"
      color : "primary-dark"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."
      
    # featured service item loop
    - name : "Game Development"
      icon : "ion-lightbulb"
      color : "primary-darker"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

      
############################# Service ###############################
service:
  enable : true
  title : "Our Products"
  description : "Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, <br> there live the
          blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics"
  service_item:
    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-total-net.png?v2"
      name: GroupDocs.Total Product Family
      link: "total"
      content: "Enable your applications to manipulate more than 100 file formats. Includes all of our 25+ individual products."
      button_net:
        enable: true
        link: "total/net"
      button_java:
        enable: true
        link: "total/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-viewer-net.png?v2"
      name: GroupDocs.Viewer Product Family
      link: "viewer"
      content: "Accelerate and simplify document or image viewing in any cross platform application with our native GroupDocs.Viewer APIs for .NET and Java"
      button_net:
        enable: true
        link: "viewer/net"
      button_java:
        enable: true
        link: "viewer/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-annotation-net.png?v2"
      name: GroupDocs.Annotation Product Family
      link: "annotation"
      content: "Manipulate documents with interactive and explanatory annotations to annotate text or images in any cross platform solution"
      button_net:
        enable: true
        link: "annotation/net"
      button_java:
        enable: true
        link: "annotation/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-conversion-net.png?v2"
      name: GroupDocs.Conversion Product Family
      link: "conversion"
      content: "Enhance productivity and streamline workflows with fast batch document conversion APIs in any cross platform application"
      button_net:
        enable: true
        link: "conversion/net"
      button_java:
        enable: true
        link: "conversion/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-comparison-net.png?v2"
      name: GroupDocs.Comparison Product Family
      link: "comparison"
      content: "Merge or Compare two similar format document by consuming difference checker APIs for .NET and Java"
      button_net:
        enable: true
        link: "comparison/net"
      button_java:
        enable: true
        link: "comparison/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-signature-net.png?v2"
      name: GroupDocs.Signature Product Family
      link: "signature"
      content: "Automate document signing with secure cross platform eSignature APIs for your personal or business signatures"
      button_net:
        enable: true
        link: "signature/net"
      button_java:
        enable: true
        link: "signature/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-assembly-net.png?v2"
      name: GroupDocs.Assembly Product Family
      link: "assembly"
      content: "Automate your document generation process with cross platform automation assembly APIs to boost productivity and accuracy"
      button_net:
        enable: true
        link: "assembly/net"
      button_java:
        enable: true
        link: "assembly/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-metadata-net.png?v2"
      name: GroupDocs.Metadata Product Family
      link: "metadata"
      content: "Organize documents with metadata within any cross platform application using GroupDocs metadata APIs to find, use, preserve and re-use data in future"
      button_net:
        enable: true
        link: "metadata/net"
      button_java:
        enable: true
        link: "metadata/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-search-net.png?v2"
      name: GroupDocs.Search Product Family
      link: "search"
      content: "Transform your document search process with this API for advance full text search capability into any existing or new cross platform application"
      button_net:
        enable: true
        link: "search/net"
      button_java:
        enable: true
        link: "search/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-parser-net.png?v2"
      name: GroupDocs.Parser Product Family
      link: "parser"
      content: "Parse, extract images, raw & formatted text with metadata and perform a lot of operations with it using APIs which work on all popular platforms and supported file formats"
      button_net:
        enable: true
        link: "parser/net"
      button_java:
        enable: true
        link: "parser/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-watermark-net.png?v2"
      name: GroupDocs.Watermark Product Family
      link: "watermark"
      content: "Watermark manipulation APIs for creating, removing, smart searching, edit locking, and performing other powerful operations across all popular platforms and supported file formats"
      button_net:
        enable: true
        link: "watermark/net"
      button_java:
        enable: true
        link: "watermark/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-editor-net.png?v2"
      name: GroupDocs.Editor Product Family
      link: "editor"
      content: "Manipulate multiple document formats using HTML with in your applications using GroupDocs.Editor APIs"
      button_net:
        enable: true
        link: "editor/net"
      button_java:
        enable: true
        link: "editor/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-merger-net.png?v2"
      name: GroupDocs.Merger Product Family
      link: "merger"
      content: "Build cross-platform applications that perform operations, such as, merging, splitting, shuffling, swapping, trimming, deleting of pages, slides & diagrams of supported formats"
      button_net:
        enable: true
        link: "merger/net"
      button_java:
        enable: true
        link: "merger/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-redaction-net.png?v2"
      name: GroupDocs.Redaction Product Family
      link: "redaction"
      content: "Build cross-platform applications that perform operations, such as, redacting, hiding, removing content and metadata from documents, presentations, worksheets and PDF files"
      button_net:
        enable: true
        link: "redaction/net"
      button_java:
        enable: true
        link: "redaction/java"

    # service item loop
    - image : "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/90x90/groupdocs-classification-net.png?v2"
      name: GroupDocs.Classification Product Family
      link: "classification"
      content: "Build custom applications to perform documents and text categorization operations using different taxonomies within your applications."
      button_net:
        enable: true
        link: "classification/net"
      button_java:
        enable: false
        link: "classification/java"
      
############################# call to action #################################
cta:
  enable : true
  # call to action content comes from "_index.md"
---