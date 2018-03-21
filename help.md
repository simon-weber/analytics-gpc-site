---
---

If your question isn't answered here, shoot me an email at [simon@simonmweber.com](mailto:simon@simonmweber.com).

## Installation

* Visit [the web store](https://chrome.google.com/webstore/detail/wip-for-google-payment-ce/ghmoohfklnhjijpmpjlapalkhhbnnlam) and click the install button.
* After installation is done, click the three dots in the top right-hand corner of Chrome.
You should see the extension icon above the "new tab" button.
Right click the extension icon and select "Show in toolbar".

## Usage

* Browse to [the Google Payments Center](https://payments.google.com/payments)
* The extension icon should light up in your toolbar.
This may take up to a minute the first time, especially for accounts with a long history.
Once it's lit up, click it.
* You'll now see your data in a new tab.

## Known Issues

* Read-only accounts are not supported.
This is caused by a problem on Google's end, since these accounts are not allowed to export data through the apis the extension uses.
To work around this you'll need to either sign in with an admin account or increase the permissions on the account you normally use.

## Troubleshooting

### the extension icon doesn't light up
This is usually caused by issues when pulling your data from Google.
Reloading the extension (instructions are below) or reinstalling can sometimes solve this.
If it doesn't, send me an email with your logs and I'll look into it.


### data is incorrect or out of date
This is usually caused by caching problems, and can be fixed by flushing the cache.

To do this, visit Google Payments and click the extension icon.
Next click the "other" tab, then click "reset cached data".
After a bit of a wait, you should see a correct graph show up.


### reloading the extension
This will restart the extension without affecting your cached data. To do this:

* navigate to chrome://extensions
* uncheck "enabled" next to the extension's entry
* check "enabled" again
* refresh any existing Google Payments tabs

### viewing your logs
The extension logs all sorts of useful debugging information while running. To check the logs:

* navigate to chrome://extensions
* check "developer mode" at the top right
* click the "inspect views: background page" link under the extension listing. This will open a new window.
* in the new window, click the "console" tab

If there were errors or warnings, the top right-hand corner will have markings like  and  respectively.
If you see these, you can use the funnel button in the top-left corner and click "Errors" or "Warnings" to filter them out from everything else.

If you'd like to send me your logs, right click anywhere in the console and click "save as", then attach the file to an email.

