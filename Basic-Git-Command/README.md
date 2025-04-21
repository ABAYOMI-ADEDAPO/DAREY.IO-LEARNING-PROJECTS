# ai_startup_website

This mini project simulates the collaboration between two software engineers with the use of GitHub.
The project involves step-by-step project to simulate workflow of Tom and Jerry using Git and GitHub. The project includes the installation of Git, setting up a GitHub repository, cloning the repository, creation of branches, making changes, and merging those changes into the main branch.

### Part 1 Setup and Initial Configuration

 * Install git 

![](./img/Git%20installation%20Proof.png)

- Create and Clone repository 

![](./img/Creating%20a%20New%20Repo%201.png)

- First commit : 

    *git status*  
    *git commit -m "This is my first commit"*
 

![](./img/Git%20Commit.png)

### Part 2: Simulating Tom and Jerry's Work

- 1. Tom's Work:

  - create branch 

     *git branch*  
    *git checkout -b update-navigation*

  ![](./img/Git%20Branch.png)

  - Commit and push update


     *git push origin update-navigation*

  
  ![](./img/Git%20Collaboration%201.png)


- 2. Jerry's Work

  - create new branch

     *git checkout main*   
    *git pull origin update-navigation*  
     *git checkout -b add-contact-info*


  
  ![](./img/Git%20Pull.png)

  - update index file 

     *git push origin add-contact-info*

  
  ![](./img/git%20status&git%20add%20updated.png)

  ### Part 3: Merging Changes
  
   - 1. Tom's PR : ![](./img/tom-pr.png)
   - 2. Tom's PR merge : ![](./img/jerry-pr-merge.png)
   - 3. Brach Update and Synchronization ![](./img/tom-update-merge.png)
   - 4. Jerry's PR: ![](./img/jerry-pr.png)
   - 5. Jerry's PR merge: ![](./img/tom-merge-request.png)

   Repo link : https://github.com/ABAYOMI-ADEDAPO/DAREY.IO-LEARNING-PROJECTS/tree/main/Basic-Git-Command