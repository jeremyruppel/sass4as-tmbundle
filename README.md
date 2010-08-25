# Sass4as.tmbundle

The Sass4as.tmbundle is a TextMate bundle with a language grammar to provide syntax highlighting for [Sass4as](http://github.com/jeremyruppel/sass4as) documents as well as a few helpful commands to use while editing them.

## Installation

	git clone git@github.com:jeremyruppel/sass4as-tmbundle.git Sass4as.tmbundle
	mate Sass4as.tmbundle
	
## Commands

**Insert Color...**

Key Activation: ⇧⌘C

This command has been blatantly stolen from the awesome [ActionScript 3 TextMate Bundle by Simon Gregory](http://github.com/simongregory/actionscript3-tmbundle). I couldn't live without it in a stylesheet package so I had to swipe it and alter it slightly.

**List Variables**

Tab Trigger: $⇥

This command presents all variables that have been declared before the caret in the document in a menu.

**Extend Class**

Tab Trigger: @⇥

At the moment, `@extend` is the only directive supported by the parser. This command will present all selectors that have been declared before the caret in the document as a menu.