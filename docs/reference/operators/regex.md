---
title: Regex operators
sidebar_label: Regex
description: Regex operators reference documentation.
---

This page describes the available operators to assist with performing pattern
matching via regular expressions.

## ~ (match)

`string ~ regex` - matches `string` value to regex

`symbol ~ regex` - matches `symbol` value to regex

[java.util.regex](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/regex/Pattern.html)

## !~ (does not match)

`string !~ regex` - checks if `string` value does not match regex

`symbol !~ regex` - checks if `symbol` value does not match regex

## regexp_replace (replace)

`string regexp_replace regex` -  replaces a sequence of characters in a string with another set of characters using regular expression pattern matching

`symbol regexp_replace regex` - replaces `symbol` value to regex