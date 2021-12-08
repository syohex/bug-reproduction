# Link containing underscores is not rendered correctly

https://github.com/jrblevin/markdown-mode/issues/671

## Specification

[Commonmark](https://spec.commonmark.org/0.30/#links) says as below. 

> The brackets in link text bind more tightly than markers for emphasis and strong emphasis. Thus, for example, *[foo*](url) is a link.

While [original markdown specification](https://daringfireball.net/projects/markdown/syntax) does not say anything about this. And current markdown implementation does not follow the rule.
