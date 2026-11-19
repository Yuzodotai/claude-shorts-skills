# claude-shorts-skills

Claude ile "2D karakterler, renkli 3D dünya" tarzında animasyonlu shorts yapmak için skill'ler.

## İçerik

| Skill | Ne yapar | Nerede |
|---|---|---|
| **shorts-script-first** | Videodan önce seslendirme metnini yazar: absürt ama gerçek bir konu bulur, bilgiyi kaynaklardan kontrol eder, üstüne özgün dramatize bir hikâye kurar. Hangi kısmın gerçek, hangi kısmın kurgu olduğunu ayrıca yazar. Metin onaylanmadan tek kare üretilmez. | Bu repoda: [`shorts-script-first/`](shorts-script-first/) |
| **cartoon-3d-short** | Onaylanan metinden videoyu üretir: three.js + Remotion ile 3D dünya, karakterler, kamera, ses efektleri ve müzik. | Mr Omi'nin ücretsiz reposu: [github.com/mromidev/claude-animated-shorts](https://github.com/mromidev/claude-animated-shorts) |

`cartoon-3d-short` skill'ini ben yapmadım; yapımcısı **Mr Omi**, MIT lisansıyla ücretsiz paylaşıyor. Tüm emek ve kredi ona ait. Bu repodaki metin skill'i onun skill'iyle birlikte çalışmak için yazıldı.

## Kurulum

1. Bu repoyu indir (Code → Download ZIP) ve `shorts-script-first` klasörünü `~/.claude/skills/` içine kopyala.
2. `cartoon-3d-short` için Mr Omi'nin reposundaki kurulum adımlarını izle.
3. Claude Code'da yaz: `/cartoon-3d-short yeni bir video yap`
4. Claude konu ve metin önerir. Metni onayla, gerisini Claude halleder.

## Notlar

- Varsayılan dil Türkçedir; başka bir dil istersen Claude'a söylemen yeterli.
- Claude Code için en az Pro plan gerekir. Opus ile sonuçlar belirgin şekilde daha iyi.
