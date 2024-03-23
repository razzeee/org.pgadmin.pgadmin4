# pgAdmin Flatpak

## Building

```
flatpak-builder build-dir --user --ccache --force-clean --install org.pgadmin.pgadmin4.yml
```

Then you can run it via the command line:

```
flatpak run org.pgadmin.pgadmin4
```

or just search for the installed app on your system
