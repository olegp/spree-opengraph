# Open Graph

This is an extension that adds Facebook Open Graph support to Spree product pages. This includes the relevant tags in the HEAD as well as the Like button on the product pages.

## Install
      script/extension install git://github.com/olegp/spree-opengraph.git

You'll also need to modify your spree_application.html.erb to include the following opening tag attributes:

      <html xmlns="http://www.w3.org/1999/xhtml" 
        xmlns:og="http://opengraphprotocol.org/schema/"
        xmlns:fb="http://www.facebook.com/2008/fbml">


## Status
Work in progress, but please do give it a go.


