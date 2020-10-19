# How to contribute
Thank you for being interested in contributing! You must follow some guidelines when contributing. Firstly, open a pull request and add the resource you wanted to add with this format:

### Formatting
- All lists are `.md` files. Try to learn [Markdown](https://guides.github.com/features/mastering-markdown/) syntax. It's simple!
- All the lists start with an Index. The idea is to list and link all sections and subsections there. Keep it in alphabetical order. If you have to add a new category, do it with this format: ```* [Python](#Python)```
- Sections are using level 3 headings (`###`), and subsections are level 4 headings (`####`).

The idea is to have
- `2` empty lines between last link and new section
- `1` empty line between heading & first link of its section
- `0` empty line between two links
- `1` empty line at the end of each `.md` file

Example:

    [...]
    * [**Pandas:**](http://example.com/example.html) Data analysis library
    * [**Pandas2:**](http://example.com/other.html) Data analysis library2

- Don't put spaces between `]` and `(`:

```
BAD : * [**Pandas:**] (http://example.com/example.html) Data analysis library
GOOD: * [**Pandas:**](http://example.com/example.html) Data analysis library
```


- Put a single space between the link and its description:

```
BAD : * [**Pandas:**](https://example.org/example.pdf)Data analysis library
GOOD: * [**Pandas:**](https://example.org/example.pdf) Data analysis library
```


### It will create something like this
* [**Pandas:**](https://pandas.pydata.org/) Python library for data analysis
