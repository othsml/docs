# PyCharm Installation Guide

This guide provides instructions for installing PyCharm Community Edition on Windows, macOS, and Linux.

## Windows

1.  **Download:** Visit the [JetBrains website](https://www.jetbrains.com/pycharm/download/) to download the installer for Windows.
2.  **Run Installer:** Execute the downloaded `.exe` file.
3.  **Follow Wizard:**
    *   Click "Next."
    *   Choose the installation location.
    *   (Optional) Create a desktop shortcut.
    *   Click "Install."
4.  **Launch:** Click "Finish" to open PyCharm.

## macOS

1.  **Download:** Get the `.dmg` file from the [JetBrains website](https://www.jetbrains.com/pycharm/download/).
2.  **Mount Image:** Double-click the `.dmg` file.
3.  **Install:** Drag the PyCharm icon to your Applications folder.
4.  **Launch:** Open PyCharm from the Applications folder.

## Linux

1.  **Download:** Download the `.tar.gz` file from the [JetBrains website](https://www.jetbrains.com/pycharm/download/).
2.  **Extract:** Open a terminal and run:
    ```bash
    sudo tar -xzf pycharm-community-<version>.tar.gz -C /opt
    ```
    *(Replace `<version>` with the downloaded version)*
> or simply double click the archive and extract
3.  **Run Script:** Execute the following command:
    ```bash
    sh /opt/pycharm-community-<version>/bin/pycharm.sh
    ```
4.  **Desktop Entry:** In PyCharm, go to "Tools" > "Create Desktop Entry" to create a launcher.
