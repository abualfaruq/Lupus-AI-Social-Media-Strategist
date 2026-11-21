# Lupus Skill — Folder Structure

```
lupus-ai-sosmed-strategist/
│
├── BRAND-PROFILE.md                          # Konteks brand (diisi via form website, dibaca PERTAMA tiap sesi)
├── SYSTEM-PROMPT.md                          # System prompt utama Lupus (LOAD PERTAMA KALI)
├── SKILL.md                                  # Skill detail Lupus (BACA SETELAH SYSTEM PROMPT)
│
├── standards/                                # Standar per capability + anti-generik rules
│   ├── standar-socmed-audit.md              # Framework & standar Social Media Health Check (7 Area Audit)
│   ├── standar-brand-level-strategy.md      # Standar penyusunan social media strategy di brand level (7 Komponen)
│   ├── standar-campaign-strategy.md         # Standar penyusunan campaign strategy terintegrasi (8 Komponen)
│   ├── standar-content-strategy.md          # Standar penyusunan content strategy & planning (6 Komponen + pillar checklist + anti-generik)
│   ├── standar-strategic-pillar.md          # ⚠️ Standar strategic pillar — DNA konten brand: penggalian konteks, formulasi, validasi, implementasi sebagai checklist
│   ├── standar-content-plan-12-layer.md    # ⚠️ 12 layer wajib per ide konten (prescriptive)
│   ├── standar-deskripsi-konten.md          # ⚠️ 10 layer wajib deskripsi konten existing (observasi)
│   ├── standar-social-commerce.md           # Standar integrasi social commerce (live, affiliate, marketplace)
│   ├── standar-monitoring-qa.md             # Standar framework monitoring & quality assurance + decision rules
│   ├── standar-riset-untuk-strategi.md      # ⚠️ Standar riset untuk fondasi strategi + insight bridge chain
│   ├── standar-six-thinking-hats.md        # ⚠️ Framework challenge strategi dari 6 perspektif (WAJIB ditawarkan setelah strategi selesai)
│   ├── standar-explore-strategic-angle.md  # ⚠️ Standar Explore Strategic Angle: 3 layer output, istilah original, anti-generik check
│   ├── standar-kpi-okr.md                 # ⚠️ Standar KPI (3 layer: Proses→Output→Outcome) + OKR untuk social media
│   └── anti-generik-rules.md               # ⚠️ Red-flag phrases & standar spesifisitas (WAJIB BACA)
│
├── frameworks/                              # Framework analisis & evaluasi
│   ├── ecosystem-360-framework.md           # Framework pemetaan ekosistem social media 360° (7 Elemen + Assessment Matrix)
│   ├── three-level-strategy.md              # Framework strategi tiga level (Brand → Campaign → Content)
│   ├── funnel-mapping-socmed.md             # Framework TOFU/MOFU/BOFU untuk social media (5 Stage + Diagnosis)
│   ├── competitive-landscape.md             # Framework analisis kompetitor di social media (6 Dimensi)
│   ├── brand-value-excavation.md            # Framework menggali nyawa brand: Nyawa Brand (4-5 pilar), Tiga Sumber Value, Value Map
│   └── content-strategic-quality.md         # Framework lensa strategi atas kualitas konten: Terarah-Tajam, Peluru, Mindset Skeptis, Tiga Peran Tim
│
└── references/                              # Referensi konteks & knowledge base
    ├── brand-profile-template.md            # Struktur format konteks brand (bentuk isi BRAND-PROFILE.md)
    ├── strategic-thinking-problem-solving.md # ⚠️ Framework strategic thinking: Centaur Model, 7 Pilar, FOREST Method, What-If Analysis
    ├── interaction-examples.md             # Contoh interaksi Lupus di berbagai skenario (7 contoh)
    ├── integration-models.md               # 5 model integrasi ekosistem social media (dari basic sampai full funnel)
    ├── socmed-wisdom-second-brain.md       # Prinsip strategis inti Second Brain by Nakama Creative Lab & Insightory
    ├── second-brain-foundational.md        # ⚠️ Second Brain by Nakama Creative Lab & Insightory: mindset, sistem, problem solving
    ├── second-brain-workflow.md            # ⚠️ Second Brain by Nakama Creative Lab & Insightory: brief → riset → strategi → planning → evaluasi
    ├── second-brain-content-intelligence.md # ⚠️ Second Brain by Nakama Creative Lab & Insightory: copywriting, storytelling, visual, 13 bias
    ├── second-brain-platform-trends-kpi.md  # ⚠️ Second Brain by Nakama Creative Lab & Insightory: platform, UGC/EUGC, KPI, AI
    ├── expert-insights-content-strategy.md  # Expert insights: 49+ frameworks content & personal brand strategy
    ├── content-pattern-library.md           # ⚠️ Taxonomy 15 format konten proven + 189 hook patterns + retention mechanics + diagnosis tool
    └── strategy-case-study-baseline.md      # 2 contoh strategi lengkap (Home Living & Health/Wellness) sebagai baseline
```

## Urutan Baca

1. **SYSTEM-PROMPT.md** — di-load pertama kali. Berisi identitas Lupus, Cap 0 onboarding system, prinsip berpikir (33 prinsip), cara kerja (5 tahap termasuk onboarding), brief collection, arsenal framework, kemampuan (9 capabilities), interaksi dengan 10 AI skills lain, prinsip komunikasi, batasan, dan daftar resources.
2. **SKILL.md** — dibaca setelah system prompt. Berisi detail teknis 9 capabilities, standar output, format output default, gaya penulisan, dan batasan detail.
3. **standards/** — ⚠️ WAJIB dibaca sebelum mengerjakan capability tertentu. Berisi standar minimum per jenis strategi/analisis.
4. **frameworks/** — dibaca saat perlu kerangka analisis, pemetaan, atau evaluasi.
5. **references/** — dibaca saat perlu konteks, contoh interaksi, knowledge base, atau model integrasi.

## Prinsip

- **SYSTEM-PROMPT.md** = identitas + fondasi berpikir (SIAPA Lupus, BAGAIMANA Lupus berpikir)
- **SKILL.md** = logic + capability detail (APA yang Lupus bisa kerjakan, BAGAIMANA mengerjakannya)
- **Standards** = quality gate (standar minimum per capability yang TIDAK BOLEH dilanggar)
- **Frameworks** = model (kerangka konseptual pemetaan, analisis & evaluasi)
- **References** = konteks (Brand Profile template + contoh interaksi + knowledge base + model integrasi)

## Catatan untuk Builder

Skill ini dirancang modular dan extensible:
- **Menambah knowledge base:** Tambahkan file .md baru di `references/` dan update pointer di SYSTEM-PROMPT.md
- **Menambah framework:** Tambahkan file .md baru di `frameworks/` dan update pointer di SKILL.md
- **Menambah standar baru:** Tambahkan file .md baru di `standards/` dan update pointer di SKILL.md
- **Menambah contoh interaksi:** Update `references/interaction-examples.md`
- **Menambah model integrasi:** Update `references/integration-models.md`
- **Menambah studi kasus:** Buat file baru di `references/` atau update `references/strategy-case-study-baseline.md`

## Resource yang Bisa Ditambahkan di Masa Depan

- `references/case-pattern-library.md` — pola strategis social media dari studi kasus nyata
- `references/platform-knowledge.md` — pengetahuan per platform (algoritma, format, best practices)
- `references/industry-benchmarks.md` — benchmark metrics per industri per platform
- `references/trend-landscape.md` — tren terkini social media marketing
- `frameworks/budget-allocation-framework.md` — framework alokasi budget per channel
- `standards/standar-brief-ke-skill-lain.md` — standar format brief ke Lyra, Pavo, Sail, dll
