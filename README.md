# **Teapot - A Python Tetris Bot for Tetrio**  

![Banner](https://github.com/user-attachments/assets/aea6983b-b7f5-4009-afed-5b7914a0e7a3)

---

## ⚡ **Features**
- **Blazingly Fast**: Searches for best moves with heuristic evaluation.
- **Customizable Playstyle**: Adjust the bot's behavior with simple edits in `heuristics.py`.
- **Resolution Support**: Currently supports 1920x1080 and 2560x1440 resolutions.
- **Easy Setup**: Low-hassle setup with minimal dependencies and no need to build/compile files yourself.


## 🚀 **Video Demo + Setup Instructions**

https://github.com/user-attachments/assets/a0071b48-5b61-449f-a2d7-505156166dd2



## 📦 **Quickstart Guide**
1. **Download and Apply Skin**  
   - Download the included skin (`skin.png`) and apply it using [Tetr.io Plus](https://gitlab.com/UniQMG/tetrio-plus).

2. **Install Libraries**
   - Run the following command in your terminal of choice:
   `pip install keyboard dxcam`
   
4. **Adjust Resolution**  
   - Modify the flag in `constants.py` to match your screen resolution. Supported resolutions are:
     - 1920x1080
     - 2560x1440

5. **Configure Tetr.io Settings**  
   - Set the following gameplay configurations:
     - **Graphics**: Low
     - **Board Zoom**: 130%
     - **Shadow Visibility**: 0%
     - **Board Bounciness**: 0%

6. **Optimize Particle Effects**  (Optional)
   - Replace the following particle effects with transparent files (`empty.png`) through Tetr.io Plus:
     - `particle_beam`
     - `particle_beams_beam`
     - `particle_chirp`
     - `particle_star`

   This ensures that the bot does not misinterpret particle effects as unknown blocks.


## 🛠 **Customization**
The bot's behavior is controlled by the values in `heuristics.py`. These values are placeholders but generally stable for testing. If you discover stronger values or optimizations, your contributions are welcome!

