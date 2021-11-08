There are a few ways to do this, but one way is to keep track of a `boolean` value named 'added'. If you add the value
to the list in the `while` loop, change `added` to `true`. If you get out of the `while` loop and `added` is still 
`false`, you know you need to add it at the end of the list.