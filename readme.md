# Image4j

This is a fork of the original library found on [Sourceforge](http://image4j.sourceforge.net/).

I found that on some bad input, the library will spin in an infinite loop. Since this kills our servers,
I needed to make a patch.

This bug was [logged on Sourceforge](http://sourceforge.net/tracker/?func=detail&aid=2971634&group_id=181651&atid=898055),
but there has been no progress on the issue in the intervening years. This repo adds the fix.