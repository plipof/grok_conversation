![xAI logo](https://brands.home-assistant.io/_/grok_conversation/icon.png)
# xAI Grok Conversation
This is a custom component of Home Assistant.

Derived from [OpenAI Conversation](https://www.home-assistant.io/integrations/openai_conversation/) but uses the xAI API URL [(https://api.x.ai/v1)](https://api.x.ai/v1).

## How it works
xAI Grok Conversation uses OpenAI's python package to call to call the xAI API URL to interact with the latest version of the Grok LLM, see xAI [documentation]([text](https://docs.x.ai/docs)).

## Installation
1. Install via registering as a custom repository of HACS or by copying `grok_conversation` folder into `<config directory>/custom_components`
2. Restart Home Assistant
3. Go to Settings > Devices & Services.
4. In the bottom right corner, select the Add Integration button.
5. Follow the instructions on screen to complete the setup (API Key is required).
    - [Generating an API Key](https://console.x.ai/)
6. Go to Settings > [Voice Assistants](https://my.home-assistant.io/redirect/voice_assistants/).
7. Click to edit Assistant (named "Home Assistant" by default).
8. Select "Grok Conversation" from "Conversation agent" tab.
    <details>

    <summary>Screenshot</summary>
    <img width="500" alt="Select a conversaion agent in Home Assistant" src="https://www.braytonstafford.com/content/images/2025/01/image-12.png">

    </details>

## Preparation
After installed, you need to expose entities from "https://{your-home-assistant}/config/voice-assistants/expose".
