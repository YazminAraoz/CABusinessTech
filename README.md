# AtelierFlow — Usability Test Report

**Target App:** [AtelierFlow (CABusinessTech)](https://yazminaraoz.github.io/CABusinessTech)  
**Test Objective:** Evaluate the user experience of the pricing calculator, prototype navigation, information density, and data privacy disclaimers.

---

## 🧪 Test Case Summary & User Feedback

### 1. Information Density & Calculator UX
* **What they tried:** Setting up a custom quote using detailed pricing parameters (hourly rates, vacations, material costs).
* **What broke or confused them:** High information density created cognitive fatigue and visual overwhelm. Users wanted a simpler default view to avoid abandoning the tool.
* **Direct User Quotes:**
  > *"It's like a little bit it overwhelms me, you know?... I have to read every little thing."*
  >
  > *"We're very lazy... you're always two clicks away from them uninstalling the app."*
  >
  > *"I don't know if [an illustrator] would have the patience to handle the app... it's easier to talk to the client than fill out every little thing."*
* **What was changed:** Introduced a **progressive disclosure pattern**. Basic parameters (commission type, hours, basic materials) are displayed first, while complex variables (vacations, surcharges) are collapsed under an **"Advanced Options"** toggle.

---

### 2. Header Control & Role Navigation
* **What they tried:** Navigating between client and artist views (`View as Client` vs. `View as Artist`) and identifying the prototype scope banner.
* **What broke or confused them:** Key switching mechanisms were missed because they lacked visual hierarchy and were located outside the natural focus area.
* **Direct User Quotes:**
  > *"Intuitively I didn't look up until I found that part. It seemed more intuitive to me the previous time that I could select it from below."*
* **What was changed:** Scaled up the header prototype controls (`Academic Prototype` / `View as Client` / `View as Artist`) and increased font weight/contrast for immediate visual prominence.

---

### 3. Data Handling & Prototype Scope
* **What they tried:** Understanding how personal client data and commission details are managed during prototype execution.
* **What broke or confused them:** Lack of immediate clarity on backend storage and legal/privacy terms for user-entered data.
* **Direct User Quotes:**
  > *"Since it's a prototype... with the disclaimer it would be enough... some legal thing you're going to have to research."*
* **What was changed:** Added explicit disclaimer notices confirming that local browser session storage is used and no data is transmitted to external servers.

---

### 4. Pricing Benchmarks (Future Feature)
* **What they tried:** Determining fair hourly and commission rates as a new artist.
* **What broke or confused them:** Difficulty in estimating realistic timelines and prices without market context.
* **Direct User Quotes:**
  > *"Which is something I should know as an artist... how long it takes me to do x thing, but maybe I don't know very well how much..."*
* **What was changed:** Added a feature concept to the backlog for automated **Community Rate Benchmarks** (calculating average price references for new artists).

---

## 📊 Results Summary

| Testing Area | Identified Problem | Direct Insight / Quote | Action Taken |
| :--- | :--- | :--- | :--- |
| **Calculator UI** | Information overload | *"It overwhelms me... I have to read every little thing."* | Added **"Advanced Options"** toggle. |
| **Role Switcher** | Visual hierarchy | *"Intuitively I didn't look up..."* | Scaled header controls & increased contrast. |
| **Usability** | Friction in form entry | *"It's easier to talk to the client than fill out every little thing."* | Simplified default inputs & added presets. |
| **Data Scope** | Data privacy ambiguity | *"With the disclaimer it would be enough..."* | Added prototype local-storage disclaimer. |
