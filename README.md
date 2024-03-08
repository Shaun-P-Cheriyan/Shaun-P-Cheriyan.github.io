# How to host your resume online
## Purpose
The purpose of the this documention is as follows : 
1. Describe the practical steps of how you hosted and formated your resume for this assignment.
2. Relate the practical steps described above to the general principles of current Technical Writing, as explained in Andrew Etter's book Modern Technical Writing

## Prerequisites
The following are the prerequisites for hosting you resume/portfolio : 
1. Email
2. resume/portfolio written in Markdown format

## Instructions
The following are insturction on how to host you reume/portfolio:
 ### 1. Signup/in to your Github account.
* If you already have a Github account, sign in to your account. Otherwise, sign up for a Github Account using an email of your choice. Complete the procedures as recquired by Github.
* The reason why you are using GitHub is because of two main reasons : It provides a Distributed Version Control and it helps in hosting static websites through GitHub Pages.
  + According to Etter, one of the most important reasons why technical writers use Distributed Version Control systems is because developers prefer them. Additionally, Distributed 
  version control systems have a better performance than centralized systems and it allows you to work offline. Moreover, distributed version control systems allow mulktiple people to 
  work on the same file simultaneously.    
  + Etter mentions his love for static websites due their speed, portability, simplicity, and security. You can host static sites using services such as GitHub Pages without the need to worry
  about any of the technical details. 
* If you recquire more help, you can check out the following [documentation](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)
### 2. Create a repository
* After signing in, you will now be at the dashboard page. The way you can confirm this is by checking the title of the page at the top left corner. 
* If it dosen't show the word dashboard there, that means you are in a different page. If so, you can be redirected to the dashboard by simple clicking the GitHub logo on the top left corner, next to the page title.
* Once you are in the dashboard, you can create a new repository. Ensure that the repository name follows the following format : **username.gituhub.io**. Also, the repository should be made public
so that it can easily be hosted.
*  If you want more information on how to create a repository/project, you can check out the following [documentation](https://docs.github.com/en/get-started/start-your-journey/uploading-a-project-to-github)  
### 3. Upload a you resume 
* Now you can upload your resume by clicking the upload an existing file under quick setup.
* Ensure that the file name is index.md. This is because GitHub recognizes certain keywords for certain functions.The keyword "index.md" makes it so that the contents of this file is shown when the site is running.
* Once you have uploaded the file, click on Commit changes button to complete the upload.
* There are advantages to having your resume in markdown format in this case : 
  + According to Etter, lightweight markup languages, such as Markdown, makes it easier to make websites because it helps in easily producing well-formed XMLs which can be used to build sites. 
  + Additionally, the content in a lightweight markup language is more human readable in its raw form than its alternatives, easier to learn and cheaper in most cases. 
* If you recquire more help, you can check out the following [documentation](https://docs.github.com/en/get-started/start-your-journey/uploading-a-project-to-github)
### 4. Hosting you resume 
* After the recquired files are uploaded, now we can host the file.
* Go to the Settings option and click on it.
* Under Settings, choose the Pages section from the list of sections on the right. 
* In Pages section, ensure that the **Source** has the  **"Deploy from branch"** option selected.
* Now under the Branch, select the main branch and save it.
* With this, GitHub will begin the process of hosting you resume file.
* It will take a bit of time to host it. If you want to see the progress, select the **"<> Code"** option. 
* Onces you do so you can see a yellow dot next to the repository name. You can click on this to see the progress.


## More Resources
1. If you want to learn how to write in Markdown, you can find a informative turtorial in the following [Markdown turtorial site](https://www.markdowntutorial.com/)
2. If you want to learn the basics of how to write in GitHub Flavoured Markdown, you can find the information in the following [documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## Authors and Acknowlegements

## FAQs
<details>
<summary> Why is Markdown better than a word processor?</summary>
Lightweight markup languges, such as Markdown, are easier to learn and write than word processors, such as 
Microsoft Word, because it just focuses on the content of the documantatiionk rather than formating the documentation.
Another advantage is that markdown is cheaper, often of no cost, than word processors which often recquire people to buy liscences.  
 </details>

<details>
<summary> Why is my resume not showing up?</summary>
 ### You can add a header

You can add text within a collapsed section. 

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```
 </details>
