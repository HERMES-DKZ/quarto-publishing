---
title: "Getting started"
teaching: 0
exercises: 1
---

::::::::::::::::::::::::::::::::::::: questions

+ How do i open a new Quarto document?
+ What editing modes exist?
+ How do i switch between modes?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

+ Open a new Quarto document.
+ Switch between editing modes

::::::::::::::::::::::::::::::::::::::::::::::::

## Opening a Quarto Document

After installing the extension, two new options appear when creating a new file in VS Code: Quarto Document and Quarto Project.
A Quarto Document creates a single file, that can be used to create singular Documents such as a PDF.
A Quarto Project offers you the option to choose between several premade setups used to create more complex structures such as a blog, book or website.

As we are currently working on the very basics, we will choose the "Quarto Document" option when creating a new file.

After opening the new file, you should see the following:
![](https://pad.zdv.net/uploads/8dec0457-7757-46e6-949e-cbea52e682de.png)
The "empty" Documents only contain a small YAML header with generic information about title and format of the document.

## Visual and Source Mode

When working in a Quarto environment the user can decide if they wish to work in a visual or source code-based layout.
The visual layout offers an easy to navigate environment similar to the layout of programs like MSWord. The Markdown specific code chunks are hidden as to not confuse the user.
The source layout lacks the visual interface but includes the underlying markdown code of the document.

[Picture Source Mode] [Picture Visual Mode]

Neither of the two environments are inherently better then the other. We will be working with both the source and the visual layout of Quarto. You will be shown the correct ways of selecting the needed options in the visual interface and how to write the needed code in the source code of the document.

:::::::::::::::::::::::::::::::::::::: callout

You can easily switch between the two editing modes by right clicking on your screen and selecting "Edit in Visual/Source Mode". This will instantly switch you over. In this Lesson we will continue to work with Source Mode.
![](https://pad.zdv.net/uploads/d708a000-4732-4942-9389-f30bb79583fa.png)

::::::::::::::::::::::::::::::::::::::::::::::::

## Rendering Your document

To render your document and see its final look, you need to click the "Preview" Button on the top right side of the screen:
![](https://pad.zdv.net/uploads/c836fe29-e267-449d-a6b6-4ffffda8dc28.png)
Alternatively can use Ctrl+Shift+K.

This will have two effects:
1. It will create a new file in your "Quarto-Lesson" folder, corresponding to your chosen format. ![](https://pad.zdv.net/uploads/a2c11153-53a8-45c5-b101-113a2c489229.png)
2. It will split your screen and show you your preview on the right side of VSCode. ![](https://pad.zdv.net/uploads/301d36e7-af93-4a55-9eef-b8de7f00921b.png)

::: challange
#### Exercise:
Create a new folder called "Quarto_lesson" and open it in VSCode. Open a new Quarto document in VSCode and save it in your newly created folder.
:::


