# How to Host a Resume on GitHub Pages

## Purpose

This readme describes the practical steps of how to host and format a resume using tools such as Markdown, Visual Studio Code, Jekyll, and GitHub Pages. This document will also introduce and reference the general principles of current Technical Writing found in Andrew Etter's book, Modern Technical Writing.

## Prerequisites

#### Your Resume in Markdown
* To host a resume page, you will need your resume to be formatted in Markdown. As the resume will be hosted using GitHub Pages, using GitHub Flavored Markdown would work best.
* Here's a link to learn [GitHub Flavored Markdown.](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

#### A Markdown Editor
* You will need a Markdown Editor to make your changes and write your Markdown formatted resume. The Markdown Editor used in this tutorial was Visual Studio Code.
* Here's a link to download [VSCode.](https://code.visualstudio.com/download)

#### A GitHub Account
* The resume will be hosted on GitHub Pages and thus you will need a GitHub account.
* Here's a link to join [GitHub.](https://github.com/join)

## Instructions

1. Create a new repository for your resume
    * Your repository name should follow this format: __\<username\>.github.io__
    * This will allow GitHub to recognize that your repository will be used for your static website with the URL __https://\<username\>.github.io/__

2. Copy the URL of your new repository

3. Open up Visual Studio Code

4. Clone your new repository
    * Drop your new repository's URL that you copied earlier!

5. Create an `index.md` file
    * This will hold your Markdown formatted resume

6. Create a `README.md` file
    * A standard file for any documentation about your page

7. Create a `_config.yml` file
    * This file will your page's configuration settings such as the Jekyll theme for your resume

8. Commit your changes locally

9. Push your new resume onto GitHub

10. Go to your repository on GitHub
    * Your 3 files should now be visible on your GitHub repository online

11. Go to your repository's Settings tab

12. Navigate to the Pages tab 
    * This should be under Code and Automation
    * Under Source, you should have Branch: main / root or Branch: master / root

14. Click Save under the Source section

15. View your static website at __https://\<username\>.github.io/__

15. Navigate back to the Pages tab

16. Under the Theme Chooser section, click the Change theme button

17. Choose the desired theme for your resume and click Select theme

## More Resources
* [Markdown Tutorial by CommonMark](https://commonmark.org/help/tutorial/)
* [GitHub Flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [GitHub Pages supported Themes](https://pages.github.com/themes/)
* [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Authors and Acknowledgements
* **Kyle Calinisan** - _Author_ - [kyl-dc](https://github.com/kyl-dc) 
* **Billie Thompson** - _Provided README Template_ - [PurpleBooth](https://github.com/PurpleBooth)
* Technical documentation concepts and ideas were referenced from [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) by Andrew Etter.

## FAQs (Frequently Asked Questions)
**1. Why is Markdown better than a word processor?**
Markdown is the most widely used lightweight markup language. (Etter, 2016) Compared to a word processor, Markdown is simply a plain text formatting syntax that makes it much easier to use. Additionally, the simplicity of Markdown makes it easier to learn without having several other buttons and functions for formatting like a word processor.

**2. Why is the selected theme not applying onto my resume?**
It may take around 5-10 minutes for your theme to render onto your resume. After changing the theme, you may view the GitHub Pages workflow under the Actions tab to see the changes being deployed onto your static website. If you are still unable to see the theme on your resume, try refreshing and deleting your browser cache. 