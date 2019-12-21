# appdaemon-widgets
Appdaemon Widgets for Home Assistant 

This is an AppDaeomon [HADashboard](https://www.home-assistant.io/docs/ecosystem/hadashboard/) widget radio allows to stream online radio channels to media_player on [Home Assistant](https://www.home-assistant.io). 
It provides a volume slider and it shows the current state, volume and radio station.

I like to improve to get the current listening radio station preselected on the drop-down menu. But first it will take me weeks to set up my HADashboard to control my home.

```yaml
myradio:
    widget_type: radio
    entity: media_player.chromecast
    title: Radio 
    title2: Wohnzimmer
    inputoptions: [ 
      { name: 'Swiss Pop', url: 'http://stream.srg-ssr.ch/m/rsp/aacp_96' },
      { name: 'Radio Energy Bern', url: 'https://energybern.ice.infomaniak.ch/energybern-high.mp3' },
      { name: 'Energy 80s', url: 'http://energyzuerich.ice.infomaniak.ch/energy80s-high.mp3' },
      { name: 'Energy 90s', url: 'http://energyzuerich.ice.infomaniak.ch/energy90s-high.mp3' },
      { name: 'Energy 00s', url: 'http://energyzuerich.ice.infomaniak.ch/energy00s-high.mp3' },
      { name: 'Energy Black', url: 'http://energyzuerich.ice.infomaniak.ch/energyblack-high.mp3' },
      { name: 'Energy Dance', url: 'http://energyzuerich.ice.infomaniak.ch/energydance-high.mp3' },
      { name: 'Energy Rock', url: 'http://energyzuerich.ice.infomaniak.ch/energyrock-high.mp3' },
      { name: 'Energy Soundtrack', url: 'http://energyzuerich.ice.infomaniak.ch/energysoundtrack-high.mp3' },
      { name: 'Energy Swiss', url: 'http://energyzuerich.ice.infomaniak.ch/energyswiss-high.mp3' },
      { name: 'Energy Charts', url: 'http://energyzuerich.ice.infomaniak.ch/energycharts-high.mp3' },
      { name: 'Energy Live', url: 'http://energyzuerich.ice.infomaniak.ch/energylive-high.mp3' },
      { name: 'Energy Lounge', url: 'http://energyzuerich.ice.infomaniak.ch/energylounge-high.mp3' },
      { name: 'SRF 1', url: 'http://stream.srg-ssr.ch/m/drs1/mp3_128' },
      { name: 'SRF Virus', url: 'http://stream.srg-ssr.ch/m/drsvirus/mp3_128' },
      { name: 'SRF 4 News', url: 'http://stream.srg-ssr.ch/m/drs4news/mp3_128' },
      { name: 'SRF 2 Kultur', url: 'http://stream.srg-ssr.ch/m/drs2/mp3_128' },
      { name: 'SRF 3', url: 'http://stream.srg-ssr.ch/m/drs3/mp3_128' } 
    ]
    icon_playing: fas-pause
    icon_idle: fas-play
    icon_off: fas-play
    icon_pause: fas-play
```
