# How to contribute

## Prerequisites

First of all fork [this repository](https://github.com/devRant-Community/Community-Programming-Book/)
and join this [discord server](https://discord.gg/TDut3Fq).

Throughout this guide, changes to files are to be made in your personal fork
and submitted for merging in the main repository through a pull-request (PR).

Taking the above mentioned points as granted the contributing guide begins now.

## Language already complete

Change/correct the files present in the directory /book/languages/[language]
where [language] is a placeholder for the language you want to change.

Please refer to the "After writing the chapter" section below and make
appropriate changes to the Summary.md file.

## Language not present

Create an issue on the main repository(mentioned in pre-requisites) with title
"Add Chapter on {Name of language}", assign this issue to yourself and add the
label "Enhancement". This helps in identifying that you are writing that
particular chapter.

Create a new sub-directory in /book/languages with the name of the language.

``` md
/book/languages/kotlin
```

In the sub-directory of the language add the files README.md and intro.md (Compulsory)

``` md
/book/languages/kotlin/
  README.md
  intro.md
```

README.md is a transition from one chapter to the next. An example is given.

``` md
# Welcome
> This chapter has been authored by <Your name goes here>

Well, next we will talk a bit about Kotlin, the new JVM language by Jetbrains.
Kotlin is less verbose than the original JVM language Java and is now one of
the main development languages of the Android Platfom. Let's get into it.
```

The intro.md should give a brief look at the language. Talk about the story of
language or tell from where it came. Look at the file intro.md present in the
root of the repository for inspiration.

The contents of the chapter are to be added as separate .md files for
each sub-chapter. An example sub-directory with sub-chapters is given.

``` md
/book/languages/kotlin/
  README.md
  intro.md
  <name_of_sub-chapter>.md
```

It is advised to divide the chapters into sub-chapters for better organization and
readability. If the author decides not to do so then the entire
contents of the chapter should be written in the intro.md file itself.

### After writing the chapter

After writing the chapter, an entry should be made in the Summary.md file similar
to the one given in the example below.

```md
* [<Name of language>](languages/assembly/README.md)

  * [Introduction](languages/assembly/intro.md)

  * [<Name of sub-chapter>](languages/assembly/<name of file>.md)
```

Note that Summary.md contains the order in which various chapters and the
sub-chapters appear in the final product, hence the entries should be made
appropriately. Also, note that various languages in the Summary.md file appear
in the order of creation/release.

For example the Summary.md file with two languages, Assembly and Python.

```md
* [Assembly](languages/assembly/README.md)
  * [sub-chapter](languages/assembly/{name of file}.md)
(leave a blank line)
* [Python](languages/python/README.md)
   * [sub-chapter 0](languages/python/{name of file}.md)
   (leave a blank line)
   * [sub-chapter 1](languages/python/{name of file}.md)

```

Feel free to ask for help regarding this aspect or anything in general.

You may also add your details in the credits.md in a similar way as other existing entries.

## Pull request and CI

After finishing your work, submit a pull request (PR) for merging your changes
into the base branch. Add  the editing team as reviewers. If the pull request
adds a new chapter, then add the label "new-chapter".

Also, close any previously opened issue(s) which are fulfilled by the
pull request.

Every pull request undergoes an automatic build process which automatically
generates the updated book. A set of rules on the format of the content is
defined all of which should be followed for the build to be successful.

These rules are given below.

* Lines should **NOT** have trailing whitespace.

* *List elements*, *fenced code blocks* and *headers* should be surrounded with **blank lines**.

```md
Some sentence.

* List element 1 or ## Header 1

* List element 2 or ## Header 2

Continuation.
```

* Each line should contain a maximum of **300** characters.

* Emphasis should **NOT** be used as a header.

* Use ``---`` for horizontal rules

* Two top-level headers should **NOT** be present.

```md
This is wrong format

# Heading 1

# Heading 2
```

* Always use ATX style headers

```md
Correct:
# ATX style H1


Wrong:
## Closed ATX style H2 ##

Setext style H1
===============
```

* Leave a space after hash on atx style header and after the "\*" symbol in list elements.

```md
Correct:
# Heading
* List element

Wrong:
#Heading
*List element
```

For everything else the standard rules, described [here](https://github.com/markdownlint/markdownlint/blob/master/docs/RULES.md), apply.

If there are any mistakes in format, the build will fail and the mistakes are
prompted by @SkayoBot to be corrected. An example prompt is given.

"------------------Prompt Begins------------

Checks failed - mdlint output:

```md
devRant-Community/Community-Programming-Book/book/languages/abc/conclusion.md
  9:3 no-space-in-links [MD039] Spaces inside link text "...aking of python-An interview ]"
devRant-Community/Community-Programming-Book/book/languages/abc/disadvantages.md
  9:100 no-trailing-spaces [MD009] Trailing spaces [Expected: 0; Actual: 3]
devRant-Community/Community-Programming-Book/book/languages/abc/misc.md
  6 no-emphasis-as-header [MD036] Emphasis used instead of a header "Function to convert given temp..."
  37:85 no-trailing-spaces [MD009] Trailing spaces [Expected: 0; Actual: 2]
devRant-Community/Community-Programming-Book/book/languages/assembly/advantages.md
```

Please fix these errors before merging!

"-----------Prompt Ends-------------

After the CI is successful please wait for the editing team to make changes
(if any) and finally approve your work for merging. You are free to discuss
with the concerned editor(s) about any edits made.

Though this guide is extensive it need not be exhaustive. If you have any
doubts or questions feel free to ask.

Happy Contributing ! :)
