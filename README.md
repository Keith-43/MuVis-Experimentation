# 🎵 MuVis - Music Visualizer  

**"See the notes they're playing."**  

<!-- ![MuVis Screenshot](MuVis/Documentation/Doc_Images/UserGuideA.png)   -->

## Features  
- **24 stunning visualizations** (each with 4 customizable options)  
- **Swipe & tap controls**:  
  - ← / → to switch visualizations  
  - ↑ / ↓ to change visualization options  
  - Triple-tap to toggle toolbars (iOS) or enable BlackHole playback (macOS)  
- **Cross-platform**: Runs on macOS, iOS, and iPadOS  
- **Real-time audio processing**: Works with music files or microphone input  

## Quick Start  
1. **Download** →  [App Store](https://apps.apple.com/us/app/muvis-music-visualizer/id1582324352) / [Source Code](https://github.com/Keith-43)  

2. **Launch MuVis** → The app plays a sample track ("The Elevator Bossa Nova") with live visualization.  

3. **Control the experience**:  
   - **Resize window** (Mac: drag corners)  
   - **Switch visualizations**:  
     - Mac: Click ◀/▶ buttons or use keyboard arrows  
     - Mobile: Swipe left/right  
   - **Adjust options**:  
     - Mac: Click ▼/▲ buttons or use up/down arrows  
     - Mobile: Swipe up/down  

## Toolbar Guide  
#### Bottom Controls:  
| Button | Action | Shortcut (Mac) |  
|--------|--------|---------------|  
| ◀ ▶ | Previous/Next visualization | ← → keys |  
| ▼ ▲ | Change visualization option | ↑ ↓ keys |  
| ⏸️ | Pause/Play music | - |  
| 🎤 | Toggle microphone input | - |  
| 🎵 | Select music file (disabled when mic active) | - |  
| 📉 | Toggle spectral enhancer (reduces noise) | - |  
| 📖 | View User Guide / Visualizations Guide | - |  

### Top Controls:  
- **Visualization Gain**: Adjust display intensity  
- **Treble Boost**: Enhance high-frequency visibility  
*(These affect only the visuals, not the audio)*  

## Visualization Options  
Each of the 24 visualizations offers 4 unique rendering styles. Experiment to find your favorite combinations!  

## Technical Details  
- Built with **SwiftUI/Swift** in Xcode  
- Uses the **BASS audio library** ([un4seen.com](https://www.un4seen.com))  
- Open-source for community contributions  

## Need More Info?  
Check the in-app guides:  
- **User Guide**: App functionality (you're reading it now)  
- **Visualizations Guide**: Detailed explanation of each visualization  
