# Python

> This chapter has been authored by Gadila Shashank Reddy.

Now is the chapter on python, one of the most
popular languages with applications in a wide variety of fields. Read to find out more on what makes
python so popular that it is referred to as the "fastest growing major programming language".

# Introduction

Python is an interpreted high level programming language for general-purpose programming. It has a
design philosophy that emphasizes on *code simplicity and readability*. It provides constructs that
enable clear programming on both small and large scales. This philosophy has enabled python to become
a very popular language used in fields such as machine learning, big data, artificial intelligence,
web development and in scientific research to name a few.

# History

## Creation

Python started out as a "hobby programming project" in December 1989 by Guido van Rossum at
Centrum Wiskunde & Informatica (CWI) in the Netherlands. Internal releases of python appeared at CWI
in 1990. Python was released to the public for the first time on February 20, 1991.

## Purpose

On how python began written by van Rossum in 1996:

> ...In December 1989, I was looking for a "hobby" programming project that would keep me occupied
during the week around Christmas. My office ... would be closed, but I had a home computer, and not
much else on my hands. I decided to write an interpreter for the new scripting language I had been
thinking about lately: a descendant of ABC that would appeal to Unix/C hackers. I chose Python as a
working title for the project, being in a slightly irreverent mood (and a big fan of Monty Python's Flying Circus). \
— Guido van Rossum

Python was supposed to be a successor to the ABC language capable of handling exceptions and interfacing
with the Amoeba operating system. But with its strong emphasis on being "programmer friendly" it
quickly evolved as a popular choice of language among programmers for development and fast prototyping. The reasons are mentioned in the following sections.

## What it solves

Python is a very simple to learn language and attempts to make development process easier with some
of its powerful features. One of them is modularity. This has helped in the making of extremely useful libraries which
can do a job in the matter of a ready-made function call in python instead of wasting time in developing
the utilities first and then using them in case of other languages.

Several such libraries are created that can be included or "imported" as per need (modularity FTW)
and there are python libraries for virtually anything. This is one major advantage of using python
for developing anything.

> Search for what you want to do and there's bound to be a library for the same.

Python is created to be very flexible in the sense that its core is extremely bare-boned and all its
utilities are included externally in the form of modules or packages and can easily accommodate
changes unlike few other languages that have features included in their core and have limited scope
for major changes without compatibility issues.

## Where would you use python?

Python doesn't have a target audience. It can be used for multiple purposes and there are several
libraries and frameworks built to  simplify specific applications. Some fields where python can be best
used are:

*Examples of libraries/frameworks built for the particular application are given in brackets.*

* Web development (Django, Flask)       

* Data analysis (Numpy)

* Machine learning (TensorFlow)

* Computer Vision (OpenCV)

* Game development (Pygame)

* Web Scraping (Beautiful Soup)

* GUI development (PyQt)

* Rapid prototyping

and the list goes on and on...

Python can also be used in places where precise numerical calculations are required because precision
in calculations in python is limited only by physical resources and not the language. This feature
makes python one of the best language to be used in scientific works.

## Disadvantages

Given such a lengthy description on how good is python as a programming language it is easy to be
mistaken that python does not have any shortcomings. Some are listed:

* Since python is an interpreted language and it being built on C/C++ execution speed is slow. But
the benefits/advantages dramatically outweigh this issue.

* Due to the above point python scripts are slower than other scripting languages.

* Database access layers are underdeveloped in python so server side applications involving extensive
database use usually are not written in python.

* Rare run time errors due to the dynamic typing of variables.

* Errors are detected only when the buggy code is executed. In a production environment this could
be a problem.

* Migration from python 2 to python 3 is a real pain.

## More about python

### Zen of python

The Zen of python is a short poem that is embedded in the interpreter summarizing the design philosophy.
Type "import this" and press enter in a python interpretor

```
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the
rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those! "
```

### How it simplifies development process

Two examples both in python to scrape information about a particular page in wikipedia

**Both examples are in python 3**

```python
 import requests
 from bs4 import Beautiful Soup
 url = "https://en.wikipedia.org/wiki/History_of_Python"
 response = requests.get(url)
 soup = BeautifulSoup(response, "lxml")
 for i in soup.find_all("p"):
     print i.text()
```

```python
import wikipedia
 print(wikipedia.summary("History of python"))
 ```

Now it should be clear how python with its features and awesome libraries simplifies development
process. Note that internally both the implementations perform the exact same set of actions but one is much more simpler than the other.

## A final word

It is now understandable how python became an immensely popular language and still remains relevant
even today 20+ years after creation. Very few such languages enjoy this status.

# Sources

* [Python (Wikipedia)](https://en.wikipedia.org/wiki/Python_%28programming_language%29)

* [History of python(Wikipedia)](https://en.wikipedia.org/wiki/History_of_Python)

* [Zen of python](https://www.python.org/dev/peps/pep-0020/)

* [Quora](https://www.quora.com/Why-is-Python-so-popular-despite-being-so-slow)

* [Disadvantages of python(Quora)](https://www.quora.com/What-are-the-disadvantages-of-Python)
