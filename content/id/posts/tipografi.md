---
title: "Pratinjau Tipografi"
image: https://placehold.co/1080x520
description: "Panduan untuk melihat semua elemen tipografi dalam tema My Notes."
date: 2025-04-02T01:19:10+07:00
lastModified: 2025-04-02T01:19:10+07:00
tags:
  - tipografi
  - pertinjau
  - konten
  - markdown
categories:
  - Blog
series:
  - Example
pinned: true
mathjax: true
draft: false
---

Konten ini memperlihatkan pratinjau elemen tipografi yang didukung oleh tema **My Notes**.  
**Selamat Membaca!**

## Judul (Heading)
Berikut adalah contoh berbagai **judul (Heading)**:

# Judul 1  
## Judul 2  
### Judul 3  
#### Judul 4  
##### Judul 5  
###### Judul 6  

## Daftar (List)
### Daftar tak berurutan
- Daftar 1  
- Daftar 2  
  - Daftar 1 di dalam Daftar 2  
  - Daftar 2 di dalam Daftar 2  
- Daftar 3  

### Daftar Berurutan  
1. Daftar Berurutan 1  
2. Daftar Berurutan 2  
   1. Daftar Berurutan 1 di dalam Daftar Berurutan 2  
   2. Daftar Berurutan 2 di dalam Daftar Berurutan 2  
3. Daftar Berurutan 3  

### Daftar Definisi
Istilah Pertama  
: Ini adalah definisi istilah pertama.  

Istilah Kedua  
: Ini adalah definisi dari istilah kedua.  
: Ini adalah definisi lain dari istilah kedua.  

## Daftar yang harus dilakukan
- [ ] Belum dilakukan  
- [x] Sudah dilakukan  

## Tabel

| Nama  | Umur | Hobi      | Profesi |  
| ----- | ---- | --------- | ------- |  
| Ana   | 27   | Memasak   | Dokter  |  
| Budi  | 30   | Memancing | Guru    |  
| Arif  | 35   | Bersepeda | Pilot   |  
| Agung | 21   | Membaca   | Pelajar |  

## Gambar  
### Bawaan markdown  

![Ini adalah gambar](https://picsum.photos/150/100)  

### Dengan Shortcodes Hugo  

#### Gambar rata kiri  
Anim nostrud cupidatat aliquip nulla fugiat fugiat ullamco exercitation dolore proident culpa laborum adipisicing anim. Officia nisi laborum laborum non reprehenderit consectetur qui culpa consequat. In amet nulla dolore nostrud proident duis laboris et officia sit. Tempor dolore voluptate in mollit deserunt non incididunt ex nostrud non officia nisi ut dolore.

{{< image src="https://picsum.photos/150/100?1" alt="Gambar di kiri." align="left" >}}  
Gambar di kiri  
{{< /image >}}

Reprehenderit enim nisi magna cillum aute eiusmod aute laboris ut. Aliqua voluptate exercitation ea sint deserunt magna et. Aliqua quis esse id consequat consequat irure quis eu occaecat exercitation officia nisi do est. Sint minim duis minim adipisicing consequat duis.

#### Gambar rata kanan  
Consequat anim aliquip veniam consequat officia aliqua. Ullamco tempor deserunt cillum irure. Et est ut laborum ad laboris consectetur laborum consectetur esse minim ad. Est ut cillum fugiat occaecat adipisicing ipsum irure Lorem elit reprehenderit sit anim anim incididunt. Magna sunt velit in laboris ad proident aliqua magna fugiat irure aliqua consectetur. Esse anim sit ad pariatur commodo occaecat est quis.

{{< image src="https://picsum.photos/150/100?2" alt="Gambar di kanan." align="right" >}}  
Gambar di kanan.  
{{< /image >}}

Duis eiusmod amet est aliquip cillum labore consectetur deserunt. Labore aliqua cillum mollit cupidatat ullamco. Mollit dolore aliqua nostrud occaecat labore cillum et labore. Sint velit culpa et fugiat incididunt excepteur reprehenderit Lorem duis voluptate voluptate occaecat. Est quis labore irure in adipisicing nisi. Sunt et dolor in Lorem irure laborum deserunt. Incididunt aute id ad Lorem nostrud culpa elit ipsum id.

#### Gambar rata tengah  
Laborum ex duis voluptate tempor consequat veniam velit sunt elit. Elit et ipsum ullamco amet aliquip ea ullamco incididunt consequat do aliquip cillum. Anim ullamco non excepteur ullamco consectetur.

{{< image src="https://picsum.photos/200/100" alt="Gambar di tengah " align="center" >}}  
Gambar di tengah  
{{< /image >}}

Reprehenderit veniam enim adipisicing duis anim aliquip sint laboris esse sint. Officia adipisicing esse aliquip cupidatat. Commodo nostrud laboris dolore ut incididunt fugiat est nostrud duis et non ullamco velit. Veniam duis nisi irure occaecat veniam adipisicing dolor commodo. Cupidatat culpa id nisi do dolore pariatur.

#### Gambar lebar Penuh  
Do dolore ad amet occaecat pariatur minim. Incididunt minim veniam commodo et sunt tempor nisi. Velit laboris aliquip aute consequat fugiat reprehenderit incididunt duis nostrud aute occaecat exercitation cillum.

{{< image src="https://picsum.photos/300/100?3" alt="Gambar Lebar Penuh" align="full" >}}  
Gambar Lebar Penuh  
{{< /image >}}

Eu sit aute amet aute sit incididunt ex. Veniam do dolore officia amet exercitation sint laborum aliqua aliquip sint. Aliqua adipisicing aliqua consequat consequat. Minim sunt consequat consectetur excepteur adipisicing deserunt minim. Officia occaecat aute enim pariatur reprehenderit aliquip. Dolor nostrud dolor dolor irure nostrud.

## Tautan  

[Menuju Google](https://www.google.com)  

## Kutipan dan Peringatan (Alert)  

### Kutipan Bawaan  

> Ini adalah kutipan bawaan.  

### Kutipan dengan Peringatan (Alert)  
> [!INFO] Informasi  
> Ini dengan peringatan (alert) Informasi.  

> [!TIP] Kiat-kiat  
> Ini dengan peringatan (alert) kiat (tip).  

> [!WARNING] Peringatan  
> Ini dengan peringatan (warning).  

> [!DANGER] Bahaya  
> Ini dengan peringatan (alert) Bahaya.  

> [!ERROR] Kesalahan  
> Ini dengan peringatan (alert) Kesalahan.

Lihat lengkap Kunjungi: [Kumpulan Peringatan](kumpulan-peringatan.md)  

## Kode  

### Python  

```python  
print("Hello World")
```

### Javascript

```Javascript
console.log("Hello World")
```

## Matematika

$$
\int_{0}^{\infty} \frac{x^2 e^{-x^2}}{1 + e^{x}} \, dx = \frac{\sqrt{\pi}}{2} \left( \text{Li}_2 \left( -e^{-1} \right) - \text{Li}_2 \left( -e^{-2} \right) \right)  
$$  

## Diagram  

### Mermaid  

```mermaid  
graph LR  
    A[Mulai] --> B{Keputusan}  
    B -->|Ya| C[Proses A]  
    B -->|Tidak| D[Proses B]  
    C --> E[Selesai]  
    D --> E  
```  

### GoAT ASCII  

```goat  
______     _____    _____   _______   _____   _______  
 /      \   /     \  /     \ /       \ /     \ /       \  
|        | |       ||       ||         ||     ||         |  
|  (o)(o)  |   \_/  ||   o   ||    |    || o   ||   |     |  
 \        /  \_____/  \_____/  \_______/ \_____/ \_______/  
  \______/
```  

## YouTube

{{< youtube id="dQw4w9WgXcQ">}}  

## HTML di Markdown  

<p style="color: red; font-weight: 700;">Tulisan Merah Dengan Ketebalan 700</p>