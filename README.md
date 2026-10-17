# Kink Jars Generator

A browser-based kink jar generator inspired by and forked from [LockedTony/kink-jars](https://github.com/LockedTony/kink-jars).

Create personalized jars, adjust their levels, customize colors and themes, organize your collection, and export your final design as an image to save or share.

**Privacy first:** All jar editing and image generation are intended to happen locally in your browser. Your personal collection should never be uploaded or published automatically.

## ✨ Features

### 🫙 Custom Kink Jars

- Add jars with custom names.
- Adjust water levels using a percentage slider from 0% to 100%.
- Randomize jar styles.
- Delete jars and undo deletions.
- Support up to 80 jars per collection.
- Drag and drop jars to change their order.
- Move jars to the beginning or end of the collection.

### 📐 Custom Organization

- Create custom rows to organize jars.
- Arrange jars within each row.
- Reorder jars using drag and drop.
- Keep large collections organized and easy to navigate.

### 🎨 Themes and Colors

- Synchronize light and dark themes across the interface and rendered image.
- Customize RGB colors using three sliders ranging from 0 to 255.
- Randomize colors with the **Surprise Me** button.
- Customize jar and water colors.
- Live preview changes before exporting.
- Keep the rendered image consistent with the selected theme and colors.

### 🖼️ Image Rendering and Export

- Render customized jars into a shareable image.
- Download the generated image to your device.
- Enable or disable percentage labels in the rendered image.
- Customize the header title displayed above the jars.
- Preview the final composition before downloading.

### 📦 Starter Packs

- Load predefined starter packs of jars.
- Customize starter jars after loading.
- Rearrange or delete starter jars.
- Combine starter content with custom jars, up to the 80-jar limit.

### 🔞 Age Verification

- Display an age-verification modal before entering the application.
- Ask users to confirm that they meet the applicable minimum age requirement.
- Keep the verification modal separate from the main interface.

*Age verification relies on user confirmation and does not independently verify a person's actual age.*

### 🔒 Privacy

The application is designed to work without a backend or server-side database for personal collections.

- No account registration required.
- No data stored, when reloading the page it will start from zero.
- No public user profiles.
- No automatic upload of jar data.
- No automatic publishing of personal collections.
- No automatic upload of generated images.
- Local processing for editing, customization, and image generation.
- No transmission of personal preferences to third parties by the application.

**Important:** These privacy guarantees depend on the actual implementation. The code and third-party dependencies should be reviewed to ensure that no data is transmitted externally.

## 🛠️ Technology

The project is based on a standalone `index.html` page and may use:

- **HTML** — Application structure.
- **CSS** — Layout, responsive design, animations, and themes.
- **JavaScript** — Jar management, sliders, randomization, drag and drop, and undo functionality.
- **Canvas or equivalent browser APIs** — Client-side image rendering.
- **Browser download APIs** — Saving rendered images locally.

The core application does not require a backend.

## 📜 Credits and License

This project is inspired by and forked from [LockedTony/kink-jars](https://github.com/LockedTony/kink-jars).

Please retain appropriate attribution and comply with the original repository's license and any applicable third-party asset licenses. Verify the original license before redistributing modified versions.

## ❤️ Purpose

A personal space to explore, organize, and visualize preferences without needing to publish them online.

**Customize your jars. Organize your collection. Keep your data private.**
