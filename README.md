# PersonUp

![Status: MVP Stage](https://img.shields.io/badge/Status-MVP%20Stage-blue)
![Built with Glide](https://img.shields.io/badge/Built%20with-Glide-black)
![Database Google Sheets](https://img.shields.io/badge/Database-Google%20Sheets-green)
![Automation Make](https://img.shields.io/badge/Automation-Make-purple)
![AI OpenAI | Gemini](https://img.shields.io/badge/AI-OpenAI%20%7C%20Gemini-orange)

PersonUp is a Human Data Intelligence SaaS that combines psychological and symbolic tests with generative AI.  
It helps organizations understand their people through data-driven insights, personalized feedback, and smart dashboards—simplifying talent development and HR decision-making.

---

## Overview
**Status:** MVP (Minimum Viable Product)  
**Purpose:** Help organizations use behavioral and symbolic data to make better decisions about culture, leadership, and team composition.

---

## Key Features
- Secure login with Google  
- Integrated psychological and symbolic tests (DISC, MBTI, Enneagram, etc.)  
- Automatic scoring and result calculation (Google Sheets)  
- AI-generated interpretations and feedback (OpenAI / Gemini)  
- Dynamic dashboards for users, teams, and HR  
- Multi-role access: User / Admin / Superadmin  
- Basic gamification (points, challenges, ranking)  
- Auto-generated reports and data exports  

---

## Target Users
- HR and Culture teams  
- Organizations implementing data-driven people analytics  
- Coaches and consultancies needing scalable diagnostic tools  

---

## Tech Stack
| Layer | Tool | Purpose |
|-------|------|----------|
| Frontend | Glide | Web/mobile interface |
| Database | Google Sheets | Data storage and formulas |
| Automation | Make (Integromat) | Logic and API orchestration |
| AI Engine | OpenAI GPT-4o mini / Gemini Pro 2.5 | Text generation and interpretation |
| Auth | Google Login | Simple secure access |

---

## Repository Structure
/PersonUp
├── README.md
├── /docs          → Documentation and guides
├── /design        → Mockups / Figma files
├── /exports       → Glide or Make templates
├── /data          → Example CSVs / Sheet samples
└── LICENSE
---

## How to Test the MVP
1. Create base tables in Google Sheets: `Users`, `Tests`, `Responses`, `Results`, `IA_Outputs`.  
2. Connect Glide → Google Sheets.  
3. Design views: Dashboard, My Tests, Results, Team Ranking.  
4. Use Make to automate data flow → AI → return results.  
5. Validate with 5 pilot users and 1 HR admin.  

---

## Roadmap (6-Week Plan)
1. Define data model and test formulas  
2. Integrate Glide + Sheets + Make  
3. Pilot with initial testers  
4. Build HR dashboards and admin control  
5. Add AI feedback and gamification  
6. Launch landing page and collect feedback  

---

## Contributing
- Open issues for bugs or ideas  
- Use feature branches and clear pull requests  
- Document product decisions in `/docs`

---

## License
No License for private SaaS development.

---

## Contact
**WAV / We Are Vision**  
[wearevision.cl](https://wearevision.cl)  
contacto@wearevision.cl
