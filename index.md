---
layout: default
title: CantikJuara
description: Review jujur produk kecantikan dan fashion di Shopee Indonesia. Skincare, parfum, tas, sepatu — based on real use, bukan template AI.
permalink: /
---

# CantikJuara

Hub review kecantikan & fashion. Review jujur dari user beneran, bukan listing seller.

## Review Terbaru

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url | relative_url }})** — {{ post.description | truncate: 100 }}
{% endfor %}

## Kategori

- 💄 [Skincare](#) — basic dan advanced
- 🌸 [Parfum](#) — wanita dan pria
- 👗 [Fashion Wanita](#) — tas, sepatu, hijab
- 👨 [Fashion Pria](#) — kemeja, jeans, sepatu
- ⌚ [Aksesoris](#) — jam tangan, dompet

## Tentang Cantikjuara

Site review kecantikan dan fashion oleh tim community Yogyakarta. Fokus pada produk yang awet dan tidak menipu.

[Baca selengkapnya tentang penulis →](/tentang/)

---

**Disclosure:** Beberapa link di situs ini adalah affiliate Shopee. Klik membantu support situs ini, tanpa biaya tambahan dari sisi Anda. [Detail disclosure →](/disclosure/)
