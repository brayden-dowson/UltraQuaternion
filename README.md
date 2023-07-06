# UltraQuaternion
## Increases the precision of quaternions. For use with other plugins that modify the map

### Before
![image](https://github.com/brayden-dowson/UltraQuaternion/assets/88667957/b188245d-54a8-476c-bcf9-57f0a8cc16e7)
### After
![image](https://github.com/brayden-dowson/UltraQuaternion/assets/88667957/06728a0b-3d38-4f02-a812-b755ea80154c)
## Install (NW-API Only)
### Auto
type "p install brayden-dowson/UltraQuaternion" into the server console to automatically install the plugin
### Manual
put UltraQuaternion.dll in PluginAPI/plugins/"your server port number"/ and extract dependencies.zip inside PluginAPI/plugins/"your server port number"/dependencies
## Config
### is_enabled:
you might want to disable it by default so a plugin can enable it conditionally.
### cmd_permissions:
the required permissions to run the command
## Command
### uq
toggles if the plugin is enabled or not (does not change the value in the config)
## API
### UltraQuaternion.Enable()
### UltraQuaternion.Disable()
