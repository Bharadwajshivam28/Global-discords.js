# Discord-Bot

---

![Screenshot from 2023-03-19 03-25-32](https://user-images.githubusercontent.com/108119109/226142563-dbb09c8f-5e2c-4e98-8eae-efeb57b0815b.png)

📌 constants are being declared using the const keyword. <br>
📌 code uses the require function to import the fs module, which is used to read files from the file system. <br>
📌 code creates a new instance of the Client class from the Discord.js.  <br>

---

![Screenshot from 2023-03-19 03-26-11](https://user-images.githubusercontent.com/108119109/226142747-0dabf4d8-68b5-4c6e-b60d-4fbfe8c4fbd1.png)

📌 Guilds: Receive events related to servers that the bot is a member of.  <br>
📌 GuildMembers: Receive events related to guild members.  <br>
📌 GuildMessages: Receive events related to messages sent in guilds.  <br>
📌 GuildMessageTyping: Receive events when a user starts or stops typing in a guild channel.  <br>
📌 DirectMessages: Receive events related to direct messages between the bot and users.  <br>
📌 DirectMessageReactions: Receive events related to reactions on direct messages.  <br>
📌 DirectMessageTyping: Receive events when a user starts or stops typing in a direct message conversation.  <br>
📌 MessageContent: Receive the content of the message, including the message's text and any attachments.  <br>
📌 Partials.Message: Receive partial information about messages, including their IDs, channel IDs, and content.  <br>
📌 Partials.Channel: Receive partial information about channels, including their IDs and names.  <br>
📌 Partials.GuildMember: Receive partial information about guild members, including their IDs, usernames, and roles.  <br>
📌 Partials.Reaction: Receive partial information about reactions, including the IDs of the users who reacted and the emojis used.  <br>
📌 Partials.GuildScheduledEvent: Receive partial information about scheduled events in guilds, such as reminders or announcements.  <br>
📌 Partials.User: Receive partial information about users, including their IDs, usernames, and avatars.  <br>
📌 Partials.ThreadMember: Receive partial information about members of threads, which are a type of channel in Discord that allow for more focused discussions within a guild.  <br>

---

![Screenshot from 2023-03-19 03-26-29](https://user-images.githubusercontent.com/108119109/226142958-ea5ef1e3-2a85-40dc-ae6b-eebdec62fe0b.png)

## In this we are targeting the channel in which we have to forward message. We can add more channel in future.

---

![Screenshot from 2023-03-19 03-26-42](https://user-images.githubusercontent.com/108119109/226143022-47e7b3d6-bed7-4133-ad67-f5c6278462a6.png)

📌 client.on initializes a new client object, which represents the connection to the Discord API. This client object will be used to listen for events and send messages .  <br>
📌 console.log logs a message when we are successfully logged.  <br>
📌 client.om('messageCreate') sets up an event listener for the 'messageCreate' event.  <br>








