# Activity 3: Creating a Basic Website

In this lab, you will learn how to create a basic website using HTML tags. We will cover essential HTML elements such as page titles, paragraphs, headings, unordered lists, ordered lists, emphasis elements, strong elements, structure vs presentation, and empty HTML elements.

**Prerequisites:**
- Visual Studio Code (VSCode) installed on your computer.
- Basic knowledge of HTML.

### Part 1/2

**Instructions:**

1. **Open Visual Studio Code:**
   - Open Visual Studio Code on your computer.

2. **Create a New HTML File:**
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
     </head>
     <body>
         
     </body>
     </html>
     ```

4. **Add Page Title:**
   - Inside the `<head>` section, add a title for your page using the `<title>` tag.
     ```html
     <title>My Basic Website</title>
     ```

5. **Add Paragraphs:**
   - Inside the `<body>` section, add some paragraphs using the `<p>` tag.
     ```html
     <p>This is a paragraph.</p>
     <p>This is another paragraph.</p>
     ```

6. **Add Headings:**
   - Use the `<h1>` to `<h6>` tags for headings of varying sizes.
     ```html
     <h1>Main Heading</h1>
     <h2>Subheading</h2>
     ```

7. **Add Unordered List:**
   - Create an unordered list using the `<ul>` and `<li>` tags.
     ```html
     <ul>
         <li>Item 1</li>
         <li>Item 2</li>
         <li>Item 3</li>
     </ul>
     ```

8. **Add Ordered List:**
   - Create an ordered list using the `<ol>` and `<li>` tags.
     ```html
     <ol>
         <li>First item</li>
         <li>Second item</li>
         <li>Third item</li>
     </ol>
     ```

9. **Add Emphasis Elements:**
   - Use the `<em>` tag for emphasized text.
     ```html
     <em>This text is emphasized.</em>
     ```

10. **Add Strong Elements:**
    - Use the `<strong>` tag for strong importance.
      ```html
      <strong>This text is strongly emphasized.</strong>
      ```

11. **Structure vs Presentation:**
    - Remember to use HTML for structure and CSS for presentation. Avoid using deprecated HTML presentation elements like `<font>`.

12. **Empty HTML Elements:**
    - Some HTML elements, such as `<img>` and `<br>`, are empty and do not require closing tags.
      ```html
      <img src="https://internetingishard.netlify.app/css-vs-html-f4fdfa.0a26cc8e.png" alt="Description">
      <br>
      ```

13. **Save and Preview:**
    - Save your HTML file.
    - Open the file in a web browser to see how your basic website looks.

### Part 2/2

**Instructions:**

1. **Open Visual Studio Code:**
   - Launch Visual Studio Code on your computer.

2. **Create a New HTML File:**
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
     </head>
     <body>
         
     </body>
     </html>
     ```

4. **Add Page Title:**
   - Inside the `<head>` section, add a title for your page using the `<title>` tag.
     ```html
     <title>My Basic Website</title>
     ```

5. **Add Anchors and Links:**
   - Use the `<a>` tag to create anchors and links.
     ```html
     <a href="https://www.example.com">Visit Example Website</a>
     ```

6. **Types of Links:**
   - Links can be absolute (starting with `http://` or `https://`) or relative (pointing to files within the same directory or website).

7. **Link Targets:**
   - Specify the target attribute to control how the linked document opens.
     ```html
     <a href="https://www.example.com" target="_blank">Visit Example Website (opens in a new tab)</a>
     ```

8. **Naming Conventions:**
   - Use meaningful names for anchor text and file names to improve accessibility and SEO.

9. **Add Images:**
   - Use the `<img>` tag to add images to your webpage.
     ```html
     <img src="image.jpg" alt="Description of the image">
     ```

10. **Image Formats:**
    - Common image formats include JPEG, PNG, and GIF. Choose the appropriate format based on your needs.

11. **Image Dimensions:**
    - Specify the width and height attributes to control the display size of images.
      ```html
      <img src="image.jpg" alt="Description" width="200" height="150">
      ```

12. **Text Alternatives:**
    - Always include descriptive alt text for images to improve accessibility and provide context for visually impaired users.
      ```html
      <img src="image.jpg" alt="A beautiful sunset over the ocean">
      ```

13. **More HTML Attributes:**
    - Explore additional attributes such as `title`, `class`, `id`, and `style` to further customize your HTML elements.

14. **HTML Entities:**
    - Use HTML entities to display special characters and symbols.
      ```html
      &copy; 2022 My Website
      ```

15. **Save and Preview:**
    - Save your HTML file.
    - Open the file in a web browser to see how your basic website looks.

