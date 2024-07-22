# Basic Repository Template

# 👀 About
This project is  
1) A template for README.md files in GitHub projects. 
2) A pull request template used for GitHub projects.  
* :octocat: [GitHub documentation](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) on how to create a repository from a template.

GitHub readme files should contain enough information at first glance that a person (maybe even your future self) can quickly understand the purpose of the project. In this about section, include a HIGH level description. Keep it short... reading be tough :cold_sweat:.  

<img src="docs/_images/webApp.gif" alt="Web App Gif" width="700"/>    

Add images and/or gifs! As they say, "An image is worth a thousand words"!  

📒 NOTE 📒  
* Use html styling when adding images so that you can control the size of the image. Example of above image: `<img src="docs/_images/webApp.gif" alt="Web App Gif" width="400"/>`. Only set the width OR height to preserve the aspect ratio.  
* Also, store the images in a separate folder under the docs folder, for example `/docs/_images`.

## Intended Audience
This repo is for developers creating new GitHub repositories.  
🔆 To use this repo as a template for your project, either copy/paste the raw code or see the instructions on [Using GitHub Templates](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)

---
# 📰 Table of Contents  

- 🖥️ [Application Overview](#🖥️-application-overview)
  - [Technologies Used](#technologies-used)
  - [Highlights](#highlights)
  - [Environment URL's](#environment-urls)
- 🛠️ [Application Usage (locally)](#🛠️-application-usage-locally)
  - [Pre-requisites](#local-execution-pre-requisites)
  - [Building locally](#building-locally)
  - [Running Automated Tests](#running-automated-tests)
  - [Running Locally](#running-locally)
- 🔗 [Related Resources](#link-related-resources)
  - [Scanning](#scanning)
  - [Monitoring](#monitoring)
  - [Other Resources](#other-resources)

---
# 🖥️ Application Overview
  - [Technologies Used](#technologies-used)
  - [Highlights](#highlights)
  - [Environment URL's](#environment-urls)

  ### Technologies Used
  ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)  

  📒 NOTE: 📒  
  For more information on badges (as seen above ⬆️) see [Other Resources](#other-resources) at the bottom of this page.

  ### Highlights

  In the [about](#👀-about) section, a very high level description of the application was given. Here is an opportunity to give more details on specific aspects of the app. Keep the highlights at a level everyone can understand. More technical details can be added below or in separate README files in the same repository. The goal of a good README is to provide clear documentation so that a developer can get everything they need to start using this repository without having to ask for assistance.

  ### Environment URLs
  
  If applicable, give urls for the different environments where this application can be used/seen.  
  | Environment   | URL   |
  | ------------- | ----- |
  | Development   | https://fakeurl.com/dev |
  | Quality Assurance | https://fakeurl.com/qa |
  | Production | https://fakeurl.com/ |  
  
  📒 NOTE: 📒  
  For more information on markdown tables (as seen above ⬆️) see "Markdown" under [Other Resources](#other-resources) at the bottom of this page.

---
# 🛠️ Application Usage (Locally)
  Instructions for setting up the application locally.  

  - [Pre-requisites](#local-execution-pre-requisites)
  - [Building locally](#building-locally)
  - [Running Automated Tests](#running-automated-tests)
  - [Running Locally](#running-locally)

  ### Local Execution Pre-requisites
  * Mac or PC
  * x86 processor
  * SDK vX.Y.Z required further instructions on installing this can be found [here](/docs/MORE_INSTRUCTIONS.md)

  📒 NOTE: 📒  
  * In order to keep this main README short and easy to read, it is encouraged to place further tangential instructions / information in separate *.md files.
  * *.md file naming convention is in all CAPS.
  * besides the main README.md file, other *.md files should be placed in the `/docs` folder

  ### Building locally
  1. Do this
     Clone from GitHub
      ```sh
      git clone <url>
      ```

  2. Then this  
      ```sh
      run build
      ```

  3. And finally this  
     Do stuff
  
  📒 NOTE: 📒  
  You can number each list item above with a 1 and markdown will automatically increment. This is helpful with long lists. You don't have to renumber the whole list every time you change an item in the beginning.
  
  ### Running Automated Tests
  * Run this command to execute unit tests  
    `run tests` 
  
  ### Running locally
  1. Run this command to build  
    `run build` 
  2. Run this command to start the app  
    `start app`

  📒 NOTE: 📒   
  Double space at the end of a line will force a carriage return on the rendered markdown.

---
# 🔗 Related Resources
  - [Scanning](#scanning)
  - [Monitoring](#monitoring)
  - [Resource Links](#resource-links)

  ### Scanning
  * Test results are stored [here](fakeLink)  
  
  ### Monitoring
  * Application monitoring can be found [here](fakeLink)
  
  ### Other Resources
  Here is a list of resources used in creating this README template:  

  #### Readme Template Resources
  * IDE & Plugins
    * This guide was created using [Visual Studio Code](https://code.visualstudio.com/download).  
    * With this [Markdown](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one#review-details) plugin.  

  * Guide to Markdown:  
    https://www.markdownguide.org/

  * List of markdown emojis:  
    https://gist.github.com/rxaviers/7360908

  * How to create badges:  
    https://shields.io/    

  * Lists of technology specific badges:  
    https://github.com/Ileriayo/markdown-badges#-languages
    https://github.com/alexandresanlim/Badges4-README.md-Profile#-frameworks--library-
    
  #### Pull Request Template Resources
  * GitHub guide for creating a PR template:
    https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository
