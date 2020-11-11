# Syntax guide

### headers
You can use one `#` all the way up to `######` six for different heading sizes.

### Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

### Lists
Sometimes you want numbered lists:

* Unordered
	* Item 1
	* Item 2
	  - Item 2a
	  - Item 2b
* Ordered
	1. One
	2. Two
	3. Three

###### Sometimes you want bullet points:

* Start a line with a star
* Dashes work just as well
	- And if you have sub points, put two spaces before the dash or star:
	  - Like this
	  - And this

### Images
If you want to embed images, this is how you do it:

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

### Block-quotes
As Kayne West said:
> We're living the future so
> the present is our past.

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

### code
If you have inline code blocks, wrap them in backticks: `var example = true`

    if (isAwesome){
      return true
    }

And if you'd like to use syntax highlighting, include the language:
``` css
#text{
	color: #333;
}
```
```javascript
if (isAwesome){
  return true
}
```


GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, you can prefix their name with an @ symbol: Hey @kneath — love your sweater!

But I have to admit, tasks lists are my favorite:

- [x] This is a complete item
- [ ] This is an incomplete item

When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!

And, of course emoji!


### links
http://github.com - automatic! [GitHub](http://github.com)

### Task Lists
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item


### Tables
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column