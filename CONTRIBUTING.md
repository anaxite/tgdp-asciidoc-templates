# Good Docs Project - Template contributing guide

Welcome to the Good Docs Project! If you’re reading this guide, that probably means you’d like to get involved and start contributing to the project. This document should hopefully help you become a full templateer (which is how we refer to the members of our community).

One of the core missions of the Good Docs Project is to provide high-quality documentation templates to open source software projects and beyond. However, we also engage in many other similar initiatives around docs advocacy, docs education, and docs tooling. We value all contributions to the Good Docs Project initiatives, including templates and our other initiatives. The [Join the community](#join-the-community) section of this guide explains how to get involved in those other related initiatives and provides links for more information.


## Table of contents

[TOC]

## Before you start

Before starting, ensure you are familiar with the Good Docs Project’s goals, key concepts, and workflows. It might also possibly help to learn more about our project's personas. For more information, see [About the Good Docs Project](https://thegooddocsproject.dev/about/).

We expect all members of our project to be nice to each other and to follow our [Code of Conduct](https://thegooddocsproject.dev/code-of-conduct/) when interacting with other members of the Good Docs Project.


### Time commitment

Most of our work is done by participating in one of our working groups, which generally meet weekly or bi-weekly for 1 hour a week. To effectively contribute templates to a project, all template writers are strongly encouraged to join one of the template writing working groups, especially if it is your first time contributing. Check our [community calendar](https://thegooddocsproject.dev/community/#calendar) or ask a member of our community for meeting times.

Working at a pace of 1-2 hours a week, most template projects take 4-9 months to complete. Keep in mind that we’ll take what you can give. You and your family come first, then work, then volunteering. So, if something in your life prevents you from working on your project, that's okay. Try to let your working group leader know if you won't be able to continue working for a space of time.


### Template roles and resources

As you work on contributing templates to our project, various resources and members of our community are available to help you along the process. These include:

- **Templateers** - Any individual who contributes to the Good Docs Project (including you!).
- **The template working group leads** - These templateers oversee our overall template development process as a project manager and provide assistance to contributors working on templates. The working group leads also usually review and approve merge requests submitted to the templates repository.
- **Template mentors** - This group of experienced templateers lead template writing working groups where you can receive guidance and mentorship while working on your template.
- **Template peers** - Your fellow templateer peers are available to review templates during the research and community feedback phases. They include members of your template writing working group, but also members from the larger Good Docs Project community.
- **Template editors** - This group is in charge of making sure our templates follow standard conventions and model high quality writing. They maintain our style guide, make style guide decisions, notify the community about style guide changes, and help to ensure compliance with our style policies.


### Template issues and boards

All the templates that are actively being worked on or which could be worked on have a corresponding issue in the templates repository. Use the issue list or the kanban board to find a template to work on and track your template’s progress as it moves throughout the template writing phases.

- [Template issues list](https://gitlab.com/tgdp/templates/-/issues)
- [Templates in progress kanban board](https://gitlab.com/tgdp/templates/-/boards/4801048)
- [Available templates kanban board](https://gitlab.com/tgdp/templates/-/boards/4896257?assignee_id=None)



### Required deliverables

See [Template Deliverables](template-deliverables.md) for more detailed information about each template deliverable.

Currently, for a template set to be considered complete, each template set should have these documentation deliverables:

<table>
  <tr>
    <th>Deliverable</th>
    <th>Description and purpose</th>
    <th>Required?</th>
  </tr>
  <tr>
    <td>Template file</td>
    <td>The template file is the raw template for the type of document you are creating. It provides a rough outline of the suggested content and a few embedded writing tips for how to fill in the different sections of the template.</td>
    <td>Required</td>
  </tr>
  <tr>
    <td>Template guide</td>
    <td>This guide provides a deeper explanation of how to fill in the template. It provides a lightweight introduction to the purpose of this documentation and explains how to fill in each section of the document. Any information that is essential to filling out the template should be noted in this guide.</td>
    <td>Required</td>
  </tr>
  <tr>
    <td>Deep dive</td>
    <td>This optional guide is a supplementary guide that can provide additional helpful information to template users such as key research, deeper theories, brainstorming, or pre-writing steps that are too comprehensive or lengthy to be included in the template guide. What is included in this guide may be unique to each template.</td>
    <td>Optional</td>
  </tr>
  <tr>
    <td>Template example</td>
    <td>After a template project is complete, our Chronologue working group will create an example of the template. While creating the example, the Chronologue group will test whether your template is user-friendly and can be used in a real documentation project. If you're still involved in the community during this phase, these team members might reach out to you for feedback or to collaborate on possible template revisions.</td>
    <td>Required, but occurs after the template writing process</td>
  </tr>
</table>


## Overview of the template writing phases
Contributing a template project to our repository has five phases, as summarized in this table:

<table>
  <tr>
    <th>Phase</th>
    <th>Your goals</th>
    <th>Resources to help you</th>
  </tr>
  <tr>
    <td>1 - Join the community</td>
    <td><ul>
          <li>Join our project’s communication channels.</li>
          <li>Decide which initiative you’d like to work on based on your interests and experience.</li>
        </ul>
    </td>
    <td><ul>
          <li>The Good Docs Project community managers</li>
          <li>Working groups</li>
        </ul>
    </td>
  </tr>
  <tr>
    <td>2 - Adopt a template</td>
    <td><ul>
          <li>Join a template writing working group.</li>
          <li>Work with a template working group lead and your group to decide which template you’ll work on.</li>
          <li>Assign yourself to the corresponding issue for that template. Note that this requires a GitLab account: https://gitlab.com/users/sign_up .</li>
        </ul>
    </td>
    <td><ul>
          <li>The issues board on the templates repo</li>
          <li>Template working group leads</li>
          <li>Template working group</li>
        </ul>
    </td>
  </tr>
  <tr>
    <td>3 - Research and draft</td>
    <td><ul>
          <li>Research examples and best practices for the type of template you are working on.</li>
          <li>Collaborate and get early feedback on your research from your template working group lead and/or other templateers as part of a template writing working group.</li>
          <li>Create drafts of the template set deliverables in Google Docs or your preferred tool.</li>
        </ul>
    </td>
    <td><ul>
          <li>Template working group leads</li>
          <li>Templates working group</li>
        </ul>
    </td>
  </tr>
  <tr>
    <td>4 - Get feedback on drafts from the community</td>
    <td><ul>
          <li>Revise and refine the drafts of your deliverables. Expect to receive feedback from at least three community reviewers.</li>
          <li>Optional: Revise and refine your draft with subject matter experts and individuals beyond our community (such as Write the Docs or subject matter experts).</li>
          <li>After making revisions, work with your template working group to determine when your draft is ready for the next phase.</li>
        </ul>
    </td>
    <td><ul>
          <li>Template working group leads</li>
          <li>Templates working group</li>
          <li>Subject matter experts and members of other technical writing communities</li>
        </ul>
    </td>
  </tr>
  <tr>
    <td>5 - Submit a merge request</td>
    <td><ul>
          <li>If needed, convert drafts from Google Docs or your preferred tool to Markdown.</li>
          <li>Open a merge request. NOTE: If you are unfamiliar with Git and GitLab, your template working group lead can recommend you for our Git Training workshop.</li>
          <li>Revise documents based on requests from merge request reviewers.</li>
        </ul>
    </td>
    <td><ul>
          <li>Template working group leads</li>
          <li>Git Training workshop</li>
        </ul>
    </td>
  </tr>
  <tr>
    <td>6 - Hand off to the Chronologue team for user testing</td>
    <td><ul>
          <li>After completing the previous phase, your template will officially be part of the Good Docs Project and will be available to our users. Yay!</li>
          <li>After a template project is complete, our Chronologue working group will create an example of the template. While creating the example, the Chronologue group will test whether your template is user-friendly and can be used in a real documentation project. If you're still involved in the community during this phase, these team members might reach out to you for feedback or to collaborate on possible template revisions.</li>
          <li>As additional users try your template out in the wild, they may report usability issues or provide feedback for improvements to the template.</li>
          <li>Either the Chronologue writer, the original template author, or another templateer will evaluate feedback and incorporate it into future versions of the template. If extensive revisions are needed, the template may need to go through the same previous template writing phases again.</li>
        </ul>
    </td>
    <td><ul>
          <li>Template mentor</li>
          <li>Templates coordinator</li>
        </ul>
    </td>
  </tr>
</table>

Each phase is explained in more depth in the remaining sections.


## Join the community

To become a full-fledged templateer, you’ll want to join our communication channels so that you can talk to us:

- **Slack** - Our [Slack workspace](https://thegooddocs.slack.com/) is one of the primary means of communicating with members of our project. After joining our workspace, join the `#welcome` channel to introduce yourself to the welcoming committee. Consider also joining these Slack channels if you plan to work on a template:
  - `#templates`
  - `#welcome`
  - One of the community-docs channels (based on your preferred time zone and meeting times)
- **Working groups** - Our project is organized into several different working groups that meet on a regular basis to work on the project’s key initiatives. One of the best ways to get started with our project is to join and meet with one of our working groups. See [The Good Docs Project Working Groups](https://thegooddocsproject.dev/working-group/) for a list of our current active groups. NOTE: If you plan to contribute to our project by writing templates, you will be required to join one of the template working groups.
- **Weekly meetings** - The project leaders hold weekly meetings to discuss project-level decisions. Feel free to join one of these meetings to introduce yourself to the project leaders and discover next steps for getting involved in the project. See the [community calendar](https://thegooddocsproject.dev/community/#calendar) for meeting times.

As you begin to join our project, remember that this is a project composed entirely of volunteers. We love to welcome new members, but want to be careful not to burn out our core project contributors. This level of mindfulness helps us ensure that we retain our project’s capacity to produce high-quality work. As such, we ask that you respect the time of our project maintainers and contributors.
(And expect us to respect your time in return!)

We expect all members of our project to be nice to each other and to follow our [Code of Conduct](https://thegooddocsproject.dev/code-of-conduct/) when interacting with other members of the Good Docs Project.


## Adopt a template

In this phase, you will decide which template project you will work on and adopt that template.

Be aware that:
- Each template project is represented by a corresponding issue in the templates repository.
- You will use this issue to communicate the status of your template project as it moves through the different phases of the template writing process.
- The Good Docs Project managers use a kanban board that shows all the issues for the current template projects. This tool allows the templateers and project stakeholders to track the overall progress of each template and assist templateers whose progress is blocked.

Links:
- [Template issues list](https://gitlab.com/tgdp/templates/-/issues)
- [Templates in progress kanban board](https://gitlab.com/tgdp/templates/-/boards/4801048)
- [Available templates kanban board](https://gitlab.com/tgdp/templates/-/boards/4896257?assignee_id=None)

Note that this requires a GitLab account: https://gitlab.com/users/sign_up 

To adopt a template:

1. Scroll through the list of available template issues and see if one interests you and/or matches your skill set. Alternatively, if you have an idea for a template project that does not yet have an issue, and you have the support of a template working group lead, you can create a new issue for your template project.

2. Assign yourself to the issue. Note that this requires a [GitLab account](https://gitlab.com/users/sign_up). See [Assignee](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#assignee) in the GitLab docs for more information.

3. Notify your template working group lead that you have adopted a template project.

If you claim a template and later realize that you don’t have the time or energy to complete the template project, please your working group lead know.


### Guidelines for choosing a template

Keep in mind that you don’t need to be an expert on any template type before you adopt it. If you are interested in writing a particular template and are excited enough to do some research to learn more about it, that's all the preparation you need and we welcome your efforts. Even if you don't have a ton of experience writing a particular type of document, you can still write a high-quality template that will be useful to others. With commitment, research, guided mentorship, and feedback from our community, you can and will create something that will have value to others!

With that in mind, when deciding which template project is right for you, scroll through the list of template issues and ask yourself the following questions:

- Does something about this type of document or template intrigue you, spark your curiosity, and make you excited to research and learn more?
- Do you wish you knew how to create the best version of this type of document? Are you energized by the idea of researching best practices or gleaning insights from subject matter experts about this type of document?
- Do you have experience writing for this type of document which you would like to share? Would having a high quality version of this type of template make your life easier at your workplace or for your open source project?
- Do you feel like there is a strong need for improved versions of this type of document in the world? Do you see lots of bad examples of this document that frustrate you?
- Has the Good Docs Project labeled this type of template as a high priority for our project? (Keep in mind that you can work on any template that you feel enthusiastic about, regardless of priority. That being said, we welcome work on our high priority templates.)

If you answered yes to more than one of these questions about a specific type of template, that might be the right template for you to work on!


## Research and draft the template

In this phase, you will research examples and identify best practices for the type of template you’re working on. At the end of this stage, our project recommends producing your working draft of the template project deliverables in a Google Doc. The reasons we recommend putting your draft in a Google Doc are because it:

- Is free (no license required) and easy to use.
- Is relatively easy to share with collaborators both inside and outside of the Good Docs Project (such as with the Write the Docs community).
- Allows collaborators to give feedback and advice in the form of comments.
- Tracks comment history for later reference.
- Has version control capabilities.

That being said, you are not required to work in Google Docs. You can work in your preferred tool (such as Markdown, Microsoft Word, or Gitbooks). However, our experience has shown that Google Docs is the easiest tool for collaborating with other Good Docs Project contributors in the early phases of doc development.


### Recommended research strategies

In our experience, successful templateers usually research their template by:

- **Looking at lots of examples.** Start by searching for examples of that type of document they want to create a template for. The more examples you can look at, the better. While it’s better to review good examples of that type of document, there is actually a lot of value in reviewing bad examples too. Consider keeping a spreadsheet to track which examples you used, what elements each one had in common, and what you thought was effective or ineffective.
- **Searching for guides, books, blog posts, conference presentations, or videos about best practices.** Search the Internet to find advice, tips, or expert research about how to create that type of document. Consider posting in a forum for resource ideas. For example, asking for helpful guides or insights on a community forum like the Write the Docs Slack workspace could be beneficial. Be mindful of, and respect copyright terms of source material. Do not plagiarize and offer attribution where appropriate.
- **Reaching out to experts.** When you find people you admire, who have researched your topic already, try reaching out to them. They often have a “how to contact me” webpage. Ask if they’d be okay with their material being used. (They might need to republish under a different copyright.) Invite them to participate in the template working group. They might even be prepared to lead it. If you feel shy about reaching out yourself, your template mentor or senior Good Docs Project member might offer to help.
- **Collaborating with others in a working group.** Work with your template writing working groups to discuss research ideas and findings.


## Get feedback on drafts from the community

In this phase, you’ll begin to share your drafts with community reviewers and invite feedback. Optionally, you might also consider sharing it beyond our community with other technical writing communities such as Write the Docs or beyond. The feedback and revision phase is arguably the most crucial and important phase in the template writing process, so your template project might spend the bulk of its time in this phase.

To share your Google Docs drafts:

1. Inside the draft, click the **Share** button and change the **Get Link** settings to: **Anyone on the internet with this link can create comments.**

2. Copy the link to your Google Doc drafts into the issue that corresponds with your template in the templates repository.

3. Notify your working group lead, who will help you get reviews for your draft from the community.

Your template working group lead will help you find reviewers. Typically three or more community reviewers will provide a detailed review of your material. When you’ve received sufficient community input and incorporated suggestions into your draft, you will collaborate with a templates coordinator to determine that your draft is ready to move to the next phase.

> :triangular_flag_on_post: **NOTE: You can only move to the next phase (submitting a merge request) after the templates working group lead has approved your draft to move on.**


### Accepting feedback from others

It’s normal to feel nervous about sharing your drafts, especially if you’re a new writer or if you don’t feel as confident in your subject matter knowledge yet. But your draft can only become the best template it can be if you invite and incorporate high quality feedback into your drafts. Successfully accepting advice on a draft is a key element that distinguishes expert writers from novice writers.

Sharing your work with reviewers:

- Allows you to see your draft with fresh eyes the way a new user would see it.
- Can make you aware of key insights or perspectives that you hadn’t yet considered.
- Can help you identify which parts of your draft need more careful thought, attention, and revision.

As you receive feedback, try to give each comment the benefit of the doubt and seriously consider it. Sometimes new writers are tempted to react defensively to feedback on their work, but remember that your reviewers have the same goals that you have: to produce a high quality template! But also keep in mind that you don’t need to accept every suggestion. If you can make a good argument not to adopt a suggestion, that is important to consider as well.

One other thing that might help you get more high quality reviews is to clearly indicate what kind of feedback you’re looking for, based on areas of the draft you think need some improvement. Do you need:

- Global-level feedback, which includes advice on the big picture, general content, tone, clarity, and overall organization or flow of the document?
- Local-level feedback, which includes wordsmithing paragraphs or sentences and polishing up the draft for final revision?

Remember to be positive and show appreciation when people take time to review your drafts. Providing feedback takes time and energy. Treat each piece of feedback as a gift (even feedback that you possibly choose to disregard). Happy editing!


## Submit a merge request

The purpose of this phase is to ensure your template project meets the standards of the Good Docs Project and is ready for public distribution. In this phase, you’ll convert your template documents into Markdown and open a merge request in the `templates` repository on GitLab.

If you are not comfortable working in Markdown, Git, or GitLab, ask your working group lead if you can participate in the next Git Training workshop.

Once you’ve submitted a merge request, your template working group lead will review your template and/or work with other working group leads to review your template. These reviewers will check the template to ensure it meets the project’s formatting and quality guidelines as outlined in our template merge request checklist. This review is intended to be a final quality check to determine whether the template is ready to be officially included in the Good Docs Project. Once the template has at least one approval from a template working group lead, it can be merged into the final project.


## Hand off to the Chronologue team for user testing

After your merge request is merged in, your template will officially be part of the Good Docs Project. Yay!

:sparkles: :mega: :raised_hands:

Great documents are never fully done and there is always room for improvement. After a template project is complete, our Chronologue working group will create an example of the template. While creating the example, the Chronologue group will test whether your template is user-friendly and can be used in a real documentation project. It's possible that the Chronologue team will identify major or minor revisions that need to be made to the template. 

If you're still involved in the community during this phase, these team members might reach out to you for feedback or to collaborate on possible template revisions. Either the Chronologue writer, the original template author, or another templateer will make any necessary revisions of templates of the template. If extensive revisions are needed, the template may need to go through the same previous template writing phases again.

After a Chronologue example is complete and users begin to try your template in their own documentation projects, they may report usability issues or provide feedback for improvements to the template. If our project receives this feedback and you’re still around to work on your original template, we encourage you to carefully review this feedback and incorporate these revisions into future versions. If you are not around to continue working on your original template or if you are too busy, we can find a different templateer to respond to user feedback on your behalf.

If a templateer determines that a new version of a template is warranted, they will take the template through the same contributing process starting from the beginning.
