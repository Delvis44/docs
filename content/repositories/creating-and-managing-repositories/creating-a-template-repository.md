---
title: Creating a template repository
intro: 'You can make an existing repository a template, so you and others can generate new repositories with the same directory structure, branches, and files.'
permissions: Anyone with admin permissions to a repository can make the repository a template.
redirect_from:
  - /articles/creating-a-template-repository
  - /github/creating-cloning-and-archiving-repositories/creating-a-template-repository
  - /github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/creating-a-template-repository
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Repositories
shortTitle: Create a template repo
---
{% note %}

**Note**: Your template repository cannot include files stored using {% data variables.large_files.product_name_short %}.

{% endnote %}

To create a template repository, you must create a repository, then make the repository a template. For more information about creating a repository, see "[AUTOTITLE](/repositories/creating-and-managing-repositories/creating-a-new-repository)."

After you make your repository a template, anyone with access to the repository can generate a new repository with the same directory structure and files as your default branch. They can also choose to include all the other branches in your repository. Branches created from a template have unrelated histories, so you cannot create pull requests or merge between the branches. For more information, see "[AUTOTITLE](/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)."

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
1. Select **Template repository**.
  ![Checkbox to make a repository a template](/assets/images/help/repository/template-repository-checkbox.png)
