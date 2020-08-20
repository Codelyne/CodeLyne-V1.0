# CodeLyne-V1.0
Official Version 1.0 website for CodeLyne.com

****************
PM : Daniel Bemsen
@Realice
<danireptor7@gmail.com>
****************

Create a proper file structure arrange your folders and file well...
The assets folder contains the various folders for css, images, js.

Please before you push your codes to the repository make sure you pull from the repository, so the changes that have been made can be reflected on your local machine, for us to avoid merge conflicts use the git command line
   
    git pull upstream BranchName

## Developers guide

This process here should be able to guide you on how to contribute effectively to this project, follow the steps below. You should not be new to the git workflow process however if you still are, the guide should still be able to help you through the process.

## Develop is the default branch

    * Fork the repository to generate a copy of your own. Please fork.

    * Clone the repository.

        ```
            git clone (the repository link)
        ```
        
    * Make your forked repo the remote upstream 
        ```
            git remote add upstream https://github.com/CodeLyne/CodeLyne-V1.0.git
        ```
    * swich to your branch 

    **make sure you are working on the branch inline with your story on trello (story 1 === branch 1)** 

        ```
        git checkout (name-of-branch)
        ```

    After changes have been made do:
        ```
        git pull upstream
        ```
    Consistently pull from the upstream to avoid not getting your pull request merged and to avoid conflicts.
    This way you can resolve conflicts from your local computer even before pushing always check what branch you are on when making changes
    
    * Make your changes, add them and make your commits

        ``` 
        git commit -m "your message"
        ```
    Write good commit messages, this is very important, so people reviewing can know what your code is doing.

    * Push your codes to your forked repository, make sure you are pushing to your branch please
        
        ```
            git push origin (name-of-branch)
        ```
    Make your Pull request from that branch of your repo to the branch of this repo and wait for it to be merged.

Write good commit messages, this is very important, so people reviewing can know what your fix, feature e.t.c. is doing
Your PR should carry good story. 
Dont forget to add it to your trello story
if you are going to make changes to an existing code, state why you are doing so in the commit messages

it is not just about the code, user workflow matters too!!

### Code with Love