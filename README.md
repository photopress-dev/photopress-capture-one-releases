# PhotoPress for Capture One

Publish images from Capture One straight to your WordPress website, and update them later without breaking the pages they appear on.

PhotoPress for Capture One is a Capture One publishing plugin. It works with the [PhotoPress](https://photopress.io) WordPress plugin.

![PhotoPress in Capture One's Publish menu](https://raw.githubusercontent.com/wiki/photopress-dev/photopress-capture-one-releases/images/hero.png)

This repository is where you **download releases**, **read the documentation** and **report problems**. The plugin's source code is not published here.

**[Download the latest release](https://github.com/photopress-dev/photopress-capture-one-releases/releases/latest)** · **[Documentation](https://github.com/photopress-dev/photopress-capture-one-releases/wiki)** · **[Report a problem](https://github.com/photopress-dev/photopress-capture-one-releases/issues/new/choose)**

## Features

### Publish from Capture One

Select images, choose **PhotoPress** from the Publish menu, pick the website, and publish. Capture One exports the images with your processing settings, and the plugin uploads them to the WordPress Media Library. Title, caption, alt text and keywords come from your images' metadata. [More](https://github.com/photopress-dev/photopress-capture-one-releases/wiki/Publishing)

### Update images in place

Re-edit an image and publish it again: the plugin finds it on your site by its file name and **replaces it in place**. Its URL, its attachment page, and every post and gallery that shows it stay as they are, and now show the new version. Optionally, its keywords, alt text and captions are updated wherever it's used. [More](https://github.com/photopress-dev/photopress-capture-one-releases/wiki/Updating-images)

### Add images to galleries

Add the images you publish to the gallery on a page, or **replace a gallery's images** with a new set, in the order you publish them. Works with pages that have several galleries, and with galleries that show a page's attached images. [More](https://github.com/photopress-dev/photopress-capture-one-releases/wiki/Galleries)

![Adding images to a page's gallery](https://raw.githubusercontent.com/wiki/photopress-dev/photopress-capture-one-releases/images/publish-tab-gallery.png)

### Attach new images to a page

Attach newly uploaded images to a post or page, chosen from the site's recent posts and pages, drafts included. [More](https://github.com/photopress-dev/photopress-capture-one-releases/wiki/Attaching-images-to-a-page)

### Keep to your site's limits

The plugin checks your site's image size limit before uploading, so WordPress never shows a scaled-down copy of what you exported. [More](https://github.com/photopress-dev/photopress-capture-one-releases/wiki/Image-size-limit)

### Several websites, one plugin

Add every site you publish to, each with its own login, and choose one each time you publish. **Test Connection** checks the site, your login and PhotoPress, and says exactly what to fix. Passwords are kept in your Mac's Keychain. [More](https://github.com/photopress-dev/photopress-capture-one-releases/wiki/Setting-up-a-website)

## Requirements

- **Capture One 16** on macOS 12 or later
- **WordPress 6.6** or later, with the **PhotoPress** plugin installed and active
- A WordPress account that can upload media (Author role or higher), and an **application password** for it

## Install

1. Download the latest `PhotoPress-x.y.z.zip` from [Releases](https://github.com/photopress-dev/photopress-capture-one-releases/releases/latest).
2. Unzip it and double-click **PhotoPress.coplugin**, or install it under **Capture One › Settings › Plugins**.
3. Restart Capture One if it asks you to.

Then [set up your website](https://github.com/photopress-dev/photopress-capture-one-releases/wiki/Setting-up-a-website).

## Get help

- **Documentation:** the [wiki](https://github.com/photopress-dev/photopress-capture-one-releases/wiki), including [Troubleshooting](https://github.com/photopress-dev/photopress-capture-one-releases/wiki/Troubleshooting).
- **Found a problem?** [Open an issue](https://github.com/photopress-dev/photopress-capture-one-releases/issues/new/choose). The form asks for the details that help most.
- **What's changed:** the [changelog](CHANGELOG.md) and [Releases](https://github.com/photopress-dev/photopress-capture-one-releases/releases).
- **Security issues:** please don't post them publicly. See [SECURITY.md](SECURITY.md).
