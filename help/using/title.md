---
title: Title Component
seo-title: Title Component
description: null
seo-description: The Core Component Title Component is a section heading component that features in-place editing.
uuid: cf190861-e5cd-42b8-9193-842b8df8c5c6
contentOwner: User
content-type: reference
topic-tags: authoring
products: SG_EXPERIENCEMANAGER/CORECOMPONENTS-new
discoiquuid: 243efc75-fcf9-427d-9303-9642b0602991
index: y
internal: n
snippet: y
---

# Title Component{#title-component}

The Core Component Title Component is a section heading component that features in-place editing.

## Usage {#usage}

The Title Component is intended to be used as the title or heading of a section of content. The available heading levels can be defined by the template author in the [design dialog](#design-dialog). The content editor can select from available headings levels in the [edit dialog](#edit-dialog). For added convenience, simple in-place editing of the heading text is also available.

## Version and Compatibility {#version-and-compatibility}

The current version of the Title Component is v2, which was introduced with release 2.0.0 of the Core Components in January 2018, and is described in this document.

The following table details all supported versions of the component, the AEM versions with which the versions of the component is compatible, and links to documentation for previous versions.

|Component Version|AEM 6.3|AEM 6.4|AEM 6.5|
|---|---|---|---|
|v2|Compatible|Compatible|Compatible|
|[v1](title-v1.md)|Compatible|Compatible|Compatible|

For more information about Core Component versions and releases, see the document [Core Components Versions](versions.md).

## Sample Component Output {#sample-component-output}

To experience the Title Component as well as see examples of its configuration options as well as HTML and JSON output, visit the [Component Library](http://opensource.adobe.com/aem-core-wcm-components/library/title.html).

### Technical Details {#technical-details}

The latest technical documentation about the Title Component [can be found on GitHub](https://github.com/adobe/aem-core-wcm-components/blob/master/content/src/content/jcr_root/apps/core/wcm/components/title/v2/title).

Further details about developing Core Components can be found in the [Core Components developer documentation](developing.md). 

## Edit Dialog {#edit-dialog}

The edit dialog allows the content author to define the title text as well as select the heading level.

* **Title** - If empty the page title will be used
* **Type / Size** - Defines the heading level of the title
* **Link** - Defines the content to which the title will link. This can be a path to a content page, an external URL, or a page anchor.

![](assets/screenshot_2018-10-19at110055.png)

>[!CAUTION]
>
>The ability to define a link for the title was introduced with release 2.2.0 of the Core Components.

The in-place editor can also be used to edit the text of the title component.

![](assets/chlimage_1-37.png) 

## Design Dialog {#design-dialog}

The design dialog allows the template author to define the default heading level that title components will have when created by the content authors.

### Sizes Tab {#sizes-tab}

![](assets/screenshot_2018-10-19at110120.png)

* **Allowed Types / Sizes for Authors** - Enable or disable heading types that will be available for content authors when they use the Title Component.
* **Default Type / Size**- Define the heading type that will be automatically assigned when a content author adds the Title Component to a page.
* **Disable Link**- Disable support for links in the title component to disallow content authors from linking from titles.

>[!CAUTION]
>
>The ability to define a link for the title was introduced with release 2.2.0 of the Core Components.

### Styles Tab {#styles-tab}

The Title Component supports the AEM [Style System](authoring.md#component-styling).