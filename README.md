# Chris Johnson's Sublime Text 2 config

## Plugins / Themes / Credits
* [Package control plugin](http://wbond.net/sublime_packages/package_control)
* [Soda theme](https://github.com/buymeasoda/soda-theme)
* [Inconsolata-dz Font](http://nodnod.net/2009/feb/12/adding-straight-single-and-double-quotes-inconsola/)
* [Icon by Daniel Matarazzo](https://github.com/dmatarazzo/Sublime-Text-2-Icon)

## Installation
1. [Install package control](http://wbond.net/sublime_packages/package_control/installation), access the Sublime Text 2 console by typing  *ctrl+`* then enter:

		import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print 'Please restart Sublime Text to finish installation'

2. Go to your packages directory:

		cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/

3. Install required extensions/themes:

		git clone https://github.com/buymeasoda/soda-theme/ "Theme - Soda"

4. Move the settings files in this repository into your packages directory.

5. Install command line 'subl' tool

		sudo ln -s /Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl /usr/bin/subl

## Notes
* Currently using ["Vintage mode"](http://www.sublimetext.com/docs/2/vintage.html) which is a mini VI command mode
* Installed Zen Coding through Package Control

## Keyboard reference
* Bring up command menu = [Command+Shift+p]
* Fuzzy search = [Command+p]
* Column selection = [Option + drag]
* Multiple selection = [Command + select]
* Distraction free mode = [Control + Command + f]
* See list of functions/css definitions = [Command + r]

### Vin(tage) mode
* Bring up VI command mode = [Esc]
* Insert mode = [i]
* Jump to line = line number + G
* Toggle case = visual select then + g~ (gU = upper, gu = lower)

### Zen Coding
* Expand Zen Coding HTML = [Tab]