# Getting-Started-with-open-source


This is a guide for people interested in contributing to my open source
projects. It is based on popular work flows in the community and my experiences


## Important Codes
Open a terminal and run

```
git clone <url you just copied>
```
Where the url can be pasted from clipboard
For example
```
git clone https://github.com/othersusername/my-first-contribution.git
```
Here you're copying the contents of my-first-contribution repository in github to your local system

Go in to that directory

```
cd my-first-contribution
```

Now create a branch using `git checkout command`

```
git checkout -b <branch name>
```
For example : 
```
git checkout -b release-app
```
Now its time to test what you have learnt, do the same for this repo, fork it, clone it
an do respectively as given above.Now open `Contributors.md` file in a text editor and add your name to it,
save the file and send a pull request.

If you go to the project directory and do `git status`, you'll see there are changes

Add those change using `git add`

```
git add Contributors.md
```

Now commit those changes using `git commit`

```
git commit -m "Add <your-name> to Contributors list"
```
replace `<your-name>` with your name

Push your changes using `git push`

```
git push origin <add-your-name>
```
Replace `<add-your-name>` with the name of the branch you created earlier
