#DrupalCheck

![Build Status](https://travis-ci.org/mikebell/drupalcheck.svg?branch=master)

A simple PHP library to determine if a site is Drupal or not.

Based off the great work of [eojthebrave](https://github.com/eojthebrave) on [isthissitebuildwithdrupal.com](https://github.com/eojthebrave/isthissitebuiltwithdrupal_com).

## Install

```composer require mikebell/drupalcheck```

## Usage

```
$test = new DrupalCheck($url);
$result = $test->isDrupal();
```
