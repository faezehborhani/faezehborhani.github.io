---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in Computer Science at Colorado State University, where I work in the [Natural User Interaction Lab](https://nuilab.org/) under the supervision of  [Francisco R. Ortega](https://scholar.google.com/citations?user=AuBa0OAAAAAJ&hl=en). My research lies at the intersection of Human-Computer Interaction (HCI) and Extended Reality (XR), with a focus on interaction modalities in Augmented and Virtual Reality systems.

More specifically, I am interested in how users perceive, learn, and interact with XR systems over time, including topics such as gesture memorability, annotation retrieval, XR privacy, cross-platform interaction consistency (AR vs. VR), and the effectiveness of multimodal feedback. I also explore applications of XR in domains such as education (e.g., wind and physics simulations in VR), accessibility, and empathic computing.

Latest News
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Community Service 
======
- 📝 Reviewer at TVCG journal 2026 (1)
- 🥽 Registration Co-Chair at SUI 2026
- 📝 Reviewer at CHI 2026 (5)
- 📝 Reviewer at TVCG journal 2025 (3)
- 🥽 Registration Co-Chair at [SUI 2025](https://sui.acm.org/2025/committee-members/)
- 🥽 Registration Co-Chair at [VRST 2025](https://vrst.acm.org/vrst2025/index.php/committee/)
- 🥽 Organizing committee of [ENPTXR Workshop at IEEE VR 2025](https://www.xrprototyping.com/)
- 📝 Reviewer at ISMAR 2025 (3)
- 📝 Reviewer at CHI 2025 (3)
- 🥽 Organizing committee of [ENPTXR Workshop at IEEE VR 2024](https://www.xrprototyping.com/)
- 📝 Reviewer at GI 2024 (2)
- 📝 Reviewer at ISMAR 2024 (2)
- 📝 Reviewer at IEEE VR 2024 (1)
- 🥽 Organizing committee of [ENPTXR at IEEE VR 2023](https://www.xrprototyping.com/)
- 📝 Reviewer at SUI 2023 (2)
- 📝 Reviewer at ISMAR 2023 (1)
- 📝 Reviewer at Frontiers 2022 (2)
- 📝 Reviewer at ISMAR 2022 (1)
- 📝 Reviewer at ISS 2022 (1)
- 🥽 Organizing committee of [ACM SUI 2021](https://sui.acm.org/2021-testing/)
- 📝 Reviewer at ISMAR 2021 (2)
- 📝 Reviewer at IEEE VR 2021 (1)
- 📝 Reviewer at CHI LBW 2021 (1)
- 🥽 Organizing committee of [DISCE at IEEE VR 2021](https://sites.google.com/view/disce)
- 🤝 Organizing Committee of Graduate poster session, CS CSU, Spring 2019
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
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
