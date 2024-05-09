# HTML

### Basics of HTML

**`himl`** tag→ This element represents the root (top-level element) of an HTML document, so it is also referred to as the root element. All other elements must be descendants of this element.

**`head`** tag→ This element contains machine-readable information (metadata) about the document, like its title, scripts, and style sheets.

**`mata`** tag→ The <meta> element represents metadata that cannot be represented by other HTML meta-related elements.

**`title`** tag→ The <title> element defines the document's title that is shown in a browser's title bar or a page's tab.

**`body`** tag→ The <body> element represents the content of an HTML document. There can be only one <body> element in a document.

```html
<!DOCTYPE html>  <!-- Defines HTML version(HTML5) -->
<html lang="en">  <!-- Parent of all HTML tags / Root element | lang -> used for defining language of HTML file -->
<head>  <!-- Parent element of all meta deta tags  -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>  <!-- Defines title of the website -->
</head>
<body>  <!-- Parent of all content tags -->
    <h1>Hello World!</h1>  <!-- Heading tag -->
</body>
</html>
```

### HTML Tags

**`Heading`** tags → The **`h1`** to **`h6`** HTML elements represent six levels of section headings. `h1` is the highest section level and `h6` is the lowest. By default, all heading elements create a [block-level](https://developer.mozilla.org/en-US/docs/Glossary/Block-level_content) box in the layout, starting on a new line and taking up the full width available in their containing block.

**`Paragraph`** tag → The **`p`** HTML element represents a paragraph. Paragraphs are [block-level elements](https://developer.mozilla.org/en-US/docs/Glossary/Block-level_content). HTML paragraphs can be any structural grouping of related content, such as images or form fields.

**`hr`  tag →** The **`hr`**  HTML element represents a thematic break between paragraph-level elements: for example, a change of scene in a story, or a shift of topic within a section.

**`Image` tag →** The **`img`** HTML element embeds an image into the document.

**`Video` tag →** The **`video`** HTML element embeds a media player which supports video playback into the document. You can use `video` for audio content as well, but the `[audio](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio)` element may provide a more appropriate user experience.

**`Anchor` tag →** The **`a`** HTML element (or *anchor* element), with its `[href](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#href)` attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.

**`Bold` tag →** The **`b`**  HTML element is used to draw the reader's attention to the element's contents, which are not otherwise granted special importance. This was formerly known as the Boldface element, and most browsers still draw the text in boldface. However, you should not use `b` for styling text or granting importance. If you wish to create boldface text, you should use the CSS `[font-weight](https://developer.mozilla.org/en-US/docs/Web/CSS/font-weight)` property. If you wish to indicate an element is of special importance, you should use the `[strong](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong)` element.

**`Italic` tag →** The **`i`** HTML ****element represents a range of text that is set off from the normal text for some reason, such as idiomatic text, technical terms, taxonomical designations, among others.

**`Preformated text` →** The **`pre`** HTML element represents preformatted text which is to be presented exactly as written in the HTML file.

**`Header` tag →** The **`header`** HTML element represents introductory content, typically a group of introductory or navigational aids. It may contain some heading elements but also a logo, a search form, an author name, and other elements.

- **`Navigation` tag →** The **`nav`**  HTML element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.

**`Main` tag →** The **`main`** HTML element represents the dominant content of the **`body`** of a document. The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application.

- **`Section` tag →** The **`section`**  HTML element represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it.
- **`Article` tag →** The **`article`**  HTML element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content.
- **`Aside` tag →** The **`aside`** HTML  element represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.

**`Footer` tag →** The **`footer`** HTML element represents a footer for its nearest ancestor [sectioning content](https://developer.mozilla.org/en-US/docs/Web/HTML/Content_categories#sectioning_content) or [sectioning root](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements#labeling_section_content) element. A `footer` typically contains information about the author of the section, copyright data or links to related documents.

**`Division` tag →** The **`div`** HTML element is the generic container for flow content. It has no effect on the content or layout until styled in some way using CSS (e.g. styling is directly applied to it, or some kind of layout model like [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout) is applied to its parent element).

`Span` tag → The **`span`** HTML element is a generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the `[class](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes#class)` or `[id](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes#id)` attributes), or because they share attribute values, such as `[lang](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes#lang)`. It should be used only when no other semantic element is appropriate. `span` is very much like a `[div](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)` element, but `[div](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)` is a [block-level element](https://developer.mozilla.org/en-US/docs/Glossary/Block-level_content) whereas a `span` is an [inline-level element](https://developer.mozilla.org/en-US/docs/Glossary/Inline-level_content).