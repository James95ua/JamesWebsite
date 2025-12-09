### 1. Fit by science with James 
- My website will be revoloving around **Supplements** and **Nutrition** where I'll be sharing info with consumers on what are the essential supplements for optimal health and welbeing and elaborate on how important nutrition is and how it deeply afects our health and mood.
### 2. My target audience will be:
  - People who are interested in fitness and healthy eating
  - Beginners who want simple guidance on supplementation
  - Potential employers who wants to see my skills in HTML and CSS
### 3. What I plan to include on each page and why: 
- **Home page (index.html)**
- Big title and subtitle with a short message about the site
- Introductiory paragraphs that explaine the purpose of the site
- Links to external resources
- Simple navigation menu at the top
- **Nutrition page (nutrition.html)*- Text about balanced meals, energy levels and practical tips
- Maybe a simple list or table of hralty food examples
- **Supplements page (supplements.html)**
- Short explanation of common supplements
- Simple pros and cons in normal language
- **Contact/About page (about.html)**  
  - Short text about me  
  - How to contact me (email or form)
  ## 4. Design decisions (color scheme, layout, typography)
  ### Colour scheme

- Main page background: #f4f3ee – a very light neutral colour that makes text easy to read.
- Header background: #0f173a – a dark navy colour that creates strong contrast and makes the site title stand out.
- Headings (h1, h2): #d97757 – a warm orange that feels energetic and fits the fitness theme.
- Links: #2563eb with a slightly darker blue on hover – a clear blue that users recognise as clickable.
- Footer: uses the text colour as background with black text to visually separate it from the main content.

### Layout choices

- I use a sticky header at the top, so the navigation stays visible when the user scrolls.
- The navigation bar has the logo/title on the left and links on the right, using flexbox for alignment.
- The main content is in a single column with a max-width of 1100px and margin: 0 auto 20px; so text lines are not too wide and stay centered on the page.
- The subtitle under the main heading is centred and has extra margin to create clear visual hierarchy.
- The footer is at the bottom with centred text and padding to give it some breathing space.

### Typography

- I use a basic sans-serif stack: Arial, Helvetica, sans-serif; because it is clean and easy to read.
- The base font size is 16px with line-height: 1.6 for comfortable reading.
- The main heading (`h1`) is much larger (`2.5rem`) and centre aligned to make the site title the first thing the user sees.
- Subtitles and section headings (`h2`) are slightly smaller but still use the same orange colour to keep the visual style consistent.

## 5. Navigation structure and why I chose it

Navigation is a simple horizontal menu at the top of every page:

- Supplementation, Nutition, Fat-loss tips, and More!
- Nutrition
- Supplements
Ichose this structure, because:
- The menu is always located in the same place easy to navigate
- The list is small so it wont be confusing to the user
- Every link leads to a seperate topic, that's why i kept them seperate

- ## 6. Sketches / wireframes

I plan to draw simple wireframes on paper:

- One sketch for the home page (header + hero text + main content + footer)
- One sketch for a content page 

I will photograph these sketches and add the images to my repository in a wireframes/ folder, then link to them here

## 7. Technologies and tools

I plan to use:
- HTML5 for page structure  
- CSS3 for styling (colours, layout, typography)  
- A simple text editor (Notepad)  
- A web browser (Chrome/Edge) to test the site

## 8. Brief discussion of HTML and CSS evolution

HTML started as a very simple language for linking documents on the web. Early versions mainly supported text, links and basic structure. Over time, HTML added more semantic elements like <header>, <nav>, <main> and <footer> to make pages easier to understand for browsers and screen readers.
***HTML version timeline***
**HTML 2**
November 24, 1995
HTML 2.0 was published as RFC 1866. Supplemental RFCs added capabilities:
November 25, 1995: RFC 1867 (form-based file upload)
May 1996: RFC 1942 (tables)
August 1996: RFC 1980 (client-side image maps)
January 1997: RFC 2070 (internationalization)

**HTML 3**
**January 14, 1997**
HTML 3.2[16] was published as a W3C Recommendation. It was the first version developed and standardized exclusively by the W3C, as the IETF had closed its HTML Working Group on September 12, 1996.[17]
Initially code-named "Wilbur",[18] HTML 3.2 dropped math formulas entirely, reconciled overlap among various proprietary extensions and adopted most of Netscape's visual markup tags. Netscape's blink element and Microsoft's marquee element were omitted due to a mutual agreement between the two companies.[14] A markup for mathematical formulas similar to that of HTML was standardized 14 months later in MathML.

**HTML 4**
**December 18, 1997**
HTML 4.0 was published as a W3C Recommendation. It offers three variations:
Strict, in which deprecated elements are forbidden
Transitional, in which deprecated elements are allowed
Frameset, in which mostly only frame related elements are allowed.
Initially code-named "Cougar", HTML 4.0 adopted many browser-specific element types and attributes, but also sought to phase out Netscape's visual markup features by marking them as deprecated in favor of style sheets. HTML 4 is an SGML application conforming to ISO 8879 – SGML.

**HTML 5**
Main article: HTML5
October 28, 2014
HTML5[26] was published as a W3C Recommendation.
November 1, 2016
HTML 5.1[28] was published as a W3C Recommendation.
December 14, 2017
HTML 5.2[31] was published as a W3C Recommendation.

***THE INFO ABOVE I GOT IT FROM WIKI HERE'S THE LINK***: https://en.wikipedia.org/wiki/HTML

CSS was created to separate content and presentation. Instead of using many presentational tags in HTML, designers could use CSS to control colours, fonts and layout. Modern CSS includes features like flexbox and grid, which make responsive layouts much easier to build for different screen sizes
Cascading Style Sheets (CSS) is a style sheet language used for specifying the presentation and styling of a document written in a markup language such as HTML or XML (including XML dialects such as SVG, MathML or XHTML).[2] CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

CSS is designed to enable the separation of content and presentation, including layout, colors, and fonts. This separation can improve content accessibility, since the content can be written without concern for its presentation; provide more flexibility and control in the specification of presentation characteristics; enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file, which reduces complexity and repetition in the structural content; and enable the .css file to be cached to improve the page load speed between the pages that share the file and its formatting.

Separation of formatting and content also makes it feasible to present the same markup page in different styles for different rendering methods, such as on-screen, in print, by voice (via speech-based browser or screen reader), and on Braille-based tactile devices. CSS also has rules for alternative formatting if the content is accessed on a mobile device.

The name cascading comes from the specified priority scheme to determine which declaration applies if more than one declaration of a property match a particular element. This cascading priority scheme is predictable.

The CSS specifications are maintained by the World Wide Web Consortium (W3C). Internet media type (MIME type) text/css is registered for use with CSS by RFC 2318 (March 1998). The W3C operates a free CSS validation service for CSS documents.

In addition to HTML, other markup languages support the use of CSS including XHTML, plain XML, SVG, and XUL. CSS is also used in the GTK widget toolkit.

Syntax
CSS has a simple syntax and uses a number of English keywords to specify the names of various style properties.

Style sheet
Main article: Style sheet (web development)
A style sheet consists of a list of rules. Each rule or rule-set consists of one or more selectors, and a declaration block.

***THE INFO ABOVE I GOT IT FROM WIKI HERE'S THE LINK***: https://en.wikipedia.org/wiki/CSS


- GitHub to store the code and documentation

## 9. HTML tags I plan to use effectively

1. `<header>` – to wrap the top part of the page with the logo and navigation.  
2. `<nav>` – to contain the main navigation links.  
3. `<main>` – to wrap the main content of each page.  
4. `<section>` – to divide content into logical sections.  
5. `<h1>`–`<h3>` – for clear headings and structure.  
6. `<a>` – for links to other pages and external resources.

### 10. CSS properties used 

1. `color` and `background-color` – to set text colour and background colours for sections and buttons.  
2. `font-size` and `line-height` – to control readability of text.
3. `margin` and `padding` – to create spacing around and inside elements.  
4. `border-radius` – to make buttons and cards have rounded corners.
