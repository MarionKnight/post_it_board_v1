##Program features:

1. When the user clicks anywhere on the Board, a new PostIt is generated.
2. PostIt objects have a header and a content area, which is editable.
3. PostIt objects can be moved by clicking and dragging the header.
4. A PostIt can be deleted by clicking on the X in the header.
5. The content area of a PostIt is editable, even though it is not a form element like <textarea> or <input>.

## Edge cases:
* When a user clicks on a post-it, does it place the cursor within that post-it or does it frustratingly generate a new post-it? Hint: you may want to check out the event.stopPropagation() method in jQuery.
* Can you drag by the header area only? Draging by the content area might give you some headaches.