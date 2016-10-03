## ITMD 361, Production Problem 3: Relative Units in CSS

For this production problem, you will be doing some math using the formula we talked about in class
on September 21. Specifically,

    target ÷ context = result

Remember that, by default, most browsers set 1em = 16px.

You’ll then use that to compute the values for the CSS styles below.

1. Convert the base font-size listed here from pixels to ems:

      html {
        font-size: 1.1875em; /* 19px div 16 */
      }

2.  Convert the base font-size listed here to ems, and set the line-height in ems accordingly:

      html {
        font-size: 1.0625em; /* 17px div 16 */
        line-height: 1.4118em; /* 24px div 17 */
      }

3. Set the padding for this page to 12px on top and bottom, and 6px on left and right. Express in
ems:

      html {
        font-size: 1.125em; /* 18px div 16 */
        padding: 0.6667em, 0.3334em; /* 12px div 18 , 6px div 18 */
      }

4. Consider the following CSS. Assuming a browser with its base size at 1em = 16px, how big is h2,
in pixels?

      html {
        font-size: 1.125em; /* 18px div 16 */
      }
      figure {
        font-size: 0.888em; /* 16px div 18 */
      }
      figure h2 {
        font-size: 1.4375em; /* 23px div 16 ; h2 equals 23px*/
      }
