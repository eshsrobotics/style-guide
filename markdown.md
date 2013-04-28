Markdown
========


This document will elaborate on the specific style conventions customary of ESHS Robotics. For just Markdown's syntax, refer to [Daring Fireball's article](http://daringfireball.net/projects/markdown/syntax) on it.

Line Wrapping
-------------

Line wrapping should always be turned on. This means you should never be putting line breaks inside of paragraphs.

Preferable:

	My super long paragraph is super long and wrapped.

Not preferable:

	My super long paragraph is
	super long and not wrapped.


Headers
-------

### Syntax Preferences

Sections inside of a Markdown document should be denotated using headers.

First-level headers should always be underlined with equals signs and second level headers should be underlines with dashes. For example:

	First-Level Header
	==================
	
	Second-Level Header
	-------------------

The rest of the header levels should be followed by hashes, indicating the level of header.

	### Third-Level Header
	
	#### Fourth-Level Header
   
	##### Fifth-Level Header
	
	###### Sixth-Level Header


### Spacing

Header presedence is as follows:

	H1 > H2 > H3 > … > H6 > other content

If a header follows a header of higher presedence, then there should be a single blank line between the headers

	Header
	======
	
	Another Header
	--------------

If a header follows a header of lower presedence, then there should be two blank lines between the headers.

	### Wallets Hold Money
	
	
	Sharpies Write Stuff
	--------------------
	
	other content
	
	
	### Watches Tell Time


### Capitalization

Use standard MLA capitalization rules for first and second-level titles. Lower level titles should only have their first word and proper nouns capitalized. 

	Modernism and Negritude
	=======================
	
	Bernard Berenson: The Making of a Connoisseur
	---------------------------------------------
	
	### The all-mighty Jim fell off a boat.


### Nesting

Headers should be nested according to the presedence detailed earlier.

	My Big Title!
	=============
	
	
	First Big Idea
	--------------
	
	### First Big Detail
	
	#### Subdetail
	
	#### Subdetail
	
	
	### Second Big Detail
	
	#### Subdetail
	
	#### Subdetail
	
	
	Second Big Idea
	---------------
	
	### First Big Detail
	
	#### Subdetail
	
	#### Subdetail
	
	
	### Second Big Detail
	
	#### Subdetail
	
	#### Subdetail


Content
-------

### Death to the tab infidels

Need to indent? Use four spaces instead of tabs

	some content
	
		indendation!
		
	more content


### Inline HTML

Don't use inner HTML when you don't have to. When you do need to, use two spaces for indentation.

	This is a regular paragraph.
	
	<table>
	  <tr>
		<td>Foo</td>
	  </tr>
	</table>


### Blockquotes

Follow standard blockquote rules.

	> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.


### Lists

#### Unordered

Presedence of list markers is as follows:

	* > - > +

Use two spaces to denote each level of the list.

	* Foo
	  - Bar
		+ Foo
		+ Baz
	  - Bar
	* Foo

If you go deeper than three levels, alternate between `-` and `+`.

    * Foo
      - Bar
        + Foo
          - Bar
            + Foo


#### Ordered

Always start ordered lists with 1 and use the proper number for each element in the list. The generated HTML should match the Markdown source.

    1. Bird
    2. McHale
    3. Parish

Although it will work, this is bad:

    1. Bird
    3. McHale
    8. Parish


#### Code

As said earlier, use four spaces instead of a tab for indentation.

    some content
    
        // Fixes the bug
        #define true false
        

#### Horizontal rules

Use three dashes separated by spaces to create a horizontal rule.

     some stuff
     
     - - -
     
     some more stuff after the horizontal rule


#### Links

Do not include the title attribute with normal links unless absolutely necessary.

    This is how [links](http://example.com/) should look.

Do not use spaces to separate the sets of brackest in reference-style links. If the reference-style link is to an article, then specify a title in parenthesis. Do not surround the URL in reference links with angle brackets.

    This is [an example][id] reference-style link.
    
    [id]: https://example.com/ (Article Title)


#### Emphasis

Use asterisks to indicate emphasis. Use double asterisks to indicate strong emphasis.

    *normal emphasis*
    
    **strong emphasis**


##### Images

Do not include the title attribute with normal image links.

    ![Screenshot](http://example.com/screenshot.png)

Do not use spaces to separate the sets of brackest in reference-style links. If the reference-style link is to an article, then specify a title in parenthesis. Do not surround the URL in reference links with angle brackets.

    [Screenshot][1]
    
    [1]: https://example.com/screenshot.png (Screenshot)