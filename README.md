# HTML Questions & Answers

**1. What is HTML and why is it important for web development?**
HTML (HyperText Markup Language) is the standard language used to structure and present content on the web. 
It provides the foundational framework of a webpage by defining elements such as headings, paragraphs, links, images, and forms.
HTML is important because it enables browsers to interpret and display content correctly, serving as 
the backbone upon which styling (CSS) and interactivity (JavaScript) are built.

**2. Can you explain the difference between HTML elements and tags?**

* **Tags** are the markup indicators enclosed in angle brackets, such as `<p>` (opening tag) and `</p>` (closing tag).
* **Elements** represent the complete structure, consisting of an opening tag, content, and a closing tag.


**3. What are some of the new features introduced in HTML5 compared to previous versions?**
HTML5 introduced significant improvements to enhance both functionality and user experience. Key features include:

* **Semantic elements** such as `<header>`, `<footer>`, `<article>`, `<section>`, and `<nav>` for clearer document structure.
* **Multimedia support** through the `<audio>` and `<video>` elements, eliminating the need for external plugins.
* **Enhanced forms** with new input types such as `email`, `date`, and `number` for improved validation and usability.
* **Graphics capabilities** using `<canvas>` and support for Scalable Vector Graphics (SVG).
* **Client-side storage** via Web Storage (localStorage and sessionStorage) and IndexedDB for offline capabilities.
* **Improved device compatibility**, making HTML5 more suitable for modern web applications across multiple platforms.


**4. How do you ensure your HTML document is accessible to people with disabilities?**
Accessibility in HTML involves designing web content so individuals with varying abilities can use it. Key practices include:

* Using **semantic HTML elements** to provide clear structure and meaning.
* Supplying **alt attributes** for images to describe visual content.
* Maintaining a logical **heading hierarchy** (`<h1>` through `<h6>`).
* Associating **labels** with form controls for clarity.
* Implementing **ARIA attributes** when additional context is required for assistive technologies.
* Ensuring sufficient **color contrast** for text readability.
* Supporting **keyboard navigation** for users unable to use a mouse.


**5. What is the Document Object Model (DOM), and how does it relate to HTML?**
The Document Object Model (DOM) is a programming interface that represents the structure of a web document as a tree of nodes. 
Each element, attribute, and text segment in an HTML document is modeled as a node within this structure.

The DOM enables programming languages, particularly JavaScript, to interact with and manipulate the document dynamically. 
This allows developers to modify content, add or remove elements, and respond to user interactions. 
In essence, while **HTML defines the static structure of a webpage, the DOM provides the mechanism through 
which that structure can be accessed and modified at runtime**.
