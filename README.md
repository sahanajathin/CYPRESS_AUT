#Automate tests in Cypress

Pre-requisites:
Windows-7 & Above 64bit & memory 4gb minimum
Node.js 12 & above
IDE (any IDE which supports, used Visual Studio Code)

Set Up:
Create a new folder for cypress project
Open the folder in VS code
Open VS code terminal and run npm init -y [will create a package .json in project folder]
Install cypress [npm install cypress]
npx cypress verify [To verify the cypress set up]
npx cypress open [ To open the cypress]
select E2E Testing>>Continue>choose a browser[for ex: firefox]
Create new empty spec [can run the default spec (spec.cy.js) as a test run]

Run Script : 
In CLI run command npx cypress run -s .\cypress\e2e\Task.cy.js -b firefox [-s => Spec and -b => Browser] or
npx cypress open>> Run spec in cypress Runner
