<div align="center">

<img src="assets/hero.svg" width="100%" alt="Maram Rzeigui, élève ingénieure Mobile, Full Stack et IA" />

<a href="https://www.linkedin.com/in/maram-rzeigui/"><img src="https://img.shields.io/badge/LinkedIn-Maram_Rzeigui-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:maram.rzeigui@esprit.tn"><img src="https://img.shields.io/badge/E--mail-maram.rzeigui@esprit.tn-B83A46?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://portfolio-nine-lime-qt6zbk7swp.vercel.app"><img src="https://img.shields.io/badge/Portfolio-en_ligne-121215?style=for-the-badge&logo=vercel&logoColor=white" /></a>

<img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=600&size=21&duration=3000&pause=800&color=E5545F&center=true&vCenter=true&width=700&lines=Je+livre+des+produits+complets%2C+du+cahier+des+charges+%C3%A0+la+production;Mobile+offline-first+%C2%B7+IA+locale+%C2%B7+pipelines+temps+r%C3%A9el;En+recherche+d%27un+PFE+de+6+mois+%C2%B7+f%C3%A9vrier+2027" alt="Typing" />

</div>

<br/>

<table align="center">
<tr>
<td align="center" width="25%"><h2>93,5 %</h2><sub>de précision en prédiction<br/>de pathologie (MedAIChain)</sub></td>
<td align="center" width="25%"><h2>100 %</h2><sub>hors ligne : application de<br/>randonnée en zone sans réseau</sub></td>
<td align="center" width="25%"><h2>20 / jour</h2><sub>commandes en ligne générées<br/>pour un restaurant client</sub></td>
<td align="center" width="25%"><h2>OCPP 1.6J</h2><sub>bornes de recharge réelles<br/>pilotées par Volteo</sub></td>
</tr>
</table>

## 👩‍💻 À propos

Élève ingénieure en informatique à **ESPRIT** (2022 – 2027), spécialité **Systèmes d'Information Mobile**. Je livre des produits complets en autonomie, **du cahier des charges au déploiement en production** : applications mobiles offline-first, pipelines de données temps réel, intégrations d'IA et de blockchain.

> 🎯 **Disponible pour un PFE de 6 mois à partir de février 2027.**

## 💼 Expérience

<details open>
<summary><b>🤖 Smartovate</b> · Junior AI Engineer (freelance) · <i>depuis 09/2026 · Londres, à distance</i></summary>
<br/>

**Pipeline temps réel de détection de fraude bancaire**
- Architecture d'un pipeline de streaming (ingestion → validation → scoring → restitution) sur **Kafka / Redpanda** et Python.
- Modèle **XGBoost** de scoring de fraude avec extraction de features comportementales (profil client, écart au panier moyen, fréquence).
- Contrôles qualité et **idempotence** : un rejeu du pipeline ne crée aucun doublon sur des données bancaires sensibles.
- Observabilité : logs, métriques et tableau de bord de suivi des performances du modèle.

`Python` `Kafka` `Redpanda` `XGBoost` `Streaming ML` `PostgreSQL` `AWS`
</details>

<details open>
<summary><b>🥾 RZ Prod</b> · Développeuse full stack (freelance) · <i>05/2026 – 07/2026 · Tunisie</i></summary>
<br/>

**Plateforme de randonnée et d'écotourisme, en partenariat avec le PNUD, le GEF/SGP et la SMSA**
- Architecture **offline-first** pour une zone de montagne sans réseau : cartes et sentiers en cache SQLite (GeoJSON), navigation GPS, alertes de sortie de sentier et **bouton SOS 100 % hors ligne**.
- Conception d'une seconde application, **EcoTracer**, qui enregistre les sentiers par GPS en temps réel, validée sur le terrain en 2 campagnes de tests en montagne.
- Chatbot IA **EcoBot**, bilingue français / arabe, avec quiz sur la faune, la flore et l'écotourisme.
- Livré en équipe de 2 en 3 mois : application Flutter, EcoTracer, back-office Flutter Web, API NestJS + PostgreSQL / PostGIS.

`Flutter` `NestJS` `PostgreSQL` `PostGIS` `SQLite` `GPS` `IA`
</details>

<details>
<summary><b>🍕 Speranza Pizza</b> · Développeuse (freelance) · <i>09/2025 – 10/2025 · client en France, à distance</i></summary>
<br/>

- Site de commande en ligne mis en production (Firebase, Vercel, Hostinger, paiements **Stripe**), jusqu'à **20 commandes par jour**.
- Application mobile d'administration pour suivre les commandes en temps réel.

`Firebase` `Stripe` `Vercel` `Mobile`
</details>

<details>
<summary><b>💻 Linedata</b> · Stagiaire développeuse .NET / Blazor · <i>07/2025 – 08/2025 · Tunis</i></summary>
<br/>

- Deux applications web **Blazor** synchronisées en temps réel via **SignalR**, sans rechargement.
- Architecture Message-Driven UI et intégration de fonctionnalités d'IA en C# / .NET.

`C#` `.NET` `Blazor` `SignalR`
</details>

## 🚀 Projets phares

<table>
<tr>
<td width="50%" valign="top">

### ⚡ [Volteo](https://github.com/maramrzeigui/volteo)
<a href="https://github.com/maramrzeigui/volteo"><img src="https://raw.githubusercontent.com/maramrzeigui/volteo/main/docs/screens/couverture.png" width="100%" /></a>

Plateforme SaaS de **recharge de véhicules électriques** : application mobile, back-office, bornes réelles en **OCPP 1.6J**, wallet Flouci / e-DINAR au solde exact, assistant IA local et guidage de trajet avec alertes vocales.

`React Native` `Laravel` `React` `Node.js` `OCPP` `Ollama`

</td>
<td width="50%" valign="top">

### 🏥 [MedAIChain](https://github.com/maramrzeigui/medaichain)
*Équipe de 5 · 01/2026 – 05/2026*

- Pipeline IA : **OCR → 20 biomarqueurs → LLM Llama 3.2 3B fine-tuné (LoRA / QLoRA)**, diagnostic structuré et niveau d'urgence, **100 % en local**.
- 6 modèles ML : **93,4 %** en triage d'urgence, **93,5 %** en prédiction de pathologie.
- Ordonnances en **NFT ERC-721** sur Polygon, wallets chiffrés AES-256-GCM.

`Flutter` `NestJS` `PostgreSQL` `Python` `LLM` `Blockchain`

### 🎓 MentoraBall
*Plateforme éducative gamifiée · 01/2025 – 05/2025*

- **Google Gemini** intégré aux cours : résumer, traduire, approfondir en un clic.
- Navigation **par commandes vocales**, bascule vers l'**authentification faciale** après 3 échecs, OAuth2, reCAPTCHA, JWT.

`Symfony` `JavaFX` `MySQL` `Gemini`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎵 Studio de musique
*Applications natives · 11/2025*

Deux applications **Android (Kotlin)** et **iOS (Swift)** avec 7 instruments virtuels jouables en temps réel, un chatbot musical et une **IA générative** de composition à partir d'un texte (ElevenLabs).

`Kotlin` `Swift` `NestJS` `MongoDB Atlas` `IA générative`

</td>
<td width="50%" valign="top">

### 🌿 EcoGuide & EcoTracer
*RZ Prod · 2026*

Randonnée au Parc National de Jebel Chitana – Cap Negro : cartes hors ligne, SOS géolocalisé, enregistrement GPS des sentiers et chatbot EcoBot.

`Flutter` `NestJS` `PostGIS` `Offline-first`

</td>
</tr>
</table>

## 📂 Mes dépôts

<div align="center">

<a href="https://github.com/maramrzeigui/volteo"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=maramrzeigui&repo=volteo&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&description_lines_count=2" /></a><a href="https://github.com/maramrzeigui/medaichain"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=maramrzeigui&repo=medaichain&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&description_lines_count=2" /></a>
<a href="https://github.com/maramrzeigui/viaitalia"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=maramrzeigui&repo=viaitalia&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&description_lines_count=2" /></a><a href="https://github.com/maramrzeigui/student-management-devops"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=maramrzeigui&repo=student-management-devops&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&description_lines_count=2" /></a>
<a href="https://github.com/maramrzeigui/site-web-gesto"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=maramrzeigui&repo=site-web-gesto&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&description_lines_count=2" /></a><a href="https://github.com/maramrzeigui/site-web-ecoguide"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=maramrzeigui&repo=site-web-ecoguide&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&description_lines_count=2" /></a>
<a href="https://github.com/maramrzeigui/site-RZ"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=maramrzeigui&repo=site-RZ&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&description_lines_count=2" /></a><a href="https://github.com/maramrzeigui/portfolio"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=maramrzeigui&repo=portfolio&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&description_lines_count=2" /></a>

</div>

## 🤝 Projets en équipe

<div align="center">

<a href="https://github.com/Yassminette5/medaichain-mobile"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=Yassminette5&repo=medaichain-mobile&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&show_owner=true" /></a><a href="https://github.com/Yassminette5/medaichain-backend"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=Yassminette5&repo=medaichain-backend&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&show_owner=true" /></a>
<a href="https://github.com/rzprodcommunity-hue/Eco-Guide"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=rzprodcommunity-hue&repo=Eco-Guide&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&show_owner=true" /></a><a href="https://github.com/mouha-byte/app_ecotourisme"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=mouha-byte&repo=app_ecotourisme&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&show_owner=true" /></a>
<a href="https://github.com/azizgargouri/springboot-repo-"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=azizgargouri&repo=springboot-repo-&theme=transparent&hide_border=true&title_color=E5545F&icon_color=E5545F&text_color=8b8b95&bg_color=00000000&show_owner=true" /></a>

</div>

<details>
<summary><b>🔒 Contributions à des dépôts privés</b> (clients et projets d'école)</summary>
<br/>

| Dépôt | Projet | Technologies |
|---|---|---|
| `SMARTOVATEAI/subul-platform` | Plateforme Smartovate | TypeScript |
| `azizgargouri/Mag-Studio-Ios` · `-Android` · `-Backend` | Studio de musique : applications natives et API | Swift · Kotlin · TypeScript |
| `rzprodcommunity-hue/Guesto` | Solution de digitalisation des restaurants | HTML · CSS · JS |
| `mouha-byte/Restaurant` · `projet_ecoguide` | Site restaurant et projet EcoGuide | HTML · Flutter |
| `ProjectWeb-java/Mentora` · `koussayFaidi2003/javapi` | MentoraBall : clients web et desktop | Symfony · JavaFX |
| `Yassine-Ayache/ProjetWeb2A36` · `AyacheYass/Escprit` | Projets d'école web et C | PHP · C |

</details>

## 🛠️ Technologies

<div align="center">

**Mobile**<br/>
<img src="https://skillicons.dev/icons?i=flutter,dart,react,kotlin,swift,androidstudio,xcode&perline=10" />

**Back-end**<br/>
<img src="https://skillicons.dev/icons?i=nestjs,nodejs,spring,java,dotnet,cs,laravel,php,symfony&perline=10" />

**Front-end**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,angular,ts,js,html,css,tailwind&perline=10" />

**Données, IA & DevOps**<br/>
<img src="https://skillicons.dev/icons?i=python,kafka,opencv,postgres,mysql,mongodb,firebase,supabase,aws,docker,jenkins,git&perline=12" />

</div>

## 🎓 Formation, langues et certifications

| | |
|---|---|
| 🎓 **ESPRIT** | Diplôme d'ingénieur en informatique, spécialité Systèmes d'Information Mobile (2022 – 2027) |
| 👁️ **Computer Vision** | Module de 5e année (OpenCV) et certification NVIDIA (en cours) |
| 🇬🇧 **Anglais** | B2, certifié EF SET |
| 🇫🇷 **Français** | B2 |
| 🇹🇳 **Arabe** | Langue maternelle |
| 🇩🇪 **Allemand** | A2 |

## 📊 Activité

<div align="center">
<img width="100%" src="profile-3d-contrib/profile-night-rainbow.svg" alt="Contributions en 3D" />
<br/><br/>
<img width="100%" src="https://raw.githubusercontent.com/maramrzeigui/maramrzeigui/output/serpent.svg" alt="Serpent des contributions" />
<br/><br/>
<img height="170" src="https://github-readme-stats.vercel.app/api?username=maramrzeigui&show_icons=true&hide_border=true&bg_color=121215&title_color=E5545F&icon_color=E5545F&text_color=d0d0d6&include_all_commits=true&count_private=true&rank_icon=github" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maramrzeigui&layout=compact&hide_border=true&bg_color=121215&title_color=E5545F&text_color=d0d0d6&langs_count=8" />
</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:B83A46,100:121215" width="100%" />
</div>
