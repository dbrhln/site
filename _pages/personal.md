---
layout: page
permalink: /personal/
title: personal
description: Apart from research, I am always happy to talk about baking, crochet, books, and travel.
nav: true
order: 5
---



### Books
I am currently reading:
* *Gottland* by Mariusz Szczygiel
* *In the Presence of Absence* by Mahmoud Darwish
* *Stories of Your Life and Others* by Ted Chiang
* *Wine and War* by Don and Petie Kladstrup

I am also working on a Python script to automatically extract titles from images of books and write them to a database to easily create and maintain a personal catalogue. The script pre-processes the image (grayscale, thresholding, canny edge detection), determines where the boundaries of each book are using Hough Transform, and the boundaries are used to slice the image into separate books as shown below. This will then be passed through pyTesseract to extract the book titles. The idea is to then use the Google Books API to search the extracted titles and retrieve the book's full information.

<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/books-process.png' | relative_url }}" alt="" title="example image"/>
    </div>

    <div class="col-sm-3 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/book-slicing.gif' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Image processing and segmentation on a test image.
</div>


### Baking

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/baking-cheesecake.jpg' | relative_url }}" alt="Cheesecake with edible violets" title="Cheesecake with edible violets"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/baking-baguette.jpg' | relative_url }}" alt="" title="Demi baguettes"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/baking-carrot.jpg' | relative_url }}" alt="" title="Carrot cake"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/baking-bonbons.jpg' | relative_url }}" alt="" title="White chocolate bon bons filled with a Thai tea ganache"/>
    </div>
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-3">
    <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/baking-caramels.jpg' | relative_url }}" alt="" title="Salted butter caramels"/>
  </div>
    <div class="col-sm mt-3 mt-md-3">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/baking-tangyuan.jpg' | relative_url }}" alt="" title="Tang yuan filled with black sesame paste"/>
    </div>
    <div class="col-sm mt-3 mt-md-3">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/baking-ondeh.jpg' | relative_url }}" alt="" title="Ondeh Ondeh (sweet pandan glutinous rice balls filled with molten gula melaka)"/>
    </div>
    <div class="col-sm mt-3 mt-md-3">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/baking-1830smincepie.jpg' | relative_url }}" alt="" title="Mince pies with lemon mincemeat made from a recipe from the 1830s"/>
    </div>
</div>
<div class="caption">
  A selection of my baking (and cooking).
</div>

<br/>
### Crochet

<div class="row">
    <div class="col-sm mt-6 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/crochet-1.jpg' | relative_url }}" alt="" title=""/>
    </div>
    <div class="col-sm mt-6 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/crochet-2.jpg' | relative_url }}" alt="" title=""/>
    </div>
    <div class="col-sm mt-6 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/crochet-bunny.jpg' | relative_url }}" alt="" title=""/>
    </div>
</div>

<div class="caption">
    A selection of my crochet projects.
</div>

<br/>
