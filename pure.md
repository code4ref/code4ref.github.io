---
title: Code4REF
---

# How to report software outputs in Pure

This guide has been written with reference to the Pure instance at the
University of St Andrews, which is version 5.13.1 at the time of writing.

Add new Research Output from the template: "Non-textual form" -> "Software"

![Image](PureImages/01_FindTemplate.png)

Then you will see the following input form:

![Image](PureImages/02_InputForm.png)

Enter publication status(es) and date(s). 
"Published" and "Unpublished" are likely to be the relevant options.

![Image](PureImages/03_PublicationStatus.png)

Enter the publication information (at least the title)

![Image](PureImages/04_Title.png)

You may leave "media of output" as "No value" or chose "Online"
for a publicly available release.

![Image](PureImages/05_Media.png)

Add contributors. You can search for internal collaborators, or
create an external collaborator manually.

![Image](PureImages/06_FindAuthor.png)

After choosing an internal collaborator, you will see the next window.

![Image](PureImages/07_AddAuthor.png)

The list of roles here is not really suitable for software projects
(this is something to ask Pure developers in the future), so for now
"Author" is likely the most useful role. There is no suitable role for
maintainers, testers etc. - you should use "Other".

![Image](PureImages/08_AuthorRole.png)

After adding a new author, you will see the extended list of authors:

![Image](PureImages/09_TwoAuthors.png)

You can change the managing organisational unit, but only if necessary.

The next step is to specify a publisher.

![Image](PureImages/10_Publisher.png)

If it is not one of the recognised publishers (e.g. the website of the software system), you can leave it empty.

![Image](PureImages/11_Find_Publisher.png)

After that, fill in "Electronic version(s), and related files and links".
This is the place where you can link to an external resource and/or upload files.
In particular, if you have a DOI you should add it here.

For example, below is what is used for the recent release of the GAP system:

![Image](PureImages/12_Versions.png)

![Image](PureImages/13_FinalPublished.png)

![Image](PureImages/14_GitHubTag.png)

When adding keywords, try and be consistent with what you have used elsewhere
(e.g. on GitHub) but try and avoid creating new keywords unnecessarily.

Link the record to any relevant existing records in Pure - Research Outputs
(papers), Acitvities, Projects, Datasets etc.

![Image](PureImages/15_Relations.png)

Finally, set the visibility according to how you wish the record to be available
and press "Save".

