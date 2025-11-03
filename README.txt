=====================================
Ankit Jaiswal – Website Guide
=====================================

🧩 1. FILE STRUCTURE
-------------------------------------
index.html   → Your main website file
style.css    → Controls colors, layout, and animation
images/      → Folder for your photos or logos (if used)

You can edit both files directly in GitHub or Notepad++ / VS Code.

-------------------------------------
🎨 2. CHANGE COLORS
-------------------------------------
- Olive accent color is #6b705c
- Background tint is #f8f9f7

To change these:
→ Open style.css
→ Press Ctrl+F and search for “#6b705c” or “#f8f9f7”
→ Replace them with your new color codes

Tip: Use https://coolors.co to find matching colors.

-------------------------------------
🧠 3. CHANGE FONT
-------------------------------------
- Currently uses “Lato”
- You can replace it in index.html (inside <head> tag)
Example:
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">

-------------------------------------
⚙️ 4. ANIMATIONS
-------------------------------------
- Fade-in effect is controlled by the “fade” class.
- If you want to disable fade-in:
  → Delete this part from index.html:
     const faders = document.querySelectorAll('.fade');
  → And remove the .fade section from style.css.

-------------------------------------
⬆️ 5. SCROLL-TO-TOP BUTTON
-------------------------------------
- Appears when you scroll down 300px.
- Located at the bottom-right corner.
- You can change its color in style.css under:
  #scrollTopBtn { ... }

-------------------------------------
📱 6. MOBILE RESPONSIVENESS
-------------------------------------
- Site automatically adjusts for mobile and tablet screens.
- The @media rules in style.css control this.

-------------------------------------
🧾 7. EDITING CONTENT
-------------------------------------
All text is inside index.html under sections:
→ About
→ Education
→ Experience
→ Skills
→ Contact

Edit directly between the <p>, <li>, or <h2> tags.

-------------------------------------
🚀 8. DEPLOYMENT
-------------------------------------
Since your Netlify is connected to GitHub:
→ Just replace files and commit changes in GitHub.
→ Netlify auto-updates within a minute.

-------------------------------------
💡 9. RECOMMENDED TOOLS
-------------------------------------
- Use VS Code for editing (syntax highlighting)
- Use Chrome for previewing changes
- For checking color contrast: https://color.review

-------------------------------------
✨ 10. BACKUP TIP
-------------------------------------
Before making major edits, download a ZIP backup of your repo.
That way, you can restore the old version anytime.

=====================================
Created for: Ankit Jaiswal
Version: 1.0 – Academic × Consultant Hybrid Website
=====================================
