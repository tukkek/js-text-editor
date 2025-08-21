# Java-script text-editor
*Manipulate text via Java-script*!

The JS Text-editor lets you easily interact-with and modify text in your browser, making it easier to perform some operations that would other-wise require macros; stand-alone scripts with IO operations;  complicated BASH piping; or unreadable regular-expressions. Paste your text; write a few lines of code; and copy the result back to where you need it in a minute, needing only a browser-tab to do it!

Unlike any IDE or RTE plug-in, it can also be used any-time; any-where. You can even down-load it as a self-contained HTML file for off-line use!

Access it at https://tukkek.github.io/js-text-editor/.

Down-load stand-alone file (right-click and save-as), https://raw.githubusercontent.com/tukkek/js-text-editor/refs/heads/main/index.html.

## Usage
The code-panel defines a function that receives 2 models of the text from the left-panel:
* `lines`, which is an array of the text as split by new-lines
* `text`, the raw-text as a string

Either or both parameters can be used and the function should return the text to be out-put. That result can then be copied to the clip-board for external-use or sent to the left-panel for further editing.
