---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
------
Hi! I am a fifth-year Ph.D. student at the Computer Science Department at University of Maryland College Park, advised 
by [Prof. Heng Huang](https://www.cs.umd.edu/~heng/). Previously, I was a Ph.D. student at ECE Department at University
of Pittsburgh before our group moving to UMD.

My research interests are generative modeling and making deep neural networks efficient and deployable in real-world
applications. I am also interested in automated medical image analysis.

I spent Summer 2023 as a research scientist intern at [Adobe Research](https://research.adobe.com/), Seattle, where I 
worked on architectural efficiency of diffusion models and was fortunate to have 
[Yan Kang](https://research.adobe.com/person/yan-kang/), [Yuchen Liu](https://lychenyoko.github.io/), 
[Richard Zhang](https://richzhang.github.io/), and [Zhe Lin](https://research.adobe.com/person/zhe-lin/) 
as my mentors. I was also a Deep Learning Intern at [Enlitic](https://enlitic.com/) in Summer 2021.

I got my Bachelor of Science (B.Sc) from University of Tehran, working with [Dr. Reshad Hosseini](https://ece.ut.ac.ir/en/~reshad.hosseini) on 3D Reconstruction of Symmetric Structures where I was a member of [Computational Audio-Vision Lab](https://visionlab.ut.ac.ir/index.html).

[//]: # (Getting started)

[//]: # (======)

[//]: # (1. Register a GitHub account if you don't have one and confirm your e-mail &#40;required!&#41;)

[//]: # (1. Fork [this repository]&#40;https://github.com/academicpages/academicpages.github.io&#41; by clicking the "fork" button in the top right. )

[//]: # (1. Go to the repository's settings &#40;rightmost item in the tabs that start with "Code", should be below "Unwatch"&#41;. Rename the repository "[your GitHub username].github.io", which will also be your website's URL.)

[//]: # (1. Set site-wide configuration and create content & metadata &#40;see below -- also see [this set of diffs]&#40;http://archive.is/3TPas&#41; showing what files were changed to set up [an example site]&#40;https://getorg-testacct.github.io&#41; for a user with the username "getorg-testacct"&#41;)

[//]: # (1. Upload any files &#40;like PDFs, .zip files, etc.&#41; to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  )

[//]: # (1. Check status by going to the repository settings, in the "GitHub pages" section)

News
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
