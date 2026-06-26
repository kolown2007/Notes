

##### **selects stills from video**

```bash
$d = [int][double](ffprobe -v error -show_entries format=duration -of default=noprint_wrappers=1:nokey=1 road.mp4); ffmpeg -ss $(Get-Random -Maximum $d) -i road.mp4 -vframes 1 -vf "scale=1000:1000,lutrgb=r='val':g=0:b='val'" -strftime 1 "thumbnail_%Y%m%d_%H%M%S.png"
```

- **Cyberpunk Cyan / Teal Duotone:** (Strips Red, keeps Green and Blue) `lutrgb=r=0:g='val':b='val'`
    
- **Sepia / Vintage Duotone:** (Boosts Red, slightly lowers Green, drops Blue) `lutrgb=r='val*1.2':g='val*0.9':b='val*0.5'`
    
- **High-Contrast Matrix Green:** (Strips Red and Blue, keeps Green) `lutrgb=r=0:g='val':b=0`

----
```bash
$d = [int][double](ffprobe -v error -show_entries format=duration -of default=noprint_wrappers=1:nokey=1 road.mp4); ffmpeg -ss $(Get-Random -Maximum $d) -i fortnite.mp4 -vframes 1 -vf "scale=1000:1000,lutrgb=r='val*1.2':g='val*0.9':b='val*0.5" -strftime 1 "thumbnail_%Y%m%d_%H%M%S.png"
```


