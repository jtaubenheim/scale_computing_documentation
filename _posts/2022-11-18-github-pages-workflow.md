---
layout: category-post
title: "Developer workflows for using GitHub pages"
categories: writing
---

This post outlines the proccess and workflow associated with using GitHub pages via CLI. 

1. Code update / change / addition is made within the repo. 

2. User navigates to the '_posts' sub-folder (or whatever we decide to call the source folder that holds the documentation for that repo). 

3. Either: 
	A. Creates a new document
	B. Finds relevant existing documentation

4. User makes the appropriate edits / additions etc. 

5. Submits their code and documentation changes:

```
git add <files>
git commit 
git push
```
6. Documentation changes are pushed to the repo along with code changes in the PR. 

7. Review and merge process. 

8. Static site generator automatically updates the website (updates existing file or adds new file)

	*Docs are organized by using the 'categories' variable in the Front Matter of the document (see Source Files) 
