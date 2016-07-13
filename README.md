# HTML Form to File.txt

HTML/JavaScript form that saves user input into a text file in Markdown format with YAML front matter for use on your local computer. Use to [quickly create a post for publishing](http://simongriffee.com/code/form-to-txt/) with a static website generator such as [Hugo](http://gohugo.io/) or [Jekyll](http://jekyllrb.com/). Based on [this code](https://thiscouldbebetter.wordpress.com/2012/12/18/loading-editing-and-saving-a-text-file-in-html5-using-javascrip/ "Loading, Editing, and Saving a Text File in HTML5 Using JavaScript").

To use it yourself: 

1. Download and save [index.html](https://raw.githubusercontent.com/hypertexthero/htmlformtofile/master/index.html) to your desktop or any location on your computer.
2. If you like, edit the file to add your own front matter fields. This involves modifying the JavaScript and HTML code and comments indicating these fields are present in the file.
3. Open `index.html` locally with your web browser, fill in the form fields and click **Save To File**. You can also put the file on your web server so you can access it from any computer.

I have tested the script on Firefox on Mac OS.

## Nota Bene 

The script also also works on Chrome, except that the autocomplete doesn't seem to work unless the form fields are wrapped in a form tag with the autocomplete attribute (`<form autocomplete="on">…</form>`), and when I do this the entire form disappears in Firefox. I'm still investigating this, and if you have any tips, I'm all ears and appreciate pull requests.