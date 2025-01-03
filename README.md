# kaithem_plugin_datasette
WIP plugin to integrate kaithem with datasette. Very early WIP.


## Install
If you did a pipx install of Kaithem, you should just be able to do:

`pipx inject kaithem kaithem-plugin-datasette`

and reboot or restart kaithem.

## Dev Install
For testing/, activate your kaithem virtual environment and do:

```bash
pip install -e  ../kaithem-plugin-datasette
```

## Use

You will then have access to the datasette resource type in any module. Create one, and
on the modules page you will find a link to a datasette instance, with editing plugins enabled,
security integrated with Kaithem's user auth, and cluster map tiles cached by the server.

This plugin does not really add many new features.