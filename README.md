Cocomotion
==

Example project for [RubyMotion](http://rubymotion.com) and [Cocos2d](http://cocos2d-iphone.org)

The following changes were made:

* Removed Resources/templates/tools folder to get the repo size down
* cocos2d-iPhone had its project's "treat warnings as errors" setting turned off since this version of cocos2d has some iOS6 deprecation warnings keeping it from building.

Known Issues
==

* inline functions are not yet supported, such as `ccc4()` This is a known bug with RubyMotion and will be fixed in a patch soon

## WHO IS RESPONSIBLE FOR THIS ATROCITY?

Sean Scally
[twitter](http://twitter.com/s_scally)
[github](http://github.com/anydiem)

Ricardo Quesada
[github](https://github.com/ricardoquesada)

The fine folks at Cocos2d-iPhone and RubyMotion!

## Discomfortingly Optimistic To-Do List

* Create CocoaPod
