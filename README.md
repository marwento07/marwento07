<!-- ===================== BANNER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=280&color=gradient&customColorList=6,12,24&section=header&text=Marwento&fontSize=48&fontAlign=50&fontAlignY=45&desc=JavaScript+Developer+%7C+Scripting+%26+Interactivity&descSize=19&descAlign=50&descAlignY=65" alt="Marwento Banner" width="100%" />
</p>

<h1 align="center">Hi, I'm Marwento 👋</h1>
<p align="center">
  <b>JavaScript Developer</b> | Contributor on <i>Profile Card Interactive — Study Case Git & GitHub</i>
</p>

<p align="center">
  <a href="https://github.com/marwento07">
    <img src="https://img.shields.io/badge/GitHub-marwento07-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/mar-wento-3b9912413?utm_source=share_via&utm_content=profile&utm_medium=member_android" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Marwento-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:marwento03@gmail.com">
    <img src="https://img.shields.io/badge/Email-marwento03@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.instagram.com/marwento?stkn=MWRyYjExeWpxbjE0dQ==" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-@marwento-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

---

## 📌 Judul Proyek
### **Profile Card Interactive — Multi-Member Showcase**
Aplikasi web profil tim interaktif yang dirancang untuk menampilkan kartu identitas dinamis setiap anggota kelompok, dilengkapi fitur *profile switching*, *like counter*, dan pengubah tema *Dark/Light Mode*.

---

## 🖼️ Visualisasi (Demo & Tampilan)

```text
┌────────────────────────────────────────────────────────────┐
│ [Logo] Profile Card       [Anggota 1] [Anggota 2] [Anggota 3]  [🌙 Dark Mode]│
├────────────────────────────────────────────────────────────┤
│                                                            │
│                      ╭──────────────╮                      │
│                      │ (Foto Avatar)│                      │
│                      ╰──────────────╯                      │
│                     <h2>Nama Anggota</h2>                   │
│                     <p>Role / Posisi</p>                   │
│                     [ 👍 Like ( 12 ) ]                     │
│                                                            │
│  ┌──────────────────────┐        ┌──────────────────────┐  │
│  │ Tentang Saya         │        │ Skill                │  │
│  │ Bio deskripsi tim... │        │ [HTML] [CSS] [JS]    │  │
│  └──────────────────────┘        └──────────────────────┘  │
└────────────────────────────────────────────────────────────┘
```

> 🌐 **Live Repository:** [agusnandaseek/studycasegitready](https://github.com/agusnandaseek/studycasegitready)  
> 🔗 **Cara Menjalankan:** Buka file `index.html` langsung di browser atau gunakan VS Code Live Server.

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/DOM_Manipulation-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="DOM" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>

---

## ✨ Fitur Utama

1. **Tab Navigasi Multi-Anggota:** Menampilkan data profil masing-masing anggota secara dinamis melalui event klik tab tanpa me-refresh halaman (*Single Page Experience*).
2. **Independent Like Counter:** Fitur tombol apresiasi (*Like*) yang menghitung jumlah klik secara terpisah untuk setiap anggota (`likeCounts` array).
3. **Toggle Dark / Light Mode:** Pengalihan tema gelap dan terang secara instan dengan manipulasi class pada `document.body` serta perubahan label tombol otomatis.
4. **Dynamic Data Binding:** Seluruh konten (nama, peran, avatar, bio, dan daftar skill) di-generate secara terpusat dari objek array JavaScript.

---

## 🤝 Contribution (Peran & Kontribusi Saya)

Pada proyek tim ini, saya berperan sebagai **Scripting & Interactivity Developer**:

* 🌿 **Branch yang Dikerjakan:** `add/script.js` (Pull Request #2).
* 💻 **Implementasi Teknis:**
  - Mengembangkan seluruh kode logika pada file [`script.js`](file:///D:/CODE%20PROJECT/studycasegitready/script.js).
  - Merancang struktur data array of objects `members` yang memuat data profil lengkap tiap anggota tim.
  - Membuat fungsi utama `renderMember(memberIndex)` yang melakukan manipulasi elemen DOM (`userName`, `userRole`, `avatar`, `aboutText`, `skillList`).
  - Mengintegrasikan logika interaktif tombol *Like* dengan pelacakan indeks anggota yang sedang aktif.
  - Membangun event listener untuk toggle Dark Mode dengan mengubah teks tombol dari `🌙 Dark Mode` menjadi `☀️ Light Mode` dan sebaliknya.
* 👥 **Kolaborasi Tim:** Berkoordinasi dengan **I Putu Agus Nanda Pratama** (struktur HTML) dan **Celvin Aprilian** (styling CSS) untuk memastikan selector ID dan kelas elemen cocok saat DOM diakses.

---

## 💡 What I Learned (Pembelajaran yang Didapat)

1. **DOM Traversal & Event Handling:** Memahami cara kerja manipulasi elemen HTML secara efisien menggunakan `document.querySelector`, `querySelectorAll`, dan `addEventListener`.
2. **State Management Sederhana:** Mempelajari cara mengelola data status dinamis (`activeMember` dan `likeCounts`) di sisi client agar data tetap sinkron saat pengguna berpindah tab.
3. **Kolaborasi Git Feature-Branch:** 
   - Mempraktikkan pembuatan branch fitur khusus (`git checkout -b add/script.js`).
   - Melakukan isolasi pengerjaan skrip sehingga tidak terjadi merge conflict dengan branch styling milik rekan tim.
   - Mengajukan Pull Request (PR), menuliskan deskripsi perubahan yang jelas, dan bekerja sama dalam proses *code review*.

---

## 🚀 Feature Improvement (Rencana Peningkatan Fitur)

Kedepannya, fitur pada aplikasi ini dapat ditingkatkan lebih jauh:
- [ ] **Penyimpanan State dengan `localStorage`:** Menyimpan jumlah like dan pilihan tema terakhir agar tidak ter-reset saat halaman ditutup atau di-refresh.
- [ ] **Animasi Transisi Halaman (Transitions):** Menambahkan transisi fade-in atau slide yang halus saat pengguna berpindah antar profil anggota.
- [ ] **Sound Effect Interaktif:** Menambahkan efek suara klik lembut saat menekan tombol like atau toggle dark mode.
- [ ] **Filter / Search Skill:** Fitur pencarian anggota berdasarkan keahlian tertentu (misal: mencari anggota yang menguasai CSS atau JavaScript).

---

### 📊 Aktivitas GitHub Saya
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=marwento07&show_icons=true&theme=radical&hide_border=false" alt="Marwento GitHub Stats" />
</p>
