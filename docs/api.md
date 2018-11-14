<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

- [KPPlaylistConfigObject][1]
  - [Parameters][2]
- [KPPlaylistCountdownOptions][3]
  - [Parameters][4]
- [KPPlaylistItemConfigObject][5]
  - [Properties][6]
- [KPPlaylistMetadata][7]
  - [Properties][8]
- [KPPlaylistOptions][9]
  - [Properties][10]
- [BaseRemotePlayer][11]
  - [Parameters][12]
  - [loadMedia][13]
    - [Parameters][14]
  - [setMedia][15]
    - [Parameters][16]
  - [getMediaInfo][17]
  - [configure][18]
    - [Parameters][19]
  - [ready][20]
  - [load][21]
  - [play][22]
  - [pause][23]
  - [reset][24]
  - [destroy][25]
  - [isLive][26]
    - [Examples][27]
  - [isDvr][28]
    - [Examples][29]
  - [seekToLiveEdge][30]
  - [getStartTimeOfDvrWindow][31]
    - [Examples][32]
  - [getTracks][33]
    - [Parameters][34]
    - [Examples][35]
  - [getActiveTracks][36]
    - [Examples][37]
  - [selectTrack][38]
    - [Parameters][39]
  - [hideTextTrack][40]
  - [enableAdaptiveBitrate][41]
  - [isAdaptiveBitrateEnabled][42]
    - [Examples][43]
  - [setTextDisplaySettings][44]
    - [Parameters][45]
  - [startCasting][46]
  - [stopCasting][47]
  - [isCasting][48]
    - [Examples][49]
  - [isCastAvailable][50]
    - [Examples][51]
  - [getCastSession][52]
    - [Examples][53]
  - [isVr][54]
    - [Examples][55]
  - [toggleVrStereoMode][56]
  - [isInVrStereoMode][57]
    - [Examples][58]
  - [ads][59]
    - [Examples][60]
  - [textStyle][61]
    - [Parameters][62]
  - [textStyle][63]
    - [Examples][64]
  - [buffered][65]
    - [Examples][66]
  - [currentTime][67]
    - [Parameters][68]
  - [currentTime][69]
    - [Examples][70]
  - [duration][71]
    - [Examples][72]
  - [volume][73]
    - [Parameters][74]
  - [volume][75]
    - [Examples][76]
  - [paused][77]
    - [Examples][78]
  - [ended][79]
    - [Examples][80]
  - [seeking][81]
    - [Examples][82]
  - [muted][83]
    - [Parameters][84]
  - [muted][85]
    - [Examples][86]
  - [src][87]
    - [Examples][88]
  - [poster][89]
    - [Examples][90]
  - [playbackRate][91]
    - [Parameters][92]
  - [playbackRate][93]
    - [Examples][94]
  - [engineType][95]
    - [Examples][96]
  - [streamType][97]
    - [Examples][98]
  - [config][99]
  - [type][100]
    - [Examples][101]
  - [defaultConfig][102]
    - [Examples][103]
  - [Type][104]
    - [Examples][105]
  - [isSupported][106]
    - [Examples][107]
- [CastEventType][108]
  - [Examples][109]
- [PlayerSnapshot][110]
  - [Parameters][111]
  - [startTime][112]
  - [autoplay][113]
  - [audioLanguage][114]
  - [textLanguage][115]
  - [mediaInfo][116]
  - [textStyle][117]
  - [advertising][118]
  - [volume][119]
  - [muted][120]
- [RemoteControl][121]
  - [Parameters][122]
  - [getPlayerSnapshot][123]
  - [getUIWrapper][124]
  - [onRemoteDeviceDisconnected][125]
    - [Parameters][126]
  - [onRemoteDeviceConnected][127]
    - [Parameters][128]
  - [onRemoteDeviceAvailable][129]
    - [Parameters][130]
  - [onRemoteDeviceConnecting][131]
  - [onRemoteDeviceDisconnecting][132]
  - [onRemoteDeviceConnectFailed][133]
- [RemotePayload][134]
  - [Parameters][135]
  - [player][136]
- [RemoteConnectedPayload][137]
  - [Parameters][138]
  - [ui][139]
  - [session][140]
- [RemoteDisconnectedPayload][141]
  - [Parameters][142]
  - [snapshot][143]
- [RemoteAvailablePayload][144]
  - [Parameters][145]
  - [available][146]
- [RemotePlayerUI][147]
  - [playbackUI][148]
    - [Parameters][149]
  - [idleUI][150]
    - [Parameters][151]
  - [adsUI][152]
    - [Parameters][153]
  - [liveUI][154]
    - [Parameters][155]
  - [errorUI][156]
    - [Parameters][157]
  - [uis][158]
- [IRemotePlayer][159]
  - [textStyle][160]
  - [muted][161]
  - [playbackRate][162]
  - [volume][163]
  - [currentTime][164]
  - [buffered][165]
  - [duration][166]
  - [paused][167]
  - [ended][168]
  - [seeking][169]
  - [src][170]
  - [poster][171]
  - [config][172]
  - [engineType][173]
  - [streamType][174]
  - [type][175]
  - [ads][176]
  - [addEventListener][177]
    - [Parameters][178]
  - [removeEventListener][179]
    - [Parameters][180]
  - [dispatchEvent][181]
    - [Parameters][182]
  - [loadMedia][183]
    - [Parameters][184]
  - [setMedia][185]
    - [Parameters][186]
  - [getMediaInfo][187]
  - [configure][188]
    - [Parameters][189]
  - [ready][190]
  - [load][191]
  - [play][192]
  - [pause][193]
  - [reset][194]
  - [destroy][195]
  - [isLive][196]
  - [isDvr][197]
  - [seekToLiveEdge][198]
  - [getStartTimeOfDvrWindow][199]
  - [getTracks][200]
    - [Parameters][201]
  - [getActiveTracks][202]
  - [selectTrack][203]
    - [Parameters][204]
  - [hideTextTrack][205]
  - [enableAdaptiveBitrate][206]
  - [isAdaptiveBitrateEnabled][207]
  - [setTextDisplaySettings][208]
    - [Parameters][209]
  - [startCasting][210]
  - [stopCasting][211]
  - [isCasting][212]
  - [isCastAvailable][213]
  - [getCastSession][214]
  - [isVr][215]
  - [toggleVrStereoMode][216]
  - [isInVrStereoMode][217]
  - [Type][218]
  - [isSupported][219]
- [RemoteSession][220]
  - [Parameters][221]
  - [deviceFriendlyName][222]
  - [id][223]
  - [resuming][224]
- [PlaylistEventType][225]
  - [Examples][226]
- [PlaylistItem][227]
  - [Parameters][228]
  - [sources][229]
  - [config][230]
  - [isPlayable][231]
- [PlaylistManager][232]
  - [Parameters][233]
  - [playNext][234]
  - [playPrev][235]
  - [playItem][236]
    - [Parameters][237]
  - [items][238]
  - [next][239]
  - [prev][240]
  - [id][241]
  - [metadata][242]
  - [countdown][243]
  - [options][244]

## KPPlaylistConfigObject

Type: [Object][245]

### Parameters

- `id` **[string][246]** The playlist id
- `metadata` **[KPPlaylistMetadata][247]** The playlist metadata
- `options` **[KPPlaylistOptions][248]** The playlist options
- `countdown` **[KPPlaylistCountdownOptions][249]** The playlist countdown config
- `items` **[Array][250]&lt;[PlaylistItem][251]>** The playlist items

## KPPlaylistCountdownOptions

Type: [Object][245]

### Parameters

- `timeToShow` **[number][252]?** When the countdown will appear (by default is towards the end)
- `duration` **[number][252]** How match time the countdown will appear (optional, default `10`)
- `showing` **[boolean][253]** Whether to show the countdown (optional, default `true`)

## KPPlaylistItemConfigObject

Type: [Object][245]

### Properties

- `countdown` **[KPPlaylistCountdownOptions][249]?** Countdown options

## KPPlaylistMetadata

Type: [Object][245]

### Properties

- `name` **[string][246]** The playlist name
- `description` **[string][246]** The playlist description

## KPPlaylistOptions

Type: [Object][245]

### Properties

- `autoContinue` **[boolean][253]** Whether to continue to the next item automatically

## BaseRemotePlayer

**Extends FakeEventTarget**

Basic remote player.
Implements the Kaltura Player playback, ads, tracks,vr and cast APIs.
Remote players should extend this class and implement the needed API.

### Parameters

- `name` **[string][246]** Remote player name.
- `config` **[Object][245]** Cast configuration.
- `remoteControl` **[RemoteControl][254]** Remote control.

### loadMedia

Loads a media to the receiver application.

#### Parameters

- `mediaInfo` **[Object][245]** The entry media info.

Returns **[Promise][255]&lt;void>** Promise to indicate load succeed or failed.

### setMedia

Sets a media to the remote player..

#### Parameters

- `mediaConfig` **[Object][245]** Media configuration to set.

Returns **void**

### getMediaInfo

Gets the media Info.

Returns **[Object][245]?** The media info.

### configure

Configure the remote player

#### Parameters

- `config` **[Object][245]** Configuration to set. (optional, default `{}`)

Returns **void**

### ready

The remote player readiness.

Returns **[Promise][255]&lt;any>** Promise which resolved when the remote player is ready.

### load

Load the remote player.

Returns **void**

### play

Play/resume the remote player.

Returns **void**

### pause

Pause the remote player.

Returns **void**

### reset

Reset the remote player.

Returns **void**

### destroy

Destroy the remote player.

Returns **void**

### isLive

#### Examples

```javascript
BaseRemotePlayer.prototype.isLive(); // false
```

Returns **[boolean][253]** Whether the current playback is a live playback.

### isDvr

#### Examples

```javascript
BaseRemotePlayer.prototype.isDvr(); // false
```

Returns **[boolean][253]** Whether the current live playback has DVR window. In case of non-live playback will return false.

### seekToLiveEdge

Seeks to the live edge.

Returns **void**

### getStartTimeOfDvrWindow

#### Examples

```javascript
BaseRemotePlayer.prototype.getStartTimeOfDvrWindow(); // 0
```

Returns **[number][252]** The start time of the DVR window.

### getTracks

#### Parameters

- `type` **[string][246]?** Track type.

#### Examples

```javascript
BaseRemotePlayer.prototype.getTracks(); // []
```

Returns **[Array][250]&lt;Track>** The remote player tracks.

### getActiveTracks

#### Examples

```javascript
BaseRemotePlayer.prototype.getTracks(); // {audio: undefined, video: undefined, text: undefined}
```

Returns **[Object][245]** The remote player active tracks.

### selectTrack

Select a certain track to be active.

#### Parameters

- `track` **Track** The track to activate.

Returns **void**

### hideTextTrack

Hides the active text track.

Returns **void**

### enableAdaptiveBitrate

Enables automatic adaptive bitrate switching.

Returns **void**

### isAdaptiveBitrateEnabled

#### Examples

```javascript
BaseRemotePlayer.prototype.isAdaptiveBitrateEnabled(); // true
```

Returns **[boolean][253]** Whether adaptive bitrate is enabled.

### setTextDisplaySettings

Sets the text display settings.

#### Parameters

- `settings` **[Object][245]** Text settings.

Returns **void**

### startCasting

Start casting.

Returns **[Promise][255]&lt;any>** A promise to indicate session is starting, or failed

### stopCasting

Stops the current cast session.

Returns **void**

### isCasting

#### Examples

```javascript
BaseRemotePlayer.prototype.isCasting(); // true
```

Returns **[boolean][253]** Whether casting is currently active.

### isCastAvailable

#### Examples

```javascript
BaseRemotePlayer.prototype.isCastAvailable(); // true
```

Returns **[boolean][253]** Whether casting is available.

### getCastSession

Gets the current remote session.

#### Examples

```javascript
BaseRemotePlayer.prototype.getCastSession(); // new RemoteSession('', '')
```

Returns **[RemoteSession][256]** The remote session.

### isVr

#### Examples

```javascript
BaseRemotePlayer.prototype.isVr(); // false
```

Returns **[boolean][253]** Whether the current media is of VR type (360 content).

### toggleVrStereoMode

Toggles VR mode on the current content.

Returns **void**

### isInVrStereoMode

#### Examples

```javascript
BaseRemotePlayer.prototype.isInVrStereoMode(); // false
```

Returns **[boolean][253]** Whether the current content displayed in VR mode.

### ads

The remote player ads controller.

Type: [Object][245]?

#### Examples

```javascript
BaseRemotePlayer.prototype.ads; // null
```

Returns **[Object][245]?**

### textStyle

Setter.

#### Parameters

- `style` **TextStyle** The text style to set.

Returns **void**

### textStyle

Getter.

#### Examples

```javascript
BaseRemotePlayer.prototype.textStyle; // new TextStyle()
```

Returns **TextStyle** The current text style.

### buffered

Gets the first buffered range of the remote player.

#### Examples

```javascript
BaseRemotePlayer.prototype.buffered; // []
```

Returns **[Array][250]&lt;any>** First buffered range in seconds.

### currentTime

Setter.

#### Parameters

- `to` **[number][252]** The number to set in seconds.

Returns **void**

### currentTime

Getter.

#### Examples

```javascript
BaseRemotePlayer.prototype.currentTime; // 0
```

Returns **[number][252]** The current time in seconds.

### duration

#### Examples

```javascript
BaseRemotePlayer.prototype.duration; // 0
```

Returns **[number][252]** The duration in seconds.

### volume

Setter.

#### Parameters

- `vol` **[number][252]** The volume to set in the range of 0-1.

Returns **void**

### volume

Getter.

#### Examples

```javascript
BaseRemotePlayer.prototype.volume; // 1
```

Returns **[number][252]** The current volume in the range of 0-1.

### paused

#### Examples

```javascript
BaseRemotePlayer.prototype.paused; // false
```

Returns **[boolean][253]** Whether the cast player is in paused state.

### ended

#### Examples

```javascript
BaseRemotePlayer.prototype.ended; // false
```

Returns **[boolean][253]** Whether the cast player is in ended state.

### seeking

#### Examples

```javascript
BaseRemotePlayer.prototype.seeking; // false
```

Returns **[boolean][253]** Whether the cast player is in seeking state.

### muted

Setter.

#### Parameters

- `mute` **[boolean][253]** The mute value to set.

Returns **void**

### muted

Getter.

#### Examples

```javascript
BaseRemotePlayer.prototype.muted; // false
```

Returns **[boolean][253]** The muted state.

### src

#### Examples

```javascript
BaseRemotePlayer.prototype.src; // ''
```

Returns **[string][246]** The current playing source url.

### poster

#### Examples

```javascript
BaseRemotePlayer.prototype.poster; // ''
```

Returns **[string][246]** The current poster url.

### playbackRate

Setter.

#### Parameters

- `rate` **[number][252]** The playback rate to set.

Returns **void**

### playbackRate

#### Examples

```javascript
BaseRemotePlayer.prototype.playbackRate; // 1
```

Returns **[string][246]** The current playback rate.

### engineType

#### Examples

```javascript
BaseRemotePlayer.prototype.engineType; // ''
```

Returns **[string][246]** The active engine type.

### streamType

#### Examples

```javascript
BaseRemotePlayer.prototype.streamType; // ''
```

Returns **[string][246]** The active stream type.

### config

Returns **[Object][245]** The runtime cast config.

### type

#### Examples

```javascript
BaseRemotePlayer.prototype.type; // BaseRemotePlayer.Type
```

Returns **[string][246]** The remote player type.

### defaultConfig

Default configuration of the remote player.

Type: [Object][245]

#### Examples

```javascript
BaseRemotePlayer.defaultConfig; // {}
```

### Type

Remote player type.

Type: [string][246]

#### Examples

```javascript
BaseRemotePlayer.Type; // 'BaseRemotePlayer'
```

### isSupported

#### Examples

```javascript
BaseRemotePlayer.isSupported(); // true
```

Returns **[boolean][253]** Whether the remote player is supported in the current environment.

## CastEventType

Type: [Object][245]

### Examples

```javascript
// Events lifecycle
1. CAST_AVAILABLE
2. CAST_SESSION_STARTING
3. CAST_SESSION_STARTED || CAST_SESSION_START_FAILED -> X
4. CAST_SESSION_ENDING
5. CAST_SESSION_ENDED
```

```javascript
// How to use
player.addEventListener(KalturaPlayer.cast.CastEventType.CAST_SESSION_STARTED, e => {
  console.log(e.session);
};
```

## PlayerSnapshot

### Parameters

- `player` **KalturaPlayer** The Kaltura player.

### startTime

Type: [number][252]

### autoplay

Type: [boolean][253]

### audioLanguage

Type: [string][246]

### textLanguage

Type: [string][246]

### mediaInfo

Type: ProviderMediaInfoObject

### textStyle

Type: TextStyle

### advertising

Type: [Object][245]

### volume

Type: [number][252]

### muted

Type: [boolean][253]

## RemoteControl

### Parameters

- `player` **KalturaPlayer** The Kaltura player.

### getPlayerSnapshot

Gets the player snapshot.

Type: [Function][257]

Returns **[PlayerSnapshot][258]** player snapshot.

### getUIWrapper

Gets the UI wrapper.

Type: [Function][257]

Returns **UIWrapper** The UI wrapper.

### onRemoteDeviceDisconnected

On remote device disconnected handler.

Type: [Function][257]

#### Parameters

- `payload` **[RemoteDisconnectedPayload][259]** disconnected payload.

Returns **void**

### onRemoteDeviceConnected

On remote device connected handler.

Type: [Function][257]

#### Parameters

- `payload` **[RemoteConnectedPayload][260]** connected payload.

Returns **void**

### onRemoteDeviceAvailable

On remote device available handler.

Type: [Function][257]

#### Parameters

- `payload` **[RemoteAvailablePayload][261]** available payload.

Returns **void**

### onRemoteDeviceConnecting

On remote device connecting handler.

Type: [Function][257]

Returns **void**

### onRemoteDeviceDisconnecting

On remote device disconnecting handler.

Type: [Function][257]

Returns **void**

### onRemoteDeviceConnectFailed

On remote device connect failed handler.

Type: [Function][257]

Returns **void**

## RemotePayload

### Parameters

- `player` **[BaseRemotePlayer][262]** The active remote player.

### player

The active remote player.

Type: [BaseRemotePlayer][262]

Returns **[BaseRemotePlayer][262]**

## RemoteConnectedPayload

**Extends RemotePayload**

### Parameters

- `player` **[BaseRemotePlayer][262]** The active remote player.
- `session` **[RemoteSession][256]** The remote session.
- `ui` **[RemotePlayerUI][263]?** Optional remote player UI preset.

### ui

Remote player UI preset.

Type: [RemotePlayerUI][263]?

Returns **[RemotePlayerUI][263]?**

### session

Remote session.

Type: [RemoteSession][256]

Returns **[RemoteSession][256]?**

## RemoteDisconnectedPayload

**Extends RemotePayload**

### Parameters

- `player` **[BaseRemotePlayer][262]** The active remote player.
- `snapshot` **[PlayerSnapshot][258]** The remote player snapshot.

### snapshot

Remote player snapshot.

Type: [PlayerSnapshot][258]

Returns **[PlayerSnapshot][258]**

## RemoteAvailablePayload

**Extends RemotePayload**

### Parameters

- `player` **[BaseRemotePlayer][262]** The active remote player.
- `available` **[boolean][253]** Remote player availability.

### available

Remote player availability.

Type: [boolean][253]

Returns **[boolean][253]**

## RemotePlayerUI

### playbackUI

Playback UI of the remote player.

#### Parameters

- `props` **[Object][245]** UI creation parameters.

Returns **React$Element&lt;any>** Component.

### idleUI

Idle UI of the remote player.

#### Parameters

- `props` **[Object][245]** UI creation parameters.

Returns **React$Element&lt;any>** Component.

### adsUI

Idle UI of the remote player.

#### Parameters

- `props` **[Object][245]** UI creation parameters.

Returns **React$Element&lt;any>** Component.

### liveUI

Live UI of the remote player.

#### Parameters

- `props` **[Object][245]** UI creation parameters.

Returns **React$Element&lt;any>** Component.

### errorUI

Error UI of the remote player.

#### Parameters

- `props` **[Object][245]** UI creation parameters.

Returns **React$Element&lt;any>** Component.

### uis

UI presets.

Type: [Array][250]&lt;UIPreset>

Returns **[Array][250]&lt;UIPreset>**

## IRemotePlayer

### textStyle

Type: TextStyle

### muted

Type: [boolean][253]

### playbackRate

Type: [number][252]

### volume

Type: [number][252]

### currentTime

Type: [number][252]

### buffered

Type: [number][252]

### duration

Type: [number][252]

### paused

Type: [boolean][253]

### ended

Type: [boolean][253]

### seeking

Type: [boolean][253]

### src

Type: [string][246]

### poster

Type: [string][246]

### config

Type: [Object][245]

### engineType

Type: [string][246]

### streamType

Type: [string][246]

### type

Type: [string][246]

### ads

Type: [Object][245]

### addEventListener

#### Parameters

- `type` **[string][246]**
- `listener` **[Function][257]**

### removeEventListener

#### Parameters

- `type` **[string][246]**
- `listener` **[Function][257]**

### dispatchEvent

#### Parameters

- `event` **FakeEvent**

### loadMedia

#### Parameters

- `mediaInfo` **[Object][245]**

### setMedia

#### Parameters

- `mediaConfig` **[Object][245]**

### getMediaInfo

Returns **[Object][245]**

### configure

#### Parameters

- `config` **[Object][245]**

### ready

Returns **[Promise][255]&lt;any>**

### load

### play

### pause

### reset

### destroy

### isLive

Returns **[boolean][253]**

### isDvr

Returns **[boolean][253]**

### seekToLiveEdge

### getStartTimeOfDvrWindow

Returns **[number][252]**

### getTracks

#### Parameters

- `type` **[string][246]?**

Returns **[Array][250]&lt;Track>**

### getActiveTracks

Returns **[Object][245]**

### selectTrack

#### Parameters

- `track` **Track**

### hideTextTrack

### enableAdaptiveBitrate

### isAdaptiveBitrateEnabled

Returns **[boolean][253]**

### setTextDisplaySettings

#### Parameters

- `settings` **[Object][245]**

### startCasting

### stopCasting

### isCasting

Returns **[boolean][253]**

### isCastAvailable

Returns **[boolean][253]**

### getCastSession

Returns **[RemoteSession][256]**

### isVr

Returns **[boolean][253]**

### toggleVrStereoMode

### isInVrStereoMode

Returns **[boolean][253]**

### Type

Type: [string][246]

### isSupported

Returns **[boolean][253]**

## RemoteSession

### Parameters

- `id` **[string][246]** Session ID.
- `friendlyName` **[string][246]** Receiver friendly name.
- `resuming` **[boolean][253]?** Whether the session is resuming.

### deviceFriendlyName

Receiver friendly name.

Type: [string][246]

Returns **[string][246]**

### id

Session ID.

Type: [string][246]

Returns **[string][246]**

### resuming

Whether the session is resuming.

Type: [boolean][253]?

Returns **[boolean][253]?**

## PlaylistEventType

Type: [Object][245]

### Examples

```javascript
// Events lifecycle
1. PLAYLIST_LOADED
2. PLAYLIST_ITEM_CHANGED (multiple)
3. PLAYLIST_ENDED
```

```javascript
// How to use
player.addEventListener(KalturaPlayer.playlist.PlaylistEventType.PLAYLIST_LOADED, e => {
  console.log(e.payload.playlist.metadata.name);
};
```

## PlaylistItem

### Parameters

- `sources` **ProviderMediaConfigSourcesObject?** The item sources
- `config` **[KPPlaylistItemConfigObject][264]?** The item config

### sources

Playlist item sources

Type: ProviderMediaConfigSourcesObject?

Returns **ProviderMediaConfigSourcesObject?**

### config

Playlist item config

Type: [KPPlaylistItemConfigObject][264]?

Returns **[KPPlaylistItemConfigObject][264]?**

### isPlayable

Returns **[boolean][253]** = Whether the playlist item has sources to play

## PlaylistManager

### Parameters

- `player` **KalturaPlayer** The player instance
- `options` **KPOptionsObject** The player config object

### playNext

Play the next item

Returns **void**

### playPrev

Play the previous item

Returns **void**

### playItem

Play a specific item

#### Parameters

- `index` **[number][252]** The index of the item to play

Returns **void**

### items

Playlist items

Type: [Array][250]&lt;[PlaylistItem][251]>

Returns **[Array][250]&lt;[PlaylistItem][251]>**

### next

Next item

Type: [PlaylistItem][251]?

Returns **[PlaylistItem][251]?**

### prev

Previous item

Type: [PlaylistItem][251]?

Returns **[PlaylistItem][251]?**

### id

Playlist id

Type: [string][246]

Returns **[string][246]**

### metadata

Playlist metadata

Type: [KPPlaylistMetadata][247]

Returns **[KPPlaylistMetadata][247]**

### countdown

Playlist countdown

Type: [KPPlaylistCountdownOptions][249]

Returns **[KPPlaylistCountdownOptions][249]**

### options

Playlist options

Type: [KPPlaylistOptions][248]

Returns **[KPPlaylistOptions][248]**

[1]: #kpplaylistconfigobject
[2]: #parameters
[3]: #kpplaylistcountdownoptions
[4]: #parameters-1
[5]: #kpplaylistitemconfigobject
[6]: #properties
[7]: #kpplaylistmetadata
[8]: #properties-1
[9]: #kpplaylistoptions
[10]: #properties-2
[11]: #baseremoteplayer
[12]: #parameters-2
[13]: #loadmedia
[14]: #parameters-3
[15]: #setmedia
[16]: #parameters-4
[17]: #getmediainfo
[18]: #configure
[19]: #parameters-5
[20]: #ready
[21]: #load
[22]: #play
[23]: #pause
[24]: #reset
[25]: #destroy
[26]: #islive
[27]: #examples
[28]: #isdvr
[29]: #examples-1
[30]: #seektoliveedge
[31]: #getstarttimeofdvrwindow
[32]: #examples-2
[33]: #gettracks
[34]: #parameters-6
[35]: #examples-3
[36]: #getactivetracks
[37]: #examples-4
[38]: #selecttrack
[39]: #parameters-7
[40]: #hidetexttrack
[41]: #enableadaptivebitrate
[42]: #isadaptivebitrateenabled
[43]: #examples-5
[44]: #settextdisplaysettings
[45]: #parameters-8
[46]: #startcasting
[47]: #stopcasting
[48]: #iscasting
[49]: #examples-6
[50]: #iscastavailable
[51]: #examples-7
[52]: #getcastsession
[53]: #examples-8
[54]: #isvr
[55]: #examples-9
[56]: #togglevrstereomode
[57]: #isinvrstereomode
[58]: #examples-10
[59]: #ads
[60]: #examples-11
[61]: #textstyle
[62]: #parameters-9
[63]: #textstyle-1
[64]: #examples-12
[65]: #buffered
[66]: #examples-13
[67]: #currenttime
[68]: #parameters-10
[69]: #currenttime-1
[70]: #examples-14
[71]: #duration
[72]: #examples-15
[73]: #volume
[74]: #parameters-11
[75]: #volume-1
[76]: #examples-16
[77]: #paused
[78]: #examples-17
[79]: #ended
[80]: #examples-18
[81]: #seeking
[82]: #examples-19
[83]: #muted
[84]: #parameters-12
[85]: #muted-1
[86]: #examples-20
[87]: #src
[88]: #examples-21
[89]: #poster
[90]: #examples-22
[91]: #playbackrate
[92]: #parameters-13
[93]: #playbackrate-1
[94]: #examples-23
[95]: #enginetype
[96]: #examples-24
[97]: #streamtype
[98]: #examples-25
[99]: #config
[100]: #type
[101]: #examples-26
[102]: #defaultconfig
[103]: #examples-27
[104]: #type-1
[105]: #examples-28
[106]: #issupported
[107]: #examples-29
[108]: #casteventtype
[109]: #examples-30
[110]: #playersnapshot
[111]: #parameters-14
[112]: #starttime
[113]: #autoplay
[114]: #audiolanguage
[115]: #textlanguage
[116]: #mediainfo
[117]: #textstyle-2
[118]: #advertising
[119]: #volume-2
[120]: #muted-2
[121]: #remotecontrol
[122]: #parameters-15
[123]: #getplayersnapshot
[124]: #getuiwrapper
[125]: #onremotedevicedisconnected
[126]: #parameters-16
[127]: #onremotedeviceconnected
[128]: #parameters-17
[129]: #onremotedeviceavailable
[130]: #parameters-18
[131]: #onremotedeviceconnecting
[132]: #onremotedevicedisconnecting
[133]: #onremotedeviceconnectfailed
[134]: #remotepayload
[135]: #parameters-19
[136]: #player
[137]: #remoteconnectedpayload
[138]: #parameters-20
[139]: #ui
[140]: #session
[141]: #remotedisconnectedpayload
[142]: #parameters-21
[143]: #snapshot
[144]: #remoteavailablepayload
[145]: #parameters-22
[146]: #available
[147]: #remoteplayerui
[148]: #playbackui
[149]: #parameters-23
[150]: #idleui
[151]: #parameters-24
[152]: #adsui
[153]: #parameters-25
[154]: #liveui
[155]: #parameters-26
[156]: #errorui
[157]: #parameters-27
[158]: #uis
[159]: #iremoteplayer
[160]: #textstyle-3
[161]: #muted-3
[162]: #playbackrate-2
[163]: #volume-3
[164]: #currenttime-2
[165]: #buffered-1
[166]: #duration-1
[167]: #paused-1
[168]: #ended-1
[169]: #seeking-1
[170]: #src-1
[171]: #poster-1
[172]: #config-1
[173]: #enginetype-1
[174]: #streamtype-1
[175]: #type-2
[176]: #ads-1
[177]: #addeventlistener
[178]: #parameters-28
[179]: #removeeventlistener
[180]: #parameters-29
[181]: #dispatchevent
[182]: #parameters-30
[183]: #loadmedia-1
[184]: #parameters-31
[185]: #setmedia-1
[186]: #parameters-32
[187]: #getmediainfo-1
[188]: #configure-1
[189]: #parameters-33
[190]: #ready-1
[191]: #load-1
[192]: #play-1
[193]: #pause-1
[194]: #reset-1
[195]: #destroy-1
[196]: #islive-1
[197]: #isdvr-1
[198]: #seektoliveedge-1
[199]: #getstarttimeofdvrwindow-1
[200]: #gettracks-1
[201]: #parameters-34
[202]: #getactivetracks-1
[203]: #selecttrack-1
[204]: #parameters-35
[205]: #hidetexttrack-1
[206]: #enableadaptivebitrate-1
[207]: #isadaptivebitrateenabled-1
[208]: #settextdisplaysettings-1
[209]: #parameters-36
[210]: #startcasting-1
[211]: #stopcasting-1
[212]: #iscasting-1
[213]: #iscastavailable-1
[214]: #getcastsession-1
[215]: #isvr-1
[216]: #togglevrstereomode-1
[217]: #isinvrstereomode-1
[218]: #type-3
[219]: #issupported-1
[220]: #remotesession
[221]: #parameters-37
[222]: #devicefriendlyname
[223]: #id
[224]: #resuming
[225]: #playlisteventtype
[226]: #examples-31
[227]: #playlistitem
[228]: #parameters-38
[229]: #sources
[230]: #config-2
[231]: #isplayable
[232]: #playlistmanager
[233]: #parameters-39
[234]: #playnext
[235]: #playprev
[236]: #playitem
[237]: #parameters-40
[238]: #items
[239]: #next
[240]: #prev
[241]: #id-1
[242]: #metadata
[243]: #countdown
[244]: #options
[245]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object
[246]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String
[247]: #kpplaylistmetadata
[248]: #kpplaylistoptions
[249]: #kpplaylistcountdownoptions
[250]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Array
[251]: #playlistitem
[252]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number
[253]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean
[254]: #remotecontrol
[255]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise
[256]: #remotesession
[257]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Statements/function
[258]: #playersnapshot
[259]: #remotedisconnectedpayload
[260]: #remoteconnectedpayload
[261]: #remoteavailablepayload
[262]: #baseremoteplayer
[263]: #remoteplayerui
[264]: #kpplaylistitemconfigobject