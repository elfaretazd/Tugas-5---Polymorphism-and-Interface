# Tugas-5---Polymorphism-and-Interface

## 📘 Ringkasan Proyek

- **Nama Proyek:** ShapeCalculator
- **Bahasa Pemrograman:** Java
- **Topik:** Polymorphism & Interface
- **Struktur Modular:** Package dan sub-package sesuai jenis class
- **Jenis Bentuk:** Circle, Square, Cube, Sphere

---

## 📆 Struktur Folder
```
praktic.geometry.bases        → abstract classes (Shape, CircularShape)
praktic.geometry.interfaces   → interfaces (TwoDimensional, ThreeDimensional, Weightable)
praktic.geometry.shapes       → bentuk geometri (Circle, Square, Cube, Sphere)
praktic.geometry.mains        → main class (ShapeCalculator)
```

---

## 🔧 Fitur Utama

- ✅ **Penggunaan semua konstruktor** (default & overload)
- ✅ **Semua method** (getArea, getVolume, printInfo, dll) dipanggil
- ✅ **Polymorphism penuh**:
  - Menggunakan deklarasi dengan superclass (`Shape`, `CircularShape`)
  - Menggunakan deklarasi interface (`ThreeDimensional`, `Weightable`)
- ✅ **Interface digunakan sesuai peruntukannya:**
  - `TwoDimensional`: Circle, Square
  - `ThreeDimensional`: Cube, Sphere
  - `Weightable`: Cube, Sphere
- ✅ **ANSI Color** di output untuk nilai penting (merah)
- ✅ **ASCII Figlet** tampil di awal program
- ✅ **Urutan input sesuai instruksi**: `7, 10, 10, 10, 21, 10, 10, 21, 10`

---

## 📤 Output Program

- Menampilkan info bentuk 2D dan 3D:
  - **Circle & Square**: Nama, Luas, Keliling
  - **Cube & Sphere**: Nama, Luas Permukaan, Volume, Berat
- Menampilkan hasil perhitungan volume dan berat dengan pewarnaan merah (ANSI color)
- Menampilkan ASCII Figlet setelah NIM
- Format output mengikuti format soal dan rapi di terminal

---

## 🥪 Cara Menjalankan

1. **Pastikan struktur folder sesuai.**
2. **Compile semua file Java:**
   ```bash
   javac praktic/geometry/**/*.java
   ```

3. **Jalankan program utama:**
   ```bash
   java praktic.geometry.mains.ShapeCalculator
   ```

4. **Gunakan terminal yang mendukung ANSI Color:**
   - Git Bash
   - VS Code Terminal
   - Windows Terminal
   - Terminal IntelliJ / Eclipse
