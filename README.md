# VFX — Unity Slash Effect

A stylized **slash VFX** created using **Photoshop** for texture work and **Unity’s Particle System** for animation.  
This effect is designed to be lightweight, reusable, and easy to drop into gameplay moments like attacks or ability hits.

## 🎨 Texture Source

This slash texture was hand-painted in Photoshop and used in the particle material.

![Slash Texture](Images/Slash.png)

## 🎥 Preview
![Slash VFX](Images/preview.gif)

## ✨ Features
- Hand-drawn slash texture (Photoshop)  
- Unity particle setup using a single optimized material  
- Adjustable color, speed, and emission  
- Performance-friendly for real-time gameplay

## 🛠️ Tools & Tech
- **Unity** (Editor version: 6000.2.10f1)
- **Photoshop** — texture creation

## 📂 Project Structure

```
Assets/
└── VFX Test/
├── Slash.png          # Texture
├── M_fx_slash         # Material
├── FX_Slash_02        # Prefab (slash effect)
└── exposure_object    # Test object used to preview the effect
```

## 🚀 How to Use
1. Download or clone the project.  
2. Open it in Unity.  
3. Drag **FX_Slash_02** into your scene.  
4. Tune particle values (lifetime, color, emission) to match your gameplay.

## 🔧 Customization Tips
- Edit **Slash.png** in Photoshop for new shapes or colors.  
- Duplicate the prefab and layer multiple slashes for stronger impact.  
- Lower particle count if you need extra performance.
- Tweak the color of **Slash** from the **FX_slash_02** prefab and Sub Emitters.

## 📌 What I Learned
- Setting up a reusable VFX prefab  
- Balancing style with performance

## 📄 License
Free to use in personal projects.  
For commercial use, credit is appreciated.

## 📚 Learning Source

This effect was created by following a tutorial.  
I used the tutorial to learn particle setup, timing, and texture workflow, and then experimented with my own tweaks....

