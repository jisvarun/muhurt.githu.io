\# शुभ मुहूर्त — Muhurat Website



एक modern, responsive single-page website जो रोज़ाना का शुभ मुहूर्त, पंचांग और अलग-अलग अवसरों (विवाह, गृह प्रवेश, मुंडन, नामकरण आदि) के लिए मुहूर्त जानकारी दिखाती है।



\## Tech Stack



\- \*\*HTML5\*\*

\- \*\*Bootstrap 5\*\* (CDN se load hota hai — grid, layout ke liye)

\- \*\*Custom CSS\*\* (theme, typography, animations — same file me)

\- \*\*Google Fonts\*\* — Rozha One (headings) + Mukta (body text)

\- Koi build step / dependency nahi — bas ek `.html` file hai



\## File



```

muhurat.html   → poora website (HTML + CSS ek hi file me)

```



\## Kaise Use Karein



1\. `muhurat.html` file ko kisi bhi browser me directly open karein — koi server ki zaroorat nahi.

2\. Agar web par host karna hai, to file ko kisi bhi static hosting (GitHub Pages, Netlify, Vercel) par upload kar dein.



\## Sections



| Section | Kya dikhata hai |

|---|---|

| Hero | Aaj ki tithi + Abhijit Muhurat + Rahu Kaal |

| Panchang Strip | Tithi, Nakshatra, Yog, Karan, Sunrise |

| मुहूर्त श्रेणियाँ | Vivah, Griha Pravesh, Mundan, Namkaran, वाहन/संपत्ति, व्यापार |

| आगामी शुभ तिथियाँ | Timeline format me upcoming auspicious dates |

| CTA | Personalized muhurat ke liye form/contact prompt |



\## Customize Kaise Karein



\- \*\*Rang (Colors):\*\* `<style>` block ke top par `:root { ... }` me CSS variables (`--maroon`, `--marigold`, `--teal`, etc.) change karein.

\- \*\*Content:\*\* Panchang values, ceremony list, aur upcoming dates seedhe HTML me hardcoded hain — inhe manually update karna hoga (ya baad me kisi API/backend se dynamic bana sakte hain).

\- \*\*Fonts:\*\* Google Fonts link `<head>` me hai; font family CSS variables me change kar sakte hain.



\## Aage Kya Add Kiya Ja Sakta Hai



\- Panchang data ke liye koi real API (jaise DrikPanchang, AstroSage) integrate karna

\- Date-wise dynamic calendar/calculator

\- User ki janm-tithi ke basis par personalized muhurat form ka backend



\---

Built with HTML, CSS \& Bootstrap 5.

