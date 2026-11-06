# Kidung Jemaat in SVG

A digital, print-ready collection of Kidung Jemaat hymns in SVG. Each hymn is provided as a self-contained file that can be opened offline.

Two editions are included:

- **Book edition** — numbered notation in a layout intended to follow the printed book.
- **Staff edition** — an additional version in staff notation.

## Preview

| Book edition | Staff notation |
| --- | --- |
| <img src="book/kj-005.svg" alt="Kidung Jemaat 005, book edition" width="320"> | <img src="staff/kj-005.svg" alt="Kidung Jemaat 005, staff notation" width="320"> |
| <img src="book/kj-046.svg" alt="Kidung Jemaat 046, book edition" width="320"> | <img src="staff/kj-046.svg" alt="Kidung Jemaat 046, staff notation" width="320"> |
| <img src="book/kj-088.svg" alt="Kidung Jemaat 088, book edition" width="320"> | <img src="staff/kj-088.svg" alt="Kidung Jemaat 088, staff notation" width="320"> |
| <img src="book/kj-101.svg" alt="Kidung Jemaat 101, book edition" width="320"> | <img src="staff/kj-101.svg" alt="Kidung Jemaat 101, staff notation" width="320"> |

## Repository contents

- `book/` — SVG files for the book edition with numbered notation.
- `staff/` — SVG files for the additional staff-notation edition.
- [`hymns.json`](hymns.json) — metadata catalog for the hymns.

Open an SVG file in a web browser or vector graphics editor. The SVG files are designed to work offline.

## Hymn catalog

`hymns.json` contains an array of hymn records. Entries can include the hymn title and number, categories, original title(s), music credits, and total number of verses. Some records also include fields such as copyright information, other hymn-book numbers, or a variant label.

A hymn may appear in multiple categories, and not every record has all fields. Category entries can include a category, subcategory, and—in some cases—a verse number. The `music` field may contain inline HTML markup.

The JSON file provides catalog metadata; the rendered notation is in the `book/` and `staff/` directories.

## Related project

This repository showcases the SVG output and its interpretation of the printed hymnal. For additional features, layout work, and quality-of-life improvements, see [numbered-notation-xml](https://github.com/jodi-ivan/numbered-notation-xml).

---

# Kidung Jemaat dalam SVG

Kumpulan nyanyian Kidung Jemaat digital dalam format SVG yang siap cetak. Setiap nyanyian tersedia sebagai file mandiri yang dapat dibuka tanpa koneksi internet.

Tersedia dua versi:

- **Versi buku** — notasi angka dengan tata letak yang ditujukan untuk mengikuti buku cetak.
- **Versi not balok** — versi tambahan dengan notasi balok.

## Isi repositori

- `book/` — file SVG versi buku dengan notasi angka.
- `staff/` — file SVG versi tambahan dengan notasi balok.
- [`hymns.json`](hymns.json) — katalog metadata nyanyian.

File SVG dapat dibuka menggunakan peramban web atau aplikasi grafis vektor, termasuk saat offline.

## Katalog nyanyian

File `hymns.json` berisi kumpulan data nyanyian. Setiap entri dapat memuat judul dan nomor nyanyian, kategori, judul asli, keterangan musik, serta jumlah bait. Beberapa entri juga memiliki informasi tambahan seperti hak cipta, nomor dari buku nyanyian lain, atau penanda varian.

Satu nyanyian dapat memiliki beberapa kategori, dan kolom yang tersedia dapat berbeda antarentri. Entri kategori dapat memuat kategori, subkategori, dan—dalam beberapa kasus—nomor bait. Nilai pada kolom `music` mungkin berisi markup HTML.

File JSON ini berisi metadata katalog; notasi yang ditampilkan tersedia di direktori `book/` dan `staff/`.

## Proyek terkait

Repositori ini menampilkan hasil SVG dan interpretasi tata letak buku nyanyian. Untuk fitur tambahan, pengembangan tata letak, dan peningkatan kenyamanan penggunaan, lihat [numbered-notation-xml](https://github.com/jodi-ivan/numbered-notation-xml).
