# Web Development Course Tasks

## Module 1: HTML Basics

### Practice Task 1
- [x] Create a basic HTML page structure with the `<!DOCTYPE>`, `<html>`, `<head>`, `<meta>`, `<title>`, and `<body>` tags.
- [x] The title will be “My Travel Blog”.
- [x] Add comments to the code to explain each section, for example, “this is the head section”.

### Practice Task 2
- [x] Create a heading tag that will have the text “My Travel Blog”.
- [x] Format the text in your heading tag using italics.

### Practice Task 3
- [x] Create a `<div>` and inside the `<div>`, create a `<p>` with your travel experience.
- [x] Add a button with the text “Read More”.

### Practice Task 4
- [x] Create a `<span>` tag outside the `<div>` with the text “What I bought” in bold.
- [x] Create an ordered list of things you bought.
- [x] Create another `<span>` tag with the text “My favorite food” and make it bold.
- [x] Create an unordered list of your favorite foods.

### Practice Task 5
- [x] Insert an image of your favorite food using the `<img>` tag and add the `src`, `width`, and `height` attributes.

### Practice Task 6
- [x] Create a link to your favorite song using the `<a>` tag with the `href` and `target` attributes.

## More Practice
- [ ] **Create a Web Page**
    - [ ] Include an `<h1>` heading with a title of your choice.
    - [ ] Write several paragraphs (`<p>`) describing your interests or goals.
    - [ ] Use an unordered list (`<ul>`) with at least 3 list items (`<li>`) of your favorite hobbies.
    - [ ] Add an anchor (`<a>`) tag linking to your favorite website.

- [ ] **Formatting Text**
    - [ ] Apply bold (`<b>`) and italic (`<i>`) formatting to text.
    - [ ] Use `<strong>` and `<em>` tags for important text.
    - [ ] Include line breaks (`<br>`) where necessary for readability.

- [ ] **Creating a Form**
    - [ ] Build a form with input fields for name, email, and a comment box (`<textarea>`).
    - [ ] Use radio buttons (`<input type="radio">`) for rating (1 to 5 stars).
    - [ ] Add a submit button (`<input type="submit">`) to send the form.

- [ ] **Building a List**
    - [ ] Create an ordered list (`<ol>`) of your top 5 favorite books or movies.
    - [ ] Use different list item styles (`<li>`), including nested lists (`<ul>` inside `<li>`).

- [ ] **Linking Pages**
    - [ ] Create multiple HTML pages linked together:
        - [ ] Main page (`index.html`) with links (`<a>`) to subpages.
        - [ ] Each subpage should have an `<h2>` heading, paragraphs (`<p>`), and a link back to the main page.

---

## Module 2: CSS Basics

### Task 1
- [x] Create an HTML document with three paragraphs.
- [x] Apply CSS styles to each paragraph using inline, internal, and external styles.

### Task 2
- [x] Design a webpage with a heading, paragraph, and a list.
- [x] Apply CSS styles to change text color, alignment, font size, font family, and font style for different elements.

### Task 3
- [x] Create an HTML document with various elements including headings, paragraphs, and `<div>`s.
- [x] Use different CSS selectors like ID, class, universal, and tag to apply unique styles to specific elements.

### Task 4
- [x] Design a webpage with multiple selections/divs.
- [x] Apply CSS styles to set different background colors, images, repeat, positions, and sizes for each selection.

### Task 5
- [x] Create a webpage with various elements such as `<div>`s, paragraphs, and images.
- [x] Apply CSS styles to add borders with different widths, colors, border radius, and box shadow effects to the elements.

### Task 6
- [x] Build a webpage with different elements like images, headings, paragraphs, and buttons.
- [x] Apply CSS styles to set the `display` property to `none`, `hidden`, `inline`, `block`, and `inline-block` for specific elements.

---

## Module 3: Git

### Task 1: Initialize a Repository
- [x] Create a new directory for your project.
- [x] Initialize a new Git repository in this directory.
- [x] Create a README.md file with a brief description of the project.
- [x] Add and commit the README.md file.

### Task 2: Create and Manage Branches
- [x] Create a new branch called `feature-1`.
- [x] Switch to the `feature-1` branch.
- [x] Make changes to the README.md file.
- [x] Commit the changes.
- [x] Switch back to the main branch.
- [x] Merge the `feature-1` branch into the main branch.

### Task 3: Tracking Changes
- [x] Create a new file called `index.html`.
- [x] Add some HTML content to the file.
- [x] Add and commit the `index.html` file.
- [x] Make changes to the `index.html` file.
- [x] View the changes using `git diff`.
- [x] Commit the changes.

### Task 4: Undoing Changes
- [x] Make another change to the `index.html` file.
- [x] Add the changes to the staging area.
- [x] Remove the changes from the staging area.
- [x] Undo the changes in the working directory.

### Task 5: Working with Remote Repositories
- [x] Create a new repository on GitHub.
- [x] Link your local repository to the GitHub repository.
- [x] Push your local changes to the GitHub repository.
- [x] Make a change to a file locally and push the changes to GitHub.

### Task 6: Pulling Changes
- [x] Make a change directly on GitHub (e.g., edit README.md).
- [x] Pull the changes from GitHub to your local repository.

### Task 7: Handling Merge Conflicts
- [x] Create a new branch called `conflict-branch`.
- [x] Make a change to the same line in `index.html` on both the main branch and `conflict-branch`.
- [x] Commit the changes on both branches.
- [x] Merge `conflict-branch` into the main branch and resolve the merge conflict.

### Task 8: Using .gitignore
- [x] Create a `.gitignore` file.
- [x] Add rules to ignore certain files or directories (e.g., `node_modules` or `.env` files).
- [x] Test the `.gitignore` file to ensure files matching the rules are not tracked by Git.

### Task 9: Viewing Commit History
- [x] Make several more commits to your repository.
- [x] Use `git log` to view the commit history.
- [x] Use `git log --oneline` for a condensed view of the commit history.
- [x] Use `git show` to view detailed information about a specific commit.

### Task 10: Reverting and Resetting Commits
- [x] Make a commit with a deliberate mistake.
- [x] Use `git revert` to create a new commit that undoes the mistake.
- [x] Make another commit with a mistake.
- [x] Use `git reset` to remove the bad commit from the history.

---

## Module 4: ## More about HTML

### Exercise Questions

- [ ]  **Create an Audio Player**
    - Create an audio player that plays an MP3 file with controls to play, pause, and adjust the volume.
- [ ]  **Embed a Video**
    - Embed a video in your HTML document that automatically plays when the page loads and loops indefinitely.
- [ ]  **Custom Video Player**
    - Create a video player with dimensions of 640x480, a poster image, and controls for play, pause, and volume adjustment.
- [ ]  **Basic Iframe**
    - Embed an iframe that displays a web page of your choice with dimensions of 800x600 and no border.
- [ ]  **Fullscreen Iframe**
    - Create an iframe that can be displayed in fullscreen mode and embed a video from YouTube.
- [ ]  **Audio with Multiple Sources**
    - Create an audio player that provides multiple source formats (e.g., MP3 and OGG) to ensure compatibility with different browsers.

### Exercise Questions of form

- [ ]  **Basic Contact Form**
    - Create a form with fields for name, email, and phone number. Add a submit button.
- [ ]  **Login Form**
    - Build a form with fields for username and password, including a submit button.
- [ ]  **Survey Form**
    - Create a form with various input types (text, radio buttons, checkboxes) to conduct a survey.
- [ ]  **Registration Form**
    - Design a registration form with fields for name, email, password, and a dropdown for selecting the country.
- [ ]  **Feedback Form**
    - Create a form that includes a textarea for user feedback, along with name and email fields.
- [ ]  **Event Signup Form**
    - Develop a form for event signup, including fields for name, email, date of birth, and a submit button.
- [ ]  **Order Form**
    - Create an order form with fields for product selection (dropdown), quantity (number input), and user details.
- [ ]  **Newsletter Subscription Form**
    - Design a form with fields for email and a checkbox for agreeing to terms and conditions.
- [ ]  **Job Application Form**
    - Build a job application form with fields for personal details, resume upload (file input), and a submit button.
- [ ]  **Appointment Booking Form**
    - Create a form for booking appointments, including date, time, and personal details fields.
- [ ]  **Donation Form**
    - Design a form for donations, with fields for name, email, donation amount (number input), and a submit button.
- [ ]  **Feedback with Rating**
    - Create a feedback form with fields for name, email, comments, and a rating (range input).
- [ ]  **Course Registration Form**
    - Develop a form for course registration, including fields for name, email, course selection (dropdown), and a submit button.
- [ ]  **Contact Form with Validation**
    - Build a contact form with name, email, and phone number fields. Add validation to ensure required fields are filled out correctly.
- [ ]  **Multi-Step Form**
    - Design a multi-step form using fieldsets and legends. Include steps for personal information, preferences, and review before submission.

### Table

- [ ]  **Basic Table**
    - Create a table with 3 rows and 3 columns, each cell containing some text.
- [ ]  **Table with Headers**
    - Create a table with a header row. Include columns for Name, Age, and Email.
- [ ]  **Table with Borders**
    - Create a table with a border around each cell. Include 4 rows and 4 columns.
- [ ]  **Table with Padding and Spacing**
    - Create a table with cellpadding and cellspacing attributes. Use different values to observe the changes.
- [ ]  **Spanning Columns**
    - Create a table where the first row has a cell that spans 3 columns.
- [ ]  **Spanning Rows**
    - Create a table where the first column has a cell that spans 2 rows.
- [ ]  **Complex Table Structure**
    - Create a table with a header, body, and footer section.
- [ ]  **Styled Table**
    - Apply CSS styles to a table to make it visually appealing. Focus on borders, padding, and background colors.
- [ ]  **Responsive Table**
    - Create a table that adjusts its width based on the screen size using CSS.
- [ ]  **Table with Form Elements**
    - Create a table that includes form elements like text inputs and checkboxes in the cells.
- [ ]  **Table with Images**
    - Create a table that includes images in some of the cells.
- [ ]  **Dynamic Table Data**
    - Create a table that displays data fetched from a JSON object (simulated by hardcoded data).
- [ ]  **Table with Links**
    - Create a table that includes hyperlinks in some of the cells.
- [ ]  **Sortable Table**
    - Create a table that can be sorted by clicking on the headers (requires JavaScript).
- [ ]  **Table with Row Highlight**
    - Create a table where hovering over a row highlights it with a different background color using CSS.

### Navbar

- [ ]  **Basic Horizontal Navbar**
    - Create a simple horizontal navbar with links to Home, About, Services, and Contact pages.
- [ ]  **Vertical Navbar**
    - Design a vertical navbar with the same links as above and style it using CSS.
- [ ]  **Navbar with Dropdown**
    - Add a dropdown menu under one of the navbar items (e.g., Services) with additional links.
- [ ]  **Sticky Navbar**
    - Create a navbar that stays at the top of the page when the user scrolls down.
- [ ]  **Responsive Navbar**
    - Build a responsive navbar that switches to a vertical layout on smaller screens using media queries.
- [ ]  **Navbar with Icons**
    - Include icons next to the text in the navbar links (use Font Awesome or similar icon library).
- [ ]  **Collapsible Navbar**
    - Implement a collapsible navbar that hides and shows the links when a button is clicked (use JavaScript).
- [ ]  **Navbar with Search Bar**
    - Add a search bar to the navbar and style it to fit with the navigation links.
- [ ]  **Multi-Level Navbar**
    - Design a multi-level navbar with submenus under certain links (e.g., Products > Category 1, Category 2).
- [ ]  **Animated Navbar**
    - Create a navbar with smooth animations when hovering over links or clicking on dropdowns.

## Module 5: Think and Make Essential UI Components

### Exercise Questions

- [ ]  **Flexbox Layout**
    - Create a basic flexbox layout with a header, main content area, and footer. The header and footer should be fixed in height, while the main content area should fill the remaining space.
- [ ]  **Nested Flexbox Layout**
    - Design a nested flexbox layout with an outer container divided into two columns. The left column should contain two rows, and the right column should contain three rows.
- [ ]  **Hero Section**
    - Create a hero section with a background image, a headline, a subheadline, and a call-to-action button.
- [ ]  **Responsive Hero Section**
    - Design a responsive hero section that adjusts its font sizes and padding based on the screen size.
- [ ]  **Card Layout**
    - Create a simple card layout with an image, title, description, and a button.
- [ ]  **Multiple Cards**
    - Design a section that contains multiple cards arranged in a grid layout using flexbox.
- [ ]  **Card Hover Effect**
    - Add a hover effect to the card boxes to change their shadow and slightly lift them.
- [ ]  **Form Card**
    - Create a card that contains a form with fields for name, email, and message, along with a submit button.
- [ ]  **Measurement Practice**
    - Design a layout using a mix of relative and absolute units (e.g., `px`, `%`, `em`, `rem`) to understand their impact on responsiveness.
- [ ]  **Image Card**
    - Create a card with an image at the top and text content below. Ensure the image maintains its aspect ratio and fills the card's width.
- [ ]  **Grid of Cards**
    - Create a grid of cards using flexbox that is responsive and adjusts the number of cards per row based on the screen size.
- [ ]  **Flexbox Navigation Bar**
    - Design a responsive navigation bar using flexbox that collapses into a dropdown menu on smaller screens.
- [ ]  **Sidebar Layout**
    - Create a layout with a fixed sidebar and a flexible main content area using flexbox.
- [ ]  **Centered Hero Section**
    - Create a hero section that is vertically and horizontally centered within the viewport.
- [ ]  **Complex Nested Layout**
    - Design a complex nested flexbox layout with multiple nested containers and varying alignments to practice advanced flexbox concepts.

## Module 6: Build a Beautiful Portfolio

- [ ]  **Build a Beautiful Portfolio**
    - Create a portfolio website showcasing your projects, skills, and contact information. Use HTML, CSS, and possibly JavaScript to make it interactive and visually appealing.

## Module 7: Set Your Web Development Objective (Assignment 1)

- [ ]  **Set Your Web Development Objective**
    - Define your goals and objectives as a web developer. Consider what skills you want to improve, projects you want to build, or career milestones you aim to achieve.

## Module 7.5: Pseudo Classes, Elements, Position

- [ ]  **Pseudo Classes, Elements, Position**
    - Practice using pseudo-classes (:hover, :focus, :nth-child, etc.), pseudo-elements (::before, ::after), and CSS positioning (absolute, relative, fixed) to style and position elements effectively.

## Module 8: Responsive Website Layout

### Task 1: Design a Responsive Flex Layout

- [ ]  Create a flexible layout using CSS Flexbox that adjusts smoothly between different screen sizes.

### Task 2: Design a Responsive Grid Layout

- [ ]  Implement a grid-based layout that maintains responsiveness across various devices using CSS Grid.

### Task 3: Design Responsive Layout 2

- [ ]  Develop a secondary responsive layout using a combination of Flexbox and Grid techniques.

### Task 4: Design Another Responsive Layout

- [ ]  Design an additional responsive layout that explores different CSS features like media queries and viewport units.

### Task 5: Adapt Images for Different Devices

- [ ]  Optimize and adjust images in your responsive layouts to ensure they display correctly and efficiently on different screen resolutions.

## Module 9: More Responsive Layout and Responsive Portfolio

- [ ]  Complete additional exercises focusing on advanced responsive layout techniques and apply them to your portfolio project.
- [ ]  [simple responsive challange](https://github.com/ProgrammingHero1/simple-responsive-challenges.git)


### Module 10: HTML/CSS-only Landing Page - G3 Architects

- [ ]  Implement a complete landing page using only HTML and CSS, following the design guidelines provided for G3 Architects.
- [ ]  [g3 architects resources](https://github.com/ProgrammingHero1/g3-architects-resources)


### Module 11: Optimize Images, Icons, and More CSS

- [ ]  Learn techniques to optimize images for web use, integrate icons into your projects using icon libraries or custom SVGs, and refine CSS styles for improved performance and aesthetics. [create influencer gear website](https://github.com/ProgrammingHero1/influencer-gear)


