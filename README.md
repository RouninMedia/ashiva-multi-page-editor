# Ashiva Find and Replace Tools v1

**Ashiva Find and Replace Tools v1** is a suite of standalone **Single Page App (SPA)** tools used to update any site using an **Ashiva WebRig**.

 - the **Ashiva MultiPage Editor** is an **SPA** which finds and replaces text across *multiple Pages*
 - the **Ashiva Scaffold Editor** is an **SPA** which finds and replaces text across *multiple Scaffolds*
 - the **Ashiva PageManifest Editor** is an **SPA** which creates, reads, updates and deletes entries on any *PageManifest*
 - the **Ashiva SiteManifest Editor** is an **SPA** which creates, reads, updates and deletes entries on any *SiteManifest*

## What SPA Framework do the Ashiva Find and Replace Tools v1 use?

**Ashiva Find and Replace Tools v1** are **SPAs** built using the **Reflective SPA** (or **veSPA**) model of *SPA Architecture*.

A **veSPA** app resides in a single document and conforms to *most* (but not *all*) conventional definitions of a **Single Page App (SPA)**.

**veSPA** parts company with a conventional **SPA** architecture models in that:

 - rather than a single page load at the start, the SPA may reload itself repeatedly in response to user interaction
 - rather then being rendered by JS, the SPA's `views` are largely (if not, entirely) determined via CSS
 - it follows that there is little to zero Client-Side DOM Rendering (`CSR`) - in fact, arguably **all** of the DOM Rendering is Server-Side
 - the app depends on server-side scripting with filesystem functionality like `PHP` and, consequently, it ***must*** be hosted on a remote server. The SPA cannot be run locally at all (and certainly not *offline*)

The ***major advantage*** of the **veSPA** model is that it enables the **SPA** to run, easily, not only:

 - client-side scripts in `JS`

***but also:***

 - server-side scripts in `PHP`

## Anything else?

Yes. A major innovative feature of the **Ashiva Find and Replace Tools v1** is that the `URL queryString` *always* describes the **entire current state** of each app.

This means that:

 - the `URL` can be bookmarked at any point and when the bookmark is clicked later, the former state of the app will be precisely reproduced
 - the browser's reload button may be pressed at any point without any visible change to the view the app is currently displaying


## What technologies do the Ashiva Find and Replace Tools v1 use?
Each of the four **veSPA** *Single Page Apps* includes the following technologies:

 - `PHP`
 - `HTML5`
 - `CSS3`
 - `Javascript ES2015+`
 - `JSON`
 - `SVG` (in the favicon and in CSS `background-images`)
