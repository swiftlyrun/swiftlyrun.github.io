---
layout: page
title: grep
docs: https://www.man7.org/linux/man-pages/man1/grep.1p.html
---
Find and print lines containing `hello` in file `./file.txt`
```bash
grep hello file.txt
```
Find and print lines containing `hello` in files in directory `./files` and it's subdirectories
```bash
grep -r hello files
```
Find and print lines containing `hello` in file `./file.txt` ignoring case
```bash
grep -i hello file.txt
```
Find and print lines containing `hello` as a seperate word in file `./file.txt`
```bash
grep -w hello file.txt
```
Find and print lines not containing `hello` in file `./file.txt`
```bash
grep -v hello file.txt
```
