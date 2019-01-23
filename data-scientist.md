# Interview - Data Scientist

Please process and analyze the following data and compose a data story for each of the following sections. A good balance of documented code, visualization, and clarifiying prose is desired.

## Semantic Scholar

[Semantic Scholar](https://www.semanticscholar.org/) is a search service for academic journal articles with a [search API](http://api.semanticscholar.org/).
Semantic Scholar made available a subset of the full corpus as its [Open Research Corpus](http://labs.semanticscholar.org/corpus/). 

**Requirements**:
1. Please use **ONLY** data from `s2-corpus-04.gz` and `s2-corpus-06.gz` of the Open Research Corpus.
1. You are allowed to use the Semantic Scholar search API to explore the data set and test ideas. However, your solutions cannot make any calls to the search API.
1. Please use any tools, software, or services you need to tell data stories. However, __CSET will not reimburse you on costs incurred for completing this project__.

### Author Graph

Construct an author graph up to "two-neighbors" starting with publication ID `22720d75b8c73afd3bf4917fd5512dcc11e19885` from the data subset that meets the requirements of this section. In other words, starting with an author of publication ID `22720d75b8c73afd3bf4917fd5512dcc11e19885`, this author graph should contain all of the author's co-authors as well as co-authors of each co-author.

What do you find interesting about this graph?

### Publication Graph

Construct a publication graph based on publications associated with the author graph above. This publication graph will be incomplete, because you are working with only the data subset that meets the requirements of this section. __You don't need to retrieve publication data beyond the subset you're required to work with__ .

What do you find interesting about this graph?

### Other Data Stories

Please feel free to implement one idea that tells an interesting data story using Semantic Scholar [Open Research Corpus](http://labs.semanticscholar.org/corpus/).

### Scalability

How scalable is your solution?

