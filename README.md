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

- Roblox experience must have **TextChatService enabled**  
- Chat version must be set to `TextChatService`  
- HTTP permissions are **not required** unless loading remotely  

## Installation

1. Enable **TextChatService** in your experience settings.  
2. Place the script in `StarterPlayer > StarterPlayerScripts`.  
3. Publish and test in a live session (TextChatService does not fully function in Studio Play Solo).  

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

Roblox’s default chat UI is inflexible for custom experiences. This script provides a clean, controllable chat layer while staying fully compatible with TextChatService.

## License

Creative Commons Zero v1.0 Universal (CC0 1.0). You can use, modify, and distribute this work without restriction, but you must always credit me: COLMLENEHAN.

## Credit

Colm Lenehan 2026
