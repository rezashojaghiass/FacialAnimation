# FacialAnimation Repository

This repository contains Blender-based facial animation resources and rigging tools for character animation, specifically featuring Buzz Lightyear character animations.

## Repository Structure

### 📁 FacialExpressionBuzzLightYear/
Contains rendered image sequences of various facial expressions for the Buzz Lightyear character. Each subfolder represents a different facial expression with frame-by-frame PNG images.

- **AA/** - Mouth shape for "AA" phoneme/expression (30 frames)
- **EE/** - Mouth shape for "EE" phoneme/expression (30 frames)
- **OO/** - Mouth shape for "OO" phoneme/expression (30 frames)
- **Sad/** - Sad facial expression animation (30 frames)
- **Smile/** - Smiling facial expression animation (30 frames)
- **Surprise/** - Surprised facial expression animation (30 frames)

These image sequences can be used for:
- Lip-sync animation reference
- Facial expression training data
- Animation demonstrations
- Character performance studies

### 📁 Rigging/
Contains the character rigging files and UI scripts for the Buzz Lightyear character in Blender.

**Files:**
- `XP_Buzz_Lightyear_Rig_Blender.blend` - Main Blender file with the complete character rig
- `XP_Buzz_Lightyear_rig_ui_BLENDER_4.0x_.py` - Custom UI script for Blender 4.0+
- `XP_Buzz_Lightyear_rig_ui_BLENDER_3.6x_.py` - Custom UI script for Blender 3.6+

The rig includes:
- Facial controls for expressions
- Body mechanics
- Custom UI for animator-friendly controls

### 📁 AutoRig Pro/
Contains the AutoRig Pro addon (version 3.73.33) for Blender, a professional rigging tool.

**Path:** `auto_rig_pro_3.73.33/auto_rig_pro-master/`

⚠️ **Important:** AutoRig Pro is a paid addon. This repository includes a purchased copy. **Users must purchase their own license** to use this addon legally. Visit the official AutoRig Pro website to obtain your own copy.

**Key Components:**
- **src/** - Source code for the AutoRig Pro addon
  - Auto rigging functions
  - FBX export/import utilities
  - Rig remapping tools
  - Preference management
- **limb_presets/** - Pre-configured limb modules for rigging
- **icons/** - UI icons for the addon
- **LICENSE.txt** - License information
- **00_LOG.txt** - Version history and changelog
- `__init__.py` - Main addon initialization

**Features:**
- Automated character rigging
- FBX export/import with advanced options
- Custom rig presets
- Multi-version Blender support

## Use Cases

This repository is useful for:
1. **Character Animation** - Pre-rigged Buzz Lightyear character ready for animation
2. **Facial Expression Studies** - Reference images for different expressions
3. **Lip-Sync Animation** - Phoneme mouth shapes (AA, EE, OO)
4. **Rigging Education** - Learning from professional character rig setup
5. **Animation Pipeline** - Integration with game engines or other 3D software via FBX export

## Requirements

- **Blender 3.6+** or **Blender 4.0+** (depending on which UI script you use)
- **AutoRig Pro addon** (included in the repository)
- Basic knowledge of Blender character animation and rigging

## Getting Started

1. Open `Rigging/XP_Buzz_Lightyear_Rig_Blender.blend` in Blender
2. Load the appropriate UI script based on your Blender version
3. Use the facial expression renders as reference for creating animations
4. Export animations using the AutoRig Pro FBX tools if needed

---

*Repository cloned from: https://github.com/rezashojaghiass/FacialAnimation*
