#What *is* mark down & what *can* it do?

---

Mark Down is a very simple *writer's* language that translates to HTML. You can create and tweak stylesheets all day long in order to get *exactly* what you want. Mark Down is also perfect for creating a rich text experience on a mobile device since it uses characters to render basic HTML. We'll take a look at some of the things that Mark Down can do and hopefully, after you read this style/feature guide you'll want to use mark down too!

---

| **Feature:** | **Included:** | **Ease of use:** |
|:--------------|:---------------:|:------------------:|
| Headings, h1-h6       |        Yes |     Super Easy     |
| Strong / **Bold** text       |        Yes |     Super Easy     |
| Emphases / *Italic* text    | Yes | Super easy |
| ***Bold / Italic*** text   | Yes | Super easy |
| ~~Strike Through~~ some text | No, Github Only | Super Easy|
| Horizontal rules    | Yes | Super easy |
| Ordered & unordered lists | Yes | Super easy |
| Code Snippets | Yes | Super Easy |
| Links or URLs    | Yes |  Easy |
| Images    | Yes | Easy |
| Block Quotes | Yes | Easy |
| Tables | Yes | Intermediate | 


---

###Headings

#h1
##h2
###h3
####h4
#####h5
######h6

Headings are created like this:` #h1 ##h2 ###h3` and so on

###Rich Text

**Bold** `**Bold**` is two * 's on the left and right sides of your word, touching it.

*Italic* `*Italic*` is one * on the left and right sides of your word or phrase, touching it.

***Bold & Italic*** `***Bold & Italic***` is three *'s on either side of your word, touching it.

~~Strike Though Text~~ `~~Strike Though Text~~` saddly is only supported on github. Too bad because it's really useful.

###Horizontal Rules

---

Hr's are easy to do, `---` will create one.

###Ordered & Unordered Lists

1. Lists are fun and easy!
2. I like to dance!
3. Motorcycles!!!!

This is an Ordered list. Create one this way:
` 1. Item One
2. Item Two
3. Item three ` 
typing a number & a period then space you'll have an ordered item! 

* I like to Move it
* I like to Move it Move it
* MOVE IT!

This is an Unordered List. Create one like this:
`* Item One * Item Two * Item Three` by typing * and space you create an unordered list.

###Code Snippets 
		<div class="codeSnippet">
			<p>This is a code snipt.</p>
		</div>
	
`<div class="inlineCodeSnippet"><p>This Code Snippet is inline!</p></div>`
	
Code snippets are created by putting ` in front and after your code, or by indenting the line. By indenting the line you keep your vertical line of code. Code Snippets are really handy for developers. :)
	
###Links & URLs
	
[A Link to Markdown Syntax](http://daringfireball.net/projects/markdown/syntax#p/ "MarkDown!")
	
Links and URLs are also easy to create. `[Link Content](http://linkaddress.com/ "Alt Text")` Easy as pie.

###Images

![Place Some Kittens](http://placekitten.com/g/200/300 "Kittens Rule!")

Markdown Supports Images! Some Markdown readers do not support them however. 
The code is just like a link only you add a ! infront `![Alt Text](path to image "Optional title")`

###Block Quotes

Emails use block quotes and they are handy for conversations. Markdown uses them too. Like everything else they are super easy. 

>
>####Black Quote Paragraph with Header
>
>Here's the paragraph: Bacon ipsum dolor sit amet shank ham jowl rump, tenderloin turducken tri-tip sausage beef ribs jerky prosciutto. Tail hamburger filet mignon, t-bone short loin shankle venison beef capicola sirloin. Beef ribs spare ribs chuck turkey kielbasa jowl ground round tongue swine, capicola venison speck. Biltong tenderloin shoulder frankfurter meatloaf pastrami. Turducken sirloin ham pork. Strip steak short ribs leberkas, salami chuck biltong ham t-bone meatball tenderloin. Drumstick ball tip shankle, speck jerky ground round pork loin ham hock meatloaf cow shank capicola filet mignon turkey.
>
>>Second Block Quote Line
>>>Third Line
>

Block quotes are easy, fun & simple. However, some markdown readers only support 1 or 2 lines of block quote or won't indent past the first line. So you get a weird paragraph. Block quotes support almost all of the other markdown elements including rich text, headers & lists!

	>Block Quotes Use the ">" to indent
	>Use anything you want
	>>Go Deep!
	>>>We must go deeper!
	
###Tables

| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |

Markdown does indeed support tables! Tables are kind of hard to build sometimes, the formatting is wacky. That's why they are last on the page. Here's the code:

	| Left align | Right align | Center align |
	|:-----------|------------:|:------------:|
	| This       |        This |     This     |
	| column     |      column |    column    |
	| will       |        will |     will     |
	| be         |          be |      be      |
	| left       |       right |    center    |
	| aligned    |     aligned |   aligned    |

Notice that to left align you add : to the left of your rule bar under the titles. To center you ad : to either side of the bar and to right align you add : to the right side. It's simple and makes sense but there is some red necking involved in getting it right the first few times. Tables also support rich text. I assume links will work as well however, I haven't tried them yet. 

---

In conclusion MARKDOWN RULES! You should be using it today! There are a variety of apps that use markdown. I personally use [ByWord](http://bywordapp.com/ "ByWord") as my word-processor & [DayOne](http://dayoneapp.com/ "DayOne") as my journal. I recently purchased [Marked!](http://markedapp.com/ "Marked") in the app store which renders an updated version of your page overtime you save. At any rate, any text editor will write markdown, including basic notepad & textedit! There's no excuse *not* to use markdown! Start using markdown today! (Heck, I wrote this *in* ByWord!)





