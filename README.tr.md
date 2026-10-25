<div align="center">

# MES Yönetim Platformu

### Operasyonel workflow, yönetim, takip ve iş raporlaması

<img src="./assets/hero.svg" alt="Animasyonlu proje başlığı" />

<p><a href="./README.md">English</a> · <a href="./README.de.md">Deutsch</a> · <a href="./README.tr.md"><strong>Türkçe</strong></a></p>

<p>
  <a href="https://github.com/tahakubilay"><img src="https://img.shields.io/badge/Taha%20Kubilay-GitHub-181717?style=for-the-badge&logo=github" alt="Taha Kubilay GitHub" /></a>
  <a href="https://github.com/tahakubilay/mes-management-platform"><img src="https://img.shields.io/badge/Repository-MES%20Platform-0A66C2?style=for-the-badge&logo=github" alt="Repository" /></a>
</p>

</div>

---

## Genel Bakış

MES Yönetim Platformu; iş workflow'larını, yönetim süreçlerini, takibi ve raporlamayı tek bir operasyon ortamında birleştiren bir yönetim sistemidir.

Platform, bir iş sürecinin yaşam döngüsü boyunca operasyonel durumun görünür ve yönetilebilir kalmasını hedefler.

## Temel Model

```mermaid
flowchart LR
    U[Kullanıcılar / Operasyon] --> UI[Yönetim Arayüzü]
    UI --> APP[Uygulama Katmanı]
    APP --> WF[Workflow & İş Kuralları]
    APP --> REP[Raporlama & Analiz]
    WF --> DATA[(Operasyonel Veri)]
    REP --> DATA
    DATA --> HISTORY[Geçmiş & Takip]
```

## Temel Yetenekler

| Alan | Amaç |
|---|---|
| **Merkezi Operasyonlar** | Operasyonel veri ve workflow'ları tek ortamda toplamak |
| **Workflow Yönetimi** | Tekrarlanabilir süreçleri ve durum geçişlerini yapılandırmak |
| **Takip** | Operasyonel hareketleri görünür ve izlenebilir tutmak |
| **Yönetim** | Yönetim ve idari süreçleri desteklemek |
| **Raporlama** | Operasyonel kayıtları yönetim görünürlüğüne dönüştürmek |
| **İş Kuralları** | Domain mantığını tutarlı biçimde sisteme taşımak |
| **Geçmiş Bağlamı** | Analiz ve inceleme için bağlamı korumak |

## Mühendislik Odağı

Ana mühendislik problemi, sistem büyürken farklı workflow'lar boyunca tutarlılığı korumaktır.

Başlıca konular:

- Domain ve workflow modelleme
- İş kurallarının uygulanması
- Operasyonel state yönetimi
- Veri tutarlılığı
- Raporlama mimarisi
- Sürdürülebilir modül sınırları
- Yönetim UX'i
- Geçmiş takibi

## Veri & Gizlilik

Public repository production kimlik bilgileri, özel şirket kayıtları, iç API secret'ları veya gizli ortama özel konfigürasyon içermez.

---

<div align="center">

### Geliştiren: [Taha Kubilay](https://github.com/tahakubilay)

`Enterprise Software` · `Workflow Design` · `Business Logic` · `Reporting` · `Full-Stack Engineering`

</div>