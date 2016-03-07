---
layout: default
title: "Lab 4: SQL, Queries, Joins"
---

Getting Started
===============

Download [CS320\_Derby.zip](../resources/CS320_Derby.zip) and [CS320\_Lab04.zip](CS320_Lab04.zip). Import them into your Eclipse workspace (**File&rarr;Import...&rarr;General&rarr;Existing projects into workspace&rarr;Archive File**). You will see projects called **CS320\_Derby** and **CS320\_Lab04** in the Package Explorer.  You will be running the **SQLDemo** class in the **CS320\_Lab04** project.

Setting up the database
=======================

Execute the **SQLDemo** class as a Java application.

Use **create table** commands to create **books** and **authors** tables. From the **SQL\>** prompt, enter the following commands:

    create table books (
        author_id integer,
        title varchar(50),
        isbn varchar(20)
    );

    create table authors (
        author_id integer primary key,
        author_lastname varchar(40),
        author_firstname varchar(40)
    );

Next, use **import** commands to load data into these tables:

    import books books.csv;

    import authors authors.csv;

Your database is now populated with data.

The schemas of the database tables are described in the notes for [Lecture 9](../lectures/lecture09.html).

Task
====

Try executing some queries to retrieve the following information:

-   the titles of all books written by F.G. Smallfinger
-   the titles of all books written by Callus Tacticus
-   the author name (first and last) and the ISBN number of the book with the title "First Flights in Witchcraft"

Each query should be terminated with a semicolon (**;**). For example, here is session showing a query to select all of the tuples in the **authors** table (user input in **bold**):

<pre>
SQL> <b>select * from authors;</b>
AUTHOR_ID AUTHOR_LASTNAME AUTHOR_FIRSTNAME
--------- --------------- ----------------
        1     Smallfinger             F.G.
        2       Whittlbey           W.H.J.
        3          Earwig          Lettice
        4         Lightly             W.E.
        5        Tacticus           Callus
OK (5 rows(s))
</pre>
