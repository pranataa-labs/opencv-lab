# AGENTS.md — Universal AI Coding Assistant Directives
# Reference: https://github.com/pranataa-labs/workflow-master

**Project:** OpenCV Lab  
**Stack:** Python 3.10+, OpenCV (`cv2`), NumPy, Matplotlib, Jupyter Notebook, Google Colab  
**Operating Workflow:** Terintegrasi penuh dengan [Workflow Master](https://github.com/pranataa-labs/workflow-master).

---

## 1. Operating Discipline & 9-Stage Engineering Workflow
Semua pekerjaan computer vision dan coding pada repositori ini WAJIB mematuhi 9 tahapan alur kerja di Workflow Master:
1. **Triage:** Pahami tujuan pemrosesan citra/video (filtering, deteksi kontur, transformasi geometri, deteksi objek).
2. **Discover:** Periksa format input gambar/video, channel warna (BGR vs RGB), resolusi, dan tipe data matriks (`uint8` vs `float32`).
3. **Design:** Tentukan alur algoritma pipeline (preprocessing, thresholding, morphological ops, feature extraction).
4. **Plan:** Tentukan file notebook atau modul script yang dikembangkan.
5. **Implement:** Tulis kode pemrosesan citra yang teroptimasi, modular, dan terhindar dari kebocoran memori pada loop video streaming.
6. **Verify:** Validasi visualisasi hasil, release window (`cv2.destroyAllWindows()`), dan release video capture (`cap.release()`).
7. **Review:** Evaluasi ketepatan deteksi dan latensi per frame (FPS).
8. **Release:** Simpan parameter threshold terbaik ke dalam file konfigurasi/script.
9. **Report:** Laporkan visualisasi komparasi (Before vs After) dan akurasi deteksi secara transparan.

---

## 2. Core Rules & Project Specific Directives
- **Rule 17 — Machine Learning & Computer Vision:** Konversi BGR ke RGB sebelum render dengan Matplotlib, pastikan selalu memanggil `cap.release()` dan `cv2.destroyAllWindows()` untuk mencegah kebocoran resource memori kamera/video, dan gunakan visualisasi komparasi side-by-side.
- **Rule 18 — AI Operational Discipline & Anti-Amnesia:**
  - *Contextual Synthesis over Blind Mimicry:* Sesuaikan contoh notebook dengan arsitektur OpenCV 4.x+.
  - *Feature-First Documentation:* Utamakan modul pemrosesan citra, kontur, thresholding adaptif, dan haar cascades.
- **Rule 11.1 — Mandatory README Topics & GitHub Metadata Sync:** Pada SETIAP pembuatan atau pembaruan `README.md`, sertakan baris tautan topik GitHub tepat di bawah judul/subjudul dan selaraskan dengan `gh repo edit <owner>/<repo> --add-topic <tags>`.
- **Rule 04 — Testing & QA:** Terapkan pola AAA (Arrange-Act-Assert) untuk pengujian fungsi transformasi citra.
- **Rule 12 — Git & AI Hygiene:** Buat commit atomik dengan standar Conventional Commits (`feat:`, `fix:`, `refactor:`, `test:`, `docs:`).
- **Rule 12.1 — Dual-Account Co-Authorship & Pairing (Otomatis Tanpa Perintah):** Pada SETIAP commit Git di seluruh repositori ekosistem, AI WAJIB menyertakan trailer co-author akun kedua secara otomatis dan mandiri, TANPA perlu diminta atau diperintahkan lagi oleh pengguna:
  ```text
  Co-authored-by: aria sastra <192975116+ariasastra-dev@users.noreply.github.com>
  ```
  Aturan ini bersifat permanen dan non-negotiable untuk menjaga sinkronisasi kontribusi dan membuka/meningkatkan tier badge GitHub (**Pair Extraordinaire**, **Pull Shark**, dan **YOLO** via alur Branch & PR). DILARANG membuat commit tanpa trailer ini. Selain itu, pada setiap inisialisasi/publikasi repositori baru, AI WAJIB otomatis mengundang akun `ariasastra-dev` sebagai collaborator dengan push permission.
