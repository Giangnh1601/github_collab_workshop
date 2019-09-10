OBS: Dette dokumentet er ikke ennå oversatt til norsk (bokmål). Du kan gjerne hjelpe med det!

<!--- # Writing and publishing on the web together using Github --->
# Skriv og publisere sammen på nett med GitHub

<!--- You may be familiar with GitHub as a source of software, scripts, and programs. But, did you know that: --->
Du har kanskje hørt om GitHub? At der finnes mykvare, kode og til og med hele dataprogrammer? Men visste du også at:

* GitHub can also be used to work on text documents?
* GitHub enables collaboration on documents and software entirely through the web interface?
* you can create a simple webpage with a few clicks through GitHub?
* you don’t need any knowledge of the command-line version control tool `git` to do all this?

Also:

* Many researchers and developers in Digital Humanities put their code and projects on GitHub – or its sister GitLab. Currently, there are >220 [repositories](https://github.com/topics/digital-humanities) listed under the topic digital-humanities.
* You can find many useful – or just fun – projects here; e.g. for creating your personal website without having the hassle of finding a webhosting service and for no hosting cost [academicpages](https://github.com/academicpages/academicpages.github.io), or for making interactive presentations [reveal.js](https://github.com/hakimel/reveal.js/).
* You can also use GitHub for managing your projects!

This course will teach you how to do these things, and more. The course is aimed at researchers and tailored towards those with very little to no experience in the subjects taught. Experience with git or GitHub or similar programs/services is not necessary, but it doesn’t hurt either.

NB time permitting, at the end the workshop, those interested can learn how to do the same operations using command line `git`.

-------------

## Set up a repository

* get GitHub account
* make repository called "Guacamole recipe" 
* IMPORTANT! In the same step, add a 'README.md' file
	* explain commit, commit message

## Add more files

* Add `ingredients.txt` file with "avocado", commit
	* show commit message etc
* Add lime, small tomato, white onion, commit
	* Show diff
* Remove small tomato, commit
	* Show diff
* Add `instructions.txt` with
	* Chop avocados
	* Chop onion
	* Squeeze lime
	* Add salt

## Collaborate directly

* Divide into pairs 
	* \#1 repo will be used
	* \#2 close the window with their repo
	* \#1 add #2 as collaborator
	* \#2 checks email and accepts invitation
	
* \#2 make a change to repo
	* add `and mix well` to `instructions.txt`
	* \#1 add comment to commit
	* \#2 respond to comment
	
* \#1 convert `ingredients.txt` to `ingredients.md`
	* quick intro markdown
	* convert into markdown list
	* add `* salt`
	* look at rendered version
	
* explain issues and pull request principles

* \#1 submit an issue
	* "We need to convert `instructions.txt` to `instructions.md`"
	* \#2 check email
	
* \#2 submit an unrelated issue
	* "Add 'lime' as ingredient"
	* \#1 check email
	
* \#2 prepare a pull request to address issue #1
	* make branch
	* make changes
	* commit to new branch
	* submit pull request
	* add link to issue in PR
	* \#1 check email
	
* \#2 prepare a pull request to address issue #2
	* this time, do not start from a new branch
	* instead, commit to new branch when finished
	* also include a typo in the change (!)
	
* \#1 add comment to PR, 'fix typo!'
	* \#2 check email
	
* \#2 fix typo, thus adding a commit to the PR

* \#1 merge PR

* Exercise: do another cycle of an issue by one, and a PR by the other, include comments and merge PR

## Prevent conflicts

* \#2 create branch with change
	* call branch collab
	* wait with the PR
	
* \#1 commit change on same line in same file in master (!) branch

* \#2 submit PR --> conflict
	* \#1 & \#2 communicate through 'code review'
	* \#1 resolve
	
* \#1 merge PR

## Collaborate by 'suggesting' changes

* no commit rights
* explain forking
* instructor makes new repo for biographies
* second instructor, demonstrate adding bio as PR
	* for the repo
	* add a new file in fork
	* find 'submit PR' button on forked repo
	* follow PR steps
* first instructor accept PR
* each participant: add a new file with two or three lines to describe yourself (can be made up), add as PR
* Exercise: in pairs
	* add issues to the other person's biography file
	* and/or add PR, comments to PR, fixes etc
	* discuss through github
	* add 'OK to merge' when ready
* instructor merges
	* merge PRs and close issues
* update your fork with the cages from the repo you forked from
	* in the fork, click the 'compare' button (right)
	* switch the base
	* check changes
	* click 'pull request'
	* now it is OK to merge your own pull request

## Real world example

* look at <https://github.com/swcarpentry/make-novice/>
* issues and pull request, conversation
* e.g. <https://github.com/swcarpentry/make-novice/pull/43>

## Building a simple website using GitHub

* back to Guacamole repo
* add `index.md` with a few lines of text
* on the 'Settings' tab of the github repo, enable find "Select a source below to enable GitHub Pages for this repository" and select 'master branch' from the pulldown
* find your webpage
* in `index.md`, add (markdown) links to `ingredients` and `instructions`
* Exercise: customise your recipe website

## Another demo: Norwegian Correspondences project website

* <https://arockenberger.github.io/NorKorr/>

## Example of the final result

<https://arockenberger.github.io/guacamole_oppskrift/>


------

## instructor notes

* Co-instructor is number 2
* Laptop switching between them, make second laptop look different
