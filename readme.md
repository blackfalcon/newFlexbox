#Playing with the new Flex Box
After reading [Dive into Flexbox](http://weblog.bocoup.com/dive-into-flexbox/) by [Greg Smith](http://weblog.bocoup.com/author/greg-smith/) I had to figure out how to wield this new found power. The new Flex Box spec comes with an amazing array of features that the legacy Flex Box could have only dreamed of. 

While Greg's article was awesome, it was the lack of code examples that really sent me on this quest. I hope that this repo will help in better understanding the complexities of this new CSS feature. 

##Browser support
In short, it [SUCKS!](http://caniuse.com/#search=flex) We are at this [weird tweener stage](http://css-tricks.com/old-flexbox-and-new-flexbox/) where browsers either have no support, only support the legacy version or are adopting the new version. 

As it stands, Chrome 21+ and Opera 12.1+ support the new version. Chrome requiring the `-webkit-` vendor prefix. Everyone else is either legacy or this weird hybrid of the two. 

As of writing this, it is being said that the new version will be fully supported in Firefox 20 w/o any prefixing, so that is cool. 

##Be aware of the differences
1. `-vendor-display: box;` == legacy
1. `-vendor-display: flexbox;` == hybrid stage
3. `-vendor-dispaly: flex` ==   

Just looking at the [IE 10](http://msdn.microsoft.com/en-us/library/ie/hh673531(v=vs.85).aspx) hybrid support can really make your head spin. 

While it appears that IE 10 is supporting the 