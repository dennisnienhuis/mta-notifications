# mta-notifications
MTA:SA Notification script written in Lua.

With this script you can make a export to the notification script.


Example usage:
``` lua
	call ( getResourceFromName ( "notification" ), "addNotification", "THIS IS A INFO MESSAGE ON RIGHT TOP", "info", 5000, "right-top" );
	exports.notification:addNotification("THIS IS A INFO MESSAGE ON RIGHT TOP", "info", 5000, "right-top");
	exports['notification']:addNotification("THIS IS A INFO MESSAGE ON RIGHT TOP", "info", 5000, "right-top");
	
	exports['notification']:addNotification("THIS IS A INFO MESSAGE ON RIGHT TOP", "info", 5000, "right-top")
	exports['notification']:addNotification("THIS IS A WARNING MESSAGE ON TOP", "warning", 5000, "top")
	exports['notification']:addNotification("THIS IS A NEWS MESSAGE ON LEFT TOP", "news", 5000, "left-top")

	exports['notification']:addNotification("THIS IS A INFO MESSAGE ON LEFT TOP", "info", 5000, "left-top")
	exports['notification']:addNotification("THIS IS A WARNING MESSAGE ON RIGHT TOP", "warning", 5000, "right-top")
	exports['notification']:addNotification("THIS IS A NEWS MESSAGE ON TOP", "news", 5000, "top")


	exports['notification']:addNotification("THIS IS A INFO MESSAGE ON TOP", "info", 5000, "top")
	exports['notification']:addNotification("THIS IS A WARNING MESSAGE ON LEFT TOP", "warning", 5000, "left-top")
	exports['notification']:addNotification("THIS IS A NEWS MESSAGE ON RIGHT TOP", "news", 5000, "right-top")
```
