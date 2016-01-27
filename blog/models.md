in our blog

Features
========

Blog will have the following features:

1. Post(table in database)
2. Categories(table in database)
3. Tag(table in database)
4. Author(table in database)

Relation between our tables
===========================

1. Post can have many categories, and a category can belong to many posts (relation between Post and Category)(ManyToMany relation)

2. a tag can have many posts and a post can have many tags (ManyToMany relation)

3. Author can have many posts and a post can have a single author (OneToMany relation) [ no post can have more than one author ]

Attributes for tables
=====================
Post
====
1. title
2. created_date
3. body
4. tags
5. categories
6. author

Categories
==========
1. cat_name
2. cat_description

Author
======
1. author_name
2. author_email
3. author_bio


Tag
===
