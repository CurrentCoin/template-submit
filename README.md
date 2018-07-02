# template-submit

This repo has been created for templates to be uploaded and reviewed as pull requests.

If you have a template you'd like to be considered for usage by CurrentCoin, please use this repo for that purpose.

To do this, clone the repo, add your files, and upload it as a branch. Our team will then review it and contact you with our feedback.

If you have questions or concerns, you can reach out to us at our email addresses.

info@currentcoin.io  
contact@currentcoin.io  
 
# template creation

The [brand page template](https://github.com/CurrentCoin/brand-page-template) and the [info spinner template](https://github.com/CurrentCoin/info-spinner-template) are examples of CurrentCoin templates.

A valid CurrentCoin template must have the following:

- A file named `interface.json` which specifies user adjustable parameters, their type, and default values.
- A file named `index.js` which exports a React component. This component must accept the user adjustable parameters as props. 

See the examples for the specifics of how the `interface.json` file is structured.

To test your template within CurrentCoin Create, create a github repository for you template. For example, https://github.com/CurrentCoin/example-template.git.

Clone the [`currentcoin-create-frontend`](https://github.com/CurrentCoin/currentcoin-create-frontend) repo.

Add your template in the folder `src/templates` alongside the other templates, by running,

`cd currentcoin-create-frontend/src/templates`

`git submodule add https://github.com/CurrentCoin/example-template.git`

Start the web-app by running,

`cd currentcoin-create-frontend`

`npm install`

`npm start`

Now you can test out your template in the browser. Note that the deploy feature will not work because your template is not yet part of the CurrentCoin system. Make a pull request, and if approved, your template will be available to anyone to deploy a live version.

