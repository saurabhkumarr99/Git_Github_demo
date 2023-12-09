# Git Github Practice

# Description
To practice upon Git Github

## Project Link
- Github: [Git-Github-Demo](https://github.com/saurabhkumarr99/Git_Github_demo)


## Getting Started

1. **Initialize Git :**

   ```bash
   git init
   git status
   ``` 

 <p align="center">
   <img src="./ScreenShots/1-Git init.png" alt="Screenshot 1" width="300" />
 </p

2.**Git add in staging area :**

   ```bash
   git add .
   git status
   ``` 

3.**Git Commit :**

   ```bash
    git commit -m "first commit"
   ``` 

 <p align="center">
  <img src="./ScreenShots/2-Git commit.png" alt="Screenshot 1" width="300" />
</p

4.**Create new branch :**

   ```bash
   git checkout -b dev1
   git branch
   ``` 

 <p align="center">
  <img src="./ScreenShots/3-Created new branch dev1.png" alt="Screenshot 1" width="300" />
</p

5.**Updated  in new branch:**

   ```bash
   git add .
   git commit -m "Updated by dev1"
   ```


 <p align="center">
  <img src="./ScreenShots/4-Updated by dev1.png" alt="Screenshot 1" width="300" />
</p

6.**Create and resolve merge conflict:**

 - `Create new branch dev2`
   ```bash
   git checkout -b dev2
   ``` 
 - `Update and commit new change in branch`
    ```bash
    git status
    git add .
    git commit -m "Added by dev2"
    git stataus
   ```

 <p align="center">
  <img src="./ScreenShots/6-Craeted new branch dev2.png" alt="Screenshot 1" width="300" />
 </p

  - `Merge dev2 into master branch`
   ```bash
    git checkout master
    git status
    git merge dev2
    git stataus
   ```

 <p align="center">
  <img src="./ScreenShots/7-Merger dev2 to master.png" alt="Screenshot 1" width="300" />
 </p

  - `Update by dev1 branch`
   ```bash
    git checkout dev1
    git status
    git add .
    git commit -m "New line added by dev1"
    git stataus
   ```
   
 <p align="center">
  <img src="./ScreenShots/8-Upadted by dev1.png" alt="Screenshot 1" width="300" />
 </p

   - `Merge conflict generated`
   ```bash
    git checkout master
    git merger dev1
   ```
   
 <p align="center">
  <img src="./ScreenShots/9-Merge conflict.png" alt="Screenshot 1" width="300" />
 </p

- `Resolved Merge conflict`
   ```bash
    git add .
    git commit -m "Resolved merge conflict"
    git status
   ```
   
 <p align="center">
  <img src="./ScreenShots/10-Resolve merge conflict.png" alt="Screenshot 1" width="300" />
 </p

7.**Create a Github Repository:**

- Github: [Git-Github-Demo](https://github.com/saurabhkumarr99/Git_Github_demo)
- `Selenium Testing`

  <p align="center">
   <img src="./ScreenShots/10-Resolve merge conflict.png" alt="Screenshot 1" width="300" />
  </p

3. **Push project to Github Repository:**

- Github: [Git-Github-Demo](https://github.com/saurabhkumarr99/Git_Github_demo)
- `Selenium Testing`

  <p align="center">
   <img src="./ScreenShots/10-Resolve merge conflict.png" alt="Screenshot 1" width="300" />
  </p
## Usage

1. *Learn Git Commands** 



## Author

- SAURABH KUMAR RAI

