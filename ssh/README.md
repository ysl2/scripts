# ssh

## Mac installation

```bash
brew install openssh
sudo launchctl load -w /System/Library/LaunchDaemons/ssh.plist
```

Restart ssh service after modifying the ssh configuration file:

```bash
sudo launchctl unload /System/Library/LaunchDaemons/ssh.plist
sudo launchctl load -w /System/Library/LaunchDaemons/ssh.plist
```
