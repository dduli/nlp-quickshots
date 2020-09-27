# To correctly parse HTML pages into text pieces


It helps to ignore inline formatting when parsing texts from htmls. For example
```
<div><em>I</em> am a <u>highschool teacher</u> working at <a href="http://abc.com">Wolfgang High School</a></div>
```
It will ignore these boundaries and can correctly parse the full sentence. The
end result is a collection of text pieces.
