# Music Files

This folder contains the audio files for the Valentine's Day proposal webpage.

## Required Files:

1. **background-music.mp3** - Plays during the scrolling experience
   - Suggested: "I Need A Girl" by Taeyang (English version)
   - This should loop continuously

2. **celebration-music.mp3** - Plays when "Yes" is clicked
   - Suggested: "Lemonade" by Internet Money ft. Gunna, Don Toliver, NAV
   - This plays once when the proposal is accepted

## How to Add Your Music:

1. Place your MP3 files in this folder
2. Rename them to match the names above, OR
3. Update the `<source src="...">` paths in `index.html` to match your filenames

## Supported Formats:

- MP3 (recommended - best browser support)
- OGG
- WAV
- M4A

## File Name Examples:

You can name them whatever you want, just update the HTML:

```html
<audio ref="bgMusic" loop>
    <source src="music/your-filename-here.mp3" type="audio/mpeg">
</audio>
```
