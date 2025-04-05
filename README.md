# Demo-NPM-package-

## Phase 1: creating the folder structure:

#### step1: create a main folder containing two sub folders as package & test.

#### step2: Install npm inside your package folder with the following creds: 
###### package name: the final name you want on your package
###### author name: the name of the author

#### step3: create index.js file and write your script inside it. Now export the module.

## Phase 2: Create Gobal Linkage and test the package
#### step4: use the command 'npm link' to create a global link

#### step5: go inside the test folder and create a script.js file and write your test code inside it.

#### step6: Import the package with global linkage using "require('package_name')" inside your script file

#### step7: install the package inside your test folder using the command "npm link 'package_name'". this will install all the dependencies of your package inside the test folder

#### step8: run the command "node script.js" to run the package.

## Phase 3: Publishing the package to NPM 

#### step9: go back to the package folder and run command npm login to sign in to your npm account 

#### step10: run the command 'npm publish --access=public' to publish your npm package with access to all

### Congrats your package is published 🥳🎉 