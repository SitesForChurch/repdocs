1. Open new jekyll project (You should only need one of these)
2. Install the nescessary software:

	* browser-sync
	* node-sass
	* bower

3. Clone the repo
4. Delete the `.git` folder
5. rename the repo folder to the url of the project
6. Setup your github repo
4. cd into repo
4. Install dependencies

	* `npm install`
	* `bower install`


5. Run `jekyll build` 
6. Setup `_config.yml` for making changes

* run `browser-sync start --server '_site' --files '_site'  --host 'http://0.0.0.0'`
* Goto `Preview` > `Port 3000 - HTTP`
* In the tab that opens, copy the full url.
* In `_config.yml` paste that URL over the value after `url:` (replacing http://localhost:3000)
6. Make your changes

	* Change the Airtable API keys in `_config.yml`
	* Change the colors style sheet (in Adore and Native) or the colors in `_css/settings.css` (in California and New England)

6. Open another console tab and run `jekyll build`
7. Go back to the tab to see your site updated
8. Run `jekyll build` anytime you make changes and want to see them.

