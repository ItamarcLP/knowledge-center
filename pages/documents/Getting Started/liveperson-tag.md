---
pagename: LivePerson Tag
categoryName: Getting started
subCategoryName: ''
indicator: both
subtitle: Add the LivePerson to your website to enable messaging or chat
level3: ''
permalink: getting-started-liveperson-tag.html
isTutorial: false
date: 2019-01-16 18:52:21 +0200

---
To use the LiveEngage web chat or web messaging channels, place the LiveEngage Monitor Tag on your website. The tag will allow you to recognize and monitor visitors as they browse around your site. This enables you to engage with visitors based upon real-time behaviors and maintain continuous conversations with visitors as they browse.

The LiveEngage Tag consists of a small, lightweight piece of code that opens the door for all of the built-in functionality of the web chat and web messaging communication channels. The tag loads asynchronously, so it will not affect initial page load.

The LiveEngage Tag should be embedded in each page of your website. If it is not, conversations can end without warning and targeted invites may not trigger.

## Included Functionality

The default functionality offered by dynamically-loaded taglets is described below:

* Monitoring taglet: Monitors your visitors in order to offer them campaigns and collect data about their journey.
* Engagements taglet: Draws your engagements on the pages, allowing you to connect with visitors or help point them to relevant parts of your site.
* Unified Chat Window bootstrap: Our embedded engagement window allows your visitors to connect with agents

**Notes:**

* Taglets are small programs, managed by LivePerson, that are used to add functionality to your website. The specific taglets brought to the page on your website depend on your LivePerson account and the version of LiveEngage you use.
* All of the above taglets contain the minimum code needed to start the applications.
* Code is loaded dynamically afterwards, based on user actions.

## Getting your tag

![](/img/LP tag.gif)

To obtain the LivePerson tag for your account, login with admin credentials and pull down the menu under your user name > select LiveEngage tag.

## Deploying your tag

  
The tag will most likely be added to your website by your development team, or someone in charge of updating your web pages.

The tag should be included into the <head> of all web pages. 

If the tag is included via an external javascript file, it should look like the following:

<script type="text/javascript" src="/le-mtagconfig.js"></script>

  
Follow these guidelines:

* Add to every page of your website (this does not mean that the button will display on every page, but it is important for integrity of the user experience) 
* The code should be included as high up in the <head> element as possible.
* If the tag is included a javascript file, be sure to omit the <script> tag and <!-- HTML comments →
* For mobile compatibility, ensure that the <head> of your web pages includes the following meta tag: <meta name="viewport" content="width=device-width, initial-scale=1.0,minimum-scale=1.0, maximum-scale=1.0, user-scalable=no"/>
  * The minimum tag required is the following: <meta name="viewport" content="width=device-width>

## Using the LivePerson Tag with a tag management system

Tag management systems are incorporated to make smart decisions about when to fire each tag, for example on a visitor’s first visit, or when a specific page is visited. Generally, fewer tags means less load, and therefore a reduction in the chances of an error. Typically today, all tags are fired asynchronously, removing a large part of site load time.

  
While the use of a tag management system is not necessary to enjoy the functionality of LiveEngage, many of our customers have experienced success using tag management Systems.

  
{: .notice}
Note: Using a tag management system can cause a delay in loading of engagements if the LivePerson Tag is loaded after many other tags. To ensure a short loading time, we recommend placing the LiveEngage Tag as high up in the loading sequence as possible.

  
Fore more technical details on the tag, visit the [developers community](https://developers.liveperson.com/le-tag-overview.html).