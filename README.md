# cucumber-protractor

setup Scripts
Clone the repository into a folder

Go inside the folder and run following command from terminal/command prompt

npm install 

Run Scripts
First step is to fire up the selenium server which could be done in many ways, webdriver-manager proves very handy for this.The below command should download the chrome & gecko driver binaries locally for you!

npm run webdriver-update

Then you should start your selenium server!

npm run webdriver-start

The below command would create an output folder named 'typeScript' and transpile the .ts files to .js.

npm run build

Now just run the test command which launches the Chrome Browser and runs the scripts.

npm test
