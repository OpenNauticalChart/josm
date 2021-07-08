JOSM Map Paint Styles (https://josm.openstreetmap.de/wiki/StylesSource):
- INT1_MapCSS.mapcss (rendering of nautical symbols according to IHO standard INT-1)
- CEVNI_MapCSS.mapcss (rendering of notice marks according to European standard CEVNI)
- BNIWR_MapCSS.mapcss (rendering of notice marks according to Brazilian BNIWR standard)
- PPWBC_MapCSS.mapcss (rendering of notice marks according to Brazilian/Paraguaian PPWBC standard)
- RIWR_MapCSS.mapcss (rendering of notice marks according to russian RIWR standard)

JOSM Tagging Presets (https://josm.openstreetmap.de/wiki/PresetsSource):
- INT-1-preset.xml
- Presets_Hafen.xml

JOSM Tagging Validator (https://josm.openstreetmap.de/wiki/RulesSource):
- Seamarks.validator.mapcss

To deploy these styles
- start JOSM
- Edit > Preferences > Map Settings > Map Paint Style
- Add a new style by entering URL
- eg. https://raw.githubusercontent.com/OpenNauticalChart/josm/master/INT1_MapCSS.mapcss

To deploy these presets
- start JOSM
- Edit > Preferences > Map Settings > Tagging Presets
- Add a new preset by entering URL
- eg. https://raw.githubusercontent.com/OpenNauticalChart/josm/master/INT-1-preset.xml

To deploy this validator
- start JOSM
- Edit > Preferences > Map Settings > Data Validator
- Add a new rule by entering URL
- eg. https://raw.githubusercontent.com/OpenNauticalChart/josm/master/Seamarks.validator.mapcss

<b>Just make sure, the URL points to the RAW file content!</b>
