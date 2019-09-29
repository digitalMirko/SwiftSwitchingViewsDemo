# SwiftSwitchingViewsDemo
Swift - Swift SwitchingViews Demo - Demo 18 of 30

In this demo app we demonstrate how to code swift Switching Views.

There are so many interesting things within swift. This demo shows two ways to use Switching View options in an app.

As the user gets into the app they are greeted with a title label on top 'Swift UIAlertViews Demo' and view label right below
'Main View'. Then right below there are two large color filled buttons which give instructions for what to click and view. The top 
button is in a light blue color with white text color and the label 'Click for View 1'. Then right below is the next button
in a purple color with white text and the label 'Click for View 2'. The background for this view is orange. Note the 
button background colors in the app reflect the view its going to's background color in the main view and view 2.

When the user clicks the top button, they are taken to view one using the segue 'Show' transition to go from one view to
another. The view has a top title label 'Welcome to View 1' to let the user know they have arrived. Followed by a label
right below calling out the transition 'Seque using Show Transition'. Now to go back to the main screen the user clicks
the navigation control back button option on the upper left top part of the screen.

Now that we are back to the main screen. The user clicks the bottom button and is taken right into View 2. The top of the view
has a welcome label 'Welcome to View 2' with a label right below calling out the seque used 'Seque using Present Modally' to
transition over. Then right below is a large orange colored button with the words 'Click for Main View'. The return transition
is setup not via seque because we don't want to stack to many seque's and cause a crash. But in code in the view controller
for the IBAction for the button we just dismiss the transition in code which takes us back to the main screen.
        
Coming soon:<br>
Details and the screen cap images of the app in use can be found on <a href="http://digitalmirko.com/iOSApps.html">Digital Mirko</a>.

Screen Cap on a iPhone Xr device:(shown below)</br>
(Left image) (Top Row) App started.<br>
(Middle Image) (Top Row) Button Clicked 'Click for View 1' user taken to view 1.<br>
(Right image) (Top Row) Top 'Back' button clicked user taken back to main view.<br>
(Left Image) (Bottom Row) Button Clicked 'Click for View 2' user taken to view 2.<br>
(Middle image) (Bottom Row) Button clicked user taken back to main view<br>
<p>
  <img align="left" src="https://github.com/digitalMirko/SwiftSwitchingViewsDemo/blob/master/githubSwiftSwitchingViewsDemo01.jpg?raw=true" width="246"/>
  <img align="left" src="https://github.com/digitalMirko/SwiftSwitchingViewsDemo/blob/master/githubSwiftSwitchingViewsDemo02.jpg?raw=true" width="246"/>
  <img align="left" src="https://github.com/digitalMirko/SwiftSwitchingViewsDemo/blob/master/githubSwiftSwitchingViewsDemo03.jpg?raw=true" width="246"/>
  <img align="left" src="https://github.com/digitalMirko/SwiftSwitchingViewsDemo/blob/master/githubSwiftSwitchingViewsDemo04.jpg?raw=true" width="246"/>
  <img align="left" src="https://github.com/digitalMirko/SwiftSwitchingViewsDemo/blob/master/githubSwiftSwitchingViewsDemo05.jpg?raw=true" width="246"/>
  
</p>
