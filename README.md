# Arapça Eğitim Sosyal Medya İçerik Asistanı

Arapça eğitim hesapları için asistan: zihin haritası, sticky notes, sadeleştirme, karusel, gönderi metni ve içerik takvimi.

Bu depo bir **Claude skill'i** içerir. Aynı talimat Gemini ve ChatGPT'de de kullanılabilir (aşağıya bak).

## Depo içeriği

- `arapca-sosyal-medya-icerik/SKILL.md`: Claude skill dosyası (başlık bilgisiyle birlikte)
- `prompt-metni.md`: Aynı talimat, başlık bilgisi olmadan. Gemini ve ChatGPT'ye yapıştırmak için.

## Claude

**Claude Code (terminal):** `arapca-sosyal-medya-icerik` klasörünü `~/.claude/skills/` içine kopyala. Sonraki oturumda otomatik tanınır.

**Claude uygulaması / claude.ai:** `arapca-sosyal-medya-icerik` klasörünü zip yapıp Ayarlar → Yetenekler (Skills) bölümünden yükle. Arayüzdeki menü adları zamanla değişebilir.

**skills CLI:** `npx skills add tumerkancimen/arapca-sosyal-medya-icerik`

## Gemini

- **Gemini uygulaması (Gem):** Yeni bir Gem oluştur, talimat (instructions) alanına `prompt-metni.md` içeriğini yapıştır, Gem'e adını ver. Her seferinde bu Gem'le sohbet başlat.
- **Gemini CLI:** Skill formatını destekliyor. `gemini skills install` ile depo adresini vererek kurulabilir. Komutu kurmadan önce Gemini CLI belgelerinden kontrol et.

## ChatGPT (GPT)

- **Özel GPT:** "GPT oluştur" bölümünde talimat alanına `prompt-metni.md` içeriğini yapıştır. Ad ve kısa açıklama ekle.
- **Proje:** Bir proje aç, proje talimatlarına `prompt-metni.md` içeriğini yapıştır. Aynı projedeki sohbetler bu talimatla çalışır.
- Hızlı kullanım: Sohbete `prompt-metni.md` içeriğini yapıştırıp ardından isteğini yaz.

Not: Özel GPT ve Gem oluşturma bazı hesap türlerinde ücretli plan gerektirebilir; güncel koşulları ilgili sitelerden kontrol et.

## Kullanım

Konunu söyle. Asistan önce eksik bilgileri sorar, sonra çıktıyı üretir.

## Uyarı

Yapay zekâ hata yapabilir. Skill uydurma kaynak, atıf veya bilgi üretmemeye çalışır ama önemli bilgileri (kelime anlamı, sınav kuralı, kaynak, atıf, dergi bilgisi) resmî kaynaklardan doğrula.
