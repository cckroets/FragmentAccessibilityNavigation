# FragmentAccessibilityNavigation

Demonstration of accessibility focus not persisting across Fragment transactions.

When navigating from Activity A to Activity B, the view with accessibiltiy-focused in Activity A remains focused, after Activity B is removed is popped off the stack.

However when navigating between Fragment transactions, the accessibility-focused view in Fragment A does not remain focused after coming back from Fragment B.

<img src="https://github.com/cckroets/FragmentAccessibilityNavigation/blob/master/demo.gif" width="300">
