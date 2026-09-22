# AI4DRR Organization Pages

This repository contains the source files for the public landing page of the AI4DRR organization.

Public website:

https://ai4drr.github.io/

## Purpose

This website serves as the main landing page for AI4DRR and provides an entry point to its projects and public resources.

Individual AI4DRR projects may have their own project pages, for example:

- Fonte — https://ai4drr.github.io/fonte/
- Mi-CAT — https://ai4drr.github.io/Mi-CAT/
- Chatbot — https://ai4drr.github.io/chatbot/

## Editing the Website

The organization landing page can be edited directly in this repository.

The main page is:

    index.html

Additional pages and static assets can also be added as needed.

For example:

    about.html
    css/
    js/
    images/

## Example Structure

The website structure is flexible. The example below shows one possible way to organize the files:

    ai4drr.github.io/
    ├── index.html
    ├── about.html
    ├── css/
    │   └── style.css
    ├── js/
    │   └── main.js
    └── images/
        └── logo.png

This is only an example. Website files and directories can be organized as needed.

## Publishing

GitHub Pages is configured directly in the repository settings.

Changes committed to the configured publishing branch are automatically reflected on:

    https://ai4drr.github.io/

There is no separate deployment workflow in `.github/workflows/` for this repository.

## Adding a New Page

For example, create:

    about.html

Once the change is committed and GitHub Pages finishes publishing, it will be available at:

    https://ai4drr.github.io/about.html

The same applies to HTML pages, stylesheets, JavaScript, images, and other static website assets.

## Important

Do not commit passwords, API keys, access tokens, credentials, or other secrets to this repository.

Remember that this is a public repository and its contents are publicly accessible.
