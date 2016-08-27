This is a macOS framework "wrapper" for the [tesseract](https://github.com/tesseract-ocr/tesseract) library.

#### Getting Started

1. Clone this repository recursively so that you get its submodules too:

```
git clone --recursive https://github.com/acj/TesseractFramework
```

2. Drag `TesseractFramework.xcodeproj` to your project.
3. In your project settings under Build Phases, add `TesseractFramework.framework` under "Target Dependencies" and "Link Binary with Libraries".
4. Add `#import <TesseractFramework/TesseractFramework.h>` to your source file.
5. Build and enjoy.

If you improve this project, please send me a pull request.

#### Credit

The fabulous Tesseract OCR library is available at [github.com/tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract).