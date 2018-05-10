### Web-sushi

A SPA where you can add/remove items from a cart, scroll through individual menu items to view nutritional information, etc.

#### Running locally

- Clone repo
- Navigate with your terminal to the newly cloned folder, and run the following commands:
- Get server dependencies: Run `npm install`
- Get client dependencies: Run `bower install`
- Run `npm start` and go to `localhost:3000` in your browser of choice

#### Notes

##### Making template changes

- This project uses [precompiled Handlebars templates](http://handlebarsjs.com/precompilation.html). Currently precompiling is a manual process, so if you make changes to a `.handlebars` files, run `handlebars views/templates/ -f public/javascripts/templatesCompiled.js` from the project directory to re-generate the templates.
