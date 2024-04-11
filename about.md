---
layout: page
title: Background
permalink: /about/
---

* [Building the Collections](#building-the-collections)
* [Our Collaborative Approach](#our-collaborative-approach)
* [Driving Technical Innovation](#driving-technical-innovation)

### Building the Collections

The End of Term Web Archive collaboration began in the summer of 2008, when the project partners,
all members of the [International Internet Preservation Consortium (IIPC)][iipc] and partners in
the [National Digital Infrastructure and Preservation Program (NDIIPP)][ndiipp], agreed to join
forces to collaboratively archive the U.S. Government web at the end of the Bush administration.
The goal of the project team was to execute a comprehensive harvest of the Federal Government
domains (.gov, .mil, .org, etc.) in the final months of the Bush administration, and to document
changes in the federal government websites as agencies transitioned to the Obama administration.
The project team resumed efforts to document changes in the government web during the transition
to Obama’s second term. The archive includes Federal Government websites in the Legislative,
Executive, and Judicial branches of government.

For the 2008 archive, a broad, comprehensive crawl of sites began in August 2008, and project
participants crawled, at varying frequencies, areas of the government web of particular interest
to their organizations. The project team also called upon government information specialists,
including librarians, political and social science researchers, and academics, to assist in the
selection and prioritization of selected websites to be included in a focused crawl. These
included sites identified as being potentially greater at risk of rapid change or disappearance.
The prioritized URLs were collected in December 2008, and again after the inauguration in
January 2009. In Spring and Fall 2009 a final broad, comprehensive crawl was performed to document
any final changes that had occurred. Each of the project partners then transferred the content they
had collected to form a single consolidated archive. The Internet Archive hosts the public access
copy of this archive, the Library of Congress holds a preservation copy, and the University of
North Texas holds an additional copy for data analysis. A total of 15TB of content was archived for EOT2008

For the 2012 archive, the process and partners from 2008 were the similar, with crawling beginning
in November 2011 by some partners institutions and bulk crawls by Internet Archive beginning in
January 2012 . Volunteers to help identify sites were again solicited, and the project team worked
closely with a group of students at the [Pratt School of Information][volunteers_pratt] to
identify additional social media content for capture. A total of 41TB of content was archived for EOT2012

For the 2016 archive, the original partners gathered again, and added Stanford University and
George Washington University as new collaborative partners. We worked with a wide range of
[volunteers][volunteers_2012] to build and promote the archive, thanks to an increased interest
by community members and the press regarding the preservation of federal government websites and
data. With increased press about the project as well as more public interest in changing
government websites, the Nomination Tool saw almost 11,400 nominations, and through the EOT's
collaboration DataRefuge, Environmental Data and Governance Initiative (EDGI), and other efforts,
a total of 100,000 webpages or government datasets were nominated by citizens and preservationists
for archiving. A total of 139TB of content was archived for EOT2016

For the 2020 archive, the End of Term team gathered document what became the transition from the Trump administration to the Biden administration. Two instance of the nomination tool were run with 37,296 URLs being added to the Bulk Lists nomination instance and 4,059 URLs from 57 nominators added to the main nomination tool instance. The Internet Archive and the University of North Texas crawled with the Internet Archiving being responsible for the larger crawls and the University of North Texas focusing on .mil domains and the suggested URLs from the nomination tool. A total of 266TB of content was archived for EOT2020

### Our Collaborative Approach

By collaborating, the partners brought various skills and interests to the project. Crawls were
performed by a number of the partner institutions, others helped with project and volunteer
coordination, others developed the front-end interface to the project or supported transfer of
data between partners.

### Driving Technical Innovation

The scale of the collection and the scope of collaboration behind the End of Term Web Archive
itself drove new developments in web harvesting and access technologies. Here are some of the
tools that were used, modified, or created in the process of carrying out this work:

* To identify, prioritize and describe the thousands of U.S. Government web hosts, the University
of North Texas built the Nomination Tool. This tool enables collaborative collection development
for web archiving, and has since been used in other archiving efforts.
* All of the partners who collected content used the [Heritrix web crawler][heritrix],
developed by the Internet Archive with support from the IIPC.
* To solve the challenges presented by transferring and aggregating the End of Term Content, the
Library of Congress developed [Bagit Library][bagit_library],
an open source Java library to support large-scale
data transfer among many institutions. The Library also released [Bagger][bagger],
an open source desktop version of the Bagit Library.
For further detail, see [The End of Term was only the beginning][eot_beginning].
* The Internet Archive reconfigured existing in-house tools to automatically generate metadata
records for the over 6,000 websites in the End Of Term Web Archive. With the California Digital
Library providing input on the Dublin Core format, IA generated the records and thumbnail images
you see when you [browse the archive][eot_web_archive].
* The University of North Texas has used the End of Term content as the data source for additional
study of automatic classification of government agency web content. For further information on
UNT's work, see [Classification of the End of Term Archive: Extending Collection Development to
Web Archives][eot_classification].
* The California Digital Library modified its open source [eXtensible Text Framework (XTF)][xtf] +digital
library access platform to provide a gateway to web-archived materials. This work is part of
broader analysis underway at CDL to more fully integrate discovery systems and formats.

The challenges posed by the scope and scale of this collaborative effort have been met with
innovation at each of the partner institutions, and have resulted in considerably more than the
archive alone.

[iipc]: https://netpreserve.org/
[ndiipp]: https://www.digitalpreservation.gov/
[volunteers_2012]: http://freegovinfo.info/node/3739
[volunteers_pratt]: https://blogs.loc.gov/thesignal/2012/11/an-abundant-crop-the-end-of-term-harvest/
[heritrix]: https://webarchive.jira.com/wiki/spaces/Heritrix
[bagit_library]: http://sourceforge.net/projects/loc-xferutils/
[bagger]: https://groups.google.com/forum/#!topic/digital-curation/g6B7H_0zraM
[eot_beginning]: http://blogs.loc.gov/digitalpreservation/2011/07/the-end-of-term-was-only-the-beginning/
[eot_web_archive]: http://eotarchive.cdlib.org/search?browse-all=yes
[eot_classification]: https://webarchive.library.unt.edu/unteotcd/20131004144728/http://research.library.unt.edu/eotcd/wiki/Main_Page
[xtf]: http://xtf.cdlib.org/
