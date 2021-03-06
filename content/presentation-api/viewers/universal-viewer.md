---
title: "Universal Viewer"
date: 2018-04-15T14:50:54-04:00
weight: 10
---

## View Our Example Manifest

To view our example manifest either look at the embedded viewer below or use the Universal Viewer demo.

## Embedded Viewer

We've also embedded the UV demo here pointing to our local manifest.

{{% notice note %}}
Note: If you don't already have a local web server and a manifest at http://localhost:3000/manifest.json then this embed won't work.
{{% /notice %}}

{{< uv "http://localhost:3000/manifest.json" >}}

<!-- #todo:230 Consider adding either an image with what UV ought to look like at this point or include another embed that points to the manifest we've created served up from this gitbook. -->

## Using the Universal Viewer Demo

Universal Viewer home page: http://universalviewer.io/

Open the Universal Viewer site and go to the "[View a IIIF Manifest](http://universalviewer.io/#view)" demo, enter in the URL as http://localhost:3000/manifest.json and click "view". If you know of other manifests you can enter those here too.

You can also go directly to this URL to launch the UV demo with the manifest we've created:

http://universalviewer.io/uv.html?manifest=http://localhost:3000/manifest.json

## Exercises and Questions

<!-- #backlog:230 Add exercises and questions around UV -->

- How do you see metadata about the resource?
- How can you download a copy of this image?
- How would you embed the view of this resource in another page?
- How can you make the viewer go full screen?
