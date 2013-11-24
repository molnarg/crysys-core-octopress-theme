Telepítés
=========

Lásd ezt a leírást: http://octopress.org/docs/setup/

Majd:

```bash
$ git clone https://github.com/molnarg/crysys-core-octopress-theme.git .themes/core
$ rake install[core]
$ rake new_page[index.html]
$ rake new_page[CTFs]
$ rake new_page[Members]
$ rake new_page[Security Challenge]
$ rake new_page[About]
```

Blog posztok hozzáadása
=======================

```bash
$ rake new_post["Poszt címe"]
```

Előnézet
========

```bash
$ rake preview
```

Oldal legenerálása
==================

```bash
$ rake generate
```

A kész oldal a `public` mappában lesz.
