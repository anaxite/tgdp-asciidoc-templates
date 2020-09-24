# The how-to article

## When do I need a how-to article?

How-to articles take the reader through a series of steps required to solve a specific, real-world problem.
Think of them as recipes for getting stuff done!

Sometimes you need to explain in detail how to do a specific task to a user.
You don't need to teach them concepts, but you do need to prescribe a set of sequential steps they must do in that order otherwise they won't be able to use a feature properly.

How-to articles are often confused with tutorials, which is not the case as they are _problem_-oriented not _learning_-oriented.

How-to articles are used by those who have experience with the product and need a specific question answered.
New users who want to solve a problem instantly can also benefit from how-to articles provided they are well-written and clearly state any prerequisite knowledge required to complete the how-to.

## Content of your how-to article

### About the "Overview" section

Summarize what the reader will get from reading the how-to articles.

Creating a good overview comes down to thinking about who is going to be using it:

* Are you writing only for end-users? For developers?
* Are you writing only for people who have a certain problem to solve?
* Is it intended for a particular industry?

### About the "Before you start" section

Have you ever got halfway through a how-to, only to discover you need to go and read other documentation before you can continue?
This section is designed to prevent this from happening in the first place.

Prerequisites can include other articles or information that needs to be read, or it can be technical dependencies such as requiring an internet connection.
Describe what the audience needs to know, or needs to have, before attempting this how-to.
By stating the requirements up-front, you prevent your audience from having a bad experience with your tutorial.
You can include links to procedures or information, or give your audience useful pointers about how to get whatever they need.
Here are some example "Before you Start" statements:

```
Make sure you meet the following prerequisites before following the steps:

* API credentials for the {company} v3.5 API. For more information about accessing your API credentials, see http://example.com/access_your_api_credentials.
* Access to the Postman application.
* An understanding about what a RESTful API is conceptually. For more information about RESTful APIs, see http://example.com/restful_apis. 
* (Optional) A development tool (IDE) that displays API responses formatted for readability.
* You need to have a list of favourites before you can manage them. For more information about favourites lists, see #Create_Favourites.

```

### About the "Step-by-step guide" sections

When you are explaining steps in a process, it can often be useful to include a screenshot for each part of the process. One of the many reasons for having a screenshot for every key step is that it helps someone who is evaluating the software to see how the software will work, even without having to install the software.

In the template-howto.adoc file, you'll notice a table in the "Step-by-step" section of the template. The table allows you to easily add a screenshot or callout next to each step.

You can also default to an ordered list structure (without screenshots) and use this in markdown with the help of HTML tables.


## How-to article examples

* **Example 1**.

* **Example 2**.
