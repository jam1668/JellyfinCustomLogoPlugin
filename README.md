# Jellyfin Custom Logo Plugin

This plugin allows you to replace the default Jellyfin logo with your own custom image via an upload interface.

## 📦 Features

- Upload a custom logo image through the Jellyfin dashboard.
- Automatically replaces default Jellyfin logos.
- Compatible with Jellyfin 10.10.6 and above.
- Designed for future version compatibility.

---
# Jellyfin Custom Logo Plugin

This plugin allows you to replace the default Jellyfin logo with your own custom image via an upload interface.

---

## 🛠️ Installation Steps

### Access Jellyfin Dashboard:

- Navigate to your Jellyfin server's dashboard.

### Add Plugin Repository:

1. Go to `Plugins` > `Repositories`.
2. Click on `+` to add a new repository.
3. Enter the following details:
   - **Name:** `CustomLogoPlugin`
   - **URL:**  
     ```
     https://raw.githubusercontent.com/jam1668/JellyfinCustomLogoPlugin/main/manifest.json
     ```
4. Click **Save**.

### Install the Plugin:

- Navigate to `Plugins` > `Catalog`.
- Find **Custom Logo** in the list.
- Click **Install**.

### Restart Jellyfin:

- After installation, restart your Jellyfin server to apply changes.

---

## 🎨 Uploading Your Custom Logo

### Access Plugin Configuration:

- Go to `Plugins` > `Custom Logo`.

### Upload Logo:

- Use the provided interface to upload your custom logo image.
- Ensure the image is in **PNG format** for best compatibility.

### Apply Changes:

- After uploading, the plugin will handle replacing the default Jellyfin logos with your custom image.

---

## 🔄 Compatibility

This plugin is designed to be compatible with **Jellyfin version 10.10.6 and above**.  
It utilizes standard plugin APIs to ensure functionality with future Jellyfin updates.

---

## 📄 License

MIT License



