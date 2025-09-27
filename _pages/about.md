---
permalink: /
#title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Professor and Ph.D. Supervisor at the School of Computer Science, Wuhan University, and also serve as the Deputy Director of the Department of Intelligent Science. My research focuses on computer vision, pattern recognition, and multimedia analysis, with a core focus on video analysis and retrieval.
For years, I have been committed to theoretical and applied research in video analysis, image processing, and machine learning. I have published over 70 academic papers in top international journals and conferences, including IEEE TIP, TIFS, TVCG, TOIS, TMM (journals), and CVPR, ACM MM, IJCAI, AAAI (conferences). I hold 23 published invention patents (13 authorized) and 3 software copyrights, and also serve as a reviewer for renowned international journals such as IEEE TIP, TMM, TCSVT, Pattern Recognition, and ACM TOMCCAP.

Research
==
Research Interests
--
* Computer Vision (pedestrian re-identification, video object detection and tracking, real-time semantic segmentation)
* Pattern Recognition (adversarial attack and defense in face recognition, few-shot learning, unsupervised domain adaptation)
* Multimedia Analysis (video instance retrieval, cross-modal content understanding, deep video parsing for story videos)
* Quantum-Inspired AI (quantum-inspired optimization algorithms for ranking aggregation, quantum machine learning in multimedia tasks)

Major Research Projects (Principal Investigator)
--
* National Natural Science Foundation of China (General Program): Research on Quantum-Inspired Composite Semantic Video Instance Retrieval Technology (Project No.: 62372339), 2024-2027.
* National Natural Science Foundation of China (General Program): Research on Key Technologies of Human-Machine Collaborative Multimedia Instance Retrieval (Project No.: 61876135), 2019-2022.
* National Natural Science Foundation of China (Youth Program): Research on Key Technologies of Person Re-identification for Video Investigation (Project No.: 61303114), 2014-2016.
* Hubei Provincial Natural Science Foundation (General Program): Research on Real-Time and High-Precision Semantic Segmentation Technology for Visual Media (Project No.: 2019CFB472), 2019-2021.
* Jiangsu Provincial Natural Science Foundation (Youth Program): Research on Key Technologies of Computer-Aided Video Investigation and System Verification (Project No.: BK20160386), 2016-2019.
* China Postdoctoral Science Foundation (First-Class General Funding): Research on Key Technologies of Person Re-identification Based on Sequential Object Appearance Modeling (Project No.: 2013M530350), 2013-2014.
* Ministry of Education Doctoral Program New Teacher Fund: Research on Person Re-identification Based on Model-Based Bag-of-Words Representation (Project No.: 20130141120024), 2014-2015.
  
Research Achievements & Awards
--
* 2023 Hubei Provincial Science and Technology Progress Award (Second Prize): "Key Technologies and Applications of Visual Media Analysis, Reconstruction, and Narrative Fusion" (rank 3/10), approved in 2024.
* Best Newcomer Award, International Workshop on Video Browser Showdown (VBS) at the 29th International Conference on Multimedia Modeling (MMM 2023).
* Best Paper Award, 15th Pacific-Rim Conference on Multimedia (PCM 2014).
* Championships in NIST TRECVID international evaluation tasks: Instance Search (INS 2021), Cross-Modal Search (AVS 2023), Deep Video Understanding (DVU 2023).
* 2020 Excellent Author Award of Wuhan University Journal (Natural Science Edition): For the paper "A Survey of Image Segmentation Methods" (the most cited and downloaded paper in the journal's history, with 535 citations and 20,894 downloads as of June 2024).
* 2016 Hubei Provincial Excellent Academic Paper Third Prize in Natural Science.

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.
nd clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub]
How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory a(https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
