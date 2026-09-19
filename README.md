# kayit-link

Profil paylaşma bağlantıları için statik site (`https://link.matestudios.online/u/kullanici_adi`).
Yalnızca `@kullanici_adi` gösterir, profil verisi içermez. Apple evrensel bağlantı kimliği `.well-known/apple-app-site-association` içindedir (uygulama kimliği kesinleşince doldurulacak).

## Yasal sayfalar
`/gizlilik/`, `/kvkk/`, `/kosullar/` uygulamadaki metinlerden üretilir (kaynak: HobbyShelf projesinde `src/legal/content.ts`, betik: `scripts/build-legal-pages.mjs`). Elle düzenlenmemeli; uygulamadaki metin değişince yeniden üretilip buraya kopyalanır.
