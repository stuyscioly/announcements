announcements
=============

I'm making the announcements page separate from the StuySciOly.github.io repository in order to maintain organization.

If you'd like to create posts, please follow the following steps (that double follow).


A. Go to this [link](https://github.com/StuySciOly/announcements/tree/gh-pages/_posts).
B. Create a new file by clicking the plus icon. ![placeholder](https://raw.githubusercontent.com/StuySciOly/miscFiles/master/plus.gif "Example image")
C. Copy and paste the following text. **THIS IS IMPORTANT**. 

> `---`

> layout: post

> title: Hello There

> `---`

> <br>

> INSERT YOUR CONTENT HERE. MAKE SURE THE NEWLINE/ENTER SPACES ARE PRESENT OR ELSE GITHUB PAGES WILL CRY.

> <br>

> ~YOUR NAME

> <br>

> &lt;br>

> &lt;br>

> &lt;br>

> &lt;br>

> &lt;br>

> &lt;hr>

> &lt;br>

> &lt;br>

> &lt;br>

> &lt;br>

> &lt;br>

D. Name the file in the following format YYYY-MM-DD-insert-cool-name-here.md

E. Commit your file!

F. The announcements page should automatically update with your post.





<hr>

THE HARD WAY.

If you'd like to create posts, please follow the following steps (that double follow).

1. Install all necessary stuffs [here](https://help.github.com/articles/using-jekyll-with-pages)
2. Git clone this repository
3. Go inside this repository through your terminal (Mac or Linux (preferably Linux (yes I'm biased)))
4. Enter the following command: bundle exec jekyll serve --watch
5. This way you can check out how the site looks through http://0.0.0.0:4000. It'll live update whenever you save a change. Pretty neat eh?
6. Go to the _posts folder and enter a post with the format name: <YEAR-MM-DD-insert-your-title-here.md> and write your post. This is **important**. Failure to do so will lead to misordered posts. You can look at 2014-01-01-example-content.md to see the magic fairy dust you can use to beautify your post.
7. When you're done, just Cntrl+C in order to exit the Jekyll server, and push to this repawsitory.
