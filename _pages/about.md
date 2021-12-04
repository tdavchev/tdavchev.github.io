---
permalink: /
title: "Todor Davchev"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final year PhD student in Robot Learning at the <b>University of Edinburgh</b>, where I am part of the [Robust Autonomy and Decisions (RAD)](http://rad.inf.ed.ac.uk/) group. I also work closely with prof. S. Schaal and F. Meier and have completed two Google X AI residencies and a research scientist internship with DeepMind.

Broadly, my interests lie in the intersection of robotics and machine learning.
In my PhD I focus on improving the sample efficiency and robustness of learnt models through utilising inductive biases in the context of robotics applications. In the past, I have studied ways of building such biases through learning modular and re-usable across tasks world models \[[1](https://ieeexplore.ieee.org/document/9309332?source=authoralert), [2](https://arxiv.org/abs/1907.06422)\]; demonstrations \[[3](https://arxiv.org/abs/2008.07682),[4](https://arxiv.org/abs/2010.09034)\]; transfer learning \[[5](https://arxiv.org/abs/1905.02675)\]; and self-supervised reinforcement learning \[[6](https://arxiv.org/pdf/2112.00597.pdf)\]. I have particular interest in fast contact-rich skill acquisitions, such as peg, gear and plug insertions and have also studied ways to improve 2D trajectory generation in crowded and collaborative settings as well as extracting robust to perturbations and task representations.
With this, I am generally excited about projects combining ML/RL and robotics, including working on algorithms, simulations, and actual robot experimentation.

<span style="color:red"> News </span> **Research** New paper on [Hindsight Goal selection for Long-horizon Dexterous Manipulation](https://arxiv.org/pdf/2112.00597.pdf)<br/>
<span style="color:red"> News </span> **Research** New paper on [Learning Time-invariant Reward functions with Meta-learning](https://arxiv.org/pdf/2107.03186.pdf)<br/>
<span style="color:red"> News </span>  **Workshop ICRA 2021 live!** Our workshop on Learning-To-Learn for Robotics aims to provide an informative overview of the existing challenges in L2L for Robotics. Consider submitting (deadline 15th May) [Website](https://sites.google.com/view/learn-to-learn-robotics/). <br/>
<span style="color:red"> News </span>  **Workshop ICLR 2021 live!** Our workshop on Learning-To-Learn brings together neuroscience and machine learning experts to push the boundaries of the field. [Website](https://sites.google.com/view/learning-2-learn). <br/>
<span style="color:red"> News </span> **Research** Our paper Learning Structured Representations of Spatial and Interactive Dynamics for Trajectory Prediction in Crowded Scenes got accepted at RA:L Special issue on Long-term Human Trajectory Prediction!<br/>
<span style="color:red"> News </span> **Research** Our paper Model-Based Inverse Reinforcement Learning from Visual Demonstration was accepted at CoRL 2020!
{: .notice}

<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
