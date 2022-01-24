# {Doctype} theory

This {doctype}-theory document provides reasoning, justifications, and links to research relevant to {doctype} documentation. It aims to empower authors to "think like a tech writer and expert in {doctype} documents" and make decisions backed by best practices.

**Version:** {MAJOR.MINOR.PATCH}

**Last updated:** {Month DD, YYYY}


## User stories

When writing, it is important to understand who you are writing for, and ensure that you provide just the right amount of information to address their needs. The following user stories should help you achieve that.

A {doctype} document aims to address the following user stories:

* As a {user persona}, I want to {achieve a specific goal}, so that I can {achieve a larger business objective}.
* ...

For a description of common personas, refer to 
_{TBD: We should link to a page we are yet to write helping people pick personas.}_

## Nature of content

{Doctype} documentation is {Discuss the nature of the content for this doctype:

* Discuss what format will best express the nature of the content. For example, text only, or multi-media options such as diagrams, screenshots or video.
* Discuss how the format you choose will impact maintenance. This can include human work-hours, as well as ongoing processes and infrastructure requirements.
* Reference your style guide, which should have recommended guidelines for using multimedia, such as image size and video length.
* For content with numerous items or steps, consider "chunking" content into sub-sections of 5-10 steps. It makes the information easier to read and remember, and gives the reader a sense of accomplishment after each chunk is completed. Chunking is recommended by major companies, such as Microsoft in its [writing style guide](https://docs.microsoft.com/en-us/style-guide/procedures-instructions/writing-step-by-step-instructions#complex-procedures), and from the Nielsen Norman Group's [research on chunking and usability](https://www.nngroup.com/articles/short-term-memory-and-web-usability/).

}

## Priorities for each quality criteria

* Each `doctype` addresses different use cases. It targets different user personas, with different needs.
* As such, there are different weightings applied to quality characteristics for each `doctype`. Reference documentation needs to comprehensively address all the features in the latest version, but can tolerate lower quality writing. Tutorials likely need only cover a sample of use cases, for an older version of the software, but there is a greater need for writing quality.
* The following table is used to help prioritize your time when writing for this {doctype} doctype.


|Quality criteria                                        |Priority to address                                                                |
|:-------------------------------------------------------|:----------------------------------------------------------------------------------|
|Currency: Alignment with the latest version of software.|{Select one of: Must, Should, Nice to have (May), Not Applicable (N/A), Should not}|
|Currency: Alignment with a specified version of software.|                                                                                  |
|Comprehensive: Covers every feature and use case.       |                                                                                   |
|Well written: Unambiguous.                              |                                                                                   |
|Well written: Concise, high information density.        |                                                                                   |
|Well written: Aligns with writing style guide.          |                                                                                   |
|Well written: Engaging, entertaining, draws the reader in.|                                                                                 |
|Audience: Target a specific persona and user story. Simplifies documentation by assuming prerequisite knowledge of the audience.|           |
|Audience: Targets a broad international, multicultural audience. Avoids slang, colloquialisms, pop cultural references or local references.||
|Audience: Considers a non-English speaking audience. Uses simple English.|                                                                  |
|Audience: Consider accessibility and disability in audiences.|                                                                              |
|Audience: Consider diversity and inclusiveness in language chosen.|                                                                         |
|Maintainability: Written to be easily translated.        |                                                                                  |
|Maintainability: Uses timeless language with reduced need to update over time.|                                                             |
|Maintainability: Has established processes for auditing and updating content.|                                                              |
|Maintainability: Has a healthy, engaged community of contributors.|                                                                         |

Note: The terms "Must”, "Should”, and "May” should be interpreted as per [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

_TBD: The quality criteria list requires review and refinement._
* _Further reading: [Tom Johnson's article on Measuring Doc Quality](https://idratherbewriting.com/learnapidoc/docapis_measuring_impact.html)._
* _Further reading: Daniel Beck's Doc Audit work. TBD: Get the public link for this._

## Implementation strategy

{Tip:

* This section is optional.
* In some cases there may be tips you can provide on how to create a specific `doctype`.

}

## Business case

{Tip:

* In this section, discuss strategies to calculate the cost of implementing this `doctype`. This may just be to reference the development strategy and maintenance strategy above.
* Then suggest business goals and reasons why this doctype would help address these goals. Business goals might be:
    * Increased developer efficiency.
    * Faster onboarding for users and/or developers.
    * Reduced support costs.
* Consider the case where the docs are only partially maintained. Would it be better to have no documentation than incorrect or partially maintained documentation?

}

### When to include {doctype} docs?

{Tip:

* Add a summarized list of reasons for writing the `doctype`, based on the business case above. 

}

You should write {doctype} docs when:

* {Reason 1.}
* {Reason 2.}

### When wouldn’t you include {doctype} docs?

{Tip:

* Add a summarized list of reasons for not including the `doctype`, based on the business case above. 

}

Don't write {doctype} docs if:

* {Reason 1.}
* {Reason 2.}

## Customization

{Tip:

* There are often multiple approaches to consider when implementing a `doctype`.
* In this section you should discuss different approaches that can be applied to this `doctype`, including logic and recommendations to help a docset owner select the best strategy for them.
* Often there would be a light and more comprehensive version of this template. Immature projects may only have the capacity to maintain the light version. You should discuss how a project might mature their docs from light to comprehensive versions.

_{TBD: Add further guidance and sample text here.}_

_{TBD: We are encouraging docset owners to branch a template and then customize. This branched version now won't track latest updates to The Good Docs Project templates. A more sustainable approach would be to have an accompanying configuration file which supports section inclusion logic and variables. A future toolchain would need to be set up before we could introduce accompanying config files.}_

* There are multiple approaches which can be taken to customize this template. These may depend upon:
    * The maturity of your project.
    * The size, interest, and skillsets of your contributor community.
    * The documentation goals you have for the project.
* This section discusses approaches you may take to customize this template to your project.

{Tip:

* {Add customization advice here. …}

}

## Maintenance strategy

See also the maintenance strategy section of the `doctype_guide`.

{Tip:

* In this section, you should recommend strategies for maintaining `doctype` documentation. This could include:
* Automated documentation generation from code.
* Automated reports which highlight:
    * When documentation is out of date with software.
    * When documentation hasn’t been reviewed for a while.
* Integrating documentation checklists into software deployment, build, and test processes.
* This section can remain empty if there are no extra recommendations to add beyond general guidance in the `doctype_guide`.

}

## Backing research and further reading

{Tip:

It isn’t sufficient to simply define best practices for a `doctype`. You need to provide compelling evidence as to why this is the best approach. If there isn't any research, then say so, provide your own recommendations, and explain why you think they are the best approach.

"Do the hard work to make it simple." [UK Open Government Design Principle](https://www.gov.uk/guidance/government-design-principles#do-the-hard-work-to-make-it-simple)

This section should summarize competing approaches and explain why you took the chosen approach.
* It might also suggest situations where a docset owner would select a different approach.
* Authoritative sources should be provided to justify recommendations.
* If this section becomes more than a page long, consider extracting out into a separate research paper and then reference the paper.

}
