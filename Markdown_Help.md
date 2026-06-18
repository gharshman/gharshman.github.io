# GitHub Flavored Markdown

* [John Gruber's original spec](http://daringfireball.net/projects/markdown/)
* [Github-flavored Markdown info page](http://github.github.com/github-flavored-markdown/)

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

Horizontal line: Three (3) or more: Hyphens, Asterisks, Underscores
-----
*****
_____

# Table of Contents (H1)
Main topics H2, Sub-topics H3     
[Topic 1](#topic1)   
[Topic 2](#topic2)   
[Topic 3](#topic3)   
&nbsp;&nbsp;&nbsp; [Subtopic 1](#subtopic1)     
&nbsp;&nbsp;&nbsp; [Subtopic 2](#subtopic2)     
&nbsp;&nbsp;&nbsp; [Subtopic 3](#subtopic3)     

-----

## Notes

> [!NOTE]  
> This is a note.

> [!TIP]
> This is a tip.

> [!IMPORTANT]  
> This is important.

> [!WARNING]  
> This is a warning.

> [!CAUTION]
> This is a caution.

-----
## Blockquotes

> This is a *block quote*. Bounty belaying pin quarterdeck scuttle grog blossom red ensign hands pillage coxswain heave down. Pressgang long clothes walk the plank pirate driver parley heave down bilge execution dock overhaul. Crack Jennys tea cup scallywag Pirate Round rutters belay bowsprit bring a spring upon her cable Brethren of the Coast clap of thunder Jack Tar. Furl Buccaneer blow the man down take a caulk tender tackle booty lateen sail killick gangway. Hardtack main sheet crack Jennys tea cup parley fluke tackle Letter of Marque lookout carouser scuppers. Coffer grapple wench no prey, no pay keel lookout Yellow Jack scourge of the seven seas Blimey fire in the hole. Splice the main brace heave down hulk provost killick Letter of Marque bilge rat flogging grog blossom Chain Shot. Warp to go on account gaff scallywag line man-of-war hands crack Jennys tea cup weigh anchor Sink me. Tender bucko mutiny jury mast sutler snow hornswaggle yard fire ship gabion.

>> This is **also a block quote**. Bounty belaying pin quarterdeck scuttle grog blossom red ensign hands pillage coxswain heave down. Pressgang long clothes walk the plank pirate driver parley heave down bilge execution dock overhaul. Crack Jennys tea cup scallywag Pirate Round rutters belay bowsprit bring a spring upon her cable Brethren of the Coast clap of thunder Jack Tar. Furl Buccaneer blow the man down take a caulk tender tackle booty lateen sail killick gangway. Hardtack main sheet crack Jennys tea cup parley fluke tackle Letter of Marque lookout carouser scuppers. Coffer grapple wench no prey, no pay keel lookout Yellow Jack scourge of the seven seas Blimey fire in the hole. Splice the main brace heave down hulk provost killick Letter of Marque bilge rat flogging grog blossom Chain Shot. Warp to go on account gaff scallywag line man-of-war hands crack Jennys tea cup weigh anchor Sink me. Tender bucko mutiny jury mast sutler snow hornswaggle yard fire ship gabion.

-----

## Code and Syntax Highlighting

Inline `code` has `back-ticks` around it.

Blocks of code are fenced by lines with three back-ticks <code>```</code>.

```javascript
var mystring = "JavaScript syntax highlighting";
alert(mystring);
```

```python
mystring = "Python syntax highlighting"
print mystring
```

```
No language indicated.
let message = 'Press ENTER when done';
// comment
<b>tag</b>.
```

-----

Emphasis, aka italics, with *asterisks* or _underscores_.     
Strong emphasis, aka bold, with **asterisks** or __underscores__.     
Combined emphasis with **asterisks and _underscores_**.     
Strikethrough uses one tilde ~Scratch This~ or two tildes. ~~Scratch this.~~      

-----

## HTML in Markdown

You can sometimes use raw HTML in your Markdown.

### Definitions

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

SuperScript<sup>You *can* use **markdown** in ***superscript***</sup>

SubScript<sub>You *can* use **markdown** in ***subscript***</sub>





### HTML Tables

<table>
  <tr><th>HTML</th><th>Tables</th><th colspan="2">Are Possible</th></tr>
  <tr><th colspan="2">Dessert:</th><td>Jello</td><td>Whirrled</td></tr>
  <tr><td colspan="4" align="center">And more flexible</td></tr>
  <tr><td colspan="4" align="center">since you can use colspan</td></tr>
  <tr><td>And</td><td rowspan="2" colspan="2" align="center">rowspan</td><td>To</td></tr>
  <tr><td>Also</td><td>Boot</td></tr>
</table>

### Details/Summary

<details><summary><b>This is the summary --- click here</b></summary>     
   **Hidden text waiting to be revealed.**     
   ### Surprise!     
   You can use markdown **here in details** but not in the **summary**.     
</details>     

For &lt;img&gt; see [***Images***](#images)  





-----
## Images

```markdown
Here's a logo (hover logo to see the alt text):

Inline-style: 
![don't forget to do alt text](https://avatars.githubusercontent.com/u/42009457?s=40&v=4 "Logo Title Hover Text")

Reference-style: 
![don't forget to do alt text, this is a logo][logo]

And regular HTML img tags work, and allows setting the width or height, and classes for use with pages:

<img width="200" alt="Hi There! Please be descriptive with Alt Text!!" class="recess" src="https://avatars.githubusercontent.com/u/42009457?s=400&u=2dcba5c146315f82f802b8b58e92a4d6b82344b3&v=4">

[logo]: https://avatars.githubusercontent.com/u/42009457?s=40&v=4 "Logo Title Hover Text: The Sequel"

```

Here's a logo (hover to see the title text):

Inline-style: 
![don't forget to do alt text](https://avatars.githubusercontent.com/u/42009457?s=40&v=4 "Logo Title Hover Text")

Reference-style: 
![don't forget to do alt text, this is a logo][logo]

And regular HTML img tags work, and allows setting the width or height, and classes for use with pages:

<img width="200" alt="Hi There! Please be descriptive with Alt Text!!" class="recess" src="https://avatars.githubusercontent.com/u/42009457?s=400&u=2dcba5c146315f82f802b8b58e92a4d6b82344b3&v=4">

[logo]: https://avatars.githubusercontent.com/u/42009457?s=40&v=4 "Logo Title Hover Text: The Sequel"





---
## Links

There are several ways to create links.

```markdown
[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers][1] for reference-style link definitions

Or leave it empty and use the [link text itself][]

This is useful when you are doing lots of cites [[2],[3]].

Some text to show that the reference links can follow later. 
But while we're at it, might as well point out we can use 
<a href="#Links" class="dismissed">html links</a> too—this is 
useful if you need to add a class for use with pages/Jeckyl/whatever.

The actual links for the above examples are below this line, but hidden in the final html output.

[arbitrary case-insensitive reference text]: https://git.myndex.com
[1]: http://apcacontrast.com
[link text itself]: http://tangledweb.xyz
[2]: http://apcacontrast.com
[3]: https://linktr.ee/Myndex

-----
*This space for lease*
```

[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers][1] for reference-style link definitions

Or leave it empty and use the [link text itself][]

This is useful when you are doing lots of cites [[2],[3]].


Some text to show that the reference links can follow later. 
But while we're at it, might as well point out we can use 
<a href="#Links" class="dismissed">html links</a> too—this is 
useful if you need to add a class for use with pages/Jeckyl/whatever.

The actual links for the above examples are below this line, but hidden in the final html output.

[arbitrary case-insensitive reference text]: https://git.myndex.com
[1]: http://apcacontrast.com
[link text itself]: http://tangledweb.xyz
[2]: http://bridgepca.com
[3]: https://linktr.ee/Myndex

-----
*This space for lease*

---
## Lists

```markdown
1. First ordered list item
2. Another item
    * Unordered sub-list, lead with 4 spaces
1. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list, lead with 4 spaces
        1. More sub, lead with 4 spaces
            3. Notice how the numbers can get janky
            1. Notice how the numbers can get janky
        2. previous sub
    2. previous sub
4. And another item.


1. Main level
    1. second level
        1. third level
            - fourth level
        2. third level
    2. Second level
7. main level



Unordered list:

- This is a list
    - This is a sub list, lead with 4 spaces
        - and a further sublist, lead with 4 spaces
            - and still more subing
    - back down a few
    1. add in some ordered stuff
    3. more ordered stuff
        2. sub ordered stuff
            1. Hi There
- Back to the future
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```

1. First ordered list item
2. Another item
    * Unordered sub-list, lead with 4 spaces
1. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list, lead with 4 spaces
        1. More sub, lead with 4 spaces
            3. Notice how the numbers can get janky
        7. previous sub
    2. previous sub
4. And another item.


1. Main level
    1. second level
        1. third level
            - fourth level
        2. third level
    2. Second level
7. main level


Unordered list:

- This is a list
    - This is a sub list, lead with 4 spaces
        - and a further sublist, lead with 4 spaces
            - and still more subing
    - back down a few
    1. add in some ordered stuff
    3. more ordered stuff
        2. sub ordered stuff
            1. Hi There
- Back to the future
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses


-----
## Line Breaks 

Here are some things to try out:

```markdown
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also begins a separate paragraph, but,
despite having a single newline, it just gets wrapped together.

This line ends with four white spaces before hitting return.    
So the next line becomes a single new line
```

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also begins a separate paragraph, but,
despite having a single newline, it just gets wrapped together.

This line ends with four white spaces before hitting return.    
So the next line becomes a single new line


-----
## Tables

```markdown
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Colons can be used to align columns.

| Tables        | Are           | Cool |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

> [!NOTE] 
> Also see HTML tables above in [HTML Tables](#html-tables)


-----

> [!TIP]
> Any requests for features fleshed out? DM me or leave a message below.

This cheatsheet started with a fork of Joshua Pekera's _"Markdown Here"_. This Gist is expanded to cover **GitHub Flavored Markdown**, and the nuances of working with various GitHub documents.
