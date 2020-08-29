# Dorico drum map for Komplete - Discovery Series - Cuba

## Installation

### Use sample project as a template

Open the ni-komplete-cuba.dorico project, delete all flows, delete players / kits that you don't need and use that as a template. The drawback is that you can't combine multiple templates this way.

### Import percussion kit, map and playback template

**Warning**, this process will remove your current VSTs from your project. That is a Dorico limitation and currently there is no other way to import endpoint configuration and playing techniques, you can read some details [here](https://www.steinberg.net/forums/viewtopic.php?f=246&t=194935&p=1029095#p1029095).



You can manually install percussion kit and percussion map, as follows:

1. In Dorico setup, create a new player and click "Import Kit" and import percussion kit you want to use.
2. Go to Play->Playback template,  import and apply "Komplete - Discovery Series - Cuba.dorico_pt"
3. This will create Kontakt VST instrument with Conga Set, Bongos, Timbales and Hand percussion ensamble

## Notes

### Cajon

Cajon is using two instruments - one for Right hand (Cajon High) and one for Left hand (Cajon Low).

This follows Komplete's patterns, which also use 2 instruments, each for one hand. This way, one could drag and drop patterns from Kontakt to Dorico (but playing techniques are not applied in this case at current version - 3.5.10).

For this reason, there are also RH and LH maps, and a single cajon is loaded twice, each bound to one channel (not sure if this is a good strategy memory-wise)?

Note that some sounds are shared by the two, see the instrument for details.

If you do not need LH and RH levle of granularity, you can use only one instrument (and delete the other one from Kontakt).