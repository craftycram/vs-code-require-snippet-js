<h1 align="center">Visual Studio Code - JavaScript Snippet</h1>
A snippet to speed up your workflow in JavaScript.

## Installation
1. Open `Visual Studio Code`.
2. Open the `Command Palette... ` (<kbd>⌘ Command</kbd>+<kbd>⇧ Shift</kbd>+<kbd>P</kbd>).
3. Enter `Preferences: Configure User Snippets`.
4. Confirm with <kbd>Return</kbd>.
5. Enter `javascript` and confirm with <kbd>Return</kbd>.
6. Copy and paste the code below.

## Usage
This snippet makes creating the basic HTML structure easy.
1. Create a `.json` file
2. Enter `req` and hit <kbd>Return</kbd>.
3. The snippet completes the require statement.

You can also use <kbd>⇥ Tab</kbd> to jump to the next placeholder.

## Code
```json
{
    // Example orgiginally by Visual Studio Code:
	// Place your snippets for javascript here. Each snippet is defined under a snippet name and has a prefix, body and 
	// description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
	// $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the 
	// same ids are connected.
	// Example:
	// "Print to console": {
	// 	"prefix": "log",
	// 	"body": [
	// 		"console.log('$1');",
	// 		"$2"
	// 	],
	// 	"description": "Log output to console"
	// }
	"require": {
		 	"prefix": "req",
		 	"body": [
				"const $1 = require('$2');$0",
			],
			"description": "import dependencies - by Marc Rufeis"
		}
}
```
