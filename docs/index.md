
## Project Materials

- [project-instructions](./project-instructions.md)
- [your-files](./your-files.md)
- [module](./module/index.md)
- [glossary](./glossary.md)
- [api](./api.md)


## Overview

This project applies a list of stock earnings call scheduled times and creates a folder for each.
Various loops are used in the code but I was able to only select the one I wanted in the main function.

The project demonstrates:

- for loops from a list
- while loops
- conditional logic
- automated file creation
- interacting with the different function blocks

## Program Intent

The intent of the program is to create folders for each of the company stock tickers and their next earning call time.  It also includes if it is premarket or postmarket.
  -this list can be used in the future to add data/information to help build patterns
  -the file name also includes the date and time for ease of scheduling

## How to Run

```shell
uv run python -m datafun.app_jcarne_stocks

## Output Example
Text file example
  -AAPL - Apple - ~Jul 30, 2026 - After Close

##Findings

The current state of the project shows how easy you can use AI to gather a list of dates and times; format it into a copy and pastable text.  Then all you need to do is import the list into your code, make sure you variables and conditions are set correctly to make a file for each of the items.  If the list is large it would be a better approach to create a seperate text file that the code can reference.
