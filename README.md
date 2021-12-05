# 🚨ELS-FiveM with WMServerSirens Integration

## 🚨NonELS Version:
[NonELS](https://github.com/Zerofour04/lux_vehcontrol)

## 📗Installation Guide
1. Clone the repository or download the [latest version](../../releases/latest).
    * Note: if cloning, pass `[ELS]` or similar to `path` argument (e.g. `git clone https://github.com/MrDaGree/ELS-FiveM [ELS]`, make sure you are in `resources`, also).
2. Place inside your server's `resources` directory.
3. Create a file called 'vcf.lua' and copy the file contents of 'vcf._default_.lua' into that file, but do not delete the default file.
4. Make altercations accordingly.
5. Place any VCF files inside the `vcf` directory so they are able to be found.
6. Enjoy!

## 🧱Requirements
- [WMServerSirens](https://github.com/Zerofour04/WMServerSirens)
- ELS Cars with CARNAME.xml
- [fxserver](https://docs.fivem.net/docs/server-manual/setting-up-a-server/)

## 📞Support
https://discord.gg/GUvNXNe

## ⌨️Default Controls
https://github.com/MrDaGree/ELS-FiveM/wiki/Controls

## ⚙️Convars
| Convar              | Parameters        | Function                                                                                                              | Example Usage                | Default State |
|---------------------|-------------------|-----------------------------------------------------------------------------------------------------------------------|------------------------------|---------------|
| `els_outputLoading` | boolean           | This outputs the loaded vehicles that have been specified in the vcf.lua                                              | `setr els_outputLoading true` | "false"      |
| `els_debug`         | boolean           | This prints information to both client or server with information of what is happening                                | `setr els_debug true`         | "false"      |
| `els_developer`     | boolean           | Provides access to developer features which may break ELS for clients on your server, should only be used when asked. | `setr els_developer true`     | "false"      |
| `els_warnOnJoin`    | boolean           | Displays a warning if the current version is outdated                                                                 | `setr els_warnOnJoin true`    | "false"      |
