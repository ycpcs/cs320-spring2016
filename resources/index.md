---
layout: default
title: "Resources"
---

This page links to useful resources.

[Fetching and merging changes from within Eclipse](fetchMerge.html)

Violet UML: [violetumleditor-2.1.0.jar](violetumleditor-2.1.0.jar)

[Great Tutorial site for HTML, CSS, Java Script, SQL, PHP](http://www.w3schools.com)

[CS320\_Derby.zip](CS320_Derby.zip) &mdash; Eclipse project with jarfiles for Apache Derby (relational database)

> <div class="callout"><b>When you implement your persistence layer using Derby</b>: when specifying the JDBC URL in the code where you connect to the database, you should use an absolute filename for the database name. For example, <code>jdbc:derby:H:/mydatabase.db;create=true</code> (this will create the database as <code>H:/mydatabase.db</code>).  If you use a relative filename, your web application will probably not find the database (because it runs in the <code>war</code> directory rather than the root directory of the project).</div>
