# Menus
Menus
Menus are a common user interface component in many types of applications.
Android-powered devices are no longer required to provide a dedicated Menu button. 
With this change, Android apps should migrate away from a dependence on the traditional 6-item menu panel and instead provide an app bar 
to present common user actions.
The options menu is the primary collection of menu items for an activity. 
It's where you should place actions that have a global impact on the app, such as "Search," "Compose email," and "Settings."
Using a menu resource is a good practice for a few reasons:
It's easier to visualize the menu structure in XML.
It separates the content for the menu from your application's behavioral code.
It allows you to create alternative menu configurations for different platform versions, screen sizes, and other configurations by 
leveraging the app resources framework.
