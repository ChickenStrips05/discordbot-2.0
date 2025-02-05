# discordbot-2.0

This is the 2nd sucsessful discord bot that I made. Anyone can contribute as this is not a very complex project.

# for developers:

This is what the data class looks like(the current code passes this data to all commands)
class data:
                    Channel = channel  (as in message.channel)
                    Message = message
                    Client = client  (as in discord.client)
                    RawText = text  (as in message.content)
                    TextList = textList (a split version of the rawText)
                    Commands = commands (a list of all commands(the names))
                    Files = files  (a list of all command files(the names))
                    Prefix = prefix (the current command prefix)
                    FileName = fileName  (the filename of the current command)
                    Auth = auth  (auth level of message.author (stored in users.json))
                    Color = color (color function that i made, only works in terminals)
                    Discord = discord  (discord module)
                    Random = random 
                    Os = os
                    Requests = requests
                    Datetime = datetime
                    Json = json
                    Confirm = False
                    Ytdlp = ytdlp
                    Time = time
