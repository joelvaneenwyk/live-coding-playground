# Live Coding Playground

Computers are fast. Really fast. So why wait to get results from your code?

This is intended to be a very simple example of how to setup a playground for different types of source files. It is intended to be small not just because simple is nice, but also because it needs to be fast.

⚠ These playground scripts are **not** running in a sandbox environment! (e.g., container, browser, etc). That means that what you write is going to get executed immediately even when it is catastrophically broken. This means if you're not careful, you can actually do really dangerous and potentially horrible things to your computer (e.g., deleting all your files or force pushing your entire drive to your public repository). You have been warned.

To get started:

1. Install `nodemon` with `npm install -g nodemon`
2. Run `nodemon` from project directory. This will start running `playground.py` by default. As you edit `playground.py` you will see the results in the terminal.
   * To test another script just append to the end of the command e.g., `nodemon playground.bat`
