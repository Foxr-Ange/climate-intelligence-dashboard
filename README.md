# 🌍 Climate Intelligence Dashboard

A lightweight, responsive **Climate Intelligence Dashboard** built using **pure HTML5 and CSS3** (strictly no JavaScript and no external frameworks). This project was developed as a Capstone Project using **IBM Bob** by applying the **3-Layer Prompt Architecture** and **Targeted Refinement** methodology.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

## 📋 Project Overview

Data terkait perubahan iklim, emisi karbon, energi terbarukan, dan peringatan bencana sering kali tersebar di berbagai sumber dengan tampilan yang rumit. *Dashboard* ini hadir untuk menyajikan visualisasi metrik iklim secara terpusat, bersih, dan sangat ringan tanpa bergantung pada *library* berat.

### ✨ 9 Core Components
1. **Sidebar Navigation** – Navigasi utama untuk berpindah antar bagian *dashboard*.
2. **Top Navigation Bar** – Baris atas untuk pencarian, notifikasi, dan informasi cepat.
3. **4 KPI Cards** – Menampilkan metrik utama secara ringkas:
   - Temperature Anomaly: `+1.2°C`
   - CO₂ Level: `421 ppm`
   - Renewable Energy: `34.7%`
   - Risk Index: `6.8/10`
4. **Climate Trend** – Visualisasi tren iklim berbasis CSS murni.
5. **Region Overview** – Ringkasan kondisi iklim berdasarkan wilayah.
6. **Disaster Alerts** – Panel peringatan dini bencana beserta tingkat risikonya.
7. **Sustainability Progress Tracker** – Pelacak progres target keberlanjutan (*progress bar*).
8. **Climate News Cards** – Kumpulan kartu berita iklim terkini.
9. **Admin Profile** – Bagian profil pengelola *dashboard*.

---

## 🎨 Design System & Tech Stack

- **Tech Stack:** HTML5 (Semantic HTML) & CSS3 (CSS Custom Properties / `:root` variables).
- **Color Palette:**
  - Primary: `#0A7C6E` (Teal)
  - Accent: `#F59E0B` (Amber)
- **UI Style:** Modern card-based layout, subtle shadows, dan `border-radius: 12px`.

---

## 🧠 Prompt Architecture (IBM Bob)

Pengembangan kode dilakukan menggunakan pendekatan **3-Layer Prompting**:
1. **Layer 1 (Role & Context):** Menetapkan peran sebagai *Senior Frontend Engineer* dengan batasan ketat HTML5 + CSS3 murni (2 file terpisah).
2. **Layer 2 (Task & Requirements):** Merinci seluruh 9 komponen wajib *dashboard* secara eksplisit.
3. **Layer 3 (Constraints & Output):** Menentukan palet warna, gaya kartu, standar *clean code*, dan komentar di setiap bagian.

Penyempurnaan dilakukan dengan metode **Targeted Refinement** (1 masalah pada output = revisi 1 layer saja tanpa menulis ulang seluruh *prompt*).

---

## 📁 Project Structure

```text
climate-intelligence
