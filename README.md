# Tugas-5---Polymorphism-and-Interface

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
