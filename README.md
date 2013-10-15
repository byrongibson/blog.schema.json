blog.schema.json
================

## Intro

[JSON schema][1] for a blog, based on the [Blogger API schema][2], describing blogs, pages, posts, comments, and users.

## Fixme

1.  Make datatypes [JSON Schema compliant][3] 
    - list -> string, or list -> array?
    - datetime -> string, or datetime -> integer (eg a Unix epoch int?) 
    - long -> integer
2.  Add "required": [] property where necessary
3.  Fill in examples
4.  Run through a validator

[1]:    http://json-schema.org/
[2]:    https://developers.google.com/blogger/docs/3.0/json/reference/
[3]:    http://json-schema.org/latest/json-schema-core.html#anchor8
