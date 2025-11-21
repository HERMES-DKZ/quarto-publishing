---
title: "An introduction to YAML headers"
teaching: 0
exercises: 1
---

::: questions 

- What is YAML?
- How to use a YAML header?
- What are the mnost useful Key-Value pairs for a scientofic paper?
  
:::

::: objectives

- Know what Key-Value pairs to use in a scientific paper.
- Know how to implement a detailled YAML header for a scientific paper.

:::

Many Quarto documents start with a so called YAML header. These headers contain fundamental information about the document and are used to concisely and easily configure metadata and appearance. While it is not necessary for the document to function, they are a useful way of integration metadata and appearance into your documents. 

YAML(short for "YAML Ain’t Markup Language") is a human readable data language most commonly used in configuration files. At its most rudimentary YAML uses easy to understand Key-Value pairs as a syntax.

----

In Quarto a YAML block is signified by three Dashes above and below the Code Block.
In order to integrate a YAML header into your document, you need to insert the following block at the top of your document and fill the space between the dashes with relevant Key-Value pairs. 
Keys relevant for format and appearance will be shown in the relevant episodes!

::: Callout
A Key-Value pair is created by pairing a predetermined key (such as name, title, date etc.) with a corresponding value. Sub-categories are created by in indenting the line with Tab.
:::

::: callout
### Example of a simple YAML header

    ```{yaml}
    title: Example
    format: html
        toc: true
    ```
:::

::: callout

#### YAML Keys:

* `title:`               – Title of you paper/webpage/publication
* `format:`              – The format of your rendered document. There are a wide variety of formats to choose from. A detailed list can be found here: https://quarto.org/docs/output-formats/all-formats.html
* `toc:`                 – **Toc:true** creates a simple table of contents for your website. the Heading you created via '#' headings are used to create it.
:::


## YAML hearders for scientific publishing

In the following example you can see an assortment of YAML pairs, which are commonly used for the implementation of metadata in scientific articles.
These pairs can contain a wide variety of information about the paper, its authors and its place of origin, as well as information on copyright, funding and other legal characteristics.
Note that not all of the pairs are necessary, and many can be cut if they are not needed or available.


    ```{yaml}
    ---
    title: How to write a YAML header
    format: pdf
    subtitle: An easy Guide with a good example
    date: 2025-08-01
    type: education
    authors:
        - name: John Doe
          id: jd
          orcid: 0000 0000 0000 0000
          email: john.doe@example.com
          url: author-website.com
          degrees: Bachelor of Arts
          role: concept
          affiliation:
              - name: Example University
                city: Towncity
                region: Arearegion
                Country: Countryland
                url: univerity-website.com
        - name: Jane Public
          id: jp
          orcid: 1111 2222 3333 4444
          email: jane.p@example.com
          url: janesawesomewebsite.net
          degrees: M.o.S.
          role: visuals
          affiliation:
              - name: XYZ Collage
                city: Villageville
                region: Random County
                Country: Republic of Example
                url: collage-page.com
    abstract: |
        A concice and easy to read abstract.
    keywords:
    - Example
    - Quarto
    - YAML
    - Headers
    
    license: "CC BY ND"
    copyright: 
      holder: John Doe
      year: 2025
    funding: If your research was funded it can be written here.
    ---
    ```

::: callout

### YAML Keys

* `title:`               – Title of you paper/webpage/publication
* `subtitle:`            – Possible subtitle or clarification
* `date:`                – Publishing date
* `type:`                – Type of publication. May use EPUB Publication Types or free strings
* `author:/authors:`     – Names and informations on the author or authors. Can be clarified through sub categories.
* `name:`                – Name of an author or institution
* `id:`                  – Identifier used to refer the author in other fields
* `orcid:`               – Creates a link to the author’s "Open Researcher and Contributor ID" (ORCID).  
* `email:`               – Email adress of person or institution.
* `url`                  – Associated website of person or institution
* `degree:/degrees:`     – Authors dregrees
* `affiliation`          – Affiliatiated institution. Can be clarified through sub categories
* `city/region/country:` – Name of corresponding geographic entity
* `abstract`             – Abstract of the publication
* `keywords`             – Keywords of the publication, can be more or less detailled
* `license`              – A license can be either specified through a string or by inserting a Creative Commons abbrevation
* `copyright`            – Copyright holder.  Can be clarified through sub categories
* `holder`               – Name of the copyright holder
* `year`                 – Year of the copyright
* `funding`              – If the publication received funding it can be mentioned here

:::

::: challenge
### Exercise
Try to create a detailed YAML header for your document and render it again to see the difference.
:::

::: solution
### A possible Outcome:
Your newly rendered document could look like this:
![](https://pad.zdv.net/uploads/0f91830e-465b-4ac4-b6e8-93637d207d2c.png)
:::


