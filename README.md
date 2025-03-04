# Unreal Engine Project

This is an Unreal Engine project. Follow the setup instructions below to get started.

## Prerequisites

Before cloning this repository, ensure you have the following installed:

- **Unreal Engine** (Recommended version: 5.5.3)
- **Git** ([Download Git](https://git-scm.com/downloads))
- **Git LFS (Large File Storage)** ([Download Git LFS](https://git-lfs.github.com/))

## Required Plugins

The following plugins must be installed from **Fab** before opening the project:

- **MetaHuman Plugin**
- **Quixel Bridge**
- **Convai**

### How to Install Plugins:
1. Go to [Fab.com](https://fab.com) and sign in with your **Epic Games** account.
2. Search for each required plugin and **add it to your library**.
3. Open **Epic Games Launcher** and go to the **Library** tab.
4. Refresh the Library and install each plugin.
5. Open **Unreal Engine**, go to **Edit > Plugins**, search for the plugins, and ensure they are enabled.
6. Restart Unreal Engine.

## Setting Up the Project

1. **Install Git LFS** (if not already installed):
   ```sh
   git lfs install
   ```
2. **Clone the Repository**:
   ```sh
   git clone https://github.com/mendimci/1sp-ai-avatar.git
   ```
   Git LFS will automatically download large files.

3. **Open the Project in Unreal Engine**:
   - Navigate to the cloned folder.
   - Open the `.uproject` file with Unreal Engine.

4. **Build the Project** (if needed):
   - Open the Unreal Engine editor.
   - Compile the project using **Build** > **Build Solution** (in Visual Studio).

## Git Best Practices

- **Always pull before making changes**:
  ```sh
  git pull
  ```
- **Commit only necessary files** (avoid committing `Binaries/`, `Intermediate/`, and `Saved/` directories).
- **Use Git LFS for large files** (tracked in `.gitattributes`).

## Troubleshooting

- If you experience missing assets, run:
  ```sh
  git lfs pull
  ```
- If Unreal Engine asks to rebuild modules, click **Yes**.

## License
