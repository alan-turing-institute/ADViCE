# Contribution Guide for ADViCE Knowledge Base
[toc]
# Contributing Content to the ADViCE Knowledge Base
## Prerequisites
1. You must have a GitHub account
## Structure of ADViCE Knowledge Base
Follow this link for the [ADViCE Knowledge Base](https://github.com/alan-turing-institute/ADViCE/tree/main)
This is what it looks like when you land on the page:

---

![image](https://hackmd.io/_uploads/HkgeBzbnp.png)

---
You only need to worry about the [content]() folder, which is where the Knowledge Base content is stored. **Do not modify the content anywhere else please**.

## Procedure
There is a specific procedure depending on the content contribution you wish to make:
- Text file that is already in MarkDown format
- Text file that is not in MarkDown format (e.g. Word, PDF, PPT,...)
- Video submission (e.g. Webinar video)
### Text file that is already in MarkDown format
- Follow the template
    - Write content in MD
    - Test it locally
    - Specify location you want
    - ONLY ADD STUFF IN THE CONTENTS FOLDER, DO NOT TOUCH ANYTHING ELSE
    - Fran will input it?
- Formatting
    - YAML metadata at the top of every new document
        - Important for title
    - _index.md Files
    - 
- Running locally so that content can be tested quickly
    - Make sure you have Hugo and Git/GitHub CLI installed
    - Clone the repository
    - run ```hugo server -D``` in the command line
    - On the browser, type the local URL given in the command line
- Types of file
    - PDF
    - MP4/any video file
        - put on YouTube
    - Word
- Type of people uploading the content
    - ADViCE team
    - Someone external to ADViCE
### Text file that is not in MarkDown format (e.g. Word, PDF, PPT,...)

### Video submission (e.g. Webinar video)

# Technical Guidance
- Built with [Hugo](), using the [Hugo Techdoc Theme]()

# Setting up the Knowledge Base
- Install Hugo in your computer
- Follow [these steps](https://gohugo.io/getting-started/quick-start/) (i.e. create local git repository and Hugo site locally first)
- Install Hugo Techdoc
    - First cd to folder where you have your project's repository
    - Then on the command line run ```
git submodule add https://github.com/thingsym/hugo-theme-techdoc.git themes/hugo-theme-techdoc```
    - This way, the files required for the template are installed.
- In the hugo.toml file:
    - Change URL to the ADViCE GitHub
    - Change ``` theme = 'hugo-theme-techdoc' ```
    - Add [Techdoc params](https://thingsym.github.io/hugo-theme-techdoc/getting-started/configuration/) to hugo.toml file
    - Remove Algolia stuff and other unnecessary things
- Run ``` git remote add [ADViCE github url]``` to connect ot the ADViCE online GitHub repository
- Commit and push all files to remote
- Create a GitHub workflow so that every time content is merged onto the main branch of the ADViCE GitHub, the website is recompiled
    - Follow the steps in [this page](https://gohugo.io/hosting-and-deployment/hosting-on-github/), which is literally just creating a YAML GitHub workflow file and marking it as the workflow file in the GitHub repository.
    - Going to GitHub Actions, you should be able to see how the workflow is triggered every time you add new content to the ADViCE repository.
- Now we are ready to add files into the *contents* folder
