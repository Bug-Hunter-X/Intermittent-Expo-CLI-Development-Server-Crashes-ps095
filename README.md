# Expo CLI Intermittent Crash Bug

This repository demonstrates a bug encountered with the Expo CLI where the development server would intermittently crash without providing error messages in the console. The app would be running and then suddenly the server would terminate without any explanation. 

## Bug Reproduction

The exact cause of the crash is difficult to pinpoint because of its randomness and lack of error messages. The `expoBug.js` file provides an example of a project demonstrating this behavior.  It may be necessary to run the project for a prolonged duration to observe the error.

## Solution

The `expoBugSolution.js` file offers potential solutions and workarounds to mitigate the issue. This often involves a combination of checking for memory leaks, closely examining the console for subtle error messages (even if they appear unrelated to the app), and potentially upgrading dependencies.