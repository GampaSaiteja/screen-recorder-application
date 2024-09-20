The project is a **Screen Recorder and Screenshot Capture Application** implemented using HTML, CSS, and JavaScript. It allows users to record their screen, take screenshots, and apply real-time filters to the video feed. The key components include video recording, screenshot capture, filter application, and a live timer during recording.

### Features:
1. **Screen Recording**:
   - Users can start and stop screen recording by clicking the record button.
   - The recording is saved as an MP4 file, which is automatically downloaded when stopped.

2. **Screenshot Capture**:
   - Users can capture screenshots of the video feed by clicking the capture button.
   - The screenshot is saved as a JPEG file and automatically downloaded.

3. **Filter Application**:
   - A selection of filters (orange, brown, pink, aqua, and transparent) can be applied to the video feed.
   - Clicking a filter changes the visual overlay applied to the video feed.

4. **Live Timer**:
   - A timer starts when recording begins, showing the duration of the current recording session.
   - The timer resets and hides once the recording is stopped.

### Technologies Used:
- **HTML**: Provides the structure of the application.
- **CSS**: Styles the UI components, including buttons, filters, and video controls.
- **JavaScript**: Implements functionality like screen recording, screenshot capture, filter application, and timer management.

### Key Interactions:
- **Recording**: Controlled by a "Record" button, which toggles the recording state and shows a live timer.
- **Capture**: A "Capture" button allows users to take screenshots of the video feed.
- **Filters**: Users can select different filters to apply a visual overlay to the video feed.
- **Timer**: A countdown timer displays the recording duration when the video is being recorded.

### Challenges Addressed:
- Ensuring the **video feed remains visible** even when a filter is applied. The filter should act as a transparent overlay, without completely covering the video.
- Managing the **download** of recorded videos and captured images automatically.
- Handling the **timer functionality** smoothly, updating the display every second during recording.

This project is a useful tool for anyone needing quick and easy screen recording with optional filters and a sleek UI design.
