# BasicWebdriverIOCucumber
#Pre setup:

node Js should be installed 
To check: npm -v

npm should be installed 
To check : node -v

typescript is recommended
npm install -g typescript

Install and run 
1. mkdir<foldername> and cd to the folder
2. npm init
3. npm -i --save-dev @wdio/cli

4. npm wdio config 
? Where is your automation backend located? On my local machine
? Which framework do you want to use? cucumber
? Do you want to use a compiler? TypeScript (https://www.typescriptlang.org/)
? Where are your feature files located? ./features/**/*.feature
? Where are your step definitions located? ./features/step-definitions/steps.ts
? Do you want WebdriverIO to autogenerate some test files? Yes
? Do you want to use page objects (https://martinfowler.com/bliki/PageObject.html)? Yes
? Where are your page objects located? ./features/pageobjects/**/*.ts
? Which reporter do you want to use? spec
? Do you want to add a service to your test setup? chromedriver
? What is the base url? http://localhost

5. npx wdio run wdio.conf.ts





