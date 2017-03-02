# Atom Snippets

## Introduction

This is my personal atom snippets.cson. These are snippets of code that can be triggered by typing a particular word and then hitting tab.

For instance:

Typing `model<tab>` in a file with a `.js` extension creates the following:

```
const mongoose = require('mongoose');
const Schema   = mongoose.Schema;

const objectSchema = new Schema({

});

const object = mongoose.model('object', objectSchema);
module.exports = object;
```

with your cursor in place to change `object` to the model of your choice.

A few of these are still quite buggy, so use with caution. 

## Installation

Append the contents of this snippets.cson file to ~/.atom/snippets.cson. Have fun
