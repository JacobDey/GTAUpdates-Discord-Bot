# GTAUpdates Discord Bot
 This is a Discord bot that scrapes https://gtaupdate.com/ for new updates on local traffic disruptions or fires, then posts it to a discord channel of your choice.

It works off a pretty complicated regex that will break if Iain changes the site at all. Be sure to add your bot token to client.run('REPLACE THIS WITH YOUR BOT KEY OR THIS WILL NOT WORK') about halfway down the code, and also change channel_name = 'gtaupdates'  to be the name of the channel you want the bot to message in.
