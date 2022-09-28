# Emoji-PNG

Extracted PNG images from Emoji font files.

## Emojis

1. **Apple Emoji** from [Keinta15/Magisk-iOS-Emoji](https://github.com/Keinta15/Magisk-iOS-Emoji).
2. **JoyPixels** from [JoyPixels® Official Site](https://www.joypixels.com/download). JoyPixels 7.0 is temporarily hosted at [cdn.joypixels.com](https://cdn.joypixels.com/distributions/generic/font/7.0/joypixels-android.ttf).
3. **Noto Emoji** from [googlefonts/noto-emoji](https://github.com/googlefonts/noto-emoji).
4. **Twemoji** from [Gontier-Julien/Twemoji-Remastered](https://github.com/Gontier-Julien/Twemoji-Remastered).

| Apple Emoji                       | JoyPixels                       | Noto Emoji                    | Blobmoji                         | Twemoji                        |
| --------------------------------- | ------------------------------- | ----------------------------- | -------------------------------- | ----------------------------- |
| <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Apple%20Emoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/JoyPixels/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Noto%20Emoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Blobmoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Twemoji/PNG/u1F60A.png" width="128" /> |



## Extraction Methods

- `pip install fonttools`, fontTools from [fonttools/fonttools](https://github.com/fonttools/fonttools).

  ```
  fontTools requires Python 3.7 or later.
  ```

- `ttx -z extfile [emojifontfile.ttf]`.

  Then you can get:

  - A `.ttx` file.
  - PNG files under `bitmaps\trike0`.
