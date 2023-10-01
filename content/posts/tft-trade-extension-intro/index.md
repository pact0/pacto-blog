---
title: "Tft Trade Extension Intro"
subtitle: ""
date: 2023-09-30T19:37:52+02:00
lastmod: 2023-09-30T19:37:52+02:00
draft: false
author: ""
authorLink: ""
description: ""
license: ""
images: []

tags: ["TFT Trade Extension", "The Forbidden Trove"]
categories: []

featuredImage: "header.jpg"
featuredImagePreview: ""

hiddenFromHomePage: false
hiddenFromSearch: false
twemoji: false
lightgallery: true
ruby: true
fraction: true
fontawesome: true
linkToMarkdown: true
rssFullText: false

toc:
  enable: true
  auto: false
code:
  copy: true
  maxShownLines: 50
math:
  enable: false
  # ...
mapbox:
  # ...
share:
  enable: true
  # ...
comment:
  enable: true
  # ...
library:
  css:
    # someCSS = "some.css"
    # located in "assets/"
    # Or
    # someCSS = "https://cdn.example.com/some.css"
  js:
    # someJS = "some.js"
    # located in "assets/"
    # Or
    # someJS = "https://cdn.example.com/some.js"
seo:
  images: ["installation.png", "extension-icon.png", "menu.png", "folder-example.png", "example-hh.png", "watchers.png"]
  # ...
---
Written guide how to install and use the TFT Trade Extension.

<!--more-->

This extension adds a bunch of functionality to the Path of Exile's trade website. This will be a short guide how to install and use this tool.

{{< admonition tip "Just in case you prefer to watch a video, here it is" false >}}
{{< youtube aHolo_zBJHA >}}
{{</ admonition >}}

## Installation

Depending on your browser go to the extension store and press the "Add to Browser" button
* [firefox](http://firefox.extension.tftrove.com)
* [chrome](http://chrome.extension.tftrove.com)

![Installation](installation.png "Installatoin")

After that you can head over to the [trade website](https://www.pathofexile.com/trade/search). You can see a a small icon.

![Extension Icon](extension-icon.png "Extension Icon")

## Usage
When you click it a gui will be opened. You will be presented with a couple sections:
* Searches
* Watchers
* Live
* Prices
* Options

![Menu](menu.png "Menu")


### Searches
This section gives you the ability to store bookmarks and organize them in multiple folders.

![Folders](folder-example.png "Folder Example")

#### Creating a bookmark
To create a folder you just press the **Add Folder** button. After that you can click **Add Current Search** to save currently opened query to the folder.


#### Bookmark options
Each folder and a search has a dropdow menu. Click the **three dot icon** to reveal it.

![Folder Menu](folder-menu.png "Folder Dropdown Menu")

{{< admonition note "What do these do?" >}}
* Rename
* Change image - you can change the folder's icon
* Add a subfolder - it creates a nested subfolder
* Import into this - this allows you to import a folder a multiple folders as a nested structure inside this folder
* Export this folder - generates export string which can be shared with friends or treated as a backup
* Set League on All contained searches - sets the league on which contained searches will be opened in
* Delete
{{< /admonition >}}


![Search Menu](search-menu.png "Search Dropdown Menu")

{{< admonition note "What do these do?" >}}
* Ancestor - currently selected league for this search
* Change League - change league for this particular search
* Replace With Current Search - overwrite listing with currently opened one
* Live Search - open as live search
* Add to Live Search Manager - adds to [Live Search Manager](#live-search-manager)
* Rename 
* Delete
{{< /admonition >}}

{{< admonition tip "DnD" >}}
You can also drag and dop these saved searches and folders and organize your stuff. 
To activate the drag mode just press and hold on either folder header or a search. You can also move searches across folders.
{{< /admonition >}}


### Watchers

This section allows you to have a list of desired items constantly get updated with their status. 

#### Adding Items to Watchers Menu
You add an item here and whenever the seller comes online/offline/afk or the price changes you will know. You can add an item to this manager by clicking the **eye icon** 

![Example Item](example-hh.png "Example HH Listing")

#### Enabling the feature
To enable the this feature you need to press **Not Watching** to start the watcher. You also have the option to toggle **Always Watching** to only watch when the trade website is opened.

You can also unclick the square box next to item's name to stop watching it. You can rename the listing and unfold it.

![Watchers](watchers.png "Example Watchers Menu")

The items will automatically get updated every couple minutes. You can also click **Click Here** to update the watchers manually.

#### How to read the menu
These listings are color coded
* Green - Seller is *Online*
* Yellow - Seller is *AFK*
* Gray - Seller is *Offline*
* Red - Item is *unavailable*


### Prices

Prices menu fetches the prices from [poe.ninja](https://poe.ninja) and displays them in the extension. You can also check out the Divine to Chaos ratio quickly. 

![Prices](prices.png "Prices Menu")
