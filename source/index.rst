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

+ 首先，我们帮助您回答第一个重要问题：什么是SQLite？在开始使用之前，您将对SQLite进行简要概述。
+ 其次，我们将逐步向您展示如何在您的计算机上下载和安装SQLite GUI工具。
+ 第三，我们向您介绍一个SQLite示例数据库，并引导您完成使用示例数据库进行练习的步骤。


基本的SQLite教程
=================

本节介绍可以与SQLite一起使用的基本SQL语句。您将首先开始从`示例数据库 <http://www.sqlitetutorial.net/sqlite-sample-database/>`_中查询数据。如果您已经熟悉SQL，那么您会注意到SQLite中SQL标准和SQL方言之间的差异。


Section 1. Simple query
-------------------------

+ `Select <http://www.sqlitetutorial.net/sqlite-select/>`_ – query data from a single table using SELECT statement.


Section 2. Sorting rows
-------------------------

+ `Order By <http://www.sqlitetutorial.net/sqlite-order-by/>`_ – sort the result set in ascending or descending order.


Section 3. Filtering data
--------------------------

+ `Select Distinct <http://www.sqlitetutorial.net/sqlite-select-distinct>`_ – query unique rows from a table using the DISTINCT clause.
+ `Where <http://www.sqlitetutorial.net/sqlite-where/>`_  – filter rows of a result set using various conditions.
+ `Limit <http://www.sqlitetutorial.net/sqlite-limit/>`_ – constrain the number of rows that you want to return. The LIMIT clause helps you get the necessary data returned by a query.
+ `Between <http://www.sqlitetutorial.net/sqlite-between/>`_ – test whether a value is in a range of values.
+ `In <http://www.sqlitetutorial.net/sqlite-in/>`_ – check if a value matches any value in a list of value or subquery.
+ `Like http://www.sqlitetutorial.net/sqlite-like/`_ – query data based on pattern matching using wildcard characters: percent sign (%) and underscore (_).
+ `Glob <http://www.sqlitetutorial.net/sqlite-glob/>`_ – determine whether a string matches a specific UNIX-pattern.
+ `IS NULL <http://www.sqlitetutorial.net/sqlite-is-null/>`_ – check if a value is null or not.


Section 4. Joining tables
--------------------------

+ `SQLite join <http://www.sqlitetutorial.net/sqlite-join/>`_ – learn the overview of joins including inner join, left join, and cross join.
+ `Inner Join <http://www.sqlitetutorial.net/sqlite-inner-join/>`_ – query data from multiple tables using inner join clause.
+ `Left Join <http://www.sqlitetutorial.net/sqlite-left-join/>`_ – combine data from multiple tables using left join clause.
+ `Cross Join <http://www.sqlitetutorial.net/sqlite-cross-join/>`_ – show you how to use the cross join clause to produce a cartesian product of result sets of the tables involved in the join.
+ `Self Join <http://www.sqlitetutorial.net/sqlite-self-join/>`_ – join a table to itself to create a result set that joins rows with other rows within the same table.
+ `Full Outer Join <http://www.sqlitetutorial.net/sqlite-full-outer-join/>`_ – show you how to emulate the full outer join in the SQLite using left join and union clauses.


Section 5. Grouping data
-------------------------

+ `Group By <http://www.sqlitetutorial.net/sqlite-group-by/>`_ – combine a set of rows into groups based on specified criteria. The GROUP BY clause helps you summarize data for reporting purposes.
+ `Having <http://www.sqlitetutorial.net/sqlite-having/>`_ – specify the conditions to filter the groups summarized by the GROUP BY clause.


Section 6. Set operators
-------------------------

+ `Union <http://www.sqlitetutorial.net/sqlite-union/>`_ – combine result sets of multiple queries into a single result set. We also discuss the differences between UNION and UNION ALL clauses.
+ `Except <http://www.sqlitetutorial.net/sqlite-except/>`_ – compare the result sets of two queries and returns distinct rows from the left query that are not output by the right query.
+ `Intersect <http://www.sqlitetutorial.net/sqlite-intersect/>`_ – compare the result sets of two queries and returns distinct rows that are output by both queries.


Section 7. Subquery
---------------------

+ `Subquery <http://www.sqlitetutorial.net/sqlite-subquery/>`_ – introduce you to the SQLite subquery and correlated subquery.
+ `Exists <http://www.sqlitetutorial.net/sqlite-exists/>`_ operator – test for the existence of rows returned by a subquery.


Section 8. More querying techniques
-------------------------------------

+ `Case <http://www.sqlitetutorial.net/sqlite-case/>`_ – add conditional logic to the query.


Section 9. Changing data
-------------------------

This section guides you on how to update data in the table using insert, update, and delete statements.

+ `Insert <http://www.sqlitetutorial.net/sqlite-insert/>`_ – insert rows into a table
+ `Update <http://www.sqlitetutorial.net/sqlite-update/>`_ – update existing rows in a table.
+ `Delete <http://www.sqlitetutorial.net/sqlite-delete/>`_ – delete rows from a table.
+ `Replace <http://www.sqlitetutorial.net/sqlite-replace-function/>`_ – insert a new row or replace the existing row in a table.


Section 10. Transactions
-------------------------

+ `Transaction <http://www.sqlitetutorial.net/sqlite-transaction/>`_ – show you how to handle transactions.


Section 11. Data definition
----------------------------

In this section, we show you how to create database objects such as tables, views, indexes using SQL data definition language.

+ `SQLite Data Types <http://www.sqlitetutorial.net/sqlite-data-types/>`_ – introduce you to the SQLite dynamic types system and its important concepts: storage classes, manifest typing, and type affinity.
+ `Create Table <http://www.sqlitetutorial.net/sqlite-create-table/>`_ – show you how to create a new table in the database.
+ `Primary Key <http://www.sqlitetutorial.net/sqlite-primary-key/>`_ – show you how to define the primary key for a table.
+ `NOT NULL constraint <http://www.sqlitetutorial.net/sqlite-not-null-constraint/>`_ – ensure values in a column are not NULL.
+ `UNIQUE constraint <http://www.sqlitetutorial.net/sqlite-unique-constraint/>`_ – ensure values in a column or a group of columns are unique.
+ `CHECK constraint <http://www.sqlitetutorial.net/sqlite-check-constraint/>`_ – ensure the values in a column meet a specified condition defined by an expression.
+ `AUTOINCREMENT <http://www.sqlitetutorial.net/sqlite-autoincrement/>`_ – explain how the attribute AUTOINCREMENT works and why you should avoid using it.
+ `Alter Table <http://www.sqlitetutorial.net/sqlite-alter-table/>`_ – show you how to use modify the structure of an existing table.
+ `Rename column <http://www.sqlitetutorial.net/sqlite-rename-column/>`_ – learn step by step how to rename a column of a table.
+ `Drop Table <http://www.sqlitetutorial.net/sqlite-drop-table/>`_ – guide you on how to remove a table from the database.
+ `VACUUM <http://www.sqlitetutorial.net/sqlite-vacuum/>`_ – show you how to optimize database file.


Section 12. Views
------------------

+ `Create View <http://www.sqlitetutorial.net/sqlite-create-view/>`_ – introduce you to the view concept and show you how to create a new view in the database.
+ `Drop View <http://www.sqlitetutorial.net/sqlite-drop-view/>`_ – show you how to drop a view from its database schema.


Section 13. Indexes
--------------------

+ `Index <http://www.sqlitetutorial.net/sqlite-index/>`_ – teach you about the index and how to utilize indexes to speed up your queries.
+ `Index for Expressions <http://www.sqlitetutorial.net/sqlite-index-expression/>`_ – show you how to use the expression-based index.


Section 14. Triggers
----------------------

+ `Trigger <http://www.sqlitetutorial.net/sqlite-trigger/>`_ – manage triggers in SQLite database.


Section 15. Full-text search
-----------------------------

+ `Full-text search <http://www.sqlitetutorial.net/sqlite-full-text-search/>`_ – get started with the full-text search in SQLite.


Section 16. SQLite tools
-------------------------

+ `SQLite Commands <http://www.sqlitetutorial.net/sqlite-commands/>`_ – show you the most commonly used command in sqlite3 program.
+ `SQLite Show Tables <http://www.sqlitetutorial.net/sqlite-show-tables/>`_ – list all tables in a database.
+ `SQLite Describe Table <http://www.sqlitetutorial.net/sqlite-describe-table/>`_ – show the structure of a table.
+ `SQLite Dump <http://www.sqlitetutorial.net/sqlite-dump/>`_ – how to use dump command to backup and restore a database.
+ `SQLite Import CSV <http://www.sqlitetutorial.net/sqlite-import-csv/>`_ – how to import CSV file into a table.
+ `SQLite Export CSV <http://www.sqlitetutorial.net/sqlite-export-csv/>`_ – how to export an SQLite database to CSV files.



SQLite Functions
==================

+ `SQLite Aggregate Functions <https://www.sqlitetutorial.net/sqlite-aggregate-functions/>`_

This tutorial shows you how to use the SQLite aggregate functions to find the maximum, minimum, average, sum, and count of a set of values.

+ `SQLite Date Functions <https://www.sqlitetutorial.net/sqlite-date-functions/>`_

This section provides you with SQLite date and time functions that help you manipulate datetime data effectively.

+ `SQLite String Functions <https://www.sqlitetutorial.net/sqlite-string-functions/>`_

This section shows the most commonly used SQLite string functions that help you manipulate character string data effectively.

+ `SQLite Window Functions <https://www.sqlitetutorial.net/sqlite-window-functions/>`_

SQLite window functions perform a calculation on a set of rows that are related to the current row. Unlike aggregate functions, window functions do not cause rows to become grouped into a single result row.


SQLite Programming Interfaces
==============================

+ `SQLite Java <https://www.sqlitetutorial.net/sqlite-java/>`_

This SQLite Java section teaches you step by step how to interact with SQLite database using Java JDBC API.

+ `SQLite Python <https://www.sqlitetutorial.net/sqlite-python/>`_

This section guides you how to work with the SQLite database using Python sqlite3 module.

+ `SQLite PHP <https://www.sqlitetutorial.net/sqlite-php/>`_

This section shows you how to use PHP PDO to interact with SQLite databases. We will walk you through the steps of setting up PHP project structure, connecting to the SQLite database, and performing the common database operations.

+ `SQLite Node.js <https://www.sqlitetutorial.net/sqlite-nodejs/>`_

This section shows you how to interact with SQLite databases from Node.js applications using the node sqlite3 module.


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
