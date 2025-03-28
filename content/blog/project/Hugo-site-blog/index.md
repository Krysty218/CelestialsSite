---
title: "Crafting the Celestials' Realm"
summary: "A deep dive into how we built The Celestials' website using Hugo and Blowfish Lowkey, the challenges we faced, and the lessons learned along the way."
categories: ["Furnace"]
tags: ["hugo", "blowfish", "vercel", "web development"]
date: 2025-03-28
draft: false
---
  

Building a site can be a pain. But with Hugo, it’s blazingly fast—once you figure out how everything clicks together. What started as a simple setup turned into a deep dive into **theme customization, structuring content, and deploying without breaking things**. Here’s how we forged **The Celestials' Realm**, what burned down, and what we reforged.  

## **Why Hugo + Blowfish Lowkey?**  
We wanted something **fast, flexible, and hands-off**—Hugo checked all the boxes. Markdown-based content? Perfect. Static speed? Insane. Blowfish Lowkey gave us a solid base, but we had to **hammer it into shape** to fit our vision.  

## **What We Reforged**  
- **The Odyssey (Blog)** → A chronicle of our journey, from insights to experiments.  
  - **Memento (Personal)** → Thoughts, reflections, and things worth remembering.  
  - **Furnace (Projects)** → The fires where our projects take shape—the process, struggles, and breakthroughs.  
  - **Miscellaneous** → Anything that doesn’t fit but still deserves a place.  
- **The Forge (Showcase)** → Where we present our finished creations, tempered and refined.  

## **What Burned Down (and How We Rebuilt It)**  
### **1. Hugo’s Learning Curve**  
Hugo is blazingly fast, but its templating system? Not so intuitive. Wrestling with **partials, taxonomies, and front matter** took some trial and error. 

 **Fix:** Reverse-engineering Blowfish’s structure made it click.  

### **2. Homepage Author Display Instead of Welcome Text**  
Blowfish’s default behavior showed **author metadata** where a welcome message should be. 

**Fix:** Tweaked `hero.html` inside `layouts/partials/home` to actually greet visitors properly.  

### **3. Vercel Deployment Hiccups**  
First deploy? Crashed. Hugo version mismatch.
 
**Fix:** Locked the correct Hugo version in `vercel.json` and smooth sailing from there.  


## **Lessons From The Fire**  
- **Hugo makes static sites blazingly fast, but expect a few bruises learning it.**  
- **Check the theme’s defaults first—sometimes small tweaks fix big annoyances.**  
- **Vercel is smooth, but double-check your Hugo version before deploying.**  

## **What’s Next?**  
The site is up, but we’re not done. Next, we’re **refining the design, enhancing navigation, and maybe adding search functionality.** If you’re thinking about using Hugo + Blowfish, go for it—just be ready to break and remake things along the way.  
