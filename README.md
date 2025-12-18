# Gradians Elite | Academic Intelligence Suite

**Gradians Elite** is a high-performance, dark-themed academic management dashboard designed for students (specifically optimized for VIT & IIT grading systems). It combines real-time GPA calculation with predictive AI modeling to help students visualize their academic trajectory and plan their grades effectively.

---

## 🚀 Key Features

### 1. Smart SGPA Calculator

* **Real-time Processing:** Calculations update instantly as you modify credits or grades.
* **Course Manifest:** Manage theory, lab, and project courses within a sleek, glassmorphic interface.
* **Automated Status:** Categorizes your performance (e.g., "Elite Scholar," "Distinction") based on your current marks.

### 2. Predictive AI (GPA Forecaster)

* **Target Simulation:** Input your current CGPA and credits to calculate exactly what SGPA you need in future semesters to reach your goal.
* **Feasibility Check:** The system mathematically validates if your target is achievable (under the 10.0 cap).
* **Goal Breakdown:** Provides a suggested distribution of grades (e.g., how many 'S' or 'A' grades are required).

### 3. Deep Analytics

* **Cumulative Growth:** A linear trend chart visualizing CGPA progress across semesters.
* **Subject Balance:** A polar area chart that breaks down credit distribution between Theory, Lab, and Project work.

### 4. Productivity Tools

* **AI Bulk Import:** Rapidly inject multiple courses using a simple comma-separated text format.
* **PDF Export:** Generate a professional academic report of your dashboard with one click.
* **Local Persistence:** Data is automatically saved to your browser's local storage—no login required for immediate use.

---

## 🛠️ Technology Stack

* **Frontend:** HTML5, Tailwind CSS (Custom Dark/Light configuration)
* **Icons:** [Lucide Icons](https://lucide.dev/)
* **Charts:** [Chart.js](https://www.chartjs.org/)
* **PDF Generation:** [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/)
* **Typography:** Plus Jakarta Sans

---

## 📥 Installation & Usage

1. **Clone or Download:** Save the code as an `.html` file (e.g., `index.html`).
2. **Run:** Open the file in any modern web browser (Chrome, Edge, Brave, Safari).
3. **Sync:** Use the "Smart Import" tool to quickly add your current semester's subjects.

---

## 💡 How it Works (The Math)

The **GPA Forecaster** uses the following formula to determine your required future performance:

If the result is > 10.0, the system flags the goal as mathematically impossible, helping you set more realistic academic targets.

---

## 🎨 UI/UX Highlights

* **Glassmorphism:** Modern frosted-glass effect with `backdrop-blur`.
* **Responsive:** Fully functional on mobile, tablet, and desktop.
* **Adaptive Theme:** Supports both High-Contrast Dark mode and a Clean Light mode.
* **Micro-interactions:** Subtle hover animations and floating profile elements for a premium feel.


