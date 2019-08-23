.. NotesOfLearningPython documentation master file, created by
   sphinx-quickstart on Mon Mar 25 10:30:19 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

#####################
SQLite-Tutorial-zh_CN
#####################

SQLite Tutorial
=================================================

本 **SQLite教程** 将教你如何有效地开始使用SQLite。你将通过广泛的动手练习来学习SQLite。

如果你已经使用过其他的关系型数据库管理系统，例如 MySQL, PostgreSQL, Oracle, Microsoft SQL Server，并听说过SQLite。而且，你希望知道它的更多细节。

如果你的朋友推荐你使用SQLite数据库，而不是使用简单的文件来管理你应用中的结构化数据。你希望立即开始使用SQLite，看看你是否可以将它用于你的应用程序。

如果你刚刚开始学习SQL并希望使用SQLite作为数据库系统。

如果你上述人员之一，那么本教程十分适合你。

SQLite是一个 *开源的*，*零配置的(zero-configuration)*，*自包含的(self-contained)*，*独立的(stand-alone)*，*事务(transaction)* 的关系型数据库引擎，它被设计用于嵌入到应用程序中。


SQLite入门
=============

如果这是您第一次使用SQLite，则应该阅读本节。按照这3个简单的步骤快速开始使用SQLite。

首先，我们帮助您回答第一个重要问题：什么是SQLite？在开始使用之前，您将对SQLite进行简要概述。
其次，我们将逐步向您展示如何在您的计算机上下载和安装SQLite GUI工具。
第三，我们向您介绍一个SQLite示例数据库，并引导您完成使用示例数据库进行练习的步骤。


基本的SQLite教程
=================

本节介绍可以与SQLite一起使用的基本SQL语句。您将首先开始从示例数据库中查询数据。如果您已经熟悉SQL，那么您会注意到SQLite中SQL标准和SQL方言之间的差异。


Section 1. Simple query
-------------------------

+ Select – query data from a single table using SELECT statement.


Section 2. Sorting rows
-------------------------

+ Order By – sort the result set in ascending or descending order.


Section 3. Filtering data
--------------------------

+ Select Distinct – query unique rows from a table using the DISTINCT clause.
+ Where  – filter rows of a result set using various conditions.
+ Limit – constrain the number of rows that you want to return. The LIMIT clause helps you get the necessary data returned by a query.
+ Between – test whether a value is in a range of values.
+ In – check if a value matches any value in a list of value or subquery.
+ Like – query data based on pattern matching using wildcard characters: percent sign (%) and underscore (_).
+ Glob – determine whether a string matches a specific UNIX-pattern.
+ IS NULL – check if a value is null or not.


Section 4. Joining tables
--------------------------

+ SQLite join – learn the overview of joins including inner join, left join, and cross join.
+ Inner Join – query data from multiple tables using inner join clause.
+ Left Join – combine data from multiple tables using left join clause.
+ Cross Join – show you how to use the cross join clause to produce a cartesian product of result sets of the tables involved in the join.
+ Self Join – join a table to itself to create a result set that joins rows with other rows within the same table.
+ Full Outer Join – show you how to emulate the full outer join in the SQLite using left join and union clauses.


Section 5. Grouping data
-------------------------

+ Group By – combine a set of rows into groups based on specified criteria. The GROUP BY clause helps you summarize data for reporting purposes.
+ Having – specify the conditions to filter the groups summarized by the GROUP BY clause.


Section 6. Set operators
-------------------------

+ Union – combine result sets of multiple queries into a single result set. We also discuss the differences between UNION and UNION ALL clauses.
+ Except – compare the result sets of two queries and returns distinct rows from the left query that are not output by the right query.
+ Intersect – compare the result sets of two queries and returns distinct rows that are output by both queries.


Section 7. Subquery
---------------------

+ Subquery – introduce you to the SQLite subquery and correlated subquery.
+ Exists operator – test for the existence of rows returned by a subquery.


Section 8. More querying techniques
-------------------------------------

+ Case – add conditional logic to the query.


Section 9. Changing data
-------------------------

This section guides you on how to update data in the table using insert, update, and delete statements.

+ Insert – insert rows into a table
+ Update – update existing rows in a table.
+ Delete – delete rows from a table.
+ Replace – insert a new row or replace the existing row in a table.


Section 10. Transactions
-------------------------

+ Transaction – show you how to handle transactions.


Section 11. Data definition
----------------------------

In this section, we show you how to create database objects such as tables, views, indexes using SQL data definition language.

+ SQLite Data Types – introduce you to the SQLite dynamic types system and its important concepts: storage classes, manifest typing, and type affinity.
+ Create Table – show you how to create a new table in the database.
+ Primary Key – show you how to define the primary key for a table.
+ NOT NULL constraint – ensure values in a column are not NULL.
+ UNIQUE constraint – ensure values in a column or a group of columns are unique.
+ CHECK constraint – ensure the values in a column meet a specified condition defined by an expression.
+ AUTOINCREMENT – explain how the attribute AUTOINCREMENT works and why you should avoid using it.
+ Alter Table – show you how to use modify the structure of an existing table.
+ Rename column – learn step by step how to rename a column of a table.
+ Drop Table – guide you on how to remove a table from the database.
+ VACUUM – show you how to optimize database file.


Section 12. Views
------------------

+ Create View – introduce you to the view concept and show you how to create a new view in the database.
+ Drop View – show you how to drop a view from its database schema.


Section 13. Indexes
--------------------

+ Index – teach you about the index and how to utilize indexes to speed up your queries.
+ Index for Expressions – show you how to use the expression-based index.


Section 14. Triggers
----------------------

+ Trigger – manage triggers in SQLite database.


Section 15. Full-text search
-----------------------------

+ Full-text search – get started with the full-text search in SQLite.


Section 16. SQLite tools
-------------------------

+ SQLite Commands – show you the most commonly used command in sqlite3 program.
+ SQLite Show Tables – list all tables in a database.
+ SQLite Describe Table – show the structure of a table.
+ SQLite Dump – how to use dump command to backup and restore a database.
+ SQLite Import CSV – how to import CSV file into a table.
+ SQLite Export CSV – how to export an SQLite database to CSV files.



SQLite Functions
==================




SQLite Programming Interfaces
==============================




Contents
========

.. toctree::
   :maxdepth: 3
   :caption: Contents:




SQLite Resources
=================
If you want to know more information about SQLite, you can go through `a well-organized SQLite resources <http://www.sqlitetutorial.net/sqlite-resources/>`_ page that contains links to useful SQLite sites.



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
