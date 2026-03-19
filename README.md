# 🎤✋ Voice + Gesture Controlled Web Playground

An experimental browser-based playground controlled entirely by **voice commands** and **hand gestures** using your microphone and webcam.

This project explores next-generation human-computer interaction where:

* 🗣️ Voice = intent
* ✋ Gesture = control
* 🌐 Browser = platform

---

## 🌐 Play Online

👉 **Launch the app:**
[CLICK HERE](https://voice-gesture-playground.designarena.ai)

---

## 🚀 Features

* 🎤 **Voice Control (Web Speech API)**

  * Create objects
  * Modify size and color
  * Delete or clear elements

* ✋ **Gesture Control (MediaPipe Hands)**

  * Move objects using finger tracking
  * Pinch to drag
  * Auto-select nearby objects

* 🧱 **Interactive Object System**

  * Dynamic object creation (boxes, circles)
  * Real-time manipulation
  * State tracking

* 🎨 **Visual Feedback System**

  * Live voice transcript
  * Selected object highlighting
  * Gesture activity indicators

* ⚡ **Runs Fully in Browser**

  * No backend required
  * Single HTML file
  * Instant execution

---

## 🛠️ How to Use

1. Open the website
2. Allow:

   * Microphone access 🎤
   * Camera access 📷
3. Try commands like:

   * "create box"
   * "change color to red"
   * "make it bigger"
4. Use your hand to:

   * Move objects
   * Pinch to drag

---

## 📦 Project Structure

```
/project
 └── index.html
```

---

## 🤖 Built With AI

This project was generated using an AI-assisted development workflow.

---

## 🧠 AI Prompt Used

```
You are a senior frontend engineer.

Your task is to build a COMPLETE, WORKING, SINGLE-FILE web app that runs immediately when opened in a browser.

IMPORTANT:
- Use ONLY HTML, CSS, and JavaScript
- Everything must be inside ONE HTML file
- Do NOT skip features
- Do NOT leave placeholders
- Do NOT require a backend
- Use CDN links if needed (for MediaPipe, etc.)

-------------------------------------

# 🎯 GOAL

Create a "Voice + Gesture Controlled Playground"

The user should be able to:
1. Speak commands using their microphone
2. Control objects using hand gestures via webcam
3. See immediate visual feedback

-------------------------------------

# 🔐 PERMISSIONS (REQUIRED)

On page load:
- Ask for microphone access
- Ask for camera access

If denied:
- Show a clear message on screen explaining what is missing

-------------------------------------

# 🎤 VOICE CONTROL (STEP-BY-STEP)

Use the Web Speech API.

Implement EXACTLY this:

1. Start continuous speech recognition automatically
2. Show live transcript on screen (top corner)
3. Restart recognition if it stops

-------------------------------------

# 🎤 SUPPORTED VOICE COMMANDS (MUST WORK)

Implement these EXACT commands:

### Object Creation
- "create box"
- "create circle"

### Object Actions
- "make it bigger"
- "make it smaller"
- "change color to red"
- "change color to blue"
- "delete object"

### System Commands
- "clear screen"

-------------------------------------

# ✋ GESTURE CONTROL (STEP-BY-STEP)

Use MediaPipe Hands via CDN.

Implement EXACTLY this:

1. Show webcam feed in a corner
2. Detect one hand
3. Track index finger tip position

-------------------------------------

# ✋ GESTURES (MUST WORK)

### Move Object
- If index finger is visible:
  → Move selected object to finger position

### Select Object
- If finger is close to an object:
  → Automatically select it

### Pinch Gesture
- Detect thumb + index touching
- While pinching:
  → Drag object

-------------------------------------

# 🧱 OBJECT SYSTEM (VERY IMPORTANT)

Objects must:

- Be simple DIV elements
- Appear in the center when created
- Have properties:
  - position (x, y)
  - size
  - color

Keep track of:
- An array of objects
- The currently selected object

-------------------------------------

# 🎨 VISUAL FEEDBACK (REQUIRED)

You MUST include:

1. Highlight selected object (outline)
2. Show current voice command text
3. Show "Gesture Active" indicator
4. Show instructions on screen:
   - Example:
     "Say: create box"
     "Pinch to drag"

-------------------------------------

# 🧠 LOGIC RULES (IMPORTANT)

- If no object is selected:
  → Voice commands apply to the LAST created object

- If no objects exist:
  → Ignore action commands safely (no errors)

- Do NOT crash under any condition

-------------------------------------

# ⚡ PERFORMANCE RULES

- Use requestAnimationFrame for updates
- Do NOT freeze the browser
- Keep everything smooth

-------------------------------------

# 🎨 UI DESIGN

- Dark background
- Center playground area
- Minimal futuristic style
- Clean readable text

-------------------------------------

# 📦 OUTPUT FORMAT

Return ONE complete HTML file.

The file MUST:
- Run immediately
- Require NO edits
- Include comments explaining key parts

-------------------------------------

# 🚫 DO NOT DO THIS

- Do NOT use React, Vue, or frameworks
- Do NOT split into multiple files
- Do NOT skip gesture implementation
- Do NOT say "this is a placeholder"

-------------------------------------

# ✅ SUCCESS CRITERIA

This is successful if:
- I can open the file
- Allow mic + camera
- Say "create box"
- See a box appear
- Move it with my finger

If any of that fails, the task is NOT complete.
```

---

## ⚠️ Notes

* Works best in Chrome-based browsers
* Requires HTTPS or localhost for microphone/camera permissions
* Performance depends on your device

---

## 🔮 Future Improvements

* Physics system
* Particle effects
* Multi-hand tracking
* AI-powered commands

---

## 📜 License

This project currently has **no license**.

All rights are reserved by the author. You may view the code, but you may not copy, modify, distribute, or use it in other projects without explicit permission.
