---
title: L.esri.Services.ImageService
layout: documentation.hbs
---

# {{page.data.title}}

Inherits from [`L.esri.Service`]({{assets}}api-reference/services/service.html)

`L.esri.Services.ImageService` is an abstraction interacting with Image Services running on ArcGIS Online and ArcGIS server that allows you to make requests to the API, as well as query and identify features on the service.

### Constructor

<table>
    <thead>
        <tr>
            <th>Constructor</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><code class="nobr">new L.esri.Services.ImageService({{{param 'String' 'url'}}}, {{{param 'Object' 'options'}}})</code><br><br><code class="nobr">L.esri.Services.imageService({{{param 'String' 'url'}}}, {{{param 'Object' 'options'}}})</code></td>
            <td>The `url` parameter is the URL to the ArcGIS Server or ArcGIS Online map service you would like to consume.</td>
        </tr>
    </tbody>
</table>

### Options

`L.esri.Services.ImageService` accepts all [`L.esri.Services.Service`]({{assets}}api-reference/services/service.html) options.

### Events

`L.esri.Services.ImageService` fires all  [`L.esri.Services.service`]({{assets}}api-reference/services/service.html) events.

### Methods

No methods.

### Example

No examples.