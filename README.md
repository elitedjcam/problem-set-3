# Problem Set 3

Problem Set 3 allows you to start exploring your creating side. You'll be designing and building your first website (almost) from scratch. You haven't formally learned any CSS yet, so your website need only incorporate the HTML elements described below.

## Getting Started

To get started, you'll need to create a [GitHub](https://github.com/) repository to store your Problem Set 3 code. After cloning my skeleton repository, you'll need to setup a remote to push your code to your repository instead of mine. Steps to accomplish this are outlined below.

### Setup

01. Login to your [GitHub](https://github.com/) account and create a new repository named `problem-set-3`.
02. In GitBash, navigate to your `APCSP` folder.
03. Clone my skeleton repository from [GitHub](https://github.com/). This will make a copy of my repository and store it locally.
```
git clone git@github.com:rwilson-ucvts/principles-pset-3-skeleton.git
```
04. The cloning process will have created a folder named `principles-pset-3-skeleton`. Rename this folder to `problem-set-3`.
```
mv problem-set-3-skeleton problem-set-3
```
05. Change directories to get into your `problem-set-3` folder.
```
cd problem-set-3
```
06. Originally, the remote will be pointing at my repository. We need to overwrite this.
```
git remote rename origin upstream
```
07. Lastly, we need to add a new remote that points at the repository you created earlier. Make sure you replace `YOUR-USERNAME` with your actual [GitHub](https://github.com/) username.
```
git remote add origin git@github.com:YOUR-USERNAME/problem-set-3.git
```
08. Launch [Atom](https://atom.io/), select `File` and click `Add Project Folder...`.
09. Navigate to the `APCSP` folder on your `Desktop`, click the `problem-set-3` project folder, and click `Open`.

You should now see a `Project` in the left-hand panel in [Atom](https://atom.io/).

16. Expand the `Project` folder. You should see a file named `index.html` and a folder named `images`.

If you see the following starter code, then you've correctly cloned and setup your project.

![principles problem set 3 skeleton code screenshot](https://www.ucvts.tec.nj.us/cms/lib/NJ03001805/Centricity/domain/760/apcsp-images/pset3-skeleton.png)

## Requirements

TBD

## Deadline

Your Canvas submission is due at or before 11:59pm on your section-specific due date.
* TBD (A 3/4 & 7/8)
* TBD (B 3/4 & 7/8)

### Submission Requirements

All that is required for submission is the URL to your [GitHub](https://github.com/) repository for this problem set.
