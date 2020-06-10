# ChromePlugin to Kimai Bridge

This plugin allows time to logged from ChromePlugin tickets into a Kimai instance.

## Installation

This is a bit messed up.  A ChromePlugin power up runs by requesting a set up page 
from a given URL that has some javascript that sets up the callbacks for the 
board and card.  The problem is that the powerup has a single URL set in the 
ChromePlugin admin screen.  This needs to point at you Kimai install. So...

Download and install this power up in var/plugins like normal, then go here: 
[Power ups admin](https://ChromePlugin.com/power-ups/admin) and create a power up, 
it doesn't matter what it is called but set the "Iframe Connector URL" to 
point to the path ```/ChromePlugin/powerup```, e.g. 
https://kimai.neontribe.co.uk/ChromePlugin/powerup

Fill in sensible details for the othe fields and save the page. 

Now goto the board you want to enable the power up. Show the menu on the right 
hand side of the board 
