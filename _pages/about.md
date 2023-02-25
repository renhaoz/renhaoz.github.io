---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My past research mainly focused on decision-making and computer vision. In decision-making, my research interest lies in **Reinforcement Learning** which I believe is one of the key factors leading to general artificial intelligence. I have used RL to solve many 6G communication problems, for example, I established a novel 6G wireless communication system in which each IoT device can allocate its spectrum and energy resources autonomously based on multi-agent deep reinforcement learning. I also published a patent reducing the sensing energy of SU by teaching them to learn the spectrum usage pattern of PU with DQN. RL has proved its ability to enable agents to make decisions intelligently, which can even beat human kinds in certain fields, so I decide to explore more in improving the performance of RL algorithms, making them more interpretable, and applying them in real scenes.

Besides, I also worked a lot on **Computer Vision** and **Computer Graphics**, especially in program inference, detection, segmentation, OCR, and 3D reconstruction. I'm now working in BVC (Brown Visual Computing) group trying to inference programs from 3D shapes. Before that, I conducted several projects about detecting niduses on CT images, and identifying motions in figure skating in HPC lab of DUT. Besides, I have participated in the development of *Face Recognition based Time and Attendance System* as an algorithm engineer intern at Panasonic Corp., and *Recognition of Japanese cursive script* as an AI Lab researcher intern at Dalian Hi-think Computer Technology Corp, where I combined CNN and Transformer to detect and recognize cursive Japanese characters.

Education
======
**Brown University** - M.S. in Electrical and Computer Engineering (GPA: 4.0)
<p align="right">08/2022-05/2024 (Expected)</p>

- Teaching Assistant: ENGN 2912B: Scientific Programming in C++, CSCI 1951R: Introduction in Robotics
- Research: Brown Visual Computing, Robotics
- Advanced Course: Computer Graphics, Coordinate Mobile Robot, Deep Learning


**Dalian University of Technology** - B.S. in Electrical Information Engineering (GPA: 3.8)
<p align="right">09/2018-06/2022</p>

- Teaching Assistant: Object Detection
- Research: Human Perception Computing, Wireless Communication
- Advanced Course: Communication Security System, Information Theory, 


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
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
