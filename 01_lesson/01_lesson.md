# Chapter 1 - Start Here

## HTML Definition

- **HTML** (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content.
- "Hypertext" refers to links that connect web pages to one another, either within a single website or between websites.
- HTML uses "markup" to annotate text, images, and other content for display in a Web browser. [[1](#1-mdn-html)]

## Elements and Tags

An element consists of an opening tag, content and an ending tag.

```html
<opening_tag>Content</closing_tag>
```

For example:

```html
<p>This is a paragraph.</p>
```

## Live Server URL

- The following is the URL of the page opened by live server
`http://127.0.0.1:5500/index.html`
- The URL `http://127.0.0.1` refers to the local server.
- The `5500` at the end of the URL is the port number.
While `index.html` is the path to the HTML file.

## Language Codes

- A `lang` attribute should be added to the `html` element indicating the language of the web page.
- A full list of ISO language codes used in the `lang` attribute is on the w3schools website. [[2]](#2-html-language-codes-list)

## Tips

- Keep file names in lower case with no space, separating words by hyphens.
- Only use one `h1` element per page.
- Always use W3C validator to check for any errors on your web page.
- Don't use double dashes inside an HTML comment.
- To resolve the "Trailing Slash of Void Elements" warning from the W3C validator for all the projects on your computer, assuming you're using Linux, perform these steps:
  - create a file with the name: ~/.prettierrc
  - In VSCode, click CTRL + , to open settings.
  - Search for prettier.
  - Under "Prettier: Config Path", write" ~/.prettierrc
  - Open the ~/.prettierrc and enter the following and then save the file:

```
{
  "htmlWhitespaceSensitivity": "ignore"
}
```
## Tools

### 🔗 [Google Chrome (Web Browser)](https://google.com/chrome/)

- A web browser is used to view web pages.

### 🔗 [Dark New Tab (Chrome Extension)](https://chrome.google.com/webstore/detail/dark-new-tab/kcphhkbdlfggickaoeiahdcfhagfbajl?hl=en)

- This extension is used in the Google Chrome browser. It is used to give new tabs in dark mode. There are buttons to switch between dark and light background in these new tabs.

### 🔗 [Visual Studio Code (Code Editor)](https://code.visualstudio.com/)

- A code editor is an application that is used for writing code. It usually has features that make writing code easier.

### 🔗 [Prettier VS Code Extension (Autoformatter)](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

- An autoformatter is used to automatically format a document usually using standardized and best practice formatting.

### 🔗 [vscode-icons VS Code Extension (Icon Pack)](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

- This extension adds icons beside each file, and at the top of each tab indicating the file type.

### 🔗 [Github Themes VS Code Extension (VSCode Theme)](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)

- This is a VSCode theme that is similar to the theme on the GitHub website.

### 🔗 [Live Server VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

- This is a vSCode extension used to create a local server that can open web pages in the browser. It automatically refreshes the page and applies new changes after every save of the page in the code editor.

### 🔗 [W3C HTML Validator](https://validator.w3.org/)

- A tool at the W3C (World Wide Web Consortium) website that checks HTML files for errors.
- W3C is the organization that makes the standards of the web overall.
## References

### 1. [MDN: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

### 2. [HTML language codes list](https://www.w3schools.com/tags/ref_language_codes.asp)
