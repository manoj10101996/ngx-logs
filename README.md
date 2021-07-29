<img src="https://img.icons8.com/ios/100/000000/console.png"/>

# Welcome to NGX-LOGS!

 Console input / output strings or any message strings at browser console.
 The  **`console.log()`**  method outputs a message to the web console. The message may be a single string (with optional substitution values), or it may be any one or more JavaScript objects.


## Preview demo

This preview was generated with [CODESANDBOX](https://codesandbox.io/s/ngx-logs-94olx)


## Import

Import the module on your `app.module.ts` file as follow.
> import { NgxLogsModule } from "ngx-logs";

Then import the module as follow on imports array
> NgxLogsModule


## Using

After importing this library with `npm install ngx-logs`, go to the component which is declared under `app.module.ts` and integrate as below.


##  NGX LOGS MODULE

> constructor(private ngxLogs: NgxLogsService) { } 

 Use reference for logs service in constructor and import it respectively at any component

## Methods

This are the methods available with ngx-logs use it as per your requirement:

|                |Method						 |Usage                        |
|----------------|-------------------------------|-----------------------------|
|Profile		 |`this.ngxLogs.profile();`      |Displays current profile from browser page 		  opened for reference as Profile with counter- *Very useful for developing*                        |
|Directory       |`this.ngxLogs.directory();`            |Logs current page info with all require information's (URL, PATH etc.)          |
|Clear 			 |`this.ngxLogs.clear();`		|Clears the entire console logs|
|Log			 |`this.ngxLogs.log('Log Message from NgxLogsService');`	|Logs standard custom strings as console logs
|Warn			 |`this.ngxLogs.warn('Warning Message from NgxLogsService');` | Logs Error message for custom strings as console logs
|Info			 |`this.ngxLogs.info('Info Message from NgxLogsService')` |Same as console logs
|Error			 |`this.ngxLogs.error('Error Message from NgxLogsService');`|Logs Error message for custom strings as console logs
|Memory			 |`this.ngxLogs.memory();`	|Logs memory info
|Counter 		 |`this.ngxLogs.counter('Value');`|Console logs for iterations with index value - Can be used with for , forin, foreach, do..while
|Table / JSON    |`this.ngxLogs.table(array)`| Displays array or JSON of array/dictionary input as a table in console


## Angular version

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.9.

## Code integration

To use this package as a service `npm i ngx-logs` install this on the root angular project .

> Note: Don't forget to run this commend `npm i ngx-logs` on root folder or else it will throw error.
