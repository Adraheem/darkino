# Darkino

![Build](https://github.com/Adraheem/darkino/workflows/Build/badge.svg)
[![Version](https://img.shields.io/jetbrains/plugin/v/PLUGIN_ID.svg)](https://plugins.jetbrains.com/plugin/PLUGIN_ID)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/PLUGIN_ID.svg)](https://plugins.jetbrains.com/plugin/PLUGIN_ID)

## Template ToDo list
- [x] Create a new [IntelliJ Platform Plugin Template][template] project.
- [ ] Get familiar with the [template documentation][template].
- [ ] Adjust the [pluginGroup](./gradle.properties), [plugin ID](./src/main/resources/META-INF/plugin.xml) and [sources package](./src/main/kotlin).
- [ ] Adjust the plugin description in `README` (see [Tips][docs:plugin-description])
- [ ] Review the [Legal Agreements](https://plugins.jetbrains.com/docs/marketplace/legal-agreements.html?from=IJPluginTemplate).
- [ ] [Publish a plugin manually](https://plugins.jetbrains.com/docs/intellij/publishing-plugin.html?from=IJPluginTemplate) for the first time.
- [ ] Set the `PLUGIN_ID` in the above README badges.
- [ ] Set the [Plugin Signing](https://plugins.jetbrains.com/docs/intellij/plugin-signing.html?from=IJPluginTemplate) related [secrets](https://github.com/JetBrains/intellij-platform-plugin-template#environment-variables).
- [ ] Set the [Deployment Token](https://plugins.jetbrains.com/docs/marketplace/plugin-upload.html?from=IJPluginTemplate).
- [ ] Click the <kbd>Watch</kbd> button on the top of the [IntelliJ Platform Plugin Template][template] to be notified about releases containing new features and fixes.

<!-- Plugin description -->
## Introducing Darkino: A Revolutionary Dark Theme for IntelliJ

Darkino is a cutting-edge dark theme designed to transform your IntelliJ experience into a visually stunning and eye-friendly environment. With its sleek and sophisticated design, Darkino sets a new standard for dark themes by delivering a darker color palette while prioritizing user comfort and reducing eye strain.

Immerse yourself in a world of deep, rich colors carefully crafted to provide optimal contrast and readability. Darkino's distinctive color scheme enhances code visibility, making it easier to focus on your work for extended periods without experiencing eye fatigue.

Not only does Darkino take care of your eyes, but it also enhances productivity by intelligently organizing the interface elements. The thoughtfully chosen syntax highlighting ensures that your code stands out, aiding comprehension and reducing distractions.

Customizable and versatile, Darkino allows you to fine-tune various aspects of the theme to suit your preferences. Tailor the font size, line spacing, and background contrast to create the perfect environment for your coding endeavors.

Darkino is compatible with a wide range of programming languages and frameworks supported by IntelliJ, making it the ideal choice for developers across various disciplines. Whether you're working on a web application, data analysis, or mobile development, Darkino will effortlessly adapt to your needs.

Experience the future of dark themes with Darkino. Upgrade your IntelliJ environment today and let your code shine in a visually stunning, eye-friendly, and immersive experience. Boost your productivity, comfort, and style with Darkino, the ultimate dark theme for IntelliJ.
<!-- Plugin description end -->

## Installation

- Using IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "darkino"</kbd> >
  <kbd>Install Plugin</kbd>
  
- Manually:

  Download the [latest release](https://github.com/Adraheem/darkino/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>


---
Plugin based on the [IntelliJ Platform Plugin Template][template].

[template]: https://github.com/JetBrains/intellij-platform-plugin-template
[docs:plugin-description]: https://plugins.jetbrains.com/docs/intellij/plugin-user-experience.html#plugin-description-and-presentation