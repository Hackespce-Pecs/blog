# Modern Elsip development  #

Maybe one of the most important advice which I can give that you should not realy on built-in Elisp functions when modern third party libaries available for your problem, and thanktfully they do.

The main reason is that elisp has its roots in Great Academical era of computer science, eons have passed since, and of course elisp has been continuisly developed, but for the arguable sake of backward compatiblity its namings are not revisited. So if you are not a sage informatican from the USA acedmic milieu with fitting arcane knowaladge, you brain will jamed by deprecated functions names like *car* which is function that returns the first item from a list.

[dash](https://github.com/magnars/dash.el) is modern list API for Emacs and more. It brings a bit of Clojure to your Elsip, which one of the most powerfull lisp dialect, and perhaps the most elegant dynamicly typed language.

[s.el](https://github.com/magnars/s.el) is a versitale and convinient string manipulation libary

[f.el](https://github.com/rejeep/f.el) is a powefull file i/o and path manipulation libary
