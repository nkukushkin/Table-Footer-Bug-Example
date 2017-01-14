## Table Footer Bug Example

### Update: this bug was fixed in iOS 10!

This is a bug that exists in iOS 9.0 - 9.2 beta 2.

Description:
After showing a section header in any table view, the table view footers **in the entire app** will get misplaced based on how many lines they have.

This only applies to `grouped` style table views.

Steps to reproduce:
	
	1. Tap [Dynamic Table View]
	2. Tap [Add Section Header]
	3. Tap [Back]
	4. Tap [Static Table View] or [Dynamic Table View]
	5. Observe how footers are misplaced!

![screen](Screens/screen.png?raw=true)
