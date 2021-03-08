# **django-crud**

**Author**: Amber Falbo <br>
**Version**: <br>
1.0.0 (skelton, 3/6/21)<br>
1.1.0 (MVP, 3/7/21)

## Overview
Add full CRUD functionality to your bag of tricks by building a Django project that allows Creating, Reading, Updating and Deleting.

## Getting Started
Create `snacks_crud_project` Django project<br>
Create `snacks` app<br>
Create `Snack` model<br>
- title field<br>
- purchaser field<br>
- description field<br>
- Register model with admin<br>

Create `SnackListView` that extends appropriate generic view<br>
- associated url path is an empty string<br>

Create `SnackDetailView` that extends appropriate generic view<br>
- associated url path is <int:pk>/<br>

Create `SnackCreateView` that extends appropriate generic view<br>
- associated url path is create/<br>

Create `SnackUpdateView` that extends appropriate generic view<br>
- associated url path is <int:pk>/update/<br>

Create `SnackDeleteView` that extends appropriate generic view<br>
- associated url path is <int:pk>/delete/<br>

Add urls to support all views, with appropriate names<br>
Add templates to support all views<br>
Add navigation links in appropriate locations to access all pages<br>
Make all necessary changes to project level files for project to run<br>
In other words, make it work<br>

<!-- ## Example -->
<!-- Show them what looks like and how how to use the application.  -->

<!-- ## Architecture -->
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->

<!-- ## Change Log -->
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an example:

01-01-2001 4:59pm - Added functionality to add and delete some things. -->