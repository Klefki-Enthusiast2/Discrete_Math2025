# Discrete Math2025

Git Hub for Discrete Math, Fall 2025 semester. A place for Graduate Students in the class to collaborate on our assigned Textbook project.

<b>
<i>
Please read through this README closely. Organization is going to be key during this project.
</i>
</b>
<br>
<blockquote>
Small Admin Note: 
<br>
Let's collaborate through this repository to complete the task at hand. Please maintain a level or organization and structure in this repository as there are quite a few of us working together on this project. 
I personally would like to avoid the need for branching as that cna create a lot of confusion, so I think making a folder structure to keep files organized might be the easiest way to go about this.
If you have any additional suggestions, feel free to reach out and communicate with out group.
I dont want to be overly controlling about this repository. You will all have a majority of permissions to work as freely as possible on this repository, but ultimately I will have admin rights here to ensure we do not spaghetti the files that go through here. You will have all available permissions up to branching (if needed) and push requests. It is not personal, I just do not know all of you yet. I am happy to give you full push rights, but I hate spaghetti, so we'll get there.
If you are unfamiliar with git, please DO NOT be afraid to ask. I would rather you ask a million questions, than messing things up for the whole class. One bad push can mess up the flow and I am not a fan of having to go backwards on git.
<br>
                                                      -t
</blockquote>
---
                                                    
# Preliminary Folder Structure
I think we should treat this more like a pipeline rather than a folder structure. As files get closer to completion, they will get passed further down the list of folders.

## Written Lecture Notes and Weekly outline
```
# weekly notes/
|
+- scanned PDFs
|  
+- preliminary latex notes
|
+- weekly outline
```
---
### scanned pdf of handwritten notes
trivial.
### initial typed lateX of the notes for the week
whoever takes notes for the week should upload their written notes here.
Additionally, when you convert handwritten -> latex, you should put your initial .tex document here.
Please make sure that your commit messages are dated and contain a sufficient description of what you are uploading.
### outline of the notes
Not sure if this section is super necessary, but the idea is that whoever is in charge of notes for the week, should include an outline of what was covered for the week. This would allow for us to organize the structure of the document/textbook and hopefully make edits easier.
If we dont agree/dont want this section, I have no problem removing it.

---

## teX edits


```
# Edits/
|
+- .tex files
|
+- files for class review
| |
| +- week 1/
| +- week 2/
| +- so on
```
---
To prevent bottlenecking, I think we should take Dr Iovino's suggestion and do 1 or 2 paragraphs at a time. Furthermore, we should make sure we communicate on what exactly we are working on. If there are multiple people working on the same section, perhaps consider drafting changes on a collaborative document like overleaf or something, then upload one document.
ALL commit messages should be dated with a GOOD description of what work was done
 command would look something like:
 ```
git commit -m "082825, edits made to section covering XX topic.
ready for class review"
```

---

## Master Files
```
#complete files/
|
+- completed sections/
| |
| +-- chapter 1/
| +-- chapter 2/
| +-- so on/
+- completed notes for sage/
```

---

### finished sections/ compiled master for sage
Here we should treat this like our "finished product" 
I persoanlly think that all of our scratch work should be contained here and only put things into sage when we are ready for Dr Iovino to view them. If he approves, great. If not, the files will go through the pipline again
