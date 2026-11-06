Pagespeed.web.dev Passes Audits:

 - [aria-hidden="true"] is not present on the document \<body\>
    - Makes auto-reader's more consistant 
 - Image elements have [alt] attributes
    - Images have short descriptions of their content in attributes
 - [user-scalable="no"] is not used in the \<meta name="viewport"\> element and the [maximum-scale] attribute is not less than 5.
    - Allows for magnification 
 - Background and foreground colors have a sufficient contrast ratio
    - Makes text readable 
 - Document has a \<title\> element
    - Title gives screen readers a overview description
 - \<frame\> or \<iframe\> elements have a title
    - Screen reader users rely on frame titles for content descriptions
 - \<html\> element has a [lang] attribute
    - Tells screen reader the text language 
 - \<html\> element has a valid value for its [lang] attribute
    - Tells screen reader the text language
 - Links have a discernible name
    - Link and alt text have discernible and unique names
 - Lists contain only \<li\> elements and script supporting elements (\<script\> and \<template\>).
    - Screen readers have a specific way of announcing lists
 - List items (\<li\>) are contained within \<ul\>, \<ol\> or \<menu\> parent elements
    - Screen readers have a specific way of announcing lists
 - Touch targets have sufficient size and spacing.
    - Buttons are large
 - Heading elements appear in a sequentially-descending order
    - Makes it easier to navigate and understand when using assistive technologies
 - Document has a main landmark.
    - One main landmark helps screen reader users navigate a web page   


    ![alt text](Images\image.png)