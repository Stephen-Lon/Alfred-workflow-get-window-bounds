# Alfred-workflow-get-window-bounds
Get position &amp; dimensions of topmost window.

This workflow simply obtains the position and dimensions of the topmost window and saves those to the clipboard. It is useful if you are writing an Alfred workflow and want to place a window precisely using the `Set Custom Window Bounds` Automation Task. Set up that window as you want it and then run this workflow to obtain the relevant details to transfer to the Automation Task in the other workflow.

To run the workflow:

- Ensure you have topmost the window the position and dimensions of which you want.
- Type the keyword (the default is `getwin` but you can change it opposite) and press <kbd>↩︎</kbd>.

Note that the final notification will include the name of the application owning the topmost window—as a basic check that you have run the workflow on the correct window.
