<img src="https://image.flaticon.com/icons/png/512/5117/5117142.png" width="150px" title="Default RATING" alt="STAR">

# Console input / output strings or any message strings at browser console.

> Managing logs for developer reference

# Preview demo

This preview was generated with [Stackblitz](https://stackblitz.com/edit/ngx-logs)

## Import

Import the module on your `app.module.ts` file as follow.

> import { NgxLogsModule } from "ngx-logs";

Then import the module as follow on imports array

> NgxLogsModule

## Using

After importing this library with `npm install ngx-logs`, go to the component which is declared under `app.module.ts` and integrate as below.

## NGX LOGS MODULE
> constructor(private ngxLogs: NgxLogsService) { } - Use reference for logs service in constructor and import it respectively
 
## METHODS
> this.ngxLogs.profile(); - Displays current profile from browser page opened for reference as Profile with counter

> this.ngxLogs.directory(); - Logs current page info with all require informations (URL, PATH etc.)

> this.ngxLogs.clear(); - Clears the entire console logs

> this.ngxLogs.log('Log Message from NgxLogsService'); - Logs standard custom strings as console logs

> this.ngxLogs.warn('Warning Message from NgxLogsService'); - Logs Warning meesage for custom strings as console logs

> this.ngxLogs.info('Info Message from NgxLogsService'); - Same as console logs

> this.ngxLogs.error('Error Message from NgxLogsService'); - Logs Error meesage for custom strings as console logs

> this.ngxLogs.memory(); - Logs memeory info

> this.ngxLogs.counter('Value'); - Console logs for iterations with index value 

> this.ngxLogs.table(array) - Displays array or json input as a table in console


## Angular version

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.9.

## Code integration

To use this package as a service `npm i ngx-logs` install this on the root angular project .

> Note: Don't forget to run this commend `npm i ngx-logs` on root folder or else it will throw error.
