Currency Checker Version 1.0.0
@author Castro Opiyo

#INSTALLATION
##1.) Install Node.js

Download and install Node.js for your OS from https://nodejs.org/en/download/

2.) copy the Currency checker code from the repository
3.) Unzip the source files in a directory
4.) Open the command line / terminal in the directory of the sources.
5.) Install dependencies by running: npm install
6.) Run the application using: `npm run search [options]`

#USAGE

##DESCRIPTION
This is a command line application to check currency support.
`npm run search [options]`
OPTIONS
Options can be one of the following: 1. ISO 4217 currency code: 3 letter string representing currency
e.g 'KES' for Kenyan Shillings
npm run search kes or npm run search KES
  
 2. Help flag: character 'h' or 'H'
npm run search h or npm run search H

    OUTPUT
        1. Shows message whether currency is supported
        2. Shows a message if input is invalid
        3. Shows a help menu
