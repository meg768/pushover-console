# Pushover Console

Intercepts messages to console and sends them to Pushover.

## Installation

````bash
npm install pushover-console --save
````

## Usage

````javascript
require('pushover-console');
````

Every call to console.info, console.warn, console.error will send a message
using Pushover.
