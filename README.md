# Asset Stage

*Video tutorial coming soon*



## Description

Asset Stage is a presentation solution for Blender, designed to streamline the asset presentation workflow, including wireframes, clay renders, and turntables.

## Features

*   **Automated Studio:** Instantly creates a cyclorama backdrop and a 3-point lighting setup (Key, Fill, Rim) scaled perfectly to your object.
*   **Camera & Framing:** Automatic framing based on object bounds, focal length adjustments, and composition locking.
*   **Turntable Animation:** One-click creation of 360-degree looping turntables. Syncs your timeline length automatically to the desired speed.
*   **Procedural Wireframes:** Apply quad-based wireframe shaders (Dark, Light, or Custom) to showcase your mesh topology. Includes a feature to auto-generate the required UVs.
*   **Clay & AO Presets:** Non-destructive material overrides including Grey Clay, Red Wax (ZBrush style), and Beige Sculpey to inspect surface details.
*   **Compositing Helpers:** Fast toggles for Shadow Catchers, Primary Visibility (Phantom mode), and Object ID masking.
*   **Smart Rendering:** Batch rendering tools with auto-file naming (Date, Scene, Camera), resolution presets (SD, HD, 4K), and automatic output path management.

## Installation

### Blender Setup
1.  Download the `assetStage.zip` file from the **Releases** section.
2.  Open Blender.
3.  Go to **Edit > Preferences > Add-ons**.
4.  Click **Install...** and select the `assetStage.zip` file.
5.  Enable the checkbox next to **Lighting: Asset Stage**.

## Usage
The tool can be found in the 3D Viewport Sidebar (N-Panel) under the **Asset Stage** tab.

### Studio & Lighting
1.  Select your target mesh object in the viewport.
2.  Click **Generate Studio**.
3.  The tool will automatically place the camera, lights, and backdrop tailored to the size of your object.

### Wireframes (Topology Presentation)
1.  Select your object.
2.  Choose a preset (**Dark** or **Light**) to apply the overlay.
3.  If UVs are missing, the tool handles generation automatically.
4.  Adjust thickness and colors in the "Settings" panel if needed.

### AO & Clay
1.  Select your object.
2.  Click **Apply Clay Mode** or choose a preset like **Red Wax**.
3.  Use the sliders to adjust the **Ambient Occlusion** distance and contrast to highlight crevices.
4.  Click **Restore** to return to your original materials.

### Turntable
1.  Select your object.
2.  Click **Make 360° Animation**.
3.  If needed, adjust the duration (Seconds) and click **Fix Frame Range** to set the timeline for a perfect loop.

### Rendering
1.  Select your Quality (SD, HD, 4K...).
2.  Choose your Destination (Relative to project, Custom folder, or Desktop).
3.  Click **Render Image** or **Render Animation**.

## Compatibility
*   **Blender Version:** 3.6 and above.
*   **Render Engine:** Optimized for Cycles (GPU recommended).

## License
This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

## Author
**CGjuice**
