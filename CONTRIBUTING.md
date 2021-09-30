# Contributing Guildelines for the L.E.O WEBSITE

* * *

There are mainly three sectors in which anyone can contribute to the our Website:
* Authoring a post (The Blog could be about anything realted to **Literature**.)
* Reporting an issue and giving suggestions.
* Localizing it or contributing to the code.

---

## Points to remember:
### 1. Local Setup:
    
   For setting up locally Fork the repositry and clone it using the commands given below in the terminal.
    
 ```sh
    # create a local clone of the repository
    git clone https://github.com/YOUR-USERNAME/leomvit.github.io.git
    # switch to the created directory
    cd leomvit.github.io.git
    # start local server
    bundle exec jekyll serve
 ```
  This will start the Jekyll Server.
   
   If the server does not start, you might not have the necessary dependencies installed. Refer the next section.

### 2. Dependencies Required: 

   This website is built with **Jekyll**, which is a website generator it is designed for building static blogs.
   
   Please follow the steps below to setup the dependencies:</br>
    1. Install Jekyll locally via command line.</br>
    2. Clone a starting point to local machine, build the website and serve it locally.
    
   For above stated steps and more you need to get familiar with GIT and GITHUB to know more about it and installation refer : [GIT/GITHUB](https://blog.glugmvit.com/gitpart2/)
   
   To know about how to contribute to open source and setting up refer: [CONTRIBUTE](https://blog.glugmvit.com/opensource/)  
   
   * * *
  
 ## Adding Post :
  There are two ways you can add posts:
   * Using _Github Editor_
   * Using _Local Editor_
   
   The Second way is more preferable more begineers as there are less chances of making mistakes and all the changes one can check on Local server.
   1. **Using _Github Editor_**
       * You can easily write your blog by adding the contents uder the _posts category.Make sure you write the content in the markdown format and save the file in filename.md
       form. '.md' refers to Markdown one can easily learn [Markdown](https://www.markdowntutorial.com/), it helps the author to write thhe content with ease and make the blog look decent. 
       * Change the file in name to today's date and the title of the post. Jekyll needs the file to be named year-month-day-title.md format. Update the title at the top of the Markdown file.
       * You can check the sample blogs and add headers from there.The sample blogs are in _drafts folder.
   2. **Using _Local Editor_**
       * You can use any editor of your choice but the most common editor used is [VScode Editor](https://code.visualstudio.com/download).Then add yout post under the _post category and name the file in year-month-day-title.md format.
       * Commit your post's markdown fike and push to your GITHUB repository. The steps to commit and pushing the file is included in above shared links.
       
      **Adding Author Details:**
       - You can add the your details while adding your post. 
       - Go to _config.yml file and make changes as stated there and save the file.
       - Go to _pages and add make a newfile and add your details.
      
      **Adding images:**
       - Navigate to _assets and then images. 
       - For adding **author profile**, go to authors and add yoir image.
       - For adding **images for posts**,either make your own folder or just add your images.
         (Images should be in .jpg, .jpeg or .png format)

   * * *
   ## Hosting on GitHub and Pull Request 
   You can use the following commands to push your changes.
      
 ```sh
       
       # Check the staus of files changed 
       git status
       # Adding the files to Commit
       git add <file name>
       # Commiting the chnages 
       git commit -m "message"
       # Pushing the changes to your github repo
       git push
       
```
    
  After the changes being pushed go to your Github Repository and make a Pull request.The maintainer will go through your changes and suggest if any more changes nededs to be done and merge your changes. 
  
  This is how easily you can write a blog and contribute to Our L.E.O Website.
  
  Thank you!
   
 
    
