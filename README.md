# Obsidian Plugin for Clearing Unused Images

This plugin helps you to keep your vault clean by deleting the images you are not referencing in your markdown notes anymore.

The plugin simply gets all of your image links from all the markdown documents and compares these images with all image files you have available in your vault.

In case any of these image files are not referenced in any document of the vault, they will be automatically deleted.

## Settings

Please make sure that you select the destination for the deleted images under "Clear Unused Images Settings" tab. You have 3 options:

<img src="https://github.com/ozntel/oz-clear-unused-images-obsidian/blob/master/images/delete-destination.png?raw=true">

1. **Move to Obsidian Trash** - Files are going to be moved to the `.trash` under the Obsidian Vault.

2. **Move to System Trash** - Files are going to be moved to the Operating System trash.

3. **Permanently Delete** - Files are going to be destroyed permanently. You won't be able to revert back.

## How to use

1. Activate the plugin from Community Plugins

2. Simply Open Command Palette (Using `Ctrl/Cmd + P` or from Ribbon)

3. Run "Clear Unused Images" and that's all.

<img src="https://github.com/ozntel/oz-clear-unused-images-obsidian/raw/master/images/Clear-Command.png">

You will see a notification of how many images are deleted from your vault:

<img src="https://github.com/ozntel/oz-clear-unused-images-obsidian/raw/master/images/images-deleted.png">

In case all images are used, you will see communication as below:

<img src="https://github.com/ozntel/oz-clear-unused-images-obsidian/raw/master/images/nothing-deleted.png">

If you want to check which images are deleted, you can go to console and see the details:

<img src="https://github.com/ozntel/oz-clear-unused-images-obsidian/raw/master/images/deleted-images.png">

**Scanned Image Formats** : jpg, jpeg, png, gif, svg, bmp

## Planned Features

-   [x] Creating settings for users to select the destination of the deleted files
-   [ ] Images to be cleaned during load of the vault if users chooses.
-   [ ] Images to be cleaned every X minutes depending on user's choice

### Support

<a href="https://www.buymeacoffee.com/ozante" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="20%" height="auto"></a>
