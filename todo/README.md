# Flutter Tips

1. In flutter, almost everything is a widget like alignment, padding and layout.

2. Scaffold widget, from the Material library, has a default app bar and 
and a body property that holds the widget tree for the 
home screen.

3. A widget's main job is to provide a build() method
that describes how to display the widget in terms of other, lower level
widgets.

4. StatelessWidgets are pretty simple. They have only one class that returns a Material App 
and it has title and a Scaffold that has [app bar and body]

5. ontap: setstate() triggers a call to the build() resulting in an update to 
the ui

6. add a new page, navigate to it via a route

7. navigator manages a stack containing the app's routes
pushing a route to the stack updates the display to the route
popping a route brings us back to the previous screen



process is:
add a list
add an icon ,
set a state,

we shall add a list icon(in the appbar), when user taps it, a new route
containing the list of saved favourites is pushed onto the stack
displaying the icon.

* press r to hot reload *
