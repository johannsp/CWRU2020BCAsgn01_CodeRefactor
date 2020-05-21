# CWRU2020BCAsgn01_CodeRefactor
Coding Bootcamp Assignment 1--Refactor HTML and CSS for a website

Refactor the sample Horiseon website as an exercise.  Apply some newer best
practices and correct any problems that are discovered.

Changes include:
- Change generic title "website" to "Horiseon" to match heading 1
- Replace instances of div with a specialized use with new HTML 5 tags:
  - nav
  - header
  - main
  - footer
  - aside
- In some places where either duplicate class and id attributes are defined for
unique elements, eliminate the class attribute and adjust the CSS to use the id.
- In one place (Search Engine Optimization) there a unique class with no id causing
a broken link, so change HTML and CSS to use an id attribute.
- Add alt="" to img tags and title="" for background image.
- Wrap paragraph text and flatten indentation so text is aligned to same indentation
level as the tag.
- For portability, where the copyright message in the footer uses a raw Unicode
character for a red Heavy Black Heart emoji substitute a hexadecimal HTML
entity for the character with the variation sequence code for red.

