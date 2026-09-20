# Hi, I'm Rachel

I'm a student exploring the intersection of artificial intelligence and real-world problem solving. My focus is on machine learning — understanding how models learn, why they fail, and how to build systems that actually work outside of a notebook.

I am also an active volunteer first responder, an NREMT and New York State Certified EMT, at Eastchester Volunteer Ambulance Corp.

My personal mission: *Build things that are useful, understand them deeply, and put them to work helping people.*

---

## What I believe

- **Understand before you apply** — knowing why an algorithm works makes you dangerous in the best way. Treat black boxes as temporary, not permanent.
- **Measure, don't assume** — intuition about what will improve a model is cheap and often wrong. Run the ablation, compare the variants, and let the numbers pick the design.
- **Ground every claim** — a model that cites its source and says "I don't know" is more useful than one that always has an answer. Especially when the answer touches someone's health.
- **Keep the human in charge** — in high-stakes domains the model drafts, the expert decides. Build the correction loop in from the start, and treat every rejection as training signal.
- **AI should empower, not replace** — the best systems give a person more reach: a faster scan, a sharper practice call, a second set of eyes. The goal is a better-equipped expert, not an absent one.

---

## Projects

### Unified Deep Learning Framework for MRI Image Contrast Translation

- A U-Net that synthesizes one MRI contrast from another in both directions (T1↔T2), so a scan session can acquire a single contrast instead of several.
- I compared five loss configurations and found that a composite loss (L1 + perceptual + gradient + frequency) beats any single term, sharpening edges and preserving fine structural detail that an L1 baseline blurs away.
- Presented a poster and gave a talk in the "Statistics and AI for Science and Society" session at the New England Statistics Symposium (NESS), May 2026.
- Session listing: https://symposium.nestat.org/images/parallel_session.html
- Slides: https://drive.google.com/file/d/1b7paNmdYKP00-6XvB4gb-I_d6_b0mR-v/view

### EMS-AI-SIM

- An AI-native ride-along simulator where EMTs run a full emergency call and get a graded debrief.
- Source material is compiled once into a persistent, cross-linked wiki rather than retrieved from raw documents, or direct LLM query per request; every clinical claim must carry explicit citations.
- The model builds knowledge database in a closed loop learning with human expertise in control — the AI drafts scenarios, a certified EMT approves or rejects them, and every rejection is distilled into lessons that shape the next draft.
- Repository: https://github.com/rachelyangg6-cloud/EMS-AI-SIM
- Live app: https://ambulance.emsridealong.app/

---

## What I'm working on

- Deepening my understanding of transformer architectures and how attention mechanisms actually work
- Building projects that go beyond toy datasets — real data, real messiness, real lessons
- Learning and practicing how ML systems are deployed and maintained in production

---

## Say hi

- 📬 [rachel.yangg6@gmail.com](mailto:rachel.yangg6@gmail.com)

Or open an issue — I read everything.
