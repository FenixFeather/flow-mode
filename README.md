flow-mode for emacs orgmode
===========================
Installation
------------
- Put flow-mode.el somewhere in your load path.
- Add ```(require 'flow-mode)``` to your init.el.
- Use M-x ```flow-mode``` to activate flow mode.

Usage
-----
Here’s some of the most useful shortcuts (C- means control, M- means alt, S- means shift):

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
<colgroup><col class="left" /><col class="left" />
</colgroup>
<thead>
<tr><th scope="col" class="left">Shortcut</th><th scope="col" class="left">Command</th></tr>
</thead>
<tbody>
<tr><td class="left">C-enter</td><td class="left">New heading</td></tr>
<tr><td class="left">C-c f</td><td class="left">New aff flow</td></tr>
<tr><td class="left">C-c n</td><td class="left">New neg flow</td></tr>
<tr><td class="left">C-c c</td><td class="left">New card/arg</td></tr>
<tr><td class="left">C-c x</td><td class="left">Alternate new card</td></tr>
<tr><td class="left">C-arrow keys</td><td class="left">Move between headings</td></tr>
<tr><td class="left">C-/</td><td class="left">Undo</td></tr>
<tr><td class="left">C-n, p, b, or f</td><td class="left">Move down, up, left, right</td></tr>
<tr><td class="left">C-c `</td><td class="left">Edit/view overflowed cell</td></tr>
</tbody>
</table>

<!-- | Shortcut        | Command                    | -->
<!-- |-----------------+----------------------------| -->
<!-- | C-enter         | New heading                | -->
<!-- | C-c f           | New aff flow               | -->
<!-- | C-c n           | New neg flow               | -->
<!-- | C-c c           | New card/arg               | -->
<!-- | C-c x           | Alternate new card         | -->
<!-- | C-arrow keys    | Move between headings      | -->
<!-- | C-/             | Undo                       | -->
<!-- | C-n, p, b, or f | Move down, up, left, right | -->
<!-- | C-c `           | Edit/view overflowed cell  | -->

- S-tab over heading to collapse/uncollapse all
- M-arrow keys to move heading underneath point up or down (to reorder flows).
- More orgmode and orgmode table shortcuts can be found in [this reference card](http://orgmode.org/orgcard.pdf).
