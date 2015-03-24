# Stratus
An open source CloudApp image hosting service.

> Hi,
>
> Your CloudApp account is changing soon. Most importantly, all free accounts will have a drop limit of 10 drops per month.
>
>The good news is that there are three easy ways to increase your limit and we have some exciting new features coinciding with these changes.

4, actually. I'll build my own.

## Thoughts

This is a holding repo. The moment this "10 image" limit hits me, I'll come back to this and build it. For any curious eyes, I'll be building it in CoffeeScript, using Hapi. It'll be a server daemon with a simple API. I'm thinking a pluggable interface for where to store the images - with defaults like "local storage" and S3. It'll probably using MongoDB to keep track of the images meta data, but won't store any images in the actual DB.

## Features
* Upload Images, get a URL for them
* Super fast and easy to use
* Install via NPM and run with 1 command (I hope)
* Test coverage
* Documented and easy API
* Optional Authentication, so you can be the only one to upload images to it.
* And lastly, I'll make a basic OS X app that does automatic image uploading from screenshots, which is really the only thing I need.

