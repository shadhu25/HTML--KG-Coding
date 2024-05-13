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

**`Heading`** tags → The **`h1`** to **`h6`** HTML elements represent six levels of section headings. `h1` is the highest section level and `h6` is the lowest. By default, all heading elements create a block-level box in the layout, starting on a new line and taking up the full width available in their containing block.

**`Paragraph`** tag → The **`p`** HTML element represents a paragraph. Paragraphs are block-level elements. HTML paragraphs can be any structural grouping of related content, such as images or form fields.

**`hr`  tag →** The **`hr`**  HTML element represents a thematic break between paragraph-level elements: for example, a change of scene in a story, or a shift of topic within a section.

**`Image` tag →** The **`img`** HTML element embeds an image into the document.

**`Video` tag →** The **`video`** HTML element embeds a media player which supports video playback into the document. You can use `video` for audio content as well, but the `audio` element may provide a more appropriate user experience.

**`Anchor` tag →** The **`a`** HTML element (or *anchor* element), with its `href` attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.

**`Bold` tag →** The **`b`**  HTML element is used to draw the reader's attention to the element's contents, which are not otherwise granted special importance. This was formerly known as the Boldface element, and most browsers still draw the text in boldface. However, you should not use `b` for styling text or granting importance. If you wish to create boldface text, you should use the CSS `font-weight` property. If you wish to indicate an element is of special importance, you should use the `strong` element.

**`Italic` tag →** The **`i`** HTML ****element represents a range of text that is set off from the normal text for some reason, such as idiomatic text, technical terms, taxonomical designations, among others.

**`Preformated text` →** The **`pre`** HTML element represents preformatted text which is to be presented exactly as written in the HTML file.

**`Header` tag →** The **`header`** HTML element represents introductory content, typically a group of introductory or navigational aids. It may contain some heading elements but also a logo, a search form, an author name, and other elements.

- **`Navigation` tag →** The **`nav`**  HTML element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.

**`Main` tag →** The **`main`** HTML element represents the dominant content of the **`body`** of a document. The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application.

- **`Section` tag →** The **`section`**  HTML element represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it.
- **`Article` tag →** The **`article`**  HTML element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content.
- **`Aside` tag →** The **`aside`** HTML  element represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.

**`Footer` tag →** The **`footer`** HTML element represents a footer for its nearest ancestor sectioning content or sectioning root element. A `footer` typically contains information about the author of the section, copyright data or links to related documents.

**`Division` tag →** The **`div`** HTML element is the generic container for flow content. It has no effect on the content or layout until styled in some way using CSS (e.g. styling is directly applied to it, or some kind of layout model like Flex-box is applied to its parent element).

`Span` tag → The **`span`** HTML element is a generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the `class` or `id` attributes), or because they share attribute values, such as `lang`. It should be used only when no other semantic element is appropriate. `span` is very much like a `div` element, but `div` is a block-level element whereas a `span` is an inline-level element.

`Emphasize` tag → The **`em`** HTML element marks text that has stress emphasis.

**`mark` tag → T**he **`mark`** HTML element represents text which is **marked** or **highlighted** for reference or notation purposes due to the marked passage's relevance in the enclosing context.

**`del` tag →** The **`del`** HTML element represents a range of text that has been deleted from a document.

**`q` tag →** The **`q`** element represents some phrasing content quoted from another source.

**`blockquote` tag →** The **`blockquote`** element represents some phrasing content quoted from another source. Specially for a paragraph.

**`Abbribiation` tag →** The **`abbr`** element represents an abbreviation or acronym, optionally with its expansion. The title attribute may be used to provide an expansion of the abbreviation.

**`cite` tag →** The **`cite`** element represents a reference to a creative work. It must include the title of the work or the name of the author(person, people or organization) or an URL reference, or a reference in abbreviated form as per the conventions used for the addition of citation metadata.

**`bdo` tag →** The **`bdo`** element represents explicit text directionality formatting control for its children.

**`address` tag →** The **`address`** element represents the contact information for its nearest article or body element ancestor.

**`button` tag →** The **`button`** element represents a button labeled by its contents.

### All codes of above tag  →

[https://github.com/shadhu25/HTML--KG-Coding/blob/main/codes/TOPICS/HTML-tags.html](https://github.com/shadhu25/HTML--KG-Coding/blob/main/codes/TOPICS/HTML-tags.html)

**`picture` tag →** The **`picture`** HTML element contains zero or more **`source`** elements and one **`img`** element to offer alternative versions of an image for different display/device scenarios.

```html
<!-- Using picture tag -->
    <div style="width: 1920px; height: 1080px; border: 5px solid black;">
        <picture>
        <source media="(min-width: 650px)" srcset="/codes/IMAGES/2407074.jpg">
        <source media="(min-width: 465px)" srcset="/codes/IMAGES/IMG_20230818_112347.jpg">
        <img src="/codes/IMAGES/download.png" alt="small image">
        </picture>
    </div>
```

**`map` tag →** The **`<map>`** HTML element is used with **`area`** elements to define an image map (a clickable link area).

```html
<!-- Using image map -->
    <img usemap="#card" src="/codes/IMAGES/IMG_20230818_112347.jpg" alt="Aadhar card">
    <map name="card">
        <area target="_blank" alt="Aadhar card" title="Download Aadhar card" href="https://uidai.gov.in/" coords="388,536,108,239" shape="rect"></area>
        <area target="_blank" alt="QR code" title="QR code" href="https://en.wikipedia.org/wiki/QR_code" coords="780,408,971,592" shape="rect"></area>
    </map>
    <!-- URL for cordinate generator -> https://www.fla-shop.com/image-map/ -->
```

**`table` tag →** The **`table`** HTML element represents tabular data—that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.

- **`caption` tag → The `caption` element represents the title of the table that is its parent, if it has a parent and that is a table element.**
- **`td` tag →The `td` element represents a data cell in a table.**
- **`th`  tag →The `th` element represents a header cell in a table.**
- **`tr`  tag → The `tr` element represents a row of cells in a table.**
- `colgroup`  tag → The `colgroup` element is used to style specific columns of a table. Each group is specified with a `col` element. The `span` attribute specifies how many columns that get the style. The `style` attribute specifies the style to give the columns.

### code →

[https://github.com/shadhu25/HTML--KG-Coding/blob/main/codes/TOPICS/Table.html](https://github.com/shadhu25/HTML--KG-Coding/blob/main/codes/TOPICS/Table.html)

`ol`  tag →The ol element represents a list of items, where the items have been intentionally ordered, such that changing the order would change the meaning of the document.

- `li`  tag→ The li element represents a list item.
- `type`  attribute → Indicates the numbering type: <br> `'a'` indicates lowercase letters, <br> `'A'` indicates uppercase letters, <br> `'i'` indicates lowercase Roman numerals, <br> `'I'` indicates uppercase Roman numerals, <br> and `'1'` indicates numbers (default).
- `start`  attribute →If you want to start counting from a specified number, you can use the `start` attribute.

```html
<!-- Ordered List -->
    <ol type="1">
        <li>C</li>
        <li>C++</li>
        <li>Java</li>
        <li>HTML</li>
        <ol type="a">
            <li>level 1</li>
            <li>level 2</li>
            <li>level 3</li>
        </ol>
        <li>CSS</li>
    </ol>
    <!-- Control List Counting -->
    <ol start="50">
        <li>C</li>
        <li>C++</li>
        <li>Java</li>
        <li>HTML</li>
        <ol type="a">
            <li>level 1</li>
            <li>level 2</li>
            <li>level 3</li>
        </ol>
        <li>CSS</li>
    </ol>
```

`ul`  tag → The ul element represents a list of items, where the order of the items is not important — that is, where changing the order would not materially change the meaning of the document. we can change list style by `tstyle = "list-style-type: circle;` .

```html
<!-- Unodered List -->
    <ul style="list-style-type: circle;">
        <li>C</li>
        <li>C++</li>
        <li>Java</li>
        <li>HTML</li>
        <li>CSS</li>
    </ul>
```

`dl`  tag → The dl element represents an association list consisting of zero or more name-value groups (a description list). A name-value group consists of one or more names (`dt` elements) followed by one or more values (`dd` elements).

```html
<!-- Description List -->
    <dl>
        <dt>Cofee</dt>
        <dd> black hot drink</dd>
        <dt>Milk</dt>
        <dd>white cold drink</dd>
    </dl>
```

### Attributes

`title` →The `title` attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element. 

`mailto` →Use `mailto` attribute inside the href attribute to create a link that opens the user's email program (to let them send a new email).

`target` → The `target` attribute specifies where to open the linked document.

### All codes of above attributes →

[https://github.com/shadhu25/HTML--KG-Coding/blob/main/codes/TOPICS/HTML-tags.html](https://github.com/shadhu25/HTML--KG-Coding/blob/main/codes/TOPICS/HTML-tags.html)