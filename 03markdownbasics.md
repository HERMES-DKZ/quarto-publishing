---
title: "Markdown Basics"
teaching: 0
exercises: 1
---

::: questions 

- What is Markdown?
- How do you use Markdown to write in Quarto?
- What are the most common parts of Markdown syntax?
  
:::

::: objectives

- Know the basic Markdown syntax.
- Know how to write a simple text, containing a variety of Markdown syntax.

:::

In order to use the source mode of Quarto, one needs to be able to write a document using the Markdown programming language. 
The relative simplicity and straightforardness of Markdown makes it one of the ideal programming languages for beginners. It is use by a variety of programms and exists in the background of most modern text based programms.
For example, this page is based on Markdown as well!
Markdown is designed as a simple and easy to understand programming language. As such there are only a few key features the user needs to know to create basic syntax in Markdown.

Rhese features contain some of the most common elements of written texts, such as tables, links and footnotes. But also features used to visually improve your text with features such as bold or italicised writing, horizontal lines for textseperation or differently sized headers.
The implementation of picrtures is also possible to implement pictures in Markdown.
Some of the most useful parts of Markdown syntax are shown here:

<div>
  <body>
    <table style="width:80%">
      <tr>
        <th>Effect/Formatting Element</th>
        <th>Markdown Syntax</th>
        <th>Frontend Appearence</th>
      </tr>
      <tr>
        <td>Normal text</td>
        <td>Text</td>
        <td>Text</td>
      </tr>
      <tr>
        <td> Headings</td>
        <td># Heading 1<br><br> ### Heading 3</td>
        <td><h1>Heading 1 </h1><br><h3>Heading 3 </h3></td>
      </tr>
          <tr>
        <td>Styles</td>
        <td>**Bold**<br>*Italics*</td>
        <td><b>Bold</b><br>
    <i>Italic</i></td>
      </tr>
      </tr>
          <tr>
        <td>Code</td>
        <td>`Code`</td>
        <td><code >Code</code></td>
      </tr>
      </tr>
          <tr>
        <td> Codeblock (Python)</td>
        <td>```{Python}<br>Codeblock:True<br>print("Hello World")<br>```</td>
        <td><code class="language-python">Codeblock = True <br>print("Hello World")</code></td>
      </tr>
      </tr>
          <tr>
        <td> Table</td>
        <td>|  X  |  Y  |  Z  |<br>|---|---|---|<br>|  a  |  b  |  c  |<br>|  d  |  e  |  f  |</td>
        <td> 
            <table style="width:60%">
      <tr>
        <th>X</th>
        <th>Y</th>
        <th>Z</th>
      </tr>
      <tr>
        <td>A</td>
        <td>B</td>
        <td>C</td>
      </tr>
      <tr>
        <td>D</td>
        <td>D</td>
        <td>F</td>
      </tr>
            </table>
      </tr>
       </tr>
          <tr>
        <td> Footnote</td>
        <td>Lorem Ipsum[^1]<br><br>[^1]: Footnote</td>
        <td><p>Lorem Ipsum<a href="#footnote-1">[1]</a>.</p>
            <p id="footnote-1">[1]Footnote</p></td>
      </tr>
       </tr>
          <tr>
        <td> Image</td>
        <td>![Alternative Text](image.jpg)</td>
        <td><img src="https://picsum.photos/200" alt="Alternative Text"></td>
      </tr>
       </tr>
          <tr>
        <td> Link</td>
        <td> [Example](https://www.example.com)</td>
        <td><a href="https://www.example.com">Example</a></td>
      </tr>
         </tr>
          <tr>
        <td> Horizontal line</td>
        <td> ____ or ----</td>
        <td><hr></td>
      </tr>
    </table>
  </body>
</div>

::: challenge

### Exercise:

Use your newly aquired knowledge in Markdown to fill your still empty Quarto documents with text.
Try to use a variety of features stuch as pictures or line breaks, be creative!
:::

::: caution
### Some Help

Should you need some help with Markdown or want to deepen your understanding of this extremely usefull language, there are a plethora of websites aimed at helping newcomers learn all there is about Matkdown.
Websites like [MarkdownGuide](https://www.markdownguide.org/) offer a wide variety of guides, cheat sheets and help.
:::
