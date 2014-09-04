---
published: true
layout: page
title: Projects
permalink: /projects/
filename: projects.md
image:
  feature: header1024-4.png
  credit:
  creditlink:
---

<section id="table-of-contents" class="toc">
  <header>
    <h3>Contents</h3>
  </header>
<div id="drawer" markdown="1">
*  Auto generated table of contents
{:toc}
</div>
</section><!-- /#table-of-contents -->
The following is a listing of projects that ADIwg has sponsored.

###Project Metadata

In 2010, ADIwg adopted a set of common fields for use in exchanging discovery level information about the who, what, when and where of projects in Alaska. In order to expedite the exchange of information, these fields were mapped to an Extensible Markup Language (XML) schema [released in 2011](#project-metadata-standard-fgdc-inactive). Some agencies provide project information as static XML documents and others have implemented RESTful endpoints to facilitate access to updated information.

Due to the importance of data integration with our international partners, ADIwg chose to base future versions on the ISO 19115/19110 family of metadata standards.

####Project Metadata Standard (ISO)

The current version of ADIwg *Project* metadata has been mapped to ISO 19115/19110. Due to the complexity of the ISO standards, ADIwg chose simplify implementation by creating an ISO-compatible JSON standard. The JSON serves as a lightweight alternative for sharing metadata amongst ADIwg members. The [mdTranslator](#mdtranslator) application allows conversion to other formats for sharing with external partners.\\
\\
**More info**: Page under development.\\
<i class="icon-github"> </i> **GitHub**: [Project Metadata Standard (ISO) Github Repository](https://github.com/adiwg/project-metadata-iso)

####Project Metadata Standard (FGDC) [^inactive]

The original version of ADIwg *Project* metadata mapped many of the fields to the Federal Geographic Data Committee (FGDC) metadata standard and Keyhole Markup Language (KML) for spatial domain information.\\
\\
**More info**: Page under development.\\
<i class="icon-github"> </i> **GitHub**: [Project Metadata Standard (FGDC) Github Repository](https://github.com/adiwg/project-metadata-fgdc)

[^inactive]: This project has been deprecated in favor of the [ISO-based](#project-metadata-standard-iso) metadata standard.

***

####Data Metadata Standard

The ADIwg *Data* metadata standard has been mapped to ISO 19115/19110. Data metadata is also supported by an ISO-compatible JSON standard. The JSON serves as a lightweight alternative for sharing metadata amongst ADIwg members. The [mdTranslator](#mdtranslator) application allows conversion to other formats for sharing with external partners.\\
\\
**More info**: Page under development.\\
<i class="icon-github"> </i> **GitHub**: [Data Metadata Standard Github Repository](https://github.com/adiwg/data-metadata)

***

###mdTranslator

To support the JSON standard ADIwg is developing the mdTranslator, a software 'engine' that converts metadata in the ADiwg JSON structure to other metadata formats, including ISO 19115-2. While the mdTranslator's primary purpose is to transform metadata stored in the ADIwg JSON standard, the architecture of the translator allows for possible conversion between many other formats. The basic process is illustrated in the figure below:

<figure>
    <a href="http://www.adiwg.org/mdTranslator/images/translator_process.png"><img src="http://www.adiwg.org/mdTranslator/images/translator_process.png"></a>
    <figcaption>Overview of the translator process.</figcaption>
</figure>

The mdTranslator isolates metadata creators from the complexity, rigor, formatting, and terminology of the output standard - a significant benefit when the output is based on the ISO 19139 XML Schema.\\
\\
**More info**: [mdTranslator Project Page](/mdTranslator)\\
<i class="icon-github"> </i> **GitHub**: [mdTranslator Github Repository](https://github.com/adiwg/mdTranslator)

***

### ADIwg JSON Schemas
ADIwg has developed a set of JSON schemas to provide documentation and validation for project and data ADIwg JSON metadata.\\
\\
**More info**: Page under development.\\
<i class="icon-github"> </i> **GitHub**: [ADIwg JSON Schemas Github Repository](https://github.com/adiwg/adiwg-json-schemas)

***

[mdTranslator]: /mdTranslator
