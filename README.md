| <img src="https://gist.githubusercontent.com/sonylnagale/062b13463394c162fe4fb7227b1a0675/raw/c0798c35ab0315db9611c66b85b1250f5f38011c/skills-gap.png" width="200px"/> | <h1>Instructional Designer Assessment</h1> |
|---|---|


# Introduction

Welcome! Your HTML5/CSS3 subject matter expert (SME) has delivered to you this wealth of information:

> Hello! Here is my material for the second lesson, showing how to tie HTML and CSS together. I have a braindump here, so I'm hoping the information is enough to craft into a lesson.

> Many thanks!

> Pat

Your task is to take Pat's material, as shown below, and organize it into a lesson to teach the marriage of HTML and CSS.

# Preconditions

1. The students have already been exposed to instruction on the basics of HTML.
1. The next task for the students is to learn how to write their own CSS and tie it with the existing HTML they created in Lesson 1 and weave a coherent narrative for this section.

# Deliverables

At the end of this exercise, you will deliver either by GitHub repository or GitHub Gist a lesson plan for this material. The goal is for the lesson to be 30 minutes, but if you feel additional time is necessary, please feel free to outline your thoughts.

This lesson plan will include:

1. A block-by-block breakdown of instruction, _e.g._ 0-5mins Topic x ; 5-15mins Topic y.
1. Clear headers and content material for an instructor to follow. This material will be written like a script, but will not be intended to be read verbatim. Use your judgement here on how to present this material for a live teaching scenario.
1. Use the best practices of [Markdown](https://www.markdownguide.org/cheat-sheet/) when writing this plan.
1. Consider rewriting parts of the SME's work into your own words. It's possible Pat may have copied segments directly from other resources. For the purposes of this exercise, use your judgement on how to rewrite and rephrase the content because parts of the content are directly lifted from other online resources. It's not important to call out Pat's plagiarism, but if you can see what parts have been lifted from other resources, it's worth noting how you would address and mitigate these concerns.

# Material

## HTML5 Boilerplate

As we learned, we can find a standard HTML5 template for oursleves to eliminate the need to start from scratch each time. As you learn HTML5 and add new techniques to your toolbox, you’re likely going to want to build yourself a boilerplate from which you can begin all your HTML5-based projects. We encourage this, and you may also consider using one of the many online sources that provide a basic HTML5 starting point for you.

Let’s start simple, with a bare-bones HTML5 page:

```HTML
<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8">

  <title>The HTML5 Herald</title>
  <meta name="description" content="The HTML5 Herald">
  <meta name="author" content="SitePoint">

  <link rel="stylesheet" href="styles.css">

</head>

<body>
  <h1>Welcoime!</h1>
</body>
</html>
```

### Doctype

It's simple, and to the point. The doctype can be written in uppercase, lowercase, or mixed case. You’ll notice that the “5” is conspicuously missing from the declaration. Although the current iteration of web markup is known as “HTML5,” it really is just an evolution of previous HTML standards — and future specifications will simply be a development of what we have today.

Because browsers are usually required to support all existing content on the Web, there’s no reliance on the doctype to tell them which features should be supported in a given document. In other words, the doctype alone is not going to make your pages HTML5-compliant. It’s really up to the browser to do this. In fact, you can use one of those two older doctypes with new HTML5 elements on the page and the page will render the same as it would if you used the new doctype.

### HTML Element

Next up in any HTML document is the html element, which has not changed significantly with HTML5. In our example, we’ve included the lang attribute with a value of en, which specifies that the document is in English. In XHTML-based syntax, you’d be required to include an xmlns attribute. In HTML5, this is no longer needed, and even the lang attribute is unnecessary for the document to validate or function correctly.

## CSS
