author: Joyce
id: sample
summary: This is a sample Postman Guide
categories: Getting-Started
environments: web
status: Hidden
feedback link: https://github.com/loopDelicious/pmquickstarts
tags: Getting-Started, Developer, Tester, Automation

# Postman Guide Template

<!-- ------------------------ -->

## Overview

Duration: 1

Please use [this markdown file](https://raw.githubusercontent.com/loopDelicious/pmquickstarts/master/site/pmguides/src/sample/sample.md) as a template for writing your own Postman Quickstarts. This example guide has elements that you will use when writing your own guides, including: code snippet highlighting, downloading files, inserting photos, and more.

It is important to include on the first page of your guide the following sections: Prerequisites, What you'll learn, What you'll need, and What you'll build. Remember, part of the purpose of a Postman Guide is that the reader will have **built** something by the end of the tutorial; this means that actual code may need to be included (not just pseudo-code).

The rest of this Postman Guide explains the steps of writing your own guide.

### Prerequisites

- Familiarity with Markdown syntax

### What You’ll Learn

- how to set the metadata for a guide (category, author, id, etc)
- how to set the amount of time each slide will take to finish
- how to include code snippets
- how to hyperlink items
- how to include images

### What You’ll Need

- A [GitHub](https://github.com/) Account
- [VSCode](https://code.visualstudio.com/download) Installed
- [NodeJS](https://nodejs.org/en/download/) Installed
- [GoLang](https://golang.org/doc/install) Installed

### What You’ll Build

- A Postman Guide

<!-- ------------------------ -->

## Metadata Configuration

Duration: 2

It is important to set the correct metadata for your Postman Guide. The metadata contains all the information required for listing and publishing your guide and includes the following:

- **summary**: This is a sample Postman Guide
  - This should be a short, 1 sentence description of your guide. This will be visible on the main landing page.
- **id**: sample
  - make sure to match the id here with the name of the file, all one word.
- **categories**: data-science
  - You can have multiple categories, but the first one listed is used for the icon.
- **environments**: web
  - `web` is default. If this will be published for a specific event or conference, include it here.
- **status**: Published
  - (`Draft`, `Published`, `Deprecated`, `Hidden`) to indicate the progress and whether the pmguide is ready to be published. `Hidden` implies the pmguide is for restricted use, should be available only by direct URL, and should not appear on the main landing page.
- **feedback link**: https://github.com/loopDelicious/pmquickstarts
- **tags**: Getting Started, Data Science, Twitter
  - Add relevant tags to make your pmguide easily found and SEO friendly.
- **authors**: Joyce Lin
  - Indicate the author(s) of this specific pmguide.

---

You can see the source metadata for this guide you are reading now, on [the github repo](https://raw.githubusercontent.com/loopDelicious/pmquickstarts/master/site/pmguides/src/sample/sample.md).

<!-- ------------------------ -->

## Creating a Step

Duration: 2

A single Postman Quickstart consists of multiple steps. These steps are defined in Markdown using Header 2 tag `##`.

```markdown
## Step 1 Title

Duration: 3

All the content for the step goes here.

## Step 2 Title

Duration: 1

All the content for the step goes here.
```

To indicate how long each step will take, set the `Duration` under the step title (`##`) to an integer. The integers refer to minutes. If you set `Duration: 4` then a particular step will take 4 minutes to complete.

The total Postman Quickstarts completion time is calculated automatically for you and will be displayed on the landing page.

<!-- ------------------------ -->

## Code Snippets, Info Boxes, and Tables

Duration: 2

Look at the [markdown source for this pmguide](https://raw.githubusercontent.com/loopDelicious/pmquickstarts/master/site/pmguides/src/sample/sample.md) to see how to use markdown to generate code snippets, info boxes, and download buttons.

### JavaScript

```javascript
{
  key1: "string",
  key2: integer,
  key3: "string"
}
```

### Java

```java
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```

### Info Boxes

> aside positive
> This will appear in a positive info box.

> aside negative
> This will appear in a negative info box.

### Buttons

<button>
  [This is a button](https://link.com)
</button>

[![Run in Postman](_shared_assets/button.svg)](https://god.gw.postman.com/run-collection/1559645-032fb22a-9afb-4c56-b8f0-4042db96a4f3?action=collection%2Ffork&collection-url=entityId%3D1559645-032fb22a-9afb-4c56-b8f0-4042db96a4f3%26entityType%3Dcollection%26workspaceId%3D7a8604d2-6966-4313-8b07-282d2ba5501c)

### Tables

<table>
    <thead>
        <tr>
            <th colspan="2"> **The table header** </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>The table body</td>
            <td>with two columns</td>
        </tr>
    </tbody>
</table>

### Hyperlinking

[Youtube - Halsey Playlists](https://www.youtube.com/user/iamhalsey/playlists)

<!-- ------------------------ -->

## Images, Videos, and Surveys, and iFrames

Duration: 2

Look at the [markdown source for this guide](https://raw.githubusercontent.com/loopDelicious/pmquickstarts/master/site/pmguides/src/sample/sample.md) to see how to use markdown to generate these elements.

### Images

![Postman illustration](assets/SAMPLE.jpg)

### Videos

Videos from youtube can be directly embedded:
<video id="tw7x3yBpU1Y"></video>

### Inline Surveys

<form>
  <name>How do you rate yourself as a user of Postman?</name>
  <input type="radio" value="Beginner">
  <input type="radio" value="Intermediate">
  <input type="radio" value="Advanced">
</form>

### Embed an iframe

![https://codepen.io/MarioD/embed/Prgeja](https://en.wikipedia.org/wiki/File:Example.jpg "Try Me Publisher")

<!-- ------------------------ -->

## Conclusion

Duration: 1

At the end of your Postman Guide, always have a clear call to action (CTA). This CTA could be a link to the docs pages, links to videos on youtube, a GitHub repo link, etc.

If you want to learn more about Postman Guide formatting, checkout the official documentation here: [Formatting Guide](https://github.com/googlecodelabs/tools/blob/master/FORMAT-GUIDE.md)

### What we've covered

- creating steps and setting duration
- adding code snippets
- embedding images, videos, and surveys
- importing other markdown files
