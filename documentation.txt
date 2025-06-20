HTML Fundamentals Assignment – Documentation

Author: Astha Jha
Repository: summer-school-online-day-1

============================
1. Purpose of Each HTML Tag
============================

<!DOCTYPE html>
- Declares that the document follows HTML5 standards.

<html>
- The root element that wraps all content of the HTML page.

<head>
- Contains metadata about the document such as title and links to styles or icons.

<title>
- Sets the page title that appears in the browser tab.

<link rel="icon">
- Adds a favicon (small icon in the browser tab) to improve branding.

<body>
- Contains all the visible content of the web page such as headings, text, images, and forms.

<header>
- Semantic element used to wrap introductory content or navigational links (like website title or logo).

<nav>
- Defines a section for navigation links. It helps users easily move between pages.

<a>
- The anchor tag creates links. Used for navigation and external references.

<h1> to <h6>
- Heading tags define titles and subtitles. <h1> is the most important, <h6> the least.
- Used to organize content and maintain accessibility hierarchy.

<p>
- Paragraph tag used to add blocks of text.

<ul>, <ol>, <li>
- Lists: 
  - <ul>: Unordered list (used for skills)
  - <ol>: Ordered list (used for education steps)
  - <li>: List item

<img>
- Embeds an image. We added the alt attribute for accessibility, so screen readers can describe it.

<table>, <tr>, <th>, <td>
- Used to organize and display project data:
  - <table>: Main container
  - <tr>: Table row
  - <th>: Table header cell
  - <td>: Table data cell

<main>
- Semantic tag that contains the primary content of the page. Improves screen reader interpretation.

<section>, <article>
- Semantic wrappers used to break content into meaningful blocks (optional but good for structure).

<footer>
- Semantic tag that holds the closing content, like copyright.

<form>
- Used to collect user input.

<fieldset>, <legend>
- Groups related form fields together for better structure and accessibility.

<label>
- Associates text with a form input. Helps screen readers and improves form usability.

<input>
- Accepts user data. Types used:
  - text: Name input
  - email: Validates email format
  - tel: Validates phone numbers
  - radio: Choose one option (inquiry type)
  - checkbox: Choose multiple options (contact method)
  - date: Pick a date
  - range: Visual urgency scale

<textarea>
- Multi-line input for messages or feedback.

<select>, <option>
- Dropdown menu to choose one item (e.g. country). Improves space efficiency.

<button>
- Used to submit the form.

============================
2. Why These Tags Were Used
============================

- Semantic tags (header, nav, main, footer) provide better document structure and improve accessibility.
- Form elements like <input type="email"> and <input type="tel"> enhance user experience by giving correct keyboards on mobile and browser validation.
- Validation attributes (required, pattern) ensure users enter valid and complete data before submission.
- Navigation through <nav> and <a> keeps the site user-friendly and accessible.
- Lists and tables structure information in readable and logical formats.

============================
3. Navigation Structure
============================

Each page includes a navigation bar (<nav>) with links:
- portfolio.html → main home page
- about.html → about me section
- contact.html → contact form

This allows users to move between sections of the website easily from any page.

============================
4. Accessibility & Standards
============================

- Every image has descriptive alt text.
- All form fields are properly labeled using <label for="id">.
- Semantic tags improve screen reader support and SEO.
- All code follows HTML5 standards for clean and valid markup.

============================
5. Bonus Implementation
============================

- Favicon added using <link rel="icon"> in the <head> for browser branding.

============================
Conclusion
============================

This project demonstrates clean HTML5 structure, semantic layout, valid form handling, and accessibility practices. It sets a strong foundation for styling and interactivity in the next stages using CSS and JavaScript.