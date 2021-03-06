---
title: Base Tutorial
layout: book
summary: A complete tutorial to use the OSGi enRoute tool chain
---

In this quick start we develop a little project that, surprise, surprise,  prints out "Hello world", and because it is OSGi based, we will also cover the "Goodbye World". 

This tutorial is light on the explanations because it focuses on introducing the overall architecture of enRoute, not the details. Over time this site will be filled with tutorials and documentation (or references to those) that will explain the minute details. This however, is about some big steps.

We will cover the whole chain, from creating a workspace all the way to continuous integration.

A disclaimer. This quick start is about learning to use OSGi enRoute, not about learning Java, Git, nor Eclipse. It is assumed that you have basic experience with these tools.

If you have any questions about this quick-start, please discuss them in the [forum][forum].

## Sections

<div>
<ol>

{% for t in site.tutorial_base %}<li><a href="{{t.url}}">{{t.title}}</a> – {{t.summary}}</li>
{% endfor %}

</ol>
</div>


## End

So, you've finished this tutorial! What's next?

Well, first, since we're still in beta, we'd love feedback. Our most favorite feedback is a pull request on the documentation. As an early user you must have run into some rough edges, outright stupidities, or you had a brilliant idea. Just go to the [OSGi enRoute][enroute-doc] repository on Github. Clone it in your own account, make your changes or additions, and send a pull request. We, and others like you, highly appreciate these kind of contributions.

After you've done this tutorial you should have a basic feeling of how to build an application with  OSGi enRoute. So the best way to continue learning is to build a small application based on these principles. Running into real problems is the best way to learn a technology. If you run into problems, use the [Forum][forum] to ask questions and get answers.

And watch this space, we will expand this site with hundreds data sheets of services you can find on the net. These data-sheets will show you how to use this service in your application with real examples. 

  

[forum]: /forum.html
[enroute-doc]: https://github.com/osgi/osgi.enroute/tree/master/osgi.enroute.doc

