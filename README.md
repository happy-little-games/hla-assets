# hla-assets

Public images for [HLA Wingman](https://hla.gg), kept here because some sites only show images from hosts they recognise. Steam's Workshop descriptions did not show a banner hosted on hla.gg, and they do show images from GitHub.

## Workshop banner

`workshop-banner.png` is a banner map makers can put in their Steam Workshop description, linking players to the map's page on hla.gg:

```
[url=https://hla.gg/maps/vault/?utm_campaign=vault-banner][img]https://raw.githubusercontent.com/happy-little-games/hla-assets/main/workshop-banner.png[/img][/url]
```

Put the map's slug from its page at https://hla.gg/maps/ in place of both `vault`s. Keep the link to that one parameter: Steam turns a second one's `&` into `&amp;` and breaks it.

To update the banner on every Workshop page that uses it, replace `workshop-banner.png` on `main`, keeping the file name. GitHub serves it with a 5-minute cache, so pages show the new version within minutes. The file is the 2400x300 export of the design in HLA's main repository.
