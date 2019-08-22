---
title: Code4REF
---

# How to report software outputs in Pure

This guide has been written with reference to the Pure instance at the
University of St Andrews, which is version 5.13.1 at the time of writing.

Create a new Research Output from template **Non-textual form->Software**

![Image](PureImages/01_FindTemplate.png)

Then you will see the following input form:

![Image](PureImages/02_InputForm.png)

Enter details for **Publication status and dates**. **Published** and
**Unpublished** are likely to be the relevant options, with Published being
appropriate for open-source software.

![Image](PureImages/03_PublicationStatus.png)

Enter the publication information. Note that the mandatory **Original
language** field does not refer to programming languages.

![Image](PureImages/04_Title.png)

Leave **Media of output** as **No value**, or specify **Online** for software publicly available for downloads.

![Image](PureImages/05_Media.png)

Add **Contributors**. Here you can search and add an internal contributor by their
nbame, or create an external person.

![Image](PureImages/06_FindAuthor.png)

After choosing an internal collaborator, you will see the next window.

![Image](PureImages/07_AddAuthor.png)

The list of roles here is not really suitable for software projects
(this is something to ask Pure developers in the future), so for now
**Author** is likely the most useful role. There is no suitable role for
maintainers, testers and other contributors who are not authors - for these, you should use **Other**.

![Image](PureImages/08_AuthorRole.png)

After adding a new author, you will see the extended list of authors:

![Image](PureImages/09_TwoAuthors.png)

Change the **Managing organisational unit** if necessary.

Add **Publisher** information.

![Image](PureImages/10_Publisher.png)

Potentially relevant options such as GitHub and Zenodo may already be available, or they can be created.
If the software is available from its webpage, but not published via some repository, you can leave this field blank.

![Image](PureImages/11_Find_Publisher.png)

The next section, **Electronic version(s), and related files and links**, is
where you can link to an external resource and/or upload files. In particular,
if you have a DOI you should add it here, along with details of the applicable
license.

For example, below is what is used for the release of the [GAP system](https://www.gap-system.org), [version 4.10.1](https://www.gap-system.org/Releases/4.10.1.html):

![Image](PureImages/12_Versions.png)

This is a link to the downloads page for the official GAP distribution:

![Image](PureImages/13_FinalPublished.png)

This is a link to the corresponding tag in the GAP repository on GitHub:

![Image](PureImages/14_GitHubTag.png)

If adding any **keywords**, try and be consistent with what you have used
elsewhere (e.g. on GitHub) but try and avoid creating new keywords
unnecessarily.

Add details of any **Relations** the record has to any existing records in Pure
- **Research Outputs** (papers), **Activities**, **Projects**, **Datasets** etc.

![Image](PureImages/15_Relations.png)

Finally, set the **Visibility** according to how you wish the record to be available
and press **Save**.


## How to import code to PURE via ORCID

This guide has been written with reference to the Pure instance at the
University of Birmingham, which is version 5.14.1 at the time of writing.

*Prerequisites:* 
* You will have to have your code listed as a research output on your [ORCID record](https://orcid.org/). You can do this manually or, if your code has a DOI assigned through [zenodo](https://zenodo.org/) or [figshare](https://figshare.com/), via [ORCID's search and link functionality](https://support.orcid.org/hc/en-us/articles/360006973653-Add-works-by-direct-import-from-other-systems) using the [DataCite](https://datacite.org/) wizard.
* Your institution has enabled ORCID as an import source for PURE.

Create a new research output by choosing "Import from online source" and pick ORCID

![Image](https://github.com/pherterich/code4ref.github.io/blob/master/PureImages/16_ORCID_import.png)

Search using your ORCID identifier and you will get a list of records on your ORCID profile that are not on PURE yet. Pick the one you'd like to add and click **import**.

![Image](https://github.com/pherterich/code4ref.github.io/blob/master/PureImages/17_ORCID_results.png)

This will add most of the metadata automatically and you will just need to ensure that creators are mapped correctly to researchers at your institution.

The import will automatically choose the template **Research output-> Other contribution**. You will change template to **Non-textual form->Software** as shown above.

![Image](https://github.com/pherterich/code4ref.github.io/blob/master/PureImages/18_Template_change.png)

You can now add any other information following the steps lined out above.
