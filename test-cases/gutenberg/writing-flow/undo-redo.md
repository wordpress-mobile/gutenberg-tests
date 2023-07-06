
# Undo / Redo - Test Cases

#### **Precondition**

Start on a new empty post.

##### TC002

**Known Issues**

- Undoing the insertion of characters can result in the cursor being misplaced. [#303](https://github.com/wordpress-mobile/gutenberg-mobile/issues/303)
- It is not possible to redo changes after redoing the insertion of an image into an image block. [#2499](https://github.com/wordpress-mobile/gutenberg-mobile/issues/2499)

**Undo/redo text**

- Write some text on a text based block .
- Press Undo until all new text has disappeared.
- Press Redo to see the text appear again.
