# How to make an online resume ?

## **Overview** 
Start from initializing a Git repository, and edit your resume online, finally can save it as `PDF` format and print it out.

## **What is Github Pages？**

`GitHub Pages` is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on `GitHub`, optionally runs the files through a build process, and publishes a website.
reference：https://help.github.com/articles/what-is-github-pages/

## **Quick Start**

 - **Github Account**
 Make a github account, and create a new repository with name as resume.
 - **About Template**
You can just clone my repositorty, [https://github.com/koshiryo/resume][1]
Or choose to download a new one. [All in chinese though.][2]
 - **Modify Your Resume**
Open the index.html file with your browser. You will find that this template is editable. All the text fields can be edited at will. Click on the image to replace it with the url of your resume pic.
 - **Modify HTML File**
After editing your resume, copy the modified code and replace it in the original `index.html`.
 - **Firefox**
Firefox: Open Viewer -> Copy the external HTML of the html tag
 - **Replace The Code**
Then replace all the content of the html tag in index.html (including the html tag).
 - **Submit The Code**
`git add .`
`git commit -m "update info"`
`git push origin master`
 - **Deploy Github Pages**
Open the project on github and click on `Settings` in the top right corner.
Go down and find GitHub Pages, select `master branch` in source, then click save.


  [1]: https://github.com/koshiryo/resume
  [2]: https://gitee.com/cool-resume?from=weekly-82
