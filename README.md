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

| Shortcut        | Command                    |
|-----------------+----------------------------|
| C-enter         | New heading                |
| C-c f           | New aff flow               |
| C-c n           | New neg flow               |
| C-c c           | New card/arg               |
| C-c x           | Alternate new card         |
| C-arrow keys    | Move between headings      |
| C-/             | Undo                       |
| C-n, p, b, or f | Move down, up, left, right |

- S-tab over heading to collapse/uncollapse all
- M-arrow keys to move heading underneath point up or down (to reorder flows).
- More orgmode and orgmode table shortcuts can be found in [this reference card](http://orgmode.org/orgcard.pdf).
