# Formatting for Markdown Documents

## Creating Titles and Headers
Headers are created using the pound key, `#`, followed by a space along with the desired name for the title. The syntax should look similar to this:

``` sql
# Title-name
```

Similarly, headers for documents are created using two pound keys, `##`, followed by a space and the title of the header:

``` sql
## Header-name
```


## Bolding, Highlighting, and Italics
Bolding is done using two asterisk signs, `**` at the beginning and ending of the desired bold text:

``` sql
**Bold-Text**
```

When creating italic text, just use a single asterisk before and after the text to create italic text:

```sql
*italic-text*
```
<Mark> (Note) For bold AND italics, use three aterisks in the same format mentioned above </mark>

Highlighting can be done using the `<mark>` followed by the text, with `</mark>` following the text field. For example,

``` sql
<mark> Highlighted-text </mark>
```



Additional HTML tags can be used to further customize the text. For a full list of HTML tags, visit the following <a href= "https://www.javatpoint.com/html-tags">site</a>.

## Block Text and Lists
You can create block text around a line by using "`". For example.
```sql
`Desired text`
```

To put multiple lines in block text, use three apostrophes, followed by sql, along with the indented text. Close this with three apostrophes following the end of the block quote:

```sql
    ``` sql
    Hello World
    ```
```

To create a block quote without the gray sqaure, use `>` before the desired block quote text.

Lists are created using an ordinary listing pattern (`1.` String *followed by enter, `2.` ...). Intented subitems can be created by using the same format in between major list numbers:

```sql
1. First item
2. Second item
    1. Second item- part A
    2. Second item- part B
3. Third item
```

Unordered lists are cerated using the same pattern, except with a number or period, items have a dash (-), asterisk (*), or plus sign (+) in front of them. Again, indents are used to create nested lists.

```sql
- First item
- Second item
    - Second item- part A
    - Second item- part B
- Third item
```

## Tables
Tables can be placesd anywhere on a page and use a format like that listed below:
```sql
| Method        | Description               |
| --------------| ------------------------- |
| First item    | This is the first item    |
| Second item   | This is the second item   |
| Third item    | This is the third item    |
```
To create:

| Method        | Description               |
| :-------------| :-------------------------|
| First item    | This is the first item    |
| Second item   | This is the second item   |
| Third item    | This is the third item    |

To align the columns to the left, center, or right, palce `:` characters at the beginning or end of the divider.

eg: (Table with text in Center)
```sql
| Method        | Description               |
| :------------:| :------------------------:|
| First item    | This is the first item    |
| Second item   | This is the second item   |
| Third item    | This is the third item    |
```
| Method        | Description               |
| :------------:| :------------------------:|
| First item    | This is the first item    |
| Second item   | This is the second item   |
| Third item    | This is the third item    |

eg: (Table with text on Left)
```sql
| Method        | Description               |
| :------------ | :------------------------ |
| First item    | This is the first item    |
| Second item   | This is the second item   |
| Third item    | This is the third item    |
```
| Method        | Description               |
| :------------ | :------------------------ |
| First item    | This is the first item    |
| Second item   | This is the second item   |
| Third item    | This is the third item    |