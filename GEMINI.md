# videocallbyraghav - Project Memory

This directory is the primary workspace for Raghav Parashar's Video Call Hub.

## Project: videocallbyraghav
- **Description:** A minimalist, peer-to-peer video calling website built using PeerJS and WebRTC.
- **Branding:** Made by Raghav Parashar
- **GitHub Repo:** https://github.com/noteforstudy1-tech/videocallbyraghav
- **Live Site:** https://noteforstudy1-tech.github.io/videocallbyraghav/

## Features
1. **P2P Calling:** Direct video/audio communication using PeerJS.
2. **Modern UI:** Sleek glassmorphism design with a dark theme.
3. **Media Controls:** 
   - Toggle microphone (Mute/Unmute).
   - Toggle camera (On/Off).
   - **Screen Sharing:** Share your screen with the remote peer.
   - End Call (Reset session).
4. **Room System:** Generate a unique Room ID or join an existing one.
5. **Call Modes:** 
   - **Video Call:** Full audio/video session.
   - **Audio Only:** Join with microphone only.
   - **Chat Only:** Text-based interaction without media.
6. **Pre-call Configuration:** Toggle Mic/Camera *before* joining a call.
7. **File Sharing:** Send and receive files via the integrated chat.
8. **Draggable PiP:** Move the local self-view window anywhere on the screen.

## Technical Notes
- **Hosting:** Designed for GitHub Pages.
- **Protocol:** PeerJS (raghav-call-[ID] namespace).
- **Libraries:** PeerJS (via CDN).

## Session History
- **2026-06-03:** 
  - Discarded previous Ludo project.
  - Built Video Call Hub from scratch.
  - Implemented WebRTC stream handling and PeerJS signaling.
  - Added responsive UI and media toggle controls.
- **2026-06-04:**
  - Added Screen Sharing (getDisplayMedia).
  - Added File Sharing (PeerJS Data Connection + ArrayBuffer).
  - Implemented Pre-call Mic/Video toggles.
  - Added specialized Call Modes (Video, Audio, Chat).
  - Made local video PiP draggable (Mouse/Touch events).
  - Refined UI for file attachments and mode selection.

---
*Managed by Gemini CLI - Raghav's Personal Co-pilot*
