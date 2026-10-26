# UTS-GRAF-SAINS-DATA-2026
UTS Graf Sains Data 2026: rekomendasi item-based KNN dengan Neo4j pada dataset RetailRocket. Training (P1) 3-17 Mei 2015, testing (P2) 1-15 Juni 2015. Evaluasi Hit@5 dan NDCG@5.

Repository ini berisi pengerjaan UTS Graf Sains Data (Python Driver Neo4j dan Rekomendasi), Gasal 2026/2027.

**Nama:** Aulia Aziza
**NIM:** 24031554102

## Deskripsi

Proyek ini membangun sistem rekomendasi item-based KNN menggunakan Neo4j dan Python pada dataset RetailRocket (Roman Zykov), yang berisi event view, addtocart, dan transaction. Data diolah menjadi graf User-Item, diproyeksikan menjadi graf Item-Item, lalu similarity antar item dihitung dengan cosine similarity untuk menghasilkan rekomendasi. Hasilnya dievaluasi dengan Hit@5 dan NDCG@5.

## Periode Data

- **P1 (training):** 3-17 Mei 2015
- **P2 (testing):** 1-15 Juni 2015

## File

- `102_Aulia Aziza_uts graf.ipynb`: notebook pengerjaan beserta penjelasannya
- `data_p1_events.csv`: data hasil filter P1
- `data_p2_events.csv`: data hasil filter P2
