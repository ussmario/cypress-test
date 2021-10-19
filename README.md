https://docs.cypress.io/guides/getting-started/installing-cypress#Install-binary

basically cypress needs to be downloaded as a dependency in every project.
create a folder, run npm init -y, then npm install cypress --save-dev
open package.json and modify test script  to read "cypress open"
now running npm test will shortcut the command npx cypress open


A solid test generally covers 3 phases:

1 - Set up the application state.
2 - Take an action.
3 - Make an assertion about the resulting application state.
You might also see this phrased as "Given, When, Then", or "Arrange, Act, Assert".