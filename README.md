## Table of Contents  
[1. miscellaneous tips](#1-miscellaneous-tips)  
[2. repository description](#2-repository-description)  
[3. sharing this repository](#3-sharing-this-repository)  
[4. plugins](#4-plugins)

## 1. miscellaneous tips

### if you are a beginner, check out tutorials
such as [this stuff for basics](https://www.youtube.com/watch?v=QgbLb6QCK88&list=PL3NaIVgSlAVLHty1-NuvPa9V0b0UwbzBd) and [this for advanced thoughts](https://www.youtube.com/playlist?list=PL-1Nqb2waX4X2HudaI-8jVqDE8W7aHWbF).

### make use of search engines
any term mentioned here is covered by blogs and youtube videos to a great extent. searching for anything you read here, will give you a plethora of additional help.

### learn how the search querries work
on the top left corner there is a magnifying glass that allows you to search. click into the field and study until you understand the options suggested there. this becomes useful in many places of this app.

### workspaces
consider activating the "workspaces" core plugin.

### chose theme
consider chosing another theme that pleases your eye under *options -> appearance*.

### make use of templates
to insert content into this vault, create a new note in the location you want to add something and use the hotkey 'ctrl + shift + t' to open the template selector, where you can chose a template that typically has the same name as the place you want to store the new content. for example, the template for a new note in *journaling -> daily* is called **notes_daily**.

### make use of MOCs
a 'map of content' helps organizing notes.

### make use of emoticons
there are operating system specific hotkeys that allow you to access the emoticon palette that come with your operating system by default (just like on the smartphone).

## 2. repository description
this is a run through the directory structure of this repository. it is tailored towards scientific work (documenting your thought process, connecting ideas and writing manuscripts) and as a side-effect also personal journaling.

### 2.1 journaling
click into the calendar to the right lower corner
- on a day to start a daily entry into the journal (placed in *journaling -> daily -> YYYY-MM-DD*)
- on a week number to start a weekly entry into the journal (placed in *journaling -> weekly -> YYYY-W*)
- start any note in *journaling -> activities* to track to-dos or other things you want to keep track of or remind yourself about. 

### 2.2 manuscripts
the place to work on and store your manuscripts. each manuscript should have its own directory, in which you can place whetever other material, such as figures/graphs, co-author coments, documentation of the submission process and the final paper. however, don't put the input data, analyses, tentative figures or output data into this directory, for this, create a specific directory in your *projects* or *data* directory elsewhere. once a publications is finished and published, move it to *manuscripts/published*.

### 2.3 notes
insert documentation or any other text that allows to check out some notes, tutorial or other *frequently asked questions* about whatever matters to you.

### 2.4 projects
the place to handle your projects. for scientific projects, this includes the project description, the proposal(s), the milestones/working packages, the tasks (should be as detailed as possible and summarised in milestones) and any documentation that may be important for writing a manuscript or report. ideas for new projects can also go here.

### 2.5 references
while storing all references in a bib or similar file, you should also have a journal on the things you read in those papers such as a summary in your own words, keywords and a list of references this paper makes. a new such item can be created with the hotkey 'ctrl + shift + o'.

### 2.6 talks
the place to store everything about your talks, presentations and posters

#### poster
so far obsidian can't be used to develop posters, but they can still be viewed and used in other parts of a workflow, so it makes sense to store them here.

#### presentation
organize presentations into this location.

### 2.7 templates
all templates used in this vault.

### 2.8 zettelkasten

#### concepts
a collection of concepts and their relation to other concepts. to create a new concept, simply encase the concent from which you want to create a concept (e.g., 'method') with a double backet `[[method]]` . when clicking on this link, a new note will be created, which you would sort into the folder *zettelkasten -> concepts* and where you would add details to connect it to other concepts. 

#### some_collection
gather ideas and questions in this folder, which is distinct from *zettelkasten/concepts* so that it can be put into a distinct repository that is shared with a group of people (for example those collaborating on a project) without having to share the whole vault.

##### ideas
similar to concepts, store ideas in this location and either connect them to keywords and/or document where you have made use of the ideas.

##### questions
and here, store questions and once you found the solution, link it here. if you do not delete these items, it can become an impressive documentation of all the problems you have solved.

## 3. sharing this repository
any vault will contain personal information, such as the journal, or ideas one does not want to share with the world just yet. this vault has therefore been designed so that use-cases are grouped into directories so that they can be shared in a meaningful way. for instance, all information about the project (proposal, description, organization) is in the same directory.

it is best to share the complete vault with git (via github/gitlab) with possible collaborators and make use of the [`.gitignore`](https://github.com/github/gitignore) file. there is a 'gitignore' file in this repository, to make use of it simply modify it according to your needs (the folders you want to keep private) and rename it to '.gitignore'.

when ignoring manuscripts, talk, projects, or your personal zettelkasten, you can still decide to initiate a seperate (private) repository, and share it only with your collaborators or workgroup peers, or keep it private all together. 

## 4. plugins
this repository comes with a range of plugins and default settings (stored in the top-level folder *.obsidian*). feel free to update the plugins and hotkeys according to your needs. there is much to explore, so don't get lost in trying to optimize over and over again!
