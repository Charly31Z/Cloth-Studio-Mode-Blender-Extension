# 🧥 Cloth Studio Mode (CLO 3D Workflow for Blender 4.0+)

**Real-Time 2D CAD Pattern Design, Hardware-Accelerated XPBD Physics Engine (NVIDIA CUDA / C++ OpenMP+AVX2), and 1-Click Game-Ready Auto-Baker for Unreal Engine 5 / MetaHumans.**

[![Blender](https://img.shields.io/badge/Blender-4.0%2B-orange?logo=blender)](https://www.blender.org/)
[![Physics](https://img.shields.io/badge/Physics-XPBD%20CUDA%20%7C%20C%2B%2B%20AVX2-success)]()
[![Language](https://img.shields.io/badge/Language-English%20%7C%20Espa%C3%B1ol-purple)]()
[![Status](https://img.shields.io/badge/Status-Early%20Access%20Beta-blue)]()

> 🚀 **Get Early Access Beta (Gumroad):** https://meshborn.gumroad.com/l/cloth-studio-mode

---

## ✨ Key Features

* **📐 Native 2D CAD Pattern Board:** Interactive Bézier curves, magnetic *Smart Guides*, live X-axis symmetry, marquee *Box Select*, interactive left tool dock, and context-sensitive right-click menus.
* **🧍 1:1 2D Avatar Silhouette & Anatomical Tape Measures:** Projects any character or MetaHuman directly onto the 2D pattern board with automatic real-time centimeter measurements (Neck, Chest, Waist, Hips, and Knees).
* **⚡ High-Performance Hybrid XPBD Engine (GPU CUDA & CPU C++):** Ultra-fast, unconditionally stable real-time cloth simulation with zero mesh explosions, multi-layer garment support (*Garment Layers*), and piece freezing (*Freeze ❄*).
* **✋ 3D Live Grab Hand & Interactive Fasteners:** Pinch, pull, and drape fabric in real time during simulation, or interactively snap and tear open **Magnetic Buttons, Snaps, and Velcro strips** with your mouse.
* **🪡 Advanced Garment & Tailoring Tools:**
  * **1-Click Automatic Neckbands, Cuffs & Ribbing** with physical elastic shrinkage.
  * **Patch Pockets** with customizable 3D clearance gap and pouch volume without cutting holes in the base mesh.
  * **Functional 3D Zippers** with adjustable opening slider (0% to 100%), procedural teeth, pull tab, and multi-piece chain linking.
  * **Puffer / Quilted Chambers** with aerodynamic internal pressure divided by symmetric internal vector lines.
  * **CLO-Style Edge Extrusion & Internal Offsets** with live 2D preview.
* **🎮 1-Click Game-Ready Export (Unreal Engine 5 / MetaHuman):** Welds seams, sculpts physical seam puckering/relief, bakes a unified PBR Texture Atlas (`Albedo`, `Tangent-Space Normal Map` with micro-threads, and `Roughness`), and automatically transfers skeletal weights (*Auto-Skinning*) from the Avatar.
* **🌐 Bilingual Interface:** Built-in language switcher (**English** by default + **Spanish** support in Add-on Preferences and Top Header).

---

## 🗺️ Development Roadmap

### ✅ Phase 1: 2D CAD Core & XPBD Physics Engine (Completed)
- [x] Dedicated 2D CAD pattern editor with Bézier curves, live symmetry, and angle snapping rulers.
- [x] 1:1 2D Avatar silhouette projection with automatic anatomical measurements in centimeters.
- [x] Native C++ (`OpenMP + AVX2`) and NVIDIA GPU (`CUDA PTX`) physics backends.
- [x] 3D Virtual Hand (*Live Grab*) for real-time interactive draping.
- [x] Automatic Neckband/Cuff (*Rib*) generator and 3D Patch Pockets with volume.

### ✅ Phase 2: Tailoring Details, UI Dock & Game-Ready Baker (Completed - v1.7)
- [x] Mirrored internal vector lines and curved Bézier pattern splitting (*Split & Cut*).
- [x] Aerodynamic chamber inflation for *Puffer Jackets* and quilted vests.
- [x] Functional 3D Zippers (0%–100% slider) and automatic multi-pattern chain linking (Rib + Body).
- [x] Interactive Magnetic Buttons, Snaps, and Velcro with live mouse tear-off threshold.
- [x] Left 2D Tool Dock, live edge extrusion/offsets, and smart right-click context menus.
- [x] 1-Click PBR Texture Atlas Auto-Baker (1K / 2K / 4K) + MetaHuman Auto-Rigging.
- [x] Full Bilingual UI (**English** default / **Spanish**).

### 🚧 Phase 3: Cross-Platform GPU & Pattern Templates (In Progress - v1.8)
- [ ] Native Linux compilation (`libcloth_fast_engine.so`).
- [ ] Cross-platform GPU acceleration for **AMD Radeon / Intel Arc** via native *Compute Shaders* (`gpu.compute`).
- [ ] Built-in ** parametric Base Pattern Library (Templates)**: Crew-Neck T-Shirt, Hoodie, Jogger Pants, Puffer Vest, and Tactical Cargo Pants.

### 🔮 Phase 4: Animation Cache & Cinematics (Future - v2.0)
- [ ] Timeline simulation recording (*Keyframe / MDD / Alembic Point Cache*) for character animation.
- [ ] Real-time fabric tension, pressure, and stretch heatmaps (*Strain Map*).
- [ ] Aerodynamic wind and turbulence force fields.

---

## 🖥️ System Requirements
* **Blender:** 4.0, 4.1, 4.2, 4.3+
* **OS:** Windows 10 / 11 (64-bit) — *Linux support coming in v1.8*
* **GPU (Optional for CUDA Backend):** NVIDIA GTX / RTX Series (Driver 520+), or any multi-core CPU for the OpenMP/AVX2 C++ backend.

---

## 🐛 Bug Reports & Feature Requests
Found a bug or have a feature request for your game dev workflow? Please open a ticket in the **[Issues](../../issues)** tab including your Blender version and hardware specs.
