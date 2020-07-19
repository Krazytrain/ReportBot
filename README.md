# AutoCleanBot
Automatically clean a channel in DIscord

# Commands
!clean \[y\] - Cleans the channel you executed the command in, **wont clean pins unless y is passed**.  
!autoclean (#channel) (time) (clear pins, pass `y` here) - Sets up a task to clean the mentioned channel every specified time. Example usage: !autoclean #bot-tests 5m y - This will clean #bot-tests every 5 mins and clear the pins.  
!autoclean list - List the tasks.  
!autoclean remove (#channel) - Remove a task for a certain channel. Example usage: !autoclean remove #bot-tests
