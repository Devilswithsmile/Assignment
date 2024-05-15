Module-1 Assignment

**Q.1** Are the HTML tags and elements the same thing?

**Ans.** HTML Tags are building blocks of HTML Page. HTML Elements are components that are used in HTML Page. HTML Tags usually exist in pairs consisting of a starting and an ending tag.

**Q.2** What are tags and attributes in HTML?

**Ans.** HTML tags are used to hold the HTML element. HTML element holds the content. HTML attributes are used to describe the characteristic of an HTML element in detail. HTML tag starts with \< and ends with \> Whatever written within a HTML tag are HTML elements
**Example**\<tag attribute_name="attribute_value">Some content...</tag\>

**Q.3** What are void elements in HTML?

**Ans.** A void element is an element whose content model never allows it to have contents under any circumstances. Void elements can have attributes. The following is a complete list of the void elements in HTML : area , base , br , col , command , embed , hr , img , input , keygen , link , meta , param , source , track , wbr.

**Q.4** What are the Entities?

**Ans**. Some characters are reserved in HTML. If you use the less than (\<) or greater than (\>) signs in your HTML text, the browser might mix them with tags. Entity names or entity numbers can be used to display reserved HTML characters.

**Q.5** What are the different types of Lists in HTML?

**Ans.** HTML lists come in three main categories: unordered lists, ordered lists, and definition lists. Each type serves a specific purpose and can be customized to fit your design and content needs.
**Example**
\<ol>
  <li>Coffee</li>
  <li>Tea
    <ol>
      <li>Black tea</li>
      <li>Green tea</li>
    </ol>
  </li>
  <li>Milk</li>
</ol>
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl\>

**Q.6** What is the 'Class' attribute in HTML?

**Ans.** The class attribute specifies one or more class names for an element. The class attribute is mostly used to point to a class in a style sheet.**Example**\<div class="city"><h2>London</h2><p>London is the
capital of England.</p></div\>

**Q.7** What is the different between the 'Id' attribute and the 'class' attribute of HTML elements?

**Ans.** A Class name can be used by multiple HTML elements, while an ID name must only be used by one HTML element within the page.
**Example**\<div class="city" id="#01"><h2>London</h2><p>London is the
capital of England.</p></div\>

**Q.8** What are the various formatting tags in HTML?

**Ans.**

- Bold text: \<b\> or \<strong\>
- Italicized text: \<i\> or \<em\>
- Underlined text: \<u\>
- Strike-through text: \<del\> or \<s\>
- Superscript and subscript text: \<sup\> or \<sub\>

**Q.9** How is Cell Padding different from Cell Spacing?

**Ans.** Cell padding is used to create a border around the content area of a web page, whereas cell spacing is used for positioning elements (such as images or text) within that content area.
**Exmaple**\<table cellpadding="value" >.....</table\>\<table cellspacing="value" >.....</table\>

**Q.10** How can we club two or more rows or columns into a single rows or column in a HTML table?

**Ans.** The purpose of this article is to explore the method of merging table cells in HTML using the **rowspan** and **colspan** attributes. By utilizing rowspan, multiple cells in a row can be merged or combined, while **colspan** enables the merging of cells in a column within an HTML table. This technique proves essential for creating visually organized and structured tables, and optimizing the presentation of data.
**Example**\<tr>\<th colspan="2">Name</th\>\<th>Age</th\></tr\>
\<tr>\<th rowspan="2">Phone</th\>\<th>7878784512</th\></tr\>

**Q.11** What is the different between the block-Level element and an inline element?

**Ans.** Inline elements never begin on a new line. Block elements completely fill the accessible area from left to right. Only the area defined by the tags in the HTML element is covered by inline elements. There are top and bottom margins for block elements.

**Q.12** How to create a Hyperlink in HTML?

**Ans.** \<a href="https://www.google.com/"\>Visit Google.com\</a\>

**Q.13** What is the use of an Iframe tag?

**Ans.** An inline frame (iframe) is a HTML element that loads another HTML page within the document. It essentially puts another webpage within the parent page. They are commonly used for advertisements, embedded videos, web analytics and interactive content.

**Q.14** What is the use of span tag ? Expain with example ?

**Ans.** In HTML, the span tag is a generic inline container element. You use this element to wrap sections of text for styling purposes or to add attributes to a section of text without creating a new line of content

Example:

| \<!DOCTYPE html\>\< **html** \> \< **body** \> \< **h2** \>Welcome To Assignment\</ **h2** \> \< **p** \> is a Example of the Span tag. \< **span** \> computer Eng. \</ **span** \> portal for \< **span** \> Assignment \</ **span** \>. \</ **p** \>\</ **body** \> \</ **html** \> |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

**Q.15** How to input the image in the background image of a Web Pages?

**Ans.**

\< **body** background=
"https://www.pixground.com/wp-content/uploads/2023/08/Valorant-Agents-4K-Wallpaper-Background-jpg.webp"\>

\< **h1** \>Valorunt Game\</ **h1** \>

\< **h2** \>Background Image\</ **h2** \>

\</ **body** \>

**Q.16** How are active links different from normal links?

**Ans.** Active links are typically links that are currently functional and lead to live web pages, while normal links can refer to any link, whether functional or broken. Active links are actively used and accessible, while normal links may or may not be functional at a given time.

**Q.17** What are the different tags to separate sections of text?

**Ans.**

- br\> tag – It is used to separate the line of text. It breaks the current line and shifts the flow of the text to a new line.
- \<p\> tag–This tag is used to write a paragraph of text.
- \<blockquote\> tag–This tag is used to define large quoted sections.

**Q.18** What is SVG?

**Ans.** SVG stands for Scalable Vector Graphics. SVG is used to define graphics for the Web.

**Q.19** What is the different between HTML and XHTML?

**Ans.** HTML (HypertextMarkup Language) and XHTML (ExtensibleHypertext Markup Language) are both markup languages used for creating and displaying web pages. The main difference between them is the syntax and structure; HTML is more lenient in its syntax, while XHTML has a more strict syntax and follows XML rules.

**Q.20** What are the logical and physical tags in HTML?

Ans.

Physical Tags:

- Physical tags dictate how specific characters should be formatted on a web page.
- They directly influence the appearance of text or content.
- Examples include \<b\>, \<i\>, \<u\>, and \<font\>.
- These tags focus on the visual presentation of content rather than its semantic meaning.

Logical Tags:

- Logical tags convey the semantic meaning of enclosed text.
- They define the structure or significance of the content.
- Examples include \<strong\>, \<em\>, \<h1\> to \<h6\>.
- Logical tags are essential for accessibility and search engine optimization as they provide meaning and structure to content

-----------------------------------------------THE END----------------------------------------------

Name:-Yagna Panchasara
