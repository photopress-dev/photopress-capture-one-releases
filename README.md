# PhotoPress for Capture One

Publish images from Capture One straight to your WordPress website, and update them later without breaking the pages they appear on.

PhotoPress for Capture One is a Capture One publishing plugin. It works with the [PhotoPress](https://photopress.io) WordPress plugin.

This repository is where you **download releases** and **report problems**. The plugin's source code is not published here.

## What it does

- **Publishes** images from Capture One to your WordPress Media Library.
- **Updates images in place.** Publish an image again and it replaces the one already on your site, keeping its URL, its page, and every post or gallery that shows it.
- **Adds images to a page's gallery**, and can replace a gallery's images with a new set.
- **Attaches new images to a page**, if you want.
- **Keeps your site's limits.** It checks the size limit your site uses and tells you before uploading if an image is too large.
- **Supports several websites.** You choose which one each time you publish.

Title, caption, alt text and keywords come from your images' metadata, the same as uploading through WordPress.

## Requirements

- **Capture One 16** on macOS 12 or later
- **WordPress 6.6** or later, with the **PhotoPress** plugin installed and active
- A WordPress account that can upload media (Author role or higher), and an **application password** for it

## Install

1. Download the latest `PhotoPress-x.y.z.zip` from [Releases](https://github.com/photopress-dev/photopress-capture-one-releases/releases).
2. Unzip it and double-click **PhotoPress.coplugin**, or install it under **Capture One › Settings › Plugins**.
3. Restart Capture One if it asks you to.

## Set up

1. In WordPress, go to **Users › Profile › Application Passwords** and create one, for example named "Capture One". Your normal login password won't work here.
2. In Capture One, open **Settings › Plugins › PhotoPress**, click **Add Website**, and enter the site address, your username and the application password.
3. Click **Test Connection**. It checks your site, your login and PhotoPress, and tells you if anything needs fixing.

## Publish

Select images, then choose **PhotoPress** from Capture One's **Publish** menu.

- **Publish** tab: the website, and optionally the page whose gallery the images go into, or that new images are attached to.
- **Advanced** tab: whether to update an image's metadata and its alt text and captions where it's used, or to add images as new copies instead of replacing them.

Images are matched to the ones already on your site by file name, so keep Capture One's output name the same as the image name.

## Get help

- **Found a problem?** [Open an issue](https://github.com/photopress-dev/photopress-capture-one-releases/issues/new/choose). The form asks for the details that help most: versions, what you did, and the plugin's log.
- **Changes in each version:** see the [changelog](CHANGELOG.md) and [Releases](https://github.com/photopress-dev/photopress-capture-one-releases/releases).
- **Security issues:** please don't post them publicly. See [SECURITY.md](SECURITY.md).
