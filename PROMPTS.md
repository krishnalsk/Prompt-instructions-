# Reusable Prompts (copy, paste, change the [brackets])

Tip: always upload `PROJECT_NOTES.md` and `script.js` (and your PPT if needed) together with the prompt.

---

## 1. Create a new demo website from a PPT
```
Act as a professional web developer. Analyze my uploaded PPT first and identify the project title,
module names, descriptions and order. Create a working demo website using only HTML, CSS and JavaScript
(separate index.html, style.css, script.js).

Requirements:
- Home page with title, short introduction and a "Start Demo" button.
- Navigation with ONLY the modules from the PPT, same names, same order.
- Each module shows: name, purpose, how it works, a small interactive demo, expected output.
- Previous Module, Next Module and Back to Home buttons.
- Use sample data and simulated processing. Clearly label simulated parts. No real backend or database.
- Pass data from one module to the next to show the system flow.
- Do not add extra modules, login, dashboards or payments. Keep it simple to run in VS Code.
Also give: VS Code run steps and a step-by-step presentation guide.
```

## 2. Give context to continue this project
```
I have a college demo website for "Detecting Zero Day Malware Threats using AI-Based Endpoint Security
Analytics". I attached PROJECT_NOTES.md and script.js. Read them first. The modules are:
1. Behavioral Monitoring  2. Malware Detection  3. Incident Response.
Everything is simulated (no backend). Do not add new modules. Help me with: [your request].
Give the full changed code for only the files that change.
```

## 3. Change or improve one module
```
In my attached project, improve Module [number: name]. I want: [example: add a search box / show a table /
add a new sample scenario]. Keep the same style and keep passing data through the shared `state` object.
Do not change the other modules. Show me exactly which function to replace.
```

## 4. Fix a bug
```
My demo has a problem. What I did: [steps]. What I expected: [expected]. What happened: [actual].
Browser console error (press F12 → Console): [paste error or write "none"].
Find the cause in the attached script.js and give the smallest fix.
```

## 5. Change design or look
```
Change only the design in style.css: [example: dark theme / bigger fonts for projector / college colors
blue and gold]. Do not change the logic in script.js.
```

## 6. Make the presentation speech
```
Based on the attached project, write a [5 / 8] minute presentation script in simple English.
For each module give: what to say, what to click, and what the audience will see.
Include a short opening and closing. Say clearly that the demo is simulated.
```

## 7. Prepare for faculty questions (viva)
```
Act as a faculty member. Ask me 15 questions about my project (zero-day malware, behavior-based detection,
AI/ML, endpoint security, the 3 modules and this demo). After each question give a short model answer
in simple English. Include tricky questions like "Is the AI real?" and "Why not use signature detection?".
```

## 8. Explain the code to me
```
Explain the attached script.js to me in simple English, function by function. I am a beginner.
Show how data moves from Module 1 to Module 2 to Module 3.
```

## 9. Add the real ML idea (explanation only, for questions)
```
Explain in simple English how my simulated scoring could be replaced by a real machine learning model
(dataset, features, training, testing, accuracy). Do not change my code, explanation only.
```
