#Markdown

---

Hi, I created this repo as an example of what Markdown can do. See the *markdown.md* file to see a full feature / style guide. If you're interested you might read the specs over at [The Daring Fireball](http://daringfireball.net/projects/markdown/syntax/ "Daring Fireball"). 
I'll be updating this file with ways you can implement markdown in your everyday life to make it better. 
If you decide that you just can't live with out markdown here's a list of apps to use in your adventures:

|  **App:**  |  **Platform:**  |  **Cost:**  |
|:---------:|:--------------:|----------:|
| [TextEdit](http://support.apple.com/kb/HT2523/ "TextEdit") (Simple Text Editor) | osX | Free! Included with OS |
| [Notepad](http://www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/app_notepad.mspx?mfr=true/ "NotePad") (Simple Text Editor) | Windows | Free! Included with OS |
| [ByWord](http://bywordapp.com/ "ByWord") (Word Processor) | Mac osX 10.6 & up, iOS | $9.99 for osX & $2.99 for iOS |
| [DayOne](http://dayoneapp.com/ "DayOne") (Journal App) | Mac osX 10.6 & up, iOS | $9.99 for osX & $2.99 for iOS|
| [Marked](http://markedapp.com/ "Marked") (Markdown Previewer) | Mac osX 10.7 | $3.99 |
|[Sublime Text 2](http://www.sublimetext.com/2) (Text Editor) | All desktop OS | Free for Beta or $50.00 |
| [TextMate](http://macromates.com/) (Text Editor) | osX | $53.00 |
| [Coda](http://www.panic.com/coda/) (Text Editor) | osX | $99.00 |
| [NotePad++](http://notepad-plus-plus.org/) (Text Editor) | Windows | Free |
| [Microsoft Visual Studio](http://www.microsoft.com/visualstudio/en-us) (IED) | Windows | Not sure |

*Remember, anything that can write text can pretty much write markdown. The programs included here either support markdown with syntax highlighting or are markdown apps that have previews built in. ByWord for example, exports the HTML, previews Markdown, uses syntax highlighting, exports richtext, & prints richtext or markdown. So, The choices is yours. If you stumble across an app i left out, feel free to message me and i'll add it!

###Implementing Markdown with Sinatra

On my blog I've implemented markdown on my posts. I'm not sure in how to do it else where but in Sinatra it looks like this:

	require "markdown"
	<%= markdown post %>
	
If you use markdown else where let me know and i'll add it. I will also update this file as I use it in other projects on other platforms. 
	