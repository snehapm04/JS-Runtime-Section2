# JS-Runtime-Section2

# Section 2: Custom Logging

## Overview
This section introduces a custom logging feature in the custom JS runtime. We will create a new console method, `console.sarcasm()`, that adds a timestamp and sarcasm to log messages.

## Steps
1. **Add Custom Logging**: Modify the `run_js` function to execute a new file, `runtime.js`.
2. **Implement Sarcasm Logging**: Write the `runtime.js` file to override the default console object and add the `console.sarcasm()` function.
3. **Test Logging**: Update the `example.js` file to test the custom logging feature by running `cargo run`.
4. **Get Creative**: Enhance the logging function with additional features like bold text, dynamic messages, and more.
