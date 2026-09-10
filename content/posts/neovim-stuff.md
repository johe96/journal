+++
title = 'Neovim Stuff'
date = 2026-09-10T18:04:29+02:00
draft = false
+++

## Do you need to search and replace something QUICK?

easy, just do:
```
:%s/>>insert_word_here<</>>insert_replacement_here<<
```
optionally add ``gc`` at the end like this ``>>insert_replacement_here<</gc``

this will prompt you to choose whether or not to search and replace a word in your file
