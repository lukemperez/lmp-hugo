---
date: "2016-05-24T17:16:58-05:00"
draft: false
title: "Hello Hugo"
tags: ["Hugo","HTML","Professional Development"]
slug: "hello-hugo"

---

I've hosted my webpage on [Squarespace][] since sometime in my second
year at UT Austin. After several years on the platform, I have nothing
but praise for the folks at [Squarespace][]: their reputation for
up-time, customer service, and all around technical bad-assery is well
deserved. If you're looking for a web-hosting/web-design company
wherein you can build a beautiful looking site *without* knowing *any*
HTML, CSS, or anything of that stuff---and I do mean it: without
any---then you cannot go wrong with a Squarespace site. But for me,
the time has come to say goodbye. 

<!--more-->

Why leave? If I've been so happy with Squarespace why make the fuss? I
could list a lot of reasons ranging from technical curiosity to summer
boredom or whatever. But really it comes down to handful of several
small but significant reasons: 

1. Blog as text files (esp. in Markdown)
3. Needs of modern academics (syntax highlighting, e.g.)
2. Cost of hosting (esp. for a graduate student)
4. Reproducability

## Blogging as public scholarship

I'd love to blog, er, post more "note" on teaching and learning (i.e.,
scholarship) but Squarespace requires new posts come from within the
browser. Sure, I could open Safari, go to my blog, click on new
content, write a new post, and push it to website with a simplicity
that only reinforces everything I've said above about why
non-programming professionals should take a serious look at the
platform. But Squarespace is a closed system. I couldn't even export
my content from their blog except into a Wordpress XML format. Which
raises an interesting question why they make support for Markdown in
the first place, since the whole point of Markdown, as I understand
it, is to have human readable plain text files that can be converted
into HTML when needed.

## Modern Academic 

Related to the first item is the need to integrate other tools of
modern researchers. Whether it is linking to a [GitHub][] repo or
conceptualizing blog posts as markdown files, working with a variety
of open source tools have become every more integrated into the
workflow of good scholarship. And although Squarespace can do some of
those things, it is now much easier for me to work in an ecosystem of
open, rather than closed systems. 

But I need a few things that are not easy to do on their blogging
module. First, as I begin to use R, Python, and other such programming
tools, I need a way to work on a file in Markdown using code blocks to
show my work and then easily convert that [plain-text][] file into
HTML, PDF, or LaTeX as my needs require. Such a workflow is possible
using MS Word, Squarespace, and other tools, but they are not the ones
I use. (I've not **installed** Microsoft Word on any computer I've
owned since 2009 or so.) 

## Costs of hosting 

Let's face it, graduate students make little to nothing. Every dollar
counts. When I started graduate school, I saw paying for my domain
name as a *sine qua non* of a good online presence. But I thought I
could "roll my own" and avoid paying a monthly hosting fee. I had
tinkered with using [Tumblr][] and [Wordpress][] but found mixed
results: namely, although the hosting was free and the url could be
custom, the layout was garbage for professional engagement. Eventually
I realized that quality can't faked. I needed a professional looking
site. Squarespace delivered. 

What's changed is that (a) my technical skills are much better than
they were a few years ago and (b) free static hosting on
[GitHub Pages][]. Now I can load an entire website to a [GitHub][] repo
(short for "repository" if you're not familiar), work a few settings,
and host a website though GitHub. The only catch is that the webpages
must be static rather than dynamic. The difference between the two is
not really a topic for today, but the short of it is that each has
their advantages. Every job needs different tools. 

Anyway, the ease of which I can manage my website without paying a
monthly fee was enough to finally push me to fill in a few gaps in my
knowledge of website development. 

## Replicate research, replicate blogging, replicate anything

I already mentioned this above:
[exporting on Squarespace](https://support.squarespace.com/hc/en-us/articles/205814028-Importing-and-exporting-content)
is not easy. I'm still not sure at the time of this drafting if I'll
even get my old blog over. Not that it matters since the friction to
getting a post online kept many a thought, good and bad, from seeing
the digital light of day. Still, it's worth repeating: modern scholars
must be able to reproduce their work. If I can't literally email a
plain text file of my blog post, journal article, or whatever to a
colleague for his or her approval, I'm not doing my job right. And
having multiple of versions of the same document in different formats
(HTML, .MD, etc.) only increases the likelihood that at some point one
file will become out of sync with the others being edited. Much easier
to simply version control with git, and push the same file, always in
sync, wherever it needs to go.


# Hello Hugo

So I finally bit the bullet and rebuilt the site as a static webpage
using [Hugo][] and some thoughts from
[Kieran Healy's post about using Hugo](https://kieranhealy.org/blog/archives/2014/02/24/powered-by-hugo/).
I read repeatedly that the process was fast, but I was still surprised
about how fast. Troubleshooting some terminal issues and downloading
Hugo took more time than it did to port my major content into Hugo's
structure. Now I have a mostly hand-built site that relies on me, my
GitHub, and some off the shelf tools. 

I'll spare you the overview of command to build a site. If you're
reading this and interested in trying it, I suggest reading the docs
at [Hugo][]. They will certainly be updated by the time that anyone
comes across this post anyway, so there's no need to date my work with
a workflow that will be largely out of date soon anyway. 

I do recommend, however, spending some time thinking about what themes
for webpage layouts you like best. A lot of folks mistaken conclude
they must build every last piece of code on their websites for it to
really look "right" or for them to say with confidence they have HTML
skills on their CVs and Resumes. But if you think of website themes, which are
built on CSS, as the webpage equivalent to a LaTeX documentclass or
`.sty` file, you'll realize there isn't much difference between the
two and, more importantly, no need to completely re-invent the wheel. 

 
So three cheers to Squarespace for getting me this far and three more
for [Hugo][] and [GitHub Pages][]. 

[Squarespace]: https://www.squarespace.com
[Wordpress]: https://wordpress.com/
[Tumblr]: https://www.tumblr.com/
[plain-text]: http://plain-text.co/
[GitHub]: https://github.com 
[GitHub Pages]: https://pages.github.com/
[Hugo]: gohugo.io
