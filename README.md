# Tailwind CSS Active State Bug
This repository demonstrates a bug where the `active` state in Tailwind CSS does not apply correctly.  The expected behavior is for the background color to change to green when the element is actively pressed. However, only the hover state functions as intended.

## How to Reproduce
1. Clone the repository.
2. Open `bug.js` and run the code.
3. Observe the behavior when hovering and clicking the div.

## Solution
The solution involves ensuring that the necessary CSS transitions are in place for the active state to take effect. The updated code is in `bugSolution.js`.