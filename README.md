<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Screenshots</a></li>
<li><a href="#sec-2">2. Installation</a>
<ul>
<li><a href="#sec-2-1">2.1. Manual</a></li>
</ul>
</li>
</ul>
</div>
</div>


# Screenshots<a id="sec-1" name="sec-1"></a>

![img](melancholy-screen-dired-mode.png "melancholy-theme in dired-mode")

![img](melancholy-screen-emmet-mode.png "melancholy-theme in emmet-mode")

![img](melancholy-screen-org-mode.png "melancholy-theme in org-mode")

# Installation<a id="sec-2" name="sec-2"></a>

## Manual<a id="sec-2-1" name="sec-2-1"></a>

Download melancholy-theme.el to the directory ~/.emacs.d/themes/.  Add this to your .emacs:

    (add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")

Now you can load the theme with the interactive function load-theme like this:

    M-x load-theme RET melancholy

<del>\*\* Melpa</del>

<del>Melancholy is available in both MELPA Stable and MELPA.</del>

<del>You can install melancholy with the following command:</del>

<del>#+BEGIN<sub>EXAMPLE</sub></del>

<del>M-x package-install melancholy-theme</del>

<del>#+END<sub>EXAMPLE</sub></del>

To load it automatically on Emacs startup add this to your init file:

    (load-theme 'melancholy t)
