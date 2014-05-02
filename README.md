 
Why do this:
````
CGRect viewFrame = view.frame;
viewFrame.size.height = 10.f;
view.frame = viewFrame;
````

When you could do this:
````
view.height = 10.f;
````
or this:
````
view.x = 0.f;
````
or this:
````
CGFloat width = view.width;
````


