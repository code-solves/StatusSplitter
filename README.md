# StatusSplitter (StatusSplitter) 

**One-tap video splitter for WhatsApp Status**  
Split any video into perfect 30-second segments and post them directly to WhatsApp Status — no manual cutting, no leaving the app.

Perfect for long videos that exceed WhatsApp's 30-second limit. Fast, simple, and built for everyday use.

[![Flutter](https://img.shields.io/badge/Platform-Flutter-blue?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Language-Dart-blue?logo=dart)](https://dart.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build In Public](https://img.shields.io/badge/Build-In%20Public-green)](https://x.com/govenoralorzuke)
[![Made in Ghana](https://img.shields.io/badge/Made%20in-Ghana-orange)](https://github.com/code-solves)

## Demo / Screenshots
*(MVP in progress — screenshots coming soon!)*

## Features (MVP & Planned)
- Pick any video from gallery
- Auto-split into exact 30-second clips (no partial segments)
- Preview clips before posting
- One-tap "Post All to WhatsApp Status"
- No watermarks, no ads (free & open-source)
- Future: Batch processing, custom lengths, manual trim adjustments

## Tech Stack
- **Framework**: Flutter (cross-platform — one codebase for Android & iOS)
- **Language**: Dart
- **Key Packages**: `video_player`, `ffmpeg_kit_flutter` (for splitting), `image_picker`, `share_plus`
- **Development**: Built on Windows → Deploy to both platforms

## My Journey & Pivot
Originally planned as my first **native iOS app** in Swift + SwiftUI (after starting with a Swift CLI calculator).  
But without a MacBook, Xcode previews, simulators, and full builds were too limited on Windows — even Xcode Cloud workarounds weren't sustainable.

→ Pivoted to **Flutter** to:
- Ship faster on my current setup
- Reach both Android and iOS users
- Focus on solving the real problem instead of fighting tools

Once I get a MacBook, I'll explore a native SwiftUI version too!  

#BuildInPublic | Learning mobile dev practically 🇬🇭

## Getting Started (For Developers)
```bash
git clone https://github.com/code-solves/StatusSplitter.git
cd StatusSplitter

flutter pub get

flutter run
```

## Contributing
Welcome! Open issues, submit PRs (UI ideas, better splitting logic, etc.), or share feedback — this is my indie mobile journey.

## License
MIT License — feel free to use, modify, or build on it. See the license badge at the top for details.

## Follow
Follow my journey on X: https://x.com/govenoralorzuke (@govenoralorzuke)




