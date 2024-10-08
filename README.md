# Heading 1
This is just some regular text!
No special characters needed to make a paragraph.
## Heading 2
We made another heading, but with two ##.
See how # is only interpreted as a heading if it is the first character on a new line?
### Heading 3
And so we can keep going.
Also, did you notice that text with a space between lines gets combined on GitHub?

# Emphasis
_italic_

**bold**

**_bold and italic_**

# Lists
## Ordered List
1. Ready
2. Set
3. Go!
## Unordered List
- Ready
- Set
- Go!

# Contextual Text Formats
## Blockquote (single line)
> This is a block quote
## Blockquote (multiple lines)
> Rule of thumb: if you think something is clever and sophisticated
> beware-it is probably self-indulgence.
> 
> \- Don Norman
## Code
`This is a snippet of code`
## Code Block
```C#
// This is a C# code block
while(true)
{
  Console.WriteLine("Hello, world!");
}
```

# Hyperlinks
For a simple hyperlink, just past it.

https://en.wikipedia.org/wiki/Game

For named hyperlinks, use this format: \[text\]\(url)

[Super secret hyperlink](https://en.wikipedia.org/wiki/Game)

# Media
Link to media,  using \!\[text\]\(path/to/media\)

We can use relative (local to repository) or absolute (full, typically for URL) paths to media files.

## Absolute Path
Useful for linking to media via URLs.

![Image of very old game](https://upload.wikimedia.org/wikipedia/commons/0/0d/Gaming_Board_Inscribed_for_Amenhotep_III_with_Separate_Sliding_Drawer%2C_ca._1390-1353_B.C.E.%2C49.56a-b.jpg)

## Relative Path
Here's some media in this GitHub repository.

![TBD relative img](./lady-bacon.png)

## Broken Link
When media cannot be found, it'll look like this (link intentionally missing extension `.jpg`).

![Image of very old game](https://upload.wikimedia.org/wikipedia/commons/0/0d/Gaming_Board_Inscribed_for_Amenhotep_III_with_Separate_Sliding_Drawer%2C_ca._1390-1353_B.C.E.%2C49.56a-b)

# Dividers
Some text.

---

Divided!

***

Divided once more!

___

And yet again!

# Colours
Mardkown does not natively support text color. If you really need it, you must use HTML syntax. However, GitHub tends to strip out HTML.

<span style="color:red;">Red text</span>.

# Escape Sequence
Use \\ if you need a character but it gets interpreted as Markdown.

\# Not a heading

\*not bold\*
