# What's Up with MODFLOW
## alternatively, Isn't MODFLOW Dead Yet?

A Guest Editorial expresses an opinion about a topic of interest to the readership at large; it should be thought-provoking and informative. Although based on opinion, the editorial should not be used to advocate one’s own research ideas or products. Editorials are limited to one (1) published page (approximately 675 words, including headers and footnotes). A guest editorial should first be submitted to the editor-in-chief (Ken.Bradbury@wisc.edu) for review and approval.

## MODFLOW Governance Charter

The MODFLOW groundwater modeling software code was originally developed by the United States Geological Survey (USGS) in the early 1980s. Since that time, ad hoc external partnerships have resulted in significant developments that have benefited the MODFLOW community. The current MODFLOW framework facilitates rapid innovation and development through an application programming interface (API). This, combined with modern software development techniques, enables both rapid development of new functionality and deliberate and rigorous advancement of the core software. The objective of this governance is to further broaden the development and decision-making base to formally include a broader cross-section of partners from the private and academic sectors of the MODFLOW community, particularly at the technical level.

## 1. Mission and Scope

* The mission of this project is to develop the core software of MODFLOW as an open-source package serving Government, private industry, and academic users.
* The scope is the technical development of the core model framework underpinning the broader ecosystem of MODFLOW functions. This includes collaborative code development, testing, formal releases, documentation, and training.
* The USGS is responsible for formal releases, subject to USGS policies, review, and initiatives.

## 2. Technical Steering Committee

* The technical steering committee (TSC) will provide technical oversight of the project.
* The TSC will focus on short-term technical decisions, particularly introduction of new functionality and improvement of existing functionality in the MODFLOW Core (see appendix), consistent with high-level strategic goals driven by the USGS and future maintainability of the core software.
* The TSC will also provide expertise and community input into USGS development strategic goals and related functionality.
* The TSC, by majority vote, can amend this document, recording amendments in section 6 below.

## 3. Technical Steering Committee Membership

* Initial TSC membership will be chosen by USGS including at least two members from the internal USGS development team, and at least two members from the broader community. Criteria for initial selection are set by USGS, but will include a proven commitment to MODFLOW development, technical skills relevant to MODFLOW development, and ongoing support to actively engage in both development and decision-making.
* Members of the TSC will serve 3-year terms. Terms may be extended an unlimited number of times by a majority vote. New members may join if they receive a majority vote from the TSC. Members may be removed from the TSC by their own choice or by a majority vote from the TSC.
* USGS members of the TSC are the primary liaisons with USGS management. 

## 4. Technical Steering Committee Voting

* Votes will be anonymous.
* The TSC will use majority rule for voting on technical decisions.

## 5. Meeting Structure and Cadence

* The TSC will meet at least twice monthly to focus on technical implementation coordination and decisions.
* The TSC will meet at least twice annually to focus on alignment with higher level strategic goals. This will also be an opportunity for the TSC members to convey broader community needs and objectives for consideration.
* At least once per year, conditions allowing, the TSC will gather in-person for a coding hack week to work on specific objectives. This meeting may include a larger group of developers invited by the TSC.
* This document, its revision history, meeting notes, and results from technical decisions will be publicly available on the MODFLOW-ORG GitHub site.

## 6. Amendments

None

## 7. Appendix: Definitions

* MODFLOW core: This is the software framework and base functionality that is the primary focus of the TSC. Formal releases of the core software are managed by the USGS.
* MODFLOW updates: These are enhancements to the MODFLOW core that serve new functionality and become embedded in the codebase in a way that needs future maintenance and support.
* MODFLOW API: The application programming interface (API), built on community interoperability standards, that allows new, non-invasive enhancements to be coupled to the MODFLOW core without changing it.
