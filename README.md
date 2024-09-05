# NearMe-App-(UIKit)-
 # How to remove the Storyboard from the app
In Xcode.
Now, when the application is created, you will notice that you have the main storyboard that is your main storyboard, that is your actual storyboard that comes with your actual application.
Currently, it only contains one view controller and you can see that.And the default.
You also have the view controller.
Feel delicate, AB delegate and so on.
The first thing we need to do is to completely delete this particular storyboard.
We don't really need it.
The reason we don't need it is not because storyboard is bad or good.
We're not going to get into that discussion.
It's because this course is going to cover how to create apps programmatically.
Now, even though we have removed the storyboard, we still have to do a couple of different steps to
make it to work.


1 ] Let's click on the project.
And after clicking on the project, let's go to our build settings.
Now over here you can see actually let's go to info.
Sorry.And in the info.
Let's open up our application scene manifest.And open the theme configuration.
Open Application Session Roll Item zero Storyboard over here.
Let's go ahead and remove that.
There we go.
2] 
All right.
So that part is now gone.
Another thing that you will see in your main application is the OR the info list is main storyboard
file name.
We don't really need that.
Also, let's remove that also turn.
The other thing we need to do is to go to our theme delegate, and now we need to make sure that using
the theme delegate, we're able to present our route controller, which is the view controller.
So I'm going to go ahead and say window theme.
And once we have the window seen, we can go ahead and create the window.
So this will be a UI window.
Based on the window seen so we can go ahead and pass in the window theme.
We can see a window dot load view controller, that's our route controller, and that will be assigned
to the view controller.
Now, if your route controller is the navigation controller, you should probably use a navigation controller
window dot.
And now we need to make sure that this particular is making key and visible.
This is visible.
And finally, we can assign the self dot window, which is a property on line number 12 to the window
itself.
OC.
Now to see that our view controller is actually getting displayed and we are running our app without
the storyboard, we can go ahead and change the background color.
So let's go ahead and change the background color to green.
Just to see that our view controller is firing.
Let's go ahead and run it.



