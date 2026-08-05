---
title: Some Grammar Issues
description: Common mistakes and style issues to avoid when writing a thesis.
---

# {% include icon.html icon="fa-solid fa-spell-check" %}Some Grammar Issues

Below some common mistakes and style issues are listed people often forget or overlook when writing their thesis. **Comments and further hints are welcome!**

**On this page**

1. [Definitions and other environments](#definitions-and-other-environments)
2. [Citations](#citations)
3. [Upper/lower case](#upperlower-case)
4. [Commas](#commas)
5. [And more stuff...](#and-more-stuff)

{% include section.html %}

## Definitions and other environments {#definitions-and-other-environments}

Please use the LaTeX [theorem package](https://ctan.org/pkg/theorem?lang=en) (already included in the thesis template). Definitions, theorems, examples, and tables are to be **numbered by chapter**, not by section or subsection. Ideally, definitions should also have a name, for example, "*Definition 3.1 (Graph). A graph is…*."

For presenting **algorithms**, use the LaTeX [algorithm2e package](https://ctan.org/pkg/algorithm2e?lang=en).

Figures are supposed to have a **caption** that explains the figure in sufficient depth.

{% include section.html %}

## Citations {#citations}

It is up to you to choose a good format and style for citations. Numbers are Ok, e.g., [2,4,7], but you can also use author names, e.g., [Mueller and Schultz, 2001]. Note that if a work has more than two authors, one typically refers to that work by saying, e.g., "*The work by Miller et al. [9] was the first that showed…*.", not just "*The work [9] showed…*". In case of less than three authors, one gives the names of the authors, e.g., "*Mueller and Schultz showed that this is the upper bound [3]*."

See also, for example, the [Dalhousie University guide on citing and referencing](https://dal.ca.libguides.com/c.php?g=257109&p=1716811).

{% include section.html %}

## Upper/lower case {#upperlower-case}

For the title of chapters and sections, one typically uses upper case for all first letters, except for "stop words", especially articles, not at the beginning of the title. Starting with subsection, lower case is used.

**Examples**:

*3. Outlier Detection Model*

*3.2 An Improved Benchmark Model for Outlier Detection*

*3.2.1 Handling uncertain data*

When referring to a chapter, section, figure and the like by number, upper case for the first letter is used.

**Examples**:

"*In Section 3.2, we present*…" or "…*is shown in Table 4.1*."
But: "*In the following section, we show*…" or "*In the table above, we have seen that*…"

{% include section.html %}

## Commas {#commas}

The following are just a few examples where people typically make mistakes.

Adverbs: after certain adverbs (e.g., however, in fact, therefore, nevertheless, moreover, furthermore, still, instead, too), a comma is used:

- "*This result, however, does not mean that*…"
- "*Therefore, in the following section, we will*…"

Other common cases where people often forget a comma:

- …, such as… (only a comma before)
- …, e.g., … (comma before **and** after)
- …, i.e., … (comma before **and** after)
- …, because…. (only a comma before)
- …, for example, … (comma before **and** after)
- …, for instance, … (comma before **and** after)

A very common error is not to place a comma when a nonrestrictive clause is used. A nonrestrictive clause is typically introduced by "which" and set off by commas.

**Example**:

"*The example above, which has also been used in the work by Schmidt [4], clearly shows that*…"

For a restrictive clause, which is typically introduced by "that", no commas are used (this is unlike the respective usage of commas in German orthography).

**Example**:

"*The object that is most similar to the given object is returned*". **NOT**: "*The object, which is most similar to the given object is returned*".

There are a few exceptions where a comma before *that* is used, e.g., "…, *that is*, …".

{% include section.html %}

## And more stuff... {#and-more-stuff}

- "*… in **the** form of…*"
- "*… on **the** basis that*…"

{% include section.html %}

[← Back to Theses]({{ '/teaching/theses/' | relative_url }})
