This was downloaded with :
```
mkdir $HOME/Attune_VMWarePowerCLI

# This will take several minutes
pwsh -Command "Save-Module -name VMware.PowerCLI -Path $HOME/Attune_VMWarePowerCLI"

cd $HOME/Attune_VMWarePowerCLI
tar cjf ../Attune_VMWarePowerCLI.tar.bz2 *
cd ..
rm -rf $HOME/Attune_VMWarePowerCLI
```

Then copy `Attune_VMWarePowerCLI.tar.bz2` into Attune.