# How to host your resume online
## Purpose
The purpose of this documentation is to show the practical steps on how to host and format your resume and relate these steps to the general principles of current Technical Writing, as explained in Andrew Etter's book Modern Technical Writing.

## Prerequisites
The following are the prerequisites for hosting you resume/portfolio : 
1. Email
2. Resume/portfolio written in Markdown format

## Instructions
The following are instructions on how to host you resume/portfolio:
 ### 1. Sign up/in to your GitHub account.
>* Go to the [GitHub Website](https://github.com/).
>* Sign in to your account, if you already have a GitHub account. 
>* Sign up for a GitHub account using an email of your choice otherwise. 
>* Complete the procedures as required by GitHub.
>``` 
>The reason why you are using GitHub is because of two main reasons : It provides a Distributed Version Control and it helps in hosting static websites through GitHub Pages.
>  * According to Etter, one of the most important reasons why technical writers use Distributed Version Control systems is because developers prefer them. Additionally, Distributed 
>    version control systems have a better performance than centralized systems and it allows you to work offline. Moreover, distributed version control systems allow multiple people to 
>    work on the same file simultaneously.
>  * Etter mentions his love for static websites due their speed, portability, simplicity, and security and suggests that you can host static sites using services such as GitHub Pages without the need to worry
>    about any of the technical details. 
  >```
>* If you require more help, you can check out the following [documentation](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account).
### 2. Create a repository
>* After signing in, you will now be at the dashboard page. It should look like this :
>>![Dashboard GitHub.png](..%2F..%2F..%2FDesktop%2FDashboard%20GitHub.png)
>>Dashboard
>* Click the GitHub logo on the top left corner, next to the page title if you are in another page. You will be brought to the dashboard page.
>> ![GitHub Logo.png](..%2F..%2F..%2FDesktop%2FGitHub%20Logo.png)
>>
>> GitHub Logo
>* Go to the **Start a new repository for [username]** section. 
>> ![GitHub - Create a repo.png](..%2F..%2F..%2FDesktop%2FGitHub%20-%20Create%20a%20repo.png)
>>
>>Start a new repository for [username]
>* Enter your repository name.
>* Ensure that the repository name follows the following format : **username.github.io**.
>* Click on the **Public** option which makes the repository public so that it can easily be hosted.
>* Click on the **Create a new repository** button.
>*  If you want more information on how to create a repository/project, you can check out the following [documentation](https://docs.github.com/en/get-started/start-your-journey/uploading-a-project-to-github)  
### 3. Upload a your resume 
>* Click on the **upload an existing file** link under the quick setup section.
>>![GitHub - upload an existing file.png](..%2F..%2F..%2FDesktop%2FGitHub%20-%20upload%20an%20existing%20file.png)
>> Quick setup 
>* Click on the **choose your file** link.
>>![GitHub - choose you files.png](..%2F..%2F..%2FDesktop%2FGitHub%20-%20choose%20you%20files.png)
>>choose you files
>* Select the resume file you want to upload. Resume file must be in Markdown format.
>* Ensure that the file name is **index.md**. 
>* If not, rename the file before uploading. This is because GitHub recognizes certain keywords for certain functions. The keyword "index.md" makes it so that the contents of this file is shown first when the site is running.
>* Click on **Commit changes** button at the bottom of the page to complete the upload.
>```
>There are advantages to having your resume in markdown format in this case : 
>  * According to Etter, lightweight markup languages, such as Markdown, makes it easier to make websites because it helps in easily producing well-formed XMLs which can be used to build sites. 
>  * Additionally, the content in a lightweight markup language is more human readable in its raw form than its alternatives, easier to learn and cheaper in most cases. 
>```
>* If you require more help, you can check out the following [documentation](https://docs.github.com/en/get-started/start-your-journey/uploading-a-project-to-github)
### 4. Hosting you resume
>* You should be in the repository page. It looks like this : 
>> ![GitHub - REpo page.png](..%2F..%2F..%2FDesktop%2FGitHub%20-%20REpo%20page.png)
>* Click on the **Settings** option in the top.
>>![GitHub - Settings.png](..%2F..%2F..%2FDesktop%2FGitHub%20-%20Settings.png)
>> Setting Option
>* Click the Pages section from the list of sections on the left. 
>> ![GitHub - Pages.png](..%2F..%2F..%2FDesktop%2FGitHub%20-%20Pages.png)
>> Pages 
>* Ensure that the **Source** has the  **"Deploy from branch"** option selected.
>> ![GitHub - Source.png](..%2F..%2F..%2FDesktop%2FGitHub%20-%20Source.png)
>>
>> Source
>* Select the main branch under the branch section if the main branch is not selected by default.
>>![GitHub - Branch.png](..%2F..%2F..%2FDesktop%2FGitHub%20-%20Branch.png)
>> Branch
>* Click on the save Button.
>* With this, GitHub will begin the process of hosting you resume file. It will take a bit of time to host it. 
>* Select the **"<> Code"** option.
>* Click on the yellow dot next to the repository name to see the progress.
>> ![GitHub - yello spot.png](..%2F..%2F..%2FDesktop%2FGitHub%20-%20yello%20spot.png)
>> See Progress
## Set a theme
>* Now we can add a theme so that the resume can look presentable.
>* Click on the **Add file** button.
>* Click the **+ Create new file** button.
>>![GitHub Add File.png](..%2F..%2F..%2FDesktop%2FGitHub%20Add%20File.png)
>> Add file
>* Write "**_config.yml**" in  the **Name your file...** space.
>* Write "**theme: jekyll-theme-minimal**" in the **Enter you contents** space in the text box.
>>![GH - Config file.png](..%2F..%2F..%2FDesktop%2FGH%20-%20Config%20file.png)
>> Writing the file
>* Click the **Commit changes...** on the right side. This will enable a Commit changes pop up.
>* Click the **Commit changes** button at the bottom right of the pop up.
>* Now wait for some time until the site is built.
>* You can access the site by going to **username.github.io**
>* It should look like the following : 
>![Resume Gif.gif](..%2F..%2F..%2FDesktop%2FResume%20Gif.gif)
>```
> Etter suggests writers to take time to customize their pages as this will help in differentiating you content for the others.
>```

## More Resources
1. If you want to learn how to write in Markdown, you can find a informative tutorial in the following [Markdown tutorial site](https://www.markdowntutorial.com/)
2. [Basics of GitHub Flavoured Markdown documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
3. [How Github Works](https://youtu.be/w3jLJU7DT5E?si=Xh75Kqty2_t0Yw3-)
4. [GitHub Docs](https://docs.github.com/en/get-started)
5. [Modern Technical Writing: An Introduction to Software Documentation by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/ref=sr_1_1?s=digital-text&sr=1-1)

## Authors and Acknowledgements
> ReadMe Author - Shaun Paraplammoottil Cheriyan
> 
>Theme Author - GitHub

> I want to thank :
> 
> My professor, Stewart Wilcox, for providing the opportunity for this assignment, resources for learning, and the help given throughout its completion.
> 
> My group mates, Aswin Manoj and Zack Wiebe, for their critiques and suggestion which helped me improve the quality of my submission.
> 
> Andrew Etter for the Modern Technical Writing Book which provided a deeper insight to technical writing

## FAQs
<details>
<summary> Why is Markdown better than a word processor?</summary>

>Lightweight markup languages, such as Markdown, are easier to learn and write than word processors, such as 
>Microsoft Word, because it just focuses on the content of the documantation rather than formatting.
>Another advantage is that markdown is cheaper, often of no cost, than word processors which often require people to buy licences.  

 </details>

<details>
<summary> Why is my resume not showing up?</summary>

> Heres are several reasons and fixes for this problem : 
> * **Wrongly written Markdown file** : Make sure that your Markdown files are written correctly with the right syntax.
> * **Incorrect repository name format** : Make sure that you repository name follows the correct format (username.github.io).
> * **Incorrect files names** : Ensure that the *index.md* and *_config.yml* files have the correct names.
> * **Empty files** : Ensure the the resume contents are in the *index.md* file anf the themes are in the *_config.yml*  file.
> * **Wrongly written configuration file** : Make sure that your *_config.yml* file is written correctly with the right syntax.
 </details>
