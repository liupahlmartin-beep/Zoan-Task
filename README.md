<p align="center">
  <img src="https://raw.githubusercontent.com/liupahlmartin-beep/Zoan-Task/main/logo.png" width="150" alt="Logo"/>
</p>

<h1 align="center">ImagePut</h1>

<p align="center">
  A powerful AutoHotkey v2 library for converting and outputting images to virtually any format or destination.
</p>

---

## ✨ Features

- **Universal Image Conversion** — Convert any image to and from Base64, Hex, URI, Bitmap pointers, HBitmap, HIcon, WICBitmap, and more.
- **File Output** — Save images directly to disk in BMP, GIF, JPG, PNG, or TIFF formats with optional JPEG quality control.
- **Clipboard Support** — Put any image directly onto the Windows clipboard.
- **Screen & Desktop** — Render images to the screen, set them as the desktop wallpaper, or draw behind desktop icons.
- **Window Display** — Show images in borderless (`ImageShow`) or bordered (`ImagePutWindow`) windows with optional animation playback and frame caching.
- **Stream & Memory** — Output images to COM Streams, RandomAccessStreams, SafeArrays, shared memory buffers, and encoded binary buffers for advanced inter-process workflows.
- **Cursor Replacement** — Set any image as the active Windows cursor with configurable hotspot coordinates.
- **Web Upload** — Upload images directly to Imgur and receive a URL back.
- **Form Data** — Encode images as `multipart/form-data` for HTTP POST requests.
- **Explorer Integration** — Save images into the currently active File Explorer window.
- **Image Comparison** — Use `ImageEqual` to perform pixel-perfect comparison between two or more images.
- **Utility Helpers** — Quickly retrieve image dimensions with `ImageWidth` / `ImageHeight`, or destroy image resources with `ImageDestroy`.

---

## 📦 Requirements

- [AutoHotkey v2.0+](https://www.autohotkey.com/)

---

## 🚀 Quick Start

```ahk
#Requires AutoHotkey v2.0
#Include ImagePut.ahk

; Save a screenshot to a PNG file
ImagePutFile([0, 0, 800, 600], "screenshot.png")

; Copy an image to clipboard
ImagePutClipboard("my_image.png")

; Get a Base64 string of an image
b64 := ImagePutBase64("my_image.png")
```

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.  
Original author: **Edison Hua (iseahound)**
