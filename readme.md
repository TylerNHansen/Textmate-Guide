#Everything I wish I knew about Textmate

1. Learn shortcuts as much as you possibly can. You will make typing mistakes, which will cause bugs you have to go back and fix. Less typing means fewer typing mistakes. It's also a lot more obvious when you enter the wrong shortcut than when you miss a parenthesis.

2. Command-T opns a dialog box to search for filenames in the current directory. Searching for 'ade' will match the file called 'abcdefg'. You can use '/' to specify searching through folders. If you learn one keyboard shortcut for rails, learn this one - opening app/assets/javascripts/models/comment.js by typing "command-T scripts/mod/comm" is much easier than trying to dive the folder structure.

3. Command-control T opens a similar dialog box to search through keyboard shortcuts. This is context sensitive - if shows javascript shortcuts in a javascript file, and ruby shortcuts in a ruby file.

4. Command-[ and Command-] adjust tabs in and out. No more moving to start or end of line.

5. Option or Command - arrows moves by "chunks" instead of letters. Option is word/paragraph, command is line/file.

6. Many commonly used patterns are stored in "snippets", which you can use by typing the name and then hitting tab. There are many snippets. Use control-command-T to find them. If you do something twice in as many minutes, there's probably a snippet for it. If there isn't, use control-option-command-B to open up a list of all snippets, command-N to bring up the dialog to add things, and the down arrow key to select "snippet". Use the word you want to trigger it with as the tab trigger, and type the text in the area underneath.

7. You can put multiple cursors, and pressing keys will do the same thing at both cursor locations. Hold down command while clicking to put more cursors down. Cursors can select multiple areas as well. So if you have a bunch of words you want to put in quotes, hold down command, double click them all, and hit " to quote them all.

8. Command-L opens up a dialog box for specifying cursor location. You can use - to indicate a range of lines, and & to specify multiple cursor locations.

9. Control-W will add to your selection the next piece of text that matches your current selection.

10. Control-Shift-O opens a terminal window in the current directory.

11. Autocompletes the current word based on the code you've written so far.

12. Ruby's # snippet and `# =>` marker. It's very, very useful. At the end of a line of ruby code, put in a `# =>`. Then, you can execute and update the markers with your ruby code, using the control-option-command-E shortcut. It puts what the code does right next to what the code is, which makes it much easier to reason about. Remembering things as you switch contexts is 90% of the difficulty of Angry Birds, and this chops that off at the root. Plus, fewer keystrokes.