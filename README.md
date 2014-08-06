Automator Workflows
===================

Osx `Automator` app is very useful for creating macros and save time. This repo is a collection of the macros that I use. 

I usually create `service` workflows for system-wide services available in `Services` menu. But those files can easily be converted to apps.

Usage
-----

Just clone the repo to`~/Library/Services` folder, or copy each .workflow file to `~/Library/Services` folder.

To clone directly

    cd ~/Library/Services
    git clone https://github.com/laplacesdemon/automator-workflows.git .
    
After cloning, all you have to do is:

 * Open `Finder`
 * Find some images and highlight them
 * There is a `Finder` menu on top-left, next to apple logo. From that menu select `Services` and then select `Rename and Scale Selected Images for iOS`

You can find some additional information on my blog page: http://www.laplacesdemon.com/2012/11/02/mac-automator-for-renaming-files/

Rename and Scale Selected Images for iOS
----------------------------------------

  * Append `@2x` to the filename (i.e image.png to image@2x.png).
  * Duplicates and renames them back to original names and scale them half the size.
