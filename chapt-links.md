# Working with links

## Adding Links []()

type the text becomes the link between the square brackets. type the URL between the parentheses.

[A great website](https://www.inter.net)

## Using Reference-Style Links

to create a reference , surround the text with square brackets contain a number
like this [This is a link to some here][1]

[1]: https://www.inter.net

## Adding a title to a link

see some text pop up when your mouse pointer is over the link in a web browser
surround the text by quotes. like this
[learn more about the open source project](https://opensource.org "At my blog, open source")

## Adding an Internal Link

a link from one section of your document to another. use internal links:

- as a table of contents for a longer web document.
- as a mini table of contents for a book chapter.
- to refer back to sth you've written in the document.

### create an internal link with markdown.

create the link followed by parentheses. add a hashtag followed by the name of the link's destination.
[Inserting a Bookmark](#bookmark)
add the name of destination surround by curl braces.
{\#bookmark}

### creating a internal link with html.

- insert a bookmark.
- create the link.

#### inserting a bookmark

<a name="bookmark"></a>
to use the bookmark, put in front of the text that you want to link to.

## <a name="inserting"></a>Inserting a Bookmark.

#### creating the link

[link text](#inserting)
