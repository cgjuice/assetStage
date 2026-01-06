# Asset Stage

### [Watch how it works on YouTube](https://youtu.be/f8vVlS8nslc)
[![Watch the video](https://img.youtube.com/vi/f8vVlS8nslc/maxresdefault.jpg)](https://youtu.be/f8vVlS8nslc)



## Description

Asset Stage is a presentation solution for Blender, designed to streamline the asset presentation workflow, including wireframes, clay renders, and turntables.

## Features

*   **Automated Studio:** Instantly creates a cyclorama backdrop and a 3-point lighting setup (Key, Fill, Rim) scaled perfectly to your object.
*   **Camera & Framing:** Automatic framing based on object bounds, focal length adjustments, and composition locking.
*   **Turntable Animation:** One-click creation of 360-degree looping turntables. Syncs your timeline length automatically to the desired speed.
*   **Material Tweaker** `NEW in 1.2` ⭐️: Dedicated panel to tweak shader inputs (Roughness, Metallic, Normal) without entering the Node Editor. Includes "Solo Mode" and tools to fix color space issues.
*   **SSS Tools** `NEW in 1.2` ⭐️: Quick Subsurface Scattering presets (Human, Alien, Marble, Avatar) and manual controls for scale and radius.
*   **Procedural Wireframes:** Apply quad-based wireframe shaders (Dark, Light, or Custom) to showcase your mesh topology. Includes a feature to auto-generate the required UVs.
*   **Clay & AO Presets:** Non-destructive material overrides including Grey Clay, Red Wax (ZBrush style), and Beige Sculpey to inspect surface details.
*   **Procedural Weathering** `NEW in 1.2` ⭐️: One-click weathering system to add dirt accumulation, grunge, and edge wear to any material.
*   **Compositing Helpers:** Fast toggles for Shadow Catchers, Primary Visibility (Phantom mode), and Object ID masking.
*   **Smart Rendering:** Batch rendering tools with auto-file naming (Date, Scene, Camera), resolution presets (SD, HD, 4K), and automatic output path management.






## Installation

### Blender Setup
1.  Download the `assetStage.zip` file from the **Releases** section.
2.  Open Blender (4.0 or higher).
3.  Go to **Edit > Preferences > Add-ons**.
4.  Click **Install...** and select the `assetStage.zip` file.
5.  Enable the checkbox next to **Lighting: Asset Stage**.

## Usage
The tool can be found in the 3D Viewport Sidebar (N-Panel) under the **Asset Stage** tab.

### Studio & Lighting
1.  Select your target mesh object in the viewport.
2.  Click **Generate Studio**.
3.  The tool will automatically place the camera, lights, and backdrop tailored to the size of your object.

### Turntable
1.  Select your object.
2.  Click **Make 360° Animation**.
3.  If needed, adjust the duration (Seconds) and click **Fix Frame Range** to set the timeline for a perfect loop.

### Material Tweaker  ⭐️ `NEW in 1.2`
*   **Solo Inputs:** Click the "Eye" icon next to any property (Base Color, Roughness, Normal) to visualize just that map on your object.
*   **Add Control:** Click the "Gear" icon to inject a hidden adjustment node (Hue/Sat or Map Range) for quick tweaks.
*   **Fix Color Space:** If a texture is using the wrong color space (e.g., sRGB on a Roughness map), a warning button will appear to fix it instantly.

### Wireframes (Topology Presentation)
1.  Select your object.
2.  Choose a preset (**Dark** or **Light**) to apply the overlay.
3.  If UVs are missing, the tool handles generation automatically.
4.  Adjust thickness and colors in the "Settings" panel if needed.

### SSS (Skin & Subsurface)  ⭐️ `NEW in 1.2`
1.  Select an object.
2.  Click a preset like **Human** or **Marble** to instantly apply Subsurface Scattering settings.
3.  Use the **Scale** slider to adjust how deep light penetrates the surface.

### AO & Clay
1.  Select your object.
2.  Click **Apply Clay Mode** or choose a preset like **Red Wax**.
3.  Use the sliders to adjust the **Ambient Occlusion** distance and contrast to highlight crevices.
4.  Click **Restore** to return to your original materials.

> 💡 **Quick Tip**  
> If this is your first time using AO shaders in Blender, you might see a **"Compiling Render Kernels"** message.  
> This is a standard one-time optimization by Blender—just give it a moment!

### Weathering  ⭐️ `NEW in 1.2`
1.  Select your object.
2.  Click **Enable Weathering**.
3.  Adjust **Dirt Amount**, **Global Scale**, and **Edge Wear** to procedurally age your asset.

### Rendering
1.  Select your Quality (SD, HD, 4K...).
2.  Choose your Destination (Relative to project, Custom folder, or Desktop).
3.  Click **Render Image** or **Render Animation**.

## Compatibility
*   **Blender Version:** 4.0 and above.
*   **Render Engine:** Optimized for Cycles (GPU recommended).

## License
This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

## Author
**CGjuice**
