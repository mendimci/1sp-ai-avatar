# Unreal Engine Project

This is an Unreal Engine project. Follow the setup instructions below to get started.

## Prerequisites

Before cloning this repository, ensure you have the following installed:

- **Unreal Engine** (Recommended version: 5.5.3)
- **Git** ([Download Git](https://git-scm.com/downloads))
- **Git LFS (Large File Storage)** ([Download Git LFS](https://git-lfs.github.com/))

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

Include any license details here (if applicable).

