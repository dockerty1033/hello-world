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
# Test header [search](duckduckgo.com)
