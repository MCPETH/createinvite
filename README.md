# Code Example create invite discord.js v13
```
client.on('ready', () => {
	// Create an invite to a channel
	channel = client.guilds.cache.get("enter your guilds id").channels.cache.get("enter your channels id");
	channel.createInvite()
		.then(invite => console.log(`Created an invite with a code of ${invite.code}`))
		.catch(console.error);
})
```
