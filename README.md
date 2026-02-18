# BLDC_6_STEP_CONTROL
Study of the 6-step control method for controlling BLDC motors

## Overview
This repository documents my study of the 6-step control method for BLDC motors, with video explanations of how the motor is driven.

## How to Drive a BLDC Motor

### Basic Concept
BLDC motors have three phases (A, B, C) that need to be energized in a specific sequence to make the motor spin. The 6-step method drives the motor by switching which phases are powered in six sequential steps.

### The 6-Step Sequence
Each electrical cycle is divided into six steps. At each step, two phases are energized:

- Step 1: A+ B-
- Step 2: A+ C-
- Step 3: B+ C-
- Step 4: B+ A-
- Step 5: C+ A-
- Step 6: C+ B-

This sequence repeats continuously to keep the motor rotating.

## Video Resources

<!-- Add your video links here after uploading -->
<!-- Example: - [BLDC 6-Step Control Explained](https://youtube.com/watch?v=xxxxx) -->

### Where to Upload Videos

Videos should be uploaded to an external video hosting platform (not stored in this GitHub repository):

**Recommended platforms:**
- **YouTube** - Free, unlimited uploads, easy sharing (https://youtube.com)
- **Vimeo** - High quality, clean interface (https://vimeo.com)
- **Google Drive** - Share with view-only link (https://drive.google.com)

### How to Add Your Videos

1. **Record** your video using screen capture software (OBS, Camtasia, etc.)
2. **Upload** to YouTube, Vimeo, or another video platform
3. **Copy** the video URL/link
4. **Edit this README** by replacing the comment above with your link:
   ```
   - [Video Title](https://your-video-url-here)
   ```
5. **Commit** the change to update the repository

## What to Explain in Videos

When recording videos, focus on:
- The 6-step commutation sequence
- How energizing different phase combinations makes the motor rotate
- Why the sequence needs to be in the correct order

## License
This is a study project for educational purposes.
