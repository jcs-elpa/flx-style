[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![JCS-ELPA](https://raw.githubusercontent.com/jcs-emacs/badges/master/elpa/v/flx-style.svg)](https://jcs-emacs.github.io/jcs-elpa/#/flx-style)

# flx-style
> Completion style for flx

[![CI](https://github.com/jcs-elpa/flx-style/actions/workflows/test.yml/badge.svg)](https://github.com/jcs-elpa/flx-style/actions/workflows/test.yml)

The implementation is simply extracted from [company-flx](https://github.com/PythonNut/company-flx).

## 🔨 Usage

```el
(setq completion-styles '(flx))
```

Notice this will only eliminate the completion candidates! You will need to config
sorting function in order to get the sorting order respect to `flx` scoring algorithm.

## Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple)](https://github.com/bbatsov/emacs-lisp-style-guide)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
