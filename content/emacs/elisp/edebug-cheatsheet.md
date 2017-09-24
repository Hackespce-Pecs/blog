# Edebug Cheatsheet #

Advices, interactive function names and their associated hotkeys, which are specific to our [Emacs configuration](https://github.com/AttilaVM/.emacs.d).

## You should know

* Emacs Basics
* Debugging in general

## Advices

You can remove instrumentation from a definition with reevaluting it. C-x e

When a result of an evalutation can not fit in the minibuffer or you want to search in it, check the *\*Messages\** buffer.

## Hotkeys

| Hotkey | Function name | Description |
|--------|--------|------:|
|  \<prefix\> d i  |  edebug-mode  |  Activate edebug to set break-points  |
|  \<prefix\> d f  |  edebug-defun  |  Break when evaluating function at point  |
|  ?  |  edebug-help  |  Display help menu, which is not verbose enough for a beginner  |
|  b  |  edebug-set-breakpoint  |  Set break-point at stop point or after point  |
|  u  |  edebug-unset-breakpoint  |  Unset break-point at stop point or after point  |
|  x  |  edebug-set-conditional-breakpoint  |  Set conditional break-point.  |
|  B  |  edebug-next-breakpoint  |  Move point to next break-point  |
|  w  |  edebug-where  |  Jump the point where the debugger is stopped  |
|  n  |  edebug-next-mode  |  Evaluate next the expression  |
|  g  |  edebug-go-mode  |  Continue until the next break-point  |
|  c  |  edebug-continue-mode  |  Pause one second at each breakpoints  |
|  t  |  edebug-trace-mode  |  Pause one second after every evalutation   |
|  s  |  edebug-stop  |  Stop debugger   |
|  d  |  edebug-backtrace  |  Display backtrace in new buffer   |
|  r  |  edebug-previous-result  |  Redisplay last result   |
