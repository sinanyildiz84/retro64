# Retro USB · Commodore 64 (tarayıcı)

Retro USB belleğindeki C64 oyunlarını tarayıcıda açan menü. Sayfa yalnız menüyü içerir; emülatör
[EmulatorJS](https://github.com/EmulatorJS/EmulatorJS) 4.2.3 (VICE x64sc, GPL) CDN'den yüklenir.

**Bu depoda oyun, ROM ya da kapak yok.** Oyunlar kullanıcının kendi belleğinden seçilir ve yalnız o
tarayıcının deposuna (IndexedDB) kopyalanır; hiçbir sunucuya gönderilmez.

- OYUNLAR (ya da C64) klasörünü seç: `C64/PORT1`, `C64/PORT2` klasörleri joystick portunu belirler,
  `.retro/kapak/c64` ve `C64/kapak` kapakları, `.ayar` dosyalarında `port=`, `reu=`, `not=` okunur,
  `.retro/gizli.txt` satırları gösterilmez.
- Oklar + sol Ctrl: joystick. Diğer tuşlar (F1-F8, Space, Return, harfler) C64 klavyesine gider.
- Esc'yi 1,5 sn basılı tut ya da sol üstteki "← Menü": menüye dön.
