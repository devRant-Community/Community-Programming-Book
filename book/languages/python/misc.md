# More about python

## Zen of python

The Zen of python is a short poem that is embedded in the interpreter summarizing the design philosophy.
Type "import this" and press enter in a python interpretor

```md
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

## How it simplifies development process

Two examples both in python to scrape information about a particular page in wikipedia

*Both examples are in python 3*

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
