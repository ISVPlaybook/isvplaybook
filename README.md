# ISV Playbook on GitHub Pages

This repository contains the source code for the ISV Playbook on GitHub Pages. The ISV Playbook is a guide for ISV partners to help them onboard to the Microsoft Partner Network (MPN) and build a successful business with help of the Microsoft ISV Team.

The repository is built using Just the Docs theme powered by [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

Following is the guidance to help you contribute to the ISV Playbook:

## Page organization and navigation:

    - The ISV Playbook is organized into sections and articles. Each section is a folder in the `_docs` directory and each article is a markdown file in the respective section folder.
    - The navigation is automatically generated based on the folder structure and the front matter of the markdown files.
    - To add a new section, create a new folder in the `_docs` directory and add a markdown file with the same name as the folder.
    - To add a new article, create a new markdown file in the respective section folder.
    - To change the order of sections or articles, update the `nav_order` in the front matter of the markdown file.

## Front matter:

    - Each markdown file should have front matter at the beginning of the file. The front matter is used to define the layout, title, navigation order, parent, and permalink of the page.
    - The front matter should be enclosed in `---` at the beginning and end of the front matter.
    - The front matter should have the following fields:
        - layout: default
        - title: Title of the page
        - nav_order: Order of the page in the navigation
        - parent: Parent section of the page
        - permalink: Permalink of the page
    - Example front matter:
        ```
        ---
        layout: default
        title: Article 1
        nav_order: 1
        parent: Section 1
        permalink: /docs/section-1/article-1
        ---
        ```

## Code snippets:

    - To add a code snippet to a markdown file, enclose the code in triple backticks.
    - To add a code snippet with syntax highlighting, add the language identifier after the first set of triple backticks.
    - Example code snippet:
        ```
        Some code
        ```

## Buttons:

    - To add a button to a markdown file, use the following syntax:
        ```
        [Link button](https://just-the-docs.com){: .btn }
        ```
    - To add a button with a specific color, use the following syntax:
        ```

## Headings

Headings are rendered like this:

<div class="code-example">
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
</div>
```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

---

## Body text

Default body text is rendered like this:

<div class="code-example" markdown="1">
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</div>
```markdown
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
```

---

## Inline elements

<div class="code-example" markdown="1">
Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page]({{site.baseurl}}/).

</div>
```markdown
Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page]({{site.baseurl}}/).

```

---

## Typographic Utilities

There are a number of specific typographic CSS classes that allow you to override default styling for font size, font weight, line height, and capitalization.

[View typography utilities]({% link docs/utilities/typography.md %}){: .btn .btn-outline }
```
