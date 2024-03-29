# Drag and Drop Blocks - Test Cases

##### TC001

### Drag block to the top of the content

**Preparation:**
-   Create a new post/page.
-   Tap on the `...` button to open the editor settings.
-   Tap on the "Switch to HTML Mode" option.
-   Copy and paste the [HTML example](./drag-and-drop-blocks.md#html-example) into the HTML editor.
-   Tap again on the `...` button to open the editor settings.
-   Tap on the "Switch to Visual Mode" option.

**Steps:**
-   Scroll down until reaching the middle of the block list.
-   Long press over a block.
-   Drag the block to the **top** of the screen (the block list will be automatically scrolled).
-   Keep dragging the block until the block list reaches the top.
-   Drop the block in the first position (a visual indication of where the block will be placed will be displayed).
-   The block will be removed from its original position and inserted into the first position.

<img src="../resources/drag-and-drop-blocks-drag-to-top-content.gif" width="200"/>

--------------------------------------------------------------------------------

##### TC002

### Drag block to the bottom of the content

**Preparation:**
-   Create a new post/page.
-   Tap on the `...` button to open the editor settings.
-   Tap on the "Switch to HTML Mode" option.
-   Copy and paste the [HTML example](./drag-and-drop-blocks.md#html-example) into the HTML editor.
-   Tap again on the `...` button to open the editor settings.
-   Tap on the "Switch to Visual Mode" option.

**Steps:**
-   Scroll down until reaching the middle of the block list.
-   Long press over a block.
-   Drag the block to the **bottom** of the screen (the block list will be automatically scrolled).
-   Keep dragging the block until the block list reaches the bottom.
-   Drop the block in the last position (a visual indication of where the block will be placed will be displayed).
-   The block will be removed from its original position and inserted into the last position.

<img src="../resources/drag-and-drop-blocks-drag-to-bottom-content.gif" width="200"/>

--------------------------------------------------------------------------------

##### HTML example

The following HTML is an example to be used for testing the drag and drop blocks functionality.

<details><summary>Click here to display the HTML</summary>

```
<!-- wp:heading -->
<h2>Text Blocks</h2>
<!-- /wp:heading -->

<!-- wp:heading -->
<h2 id="this-is-an-anchor">What is Gutenberg?</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><strong>Bold</strong> <em>Italic</em> <s>Striked</s> Superscript<sup>(1)</sup> Subscript<sub>(2)</sub> <a href="http://www.wordpress.org" target="_blank" rel="noreferrer noopener">Link</a></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":4} -->
<h4>List</h4>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li>First Item</li><li>Second Item</li><li>Third Item</li></ul>
<!-- /wp:list -->

<!-- wp:heading {"level":4} -->
<h4>Quote</h4>
<!-- /wp:heading -->

<!-- wp:quote {"align":"left","className":"is-style-large"} -->
<blockquote class="wp-block-quote has-text-align-left is-style-large"><p>"This will make running your own blog a viable alternative again."</p><cite>— <a href="https://twitter.com/azumbrunnen_/status/1019347243084800005">Adrian Zumbrunnen</a></cite></blockquote>
<!-- /wp:quote -->

<!-- wp:pullquote -->
<figure class="wp-block-pullquote"><blockquote><p>One of the hardest things to do in technology is disrupt yourself.</p><cite>Matt Mullenweg</cite></blockquote></figure>
<!-- /wp:pullquote -->

<!-- wp:heading {"level":4} -->
<h4>Style Paragraph</h4>
<!-- /wp:heading -->

<!-- wp:paragraph {"dropCap":true,"className":"custom-class-1 custom-class-2 has-background has-vivid-red-background-color","fontSize":"large"} -->
<p class="has-drop-cap custom-class-1 custom-class-2 has-background has-vivid-red-background-color has-large-font-size">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempor tincidunt sapien, quis dictum orci sollicitudin quis. Proin sed elit id est pulvinar feugiat vitae eget dolor. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":4} -->
<h4>Pre formatted</h4>
<!-- /wp:heading -->

<!-- wp:preformatted -->
<pre class="wp-block-preformatted">Some <em>preformatted</em> text...<br>And more!</pre>
<!-- /wp:preformatted -->

<!-- wp:heading {"level":4} -->
<h4>Code</h4>
<!-- /wp:heading -->

<!-- wp:code -->
<pre class="wp-block-code"><code>if name == "World":
    return "Hello World"
else:
    return "Hello Pony"</code></pre>
<!-- /wp:code -->

<!-- wp:heading {"level":4} -->
<h4>Verse</h4>
<!-- /wp:heading -->

<!-- wp:verse {"textAlign":"center"} -->
<pre class="wp-block-verse has-text-align-center">Come<br>Home.</pre>
<!-- /wp:verse -->

<!-- wp:heading -->
<h2>Media</h2>
<!-- /wp:heading -->

<!-- wp:heading {"level":4} -->
<h4>Images</h4>
<!-- /wp:heading -->

<!-- wp:image -->
<figure class="wp-block-image"><img alt=""/></figure>
<!-- /wp:image -->

<!-- wp:image -->
<figure class="wp-block-image"><img src="https://cldup.com/cXyG__fTLN.jpg" alt=""/><figcaption>Mountain</figcaption></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":4} -->
<h4>Video</h4>
<!-- /wp:heading -->

<!-- wp:video {"autoplay":false,"id":683,"loop":false,"muted":false} -->
<figure class="wp-block-video"><video controls src="https://i.cloudup.com/YtZFJbuQCE.mov"></video><figcaption>Videos too!</figcaption></figure>
<!-- /wp:video -->

<!-- wp:heading {"level":4} -->
<h4>File</h4>
<!-- /wp:heading -->

<!-- wp:file /-->

<!-- wp:file {"id":3,"href":"https://wordpress.org/latest.zip"} -->
<div class="wp-block-file"><a id="wp-block-file--media-faec35c1-6522-481c-97ea-d8e96254faa4" href="https://wordpress.org/latest.zip">WordPress.zip</a><a href="https://wordpress.org/latest.zip" class="wp-block-file__button" download aria-describedby="wp-block-file--media-faec35c1-6522-481c-97ea-d8e96254faa4">Download</a></div>
<!-- /wp:file -->

<!-- wp:heading {"level":4} -->
<h4>Audio</h4>
<!-- /wp:heading -->

<!-- wp:audio /-->

<!-- wp:audio {"id":5} -->
<figure class="wp-block-audio"><audio controls src="https://cldup.com/59IrU0WJtq.mp3"></audio></figure>
<!-- /wp:audio -->

<!-- wp:heading {"level":4} -->
<h4>Gallery</h4>
<!-- /wp:heading -->

<!-- wp:gallery {"columns":8,"linkTo":"none","className":"alignfull"} -->
<figure class="wp-block-gallery has-nested-images columns-8 is-cropped alignfull"><!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon.png" alt=""/><figcaption>Paragraph</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Heading.png" alt=""/><figcaption>Heading</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Subheading.png" alt=""/><figcaption>Subheading</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Quote.png" alt=""/><figcaption>Quote</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Image.png" alt=""/><figcaption>Image</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Gallery.png" alt=""/><figcaption>Gallery</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Cover-Image.png" alt=""/><figcaption>Cover Image</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Video.png" alt=""/><figcaption>Video</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Audio.png" alt=""/><figcaption>Audio</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Column.png" alt=""/><figcaption>Columns</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-File.png" alt=""/><figcaption>File</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Code.png" alt=""/><figcaption>Code</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-List.png" alt=""/><figcaption>List</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Button.png" alt=""/><figcaption>Button</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-Embeds.png" alt=""/><figcaption>Embeds</figcaption></figure>
<!-- /wp:image -->

<!-- wp:image {"sizeSlug":"large","linkDestination":"none"} -->
<figure class="wp-block-image size-large"><img src="https://wordpress.org/gutenberg/files/2018/07/Block-Icon-More.png" alt=""/><figcaption>More</figcaption></figure>
<!-- /wp:image --></figure>
<!-- /wp:gallery -->

<!-- wp:heading -->
<h2>Separators</h2>
<!-- /wp:heading -->

<!-- wp:nextpage -->
<!--nextpage-->
<!-- /wp:nextpage -->

<!-- wp:more -->
<!--more-->
<!-- /wp:more -->

<!-- wp:spacer -->
<div style="height:100px" aria-hidden="true" class="wp-block-spacer"></div>
<!-- /wp:spacer -->

<!-- wp:heading -->
<h2>Layout</h2>
<!-- /wp:heading -->

<!-- wp:heading {"level":4} -->
<h4>Group</h4>
<!-- /wp:heading -->

<!-- wp:group -->
<div id="this-is-another-anchor" class="wp-block-group"><!-- wp:paragraph -->
<p>One.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Two</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Three.</p>
<!-- /wp:paragraph --></div>
<!-- /wp:group -->

<!-- wp:heading {"level":4} -->
<h4>Columns</h4>
<!-- /wp:heading -->

<!-- wp:columns {"className":"gutenberg-landing\u002d\u002ddevelopers-columns has-2-columns"} -->
<div class="wp-block-columns gutenberg-landing--developers-columns has-2-columns"><!-- wp:column -->
<div class="wp-block-column"><!-- wp:paragraph {"align":"left"} -->
<p class="has-text-align-left"><strong>Built with modern technology.</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"left"} -->
<p class="has-text-align-left">Gutenberg was developed on GitHub using the WordPress REST API, JavaScript, and React.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"left","fontSize":"small"} -->
<p class="has-text-align-left has-small-font-size"><a href="https://wordpress.org/gutenberg/handbook/language/">Learn more</a></p>
<!-- /wp:paragraph --></div>
<!-- /wp:column -->

<!-- wp:column -->
<div class="wp-block-column"><!-- wp:paragraph {"align":"left"} -->
<p class="has-text-align-left"><strong>Designed for compatibility.</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"left"} -->
<p class="has-text-align-left">We recommend migrating features to blocks, but support for existing WordPress functionality remains. There will be transition paths for shortcodes, meta-boxes, and Custom Post Types.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"align":"left","fontSize":"small"} -->
<p class="has-text-align-left has-small-font-size"><a href="https://wordpress.org/gutenberg/handbook/reference/faq/">Learn more</a></p>
<!-- /wp:paragraph --></div>
<!-- /wp:column --></div>
<!-- /wp:columns -->

<!-- wp:heading {"level":4} -->
<h4>Media Text</h4>
<!-- /wp:heading -->

<!-- wp:media-text {"isStackedOnMobile":false,"className":"is-stacked-on-mobile"} -->
<div class="wp-block-media-text alignwide is-stacked-on-mobile"><figure class="wp-block-media-text__media"></figure><div class="wp-block-media-text__content"><!-- wp:paragraph {"className":"has-large-font-size"} -->
<p class="has-large-font-size"></p>
<!-- /wp:paragraph --></div></div>
<!-- /wp:media-text -->

<!-- wp:heading {"level":4} -->
<h4>Cover</h4>
<!-- /wp:heading -->

<!-- wp:cover {"url":"https://cldup.com/cXyG__fTLN.jpg","id":890,"dimRatio":20,"overlayColor":"luminous-vivid-orange","focalPoint":{"x":"0.63","y":"0.83"},"minHeight":219,"isDark":false} -->
<div class="wp-block-cover is-light" style="min-height:219px"><span aria-hidden="true" class="wp-block-cover__background has-luminous-vivid-orange-background-color has-background-dim-20 has-background-dim"></span><img class="wp-block-cover__image-background wp-image-890" src="https://cldup.com/cXyG__fTLN.jpg" style="object-position:63% 83%" data-object-fit="cover" data-object-position="63% 83%"/><div class="wp-block-cover__inner-container"><!-- wp:paragraph {"align":"center","placeholder":"Write title…","className":"has-text-color has-very-light-gray-color","fontSize":"large"} -->
<p class="has-text-align-center has-text-color has-very-light-gray-color has-large-font-size">Cool cover</p>
<!-- /wp:paragraph --></div></div>
<!-- /wp:cover -->

<!-- wp:heading -->
<h2>Dynamic Blocks</h2>
<!-- /wp:heading -->

<!-- wp:latest-posts {"displayPostContent":true,"displayPostDate":true} /-->

<!-- wp:heading -->
<h2>Buttons</h2>
<!-- /wp:heading -->

<!-- wp:buttons -->
<div class="wp-block-buttons"><!-- wp:button -->
<div class="wp-block-button"><a class="wp-block-button__link">Solid Button</a></div>
<!-- /wp:button -->

<!-- wp:button {"gradient":"luminous-vivid-amber-to-luminous-vivid-orange"} -->
<div class="wp-block-button"><a class="wp-block-button__link has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background has-background">Gradient Button</a></div>
<!-- /wp:button --></div>
<!-- /wp:buttons -->

<!-- wp:heading -->
<h2>Legacy</h2>
<!-- /wp:heading -->

<!-- wp:shortcode -->
[youtube https://www.youtube.com/watch?v=ssfHW5lwFZg]
<!-- /wp:shortcode -->

<!-- wp:heading -->
<h2>Unsupported</h2>
<!-- /wp:heading -->

<!-- wp:rss /-->

<!-- wp:heading {"textAlign":"left","level":4,"style":{"typography":{"lineHeight":"2.5"}},"className":"has-primary-background-color has-background"} -->
<h4 class="has-text-align-left has-primary-background-color has-background" style="line-height:2.5">Heading with line-height set</h4>
<!-- /wp:heading -->
```

</details>

The following QR code can be used for accessing this page easily from a device:

<img src="https://chart.googleapis.com/chart?cht=qr&chs=500x500&chl=https%3A%2F%2Fgithub.com%2Fwordpress-mobile%2Ftest-cases%2Fblob%2Ftrunk%2Ftest-cases%2Fgutenberg%2Fdrag-and-drop-blocks.md%23html-example" width="150" height="150">