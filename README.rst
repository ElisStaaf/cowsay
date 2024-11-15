Cowsay
======
.. image:: https://img.shields.io/badge/Build%20(fedora)-passing-2a7fd5?logo=fedora&logoColor=2a7fd5&style=for-the-badge
   :alt: Build = Passing
   :target: https://github.com/ElisStaaf/cowsay
.. image:: https://img.shields.io/badge/Version-1.0.0-38c747?style=for-the-badge
   :alt: Version = 1.0.0
   :target: https://github.com/ElisStaaf/cowsay
.. image:: https://img.shields.io/badge/Language-Perl-grey?logo=c&logoColor=white&labelColor=007cff&style=for-the-badge
   :alt: Language = Perl
   :target: https://github.com/ElisStaaf/cowsay

This is just another cowsay ripoff to be honest... Cowsay is a thing that makes the cow... Say!
E.g if I were to run "cowsay.pl" with the flag "Hello World!", the program world print:

::
    ______________
   < Hello World! >
    --------------
           \   ^__^
            \  (oo)\_______
               (__)\       )\/\
                   ||----w |
                   ||     ||

Requirements
------------
* `perl`_
* `git`_ or `gh`_

Installation
------------
To install, clone the repo:

.. code:: sh

   # git
   git clone https://github.com/ElisStaaf/cowsay ~/cowsay

   # gh
   gh repo clone ElisStaaf/cowsay ~/cowsay

   # Add to path (optional)
   "export PATH=\"\$PATH:$HOME/cowsay\"" >> "~/your/shell/rc"

.. _`perl`: https://learn.perl.org/installing
.. _`git`: https://git-scm.com/downloads
.. _`gh`: https://github.com/cli/cli#installation
