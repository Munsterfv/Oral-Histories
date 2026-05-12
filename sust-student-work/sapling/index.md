---
title: Mark Robertson - Loose Leaf Farm
author: Fred Gibbs
layout: scrollstory
date: 2025-07-21
header-image: images/white-text-loose-leaf-farm.png
thumbnail: images/loose-leaf-farm.png
summary: Our Sapling essay uses a few more features than our Seed essay, including the simplest scrolly box.
header-title:
header-position: 0px
toc-section: second
geo: [41.240000, -81.550000]
placename: Cuyahoga Valley National Park
tags:
    - history
    - nature
---

# Introduction

Mark Robertson is a 49 year old veteran of the United States Navy who has been farming in Albuquerque’s North Valley for the past 10 years. Alongside his wife, Sarah, Mark runs two small farming spaces where they grow produce for CSA members, farmers markets, and local restaurants such as Campo at Los Poblanos and Farm & Table. Even though Mark did not grow up farming, his background in engineering and biology has shaped the way he farms today. A lot of what he knows came from reading, experimenting, and learning through experience out in the field.


## From the Navy to Farming
{% include images/figure.html
class="right"
width="48%"
caption="Mark Robertson holding freshly harvested garlic at one of the farming spaces he and his wife Sarah manage in Albuquerque’s North Valley."
image-path="images/happy-mark.png"
%}

Before becoming a farmer, Mark served in the Navy during 9/11. After leaving the military, he used the GI Bill to return to school. At first, he planned to continue in engineering because of the electrical engineering training he had received while serving. Eventually, he switched to biology because he became more interested in environmental systems and how living organisms work together.

While studying biology, Mark realized that many careers connected to the field would keep him indoors working in labs. He wanted something different. He wanted work that kept him outside and allowed him to do something more hands on, which eventually led him to farming.


{% include scrollybox/bg.html
  image-path="images/loose-leaf-scroll.png"
  above-box-space = "100vh"
  below-box-space = "80vh"
  box-content=' “After figuring out that farming was… kind of soul-enlivening… you’re going to be happier, a lot happier.”'
%}


## Farming and Community
One thing that stood out during Mark’s interview was the way he talked about farming and how much it changed his life. Even though the work is exhausting and unpredictable at times, he explained that it gave him a sense of purpose that he did not feel in other career paths.

He especially talked about the experience of selling at farmers markets after long work weeks on the farm. There were days when he and Sarah felt drained and did not feel like waking up early to prepare vegetables and interact with customers. However, once they arrived and started talking to people, it reminded them why they continued doing the work.


## Pull Quotes Still Work
{% include typography/aside.html class="left" text="
“I think it is just part of who I am… I don’t want to work for somebody else. Plus, farming is very rewarding.”" %}

Another part of farming that mattered to Mark was the independence that came with it. During the interview, he explained that he never really wanted to work for somebody else. Farming gave him the opportunity to build something of his own, even though it came with financial risk and uncertainty.

Instead of following someone else’s schedule or goals, he was able to shape his own path and make decisions based on his own values.


## Learning Through Experience
Mark and Sarah are first generation farmers, so they had to figure out much of the process on their own. Instead of learning from generations of family farming knowledge, Mark depended heavily on research and trial and error. His background in biology helped him better understand soil systems, microbes, insects, and plant health.

He used that knowledge to develop his own approach to farming over time. He became focused on regenerative and biodiversity based farming methods instead of relying heavily on chemicals or shortcuts.

{% assign images =
"images/mark-sarah.png,
images/mvh-history-stays.jpg,
images/mvh-room-cost.jpg" | split: ','
%}

{% include images/carousel.html
id="first"
images=images
%}

**Why use carousels?** When you have 3-5 related images (historical documents, different views of a building, a sequence of photos), a carousel lets readers compare them side-by-side without scrolling past each one. Click the arrows or dots to move between images.

**Accessibility note:** Always include captions and source links so screen readers and citations work properly.


## Larger Images
{% include images/figure.html class="right" width="60%" caption="This image is 60% width instead of 48%, giving it more visual weight. Adjust widths based on what the image needs. [Source](https://rmoa.unm.edu/docviewer.php?docId=nmu1unma028.xml)" image-path="images/mvh-floorplan.jpg" %}

Just like in Seedling, you control image sizes with the `width` parameter. A floorplan or map might need 60-70% width to be legible, while a portrait might look better at 40%.

Duis ut dui dolor. Integer eu lectus at tellus accumsan euismod eget a ligula. Morbi venenatis, elit eu varius fermentum, ligula est dictum massa, sit amet ullamcorper augue nisl ut nunc.


## Block Quotes for Primary Sources
Sed efficitur leo in magna pretium, euismod malesuada risus interdum. Proin sed libero et enim pulvinar convallis non eget est.

> As of 1967 this was the design for the first floor of La Posada, reflecting the original design of Ernest J. Kump, lead design architect, and the alteration made by Sherman Smith. [Source](https://rmoa.unm.edu/docviewer.php?docId=nmu1unma028.xml)

Block quotes span the full text width and are perfect for extended quotations from archival sources, documents, or scholarly works. They're visually distinct from the scrollybox overlays and pull quotes.


## What You've Learned in Sapling
If you can create a Sapling essay, you can:

- **Use scrollyboxes** to overlay text on full-screen background images
- **Control pacing** with scroll space parameters
- **Add image carousels** for comparing multiple related images
- **Mix components** - scrollyboxes, pull quotes, carousels, and standard images in one essay
- **Create immersive narratives** that feel more like multimedia stories than traditional web pages

**This is enough for most sophisticated digital humanities projects.** The Forest essay adds background switching and side-scrolling for even more cinematic effects, but Sapling gives you all the tools for compelling visual scholarship.


## Bibliography

- Hooker, Van Dorn, Melissa Howard, and V. B Price. _Only in New Mexico: An Architectural History of the University of New Mexico: The First Century, 1889-1989_. Albuquerque, NM: University of New Mexico Press, 2000.

- University of New Mexico. Bainbridge Bunting Photograph Collection, 1870-1980, collection PICT 000-385, box 6	folder 102. Center for Southwest Research, University Libraries, University of New Mexico.

- University of New Mexico. Dept. of Facility Planning architectural drawings, 1892-2011, collection SWA UNMFPLAN Drawings, Stack 13	Drawer 01. Center for Southwest Research, University Libraries, University of New Mexico.

- University of New Mexico. Dept. of Facility Planning Records, 1889-, collection UNMA 028,Box  34. Center for Southwest Research, University Libraries, University of New Mexico.

---

## Ready to Create Your Own?

**New to Xanthan?** Start with the [Getting Started guide](../../../docs/getting-started/) to create your own site first. Once you have a working site, come back here to build your ScrollStory.

**Already have a Xanthan site?** To make your own Sapling essay:

1. **Duplicate this folder** (`scrollstories/sapling/`) and rename it for your topic
2. **Replace the text** with your own content, keeping the structure
3. **Add your own images** to the `images/` folder
4. **Update the front matter** at the top (title, author, date, header image, etc.)
5. **Customize components** - Add or remove scrollyboxes, carousels, and asides as needed

**What makes Sapling different from Seedling?**
- Background scrollyboxes for immersive text overlays
- Image carousels for comparing multiple images
- More sophisticated visual storytelling
- All Seedling components still work

Ready for even more? Check out the [Forest template](../forest/) for advanced features like background switching and side-scrolling.

{% include scrollybox/auto-scroll.html speed=1.5 %}
