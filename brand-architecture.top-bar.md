---
layout: default
title: Top bar
prevPage: /brand_architecture/structure/
nextPage: /brand_architecture/navigation_bar/
permalink: /brand_architecture/top_bar/
category: brand_architecture
subcategory: structure
order: 2.2
---

# Top bar

The top bar is always the first element in a page. It serves as a fast way to stay connected
with WRI main sections, with a dropdown with links to the most relevant issues and
sections deploying dropdown menu when clicking on any place of the bar.

![image description]({{ site.baseurl }}/images/image3.png)

<a class="button align-right" href="https://vizzuality.github.io/wri-guide/">Preview</a>

We've created a simple snippet to add this bar automatically.

```js
(function(){
  var element = document.createElement('div'),
    scriptTag = document.createElement('script');
  element.id = 'headerWrI';
  scriptTag.src = 'https://vizzuality.github.io/wri-guide/wri-guide-assets.js';
  document.body.insertBefore(element, document.body.firstChild);
  document.body.appendChild(scriptTag);
})();
```

<div class="align-right">
	<button class="button align-right" data-clipboard-text="(function(){var element = document.createElement('div'), scriptTag = document.createElement('script'); element.id = 'headerWrI'; scriptTag.src = 'https://vizzuality.github.io/wri-guide/wri-guide-assets.js'; document.body.insertBefore(element, document.body.firstChild); document.body.appendChild(scriptTag); })();">Copy</button>
</div>

<mark> * </mark> The drop-down menu height is 50% of the window and has a minimum height of 400px.
