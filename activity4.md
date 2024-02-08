# Activity 4: Creating a Basic Website with CSS Stylesheets 

In this lab, you will learn how to create a basic website and apply CSS (Cascading Style Sheets) styles to enhance its appearance. We will cover essential CSS concepts such as linking stylesheets, comments, multiple properties, different elements, units of measurement, multiple selectors, list styles, reusable stylesheets, more text styles, and the cascade.

**Prerequisites:**
- Visual Studio Code (VSCode) installed on your computer.
- Basic knowledge of HTML and CSS.

### Part 1/3

**Instructions:**

1. **Open Visual Studio Code:**
   - Launch Visual Studio Code on your computer.

2. **Create HTML File:**
   - Click on "File" in the menu bar, then select "New File" to create a new file.
   - Save the file with a `.html` extension (e.g., `index.html`).

3. **Add HTML Boilerplate:**
   - Type `html` and press `Tab` to generate the basic HTML structure.
   - Your file should now contain the following code:
     ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>My Basic Website</title>
         <link rel="stylesheet" href="styles.css">
     </head>
     <body>
         <h1>Welcome to My Basic Website</h1>
         <p>This is a paragraph of text.</p>
     </body>
     </html>
     ```

4. **Create CSS File:**
   - Click on "File" in the menu bar, then select "Save As".
   - Save the file with a `.css` extension (e.g., `styles.css`).

5. **Link CSS Stylesheet:**
   - Inside the `<head>` section of your HTML file, add a link to the CSS stylesheet using the `<link>` tag.
     ```html
     <link rel="stylesheet" href="styles.css">
     ```

6. **Add CSS Styles:**
   - Open the `styles.css` file.
   - Add CSS styles to customize the appearance of your webpage.
     ```css
     /* CSS Comments */
     /* Styles for Heading */
     h1 {
         color: blue;
         text-align: center;
     }
     
     /* Styles for Paragraph */
     p {
         font-size: 16px;
         line-height: 1.5;
     }
     ```

7. **Multiple Properties:**
   - Apply multiple properties to each CSS selector to control various aspects of the styling.

8. **Different Elements:**
   - Use different HTML elements as selectors to apply specific styles to each element type.

9. **Units of Measurement:**
   - Experiment with different units such as pixels (`px`), percentages (`%`), and em units (`em`) for sizing elements.

10. **Multiple Selectors:**
    - Combine multiple selectors to apply the same styles to multiple elements.

11. **List Styles:**
    - Customize list styles using CSS properties like `list-style-type` and `list-style-image`.

12. **Reusable Stylesheets:**
    - Define reusable styles that can be applied to multiple elements throughout your website.

13. **More Text Styles:**
    - Explore additional text styling properties such as `font-family`, `font-weight`, and `text-decoration`.

14. **The Cascade:**
    - Understand the concept of the cascade and how CSS rules are applied in the document.

15. **Save and Preview:**
    - Save both your HTML and CSS files.
    - Open the HTML file in a web browser to see the styled webpage.

### Part 2/3: Instructions for Writing a Simple HTML Page Using Emmet

In this task, you will create a basic HTML page using Emmet, a shorthand syntax for writing HTML and CSS quickly and efficiently. Emmet allows you to write HTML code using simple abbreviations and shortcuts.

**Instructions:**

1. **Open Your Text Editor:**
   - Open vscode.

2. **Start a New HTML File:**
   - Begin by creating a new file with an `.html` extension. You can do this by selecting "New File" from the file menu or pressing `Ctrl + N`.

3. **Use Emmet Abbreviations:**
   - Refer to the [Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/) to familiarize yourself with the Emmet syntax and abbreviations.
   
4. **Write HTML Structure:**
   - Utilize Emmet abbreviations to quickly generate HTML structure. For example:
     ```
     html:5
     ```
     This abbreviation expands into a basic HTML5 template.

5. **Add Content:**
   - Use Emmet abbreviations to add elements and content to your HTML page. For instance:
     ```
     div>h1{Hello, World!}+p{This is a simple HTML page.}
     ```
     This abbreviation creates a `<div>` containing an `<h1>` with the text "Hello, World!" followed by a `<p>` with the text "This is a simple HTML page."

6. **Save Your HTML File:**
   - Save your HTML file with an appropriate filename, such as `index.html`.

7. **Preview Your HTML Page:**
   - Open your HTML file in a web browser to preview the content and layout of your simple HTML page.

### Part 3/3

- Write the necessary HTML to make your page look ![like this.](html_mock1.png)
- Compare your solution to [this](./solution.html)
