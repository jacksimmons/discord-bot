# Setup
Create a discord developer application using the [discord developer portal](https://discord.com/developers/applications).  
Get the token for your application (App -> Bot/Token).  
Create ".env" file in the base directory with contents `TOKEN = (Token goes here)`.  

If python is installed, run these terminal commands in the base directory:  
```
py -m venv .
./Scripts/activate.(bat|ps1)
py -m ensurepip --default-pip  
py -m pip install -r requirements.txt  
```

Run the bot server:  
`py main.py`

Back in the developer portal, add the application to a Discord server (App -> Installation).  
Interact with the bot with slash commands (start a message with "/"), or ! commands (start a message with "!", use "!help" for documentation).  
