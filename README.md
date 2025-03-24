# DTD Releases

To use the plugin payload with an SRI integrity hash, follow these steps:

1. Open `latest.txt` from this repository.
1. Download the file referenced in the script tag to a secure, publicly accessible location where you will host it.
1. In your file that loads the plugin, delete the tag that references `ddplugin.js`.
1. Copy/paste the contents of `latest.txt` into the location where the script tag was just deleted.
1. Replace the `<<replace-me>>` text with publicly URL of the file you downloaded.
