# bitfinex mobile application testing using webdriverIO

The framework is based on emulator for andoird 12.0 and is configurable for other version too. 

## Pre-Condition 
* Android SDK is installed on machine and there should be one working emulator with version 12. Here is link to android SDK installation: https://developer.android.com/studio?gclid=Cj0KCQjw-pCVBhCFARIsAGMxhAf1x03LhY434R4mONjHXbZeurqMdZkCYTMAkBb5Tcxuup3MKdmQtJsaAlpcEALw_wcB&gclsrc=aw.ds
* Creating virtual device for android https://developer.android.com/studio/run/managing-avds

## Tech Stack 
- Andorid SDK to work in emulators 
- javaScript 
- mocha framework 
- webdriverio

## UseCase which is automated 
1. User get confirmation dialog with ETH value.

## Demo 


## Setup

* Must have NodeJS and NPM installed (https://nodejs.org/en/)
* Install dependencies by running `npm install`

## Running Tests

* To run the tests, run `npx wdio`


## Enhancement
  * allure-results integration 
  * Integration with CI tool i.e. Jenkins
  * Convert to pageObject desgin pattern or gerkins 
  * API call for setup and tearDown 
