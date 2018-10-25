# markdown-best-practices
ref: https://docs.cloudposse.com/development/markdown/best-practices/

Markdown Best Practices
Using Markdown is essential for clear communication on mediums such as GitHub, Slack or just plain text. Here are some of our recommendations on when to use certain conventions.

EDIT THIS PAGE
Markdown Logo

MARKDOWN CHEATSHEET 
If you’re new to Markdown or need a refresher, check out our Markdown cheatsheet.

Code Blocks 
Use code blocks for anything more than 1 line. Use code for inline code, filenames, commands, etc.

Code Block 
```
# This is a code block
```
Table of Options 
Use tables to communicate lists of options.

Here’s an example:

Table of Options 
| Name       | Default | Description                                | Required |
|:---------- |:-------:|:------------------------------------------ |:--------:|
| namespace  |         | Namespace (e.g. `cp` or `cloudposse`)      |   Yes    |
| stage      |         | Stage (e.g. `prod`, `dev`, `staging`)      |   Yes    |
| name       |         | Name  (e.g. `bastion` or `db`)             |   Yes    |
| attributes |   []    | Additional attributes (e.g. `policy`)      |    No    |
| tags       |   {}    | Additional tags  (e.g. `map("Foo","XYZ")`) |    No    |
:--------: should be used for “Default” and “Required” values
:--------- should be used for all other columns
Use value for all values
Which will render to something like this:


Example Markdown Table Rendering 

Example Markdown Table Rendering 
Feature List Formatting 
Use this format describe the features & benefits.

Feature List Example 
1. **Feature 1**** - Explanation of benefits
2. **Feature 2**** - Explanation of benefits
Use Block Quotes 
Reference copyrighted text, quotes, and other unoriginal copy using >

Block Quote Example 
> Amazon Simple Storage Service (Amazon S3) makes it simple and practical to collect, store, and analyze data - regardless of format – all at massive scale.
