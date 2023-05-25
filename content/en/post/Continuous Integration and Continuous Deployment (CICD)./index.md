---
title: Continuous Integration and Continuous Deployment (CI/CD).
subtitle: 
# Summary for listings and search engines
summary:

# Link this post with a project
projects: []

# Date published
date: '2023-03-15T00:00:00Z'

# Date updated
lastmod: '2023-03-15T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `1.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [Этапы CI/CD](https://simpleone.ru/glossary/ci-cd-cd-continuous-integration-continuous-delivery-continuous-deployment/#)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin


tags:
  - education


categories:
  - Post on the chosen topic

---



## Continuous Integration and Continuous Deployment (CI/CD).

**Continuous Integration (CI)**

Continuous Integration (CI) is the primary, basic software update process, in which all code—level changes are made to a single central repository. Such an introduction is commonly called a merger. After each merge (which takes place several times a day), automatic assembly takes place in the modified system (often the application is packaged in Docker) and testing (checking specific code modules, UI, performance, API reliability). Thus, developers are insured against too late detection of problems in updates.

**Continuous Delivery (CD)**

Continuous Delivery (CD) — CI + CD. The next level after CI. Now a new version is not only created and tested every time the code is registered in the repository, but it can also be launched quickly at the click of the deploy button. However, the deployment is still launched manually — someone still needs to press the same button. This method allows you to release changes in small batches, which are easy to change or eliminate if necessary.


**Continuous Deployment (CD)**

Continuous Deployment (CD) — CI +CD + CD. After automating the release, there is only one manual stage left: approval and launch of the deployment. The practice of continuous deployment eliminates this, too, without requiring direct approval from the developer. All changes are deployed automatically.





