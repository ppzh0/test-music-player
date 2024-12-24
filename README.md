# Experimental Music Player
In this site, I tried to play YouTube videos within the site's iframe.

## Manipulation of iframe
It is simple to understand the working of it. I had to give the anchor tag its property to `target="%iframesName%"`. By doing so, it direct the links to visit within the said iframe. 
<!-- Searched for that solution for almost 5 hours through two days. -->

## YouTube Embeds
Since giving the visitor full control of the embedded player (within the iframe) make it feels like they're watching YouTube but on a different site, I have to remove the controls.

YouTube also promotes non-related content after a video has finished. Thus, adding `rel=0` after the operator `&` to the YouTube embed URL changes the non-related recommendations into the channel's content. 

It seems that some creators on YouTube do not allow their content to be embedded. So, there is an awkward "Watch on YouTube" warning, sometimes.

## Rounded Borders
Somewhere in the past, YouTube had made a big mistake of making videos with rounded borders. It sucks, feels like child-ish, unworthy. So, I broke it by having the iframe's CSS property in default `border-radius` value of `0`.

Meaning YouTube enthusiasts can watch videos without rounded borders. (though they'd probably be using extensions for that)