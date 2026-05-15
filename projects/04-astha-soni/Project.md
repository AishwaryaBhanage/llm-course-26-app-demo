
---

slug: astha-soni

title: Recipe Remix: AI-Powered Recipe Transformation App

students:
  - Astha Soni

tags:
  - ai-recipes
  - computer-vision
  - nextjs

category: lifestyle

tagline: Transform recipe screenshots into personalized meals instantly.

featuredEligible: true

semester: "Spring 2026"

shortTitle: "Recipe Remix"

studentId: "116530101"

videoUrl: "https://drive.google.com/file/d/1EE3GK9HPFt8c4X9Eub6XtgZUUG_5vvxR/view?usp=drive_link"

thumbnail: "https://drive.google.com/file/d/15nfCR0x-m32AeGFDYhiokOoAXfWj1pL3/view?usp=drive_link"

githubUrl: "https://github.com/asthasoni22/Recipe-Remix-vibecoding"

---


## Problem

People often find recipes online that do not match their dietary needs, preferred cuisine, or available cooking appliances. Modifying recipes manually can be time-consuming and difficult, especially for beginners.


## Solution

Recipe Remix is an AI-powered application that transforms recipe screenshots into customized recipes based on cuisine preferences, dietary restrictions, and cooking appliances. Users can upload any recipe image and instantly receive a remixed version tailored to their needs.


## User Flow

- Upload a recipe screenshot using drag-and-drop or file upload
- Select a preferred cuisine style such as Indian, Italian, Thai, or Mexican
- Choose dietary preferences like Vegan, Keto, or Gluten-Free
- Select the available cooking appliance such as Oven, Air Fryer, or Stovetop
- Generate the remixed recipe using AI
- Copy or download the transformed recipe


## LLM Components

- **Recipe Extraction** — Uses vision-based AI to extract recipe text from uploaded screenshots
- **Recipe Transformation Engine** — Adapts ingredients and cooking instructions based on selected cuisine and dietary preferences
- **Appliance Adaptation System** — Rewrites cooking steps according to the selected appliance
- **Natural Language Generation** — Produces human-readable recipe instructions with improved clarity and formatting


## Tools

- **Frontend:** Next.js 14, React, Tailwind CSS
- **Backend:** Next.js API Routes, Node.js
- **LLM:** OpenAI GPT-4o (Vision + Text)
- **Deployment:** Vercel
