## This is my online dev portfolio

Some notes and work-arounds I encountered for basic problems were:

- Relative linking WITHIN the page: 
    it seems Mozilla does not recogise internal links without anchor tags, also they do not recognise id="".
    So to get cross-browser linking functionality, I used both id="" and name="", and added "a" tags within divs that had internal relative links. (source:https://stackoverflow.com/questions/23282075/a-href-link-not-working)

- The Hamburger Nav dropdown using only CSS:
    In order to achive a drop-down menu using only vanilla CSS, I used the 'input' element with a 'checkbox' attribute. This is a common element used in forms that allowed me to reveal a dropdown nav menu when the checkbox was 'checked'. All that needed to be done to substitute the checkbox with a hamburger menu icon was to position the icon over the box then set its display to none.
