---
title: "Residue-Free Computing"
collection: publications
permalink: /publication/residuefree
excerpt: 'Use your computer without leaving potentially invasive digital breadcrumbs'
date: 2021-07-22
venue: 'Proceedings on Privacy Enhancing Technologies'
paperurl: 'https://www.sciendo.com/article/10.2478/popets-2021-0076'
projectpage: /residuefree
github: 'https://github.com/LArkema/residuefree'
citation: 'Arkema, Logan and Sherr, Micah &quot;Residue-Free Computing&quot; <i>Proceedings on Privacy Enhancing Technologies</i>, vol. 2021, no.4, 2021, pp.389-405.'
---
**Abstract:** Computer applications often leave traces of residue that enable forensic examiners to gain a detailed understanding of the actions a user performed on a computer. Such digital breadcrumbs are left by a large variety of applications, potentially (and indeed likely) unbeknownst to their users. This paper presents the concept of residue-free computing in which a user can operate any existing application installed on their computer in a mode that prevents trace data from being recorded to disk, thus frustrating the forensic process and enabling more privacy-preserving computing. In essence, residue-free computing provides an “incognito mode” for any application. We introduce our implementation of residue-free computing, ResidueFree, and motivate ResidueFree by inventorying the potentially sensitive and privacy-invasive residue left by popular applications. We demonstrate that ResidueFree allows users to operate these applications without leaving trace data, while incurring modest performance overheads.

[Download paper here](/files/residue-free_computing.pdf)

This paper has a dedicated [project page]({{ page.projectpage }}) and a [github repository]({{ page.github }}) with more technical information about our implementation and links to an Ubuntu VM with ResidueFree ready to run.