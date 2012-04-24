About
============
This bundle contains some handy shortcuts to make writing ExactTarget SSJS *JUST* a little bit easier. This is by no means a complete collection of commands and I certainly welcome any contributions, additions, and suggestions.

Thanks!
Kyle Keesling
kkeesling@exacttarget.com
[@kylekeesling](http://twitter.com/kylekeesling)

Installation
============
To install via Git run the following Commands in Terminal:

		cd ~/Library/Application\ Support/TextMate/Bundles/
		git clone git://github.com/kylekeesling/ET-SSJS.git "ET-SSJS.tmbundle"
		osascript -e 'tell app "TextMate" to reload bundles'		

Updating
============
If you want to make sure you are running the latest version of the bundle run the following commands in Termial:

	cd ~/Library/Application\ Support/TextMate/Bundles/ET-SSJS.tmbundle
	git pull
	osascript -e 'tell app "TextMate" to reload bundles'
	
Troubleshooting
===================	
If you have modified the bundle since pulling it from the repo and run this command you'll get an error saying something like the following:

	error: Your local changes to the following files would be overwritten by merge:
	Please, commit your changes or stash them before you can merge.
	
If you are ok losing these changes run the following commands in Terminal, this will reset the bundle and pull the latest version from github.

	cd ~/Library/Application\ Support/TextMate/Bundles/ET-SSJS.tmbundle
	get reset --hard
	git pull
	osascript -e 'tell app "TextMate" to reload bundles'
	
If you don't want ot lose the changes and think they'd be useful for everyone then submit them to me in a pull request and I'll add them to the bundle so everyone can take advantage of them.





