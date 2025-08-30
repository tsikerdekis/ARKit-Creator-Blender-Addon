# ARKit Blendshape Baker for Blender

A Blender addon that helps you quickly generate the 52 ARKit-compatible shape keys (blendshapes) required for facial animation workflows (Unity, Unreal, iOS ARKit).  
It guides you step-by-step with preview reference images, so you can pose your rigged face and bake each shape key.

---

## ✨ Features
- Works with **Rigify** (free) or **AutoRig Pro** (paid).
- Supports multiple meshes: select them all, and the addon merges them for the baking session.
- Automatic **Basis** shape key creation.
- Step-by-step posing with **Next** and **Previous** navigation.
- Preview reference images for each ARKit blendshape to guide posing.
- Auto-detection of the armature so you’re left in **Pose Mode** ready to sculpt.
- At the end of the session, the meshes are split back automatically.

---

## 📖 Requirements
- Blender **4.4.x** or newer
- A generated rig (Rigify or AutoRig Pro).
  - If using **AutoRig Pro**, make sure to **export the FBX using AutoRig Pro’s export option**, otherwise Unity/Unreal may not detect the bones correctly.

---

## 🚀 Usage
1. Install the addon:  
   - Download the ZIP of this repository.  
   - In Blender: `Edit → Preferences → Add-ons → Install…`, select the ZIP.  
   - Enable **ARKit Blendshape Baker**.

2. Prepare your model:  
   - Rig your face with **Rigify** or **AutoRig Pro**.  
   - Select **all face meshes** (eyes, teeth, skin, etc.).

3. Start the session:  
   - `N-panel → ARKit Baker → Start ARKit Bake Session`.  
   - Your meshes are merged, and you are switched into **Pose Mode**.  
   - A reference image appears for the first shape.

4. For each ARKit shape:  
   - Pose the rig to match the reference image.  
   - Click **Bake Shape Key**.  
   - Move to the next shape with **Next**.  
   - Repeat until all 52 are completed.

5. Export:  
   - Once finished, the addon splits meshes back (if needed).  
   - Export to FBX.  
   - For AutoRig Pro: use **ARP Export FBX** to preserve bone naming.

---

## 📦 Installation Notes
- Reference images are bundled in the addon ZIP.  
- If you don’t see them in the sidebar, check your console for debug logs (the addon prints when loading images).  

---

## 📜 License
This addon is licensed under the **MIT License**.  
You are free to use, modify, and distribute with proper attribution.

---

## 👨‍💻 About the Author
Created by [Michael Tsikerdekis](https://michael.tsikerdekis.com) — writer, developer, and indie game creator.  
Check out more of my work at [Northshore Press](https://northshorepress.co).

🎮 Games:  
- [**Park it at All Costs (Steam)**](https://store.steampowered.com/app/3958150/Park_it_at_All_Costs/)  
- [**Park it at All Costs (Google Play)**](https://play.google.com/store/apps/details?id=com.northshorepress.parkitatallcosts)

---

💡 *If you find this tool useful, consider supporting my projects or checking out my games. Your support keeps indie tools like this alive!*
