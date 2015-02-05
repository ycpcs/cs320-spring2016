---
layout: default
title: "Assignment 6: Problem Domain Analysis"
---

Due: **Wednesday, February 18th** by 11:59 PM

This is a **team** assignment

Problem Domain Analysis
=======================

In this assignment, your team will conduct an analysis of the problem domain of your team project, and build an analysis model of the problem domain.

Step 1: Textual Analysis
------------------------

Go through the requirements and use cases you wrote in [Assignment 5](assign05.html). Identify the important noun and verb phrases which describe entities and concepts in your problem domain.  Save these in a document.

Step 2: Build an Analysis Model
-------------------------------

Based on your textual analysis, construct a UML class diagram modeling your project's problem domain.

You will probably want to work with your group using a whiteboard, since problem domain analysis is a *process*.  Your group will undoubtedly make a number of changes to the model as you explore possible ways of modeling the problem domain.

Once your group is satisfied with your model, create an electronic version of the model using [Violet UML](http://alexdp.free.fr/violetumleditor/page.php).  Note that you can download the Violet UML jar file from the course [Resources](../resources/index.html) page.

> **Note**: If you would like to use a different UML modeling tool, please see me.

Use associations (plain, aggregation, composition) and generalizations (Is-A / inheritance) to show the relationships between the classes (noun phrases) in your model. Give each association a name to indicate the roles of the two classes involved in the association. Add the important methods (verb phrases) to the classes to which they are most likely to belong. Don't worry about specifying parameters and return types for the methods.

> **Note**: Because you are building an analysis model, avoid modeling any "implementation" classes such as those involved in the user interface, data storage, etc., unless there are important requirements which would not otherwise be addressed by the model.

Step 3: Explain the Model
-------------------------

In a text document of 1 page, *briefly* explain your analysis model. Discuss why you felt the classes you modeled are the most important ones. Is there a class or classes that seem to be "central" to the model? How did you determine where to put the important methods?

Submitting
==========

Create a zip file containing:

1.  a text document with your textual analysis (noun and verb phrases)
2.  the Violet UML (.class.violet) file with your analysis model
3.  a text document with your explanation of the analysis model

Text documents must be in **PDF** format.

You can create a zip file using Windows by creating a folder, putting some files inside the folder, right-clicking on the folder, and choosing **Send to &rarr; Compressed Folder**.  In Linux, use a terminal to navigate to the parent directory of the directory containing your files, then run the command

<pre>
zip -9r <i>zipname</i> <i>dirname</i>
</pre>

where *zipname* is the name of the zip file you want to create, and <i>dirname</i> is the name of the directory containing your files.

Upload the zip file to the Marmoset server as **assign06**:

> <https://cs.ycp.edu/marmoset/>

Only one team member needs to upload the zip file.

<!-- vim:set wrap: ­-->
<!-- vim:set linebreak: -->
<!-- vim:set nolist: -->
