# njuskalo-qa-specialist
## instructions
1. git clone this repository
2. cd into cloned repository and open it in editor of choice
3. input username and password for an existing profile on njuskalo.hr website in `cypress/e2e/main.cy.js` file
4. run command to install cypress
    ```
    npm install cypress --save-dev
    ```
5. run command to start cypress
    on linux
    ```
    node_modules/.bin/cypress open
    ```
    on windows
    ```
    node_modules\.bin\cypress open
    ```
6. in opened window choose `E2E Testing`
7. next choose your preferred browser
8. to run the automated test click on `main.cy.js` file