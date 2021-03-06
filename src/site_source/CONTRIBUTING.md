Contributing to our Blog
=============================

First, thanks for your interest in contributing and helping us craft quality content for our official Developer Blog. Second, in order to make contributing a pleasant experience while maintaining a visual and content standard, complete these steps before writing and submitting a blog entry for publishing.

#### Writing your blog entry

1) Fork this repo, then clone your fork.

2) Before you start working, make sure your content is up-to-date and merged with the right branch:

        git remote add upstream git@github.com:rackerlabs/developer.rackspace.com.git
        git checkout master
        git fetch upstream
        git checkout -b name-of-you-branch
        git merge upstream/master

2) Create a file inside `src/site_source/_posts/` with the following naming convention `YYYY-MM-DD-title-of-your-post.md` where `YYYY-MM-DD` is the date you want you entry to be published.

3) Add Jekyll front matter (i.e. metadata) to the top of the file you created in the previous step, for example:


    ---
    layout: post
    title: "Blog Entry Title"
    date: YYYY-MM-DD 23:59
    comments: true
    author: Author(s) name(s)
    published: true
    categories:
        - This Category
        - That Category
        - Other Category 
    ---


Make sure that the dates in the file name and front matter match.   

4) Format your blog entry in formatted using [markdown](http://daringfireball.net/projects/markdown/basics). If you are not comfortable authoring in markdown, send a message to @rgbkrk for other options.
  
#### Submitting your Blog entries

Follow these steps to submit you're entry for publication. 

1) Submit a PR (pull request) against `master` branch.

2) Include this information in your PR message, even if you've submitted blog entries previously:
    
 - author(s) mini bio, soft capped to 75 words
 - author(s) social media contact info
 - accept/decline to allow redaction, editing or structure changes by technical writer staff
 - desired date of publishing
 
