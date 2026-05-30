# 📝 Alisizm 3D Text for FiveM

[![Tebex Store](https://img.shields.io/badge/Purchase-Tebex-orange?style=flat-square&logo=tebex)](https://alisizm.tebex.io/package/7465126)
[![Framework](https://img.shields.io/badge/Framework-QBCore%20%7C%20QBX%20%7C%20ESX-blue?style=flat-square)](#)
[![YouTube Channel](https://img.shields.io/badge/YouTube-Subscribe-red?style=flat-square&logo=youtube)](https://www.youtube.com/@Alisizmsc)

In-game 3D interaction labels and Text UI for your FiveM server, easily managed with a simple admin panel.

---

## 🔗 Links
*   **🛒 Purchase:** [Tebex Store](https://alisizm.tebex.io/package/7465126)
*   **📺 YouTube Channel:** [Alisizm Development](https://www.youtube.com/@Alisizmsc)
*   **🛍️ My Store:** [View all scripts](https://alisizm.tebex.io/package/)

---

## 🇬🇧 English Description

Alisizm 3D Text allows you to add interactive 3D buttons and screen Text UI anywhere on the map using the `/atext` command. No server restart is needed: all saves and changes apply instantly for all players in real-time.

### ✨ Features
*   **Admin Menu:** Compact blue admin panel on the right side of the screen via the `/atext` command.
*   **Two Display Types:** 
    *   `Button`: 3D world prompt with an interaction key.
    *   `Text UI`: Side HUD prompt on the screen.
*   **Themes:** Includes Yellow and Dark Green theme options.
*   **Job Filter:** Restrict visibility to "Everyone" or specifically to any job listed in your framework's job lists.
*   **Positioning:** Set positions via manual coordinates or use the quick "Get Location" feature.
*   **Saved Points Management:** View a list of saved points to click for details, teleport to them, or delete them instantly.
*   **File-Based Admin:** Secure access using your Rockstar license in `data/admins.json` (does not require full server 'god' mode).
*   **Persistent Storage:** Data is saved in `data/saved_texts.json` (fully editable and not escrow-encrypted).
*   **Framework Support:** Auto-detects and supports **QBCore, QBX, and ESX**.
*   **Optimized Performance:** Low resmon footprint with lightweight loops; syncs occur only on save or player join.
*   **Security:** Resource name protection (must run exactly as `alisizm-3dtext`).
*   **Escrow-Ready:** JSON config and data files remain fully open for server owners to edit.

### 📋 Requirements
*   A working FiveM server.
*   `qb-core`, `qbx_core`, or `es_extended` (for job functionalities and notifications).

### 🚀 Installation
1.  Place the resource folder in your server and ensure the name is strictly `alisizm-3dtext`.
2.  Add your Rockstar license to the `data/admins.json` file. *(You can find your license in-game using `/atextlicense`)*.
3.  Add `ensure alisizm-3dtext` to your `server.cfg`.
4.  Restart your server.

**Author:** alisizm · **Version:** 1.0.0

---
---

## 🇹🇷 Türkçe Açıklama

Alisizm 3D Text, FiveM sunucunuz için oyun içinden kolayca yönetilen 3D etkileşim yazıları ve Text UI sistemidir. Haritada istediğiniz noktaya `/atext` komutuyla 3D buton veya Text UI ekleyebilirsiniz. Kayıt anında tüm oyunculara anında yansır; sunucuya restart atmanıza gerek kalmaz.

### ✨ Özellikler
*   **Yönetim Menüsü:** `/atext` komutuyla açılan, ekranın sağında kompakt mavi admin paneli.
*   **İki Farklı Tip:** 
    *   `Buton`: 3D dünya üzerinde tuş destekli yazı.
    *   `Text UI`: Ekranın sağında beliren HUD yazısı.
*   **Temalar:** Sarı ve Koyu Yeşil tema seçenekleri.
*   **Meslek Filtresi:** Yazıları "Herkes"e veya QBCore/ESX mesleklerinize (jobs) özel ayarlayabilirsiniz.
*   **Konumlandırma:** Elle koordinat girebilir veya tek tıkla "Konum Al" özelliğini kullanabilirsiniz.
*   **Kayıtlı Noktalar Listesi:** Eklenen noktalara tıklayıp detaylarını görebilir, o noktaya ışınlanabilir (TP) veya silebilirsiniz.
*   **Dosya Tabanlı Yetki:** `data/admins.json` dosyasına lisans (license) ekleyerek yetkilendirme (Sunucu 'god' yetkisi gerektirmez).
*   **Kalıcı Kayıt:** Veriler `data/saved_texts.json` dosyasında tutulur (düzenlenebilir, şifrelenmez).
*   **Framework Desteği:** **QBCore, QBX ve ESX** sistemlerini otomatik olarak algılar.
*   **Yüksek Performans:** Düşük resmon, hafif döngüler; veriler sadece kayıt anında veya sunucuya girişte senkronize edilir.
*   **İsim Koruması:** Eklenti klasör adı kesinlikle `alisizm-3dtext` olmalıdır.
*   **Escrow Uyumlu:** JSON config ve veri dosyaları sunucu sahibine tamamen açık kalır.

### 📋 Gereksinimler
*   FiveM sunucusu.
*   `qb-core`, `qbx_core` veya `es_extended` (meslek kontrolleri ve bildirimler için).

### 🚀 Kurulum
1.  Eklenti klasörünü sunucunuza atın (Klasör adı `alisizm-3dtext` olmak zorundadır).
2.  `data/admins.json` dosyasına kendi lisansınızı ekleyin *(Oyun içinde lisansınızı `/atextlicense` yazarak öğrenebilirsiniz)*.
3.  `server.cfg` dosyanıza `ensure alisizm-3dtext` satırını ekleyin.
4.  Sunucunuzu yeniden başlatın.

**Geliştirici:** alisizm · **Sürüm:** 1.0.0

---

## ⚖️ License Information / Lisans Bilgilendirmesi

### English
**This software is NOT Open Source.** 
"Alisizm 3D Text" is a commercial product licensed and distributed exclusively via the official Tebex store. This resource is protected by the FiveM Asset Escrow system.

*   **Usage:** By purchasing this resource from the official Tebex store, you are granted a non-exclusive license to use it on your own FiveM server.
*   **Customization:** You are **ALLOWED** to modify the unencrypted files (`data/admins.json`, `data/saved_texts.json`).
*   **Redistribution:** You may **NOT** redistribute, share, publish, resell, or leak any part of this software.
*   **Enforcement:** Unauthorized distribution or tampering with the escrow system or hidden markers will result in an official DMCA takedown notice submitted to **Cfx.re (FiveM)** and **Tebex**, leading to account bans and server blacklisting.

### Türkçe
**Bu yazılım Açık Kaynak (Open Source) DEĞİLDİR.**
"Alisizm 3D Text", ticari bir üründür ve yalnızca resmi Tebex mağazası üzerinden lisanslanarak dağıtılmaktadır. Bu eklenti, FiveM Asset Escrow sistemi ile korunmaktadır.

*   **Kullanım:** Bu ürünü resmi Tebex mağazasından satın alarak, yalnızca kendi FiveM sunucunuzda kullanmak üzere münhasır olmayan bir kullanım hakkı elde edersiniz.
*   **Özelleştirme:** Şifrelenmemiş veri dosyalarını (`data/admins.json`, `data/saved_texts.json`) düzenlemenize **İZİN VERİLİR**.
*   **Dağıtım:** Bu yazılımın herhangi bir parçasını dağıtmak, paylaşmak, yayınlamak, satmak veya sızdırmak **YASAKTIR**.
*   **Yaptırım:** Escrow sistemini kırmaya çalışmak, izinsiz dağıtım veya sızıntı durumunda doğrudan **Cfx.re (FiveM)** ve **Tebex** platformlarına resmi telif ihtarı (DMCA) gönderilecek olup; hesaplarınız kapatılacak ve sunucunuz kara listeye alınacaktır.
