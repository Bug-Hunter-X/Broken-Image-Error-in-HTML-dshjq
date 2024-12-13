# Broken Image Error in HTML

This repository demonstrates a common but easily overlooked HTML error: using an `<img>` tag with a non-existent image source.  The example shows how this can lead to a broken image in the browser and provides a solution.

## Bug

The `bug.html` file contains an `<img>` tag with a `src` attribute pointing to a file named `missing-image.jpg`, which does not exist.  This results in a broken image being displayed.

## Solution

The `solution.html` file provides a corrected version by ensuring the image file exists in the same directory (or by providing a valid URL).