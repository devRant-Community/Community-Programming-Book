# How to contribute

## Language already complete

You can change and correct the files, by forking and changing the files in the directory /book/languages/[language] in your forked repo. After you're finished make a PR from your forked repo to this repo.

## Language not present

You must create a new subdir on /book/languages with the name of your language

### Example

``` md
/book/languages/kotlin
```

On this subdir you must create the files

``` md
readme.md
intro.md
```

The Readme.md is just to get into the next language, something like this:

``` md
# Welcome

Well, next we will talk a bit about Kotlin, the new JVM language by Jetbrains.
Kotlin is less verbose than the original JVM language Java and is now one of
the main development languages of the Android Platfom. Let's get into it.
```

The intro should be a bit longer, it should give you an brief look at the language. Talk about the story of language or tell from where it came. Look into the file intro.md at the repo root for inspiration.

You should also add your new language to the /book/Summary.md by adding

``` md
* [<Language>](/languages/<Language>/readme.md)
  * [Intro](/languages/<Language>/intro.md)

```

## Adding chapter

To start writing on a new chapter create a new file called [chapter].md at the root of language directory. Also you should add it to the /book/Summary.md

``` md
* [<Language>](/languages/<Language>/readme.md)
  * [Intro](/languages/<Language>/intro.md)
  * [<Chapter>](/languages/<Language>/<Chapter>.md)
```
