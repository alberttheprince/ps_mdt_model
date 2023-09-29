![image](https://github.com/alberttheprince/ps_mdt_model/assets/85725579/555fc573-5130-4d9d-bf6a-daf032ef1dd8)

# ps_mdt_model
A tablet model reskin for PS-MDT https://github.com/Project-Sloth/ps-mdt

The UI is a "colour neutral," zoomed-in version of the PS-MDT UI to avoid conflicting EMS/LSPD/Sherrif/etc. symbols. This was made because the default prop used by PS-MDT is thematically off, using a tablet with the Life Invader social page.

To install this, put it where you put your stream files and add:

ensure ps_mdt_model

to your server cfg

Then go to client > main.lua 

and change line 9 to ```local tabletProp = `prop_cs_tablet_psmdt` ```

And line 12 to ```local tabletRot = vector3(10.0, 0.0, 0.0)```
