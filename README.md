# NeedNamaTim - Case 2 BDC TelU

Repositori ini berisi notebook analisis, keluaran olahan data, dan salindia hasil analisis untuk Case 2 seleksi BDC TelU.

## Gambaran Proyek

Analisis dalam repositori ini meneliti percakapan publik tentang MBG di X/Twitter. Fokus utamanya adalah topik yang paling dominan, aktor yang paling berpengaruh dalam membentuk percakapan, tingkat polarisasi antar komunitas, serta indikasi awal amplifikasi yang terkoordinasi.

Hasil akhirnya disusun dalam bentuk notebook, tabel ringkasan, visualisasi, dan file presentasi agar alur analisis bisa ditelusuri dari data mentah sampai kesimpulan akhir.

## Struktur Repositori

```text
NeedNamaTim-Case_2-BDC-TelU/
├── NeedNamaTim.pdf
├── case_2_dataset.xlsx
├── mbgg2.ipynb
├── notebookd8fc6279cf.ipynb
├── Petunjuk Teknis Case 2 BDC (Internal - 2026).pdf
└── notebook1/
    ├── case_2_analysis.ipynb
    └── outputs/
        ├── slide_contents.json
        ├── slide_contents_advanced.json
        ├── presentation.html
        ├── daily_trends.csv
        ├── top_hashtags.csv
        ├── top_influencers.csv
        ├── top_users.csv
        ├── bertopic_topic_info.csv
        ├── lda_topics.json
        ├── semantic_topics.csv
        ├── centrality_ranking.csv
        ├── communities.csv
        ├── interaction_graph.gexf
        ├── community_sentiment.csv
        ├── polarization_report.json
        └── possible_amplification_accounts.csv
```

## File Utama

- `NeedNamaTim.pdf` - salindia hasil analisis
- `notebook1/case_2_analysis.ipynb` - notebook analisis utama
- `mbgg2.ipynb` - notebook pendukung untuk analisis amplifikasi terkoordinasi dan anomali perilaku
- `notebookd8fc6279cf.ipynb` - notebook pendukung untuk audit data, engagement, dan framing jaringan
- `notebook1/outputs/` - tabel, grafik, dan artefak hasil proses analisis