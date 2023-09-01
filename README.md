# Scaling Categorization for Citizen Science Data Collection

How I helped a team scale their categorization using design thinking, cross-functional collaboration, and applied research.

> 🎯 Water Reporter's reports increased by 300% from the previous year upon introducing hashtags, user accounts, and promoting these features through in-person workshops.

![Water Reporter for iPhone with an example of the Report Hashtag and User Account Features](assets/images/WaterReporter-Hashtags.png)

## Table of Contents

  * [Overview](#overview)
  * [Problem](#problem)
    + [Issues](#issues)
    + [Questions arose about category manageability](#questions-arose-about-category-manageability)
  * [Research](#research)
    + [“How might we…” Questions](#-how-might-we---questions)
    + [Iterative Storyboarding](#iterative-storyboarding)
  * [Outcomes](#outcomes)
  * [Conclusion](#conclusion)
  
## Overview
Launched in 2013 for the Potomac Riverkeepers, the [Water Reporter app]((https://medium.com/@joshuaisaacpowell/launching-the-water-reporter-app-92365be4ffa4)) initially helped their team manage and respond to pollution reports. With insights gained from generative research between 2012-2017, I led visual design, established data infrastructure, and developed follow-on apps that enabled the team to scale to 184 organizations and over 8,500 active users.

## Problem
Originally, the Water Reporter app required users to assign a category to a report for submission, a carryover from its original architecture. As the app grew to support multiple organizations, each with their own categories, the number of options ballooned to a cumbersome list. While manageable for a small group of advanced users, the increasing number of categories became unmanageable as the app expanded.

### Issues
- New organizations wanted to add their own categories, adding to the already long list
- Organizations were unwilling to give up their categories
- The list was continuing to grow with each new organization

### Questions arose about category manageability
- How long is too long for a dropdown list?
- How much time is spent choosing a category?
- How do users know which category belongs to their organization?
- Who will manage the growing list?
- Will category confusion lead to fewer submissions?
- How will duplicates and changes be managed?

## Research

As UX team lead, I tackled the issue at my desk by reviewing existing categories and cross-referencing them with pollution report keywords. But questions quickly piled up:

- How many categories are we adding in the coming months?
- What's our growth projection for the next year or two?
- How can we make the categories more readable?
- What UI patterns can solve these issues?
- How can we avoid future re-solves of the problem?

I held a follow-up meeting to clarify needs and long-term goals, from which my UX team and I formulated "How might we..." statements to focus on the problem:

- **How might we** create and share categories organically?
- **How might we** minimize the effort of maintaining categories?
- **How might we** simplify category selection's cognitive load?

![January 2015 Cross-organization retreat with Viable Industries and The Commons, Inc.](assets/images/0*lYAGvj4IHgGQ21mQ.jpg)

To make actionable recommendations, my UX team and I organized an in-person design thinking workshop to clarify our "How might we..." questions.

### “How might we…” Questions
We began the workshop by discussing the "How might we..." questions. As the facilitator, I recorded ideas, concerns, sketches, and clarifying questions on sticky notes. Once the exercise was complete, I categorized the notes and reconvened the team.

### Iterative Storyboarding
The next portion was facilitated by another UX team member. We sketched iterative storyboard concepts based on the groups of ideas, concerns, and questions we had from the previous exercise. We got everyone involved in this, even the Water Reporter organization’s executive director and software engineer.

Another member of the UX team facilitated the sketching and storyboard sessions that were based on the ideas, concerns, and questions we had categorized in the previous exercise. We involved everyone in this, including the non-profits executive director and lead analyst.

### We realized that our ideas had varying issues:

- __Type-ahead or Autocomplete__ required even more cognitive load and didn't shorten the list. How would users know what to type without context?
- __Drop Down Grouping__ would provide organization group names, but how would the organization manage the list? Would this add too much overhead?
- __Organization Specific Drop Down__ would limit the community aspect and add the same overhead as Drop Down Grouping.

### We made some decisions as a team:

- Organizations wouldn't manage their own categories
- The Water Reporter product team wouldn't manage all categories

This led us to the question: "How can we eliminate categories while maintaining structured category data?"

## Outcomes
Hashtags. Yeah, I know “hashtags” aren’t revolutionary. Hashtags are pretty common practice. Simple as they may seem, hashtags were the answer we were looking for.

- Hashtags would let the user freely “categorize” their reports
- Hashtags would reduce the number of fields on our form, no more need for a category and subcategory drop down
- Hashtags can take advantage of the first idea from above, autocomplete, and help our users find and reuse categories

Hashtags also had a few other intrinsic benefits

- __Organizations could easily "promote" specific hashtags__ for their projects, programs, initiatives, or events.
- __Users quickly accepted the new feature__ since the concept of hashtags was already well understood in 2015, resulting in minimal pushback from our user base. In fact, during usability testing, most responses were along the lines of "Wait, the app didn't always have hashtags?" and "Why didn't you add hashtags sooner?".
- __Structured data was still achievable__ as we could programmatically create and associate hashtag records with report records, enhancing our search capabilities.

## Conclusion
The 2 ½ day design thinking workshop resulted in several new features being added to the Water Reporter app, including hashtags, user accounts, and a standalone application for remediation efforts. 

I designed, implemented, and conducted usability testing on these new features for both the mobile apps and community web application. Following the introduction of hashtags, user accounts, and promotion through in-person workshops, Water Reporter experienced a 300% increase in new reports submitted.

---

This post is part of the Water Reporter series published by Joshua Powell to share the research and engineering work he’s completed over the course of his career. 

Joshua played a key role in launching the initial version of WaterReporter on ArcGIS in 2013. He subsequently contributed to expanding the platform from a single organization app to a platform serving over 200 organizations and 8,500 environmental non-profit staff and volunteers. His contributions to the platform encompassed designing and constructing the REST API infrastructure, developing mobile applications, and creating the various websites and data tooling to grow the platform.

You can read more stories, like this one, by [visiting his website](https://joshuapowell.io).
