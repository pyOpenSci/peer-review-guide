# pyOpenSci Review Guide for Python Open Source Package Maintainers and Authors

Are you considering submitting a package for review with pyOpenSci? You've 
come to the right place! Below you will find the steps that you need to follow to submit a package 
to pyOpenSci for peer review. 

Before you begin this process, [please be sure to read the review process guidelines](../about-peer-review/policies-guidelines).


```{note} 
**Before you consider submitting to us please consider the following:**

1. Please be sure that you have time to devote to making changes to your 
package. During review, you would get feedback from an editor and two reviewers. Changes could 
take time. Please consider this before submitting to us. You can read more about the timeline to make changes in our [peer review policies page](../about-peer-review/policies-guidelines).
2. Peer review is lead by a diverse group of volunteer editors and reviewers. 
Please be considerate when engaging with everyone online. 
```

## 1. Do you plan to continue to maintain your package?
One of the goals of pyOpenSci is to maintain a curated list of 
community-approved, maintained and vetted tools that support open science workflows. 

As such, we review packages that will be useful to the community
and maintained over time. While we understand that burnout is real,
and you may move on in the future to other projects, we ask that you commit
to maintaining your package for at least 1-2 years after the review process 
is complete. 

If that maintenance commitment is too much, you might consider submitting 
your package to a journal that is more focused on publication only.



### Who should submit the package for review?

If you have a team of people maintaining your package, please be sure
that the submitting author is the person who "owns" or leads that maintenance. 
That person will become the long term point of contact 
for pyOpenSci. 
* Please also include the names of all maintainers on the project
as we also want to ensure that everyone working on the project gets full credit 
for their effort. 


```{note}
If your package is more of a tool to support a specific workflow that 
either:
* may not be maintained long term or 
* may be so specific that it won't have a user base outside of your lab or work environment 

please consider submitting it directly to a publisher like the
Journal of Open Source Software (JOSS). A publisher like JOSS has less
emphasis on long term software maintenance and focuses more on 
publication quality and citation / credit.  
```

## 2. Does Your Package Meet Packaging Requirements?
Before submitting your project for review with pyOpenSci, make sure that it
follows the standards and guidelines outlined in the 
[pyOpenSci Python packaging guide](https://www.pyopensci.org/python-package-guide).

```{note}
**Package Prep Help - Can we actually support this now??**

If you would like help preparing your package for review, create 
a [new help request post in our Discourse forum under `coding-help`](https://pyopensci.discourse.group/c/coding-help/10). We can find someone to help you prep your code 
and add things like testing, documentation, and/or continuous integration.  

Also check out the rest of our [Packaging Guide](https://www.pyopensci.org/python-package-guide), which may help answer some of your questions about packaging your code.

**NOTE: we are currently updating our packaging guide and intend to add 
tutorials on Python packaging. Please expect these resources to be online sometime by Spring, 2023.**
```

## 3. Is Your Package in Scope for pyOpenSci?
Next, check to see if your package falls into the topical and technical scope of pyOpenSci. If you aren't 
sure about whether your package fits within pyOpenSci's scope (below), submit
a [presubmission inquiry issue on the software-review](https://github.com/pyOpenSci/software-review/issues/new?assignees=&labels=0%2Fpresubmission&template=presubmission-inquiry.md&title=)
repository. After you submit an inquiry, a pyOpenSci editor will get back to you 
with input regarding the fit of your package for pyOpenSci review. This can take 
up to a week. 

Our current categories for determining package scope are below:

```{include} ../appendices/scope.md
```

## 4. Submit Your Package for Peer Review
To submit your package for peer review, you can 
open an issue in our [pyopensci/software-review repo](https://github.com/pyOpenSci/software-review/issues/new/choose/)
repository and fill out the [Submit Software for Review](https://github.com/pyOpenSci/software-review/issues/new?assignees=&labels=1%2Feditor-checks%2C+New+Submission%21&template=submit-software-for-review.md&title=) issue template. 

## 5. Editor in Chief Reviews Package for Scope and Minimal Infrastructure Criteria
Once the issue is opened, our editor-in-chief and an editor from our editorial board will review your submission within 
**2 weeks** and respond with next steps. The editor may request that you make updates
to your package to meet minimal criteria before review. They also may reject your 
package if it does not fall within our scope. 

```{button-link} https://www.pyopensci.org/software-peer-review-guide/editor-in-chief-guide.html#editor-checklist-template
:color: secondary
:class: sd-rounded-pill
Click here to view the editor checks that will be used to evaluate your package. 
```

## 6. The Review Begins
If your package meets minimal criteria for being 
reviewed it may then be given to an editor with appropriate domain experience 
to run the review. That editor will assign 2-3 reviewers to review your 
package. Reviewers will be asked to provide review feedback  as comments on your 
issue within **3 weeks**. Reviewers also can open issues in your package repository. 
We prefer issues that link back to the review as they document changes made to your 
package that were triggered by our review process.

## 7. Response to Reviews
You should respond to reviewers’ comments within **2 weeks** of the 
last-submitted review. You can make updates to your package at any time. We 
encourage ongoing conversations between authors and reviewers. See the 
[guide for package reviewers](reviewer-guide.md) for more details about how reviewers engage with package 
maintainers during a review.

## 8. Acceptance into pyOpenSci
Once the reviewers are happy with changes that you've made to the package, the
editor will review everything and accept your package into the pyOpenSci ecosystem.
Congratulations! You are almost done!

## My Package is Approved, Now What?

Congratulations on being accepted into the pyOpenSci community of maintainers!
Once your package is approved, a few things will happen:

1. We will ask you to ensure that your package is being tracked / archived using 
Zenodo. You will then want to created a tagged release representing the version of the 
package accepted by pyOpenSci.
2 We will ask you to add the pyOpenSci badge [![pyOpenSci](https://tinyurl.com/y22nb8up)](https://github.com/pyOpenSci/software-review/issues/issue-number) to the 
top of your **README.md** file.
1. We will ask you to add your package to the [pyOpenSci website](https://www.pyopensci.org/our-community/). This will give 
your package more visibility in the community as a vetted pyOpenSci tool.
    * We also will ask you (and those who reviewed your package) to add yourself to our list of [pyOpenSci community members](https://www.pyopensci.org/our-community/)!
1. We will promote your package on our social media channels!
1. We will invite you to write a blog on our website spotlighting your package. The blogs that our maintainers write are some of the most popular content on the website! 


If you wish to go on to submit your package to JOSS, you can do so now. Remember that JOSS will accept our review as theirs so you DO NOT need to go through another review. Read more below.

### Journal of Open Source Software (JOSS) Submission

PyOpenSci has a partnership with JOSS where our review is accepted by JOSS by
default if the package fits into the JOSS scope.

- When you submit your package for pyOpenSci review, you can opt to include a 
submission to JOSS after passing pyOpenSci review. In this case, your package 
will evaluated by JOSS through the pyOpenSci review
- To complete the JOSS submission, you will also need to craft a **paper.md** 
file describing the package following JOSS' standards (see below). More detail on the requirements for JOSS can be found on [their website](https://joss.readthedocs.io/en/latest/submitting.html#what-should-my-paper-contain).
- If you choose to opt into the pyOpenSci / JOSS partnership in your review, 
you DO NOT need to go through a second review with JOSS. JOSS accepts our review
for theirs. Please start a review process with JOSS and reference the pyOpenSci
review issue where your package was accepted. Make sure
that you let the JOSS editor know that we have already accepted your package. The JOSS editor will review your paper and once that is accepted you now have a JOSS DOI and badge to display on your README file as well!  

```{note} 
Acceptance to pyOpenSci does not guarantee acceptance to JOSS. In particular, 
JOSS doesn't accept the full variety of packages that are in scope for
pyOpenSci. For example, thin API wrappers fall within
[pyOpenSci's scope](../about-peer-review/aims-and-scope) but 
are usually not accepted by JOSS. Be sure to review JOSS's 
[submission requirements](https://joss.readthedocs.io/en/latest/submitting.html#submission-requirements) 
before writing up a paper about your package.
```

## Post review - now what?

Once you have been accepted into the pyOpenSci ecosystem, you will 
be invited to join our Slack channel.

We also will keep in touch with you, periodically checking in to ensure that package maintenance is going well and to better understand ways in which pyOpenSci can support you. 

If at any time, you need to step down from maintaining your package, 
or you need help with maintenance, please let us know - preferably 
in advance. We will try to help you by either:

* Find a new maintainer to take over your project (or additional maintainers to support maintenance) or
* Sunset your package.

If the package is sunsetted, we will remove it from our curated list 
of vetted tools. 

### Communication with pyOpenSci and removing tools from our vetted tool list 

To ensure packages that we support and advocate for are maintained, if your package is accepted and we are not able to get in touch with you through normal communication channels (GitHub, email) after reaching our for at least 1-2 months, we will remove your package from our list of vetted tools. We will also remove any blogs written that highlight your tool. 
