# itl-linuxfabrik

Check Command definitions of plugins from [Linuxfabrik](https://github.com/Linuxfabrik/monitoring-plugins).

The JSON file is stored because of finding differences to new versions easier. To generate this file follow [these](https://github.com/Linuxfabrik/monitoring-plugins/blob/main/ICINGA.rst#all-plugins-linuxfabrik-icinga-director-configuration)  instructions.

Whether Check or Notification Command, a constant LinuxfabrikPluginDir is required for both, which must be set to the correct path to the plugins.
