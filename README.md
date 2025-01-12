# Tailwind CSS Bug: Misspelled or Non-Existent Class

This repository demonstrates a common but easily overlooked error in Tailwind CSS: using a class name that doesn't exist in your configuration or has a typo.

## Bug Description
The bug occurs when an incorrect class name is used.  This can lead to a lack of styling or unexpected behavior, and is difficult to debug without a careful review of the class names.

## How to Reproduce
1. Clone this repository.
2. Examine `bug.js`. You'll see a `div` with a Tailwind CSS class.  The class name may be intentionally misspelled or may reference a class that's not defined in your `tailwind.config.js` file.
3. Run the code. Observe that the div will not be styled correctly.

## Solution
The solution is simple: Ensure that all Tailwind CSS classes are correctly spelled and exist within your configuration or that you have imported the required modules if needed.  Utilize a linter for this purpose.

## Bug Solution
Examine `bugSolution.js`.  The correct Tailwind class has been used, resulting in proper styling.