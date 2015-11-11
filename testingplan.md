# W3C QA Manager – Preliminary Project Plan 
This document outlines a preliminary project plan for the [W3C QA Manager](http://www.w3.org/Consortium/Recruitment/#qamgr) position. It also identifies the stakeholders, their needs, and a set of tasks for the QA Manager to kick-start the project. I’ve assumed that the project will run for approximately 2 years. Some aspects may require additional funding from the W3C or its membership.

**This is a draft/personal proposal for review by the general public. It has no official standing and is not endorsed by the W3C.**

## Responsibilities of the QA Manager
Having spoken to various stakeholders and W3C members, I’d like to propose that the QA manager have the following responsibilities (these cover the responsibilities listed on the W3C's [description of the position](http://www.w3.org/Consortium/Recruitment/#qamgr), but go into a bit more detail on each):

 * Gather understanding of the requirements from the various industry sectors involved at the W3C. Particularly from telecommunications, entertainment/media, social media, and gaming industries.
 
 * Coordinate the allocation of resource to create test suites (or similar applications) that meet the testing and conformance requirements of various industry sectors involved at the W3C.

 * Collaborate with the appropriate working groups to ensure that test suites have enough coverage to achieve technological interoperability and satisfy W3C Process requirements. The aim being to make sure these specifications can progress to “Recommendation” status in a timely manner.

 * Where possible, push to harmonize the format, quality, and means of accessing tests that pertain to the Web Platform (i.e., those technologies that come under the HTML5 umbrella).

 * Manage improvements to existing testing tools – particularly testharness.js and WebIDL harness.

 * Leverage existing infrastructure (within and outside the W3C) to make tests readily accessible to the W3C membership and the public at large.

 * Track testing efforts across working groups and report to stakeholders on progress. Where progress has stalled, find ways to get things moving again.

 * Establish an active/informed testing community across the W3C membership, in which the public can also participate.

* Document the location of test suites, as well as relevant details pertaining to those test suites. Where possible, encourage Editors to provide pointers to test suite in their specifications and provide relevant markers of stability.

##  Stakeholders
Given the set of responsibilities, the QA Manager will need to coordinate with the following stakeholders:

 * Industry representatives, particularly those involved in:
   * Core Mob
   * the Web and TV IG.
 * Tools and Tests WG.
 * Browser vendors.
 * Developers of testharness.js and Web IDL Harness.
 * Coordinators of Test the Web Forward.
 * W3C management and team.
 * W3C Chairs, editors, and community at large.

## Needs of stakeholders
By coordinating tasks across all these stakeholders, the W3C can create a complete quality assurance solution to meet their needs.

Broadly speaking, these needs of stakeholders are as follows:

 1. Have a documented shared understanding of where we want to be in the short, medium, and long term (i.e., to fit into the HTMLWG’s 2014 Plan).
 2. Have test suites that over time can result in interoperable implementations of Web standards.
 3. Get IPR commitments from document reaching Recommendation status.
 4. Put in place resources and infrastructure that allows the membership to collaborate effectively on QA related matters.
 5. Establish services or tangible deliverables (e.g., downloadable/modular test suites) that allow industry to assure the quality of their own products and services.

## Tasks intended to meet the needs of stakeholders
To meet the needs of stakeholders, the following section describes an initial set of tasks that need to be undertaken by the QA manager.

## Coordinate with Industry
Each industry has its own acceptance testing that is performed to ascertain if a product is ready to go to market. In order to better service major industry sectors involved at the W3C, it is important to understand and document how these industries undertake their testing. Having that knowledge can potentially help the W3C better serve its membership in various industry sectors.

<strong>Task:</strong> Meet with various industry representatives to understand and document their requirements. If possible, gain access to their current testing frameworks to get a technical understanding of how they currently operate.

### Core Mob
As is evident by the number of participants in the [Core Mob Community Group](http://www.w3.org/community/coremob/), there is a strong desire to rapidly achieve a standardized and competitive Web Platform. The value in [Core Mob](http://www.w3.org/community/coremob/) is that it contains an active community of industry players ranging from hardware manufacturers, mobile network operators, news media publishers, browser vendors, game publishers, web developers, and representatives from large e-commerce websites.

Unfortunately, due to various factors, [Core Mob](http://www.w3.org/community/coremob/) has made limited progress towards meeting its goals. As a consequence, the [Core Mob CG](http://www.w3.org/community/coremob/) has now switched towards creating scenario/personal-based use cases and requirements. This is a positive step forward, but it does not yet cover the needs of the industries currently represented in the community group. This gives an opportunity for the QA Manager steer the group towards defining a set of scenarios that meet the needs of the represented industries.

If consensus can be reached in the group, the [Core Mob CG](http://www.w3.org/community/coremob/) could define actual applications that would serve as test suites. With appropriate funding, these applications could be professionally developed. This can be seen as akin to the Acid Test style testing – but unlike the Acid tests, the applications would be created to specifically exercise certain capabilities under realistic situations, as opposed to focusing on edge cases.

Note that testing scenarios would compliment traditional test suites, not supersede them.  

<strong>Task:</strong> Coordinate with the [Core Mob CG](http://www.w3.org/community/coremob/) to define usage scenarios and create a set of applications that meet the testing needs of industry (i.e., make sure key industries are represented and that they are satisfied with the requirements).

<strong>Task:</strong> Manage the creation of test suites or applications that can meet industry requirements. Depending on the applications that the group would build, the W3C should seek approximately $20,000 per application (it will probably need 4-5 distinct applications to cover all the requirements). A budget can be drafted once we have more information and consensus to move forward with the project.

###Web and TV IG
The [Web and TV IG](http://www.w3.org/2011/webtv/) recently formed a testing Task Force (TF) that aims to: 

 * reach out to industry to understand where tests are currently lacking, or are inconsistant, and what test suites need to be prioritized.
 * gather requirements to enable a single point of access from where one or many test suites can be run. 
 * explore how different devices can be tested in a way that meets industry requirements.

See also [presentation from TPAC 2012](http://www.w3.org/2012/10/29-webtv-slides/WebTVTestingTF.pdf).

<strong>Task:</strong> help with outreach to industry members with Web and TV IG testing task force. 

<strong>Task:</strong> help requirements gathering and documentation.  

## Coordinate with tools and Tests WG
A critical component that is being developed by the Tools and Tests WG is [Web Driver](http://www.w3.org/TR/webdriver/). [Web Driver](http://www.w3.org/TR/webdriver/) facilitates automation of dynamic data and user interaction in Web applications. This piece of technology is critical for testing parts of the Web platform that cannot otherwise be tested without human intervention.

Additionally, the [Tools and Test WG](http://www.w3.org/testing/browser/) contains subject matter experts with significant experience in testing browser-based software on a large scale (e.g., Wilhelm Joys Andersen, formally of Opera software). Given their experience, it would be helpful to have such individuals involved throughout the lifetime of this project.

<strong>Task:</strong> Investigate and document the limitations of Web Driver. 

<strong>Task:</strong> Speak to various industry representatives about the feasibility of using Web Driver on various devices and platforms (e.g., on TVs and mobile).   

<strong>Task:</strong> Track progress on Web Driver and reach out to any browser vendor not yet fully supporting the standard.

<strong>Task:</strong> Discuss infrastructure requirements, as well as general QA issues, with key members of the working group. Particularly, work out what the pros and cons are with current the testharness.js approach.

## Source tests from browser vendors
Browser vendors contribute the majority of tests that make up the test suites at the W3C. As such, the QA Manager will need to liaise with browser vendors to source the majority of tests for the Web Platform.

<strong>Task:</strong> Identify and co-ordinate with key QA staff working for browser vendors to source tests. Where possible, and under confidentiality if necessary, work with those individuals to find ways to reduce duplication (and to source the test suites once browser vendors are ready to hand them over).

<strong>Task:</strong> For when test suites are sought, coordinate the review and cleanup of test suites (i.e., remove any vendor specific material and identify gaps).

<strong>Task:</strong> Communicate and promote the sourcing of a test suite with the rest of the W3C community.

<strong>Task:</strong> Where no browser vendor is working on test suites, seek funding from industry to allow other resources to create a test suite.

## Manage testharness.js and Web IDL Harness
[testharness.js](http://w3c-test.org/resources/testharness.js) is rapidly becoming the testing framework of choice for those involved with HTML5. As such, this resource must be managed in a way that meets the needs of stakeholders (currently, it’s primarily serving the needs of browser vendors).

Another important side project that builds on testharness.js is [IDL Harness](http://www.w3c-test.org/resources/idlharness.js). This application converts Web IDL fragments into testharness.js compatible tests automatically. Effectively, [IDL harness](http://www.w3c-test.org/resources/idlharness.js) can generate thousands of tests thus providing more complete coverage of specifications – while saving potentially hundreds of hours in manual test creation and verification. [IDL harness](http://www.w3c-test.org/resources/idlharness.js) was developed by Aryeh Gregor, but unfortunately, it is not yet complete and its development needs to be managed (perhaps even funded).

<strong>Task:</strong> Coordinate with James Graham and make sure he has everything he needs to keep testharness.js going.

<strong>Task:</strong> Coordinate with members using testharness.js to make sure they have everything they need to use test harness effectively.

<strong>Task:</strong> Make sure [IDL harness](http://www.w3c-test.org/resources/idlharness.js) is completed and continues to match Web IDL. Continue to find resources to improve documentation.

<strong>Task:</strong> Talk to Aryeh Gregor and see what he needs to finish [IDL harness](http://www.w3c-test.org/resources/idlharness.js). If possible, find funds and other resources to help maintain the project.

## Add Web IDL checking to Pub Rules
The W3C currently requires that all specifications meet a certain quality criteria before being eligible for publication on [/TR/](http://www.w3.org/TR/). However, the “[Pub Rules](http://www.w3.org/2005/07/pubrules)” system currently lacks any checks for conformance to [Web IDL](http://www.w3.org/TR/WebIDL/). This is currently a problem with some specifications that have reached [/TR/](http://www.w3.org/TR/) because their IDL does not conform to [Web IDL](http://www.w3.org/TR/WebIDL/) (hence, they won’t be machine processable).

For specifications that use [Web IDL](http://www.w3.org/TR/WebIDL/), when a specification reaches a certain publication status, [Pub Rules](http://www.w3.org/2005/07/pubrules) should enforce conformance to [Web IDL](http://www.w3.org/TR/WebIDL/). This could be done through Robin Berjon’s Web IDL parser.

<strong>Task:</strong> Coordinate with W3C system’s team to see if they can add optional conformance checking for Web IDL. If possible, work out how to make it user friendly.

<strong>Task:</strong> Coordinate with Robin Berjon to make sure that the Web IDL parser can be used as a service and outputs human-friendly error messages.

<strong>Task:</strong> Communicate with spec Editors to make sure they put the right hooks in place to allow Pub Rules to find their Web IDL.

## Source test from community
Although the majority of tests come from browser vendors, other members sometimes contribute a small number of tests. Where possible, documentation should be made available to allow other W3C members to contribute tests.

<strong>Task:</strong> Gather documentation for how to contribute tests, as well as any templates, etc.

<strong>Task:</strong> Established a centralized place where people can find out about testing.

<strong>Task:</strong> Help members who want to do testing get started.

## Test the Web Forward
[Test the Web Forward](http://testthewebforward.org/), and similar events, plays an important role educating the development community about browser testing and reporting bugs. Unfortunately, the majority of the tests sourced from <cite>Test the Web Forward</cite> are generally not of sufficient quality to be incorporated into a HTML test suite. Regardless, some percentage of tests from the event can be salvaged for integration into test suites of related specifications.

<strong>Task:</strong> investigate ways to increase the quality of tests generated at these events (so less tests are discarded). This will include discussing what the limitations are with organizers and test reviewers, and making sure that these are documented and articulated to those making tests.