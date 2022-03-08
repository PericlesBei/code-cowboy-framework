# Github
This folder contains two separate exercises.  
Firstly, clone this repository
```sh
git clone https://github.com/hellofresh/d-a-bnlf-code-cowboy-framework
cd d-a-bnlf-code-cowboy-framework
```

## Exercise_1
- **Create a new branch**
```sh
git checkout -b feature/DABNLF-<ticket_number><branch_name>
```
- **Navigate to exercise 1**. This exercise is located in this path `github/Exercise_1`.
```sh
cd github/Exercise_1
```
- **Copy the empty file**. In this exercise you will need to copy the file `copy_this_file.py` and create a file of your own. If your name is `Pauwel`, then create a file called `pauwel.py`.  
- **Print hello world**. Edit this file to include a print with "Hello World"
- **See what you modified**.
```sh
git status
```
- **Add the file**
```sh
git add <your_filename.py>
```
- **Commit the file**
```sh
git commit -am '<commit message>'
```
- **Push your changes to GitHub**
```sh 
git push origin feature/DABNLF-<ticket_number><branch_name>
```
- **Create a Pull Request and send a link to the review!**


## Exercise_2
- **Navigate to exercise 2**. This exercise is located in this path `github/Exercise_2`. If you were in exercise 1, you can go back in the terminal with `cd ..`.
```sh
cd github/Exercise_2
```
- **Solve the TODO**. You will find it in a file called `code_cowboys.py`.
- **Commit the file**
```sh
git commit -am '<commit message>'
```
- **Push your changes to GitHub**
```sh 
git push origin feature/DABNLF-<ticket_number><branch_name>
```
- **Create a Pull Request and send a link to the review!**
