# MAE6226 (Spring 2018) - Student projects

Students should fork this repository, clone it to a local working directory, then add a folder for their project.
Name the folder in a way that identifies the student (pick your name, or a nickname we know).
The project report should be a single Jupyter notebook (include any dependencies, like figures, data), and submit via pull request.
The instructor will provide feedback as comments on the pull request, and merge the pull request when the project is good!


**Please add all your files in one folder, named with your GitHub handle or last name.** And *please* do not include the notebook checkpoints in your commits (add the checkpoints folder to the ignore list).


### Step-by-step instructions

Student submitting a project should **fork** the present repository.

Go to `https://github.com/barbagroup/AeroPython-studentprojects2018`.
Click on the `Fork` button in the top-right corner to fork the repository `AeroPython-studentprojects2018` to your GitHub account.
You will be redirected to your GitHub "forked" repository.

In your terminal (on JupyterHub or on your local machine), clone the forked repository and change directory to it:
```
git clone https://github.com/<your-github-username>/AeroPython-studentprojects2018.git
cd AeroPython-studentprojects2018
```

There, create a new folder in a way that identifies you (e.g., your GitHub username or your last name):
```
mkdir <your-github-username>
cd <your-github-username>
```

Inside this new folder, you will develop your project.
The project report should be a single Jupyter Notebook.
Other files, such as data and figures, should also be placed in this folder.
Commits your changes as you develop your project and write your report (with `git add`, `git commit`, and `git push`).
New commits are pushed to your fork of `AeroPython-studentprojects2018` and do not yet appear on the main repository (under `barbagroup`).

Once you are done with your project, you create a **Pull request**.
To do that, go to your repository (`https://github.com/<your-github-username>/AeroPython-studentprojects2018`) and click on `Pull request`.
The `head fork` should be your fork (`<your-github-username>/AeroPython-studentprojects2018`) and the `base fork` should be the main repository (`barbagroup/AeroPython-studentprojects2018`), comparing your `master` branch with the `base` branch `master` (located in the main repository).
Click on the button `Create pull request`.
Add a title and a description of the changes you wish to merge into the main repository (in this case, a short summary of your project).
Finally, click on the button `Create pull request`.

That's it!
Your pull request is now listed at `https://github.com/barbagroup/AeroPython-studentprojects2018/pulls`.
We will review it and provide feedback on your project, writing comments on the pull-request page directly.
Once we estimate your project to be good, we will merge it into the main repository.