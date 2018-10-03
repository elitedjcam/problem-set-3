# Problem Set 3

Problem Set 3 allows you to start exploring your creating side. You'll be designing and building your first website (almost) from scratch. You haven't formally learned any CSS yet, so your website need only incorporate the HTML elements described below.

## Getting Started

To get started, you'll need to create a [GitHub](https://github.com/) repository to store your Problem Set 3 code. After cloning my skeleton repository, you'll need to setup a remote to push your code to your repository instead of mine. Steps to accomplish this are outlined below.

### Setup

01. Login to your [GitHub](https://github.com/) account and create a new repository named `problem-set-3`.
02. In GitBash, navigate to your `APCSP` folder.
03. Clone my skeleton repository from [GitHub](https://github.com/). This will make a copy of my repository and store it locally.
```
  git clone git@github.com:rwilson-ucvts/principles-pset3-skeleton.git
```
04. The cloning process will create a folder named `principles-pset3-skeleton`. Rename this folder to `problem-set-3`.
```
  mv principles-pset3-skeleton problem-set-3
```
05. Change directories to get into your `problem-set-3` folder.
```
  cd problem-set-3
```
06. The cloning process will add a remote named `origin` that points at my skeleton repository. Rename `origin` to `upstream`.
```
  git remote rename origin upstream
```
07. Add a new remote that points at the `problem-set-3` repository you created earlier. Make sure you replace `YOUR-USERNAME` with your actual [GitHub](https://github.com/) username.
```
  git remote add origin git@github.com:YOUR-USERNAME/problem-set-3.git
```
08. Launch [Atom](https://atom.io/), select `File` and click `Add Project Folder...`.
09. Navigate to the `APCSP` folder on your `Desktop`, click the `problem-set-3` project folder, and click `Open`.

You should now see a folder named `problem-set-3` in the `Project` panel in [Atom](https://atom.io/).

10. Expand the `Project` folder. You should see a file named `index.html`, and another named `README.md` (which is what you're reading right now!). Open the `index.html` file.

If you see the following starter code, then you've correctly cloned and setup your project.

![principles problem set 3 skeleton code screenshot](https://www.ucvts.tec.nj.us/cms/lib/NJ03001805/Centricity/domain/760/apcsp-images/pset3-skeleton.png)

## Requirements

Create a website about a (school-appropriate) topic that interests you. This might be an extracurricular activitiy in which you participate, a sport or instrument you play, or just a hobby of yours. For now, your website should be informative in nature. Later, we'll add some style and creative expression.

More specifically, your website must include and incorporate the following features and elements.

* 4 distinct pages (i.e., `.html` files)
   - 1 page that gives a brief overview of your website topic (i.e., a homepage, which should be written in your `index.html` file)
   - 3 pages that discuss separate subtopics in greater detail
* A navigation bar that allows you to navigate to and from each of the 4 pages
* A unique and descriptive `<title>` for each of the 4 pages
* At least 3 of the header tags variations: `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, and `<h6>`
* At least 7 hyperlinks
   - At least 4 internal links that use a relative URL: `<a href="/relative/url.html>` or `<a href="#id">`
   - At least 3 external links that use an absolute URL: `<a href="https://absoluteurl.com">`
* At least 1 image per page: `<img src="/images/picture.png">`
   - All images must be stored in a folder named `images` (the use of subfolders within `images` is at your discretion)
* At least 2 lists
   - At least 1 ordered list: `<ol>`
   - At least 1 unordered list: `<ul>`
* At least 1 horizontal rule: `<hr/>`
* At least 1 `<table>`
   - Your `<table`> must include a header (`<thead>`), a body (`<tbody>`), and a footer (`<tfoot>`)
* A consistent page footer on every page
   - Your footer must include the copyright symbol and year (i.e., © 2018)
   - Your footer must include the school (appropriately hyperlinked), and course (i.e., AIT | APSCS)
   - Your footer must include a contact email (appropriately hyperlinked)
      * You must not use an actual email (instead, use info@example.com)

To avoid confusion, your directory structure must match the following. If something is followed with a `/`, it is a folder; otherwise, it is a file.

```
problem-set-3/
   images/
      myimage1.png
      subfolder/
         myimage2.png
   index.html
   mysubtopic1.html
   mysubtopic2.html
   mysubtopic3.html
   README.md
```

Of course, your filenames will be different than mine. They are alphabetized, so they will likely appear in a different order, too. The `subfolder` inside of the `images` folder is optional. You might find it useful to further categorize your pictures, but it is not required. The image files inside of the `images` and `subfolder` folders are examples. Yours, of course, will be named differently.

## Deadline

Your Canvas submission is due at or before 11:59pm on your section-specific due date.
* October 9, 2018 (A 3/4 & 7/8)
* October 10, 2018 (B 3/4 & 7/8)

### Submission Requirements

All that is required for submission is the top-level URL to your [GitHub](https://github.com/) repository for this problem set.
