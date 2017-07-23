# How to share code for review and getting help (online)

## Motivation

This document aims to provide some general guidelines for sharing source code
which exhibits an undesirable behaviour, in order for it to be reviewed and
corrected on online forums.

## Guidelines

### Short, Self Contained, Correct, Example

First of all, your code should exhibit the problem you are having and should be a ''self-contained'', and ''reproducing'' example (see [“The Short, Self Contained, Correct, Example”](http://sscce.org/) page).

#### Reducing the code

If the code is too large, please consider reducing it to a more minimal example that still exhibits the problem (see the [bisection method](https://en.wikipedia.org/wiki/Bisection_method) ). Namely, you can try gradually removing parts of
the code while each time ascertaining that the problem can still be reproduced
until you have reached the shortest possible code. Often, doing that will be
enough to find the culprit reason for the failure and to fix it.

### Show the Whole Code

Please don't share non-runnable pieces and fragments of your code, see [“Show Us The Whole Code”](http://shadow.cat/blog/matt-s-trout/show-us-the-whole-code/) .


### How to upload the code

<ol>

<li>

<p>

If you are coding a web page, you can try sharing your code using [jsfiddle](http://jsfiddle.net/) .

</p>

</li>

<li>

<p>

Otherwise, if your code is self-contained in one file, you can use a paste site such as [ideone](http://ideone.com/) or [paste.debian.net](https://paste.debian.net/). If you are using an IRC chatroom, don't floodpaste the code to the channel because this is slower and more annoying than using a paste site and may get you kicked or devoiced out of the channel.

</p>

<p>

Some other types of forums allow you to quote a single and self-contained codebase using a notation such as [“pre” tags](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/pre), or using indentation or triple-backquotes, so it may be an option there depending on the forum’s policy.

</p>

</li>

<li>

<p>

If you have more than one file in the project, then you should put it in a self-contained version control repository on a code sharing site such as [GitHub](http://github.com/) , [Bitbucket](http://bitbucket.org/) , or [GitLab](https://about.gitlab.com/) , so people can easily clone or checkout it.

</p>

</li>


</ol>

## Links

* [Freenode’s ##programming channel FAQ](https://github.com/shlomif/Freenode-programming-channel-FAQ/blob/master/FAQ.mdwn) - where this document originated from, and which may contain some other insights.

### Project Links

* [Canonical URL for the document](http://www.shlomifish.org/philosophy/computers/FILL_IN/) - on Shlomi Fish’s home site. That page should validate as XHTML 1.1.
* [GitHub repository](https://github.com/shlomif/how-to-share-code-for-review) - contains the Markdown sources, an issue tracker and more resources. Contributions are welcome.

## Licence

This document is Copyright by Shlomi Fish, 2017, and is available
under the
terms of <a rel="license"
href="http://creativecommons.org/licenses/by/4.0/">the Creative Commons
Attribution License 4.0 Unported</a> (or at your option any
later version of that licence).

For securing additional rights, please contact
<a href="http://www.shlomifish.org/me/contact-me/">Shlomi Fish</a>
and see <a href="http://www.shlomifish.org/meta/copyrights/">the
explicit requirements</a> that are being spelt from abiding by
that licence.
