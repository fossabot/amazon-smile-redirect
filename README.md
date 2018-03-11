# Amazon Smile Redirect

[![devDependency Status](https://david-dm.org/nitrohorse/amazon-smile-redirect/dev-status.svg)](https://david-dm.org/nitrohorse/amazon-smile-redirect#info=devDependencies)
[![Known Vulnerabilities](https://snyk.io/test/github/nitrohorse/amazon-smile-redirect/badge.svg?targetFile=package.json)](https://snyk.io/test/github/nitrohorse/amazon-smile-redirect?targetFile=package.json)

Browser extension that redirects [https://www.amazon.com/*](https://www.amazon.com) links to [https://smile.amazon/*](https://smile.amazon.com) so that you don't forget to contribute to your favorite non-profit.

## Download
* [Firefox](https://addons.mozilla.org/en-US/firefox/addon/amazon-smile-redirector/)

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

## Resources
* Icon by [Icons8](https://icons8.com/)
