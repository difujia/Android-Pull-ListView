Android-Pull-ListView
=====================

A customisable ListView that supports pull-to-do-something.

 Derived from this <a href="https://github.com/erikwt/PullToRefresh-ListView">project</a>
 
Generic pull-to-do something list view, the header view being pulled out is 100% customisable. A couple of events are triggered at appropriate time to allow customisation of header view, mainly for animations.

Quick use:

1. Create a layout xml as header container which has at least one child view (real header). 
2. Subclass PullToFireListView, customise the header in appropriate methods, see details in those methods.
3. Refresh graphic editor (eclipse), add the concrete subclass view in your layout.
4. Implement OnFireListener, set it on this view to listen to pull event.
