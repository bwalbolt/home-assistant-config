#### Backup of main configuration files and notes on in development features
---
### nVIDIA Shield Code
#### Hulu
```
entity_id: media_player.nvidia_shield
command: 'am start -a android.intent.action.VIEW -d https://www.hulu.com/watch/8c2b6d15-ecdb-4c15-a0d3-6c7d07b0f323 -n com.hulu.livingroomplus/.WKFactivity'
```
#### Netflix
```
entity_id: media_player.nvidia_shield
command: 'am start -c android.intent.category.LEANBACK_LAUNCHER -a android.intent.action.VIEW -d http://www.netflix.com/watch/70136120 -f 0x10808000 -e source 30 com.netflix.ninja/.MainActivity'
```
#### HBO (fails auto-play)
```
entity_id: media_player.nvidia_shield
command: 'am start -c android.intent.category.LEANBACK_LAUNCHER -a android.intent.action.VIEW -d https://play.hbomax.com/episode/urn:hbo:episode:GXt_JNgGdSJuSkwEAAAmA -n com.hbo.hbonow/com.hbo.go.LaunchActivity'
```