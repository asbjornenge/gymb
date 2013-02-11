# Gymb

> Github Python Markdown Blogger

Gymb is a static site generator for github pages. It is built with python and relies on [mako](http://www.makotemplates.org/) and [misaka](http://misaka.61924.nl/).

## Installation

Gymb is not yet on pypi, so for now you need to fork this repo.

	git clone ssh://repo
	cd repo && virtualenv .
	source bin/activate
	pip install -r requirements.txt
	
## Usage

Gymb will convert markdown (.md) files to html. Add a .md file anywhere withing your repo and gymb will convert it.

Gymb makes use of mako templates to wrap around your markdown content. This requires a file named *base.html* in your repo root.

Gymb can also group your articles in a *blogs* and provide those blog with content and metadata to the mako templates during build. This means you can build lists of your posts, filter on published date etc.

### gymb.json

The information about blogs and their posts is held by a file named *gymb.json* in your repository root.

It has a list of blogs and a property for each blog containing posts and metadata.

### base.html

The file *base.html* in your repository root is used by gymb to wrap around your markdown content. Gymb will pass two variables; ***markdown*** and ***config*** to your mako files.

### mako files

### Build

Th ***build*** command will look for any

### Add

### Del

### Meta

## Wishlist

* index
* tab completion


&nbsp;