# Custom Roblox TextChat UI

A custom client-side chat interface built on Roblox’s **TextChatService**. Designed to work cleanly on **PC and mobile**, with modern UI, slash-to-chat support, and a live scrollable message feed. This replaces the default Roblox chat UI while still using official TextChatService channels.

## Features

- Custom draggable chat window  
- Scrollable message history  
- Live incoming messages from other players  
- Message format: `[DisplayName]: message`  
- Mobile-friendly **Send** button  
- PC shortcut: press `/` to start typing  
- Enter-to-send support  
- Uses `RBXGeneral` TextChatService channel  
- No server scripts required (client-only UI)  

## Requirements
- Android on a mobile device or Android emulator, like Genymotion or Mumu Player.
- Roblox experience must have **TextChatService enabled**  
- Chat version must be set to `TextChatService`  
- HTTP permissions are **not required** unless loading remotely  

## Installation

1. Go to https://deltaexploits.gg/ and install. This is for Android only. I'm not responsible if you get hacked.
2. Once installed, set up an Alt Roblox account to prevent getting banned. I recommend using an emulator, like Genymotion or Mumu Player. 
3. Once you join a game, load the script and chat with other people! This emulates the Roblox TextChatService inside of a new GUI that Roblox can't understand.

## Usage

- Click the text box or press `/` on PC to start typing  
- Press **Enter** or tap **Send** to send a message  
- Messages from all players appear in the scrollable message panel  
- Display names are shown automatically  

## Message Format


Display names are pulled directly from the sending player via `TextSource.UserId`.

## Customization

You can easily tweak:

- UI size and position  
- Fonts and colors  
- Message text size  
- Max chat history (by clearing old labels)  
- Channel name (replace `RBXGeneral`)  

## Limitations

- Only listens to one channel (`RBXGeneral`) by default  
- No moderation, filtering UI, or system messages included  
- Styling is intentionally minimal and neutral  

## Why This Exists

Two Reasons,

1: Roblox introduced Age Checks, and anybody who does not comply with Age Checks will not be able to chat. I've noticed that people are making custom chats inside of games, but that doesn't work everywhere. So why not make one that does?

2: Roblox’s default chat UI is inflexible for custom experiences. This script provides a clean, controllable chat layer while staying fully compatible with TextChatService.

## License

Creative Commons Zero v1.0 Universal (CC0 1.0). You can use, modify, and distribute this work without restriction, but you must always credit me: COLMLENEHAN.

## Credit

Colm Lenehan 2026
