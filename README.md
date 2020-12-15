# HTML
   HTML is the standard markup language for creating websites and CSS is the language that describes the style of an HTML document. We will combine HTML and CSS to create a basic web page.
   For creating an html page we use tags
   * <html></html>:- It element is the root element of an HTML page.
   * <title></title>:- It specifies the title of the document.
   * <head></head>:- It contains title tag and css codes are write inside it.
   * <body></body>:- It contains the element of our website.
  These are the basic HTML tag used for to create html page. Other tags are <style>,<p>,<font>,<i>,<u>,<b>,<align>,<marque>,etc.
  For styling html pages we use css(cascade style sheet)
  
   
# WORKFLOW OF GIT
1. #### **Creating a new repository**
    * Creating new empty repository named local.
    
2. #### **Create a local git repo**
    * Creating a local git repo named WebGit.
    
3. #### **Initialize the git** 
    * Firstly we install git on our system using `sudo apt install git`
    * We use command for initializing git in the folder ``git init.
    
4. #### **Setting git configurations**
    Using the following commands for configurations.
    * `git config --global user.name "SREELEKSHMIPRATHAPAN"`
    * `git config --global user.email "sreelekshmitml@gmail.com"`

5. #### **Cloning the github repository**
    * To clone use the command `git clone https://github.com/SREELEKSHMIPRATHAN/local.git`

6. #### **Adding files to the repository**
    * Via upload files add all the programs into the github repository.

7. #### **Add remote repostory as origin and create version**

   First,need to set your central repository as origin using the following command:

    * To clone use the command `git clone https://github.com/SREELEKSHMIPRATHAN/local.git`
    `git remote set-url origin `
    `git pull origin master`

8. #### **Git push**

    The `git push` command transfer commits from your local repository to your remote repository.The use of  `git push` is to publish your local changes to a central repository. The following command is used for push operation,

    `git push origin master`

