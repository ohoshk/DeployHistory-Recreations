# DeployHistory Recreations
Recreation of gametest1, gametest2, and sitetest1-3's DeployHistories. Gametest3-5 and Sitetest4 will be included as their archive.org snapshots.

## How you can help
This isn't an easy task to do by myself, so any help is appreciated.

### Getting & Contributing Hashes
**TODO: Create a better guide in the future.**

To get hashes, you can search various anti malware websites, or search old hard drives. I recommend [OTX AlienVault](https://otx.alienvault.com/) and [VirusTotal](https://www.virustotal.com/).

If you find a hash, check it against the DeployHistories here and on the actual sites to make sure you haven't found a duplicate. If your hash is not a duplicate, wonderful! You've found a new hash to contribute!

To contribute the hash, either create an issue with the hash and label it with the appropriate site, or create a Pull Request, and do the same thing.

Make sure you have the correct version and date! To get the correct version, right click on the executable of the player or studio (_NOT_ the launcher  binary!!) and go to the Details tab. 

Note what is in the File Version row, under Details. To get the correct date, go to the Digital Signatures tab, click the signature, and click Details. Copy everything in signing time.

Finally, to contribute the hash, either create an issue and format the issue with the title as the version hash and the label as the proper site. The body should contain something like this: `New [WindowsPlayer|Studio|StudioBeta|Client] [Version Hash] at [Signing date & time formatted as MM/DD/YYYY HH:MM:SS PM|AM], file version: [File Version]...Done!`

Alternatively, you can also create a Pull Request to contribute your hash.

Example: `New WindowsPlayer version-428b22c7474444fe at 2/8/2017 10:31:38 PM, file version: 0, 278, 0, 39156...Done!`

### More information

Commits that include > 10 hashes will be formatted as `[WindowsPlayer|Studio|StudioBeta|Client] [Signing date & time formatted as MM/DD/YYYY HH:MM:SS PM|AM]`, as these are considered major contributions.
