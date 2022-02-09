### Adding and removing with ListIterators

Expected time required: 20 min

You're creating an app that keeps track of your Amazon wish list. You want to be able to safely add and remove items
from your list using a `ListIterator<E>`. The `WishListItem` class is already created for you with a constructor to initialize
all new wish list items. Implement the following four methods in the `WishList` class to successfully add and remove
items from your wish list!

* `addLast()` : accepts a `List<WishListItem>` and a `WishListItem` and adds the item to the end of the list.
* `addAtIndex()` : accepts a `List<WishListItem>`, a `WishListItem`, and an index and adds the item at the given index. If the given index
    is out of bounds, add the item to the end of the list (i.e. if there are 3 items in the list and the given index is 6,
    add the item to the end of the list).
* `removeAll()` : accepts a `List<WishListItem>` and safely removes all items from the list.
* `removeItem()` : accepts a `List<WishListItem>` and an item and removes that specific item from the list.

Once these methods are properly implemented, you should be able to pass all of the tests in the `WishListTest` class.

HINTS:
* [I'm having difficulty knowing when to add the item to the end of the list in the addAtIndex method.](./hints/hint-01.md)
* [How do I delete a specific item in the removeItem method?](./hints/hint-02.md)
