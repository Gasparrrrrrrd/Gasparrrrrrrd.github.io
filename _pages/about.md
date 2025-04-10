---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi ! I am a student in cognitive science at ENS-PSL (centered on computational neuroscience). Currently I am a research intern at NeuroPSI-Paris Saclay (Cognitive & Network Neuroscience unit) working on the neural circuits of decision-making in <i>Drosophila</i>. I look at the neural bases of the decision-making process at circuit and single neuron Level. Practically, what I do is computational analysis of neural circuits that underlie competitive interactions between actions in <i>Drosophila larva</i>. 

My research interests are in the neural dynamics underlying cognitive processes, with particular emphasis on decision-making and behaviour. I am particularly interested in how circuit-level mechanisms give rise to emergent population-level phenomena, I find neural manifolds and neural population geometry quite appealing. You can find more about my interests and background in my [CV](https://gasparrrrrrrd.github.io/files/CV.pdf).

Outside of work, I like French New Wave Cinema, as well Woody Allen's movies (especially the good old funny ones). Outside of cinema I try to cherish moments in my life and table tennis!

Short Bio
======
Somehow you landed on my personal page, allow me to introduce myself. I'm Gaspard, born in Munich to french and danish parents. I grew up between Germany and Brussels and went on to study in the Netherlands. I first studied [Nanobiology](https://en.wikipedia.org/wiki/Nanobiotechnology) at TU Delft, did mostly maths and physics applied to biology at the very small scale that is the nanometer (svg. diameter of globular proteins is ~5 nm, same for a virus, while diameter of DNA is 2.04 nm, the size of a glucose molecule is 1.5 nm). There I did a research internship in applied biophysics, in [Marileen Dogterom's lab](https://www.tudelft.nl/tnw/over-faculteit/afdelingen/bionanoscience/research/research-labs/marileen-dogterom-lab), in the BioNanoscience Department of the TU Delft. I investigated the biophysics of microtubules, in the context of a synthetic cell. We looked at the spatial organisation of these essential filaments in constrained environments. In particular, we tried to control aster (the microtubule organising center in the cell) positioning in droplets. 

During my BSc. I took a minor in Brain & Cognition which lead me to reconsider life at the bigger scale. From there on I did another research intenship in cognitive neuroscience. This lead me to go study cognitive science at ENS-PSL, in Paris. I am mostly focused on computational neuroscience and neuroAI. This means I mostly study mathematical methods and theories that apply to neural networks, as well as to cognitive subjects. 


Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
