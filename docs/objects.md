---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Objects
description: Learn about shapes that Lunacy provides
icon: 'ungroup-objects'

# Micro navigation
micro_nav: false

# Page navigation
page_nav:
    next:
        content: Text
        url: '/text'
    prev:
        content: Editing
        url: '/editing'
---

## Shortcuts for the Tools

Lunacy supports the typical tools for any vector editor.

<table>
  <thead>
    <tr>
      <th>Object</th>
      <th>Keyboard shortcut</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Text</td>
      <td><code>T</code></td>
    </tr>
    <tr>
      <td>Rectangle </td>
      <td><code>R</code></td>
    </tr>
    <tr>
      <td>Oval</td>
      <td><code>O</code></td>
    </tr>
    <tr>
      <td>Line</td>
      <td><code>L</code></td>
    </tr>
    <tr>
      <td>Bitmap</td>
      <td><code>P</code></td>
    </tr>
    <tr>
      <td>Avatar</td>
      <td><code>Ctrl</code> <code>P</code></td>
    </tr>
    <tr>
      <td>Artboard</td>
      <td><code>A</code></td>
    </tr>
  </tbody>
</table>


Let’s review some of these tools in more detail.

## Text

You can add text by choosing the Text tool from the Shapes and Objects toolbar (or press `T`). The pointer changes to the Text Input tool icon and then you can click anywhere in the Canvas to insert your text layer at that point. When you click on a canvas, a new text layer will be inserted with a “Type something” placeholder, ready for you to add your text.

{:.is-big}
![Adding text](public/objects_adding_text.png)

{:.image-info}
Text tool in action

When you have a text layer selected you will notice that the Inspector changes to show you all the properties that apply to text. For details about working with text in Lunacy, click [here](https://docs.icons8.com/text/).

## Squares, Circles, Straight Lines

If you need a square, choose the Rectangle tool and hold `Shift` while drawing. You easily can create other primitives as well.

{:.is-big}
![Adding primitives](public/objects_adding_primitives.gif)

{:.image-info}
Basic primitive objects

## Bitmaps

Bitmaps, or images are one of the object types that are supported in Lunacy. Bitmaps, (or raster) images are made up of pixels; those images can take many forms, such as screenshots or photographs. Lunacy supports all the most common image formats, like PNG, JPG, JPEG.

{:.is-big}
![Adding bitmaps](public/objects_bitmaps.gif)

{:.image-info}
Image tool will help you to insert bitmap graphic into your designs

## Avatar Tool

When designing user interfaces, one of the most common tasks is creating avatars. This time consuming process is easy with Lunacy, as it has a tool specifically for this. The avatar tool lets you create them in one click.

{:.is-big}
![Create an avatar in one click](public/objects_avatars.png)

{:.image-info}
Image tool will help you to insert bitmap graphic into your designs

## Masks

The masks (keyboard shortcut `Ctrl` `M`) in Lunacy are used to show parts of objects selectively. For example, masking two overlapping ovals gives you an oval image.

{:.is-big}
![How masks works](public/objects_masks.png)

{:.image-info}
Masking objects

## Boolean Operations

Using boolean operations, you can easily draw complex shapes using primitives.

* Union: The result is a vector that is the sum of both vectors’ areas.
* Subtract: The result is a vector where the area of the top shape is removed from the one under it.
* Intersect: The result is a vector consisting of the parts where the original shapes overlapped.
* Difference: The result is a vector that is exactly the part where they didn’t overlap. It’s the inverse of an intersect operation.

{:.is-big}
![How boolean operations works](public/BoolOps.gif)

Also, Lunacy has a Flatten selection operation: The result is a vector that represents the multiple paths inside the shape as one path. However, there are many paths that can’t be flattened into one. A shape with a hole inside it will always represent as two paths; one for outer path, and one for the inner path.

{:.is-big}
![How flatten selection works](public/Flatten.gif)