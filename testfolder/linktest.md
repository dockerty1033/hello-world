# Test of links in Markdown.

Normal link [link text](test.md)

Empty link text [](<https://www.lmgtfy.com/>)
- even though I don't get an error, the link doesnt' show; I was hoping the link destination would be filled in as the link text :-(

Link with spaces in url [link to "test md with spaces"](<test md with spaces.md>)

Autolink <https://github.com/dockerty1033/hello-world>

## More tests
Link with markdown inside link text
- looks like italic or bold work, but not headings

[_Let me Google that for you_](lmgtfy.com)\
[__Let me Google that for you__](lmgtfy.com)\
[## Let me Google that for you](lmgtfy.com)\

What about a link on a header line?
### Test header [search](duckduckgo.com)
### [search2](lmgtfy.com)

What about a link to a section? [Top](linktest.md#test-of-links-in-markdown)

## Reference links

Found on <https://stackoverflow.com/questions/24580042/github-markdown-are-macros-and-variables-possible>, 2nd answer.\
Which points to <https://github.com/biserkov/markdown-playground/blob/master/README.md>

### markdown-playground

First Header  | Second Header | Third Header
------------- | ------------- | -----------
[oneone][11] | [12] | [13]
[21] | [twotwo][22] | [23]
[31] | [32] | [three trees][33]

[11]: http://www.a-big-long-big-big-long-hyperlink/more-long-stuff?id=11
[12]: http://www.a-big-long-big-big-long-hyperlink/more-long-stuff?id=12
[13]: http://www.a-big-long-big-big-long-hyperlink/more-long-stuff?id=13
[21]: http://www.a-big-long-big-big-long-hyperlink/more-long-stuff?id=21
[22]: http://www.a-big-long-big-big-long-hyperlink/more-long-stuff?id=22
[23]: http://www.a-big-long-big-big-long-hyperlink/more-long-stuff?id=23
[31]: http://www.a-big-long-big-big-long-hyperlink/more-long-stuff?id=31
[32]: http://www.a-big-long-big-big-long-hyperlink/more-long-stuff?id=32
[33]: http://www.a-big-long-big-big-long-hyperlink/more-long-stuff?id=33
