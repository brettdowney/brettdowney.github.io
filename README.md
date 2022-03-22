# **How to Host and Format a Resume using Markdown, a Markdown Editor, GitHub Pages, and Jekyll**
---

## **Purpose**  
The goal of this document is to provide instructions on how to host and format a Markdown resume on GitHub Pages using the principles and tools in Andrew Etter's book [*Modern Technical Writing*](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS). It is assumed that the reader has no prior experience with Markdown and GitHub. 

---
## **Table of Contents**
- [Documentation Tools](#documentation-tools)
- [Prerequisites](#prerequisites)
- [Instructions](#instructions)
- [More Resources](#more-resources)
- [Authors and Acknowledgments](#authors-and-acknowledgments)
- [FAQs](#faqs)
---
## **Documentation Tools**
This tutorial is built using the technical documentation tools and practices described in Andrew Etter's book [*Modern Technical Writing*](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS). To understand the tools used throughout the guide, below is a brief description of each.    
 
 **Markdown**

 - [Markdown](https://www.markdownguide.org/getting-started/) is a markup language used to format text documenation that will be displayed on the web. 
 
 **Markdown Editor**

 - A [Markdown Editor](https://www.oberlo.ca/blog/markdown-editors) is a writing tool used to convert text to HTML.

 **Static Site Generator**

 - A [Static Site Generator](https://www.cloudflare.com/en-ca/learning/performance/static-site-generator/#:~:text=A%20static%20site%20generator%20is,to%20users%20ahead%20of%20time.) is a tool used to manage web content and create websites.   

 **GitHub**

 - [GitHub](https://github.com/) is a web service used to store, manage, and host a project through version control.  

 **GitHub Pages**

 - [GitHub Pages](https://pages.github.com/) is a hosting service for static websites.  


 ---

## **Prerequisites**

#### Before proceeding, you will require the following tools: 

1. A current **Resume** formatted in **Markdown**. Visit this [site](https://www.markdownguide.org/getting-started/) for information about Markdown and click [here](https://www.markdownguide.org/basic-syntax/) to learn about formatting your resume using Markdown.   
    
2.  A **Markdown Editor** (recommended, but not required). Visit [here](https://www.oberlo.ca/blog/markdown-editors) for a list of options based on your operating system.  
    - I personally used [Visual Studio Code](https://code.visualstudio.com/), which is a free open source Markdown desktop editor. For those new to Markdown and do not want to download anything try [Dillinger](https://dillinger.io/), which is an online editor with a live preview.

3. An account on **GitHub**, available [here](https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2Fnew). For those new to GitHub, here is a [quick tutorial](https://www.wikihow.com/Create-an-Account-on-GitHub) on how to create an account.

See the [More Resources](#more-resources) section below if you want to learn more about these tools. 

 
---

## Instructions

**Follow the steps below to learn how to host and format your resume on GitHub Pages.**

### Create a GitHub Repository
This is where you are going to store and host your resume. GitHub provides users with a platform to manage their projects and also their text documentation. In the *Modern Technical Writing*, Etter recommends using a distributed version control systems like Git. This allows for the storage of your text documentation in the same repository as your source code. It is also a benefit for when you want to update your project or have other developers contribute to it or review. 
1. Log in to your [GitHub account](https://github.com/login)
2. Click on the `[+]` button in the upper right-hand corner of the page 
3. Select `[New repository]`from the drop down menu
4. Enter `[YourUserName].github.io` for the repository name (this must match the user name that you used to create your account). For example, if your username is `[dragon]`, then enter `[dragon.github.io]`
5. Select `[Public]`
6. Click on `[Create repository]`  

### Next, Add your Markdown Formatted Resume to GitHub
Markdown is a lightweight markup language and is one of the documentation tools recommended by Etter. It provides users with a simple and easy way to write and format text documents that can be published to the web in HTML. Once you try Markdown, you may never want to use *Word* again.  

7. Click on `[Addfile]`  
8. Select `[Create new file]`,located under the drop-down menu  
9. Enter `[index.md]` in the box showing `[Name your file]`  
10. Press enter  
11. Copy and Paste your saved Markdown- formatted resume into the blank text area  
12. Select `[Commit new file]`, which is located at the bottom right of the page
#### To verify and view your Markdown Resume try this:  
13. Click on the `[index.md]` in your repository **OR** Enter `[http://YourUserName.github.io/]`

### Next, Build a Static Website with GitHub Pages
Setting up GitHub Pages allows you to  host and share your resume through static websites. Etter recommends using static websites as they are easy to install, fast, portable, and provide a level of security as they never crash. Also, any changes to your resume through your GitHub Pages will be seen almost immediately.  

14. Click on the `[Settings]` tab in your repository  
15. Scroll down the page until you see **GitHub Pages**  
16. Click on `[Check it out here!]`

### Finally, Customize your Resume with a **Static Site Generator** such as Jekyll 
Jekyll is a static site generator that is used to create websites. According to Etter's prinicples, static site generators such as Jekyll are styling tools used to make your documentation look professional. There are many static site generators available to select from, each with its own themes to allow for a customized website.    

17. Click on `[Choose a theme]`located on your GitHub Pages    
18. Scroll through the different Jekyll themes until you find one that you like for your resume
19. Click on the `[Select Theme]` button to select the desired theme
20. Select the `[Code]` tab in your GitHub Pages; there should be a file called `[_config.yml]`
21. Click on `[_config.yml]`
22. Click on the `[pencil icon]` located on the right hand-side of the page
23. Add a line of code under line 1 by entering `[title: YourName Resume]`
24. Scroll to the bottom of the page and select `[commit changes]`

  

#### Congratulations!!! Your resume in now available at `[https://(YourUserName).github.io/]`  
---


**Depending on the theme you selected, your website should look something like this:**

![gif displaying resume](https://i.imgur.com/Jsq1vhe.gif)


Click [here]( https://brettdowney.github.io/) to check out my resume. 

---

## More Resources
- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet)
- [GitHub Tutorial](https://docs.github.com/en/get-started/quickstart/hello-world)
- [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) by Andrew Etter
- [Setting up Jekyll](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages#setting-up-jekyll-)
---


## Authors and Acknowledgments
Guide written by [Brett Downey](https://github.com/brettdowney/brettdowney.github.io)

Jekyll theme template used: **Slate**

Thank you to the following group members for their feedback of this guide:

- Chris Rogers
- Xian Mardiros
- Christian Bera
- Ashish Ashish
---


## FAQs
**Why is Markdown better than a word processor?**  
 Markdown provides a simple and effective way to publish text online as it is easy to convert to HTML, unlike a word document. With Markdown, you can use any text editor for writing and it also allows for the ability to be portable and works on any operating system. Markdown is vesatile and can be used for creating resumes, writing emails, publishing books, or writing technical documentation.   

 **Why is my resume not showing up?**  
 If you resume is not showing up check to ensure your repository is named correcty (YourUserName.github.io). Also, try waiting a few minutes and refreshing, sometimes it takes a few minutes to appear.    
