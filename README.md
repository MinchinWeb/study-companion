# study-companion

Create an evolving notebook of my scripture study.

## Pieces

- text of the scripture themselves. The Church doesn't appear to have a
  plaintext or even official HTML source available online, but they do have an
  [online HTML](https://www.lds.org/scriptures?lang=eng), as well as [PDF,
  Mobi, and ePub](https://www.lds.org/scriptures/formats?lang=eng) version
  available. There are also several un-official sources online and on GitHub.
  Note that there is [an updated 2013
  edition](https://www.lds.org/scriptures/press?lang=eng), with most of the
  changes in the study aids.
- the footnotes and study aids to the scriptures. If I start with the official
  edition of the scriptures, hopefully these will be included.
- Conference Talks and Engisn articles
- study manuals, Lectures on Faith
- additional, ad-hoc material such as my pariarchal blessing
- a French translation of the scriptures?
- the text of the Hymns?
- my anotations; I expect these to include:
  - boxing around words and verses
  - sidebar notes
  - additional cross references
  - semantic information (e.g. who is speaking)
- my study notes. These will be more full-form notes, often topical in nature.
  These my be developed to summerize personal thoughts, or lesson or talk
  notes.
- automatic portaits of the author next to quotes?
- include my Journal entries?
- index by scripture reference
- index by date
- index by topic

## Format

Do I do raw HTML, or start with wither a Markdown or ReST source material? or
LaTeX?

- HTML gives the most direct options, is self contained, but is hard to update
  formatting universaly.
- ReST is desgined to documentation generation, and so may be a great option,
  seperates most content from the actual display, but I can't find how to
  include inline (span) elements
- Markdown is simplier that ReST, but similiar on a base level, and so has many
  of it's advantages. The biggest advantage of Markdown over ReST is it's
  designed to fallback to HTML when needed. Plus, I've used it more.
- LaTeX is designed for print layout, and so it should be the ultimate in
  layout control. However, I've never used it, I'm probably targetting screne
  layout rather than print layout, and it's probably more verbose than ReST or
  Markdown.

Do I include my notes an additions directly on the source text, or do I include
these as seperate, applied on additions? Directly in the source text will make
them easier to render, especially without JavaScript, but will make it harder
to later dis-intangle my notes from the source material.

## Style

- [Sidenotes with CSS +
  JS](https://fransdejonge.com/wp-content/uploads/2010/01/sidenotes.html) --
  from 2010. I would like to avoid JS if possible, but on the whole it seems
  like a workable option.
- [Edward Tubble CSS](https://github.com/edwardtufte/tufte-css) and
  [demo](https://edwardtufte.github.io/tufte-css/) -- a CSS project that sets
  out to include sidenotes. Very clean looking, very well done side notes. In
  the absense of something markedly better, I'm inclines to use this. As a
  bonus, it seems to be based entirely on CSS (no JS). The included font seems
  very good to long passages of reading.
- [Game Programming
  Patterns](http://gameprogrammingpatterns.com/introduction.html) -- actually a
  book, but has a number of asides that seem to work well. The downside of this
  is that they don't seem to be tied to a specific place in the main body of
  the text. The design is responsive, and so on a small enough screen the
  sidenotes fall into boxes in the main flow the text. Full source is available
  on [GitHub](https://github.com/munificent/game-programming-patterns).
- [Responsive Sidenotes](https://johndjameson.com/blog/responsive-sidenotes/)
  -- uses CSS + JS to turn footnotes into sidenotes that appear beside the text
  on a wide enough screen. From 2014. Doesn't appear to provide an example, 
- [Coldstyle](https://www.myfonts.com/fonts/ephemera/coldstyle/) (font) -- a
  font that evokes an old time printer. I quite like it, but need to find a
  source for it.
  
## Samples, Code

- <https://www.bookofmormonorigins.com/> provides an example of how the text
  might be combined with notiations. It's built using Ruby + GitBook (I'd
  rather it was in Python) and the site's goal is to undermine the Book of
  Mormon, but it may be possible to crib some of the layout for our own purpose
  here.
- [Annotated Book of
  Mormon](https://annotatededitionofthebookofmormon.wordpress.com/2018/08/31/annotated-edition-of-the-book-of-mormon/)
  is a much more faith-promoting edition of the Book of Mormon, that aims to
  show the Book of Mormon is about Christ, and founded in Biblical prophecies.
  The book is a physical, hard cover book, and so not quite what I'm trying to
  do here, but it's comments on how the text has been re-formatted (see images
  in this repo) are probably in line with what I hope to accomplish.
- The [Iron Rod ASCII Scipture](http://ldsguy.tripod.com/Iron-rod/) has a copy
  of the Standard Works in text form.
- The HTML5 elemect `<aside>` seems to have been created for sidenotes  like I
  want to create (among other uses).
- [Custom Span Class Markdown
  Extension](https://github.com/exaroth/mdx_custom_span_class) extends Markdown
  to allow customized span classes to me added via Markdown
- [mdx include](https://github.com/neurobin/mdx_include) allows Markdown files
  to literally include other files. This may be helpful if I want to include
  pieces from seperate places.

## Further Reading

- [How to Study the Book of
  Mormon](https://www.lds.org/liahona/2011/10/how-to-study-the-book-of-mormon?lang=eng),
  by Elder D. Todd Christofferson, October 2011, *Liahona*
- [Ten Scripture Study
  Tools](https://www.lds.org/ensign/2010/09/ten-scripture-study-tools?lang=eng),
  September 2010, *Ensign*
- [Successful Scripture
  Study](https://www.lds.org/new-era/2012/01/successful-scripture-study?lang=eng),
  by Paul Vandenberghe, January 2012, *New Era*
- "[How do I Study Effectively and Prepare to
  Teach?](https://www.lds.org/manual/preach-my-gospel-a-guide-to-missionary-service/how-do-i-study-effectively-and-prepare-to-teach?lang=eng)",
  *Preach My Gospel*
- [Learn about My Study
  Notebook](https://www.lds.org/topics/scriptures-and-study/study-tools?lang=eng)
  (LDS.org)
