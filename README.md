To contribute in this repository, perform the following steps.

Fork this repository.
Now run the following code in your terminal/prompt : 

clone the forked repository(the repository made in your account after you forked this repo) by running this command : 
*** git clone https://github.com/(YOUR_USERNAME)/icefeet-2020.git ***
 
1. cd icefeet-2020
This command will take you to the folder containing the code.
Currently you are on your master branch. Inorder to contribute to my repo, you need to work on another branch in your repository.

2. git remote add upstream https://github.com/jhasaurabh312/icefeet-2020.git
This command set this repo as your upstream repository.

3.git pull upstream master
By performing this you locally have the updated code present in this repo.

4. git checkout -b "develop"
This command will create a new branch named develop in your repository and you are on the develop branch.

DO ALL THE CHANGES YOU WANT TO DO IN THE CODE.

5. git add.
6. git commit -m "COMMIT_MESSAGE"
7. git push origin develop

By doing step 5,6,7 you have pushed your updated code on the develop branch of your repository.

8.Make a pull request from your repo to this(original) repo.

       Click on the green pull request button.
       Base repository : THIS REPOSITORY.    Base : MASTER
       Head repository : YOUR REPOSITORY.    Compare : develop(branch name you are working on)

9. Once your pull request gets merged, Do the following steps : 

   git checkout master   (this step just changed your working branch from develop to master)
   git pull upstream master (you got the new code from this repo in your master branch)
   
10. In order to further contribute to this repo : 

      REPEAT THE STEPS FROM STEP-4 with a new branch name(branch name was develop until now)
      E.g. git checkout -b "XYZ"
      
      
      
*****KEEP CONTRIBUTING AND HAPPY CODING********************      
          
          
   
   





 
 

 
