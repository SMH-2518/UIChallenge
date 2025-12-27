This repository contains a **starter SwiftUI project** for a UI-focused assignment.

The goal of this challenge is to test your understanding of **SwiftUI basics, state handling, layout, and theming**, not to build a large or complex app.


## Challenge Objective

You are given a **pre-built SwiftUI screen in light mode**.

Your task is to:

- Convert the UI from **Light Mode → Dark Mode**
    
- **OR** enhance the screen by adding **additional UI elements or improvements** while keeping the design clean and readable
    

You are free to be creative, but keep the scope reasonable.

---

## Topics This Challenge Covers

You are expected to work with (or revise):

- `var` vs `let`
- Basic data types (`String`, `Int`, `Bool`)
- `if / else` statements
- Functions
- Optionals
- `VStack`, `HStack`, `ZStack`
- Text styling (fonts, colors, multiline text)
- Images: resizing, aspect ratio, `clipShape`
- `frame`, `padding`, `Spacer`
- Buttons and tap actions
- `TextField` for user input
- `@State` for updating the UI
- Basic navigation (`NavigationStack` / `NavigationLink`)
---

## What You Are Allowed to Do

You may:

- Modify colors, fonts, spacing, and layout
- Add new UI components (buttons, toggles, cards, etc.)
- Improve visual hierarchy
- Add light animations (optional)
- Use system colors for better Dark Mode compatibility

You **do not** need:

- External libraries
- Networking or backend logic
- Over-engineered architecture

---

## What You Should NOT Do

- Do not add heavy third-party dependencies
- Do not rewrite the entire app from scratch
- Do not submit via Pull Request (PR)

---

## Getting Started

### 1. Fork the Repository

Fork this repository to your own GitHub account.

---

### 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/UIChallenge.git
cd iOS
```

---

### 3. Open the Project
Open the `.xcodeproj` file in Xcode and run the app on:

- Simulator **or**
- Physical device (both are acceptable)
#### Important: Fix Signing & Capabilities (iOS)

After **downloading the project ZIP from GitHub** (`Sandesh282/UIChallenge/iOS`) and extracting it on your system, you **must** update the Signing settings in Xcode before running the app.

If you skip this step, the project will not build or run.

#### Step-by-Step Instructions

1. Extract the downloaded ZIP file
2. Open the project by double-clicking the `.xcodeproj` file in **Xcode**
3. In the left sidebar, click on the **project name** (top item)
4. Select the **App target** (not the Tests target)
5. Open the **Signing & Capabilities** tab
6. Under **Team**, select your **Apple ID / Personal Team**
7. Make sure **Automatically manage signing** is enabled
8. If Xcode shows any errors, click **Fix Issue** and let Xcode resolve them

#### After This Step

Once signing is configured, you can run the app on:

* iOS Simulator
* Physical iPhone (optional, but recommended)

#### Notes

* If your Apple ID does not appear, add it from **Xcode → Settings → Accounts**



---

### 4. Work on the Challenge

Modify the SwiftUI code to:

- Implement Dark Mode properly
- **OR** enhance the UI while maintaining usability and consistency

---

## Assignment Submission (Important)

Submit your assignment using the following Google Form link:

**Submission Folder**
[here](https://docs.google.com/forms/d/e/1FAIpQLSf5behp6IUB8Eq1BA8XPMTBOckJuZm7mFgKJZSV_sY8THLznA/viewform)

### What to Upload

- A text file containing the link to your forked GitHub repository

Make sure your **name is clearly mentioned**.

---

## Evaluation Criteria

Submissions will be evaluated based on:

- Correct use of SwiftUI layouts
- Dark Mode readability and contrast
- Clean and understandable code    
- UI clarity and consistency
- Reasonable creativity (not unnecessary complexity)

---

## Bonus (Optional)

- Smooth transitions or subtle animations
- Use of semantic/system colors
- Accessibility-friendly text sizes
---

## Final Note

This challenge is designed to test **fundamentals**, not perfection.  
Focus on **clarity, correctness, and intent** rather than overbuilding.

_Good Luck!!!_
