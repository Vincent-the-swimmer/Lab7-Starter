Names:
<br>
Vincent Gao
<br>
Joseph Kim
1) The tests would be run within a Github action that runs whenever code is pushed because these tests should make sure that any code that is to be merged with the main branch won't break the code. Along with that, if code is pushed regularly, it allows for code to be tested consistently and not all at once.
2) No
3) What is the difference between navigation and snapshot mode?
Navigation simulates a user going to the page and analyzing how long the website takes to load fully. This is good for testing the full page's performance. Snapshot, on the other hand, doesn't reload the page and instead uses it at that moment to check for accessibility and best practices.
4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
- According to navigation mode, we can save 464.4 KiB of data if we were to properly size our images. We could use WebP to save storage 
- We can include "lang" attributes to our html in order to improve accessibility. According to the warning, "If a page doesn't specify a lang attribute, a screen reader assumes that the page is in the default language that the user chose when setting up the screen reader. If the page isn't actually in the default language, then the screen reader might not announce the page's text correctly."
- We can utilize a `<meta name="viewport">` tag with `width` or `initial-scale`. According to the page, "A `<meta name="viewport">` not only optimizes your app for mobile screen sizes, but also prevents a 300 millisecond delay to user input."