# Simpler Apps Framework (or SA)

Simpler Apps (or SA) is a minimal framework that encourages you to build your application with your own components (or use existing component library). Coding with HTML, CSS, templates, etc. is considered "runtime code" needed for the components to operate, but should not really be the "finished" code. The components can vary from full page to small widgets, action components, data manipulation elements, etc.

Once you develop your application, you can copy all the component JavaScript files and resources into the PhoneGap "/www" directory. You can then build your PhoneGap application as a native Mobile App that you can test on simulators and install through the App Stores. You can also test your pre-built app on browsers with different types and sizes.

The entire SA app is built with components called Adaptive Mobile Components (more on this below). The initial loading is done via a call to "SA.loadComponent()" call in index.html to load the "Main" component. Once loaded, the entire application is constructed based on other referenced components

### What are Adaptive Mobile Components?

Adaptive Mobile Components (AMC) are components built with JavaScript and define within its local namespace all the UI elements and the controller logic needed to interact-with and/or render per device specification (patent filed). The adaptability is part of the components' architecture where it is designed as Responsive to the component level as well as changing its behavior based on usability and the device it runs on. For example, the "CodeTester" component on the home page changes its code editor view based on what device it is running on (make it simpler for mobile devices). Another example will be a component that shows up as a dialog box on a browser and single page on mobile devices.

### Why should I use Simpler Apps and AMCs?

As a developer it is more precise and elegant. It will lead you to creating your own component library. You can break up your app into a blend of components, each with its own css and html definitions (instead of having large number of global CSS and HTML scripts). Your components can interact seamlessly by passing asynchronous events or calling methods on specific instances. It is really smart and a lot of fun!

As an organization it will save you a lot of money. You can have one applications team that builds single codebase apps to deploy on many devices and Web. You can invest in building great reusable component library that will lower the cost of future app development. Such investments in app building infrastructure will greatly enhance your business.

For more information goto: [http://simpler-apps.com] (http://simpler-apps.com) 

