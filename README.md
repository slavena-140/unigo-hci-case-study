# UniGo - Digital Student Transit Card (UI/UX Case Study)

📅 **Date:** 3rd Semester (Winter 2025)  
🌱 **Project Status:** Completed (Human-Computer Interaction Academic Project)  

UniGo is a comprehensive, user-centric mobile application prototype designed to digitize and revolutionize the student public transit validation and renewal system for Varna Municipality. The project covers the full spectrum of User Experience (UX) engineering - moving from qualitative user research, persona creation, and low-fidelity paper wireframing to iterative user testing and a high-fidelity interactive prototype in Figma.

---

## 🔗 Live Interactive Prototype

You can launch, click through, and fully experience the responsive high-fidelity smartphone prototype directly inside your web browser:

👉 **[Click Here to Open the Figma Prototype](https://www.figma.com/design/d0Ljz169rgeOIFUmz0CvQk/UniGo---HCI-140-24126?node-id=3-10&p=f&t=vqBei82nwzw3fZtO-0)**  
*(Pro-Tip: Press **'R'** on your keyboard inside the Figma screen to reset the interactive user flow from the beginning!)*

---

## 🚀 The UX Lifecycle & Methodology

### 1. User Research Phase (Discovery)
Conducted qualitative in-depth user interviews with 3 real university students to identify core pain points in the existing physical registration workflow. 
- **Core Insights Uncovered:** Students lose hours waiting in physical lines at the municipality office every single semester, carry a constant emotional fear of losing/breaking their physical cards, and face sudden penalty fines due to a complete lack of expiration tracking.

### 2. Analysis & Target Personas
Synthesized research data into two distinct, high-signal target personas to guide all layout and interaction architectures:
- **Persona 1: Elitsa (19) - "The Confused Freshman":** Needs crystal clear guidance for initial pass activation, simple onboarding, and instant operational confirmation to avoid administrative friction.
- **Persona 2: Ivan (22) - "The Busy Working Bachelor":** Demands high-speed online processing under 5 minutes, transparent validation statuses, push notifications, and advanced security layers.

### 3. User Journey Mapping (AS-IS vs. TO-BE)
Mapped detailed psychological and operational timelines comparing the current framework to the UniGo implementation:
- **AS-IS:** Emotional dips down to **-5** during physical queuing, paper handling, and face-to-face bureaucratic friction.
- **TO-BE:** Sustained positive user engagement (**+4 to +5**) powered by automated push alerts 7 days prior to card expiration, mobile scanning of enrollment documents via camera, and instant digital validation.

### 4. Low-Fidelity Sketching & User Feedback
- Developed 2 full iterations of rapid paper prototypes (`Sketch 1` & `Sketch 2`).
- **Usability Testing Enhancements Implemented:** Re-engineered the dashboard based on user testing critiques - removed redundant buttons, added explicit explanatory subtext for primary menus, introduced visual system state icons (such as active verification checkmarks), and completely overhauled the typography scale (`H1: 24px Bold`, `Body: 16px Medium`).

---

## 📱 Core Application Modules Designed

- **Secure Gatekeeping & Registration:** Unified login view featuring separate workflows for returning users and a step-by-step document attachment pipeline for freshmen.
- **The Visual Ticket Wallet ("My Card"):** Employs a prominent, dynamic QR code interface tailored for rapid security verification by transit operators, featuring high-contrast validity flags (`Valid until 10.02.2026`).
- **Instant Mobile Renewal ("Zaverka"):** A specialized file-upload view allowing students to instantly capture a photograph of their semester university stamp and submit it for remote administrative approval.
- **Real-Time Route Telemetry:** Integrated map navigation view with live bus location tracking and schedule listings to add daily operational value.

---

## 🛠️ Tooling & Design Specifications
- **Design Environment:** Figma (Vector wireframing, component variants, smart animations, reactive overlays).
- **Design Tokens:** Strictly structured typography bounds (`H1/H2/Buttons/Body/Subtext`) and distinct visual accents for actionable states (solid color fills for sign-ins vs. outlined frames for secondary onboarding).

---

## 📁 Project Structure
```text
├── UniGo.pdf  # Full academic research & project documentation 
└── README.md  # Interactive presentation layer 
