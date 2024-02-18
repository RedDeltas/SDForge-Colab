# SDForge-Colab
<a target="_blank" href="https://colab.research.google.com/github/RedDeltas/SDForge-Colab/blob/main/RedDeltasSDForge.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Utilities for running Stable Diffusion WebUI Forge in Google Colab. If you have any problems or suggestions please create an Issue on this repository.

## Notebook Parameters
*   **USE_GOOGLE_DRIVE** - Stores the Forge installation in your GDrive, this makes it easy to store your generated images, checkpoints, installed extensions etc between sessions
*   **UPDATE_FORGE** - Update your Forge installation when you run this notebook
*   **INSTALL_DEPS** - Installs optional dependencies such as `insightface`
*   **ALLOW_EXTENSION_INSTALLATION** - Allow installing extensions through the UI **Warning**: It is recommended to have **USE_USERNAME_AND_PASSWORD** turned on if you're using this, otherwise anyone with your Gradio URL could install malicious extensions on your instance
*   **USE_USERNAME_AND_PASSWORD** - Require inputting a username and password when accessing the Gradio URL
*   **USERNAME** - Username to use when accessing the Gradio URL
*   **PASSWORD** - Password to use when accessing the Gradio URL
