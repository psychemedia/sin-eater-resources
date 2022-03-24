# Appendix - Methodology

This book has been published using the [*Juptyer Book*](https://jupyterbook.org/intro.html) publishing framework.

The original texts were sourced predominantly from [`archive.org`](https://archive.org/), the [National Library of Wales](https://newspapers.library.wales/) and the [Hathi Trust](https://www.hathitrust.org/), all of which are free services. I also retrieved article text via a personal subscription to the [British Newspaper Archive](https://www.britishnewspaperarchive.co.uk/), and via a university subscription to the [*Times* online archive](https://www.gale.com/intl/c/the-times-digital-archive).

Source text excerpts were added to separate text files corresponding to each separate publication. Excerpts were added to the text files using the following convention:

```text
---
URL

Periodical / book title

Date

pNNN

Article Title

Article text.
---
```

The page number element (`p...`) was REQUIRED and served to separate the metadata (URL, title, date) from the text. The page number element could take various forms (for example, `p1`, `p10-15`, `p25-7`, `pxiv`, and if unknown / not relevant, `p?`). Individual records in a file were separated by `---` separators.

Records were loaded from the text files into a simple file based `sqlite` database. This provided a means for searching over the content, as well as republishing into skeleton book pages, (for example, a page containing all the articles published in a particular year and that contained a particular search term).

Several tools were developed to support ["fuzzy" searching](https://github.com/innovationOUtside/ouseful-sqlite-search-utils) where search terms almost, but don't quite, match terms included in a particular text, and tools for extracting fragments of text from each record (for example, extracting a particular paragraph or the text between start and end fragments).

The original text extracts can be found [here](https://github.com/psychemedia/sin-eater-resources/tree/main/resources). The "source code" documents processed by the Jupyter Book publishing tools to create the final book can be found [here](https://github.com/psychemedia/sin-eater-resources/tree/main/src).

As a related activity, I have also started developing full text searchable collections of articles from publications such as *Notes & Queries*, as described in [Story Notes – Technical Recipes](https://psychemedia.github.io/storynotes/).
