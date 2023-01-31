# VS Code extension that I use

## List of extension

- [VS Code extension that I use](#vs-code-extension-that-i-use)
  - [List of extension](#list-of-extension)
    - [Code Spell Check](#code-spell-check)
    - [Markdownlint](#markdownlint)
    - [Markdown all in one](#markdown-all-in-one)
    - [TODO Highlight](#todo-highlight)
    - [Todo Tree](#todo-tree)
    - [Gitlens](#gitlens)
    - [Markdown Preview Mermaid Support](#markdown-preview-mermaid-support)
    - [Azure Account](#azure-account)
    - [Azure Functions](#azure-functions)
    - [Azure Logic Apps (Standard)](#azure-logic-apps-standard)
    - [Azure Resources](#azure-resources)
    - [Azurite](#azurite)
    - [C sharp](#c-sharp)
    - [Docker](#docker)
    - [Shopify Liquid](#shopify-liquid)
    - [GitHub Pull Requests and Issues](#github-pull-requests-and-issues)
    - [REST Client](#rest-client)
    - [Dendron Paste Image](#dendron-paste-image)
    - [Markdown Emoji](#markdown-emoji)
    - [Todoist](#todoist)
    - [VSCode-pdf](#vscode-pdf)
    - [Not Installed](#not-installed)
  - [Workspace recommended extensions](#workspace-recommended-extensions)
  - [Extension settings](#extension-settings)
    - [markdownlint](#markdownlint-1)

### Code Spell Check

This is extension for spell check and it can be found at [Link](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker).

### Markdownlint

This is extension for linting and adding extra style to markdown files. This extension can be found at [Link](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

### Markdown all in one

This is extension for markdown formatting shortcuts.
[Link](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

### TODO Highlight

This is extension to highlight the tags(Todo/Fix it etc..) you have in your file.
[Link](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

### Todo Tree

This is extension for pulling all todo and showcasing them.
[Link](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

### Gitlens

This is extension helps working with git repository by enhancing the ability of vs code.
[Link](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

### Markdown Preview Mermaid Support

This extension provides mermaid support to markdown preview of vscode.
[Link](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)

### Azure Account

The Azure Account extension provides a single Azure sign in and subscription filtering experience for all other Azure extensions. It makes Azure's Cloud Shell service available in VS Code's integrated terminal.
[Link](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account)

### Azure Functions

Use the Azure Functions extension to quickly create, debug, manage, and deploy serverless apps directly from VS Code. Check out the Azure serverless community library to view sample projects.

[Link](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions)

### Azure Logic Apps (Standard)

Use the Azure Logic Apps (Standard) extension to quickly create, debug, manage, and deploy Logic Apps directly from VS Code.
[Link](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurelogicapps)

### Azure Resources

View and manage Azure resources directly from VS Code.
[Link](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureresourcegroups)

### Azurite

Azurite is an open source Azure Storage API compatible server (emulator). Based on Node.js, Azurite provides cross platform experiences for customers wanting to try Azure Storage easily in a local environment. Azurite simulates most of the commands supported by Azure Storage with minimal dependencies.
[Link](https://marketplace.visualstudio.com/items?itemName=Azurite.azurite)

### C sharp

This extension provides the following features inside VS Code:
Lightweight development tools for .NET Core.
Great C# editing support, including Syntax Highlighting, IntelliSense, Go to Definition, Find All References, etc.
Debugging support for .NET Core (CoreCLR). NOTE: Mono debugging is not supported. Desktop CLR debugging has limited support.
Support for project.json and csproj projects on Windows, macOS and Linux.
[Link](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)

### Docker

Docker for Visual Studio Code Version Installs Build Status
The Docker extension makes it easy to build, manage, and deploy containerized applications from Visual Studio Code. It also provides one-click debugging of Node.js, Python, and .NET Core inside a container.
[Link](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

### Shopify Liquid

Official VS Code extension for Shopify Liquid powered by Theme Check the Liquid linter and language server for online store themes.
[Link](https://marketplace.visualstudio.com/items?itemName=Shopify.theme-check-vscode)

### GitHub Pull Requests and Issues

This extension allows you to review and manage GitHub pull requests and issues in Visual Studio Code. The support includes:

- Authenticating and connecting VS Code to GitHub and GitHub Enterprise.
- Listing and browsing PRs from within VS Code.
- Reviewing PRs from within VS Code with in-editor commenting.
- Validating PRs from within VS Code with easy checkouts.
- Terminal integration that enables UI and CLIs to co-exist.
- Listing and browsing issues from within VS Code.
- Hover cards for "@" mentioned users and for issues.
- Completion suggestions for users and issues.
- A "Start working on issue" action which can create a branch for you.
- Code actions to create issues from "todo" comments.

[Link](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)

### REST Client

REST Client allows you to send HTTP request and view the response in Visual Studio Code directly.

- Send/Cancel/Rerun HTTP request in editor and view response in a separate pane with syntax highlight
- Send GraphQL query and author GraphQL variables in editor
- Send cURL command in editor and copy HTTP request as cURL command
- Auto save and view/clear request history
- Compose MULTIPLE requests in a single file (separated by ### delimiter)
- View image response directly in pane
- Save raw response and response body only to local disk
- Fold and unfold response body
- Customize font(size/family/weight) in response preview
- Preview response with expected parts(headers only, body only, full response and both request and response)
- Authentication support for:
  - Basic Auth
  - Digest Auth
  - SSL Client Certificates
  - Azure Active Directory
  - Microsoft Identity Platform
  - AWS Signature v4
- Environments and custom/system variables support$$
  - Use variables in any place of request(URL, Headers, Body)
  - Support environment, file, request and prompt custom variables
  - Interactively assign prompt custom variables per request
  - Auto completion and hover support for both environment, file and request custom variables
  - Diagnostic support for request, file and prompt custom variables
  - Go to definition support for request and file custom variables
  - Find all references support ONLY for file custom variables
  - Provide system dynamic variables
    - `{{$guid}}`
    - `{{$randomInt min max}}`
    - `{{$timestamp [offset option]}}`
    - `{{$datetime rfc1123|iso8601 [offset option]}}`
    - `{{$localDatetime rfc1123|iso8601 [offset option]}}`
    - `{{$processEnv [%]envVarName}}`
    - `{{$dotenv [%]variableName}}`
    - `{{$aadToken [new] [public|cn|de|us|ppe] [<domain|tenantId>] [aud:<domain|tenantId>]}}`
  - Easily create/update/delete environments and environment variables in setting file
  - File variables can reference both custom and system variables
  - Support environment switch
  - Support shared environment to provide variables that available in all environments
- Generate code snippets for HTTP request in languages like Python, JavaScript and more!
- Remember Cookies for subsequent requests
- Proxy support
- Send SOAP requests, as well as snippet support to build SOAP envelope easily
- HTTP language support
  - .http and .rest file extensions support
  - Syntax highlight (Request and Response)
  - Auto completion for method, url, header, custom/system variables, mime types and so on
  - Comments (line starts with # or //) support
  - Support json and xml body indentation, comment shortcut and auto closing brackets
  - Code snippets for operations like GET and POST
  - Support navigate to symbol definitions(request and file level custom variable) in open http file
  - CodeLens support to add an actionable link to send request
  - Fold/Unfold for request block
- Support for Markdown fenced code blocks with either http or rest.

[Link](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

### Dendron Paste Image

Paste images directly from your clipboard to markdown/asciidoc(or other file)!
[Link](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-paste-image)

### Markdown Emoji

Adds :emoji: syntax support to VSCode's built-in Markdown preview and to ,markdown cells in notebooks.
[Link](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-emoji)

### Todoist

Todoist related extension for VSCode.
[Link](https://marketplace.visualstudio.com/items?itemName=waymondo.todoist)

### VSCode-pdf

VSCode-PDF is extension for previewing PDF.

[Link](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf)

### Not Installed

These are extensions that are not installed but will be installed later.

- Markdown Preview Enhanced [Link](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

## Workspace recommended extensions

In order to view the workspace recommended extensions.
Do the following,

- Ctrl + Shift + P to go to command panel,
- Type "configure recommended extensions" and press "Enter"

Related images are,
![configure recommended extensions](images/configurerecommendedextensionscommand.png)

That way you will get to the workspace recommended extensions setting page.
At the time of writing following are the extensions,

```JSON
{
// See https://go.microsoft.com/fwlink/?LinkId=827846 to learn bout workspace recommendations.
// Extension identifier format: ${publisher}.${name}. Example: scode.csharp
// List of extensions which should be recommended for users of his workspace.
"recommendations": [
"yzhang.markdown-all-in-one",
"DavidAnson.vscode-markdownlint",
"wayou.vscode-todo-highlight",
"Gruntfuggly.todo-tree",
"bierner.markdown-mermaid",
"eamodio.gitlens",
"ms-vscode.azure-account",
"ms-azuretools.vscode-azurefunctions",
"ms-azuretools.vscode-azurelogicapps",
"ms-azuretools.vscode-azureresourcegroups",
"Azurite.azurite",
"ms-dotnettools.csharp",
"ms-azuretools.vscode-docker",
"Shopify.theme-check-vscode",
"GitHub.vscode-pull-request-github",
"humao.rest-client",
"dendron.dendron-paste-image",
"bierner.markdown-emoji",
"waymondo.todoist",
"tomoki1207.pdf"
],
// List of extensions recommended by VS Code that should not be recommended for users of this workspace.
"unwantedRecommendations": [
]
}
```

## Extension settings

### markdownlint

Had to make following adjustment to setting of Markdownlint extension, in order for inline html tag to be allowed. I had to do it, as for following reason,

- `<kyb>` used to show special keys like <kbd>Ctrl</kbd>, and
- `<mark>` inline html tag are required, as the preview window of VS Code does not support related markdown equivalent.

![Mark Down Lint Settings](images/markdownlintsettings.png)
