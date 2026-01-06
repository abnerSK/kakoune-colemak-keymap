Kakoune features a thoughtfully designed and highly mnemonic keymap that prioritizes efficiency. This VS Code keybinding configuration enables navigation without sacrificing comfort for Colemak typists. 
Basically, it maps the core movement commands—akin to Vim’s or Kakoune’s HJKL—to keys on the right-hand home row(HNEI). This allows Kakoune Colemak users to keep their fingers in the optimal typing position while maintaining rapid navigation. 


🟠: modified

<table><thead><tr><th>Key</th><th>Description</th><th>ALT&nbsp;+&nbsp;key</th><th>CTRL&nbsp;+&nbsp;key</th><th>g&nbsp;key&nbsp;(goto)</th></tr></thead><tbody>
<tr><th>j</th><td>🟠join lines and select spaces</td><td>join lines</td><td></td><td>buffer bottom</td></tr>
<tr><th>J</th><td></td><td></td><td></td><td></td></tr>
<tr><th>k</th><td>🟠insert before selected text</td><td>🟠select inner object</td><td>redo last selection change</td><td>buffer top</td></tr>
<tr><th>K</th><td>🟠insert at line begin</td><td></td><td/><td></td></tr>
<tr><th>l</th><td>🟠select to next word end</td><td>🟠select to next WORD end</td><td></td><td>line end</td></tr>
<tr><th>L</th><td>🟠extend to next word end</td><td>🟠extend to next WORD end</td><td/><td></td></tr>
<tr><th>h</th><td>move left</td><td>select to line begin</td><td>undo last selection change</td><td>line begin</td></tr>
<tr><th>H</th><td>extend left</td><td>extend to line begin</td><td/><td></td></tr>
<tr><th>n</th><td>🟠move down</td><td></td><td/><td></td></tr>
<tr><th>N</th><td>🟠extend down</td><td></td><td/><td></td></tr>
<tr><th>e</th><td>🟠move up</td><td>🟠keep selections matching given regex</td><td>redo last selection change</td><td>buffer end</td></tr>
<tr><th>E</th><td>🟠extend up</td><td>🟠keep selections not matching given regex</td><td/><td></td></tr>
<tr><th>i</th><td>🟠move right</td><td>🟠select to line end</td><td>jump forward in jump list</td><td>line begin (non blank)</td></tr>
<tr><th>I</th><td>🟠extend right</td><td>🟠extend to line end</td><td/><td></td></tr>


Usage: Copy the following code to your VSCode keymap shortcuts JSON file.
