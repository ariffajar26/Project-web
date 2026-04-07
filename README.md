# Tugas HTML — Form & Tabel Data Siswa

Tugas Pemrograman Web Dasar · SMK Negeri 7 Pekanbaru · Kelas X PPLG

---

## Tentang Project

Project ini berisi dua file HTML untuk input data siswa:

- `form_siswa.html` — Form untuk mengisi data diri siswa
- `Tugas.html` — Tabel untuk menginput data siswa secara terstruktur

Dibuat menggunakan HTML murni, tanpa CSS atau JavaScript.

---

## Struktur File

```
tugas-html/
├── form_siswa.html
├── Tugas.html
└── README.md
```

---

## Penjelasan File

### `form_siswa.html`

| Field   | Tipe Input    | Keterangan             |
|---------|--------------|------------------------|
| Nama    | Text Input   | Nama lengkap siswa     |
| Kelas   | Dropdown     | X / XI / XII           |
| Jurusan | Dropdown     | PPLG, Akuntansi, Animasi, TO, TE |
| TTL     | Text Input   | Tempat & Tanggal Lahir |
| JK      | Radio Button | Lanang / Betina        |
| —       | Submit       | Tombol Simpan          |

### `Tugas.html`

| Kolom   | Tipe Input | Keterangan   |
|---------|-----------|--------------|
| Nama    | Text Input | Nama siswa  |
| Kelas   | Dropdown   | X / XI / XII |
| JK      | Dropdown   | Lanang / Betina |
| Hobi    | Text Input | Hobi siswa  |
| Umur    | Text Input | Umur siswa  |
| Jurusan | Dropdown   | PPLG, Akuntansi, Animasi, TO, TE |

---

## Konsep HTML yang Digunakan

```html
<!-- Input teks -->
<input type="text" name="nama">

<!-- Dropdown -->
<select name="kelas">
  <option value="X">X</option>
  <option value="XI">XI</option>
  <option value="XII">XII</option>
</select>

<!-- Radio button -->
<input type="radio" name="JK" value="lanang"> Lanang
<input type="radio" name="JK" value="betina"> Betina

<!-- Tabel -->
<table border="1">
  <tr>
    <td colspan="3"><center>Tabel Siswa</center></td>
  </tr>
</table>

<!-- Submit -->
<input type="submit" value="Simpan">
```

---

## Cara Menjalankan

```bash
git clone https://github.com/rikuhasrad12/tugas-html.git
cd tugas-html
```

Buka file `.html` langsung di browser. Tidak perlu server atau install apapun.

---

## Materi yang Dipelajari

- Struktur dasar HTML
- Elemen form: `<input>`, `<select>`, `<option>`
- Radio button
- Tabel: `<table>`, `<tr>`, `<td>`, `colspan`
- Atribut `name`, `value`, `size`, `border`
- Tombol submit
