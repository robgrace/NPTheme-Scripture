# UnitTest

(This file needs to be moved to Notes)
Samples to check regexp syntax parsing in a variety of conditions

## Primary Link: OliveTree BibleReader 
Here are some examples:
Romans 2:3 start of line OR whitespace must precede a verse ref
    Romans 2:4 white space before verse
Another line might have a verse ref such  as Rom 3:4 in the middle of text. 
But not Romans 2 - but w/o delimiters, does not match on chapter only, since this would lead to too many false hits in other note text. 
Also, a ref like **Col3:12** without a space inbetween is not allowed (OliveTree will not parse it) 
(Col 3:12 same verse ref with space) note that parentheses is allowed
(Col 3:12) parenthesis only
john 1:34 and genesis 1:1-12, 
1Cor 3:4 numbered book test, and verse reference in the middle col 3:12 test 
1cor 3:14-16 verse range allowed, but not used in Olivetree
1cor 3:4-4:2 range spanning chapters also allowed

## Alternate link
Using delimiter (square brackets, for now) invokes an alternate link:
[Romans 2:7] Bible Gateway link (if delimited)  single verse

[ro 2:7-8] verse range

[1co 3:18-4:2] range spanning chapters

Additional syntaxes allowed (vs OliveTree):
[Romans 2] chapter-only ref - no concerns about false hits, b/c of delimiters!
[Col3:12] ref without space - WILL parse, since this works fine with Bible Gateway
