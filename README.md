# golbikiwmiv
blog using markdown and vimwiki (a very good vim plugin that we should all be using)
https://vimwiki.github.io/
http://thedarnedestthing.com/vimwiki%20cheatsheet

Add something that looks like this to your vimrc file:
let g:vimwiki_list = [{
	\ 'path': '$HOME/Workspace/vimwiki1',
	\ 'template_path': '$HOME/Workspace/vimwiki1/templates',
	\ 'template_default': 'default',
	\ 'template_ext': '.html',
	\ 'css_name': 'style.css',
	\ 'auto_export': 1}]
And place a default.html file in the corresponding templates directory,
that you will be able to edit at your convenience (edit vimwiki default styles...)
You can add more wiki configurations in your vimwiki_list if you wish.
In case you don't want auto_export (upon save), you can execute manually
:Vimwiki2HTML



