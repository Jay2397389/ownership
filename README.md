# 🐔 Polloshook — Official Update Repository

This is the **official update repository** for **Polloshook**, a Java-based application that supports automatic updates.

The repository hosts versioned binary files that the client downloads and applies to stay up to date. This system allows for lightweight, efficient updates without requiring manual downloads or full reinstalls.

---

## 📂 Repository Contents

This repository currently includes two update files:

### `1.bin`

* **Purpose**: Main update package.
* **Description**: Contains the **compiled Java classes and resources** for the Polloshook client.
* **Contents**:

  * Standard `.class` files (compiled from `.java`)
  * Resource files (e.g. icons, config defaults, etc.)
* **Format**: This is typically a renamed `.jar` or a flat archive used by the Polloshook client directly.

### `2.bin`

* **Purpose**: Secondary or supplemental update file.
* **Description**: Used for **additional resources or modular components** that are loaded separately.
* **Contents**:

  * Extra assets (e.g. localization files, optional modules)
  * Data used for runtime patching or extending functionality

---

## 🔄 How Polloshook Auto-Updating Works

1. On startup, the Polloshook client checks this repository for new `.bin` files.
2. If newer versions are found, the client downloads them and applies the update.
3. The update process may overwrite existing files or expand new ones, depending on the versioning logic.
4. Once updated, the client restarts or refreshes its state.

## ✅ Trust & Transparency

This project is committed to being:

* Open,
* Easy to audit,
* Developer-friendly.

---

## 📬 Contact

If you have questions, suggestions, or want to contribute, feel free to reach out through the main Polloshook project, in the Krcrystal discord.
