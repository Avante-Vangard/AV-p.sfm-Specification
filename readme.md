Introduction to P.SFM
==============


Basic tag types in p.sfm.
---------------------------

Tags in p.sfm fall into several broad categories of tags: meta tags, line tags, word tags, note tags and figure tags. 

**Meta tags** are information markers. These tags provide information to the translation team, publisher and editing tools. These tags and their contents don't get translated the way line and word tags do, but are intended to be instructions in p.sfm language and english or source language to accomplish the project. within the p.sfm editor, meta tags appear as line tags, but within the formatted display, they are hidden information or are transformed into their marked up form.
**Line tags** or paragraph markers are the basic unit in p.sfm. each 'line' or paragraph begins with a line tag, and ends with a line ending. These are grouped into several classes: Body text, poetic text, lists, peripheral text, title text, outlines, and more. 
**Word tags** or character markers occur in pairs, marking the boundary of formatting or other word breaks. Word tags can be for semantics (what it means in the work), or markup (what it should look like) or even provide meta tag placement (insert meta information or pointers to such at the word level.) 
**Note tags** or annotation markers also occur in pairs, and contain the annotation. Within the editing program these annotations appear in the line where they apply, set off by background color, but in the final form, they appear as footnotes, endnotes, columnar notes, callouts, or hyperlinks. 
**Figure tags** or illustration markers assemble multiple tags, some normal word and line tags as well as special tags for building tables and illustration frames.

Numbered tags
-----------------

Some USFM markers include an optional numeric variable, which is represented in this documentation by a hash character #, but in most cases are listed out for all numbers. 

In USFM the number indicates:

- A portion of a complete element, or relative weighting of the “pieces” of the elements, such as ∖id1, ∖id2, ∖id3 which are all parts of the ∖id line. 
- The level of division (hierarchy). For instance ∖mt1 is for a large portion of the work or the whole work, while ∖mt3 is used for individual chapters. 
- The level of indentation relative to other like elements, as in poetry ∖q# or lists or outlines .

**Number null and zero tags**

The null tag (∖tag) vs. prime tag (∖tag1) — in p.sfm, the null (unnumbered) version of a tag is the "top level" tag, above the "zero" tag, above the prime (1st) level. the null marker may be used alongside any of the numbered tags in this heirarchy: (null), 0, 1, 2, 3, 4, 5, 6, 7, 8, 9. Be aware that null tags of the tag produce different output than the prime tag. for line indentation, the null likely will center the line instead of indenting it. For tags with heirarchy, the null tag is likely visibly larger or heavier than the prime tag. For tags that apportion, the null is the entire line, complete with the field boundaries.
