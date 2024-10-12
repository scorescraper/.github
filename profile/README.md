# Welcome to the Scorescraper Github!
### Created by [Zach Lieberman](https://github.com/zachgliebs), [Mikey Evarts](https://github.com/hieyou1), and [Sam Schwartz](https://github.com/shwami67)

## What is Scorecraper?
Scorescraper is a program that runs inside of node.js. It was originally created to pull highschool football data, but has since been adapted to pull football data from not only highschool, but also College Football (D1) and NFL.
## How does Scorescraper work? 
We uitilze many plugins within [node.js](https://nodejs.org/en). Many of which can be found in the following code block:
```ts
import fetch from "node-fetch"; // A Node.js implementation of the browser's fetch API.
import { readFile, writeFile } from 'fs/promises'; // Asynchronous file system operations for reading and writing files.
import { JWT } from 'google-auth-library'; // Handles JWT authentication for Google's API services.
import { GoogleSpreadsheet, GoogleSpreadsheetCell } from 'google-spreadsheet'; // API to interact with Google Spreadsheets.
import { DateTime } from 'luxon'; // A library for working with dates and times.
```
With these plugins, along with the plenty of other code, we are able to pull data, and format it into a csv (a google sheet). The current use case for this is to display these scores on our local highschool display board by using a software called [VMIX](https://www.vmix.com/) (not associated).

Here is an image of the code in action!

![IMG_8235](https://github.com/user-attachments/assets/4111c455-e5fb-4d53-b1aa-a3c5f963fbe4)


## How can I support this amazing project?
In total, ***around 45+ hours*** has been put into this project! You can support the Scorescraper team by [**buying us a coffee**](https://buymeacoffee.com/scorecraper) (*all profits are split evenly amongst the 3 members*)

## How do I submit my requests and/or see the current progress of the project?
If this is running through your mind at the moment, then we have the solution for you! Feel free to email us at [contact@scorescraper.live](mailto:contact@scorescraper.live)

## How do I use Scorescraper?
For more information, contact us at the email above!
