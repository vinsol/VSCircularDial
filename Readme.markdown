VSCircularDial
================================

VSCircularDial is an UIView enhancement which provides you a 360 degree rotating scroller.

![VSCircularDial](/vinsol/VSCircularDial/blob/master/Demo%201/sample_screenshot_1.png?raw=true)

Features
---------

1. Easy to use, just like normal UIView.
2. Fully customizable
3. Optimized for different resolutions, including iPhone, iPad and iPhone 4 (Retina Display)
4. Callbacks can be implemented to call specific methods on rotating the view.


Usage
-----

Very similar to UIView. For VSRotatingView, you can initialize with "new" method:

    VSRotatingView *rv = [VSRotatingView new];
    [view addSubview:rv];


Initial Steps:

1. Download and add the complete "VSRotatingView" folder in your project from [here](https://github.com/vinsol/VSCircularDial/tree/master/VSRotatingView).
2. You need to add three frameworks in your project - QuartzCore, AVFoundation and Security.
3. Add #import "VSRotatingView.h" to the top of view controller in which you are going to use the above code and you are ready to go.
4. Function "- (void)viewCirculatedToSegmentIndex:(NSUInteger)index;" can be called in its delegate which can be used to know when view is beeing rotated and which segment is the current selected one. 

Customizing this view is a lot simple. Variables could be modified in VSConstants.h to get desired functionality and the main image of dial can be replaced easily with image named "pain-cycle.png". Complete code can be accessed in VSRotatingView.h/.m files and full modification is possible.

Included Demo project#2 displays how you can customize this view and show a 360 degree view like the one below:

![VSCircularDial](/vinsol/VSCircularDial/blob/master/Demo%202/sample_screenshot_2.png?raw=true)
