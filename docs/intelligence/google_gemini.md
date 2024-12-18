### Pyrogram + AI Powerful

• Required: `pip3 install git+https://github.com/xtsea/pyrogram` (forked from kurigram original)<br>
• Can add many modules

### Examples
```python
from pyrogram import Client, filters

client = Client(...)
client.start()

await client.send_google_gemini(
     chat_id=0,
     prompt="hello world",
     api_key="...",
     disable_web_page_preview=True
)
