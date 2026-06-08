<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=42&duration=2800&pause=900&color=DD0031&center=true&vCenter=true&width=800&lines=Mohamed+Askar" alt="Name" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2500&pause=1000&color=FFFFFF&center=true&vCenter=true&width=700&lines=Frontend+Engineer+%E2%80%A2+Angular+%26+TypeScript+Specialist;Building+AI-powered+products+from+scratch;Reactive+Architecture+%7C+Signals+%7C+RxJS" alt="Role" />

<br/>

[![X](https://img.shields.io/badge/X-@askarthemass-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/askarthemass)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mohamed%20Askar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-askar-a-9370a1b2/)
[![Gmail](https://img.shields.io/badge/Gmail-mohamedaskar476-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamedaskar476@gmail.com)
[![GitHub](https://img.shields.io/github/followers/askarthemasss?label=GitHub&style=for-the-badge&logo=github&logoColor=white&color=181717)](https://github.com/askarthemasss)

![Profile Views](https://komarev.com/ghpvc/?username=askarthemasss&style=for-the-badge&color=DD0031&label=PROFILE+VIEWS)

</div>

---

```typescript
// src/app/developers/askar.ts

import { Injectable, signal, computed } from '@angular/core';

@Injectable({ providedIn: 'root' })
export class AskarService {

  readonly role     = signal('Frontend Engineer');
  readonly location = signal('Chennai, India 🇮🇳');
  readonly employer = signal('Agilysys — Hospitality Technology');

  readonly stack = signal({
    primary:   ['Angular', 'TypeScript', 'RxJS', 'Signals'],
    tooling:   ['Jest', 'NgRx', 'ESLint', 'Git', 'Supabase'],
    exploring: ['Gemini AI', 'LangChain', 'Node.js', 'Python'],
  });

  readonly building = signal([
    'LifeOps  — AI-powered personal management PWA',
    'Recurra  — Subscription tracker with Gmail AI parsing',
    'Kairos   — Automated GitHub PR review tool',
  ]);

  readonly superpower = computed(() =>
    `Turning complex UI problems into elegant, reactive Angular solutions`
  );

  readonly mindset = computed(() =>
    `Ship fast. Build clean. Let AI handle the repetitive parts.`
  );
}
```

---

## ⚡ Tech Stack

### Frontend Core

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=for-the-badge&logo=reactivex&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=sass&logoColor=white)

### Testing & Quality

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black)
![Jasmine](https://img.shields.io/badge/Jasmine-8A4182?style=for-the-badge&logo=jasmine&logoColor=white)

### State & Architecture

![NgRx](https://img.shields.io/badge/NgRx-BA2BD2?style=for-the-badge&logo=redux&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![REST API](https://img.shields.io/badge/REST%20API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### Dev Workflow

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

### 🤖 AI Stack — What I Build With

![Google Gemini](https://img.shields.io/badge/Gemini%20AI-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20AI-D97706?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97706?style=for-the-badge&logo=anthropic&logoColor=white)
![Lovable](https://img.shields.io/badge/Lovable-FF3E9A?style=for-the-badge&logo=sparkles&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

---

## 🏗️ Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 LifeOps
> AI-powered personal life management PWA

An all-in-one life OS — habits, finance, health, career tracker, journal, and an embedded AI assistant (**Orbit AI**) built on Gemini. Designed as a production PWA with offline-first architecture.

**Stack:**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</td>
<td width="50%" valign="top">

### 📬 Recurra
> Subscription tracker with AI email parsing

Auto-detects active subscriptions by connecting to Gmail via OAuth, runs AI parsing on email receipts, and surfaces a clean spending dashboard. No manual entry needed.

**Stack:**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black)
![Gmail API](https://img.shields.io/badge/Gmail%20API-EA4335?style=flat-square&logo=gmail&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ Kairos
> Automated GitHub PR review tool

A developer productivity tool that auto-creates, reviews, and resolves GitHub PR comments using AI. Built to eliminate the manual overhead in code review cycles.

**Stack:**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![GitHub API](https://img.shields.io/badge/GitHub%20API-181717?style=flat-square&logo=github&logoColor=white)
![Claude AI](https://img.shields.io/badge/Claude%20AI-D97706?style=flat-square&logo=anthropic&logoColor=white)

</td>
<td width="50%" valign="top">

### 📡 Daily Angular Content
> Sharing modern Angular on X

Consistent technical content covering Angular v18–20 internals — Signals, `resource()` API, zoneless change detection, `@for`, `inject()`, incremental hydration, and more.

**Stack:**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
[![Follow on X](https://img.shields.io/badge/@askarthemass-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/askarthemass)

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=askarthemasss&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=DD0031&icon_color=DD0031&text_color=c9d1d9&count_private=true&include_all_commits=true" />
&nbsp;
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=askarthemasss&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=DD0031&text_color=c9d1d9&langs_count=6" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=askarthemasss&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=DD0031&ring=DD0031&fire=FF6B6B&currStreakLabel=DD0031&sideLabels=c9d1d9&dates=c9d1d9" width="55%" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=askarthemasss&theme=github-compact&hide_border=true&bg_color=0D1117&color=DD0031&line=DD0031&point=ffffff&area=true&area_color=3d0a0a" width="100%" />

</div>

---

## 🏆 Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=askarthemasss&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=6" />
</div>

---

## 🎯 What's Next

```
  ✅  Angular Signals & standalone components in production
  ✅  SSO implementation & reusable billing component
  ✅  100+ LeetCode problems solved
  ✅  Shipped 3 AI-assisted side projects

  🔄  Zoneless Change Detection & Angular Resource API
  🔄  LifeOps v1 public launch
  🔄  Recurra private beta

  🎯  Personal dev portfolio
  🎯  Open-source Angular contributions
  🎯  Angular blog / tutorial series
  🎯  Speak at a tech meetup
```

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=3500&pause=1500&color=DD0031&center=true&vCenter=true&width=700&lines=Always+building.+Always+shipping.+Always+learning." alt="Footer Motto" />

<br/>

[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/askarthemass)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-askar-a-9370a1b2/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamedaskar476@gmail.com)

</div>
