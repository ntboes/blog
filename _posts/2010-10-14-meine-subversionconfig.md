---
title: Meine .subversion/config
author: Markus Tacker
layout: post
permalink: meine-subversionconfig
lang: de
categories:
  - development
tags:
  - svn
  - subversion
---
    [helpers]
    diff-cmd = colordiff
    diff-args = --ignore-all-space --ignore-blank-lines
    [miscellany]
    enable-auto-props = yes
    [auto-props]
    * = svn:keywords=Id Rev
    [auth]
    # Verhindert die Verwendung von Keychain / Keyring
    password-stores =
