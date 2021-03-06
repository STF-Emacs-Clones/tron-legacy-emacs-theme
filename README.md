<h3 align="center">Tron Legacy Emacs Theme</h3>
<hr/>


<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/EmacsIcon.svg/120px-EmacsIcon.svg.png" />
</p>

<p align="center">
<a href="https://github.com/ianpan870102/tron-legacy-emacs-theme"><img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" alt="Maintenance"></a>
<a href="https://www.gnu.org/licenses/gpl-3.0"><img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg" alt="GPL License"></a>
<a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome"></a>
</p>

<br/>

<p align="center">Inspired by Base16-Black-Metal, Doom, Grayscale and City Lights.</p>


### Invoking the theme:


Download `tron-legacy-theme.el` and put it under `~/.emacs.d/themes/` (or `~/.config/emacs/themes/`), then add these lines to your `init.el`:

```
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
# or 
(add-to-list 'custom-theme-load-path "~/.config/emacs/themes/")

(load-theme `tron-legacy t)
```

<br>

### Customization options:

1. Setting `tron-legacy-dark-fg-bright-comments` to `t` causes the foreground to be dimmed and comments to be brighter (comments will be brighter than default foreground), as presented in the screenshot. The default value is `nil` (default foreground is brighter than the comments).

```emacs-lisp
(setq tron-legacy-dark-fg-bright-comments t)
```

2. Setting `tron-legacy-vivid-cursor` to `t` changes the cursor colour to bright golden, making it easier to spot.

```emacs-lisp
(setq tron-legacy-vivid-cursor t)
```

<br>
<br>

### Screenshots:

(left to right) Treemacs | Emacs Lisp | JSX

<img src="./screenshot1-tron.png" width=900>

<br>

(left to right) Treemacs | Emacs Lisp | JSX/HTML | Which-key

<img src="./screenshot2-tron.png" width=900>



<br>
<br>



Copyright© 2018-2020 Ian Y.E. Pan

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
