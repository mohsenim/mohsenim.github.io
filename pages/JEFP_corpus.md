---
layout: default
---

# A Corpus of Canonical and Non-Canonical Texts

Canonical fictional texts are considered to have high cultural value and are familiar to educated members of society, and are included in school curricula. Writers of canonical texts are prestigious writers and hold strong reputation.
Although canonization is a process influenced by various stakeholders, and the reputation of canonical texts is promoted by influential sectors of society, for a text to be selected in a canon, the textual properties, reading, and readership of these texts undoubtedly play crucial roles.
Conversely, non-canonical texts do not gain recognition comparable to canonical texts, and many of them may not survive, as was probably the fate of most during the pre-digitalization era.
To analyze canonical texts in comparison to non-canonical texts, we built a corpus called the "Jena Corpus of Expository and Fictional Prose (JEFP)," which includes the two aforementioned fictional categories, canonical and non-canonical, as well as one category of non-fictional texts, which allow for inter- and intra-genre comparisons.

To classify a text as a canonical text, we considered three criteria:
    1. The text has been recognized as a canonical text in _The Western Canon: The Books and School of the Ages_ (Bloom, 1994). These texts have been extracted from Project Gutenberg in the _Corpus of Canonical Western Literature_ (Green, 2017).
    2. The author should have a high international reputation, measured by counting the number of pages the author has in the top 30 Wikipedia editions.
    3. The text should be long enough to facilitate structural analysis. We set a threshold of 35K tokens, including words and punctuation. This length allows us to apply various types of structural analysis, including long-range correlation analysis (fractal analysis).

In total, 76 canonical texts, written by 30 authors in the 19th and early 20th century, were incorporated in the The JEFP corpus, version 2.0.  The list of authors is as follows:

| Anne Bronte | Arnold Bennett | Bram Stoker | 
| Charles Dickens | Charlotte Bronte | Edgar Allan Poe | 
| Elizabeth Gaskell | George Eliot | Henry David Thoreau | 
|Henry James | Herman Melville | James Fenimore Cooper | 
|James Joyce | Jane Austen | Joseph Conrad | 
| Lawrence D.H | Louisa May Alcott | Mark Twain | 
| Nathaniel Hawthorne | Oscar Wilde | Rudyard Kipling | 
|Sinclair Lewis | Theodore Dreiser | Thomas Carlyle | 
|Thomas Hardy | Walter Scott | Wilkie Collins | 
|Willa Cather | William Makepeace Thackeray | William Morris |
The complete list of texts is published in this github repository.

The violin plot below shows that number of pages that e
<!---
Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

--->
