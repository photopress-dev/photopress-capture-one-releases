# Changelog

Each version's notes are also on its [release](https://github.com/photopress-dev/photopress-capture-one-releases/releases).

## 1.3.3

- Fixed: images whose file names contain spaces or certain other characters were uploaded again instead of being updated. WordPress changes such names when it saves an upload (a space becomes a hyphen), and the plugin now looks for the name as WordPress saved it.
- The plugin's log now records how each image was matched to the one already on the site.

## 1.3.2

- The Publish dialog is reorganised into two tabs. **Publish** has the website and, when needed, the page. **Advanced** has the update and duplicate options.
- The page is only asked for when it's used: when **Add images to a page's gallery** or **Attach new images to a page** is ticked.
- A remembered page stays selected even when the site's page list can't be loaded.
- New tagline in Capture One's plugin list, and the full-size PhotoPress icon.

## 1.3.1

- New PhotoPress icon for the plugin and its Publish menu item.

## 1.3.0

- **Test Connection** checks, in order: that the address is a WordPress site, that the login works, that PhotoPress is installed, that the account can upload, and that the WordPress features publishing needs are available. Each problem gets a specific message, including when WordPress or PhotoPress is too old.
- **Add images to a page's gallery**, with an optional gallery anchor for pages with several galleries, and **Remove existing images from the gallery** to replace a gallery's images with the published set.
- Images already on the site are **replaced in place** by default. **Duplicate existing images** uploads them as new copies instead.
- Publishing is refused, before anything is uploaded, if an image is larger than the site's size limit.
- Publish to any of several websites, chosen in the Publish dialog.
