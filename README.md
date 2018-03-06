# Amazon Smile Redirect

Browser extension that redirects [https://www.amazon.com/*](https://www.amazon.com) links to [https://smile.amazon/*](https://smile.amazon.com).

## Download
* Coming soon...

## Install Locally
* Firefox: [temporary](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Temporary_Installation_in_Firefox)
* Chrome: [permanent](https://superuser.com/questions/247651/how-does-one-install-an-extension-for-chrome-browser-from-the-local-file-system/247654#247654)

## Develop Locally
* Clone the repo and `cd` into it
* Install dependencies: 
	* `yarn`
* Run add-on in isolated Firefox instance using [web-ext](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Getting_started_with_web-ext):
	* `yarn serve`
* Bundle add-on into a zip file for distribution:
	* `yarn bundle`