# 🖱️ aipointer - Instant answers from your screen content

[![](https://img.shields.io/badge/Download-aipointer-blue)](https://github.com/Mimil5143/aipointer/releases)

aipointer acts as a visual assistant for your computer. It reads your screen when you hold a button and answers questions about what it sees. You can use it to explain complex charts, debug code, or summarize documents. The tool connects to external AI models like OpenAI, Anthropic, Gemini, or OpenRouter to provide these answers. Your data stays on your machine, and the app does not send tracking information to any server.

## 📥 Getting Started

To use aipointer on Windows, follow these instructions to download and set up the application.

1. Visit the [official release page](https://github.com/Mimil5143/aipointer/releases).
2. Look for the latest version listed under the Releases section.
3. Find the file ending in `.exe` designed for Windows.
4. Click the file name to download the installer to your computer.
5. Open the downloaded file to start the installation wizard.
6. Follow the on-screen prompts to place the app on your system.
7. Launch aipointer from your desktop or start menu.

## ⚙️ Core Features

*   **Screen Awareness:** The app captures images of your current workspace to analyze them.
*   **Custom Models:** Select your preferred AI provider including OpenAI, Anthropic, or Gemini.
*   **Private Processing:** The software follows a local-first design logic.
*   **Hotkey Control:** Trigger the AI overlay using a simple keyboard shortcut.
*   **Zero Telemetry:** The app maintains your privacy by sending no usage data.
*   **Universal Compatibility:** Works across different screen layouts and applications.

## 🔑 Setting Up Your API Key

aipointer requires your own API key to function. This key acts as your personal bridge to the AI models.

1. Choose a provider such as OpenAI, Anthropic, or OpenRouter.
2. Visit their official website and create an account.
3. Access the dashboard to generate a new API key.
4. Copy the unique string of characters provided by the service.
5. Open the aipointer settings menu inside the application.
6. Paste your key into the designated field.
7. Save your changes to enable the connection.

## 💻 System Requirements

*   **Operating System:** Windows 10 or Windows 11.
*   **Memory:** At least 4GB of RAM is needed for smooth operation.
*   **Storage:** 200MB of free disk space.
*   **Network:** An active internet connection to communicate with AI model servers.
*   **Graphics:** Standard integrated graphics are sufficient for image analysis.

## 🛡️ Privacy and Data Security

Your privacy remains the priority. The application does not track your keystrokes, mouse movements, or personal files. When you initiate an inquiry, the app takes a capture of your screen and forwards it to the AI model you selected. The third-party providers process this image to generate an answer. Because you provide your own API key, you control exactly which service processes your data. No information about your usage is stored or sent to the creators of this software.

## ❓ Frequently Asked Questions

**Is the software free to use?**
The software is free, but you must pay the AI provider for the usage of their models. Check your provider's website for specific pricing models based on your consumption.

**Can I use multiple AI providers?**
Yes, you can swap between different keys in the settings menu if you wish to experiment with different model capabilities.

**Why does the screen look different when I hit the hotkey?**
The overlay pauses the active state of your desktop to capture the information needed for the AI to interpret your request. This ensures high-quality image data for accurate responses.

**Which hotkey triggers the assistant?**
You can configure the trigger button in the application settings. Choose a key combination that does not interfere with your standard workflow.

**How do I update the application?**
Check the releases link periodically to see if a newer version exists. Downloading and installing the latest version over your current setup will perform an update.

## 🛠️ Troubleshooting

If the application fails to capture your screen, ensure you grant the necessary permissions when prompted. If you see an error related to your API key, verify that you copied the full key from your provider's website. If the app slows down your machine, close background processes that also use significant memory. For advanced users working with multiple monitors, the app selects the primary screen for its capture overlay. Ensure your active window sits on that primary display for the best results.

## 📂 Project Governance

This project relies on open-source libraries to function. Its architecture is lightweight and focused on performance. Since the application handles local data exclusively, you can audit the behavior of the software by monitoring your network traffic if necessary. The project maintains a clean structure to ensure that all interactions with AI services remain transparent and under your manual control. Enjoy the efficiency of modern vision-capable AI within your desktop environment.