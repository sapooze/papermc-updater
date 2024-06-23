# What it does
This script updates the Paper Jar of one or multiple Servers at once, using the PaperMC API.
You just add the Server Folder to the list and run the updater.

This script allows you also to choose the version of the Paper Jar.
It supports all Paper Versions that exists.


# Requirements
jq, wget and curl are required for the script to run. You can install them with
`sudo apt install jq wget curl -y`

# How to use
1. Give the Updater the permissions it needs: `chmod +x PaperUpdater-v1.0.0.jar`
2. Execute the Updater by using: `./PaperUpdater-v1.0.0.jar`
3. If you haven't yet, add a Server Folder in the Server Settings by entering 2.
4. If you want to update a Server enter 1 and follow the updating process.

# Updating Multiple Servers at once
To update multiple Servers at once, separate the Servers with a comma, with no space in between.

> ### Example
> If you want to update server1 and server2 use:
> `server1,server2`

## Future Updates

- [ ] Optimize the script
- [ ] Add an FTP/SFTP Option
- [ ] Add an Option to update Bungeecord
- [ ] Add an Option to update Spigot

