# Xtext grammars
A collection of useful and common Xtext grammars

### Templates.xtext

This grammar contains rules and terminals to implement templating languages and interpolated strings. It allows to declare the following expressions:

- `«This is text «{"Java".length + 5}»»`
- `[This is text <% "Java".length + 5 %>]`
- `«This is text ‹"Java".length + 5›»`
- `'This is text {"Java".length + 5} it also allows to escape chars \{hi!}'`

In order to reproduce the examples, comment and uncomment terminal rules depending on the desired characters.

This grammar has been extracted and adapted from [Eclipse BeeLang's grammar](http://git.eclipse.org/c/b3/b3.git/tree/org.eclipse.b3.beelang/src/org/eclipse/b3/BeeLang.xtext)
