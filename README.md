# CMPSC 480: Assignment 7, Starting a portfolio
* Due: 18 November
  * With supporting assignments along the way

## Supporting readings

This assignment assumes that you either:

* do not have a portfolio site already
* are interested in re/building a new one

If you already have a portfolio and would like to move forward with your existing site, your site must still comply with all of the content-based best practices (see the [projects](#including-projects) section).

* [Why Every Job Seeker Should Have a Personal Website](https://www.forbes.com/sites/jacquelynsmith/2013/04/26/why-every-job-seeker-should-have-a-personal-website-and-what-it-should-include/)
* [Getting Started with GitHub Pages](https://guides.github.com/features/pages/)
* [Eleventy, a simpler static site builder](https://www.11ty.dev/)

### Optional

* [Google domains](https://domains.google/)
 
Note: if you already have a site using Netlify or another provider, you do not need to rebuild it on GitHub pages; alternatively, if you would _rather_ build using another platform, please reach out to Technical Leaders or the instructor.
 
## Overview
 
This assignment is meant to jump-start the development of a personal portfolio site. Resuḿes, elevator pitches, and  presentations  aside, the quality and novelty of your responses to real-world practical or theoretical issues through the discipline of computer science often rests on the more concrete work that you do. Projects generated by your interes in participating in software culture serve as practical, concrete expressions of skills enumerated in professional documents and conversations. Often functioning as a "calling card" and finishing touch for your presentation of your technical identity, web portfolios do one thing well: they _show your work_.

But, they're not the end-point of the conversation about your professional identity. If anything, they serve as one more "entry" or "channel" to the universe of your work.

### Building a portfolio

This project should result in a GitHub repository from which to deploy your site that:

1. Contains website markup/code using a theme whose choices (color, layout, opportunities and abilities) are consonant with the "pre-work" completed this semester
2. Comprises itself from material which features at least content from your Resuḿes, developer narrative (in the form of personal statements or an "About Me" section), and any public projects targeted toward your current professional goals (see the [Projects section below](#including-projects))
3. Provides links to your various professional social networks (including, but not limited to: LinkedIn, GitHub)
4. Uses functionality to monitor and provide analytics data on visitors for your site; Google Analytics has become the de facto standard. However, tracking social media engagement can be a bit complicated{read some of Google's posts about understanding and [tracking social interactions](https://support.google.com/analytics/answer/6209874) and [understanding analytics](https://developers.google.com/analytics/devguides/collection/analyticsjs/social-interactions)
5. Has a link to the final site and repository included below:
6. Features a professional `README`, using a short "About Me" statement and other professional links

My website URL:
https://tourmaline-hotteok-61e4ca.netlify.app/

My website's github repo:
https://github.com/Allegheny-ComputerScience-302-S2022/dlholland-personal-portfolio

6. A reflective statement in this repository's `reflection.md` file which addresses:

* A brief description of your site build process (including challenges and solutions)
* A summary of the audiences for which the site is built and how its overall form and content cater to their interests
* How your design decisions are informed by the various professional documents you've completed this semester

#### Using `11ty`

Per `11ty` guidelines, you'll need:

* `nodejs` > 12.0 or newer

To install a given template:

1. `clone` the template to your repository directory, preferably as the `site` directory:

```bash
git clone URL_OF_TEMPLATE site
```

2. `cd` to the `site` folder and `npm install`
3. For _some_ themes (including the included example), `npm start` will launch a `localhost` server at port `8080`, visit it in your browser at [http://localhost:8080](http://localhost:8080)
4. Other templates will likely have other instructions; **_pay attention to their `README.md`!_**

### Including projects

Your work (in any discipline) may encompass projects which do or do not include code. For every project, depending on format, any item you post to your professional portfolio site should adhere to the appropriate checklists below.

#### Code-based projects

A GitHub repository stored in your personal GitHub account which stores code for a project that:

1. Follows platform best practices for project documentation (specifcally as they pertain to `README.md` files, many of which appear in the [GitHub Guide to Documenting your projects on GitHub](https://guides.github.com/features/wikis/))
2. Contains full and complete source for the program; this includes installation and any needs for deployment
3. Uses in-line comments or documentation to enhance understanding and code legibility
4. Organizes itself according to practices like those proposed by this helpful repository
5. Observes and implements licensure correctly (respecting Fair Use, other other contemporary conventions around licensing and copyright
6. Appears in any combination of languages or scripts, keeping in mind that many different communities institute different kinds of best practices with regards to formatting and syntax
7. Uses GitHub Flow best practices including branching, merging, and descriptive, professional documentation of process (i.e. commit messages, et al.)

Note on GitHub repositories: adding the appropriate license is a requirement (in addition to the recommended documentation). [Consult this guide](https://choosealicense.com/) to understand the various licenses and how to use them.

#### Content-based projects

The rules for these necessarily ambiguous projects are, themselves, necessarily ambigious. However, for any public project you wish to use as a portfoio item:

1. Edit and revise to ensure documents are free of typographical or content-based issues
2. Incorporate some element of design if the medium requires it (for example, revisit visual aesthetics for a Powerpoint presentation deck or other visual media)
3. Include links to any relevant portions of the project which are hosted elsewhere
4. Provide a brief 100-200 word description of the project which describes its source, intent, and outcome -- especially if the project had a public impact or outcome

##### Blogs

If planning a blog, include (in the repository's `reflection.md`) a standard publishing schedule (e.g. frequency of posts, channels -- social media -- where this content will be shared, and how often).

### "Tiered" grading

This assignment does not inherently have grading tiers. The work we complete along the way _will_, though. Given that this work will feed into your site's process, the end result of a higher-quality process _should_ lead to an inevitable higher-quality site.

#### A note on working hours

You are welcome to work on this project during dedicated class time in your groups, and I suggest doing so as you will have the most direct support from instructors or Technical Leaders. Know, however, that projects like the above often require considerable "off-hours" labor and maintenance.
