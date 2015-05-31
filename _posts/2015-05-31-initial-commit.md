---
layout: post
title: Initial commit.
---

During this first week of Google Summer of Code I have been working on the SQL parsing library that I have to complete before continuing my work on phpMyAdmin.

Recently, I published the code I have been writing for the past weeks under a repository on my GitHub account. I decided to implement `SELECT`, `INSERT`, `DELETE`, `UPDATE` and `CREATE TABLE` statements first because they are some of the most used statements and analyzing their syntax helped me a lot when I sketched the first prototype.

What is interesting about these queries is that their syntax differs so much that it helped me find a balance between abstraction and performance that will help me to easily adapt current code base to implement other types of statements.

For the next week, I planned on finishing implementing the parsers for most statement types, which will let me continue my work on phpMyAdmin and start implementing it.

If you want to check out the code I wrote during the past weeks, you can find it in its repository [here](https://github.com/udan11/sql-parser).