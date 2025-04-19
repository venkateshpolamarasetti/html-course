HTML - Hyper text Markup Langauge
What is html?
HTML stands for HyperText Markup Language. It is the standard markup language used to create the structure of web pages. HTML consists of a series of elements with tags that tell the browser how to display content like text, images, links, and other media. It provides the skeleton of a webpage, which can be styled with CSS and made interactive with JavaScript.

What are HTML tags?
HTML tags are the building blocks of HTML. They are used to define elements on a web page—like headings, paragraphs, links, images, etc.

What are HTML elements?
An HTML element is everything from the opening tag to the closing tag, including the content in between. It defines the structure and meaning of a piece of content on a web page.

What are HTML Attributes?
Attributes are the properties that can be added to HTML opening tag. These attributes change the way the tag behaves or is displayed.

What are heading tags in HTML?
Heading tags in HTML are used to define headings on a web page. They range from <h1> to <h6>, where:
<h1> defines the most important (largest) heading
<h6> defines the least important (smallest) heading.

what is paragraph tag?
The <p> tag in HTML stands for paragraph. It's used to define blocks of text as paragraphs in a webpage.

what are text formating tags?
Tag | Description | Example
<b> Bold text (no extra importance) → Bold
<strong> Important text (semantically strong)→ Important
<i> Italic text (for style)→ Italic
<em> Emphasized text (semantically important)→ Emphasis
<mark> Highlighted text→Highlight
<u> Underlined text →Underline
<small> Smaller text
<del> Deleted (strikethrough)
<ins> Inserted text (often underlined)
<sub> Subscript text
<sup> Superscript text

what is Marquee tag text?
The <marquee> tag in HTML is used to create scrolling text or images across the screen—either horizontally or vertically.
    behavior = scroll, slide, alternate, direction= top, bottom, left, right

Define the list types in HTML.
There are 3 list types in HTML are as follows:
    1.Ordered list–The ordered list uses <ol> tag and displays elements in a numbered format.
    2.Unordered list–The unordered list uses <ul> tag and displays elements in a bulleted format.
    3.Definition list–The definition list uses <dl>, <dt>, <dd> tags and displays elements in definition form like in a dictionary.

How do you align list elements in an HTML file?
We can align the list elements in an HTML file using indents. If you indent each nested list further than the parent list, you can easily align and determine the various lists and their elements.

Differentiate between an Ordered list and an Unordered list.
An unordered list uses <ul> </ul> tags, and each element of the list is written between <li> </li> tags. The list items are displayed as bullets rather than numbers.
An ordered list uses <ol> </ol> tags, and each element of the list is written between <li> </li> tags. The list items are displayed as numbers rather than bullet points.

What is the difference between HTML and CSS?
HTML creates a web page's structure and content, while CSS defines its appearance and layout.

What are void elements in HTML?
Void elements in HTML are tags that do not require a closing tag. They are used to insert images, line breaks, and other content that does not require additional information.

What is the advantage of collapsing white space?
Collapsing white space in HTML can help reduce web pages' size and make them load faster. It involves removing unnecessary white space between HTML elements.

What are HTML Entities?
HTML Entities are special characters used to represent characters that cannot be typed on a keyboard. They are often used to display special symbols and foreign characters.

How you display table on webpage?
To display a table in an HTML webpage, you use the <table> tag along with other related tags to define rows and cells.
    <table> Defines the table itself
    <tr> Table row
    <th> Table header cell (bold + centered by default)
    <td>  Table data cell
    border Optional attribute to add a border

How do we insert a comment in HTML?
We can insert a comment in HTML by beginning with a lesser than sign and ending with a greater than sign. For example, “<!-“ and “->.” 

How do you create a hyperlink in HTML?
We use the anchor tag <a> to create a hyperlink in HTML that links one page to another. The hyperlink can be added to images, too.

Define an image map.
An image map in HTML helps link different kinds of web pages using a single image. It can also be used to define shapes in the images used in the image mapping process.

How do you add buttons in HTML?
We can use the built-in Button tag in HTML to add buttons to an HTML web page.

How do you add CSS styling in HTML?
There are three ways to include the CSS with HTML:
Inline CSS: It is used when less styling is needed or in cases where only a single element has to be styled. To use inline styles add the style attribute in the relevant tag.
External Style Sheet: This is used when the style is applied to many elements or HTML pages. Each page must link to the style sheet using the link tag.
Internal Style Sheet: It is used when a single HTML document has a unique style, and several elements must be styled to follow the format. Internal styles sheet is added in the head section of an HTML page by using the style tag.

What hierarchy do the style sheets follow?
If a single selector includes three different style definitions, the definition closest to the actual tag takes precedence. Inline style takes priority over embedded style sheets, which take priority over external style sheets.

How do you add JavaScript to an HTML webpage?
JavaScript is used to make HTML web pages more interactive and user-friendly. It is a scripting language that allows you to interact with some aspects of the page based on user input. As with CSS, there are three significant ways of including JavaScript:
Inline:
You can add JavaScript to your HTML elements directly whenever a certain event occurs. We can add the JavaScript code using attributes of the HTML tags that support it. Here is an example that shows an alert with a message when the user clicks on it:
Script block:
You can define a script block anywhere on the HTML code, which will get executed as soon as the browser reaches that part of the document. This is why script blocks are usually added at the bottom of HTML documents.
External JavaScript file:
You can also import the JavaScript code from a separate file and keep your HTML code clutter-free. This is especially useful if a large amount of scripting is added to an HTML webpage.

What is the ‘class' attribute in HTML?
The ‘class' attribute in HTML defines a class for an HTML element. It can be used to apply a specific style to a group of elements on a web page.

What is the difference between the ‘id' and ‘class' attributes of HTML elements?
The ‘id' attribute defines a unique identifier for an HTML element, while the ‘class' attribute defines a class for a group of elements. An ‘id' can only be used once on a page, while a ‘class' can be used multiple times.

What is the difference between an absolute and relative URL?
An absolute URL includes the full web address, the protocol (such as http or https) and the domain name (such as www.example.com). A relative URL, on the other hand, specifies the location of a resource relative to the current web page. For example, a relative URL might include the file path (such as /images/picture.jpg) or the relative path (such as ../images/picture.jpg).

What is the role of the title attribute in HTML?
The title attribute provides additional information about an element, such as a link or an image. The title text is displayed as a tooltip when a user hovers over the element.

What is a form in HTML?
A form is a set of input fields and other elements to collect user data. Forms can be used for various purposes, such as logging in, submitting feedback, or purchasing.

What is the role of the action attribute in HTML forms?
The action attribute is used to specify the URL of the script or program that will process the data submitted by the form. When the user clicks the submit button, the form data is sent to the specified URL for processing.

What is the role of the method attribute in HTML forms?
The method attribute specifies the HTTP method for submitting the form data. The two most common methods are GET and POST. GET retrieves data from the server, while POST sends data to the server.

In how many ways can you display HTML elements?
HTML elements can be displayed in several ways, including block, inline, inline-block, and none. The display property can specify how an element should be displayed.

What is the difference between “display: none” and “visibility: hidden” when used as attributes to the HTML element?
Elements with “display: none” are not visible and do not take up any space on the page, while elements with “visibility: hidden” are not visible but still take up space.

How to specify the link in HTML and explain the target attribute?
Links can be specified using the <a> tag. The href attribute is used to specify the URL of the page that the link should go to. The target attribute can specify where the linked page should open, such as in a new or similar window.

When to use scripts in the head and when to use scripts in the body?
Scripts can be placed in the <head> section of the HTML document or in the <body> section. Scripts that must be executed before the page is displayed, such as scripts that define variables or functions, should be placed in the <head> section. Scripts that must be executed after the page is displayed, such as scripts that manipulate the DOM, should be placed in the <body> section.

What are forms, and how to create forms in HTML?
Forms collect user data, such as login information or search queries. Forms can be created using the <form> tag, and input fields, such as text fields and checkboxes, can be added using various other tags.

How to handle events in HTML?
Events can be handled using JavaScript, which can be included in the HTML document using the script tag.

What is the difference between <figure> tag and <img> tag?
HTML <img> tag is used to add a picture in the webpage/website. In HTML5, you can <figure> tag to primarily group related content, such as an image and its caption or a code block and description. Examples of this type of material include diagrams, pictures, codes, and illustrations. Thus, In an HTML document, a picture is embedded using the image tag, while its content is logically organized using the figure tag.

Are the <datalist> tag and <select> tag the same?
The <datalist> tag provides a list of suggested values for an <input> element, while the <select> tag creates a dropdown list where users can select one or more options from a predefined set.

Define Image Map.
An HTML image map allows you to make some portions of a picture clickable, serving as links to other locations. This method works well for developing interactive visuals for websites or intricate navigation systems.

What are Semantic Elements?
HTML5 Semantics describes how to give web content a more logical structure and meaning by using specific elements such as <header>, <footer>, <nav>, <article>, <section>, etc. The tags that provide an HTML page more than just a presentation are called HTML semantics.
Semantic HTML increases search engine optimization (SEO), makes websites more accessible, and gives information a more logical structure and meaning. It improves HTML readability by providing explicit definitions for sections and page layouts.

What is the difference between the <meter> tag and <progress> tag?
The <progress> tag is most appropriate for displaying the progress of a single task. For tasks unrelated to task completion, including memory or disk space utilization, the <meter> works well. It displays a measurement of something, such as battery life, fuel level, or thermometer.

Is drag and drop possible using HTML5, and how?
With drag and drop in HTML, an element can be dropped to a different location by clicking and holding the mouse button over it and then letting go of it. 

You can enable the drag-and-drop feature in HTML 5 by following these steps:

Use the draggable attribute to make an element draggable: <img draggable="true">.
Use the ondragstart attribute to specify the drag behavior. 
Use the ondragover event to allow dropping by preventing the default behavior:
Use the ondrop event to handle the drop and retrieve the data.

What type of audio files can be played using HTML5?
HTML5 supports various audio files, including MP3, WAV, and OGG. The supported audio formats depend on the browser. While MP3, WAV, and OGG are commonly supported, not all browsers support every format.

Explain the concept of web storage in HTML5.
HTML5 supports two different forms of data storage: session storage and local storage. SessionStorage stores data only for the current session. The data is deleted when the tab or window is closed; local storage stores data with no expiration date and persists until deleted. Thus, LocalStorage stores data with no expiration time, while SessionStorage only retains data for the duration of the page session.

What is Microdata in HTML5?
Search engines use HTML microdata better to understand the composition and content of web pages, making it a crucial component of contemporary web development. Web developers can use Microdata to offer more details about particular items on a page, which helps search engines better comprehend the website's context and content.
Microdata uses a set of common attributes and values, such as itemprop and item type, to define particular elements on a web page. However, microdata improves a web page's representation in search results, not directly its ranking.

Explain HTML5 Graphics.
Graphics are visualizations that enhance user interaction and experience and make websites and applications aesthetically pleasing. Examples of graphics include maps, flowcharts, bar graphs, engineering drawings, construction blueprints, and photos. Web graphics typically use the following technologies: PNG, Canvas API, WebCGM, JPG or JPEG, CSS, SVG, etc.

Why do you think adding drag-and-drop functionality in HTML5 is important? How will you make an image draggable in HTML5?
You had to use other JavaScript frameworks, such as jQuery or more complicated JavaScript programming, to accomplish the drag-and-drop capability in regular HTML4. HTML5's drag-and-drop features are a fundamental UI concept that allows you to copy, reorganize, and remove items with your mouse. 
An element can be moved by dragging it while holding the mouse button. Let go of the mouse button to drop the element there. Set draggable=true on an object's element to enable draggable functionality. You can drag and drop almost anything on your website, including files, photos, links, and other markup.
Once you've defined the draggable="true" attributes, attach a drag start event handler to your content. This will initiate the drag sequence for each column. Use the drag enter, drag over, and drag leave event handlers to make it easier for the user to comprehend how to interact with your UI.

Why do we need the MathML element in HTML5?
MathML is useful for displaying formulas on technical and mathematical websites. HTML5 supports MathML, although it must be used inside the <math> and </math> tags. This guarantees sophisticated algorithms, scientific publications, and e-learning resources have clear math information. Its goal is to include mathematical formulas in texts and on World Wide Web sites. Only Mozilla Firefox and Google Chrome are compatible with MathML. MathML support can vary; other browsers might require polyfills or third-party libraries.

What are the server-sent events in HTML5?
When a web page automatically receives updates from a server, it's known as a server-sent event (SSE). Servers can use HTTP connections to send clients real-time data through these events. 

What are Web Workers?
Web Workers provide a simple way for web content to run scripts on background threads. The worker thread can complete tasks without affecting the user interface. They can also use the XMLHttpRequest and fetch() APIs for network requests. 

What is the usage of a novalidate attribute for the form tag that is introduced in HTML5?
The novalidate attribute prohibits forms from running validation logic when they are submitted. It always allows the form submission process to proceed, even if the validation logic yields a different result.

What are raster images and vector images?
Raster images are composed of pixels, which are tiny dots that combine tone and color to create an image. When you zoom in or magnify an image, pixels appear as tiny squares on graph paper. The number of pixels determines the image's resolution and higher pixel counts lead to better quality but larger file sizes.

What is a manifest file in HTML5?
The manifest file is a basic text file that specifies which resources the browser should cache for offline access. Manifest files are always prefaced with the phrase CACHE MANIFEST and are saved under the .appcache extension. They are divided into three sections: FALLBACK, NETWORK, and CACHE. The manifest attribute in the <html> tag specifies the HTML5 cache web pages. Every time a user views a webpage that has manifest properties or is specified in the manifest file, that webpage will be cached

What is the Geolocation API in HTML5?
Geolocation is one of the greatest HTML5 APIs for determining the user's geographic location in a web application. This new HTML5 feature lets you retrieve the current user's latitude and longitude coordinates. You can see your current location on the page by having JavaScript collect these coordinates and submit them to the server. The user's position can be obtained using the getCurrentPosition() method.

Explain Web Components and their usage.
Web Components combine three major technologies: Custom Elements, Shadow DOM, and HTML Templates to create adaptable, customized elements with encapsulated functionality that can be reused wherever you want without the risk of code clashes. By encapsulating a web component, you can write a reusable, single-responsibility code unit on any website. 

list all attributes and its functionality?
✅ Global Attributes
(These can be used on almost any HTML tag)
Attribute	Description
id	Unique identifier for the element
class	Assigns a class name (for CSS/JS)
style	Inline CSS styling
title	Tooltip text shown on hover
lang	Language of the element (e.g., en, fr)
dir	Text direction (ltr, rtl)
hidden	Hides the element from display
tabindex	Keyboard navigation order
contenteditable	Makes the content editable
draggable	Allows dragging (true/false)
accesskey	Sets a shortcut key
spellcheck	Enable/disable spell checking (true/false)
data-*	Custom data attribute (e.g., data-id, data-user)

🧾 Form-Related Attributes
Attribute	Description
name	Name of the input (used for form data)
value	Default value
placeholder	Placeholder text
required	Field must be filled out
readonly	Field is read-only
disabled	Field is disabled
maxlength	Max number of characters
min / max	Set numeric range for input
step	Steps for number/range inputs
type	Type of input (text, email, number, etc.)
checked	Default checked for radio/checkbox
selected	Default selected option
multiple	Allow multiple selections or file uploads
autofocus	Focus on the element on page load
autocomplete	Enables autocomplete suggestions
pattern	Regex pattern validation
action	Form submission URL
method	HTTP method (GET, POST)
enctype	Encoding type for file upload forms

📷 Media Attributes
Attribute	Applies To	Description
src	img, video, audio, script	Source file
alt	img	Alternative text
width, height	img, <video>	Dimensions
controls	<video>, <audio>	Display player controls
autoplay	<video>, <audio>	Auto-play the media
muted	<video>, <audio>	Start muted
loop	<video>, <audio>	Loop the media
poster	<video>	Image shown before video plays
preload	<video>, <audio>	Preload options (e.g. auto, metadata, none)
loading	<img>	Lazy-load images (lazy, eager)

🔗 Link & Anchor Attributes
Attribute	Applies To	Description
href	<a>, <link>	URL target
target	<a>	Where to open the link (_blank, _self, etc.)
rel	<a>, <link>	Relationship (e.g., noopener, stylesheet)
download	<a>	Forces file download
type	<link>, <script></script>

🧱 Layout/Structural Attributes
Attribute	Applies To	Description
colspan	<td>, <th>	Merge columns in table
rowspan	<td>, <th>	Merge rows in table
scope	<th>	Defines whether it's a row or column header

<!-- ⚙️ Script-Related Attributes

Attribute	Applies To	Description
defer	<script>	Runs script after parsing HTML
async	<script>	Runs script asynchronously
type	<script>	Script type (e.g., module, text/javascript)
src	<script>	External JS file --> 

list out all semantic tags?
🧱 Structural Semantic Tags

Tag	Description
<header>	Introductory content or navigation links (for page or section)
<nav>	Navigation links
<main>	Main content of the document (only one per page)
<section>	Generic standalone section of related content
<article>	Self-contained content (blog post, news, etc.)
<aside>	Side content like ads, notes, or related links
<footer>	Footer content (for page or section)
<address>	Contact information for a person or organization
📸 Media-Related Semantic Tags

Tag	Description
<figure>	Self-contained content (images, diagrams, etc.)
<figcaption>	Caption for the <figure> content
<picture>	Container for multiple image sources
<mark>	Highlights or marks important text
<time>	Represents a date, time, or duration
<progress>	Progress indicator (like a download bar)
<meter>	Gauge or scalar measurement (e.g. fuel level)
📑 Text-Level Semantic Tags

Tag	Description
<strong>	Important text (usually bold)
<em>	Emphasized text (usually italic)
<abbr>	Abbreviation with optional full form
<cite>	Title of a creative work (books, movies, etc.)
<dfn>	Defines a term
<code>	Inline computer code
<samp>	Sample output from a program
<kbd>	Keyboard input
<var>	Variable in a programming or math expression
<q>	Short inline quotation
<blockquote>	Long block quotation
<bdi>	Bi-directional isolation for text
<bdo>	Overrides text direction
<small>	Small print or fine print
<sub>	Subscript text
<sup>	Superscript text
<ins>	Inserted text
<del>	Deleted text
🎯 Interactive & Misc Tags

Tag	Description
<summary>	Summary or heading for a <details> element
<details>	Expandable content area
<dialog>	Dialog box or popup window
<template>	Client-side content not rendered at page load
<output>	Result of a calculation or script
