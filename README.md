# Krushnrajsinh Chudasama — Premium Freelance Portfolio

A bespoke, high-performance portfolio website engineered for **Krushnrajsinh Chudasama** (Freelance Website Developer & Presentation Designer). Built with React 19, TypeScript, Vite, and custom HTML5 Canvas interactive thread physics.

---

## ⚡ Central Configuration

All personal details, primary email address, availability, achievements, services, and portfolio projects are configured in **a single central location**:

📁 **[`src/config.ts`](file:///C:/Users/hp/.gemini/antigravity/scratch/portfolio/src/config.ts)**

```typescript
export const SITE_CONFIG = {
  fullName: "Krushnrajsinh Chudasama",
  brandName: "Krushnrajsinh Chudasama",
  professionalIdentity: "Freelance Website Developer & Presentation Designer",
  email: "krushuchudasama03@gmail.com", // <-- Change here to update everywhere
  age: 15,
  isAvailableForWork: true,
  // ...
};
```

---

## 🚀 How to Run Locally

### Prerequisites
- Node.js (v18+ or v24+)
- npm

### Commands
```bash
# Navigate to project folder
cd C:\Users\hp\.gemini\antigravity\scratch\portfolio

# Install dependencies (if not already done)
npm install

# Run the live development server
npm run dev

# Or build for production
npm run build
```

The website will be served at `http://localhost:5173/`.

---

## ✨ Features & Architecture

1. **Interactive Cursor Threads (Signature Canvas Feature)**:
   - File: [`src/components/InteractiveThreads.tsx`](file:///C:/Users/hp/.gemini/antigravity/scratch/portfolio/src/components/InteractiveThreads.tsx)
   - Organic particle field with dynamic distance-based thread connections.
   - Mouse repulsion and attraction with inertia and easing.
   - Respects `prefers-reduced-motion` and adapts density for mobile devices.
   - Zero DOM bloat using `requestAnimationFrame`.

2. **PowerPoint Presentation Design Showcase**:
   - File: [`src/components/PresentationService.tsx`](file:///C:/Users/hp/.gemini/antigravity/scratch/portfolio/src/components/PresentationService.tsx)
   - Interactive 16:9 HD slide preview mockup with theme switching (Dark Cinematic, Academic Research, Modern Business).
   - Demonstrates clear data hierarchies, charts, and deliverables.

3. **Modern Website Design & Development Showcase**:
   - File: [`src/components/WebsiteService.tsx`](file:///C:/Users/hp/.gemini/antigravity/scratch/portfolio/src/components/WebsiteService.tsx)
   - Realistic browser window preview with URL pill and interactive concept switcher.
   - Demonstrates responsive layouts, clean code handover, and performance standards.

4. **Honors & Achievements**:
   - File: [`src/components/Achievements.tsx`](file:///C:/Users/hp/.gemini/antigravity/scratch/portfolio/src/components/Achievements.tsx)
   - Highlights your verified accolades:
     - **WSRO Regional Winner** (World STEM & Robotics Olympiad)
     - **Sahodaya Inter-School Debate** distinction
     - **Model United Nations (MUN)** delegation & diplomacy

5. **Direct 1-Click Email Flow (User Requested)**:
   - File: [`src/components/Contact.tsx`](file:///C:/Users/hp/.gemini/antigravity/scratch/portfolio/src/components/Contact.tsx)
   - Clicking **CONTACT ME** immediately launches the visitor's default email client with your address (`krushuchudasama03@gmail.com`), custom subject, and project scope already pre-filled.
   - Also includes a one-click copy button with festive confetti feedback.
