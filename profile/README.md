# Tim Riset AI

<div align="center">

<img src="https://raw.githubusercontent.com/tim-riset-ai/.github/main/assets/logo.png" alt="Tim Riset AI Official Logo" width="360" />

<br/>

### Applied Artificial Intelligence & Computer Vision Research Group
*Advancing Optical Document Forensics, Superimposed Text Localization, and Neural Pattern Analysis*

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=flat-square&logo=opencv&logoColor=white)](https://opencv.org/)
[![Open Science](https://img.shields.io/badge/Open%20Science-Reproducible%20Research-008080?style=flat-square)](https://github.com/tim-riset-ai)
[![License](https://img.shields.io/badge/License-Apache%202.0%20%2F%20MIT-green?style=flat-square)](LICENSE)

</div>

---

## 📌 About the Research Group

**Tim Riset AI** adalah kelompok riset kolaboratif yang berfokus pada pengembangan kecerdasan buatan, visi komputer terapan (*applied computer vision*), dan analisis integritas dokumen digital. Riset kami menitikberatkan pada perancangan arsitektur *deep learning* yang dapat direproduksi (*reproducible*), transparan, dan terukur secara empiris.

Fokus riset utama laboratorium saat ini diarahkan pada pemecahan tantangan **deteksi dan lokalisasi manipulasi dokumen optik**, khususnya fenomena penimpaan teks (*overwritten / superimposed text alteration*) pada dokumen resmi dan instrumen legal.

---

## 🔬 Core Research Pillars

```
                     ┌────────────────────────────────────────┐
                     │          TIM RISET AI GROUP            │
                     └───────────────────┬────────────────────┘
                                         │
        ┌────────────────────────────────┼────────────────────────────────┐
        ▼                                ▼                                ▼
┌───────────────────────┐    ┌───────────────────────┐    ┌───────────────────────┐
│  DOCUMENT FORENSICS   │    │  DEEP VISION PATTERNS │    │  DATASETS & BENCHMARK │
│  & TAMPER DETECTION   │    │   & FEATURE LEARNING  │    │      EVALUATION       │
├───────────────────────┤    ├───────────────────────┤    ├───────────────────────┤
│ • Overwrite Detection │    │ • Multi-scale Pyramids│    │ • Standardized Splits │
│ • Superimposed Text   │    │ • Frequency Domain    │    │ • Pixel-level IoU     │
│ • Stroke Discontinuity│    │   Artifacts (FFT/DCT) │    │ • Boundary Precision  │
│ • Forensic Pixel Mask │    │ • Attention Mechanisms│    │ • Cross-domain Tests  │
└───────────────────────┘    └───────────────────────┘    └───────────────────────┘
```

### 1. Document Forensics & Overwritten Text Detection
- **Superimposed & Overwrite Text Localization**: Mendeteksi dan mengisolasi goresan teks tambahan yang ditimpakan di atas teks atau latar belakang dokumen asli (*tampered character strokes*).
- **Stroke Discontinuity & Ink Inconsistency Analysis**: Menganalisis ketidaksesuaian gradien tepi, kepadatan piksel, dan karakteristik morfologi goresan tinta untuk membedakan lapisan teks asli versus modifikasi.
- **Micro-Artifact & Frequency Analysis**: Memanfaatkan dekomposisi frekuensi (FFT/DCT) dan representasi spasial resolusi tinggi guna mengekspos anomali kompresi dan manipulasi pada tingkat sub-piksel.

### 2. Neural Computer Vision & Feature Learning
- **Multi-Scale Feature Aggregation**: Mengembangkan *encoder-decoder* dan *feature pyramid networks* yang sensitif terhadap fitur semantik mikro (teks kecil) dan struktur makro dokumen.
- **Dual-Branch Spatial-Frequency Networks**: Mengintegrasikan analisis domain spasial dengan domain frekuensi untuk menangkap distorsi manipulasi yang tidak kasat mata.
- **Attention & Boundary Refinement**: Mempertegas batas segmentasi piksel manipulasi menggunakan mekanisme *spatial-channel attention* yang terkalibrasi.

### 3. Empirical Benchmarks & Scientific Rigor
- **Standardized Benchmark Datasets**: Membangun protokol evaluasi berbasis ground truth piksel (*pixel-level segmentation masks*) dan bounding-box deteksi tingkat karakter/kata.
- **Rigorous Metrics Reporting**: Evaluasi menyeluruh menggunakan Precision, Recall, $F_1$-Score, mean Intersection-over-Union (mIoU), dan AUC-PR untuk memastikan ketahanan model terhadap variasi noise dan degradasi scan.

---

## 📐 Scientific Standards & Reproducibility

Setiap repositori dan proyek eksperimen di lingkungan **Tim Riset AI** mengikuti standar penelitian yang ketat:

1. **Deterministic Reproducibility**: Menyediakan fixed random seed, lingkungan dependensi terisolasi, dan script pelatihan yang terverifikasi end-to-end.
2. **Standardized Evaluation Metrics**:
   - **Detection & Localization**: Precision, Recall, $F_1$-score, IoU (Intersection over Union), dan Boundary F-score.
   - **Pixel Classification**: False Positive Rate (FPR), True Positive Rate (TPR), dan Area Under Precision-Recall Curve (AUC-PR).
3. **Data Integrity**: Menjamin keabsahan ground-truth anotasi melalui proses verifikasi silang antar-peneliti dalam kelompok.

---

## 📑 Citation & Academic Attribution

Apabila Anda menggunakan arsitektur, dataset, atau modul penelitian yang dikembangkan oleh **Tim Riset AI**, silakan gunakan format sitasi berikut:

```bibtex
@misc{timrisetai2026,
  author       = {Tim Riset AI Group},
  title        = {Applied Computer Vision & Document Forensics Research Group},
  year         = {2026},
  publisher    = {GitHub},
  journal      = {GitHub Organization Profile},
  howpublished = {\url{https://github.com/tim-riset-ai}}
}
```

---

<div align="center">
  <sub>Tim Riset AI • Collaborative Research Group • Est. 2026</sub>
</div>
