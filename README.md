## This is my online dev portfolio

Some notes and work-arounds I encountered for basic problems were:

- Relative linking WITHIN the page: 
    it seems Mozilla does not recogise internal links without anchor tags, also they do not recognise id="".
    So to get cross-browser linking functionality, I used both id="" and name="", and added "a" tags within divs that had internal relative links. (source:https://stackoverflow.com/questions/23282075/a-href-link-not-working)

- 