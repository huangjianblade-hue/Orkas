# Orkaslar

**Masaüstünüzde AI ajanlarından oluşan açık kaynaklı bir ekip ✓ hedeflerinizi bitmiş işlere dönüştürür ve hareket etmesini sağlar.**

Orkas, açık kaynaklı (MIT) bir yerel ilk çok ajan masaüstü uygulamasıdır.**Commander** Ne ihtiyacınız var: kendi başına birçok görev bitirir ve daha büyük işler için adımları planlar ve zaten kullandığınız kodlama ve kişisel ajanlarla birlikte uzman ajanları getirir**Claude Code, Codex, OpenCode, OpenClaw ve Hermes-Agent** - Birlikte çalışmak.

Orkas tek bir soruyu yanıtlamakla yetinmez; projelerin ilerlemesini sağlamak için tasarlanmıştır. **Projeler** hedefleri, kuralları, belleği ve dosyaları bir arada tutar; yeni bir görüşmede kaldığınız yerden devam edebilirsiniz. **Yapılacak işler** kişilere ve ajanlara atanabilir. **Auto-advance** açıkken ekip sıradaki işi kendisi üstlenir. **Zamanlanmış otomasyonlar** rutin işleri saatlik, günlük, haftalık veya aylık olarak tekrarlar. Tüm verileriniz bilgisayarınızda kalır ve tamamlanan işler incelemeniz için size iletilir. Böylece işletmenizde süreklilik gerektiren işleri Orkas’a güvenle emanet edebilirsiniz.

**[ — Orkas'ı macOS ve Windows için indir](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** — ücretsiz, içinde yerleştirilmiş Orkas modeli için 500 kredi ile, böylece başlamak için bir API keyna ihtiyacınız yok. Kendi anahtarlarınızı tercih eder misiniz? Claude · OpenAI · Gemini · DeepSeek · Kimi · GLM · Qwen · MiniMax · Doubao, veya yerel OpenAI uyumlu bir uç noktası.

[![Download for macOS & Windows](https://img.shields.io/badge/Download-macOS%20%26%20Windows-5b57d6?style=for-the-badge)](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Orkas-AI/Orkas?style=flat&logo=github&label=Stars&color=yellow)](https://github.com/Orkas-AI/Orkas/stargazers)
[![Release](https://img.shields.io/github/v/release/Orkas-AI/Orkas?color=blue)](https://github.com/Orkas-AI/Orkas/releases)
[![X: @leochenpm](https://img.shields.io/badge/X-%40leochenpm-black?logo=x)](https://x.com/leochenpm)
[![Website: orkas.ai](https://img.shields.io/badge/Website-orkas.ai-5b57d6)](https://orkas.ai/?source=gh-orkas)

[English](./README.en.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [Español](./README.es.md) · [Bahasa Indonesia](./README.id.md) · [Español (Latinoamérica)](./README.es-419.md) · [Русский](./README.ru.md) · [Português (Brasil)](./README.pt-BR.md) · [Türkçe](./README.tr.md) · [繁體中文](./README.zh-TW.md) · [Tiếng Việt](./README.vi.md) · [Deutsch](./README.de.md) · [ไทย](./README.th.md) · [Français](./README.fr.md) · [Italiano](./README.it.md) · [Português (Portugal)](./README.pt-PT.md) · [العربية](./README.ar.md)

---

https://github.com/user-attachments/assets/4f8b16c8-a192-45a4-b19f-80e8d02c3dab

![Orkas masaüstü — görev konuşması ve teslimatları](./resources/app-ui/task-en.png)

---

## Takımın sağladığı

- **Videolar, sesli yayınlar ve görüntüler** — VideoStudio, VoiceStudio, ImageStudio
- **Araştırma raporları, SEO denetimleri ve pazar analizi** — DeepResearcher, SeoGeoAgent, StockAnalyzer
- **Gösteriler, makaleler, haberletirler ve slaytlar** — ContentWriter, PptMaker
- **Web siteleri, kullanıcı kullanımı ve kod** — UID tasarımcı, ProductDeveloper
- **Word, Excel, PowerPoint ve PDF dosyaları** — OfficeWorker
- **E-ticaret işi** — 5 e-ticaret ajanından ürün araştırması, listeleme, inceleme analizi, satış analizi ve katalog değişiklikleri
- **Çok sayıda ajanı gerektiren karmaşık bir iş** — Komutan bölüşür, her bir parçayı doğru ajanı verir ve sonuçları birleştirir; örneğin, bir rapor, bir slayt güvertesi ve bir başlatma videosu haline gelen pazar araştırması

Uygulama, her birinin kendi becerileri, belleği ve araçları olan 16 uzman yapay zekâ ajanıyla gelir. [Ajan kitaplığında](https://orkas.ai/views/marketplace/gs/agents/?source=gh-orkas) 30'dan fazla ajan arasından seçim yapabilir veya ihtiyacınız olan rolü tarif ederek Commander’dan özel bir ajan oluşturmasını isteyebilirsiniz.

<details>
<summary><b>Tüm 16 içe gömülü ajan</b></summary>

| Bölge | Ajan . | Neyi sağlıyor |
| --- | --- | --- |
| Araştırma ve analiz | **DeepResearcher** | Kanıtlara dayalı araştırmalar, doğrulanmış kaynaklar, işaretli çelişkiler ve denetlenebilir bir rapor ile |
| | **SeoGeoAgent** | Verilen URL üzerinden teknik SEO, içerik kalitesi, Core Web Vitals ve içeriğin yapay zekâ yanıtlarında alıntılanabilirliğini (GEO) inceler; önceliklendirilmiş bir düzeltme listesi sunar |
| | **StockAnalyser** | Ekiplik araştırması, faktör ekranları, arka testler ve portföy risk kontrolleri, izlenebilir araç tablosu ile |
| İçerik & medya | **ContentWriter** | Bir hedef, kaynak veya kaba bir taslaktan yayınlanabilir yayınlar, makaleler, haberletirler ve vaka çalışmaları |
| | **PptMaker** | Bir konudan, çizelgesinden veya belgedeki düzenlenebilir ve gözden geçirilebilir PPTX güverteleri |
| | **ImageStudio** | Posterler, kapaklar, sosyal görüntüler ve infografikler |
| | **VideoStudio** | Hikaye, Yapay zeka sunucuları, başlıklar ve dublajlama, videoları vurgulamak, yerleştirmek ve kendi içerik ve görüntüleri ile referans video rekreasyonu |
| | **VoiceStudio** | Hikaye, çok sesli ses, transkript ve altyazılar, ses düzenleme ve karıştırma |
| | **UIDesigner** | Düzenlenebilir, ürün hedeflerinden, PRD'lerden, ekran görüntüleri veya Figma malzemesinden HTML-birinci UI |
| Yapım ve ofis | **ProductDeveloper** | Repo-aware mühendisliği      PRD uygulamak, hataları düzeltmek, refactor, inceleme, doğrulanabilir sonuçlar ile |
| | **OfficeWorker** | Word / Excel / PowerPoint / PDF dosyalarını birer birer veya seri olarak oluşturun, düzenleyin, kontrol edin ve teslim edin |
| E-ticaret | **ECommerceResearcher** | Ürün seçimleri bütçe, piyasa ve kaynak sınırları    adaylar, reddedilme nedenleri, onaylama planları |
| | **ECommerceWriter** | Üstünlükler, detay sayfaları, Sık Sorular, resim kopyası ve video senaryoları marka sesinizle |
| | **ECommerceReviewer** | Yorum ve itibar analizi — Müşteri teması, kötü incelemelerin temel nedenleri, öncelikler |
| | **ECommerceAnalyzer** | Dışarıdan yapılan satışlar, kar, reklamlar, geri ödeme ve envanter — uyumlu ölçümler ve kararlar |
| | **ECommerceOperator** | Katalog, fiyat, promosyon ve envanter değişikliklerini planlar; yalnızca bağlantı kurduğunuz araçlar aracılığıyla yürütür |

Her ajan hakkında daha fazla bilgi[orkas.ai/ajanlar](https://orkas.ai/agents/?source=gh-orkas)

</details>

### Kendi içeriklerinizle referans videoları yeniden oluşturun

**VideoStudio** Bir viral videonun anlatım yapısını, görsel stilini ve düzenleme hızını kendi ürününüzü, senaryounuzu ve görüntüleri kullanarak yeniden yaratabilirsiniz. Referans bir video dosyası ve varlıklarınızı sağlayın: ajan kaçağı, bilgi sırasını, görsel atışları ve eylem çağrısını analiz eder, sonra üretmeden önce neyi koruyacağını ve neyi değiştirmeyeceğini önerir.

Bu, hareket grafik açıklayıcıları, SaaS veya uygulama gösterileri ve mevcut görüntülerden oluşturulan ürün reklamları için en iyi şekilde çalışır. Yerel olarak yazar metin, başlıklar, anlatım ve klipler ayrı olarak gözden geçirilebilir; AI'den oluşan görüntülere pişirilmiş metin o görüntüyi değiştirmeyi gerektirir.

> "30 saniyelik dikey promosyon için referans.mp4'i kullanın. Hakkını, tipografi ve ritmini koruyun, içeriği ürünümle ve ekran kayıtlarımla değiştirin ve önce bana ayrıntıları gösterin ve planlayın".

Ajanın okuyabileceği bir video dosyası gerekir. Sosyal medya paylaşım bağlantılarından video indirme özelliği henüz yoktur. Kamera hareketlerinin ya da oyuncu performansının aynen tekrarlanması veya kare kare eşleşme garanti edilmez. Ayrıntılar için [referans videoyu yeniden oluşturma iş akışına](./resources/builtin/marketplace/agents/79df9cc89f5f/skills/video-craft/references/reference-recreation.md) bakın.

---

## İşleri devam ettirin.

Bir görev iyi bir başlangıç. Orkas devam eden iş için inşa edilmiştir.

- **Projeler** — hedefler ve kurallar, hafıza ve dosyalar projede her konuşmanın başlaması, böylece asla sıfırdan kısaca anlatmazsınız.
- **Yapılacaklar ve Auto-advance** — Her projede insanlar ve ajanlar için yapılacak şeyler listesi vardır. Auto-advance ile, ekip bir sonraki öğeyi kendi başına alır ve incelemeniz için bitmiş işi geri getirir.
- **Zamanlanmış otomasyonlar** — Görevleri saatlik, günlük, haftalık veya aylık çalıştırabilirsiniz. Orkas bilgisayarınızda çalışır. 1.9 sürümünden itibaren, bilgisayar uyku modundan çıktığında veya uygulama başlatıldığında her otomasyon önceki 12 saatte kaçırdığı çalıştırmalardan yalnızca en sonuncusunu gerçekleştirir.
- **Bağlayıcılar** — Gmail, Google Calendar, Sheets, Drive, Notion, Slack, Shopify, Stripe ve diğer hizmetlere bağlanır. Orkas varsayılan olarak bir şey göndermeden, paylaşmadan veya silmeden önce onayınızı ister.
- **Uygulamalar** — bir aracı tanımlar ve Orkas onu masaüstü uygulaması içinde yerel bir uygulama olarak oluşturur. Paketlenmiş uygulamada, ücretli planlar da kamu bağlantısı olan bir web uygulaması olarak yayınlayabilir.
- **Paylaşılan projeler** (kurulum sürümü) — İş arkadaşlarınızı veya sanal asistanları davet edin; her işi bir kişiye ya da ajana atayın.

> [!NOTE]
> Paylaşılan projeler, bulut eşitleme ve web uygulaması yayımlama yalnızca kurulum sürümünde sunulur; açık kaynak sürümünde henüz desteklenmez. Bu özellikleri kullanmak için **[macOS ve Windows için Orkas’ı indirin](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** (ücretsiz, 500 kredi dahil).

---

## Claude Code, Codex, OpenCode, OpenClaw ve Hermes-Agent'i birlikte çalıştırın.

Orkas, zaten yerel oturumlar olarak kurduğunuz CLI ajanlarını kendi uzmanlarının yanında ✓ kodlama ajanları**Claude Kod, Kod ve OpenCode**, ve kişisel ajanlar** OpenClaw ve Hermes-Agent**Komutan her birine en iyi bölümünü verir ve hepsinde bir plan tutar, böylece tek bir sohbet hataları düzeltebilir, değişiklikleri gözden geçirebilir ve yayın notunu hazırlayabilir.

[Claude Kodesi ve Codex'i birlikte kullanmak →](https://orkas.ai/blog/claude-code-codex-together/?source=gh-orkas)

---

## Orkas Neden?

- **Plan yapan, delegasyon yapan ve geri kalanı yapan bir komutan.** — hedefleri parçalayarak, doğru ajanları, becerileri, bağlantılarını ve araçları seçer ve hiçbir uzman daha uygun olmadığında analiz, yazma, araştırma ve dosya çalışmasını kendisi halleder.
- **Öncelik yerel depolamada** — Sohbetler, dosyalar, bilgi tabanları ve özel ajanlar varsayılan olarak bilgisayarınızda saklanır. Kurulum sürümünde bulut eşitlemeyi etkinleştirebilirsiniz. Kendi anahtarınızı kullandığınızda model istekleri bilgisayarınızdan doğrudan sağlayıcıya gider; yerleşik Orkas modeli, Orkas’ın yönettiği hizmeti kullanır.
- **Modeli istediğiniz zaman değiştirebilirsiniz** — Commander ve yerleşik ajanlar aynı model ayarını kullanır: yerleşik Orkas modeli, kendi sağlayıcınız veya yerel bir uç nokta. Haricî CLI ajanları kendi model ayarlarını kullanmaya devam eder.
- **Daha iyi olan ajanlar** — her ajan özel becerileri ve hafızasını korur. Arka plan incelemeleri, uygulama boş kaldığında yeni etkinlikleri inceliyor ve kendi kendini değerlendirmeyi, tekrar kullanılabilir yöntemleri ve öğrenilen becerileri iyileştirebilir.
- **Açık kaynak, kara kutu yok** — Orkas'ın ve her ajanın ve yetkinliğin ne yaptığını oku.

> ⭐ Eğer Orkas size yararlıysa, bir yıldız daha fazla insanın projeyi bulmasına yardımcı olur.

---

## İndir

| | Paketlenmiş uygulama (önerlenir) | Kaynaktan çalıştır |
| --- | --- | --- |
| Platformlar | macOS 12+ (Apple Silicon & Intel), Windows 10+ | macOS, Windows, glibc 2.34+ Linux x64/arm64 |
| Hesap | Oturum açınca 500 kredi | Hesap gerekmez |
| Modeller | İçinde yerleştirilmiş Orkas modeli veya kendi anahtarlarınız | Kendi anahtarların ya da yerel bir son noktasın |
| Ayrıca içerir | Proje işbirliği, uygulama yayınlama, bulut senkronizasyonu ve daha fazlası | — |
| Al bakalım. | **[Orkas indir](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** | [Hızlı başlatma](#hızlı-başlatma) |

İndirme bağlantısı sisteminizi tespit eder ve doğru yükleme cihazını başlatır.

---

## İnsanlar ne için kullanıyor?

- **Pazarlama içeriği** — Sesinizle videolar, ürün sayfaları, yayınlar ve haberletirler başlatın.[İçerik yazısı](https://orkas.ai/use/content-writing/?source=gh-orkas) · [Videolar](https://orkas.ai/use/make-videos/?source=gh-orkas)
- **Depo operasyonları** — Haftalık satış raporları, inceleme cevapları, listeler ve rekabetçilerden yapılan kontroller.[E-ticaret](https://orkas.ai/use/ecommerce/?source=gh-orkas)
- **Araştırma ve raporlar** — talep üzerine veya her hafta kaynaklanan raporlar ve güverteler.[Araştırma](https://orkas.ai/use/researchers/?source=gh-orkas) · [Veriler analiz](https://orkas.ai/use/data-analysis/?source=gh-orkas)
- **Belgeleriyle sohbet et .** — cevaplar kendi dosyalarınızda yerleştirilmiştir, kaynak bölümlerine alıntılar ile.[Belgelerle sohbet edin](https://orkas.ai/use/chat-with-documents/?source=gh-orkas)
- **Müşteri işi** — toplantı raporları, aylık müşteri raporları ve şablonunuzdaki güncelleme paketleri.[Aylık müşteri rapor şablonu](https://orkas.ai/blog/monthly-client-report-template/?source=gh-orkas)
- **Ürün başlatılması** — iniş sayfaları, testlerle hata düzeltmeleri, değişim logları ve başlatma yayınları.[Geliştiriciler](https://orkas.ai/use/developers/?source=gh-orkas)
- **Bir uygulama oluştur** — quote hesap makineleri, rezervasyon formları, iç araçlar.[Uygulama oluştur](https://orkas.ai/use/build-apps/?source=gh-orkas)
- **Küçük takımlar** — insanlar ve ajanlar için bir proje.[Küçük takımlar](https://orkas.ai/use/small-teams/?source=gh-orkas)

---

## Orkas'ın karşılaştırma şekli

| Araç | Ne olduğunu | Orkas'ın Farklılığı |
| --- | --- | --- |
| **Claude Code** | Antropic'in ajantik kodlama aracı — terminalde, IDE, masaüstü ve web'de, Claude modellerine dayanıyor. | Orkas, Claude Code'u ajanlarından biri olarak yönetir. Orkas, kodun — araştırma, içerik, video ve daha fazlası — ile birlikte projeler, görevler ve otomasyonlar ile hareket etmesini sağlayan çalışmalar için bir model-agnostik ekibi ekler.[Orkas vs Claude Code](https://orkas.ai/compare/orkas-vs-claude-code/?source=gh-orkas) |
| **Codex** | OpenAI'nin kodlama ajanı terminalde, editörünüzde ve bulutta. | Ya da ya da değil: Orkas, Codex'u Claude Code ve OpenCode'nin yanında ajanlarından biri olarak çalıştırır. Komutan kodlamayı Codex'a ve incelemeyi başka bir ajanı teslim edebilir, ardından bir yayın — belgeleri, başlatma gönderileri ve videolarının kodsuz yarısını kapsayabilir.[Orkas vs Codex →](https://orkas.ai/compare/orkas-vs-codex/?source=gh-orkas) |
| **Claude Cowork** | Günlük iş için Anthropic'in ajanı, şimdi ücretli Claude planıyla masaüstü, web ve mobilde Claude — 'un bir parçasıdır. Öntanımlı olarak Anthropic bulutunda çalışır ve Claude modellerini kullanır. | Orkas, bilgisayarınızı uyanık tutmak için kullanıyor ve verilerinizi öntanımlı olarak yerel olarak, içinde yerleşik olan Orkas modeli, kendi sağlayıcı anahtarlarınız veya yerel bir uç noktasıyla koruyor. Komutan ayrıca Claude Code, Codex ve diğer CLI ajanlarını da getirebilir.[Claude Cowork alternatifleri](https://orkas.ai/compare/claude-cowork-alternatives/?source=gh-orkas) |
| **Manus** | Manus'un bulutunda görevleri varsayılan olarak planlayan ve çalıştıran bir AI ajansı. Manus Studio masaüstü uygulaması (macOS ve Windows) ayrıca bulutta hala planlanan görevlerle seçtiğiniz bir klasörde çalışabilir. | Açık kaynaklı bir alternatif (MIT) olan Manus. Orkas, ajanlarını bilgisayarınızda çalışır ve verilerinizi öntanımlı olarak yerel olarak, içinde yerleşik olan Orkas modeli, kendi sağlayıcı anahtarlarınız veya yerel bir son noktayı ile tutar. Projeler, görevler ve otomasyonlar işi hareket ettirir.[Açık kaynaklı Manus alternatif](https://orkas.ai/open-source-manus-alternative/?source=gh-orkas) |
| **LangChain** | Bir geliştiriciler çerçevesini / LLM uygulamaları ve ajanları oluşturmak için bir kitaplık  kod ilk, kendi Python / JS uygulamasına gömülü. | Orkas, konuşma aracılığıyla yönlendirdiğiniz bir masaüstü uygulamasıdır, orkestra kodunu yazmakla değil. Veriler varsayılan olarak yerel kalır. |
| **CrewAI** | Rol oynayan özerk ajanları orkestralamak için Python çerçevesini | Orkas, bir masaüstü uygulamasına çoklu ajan orkestrasyonunu getirir. Proje, görevler, otomasyonlar ve her ajanın kendi kendini geliştirmesi ile birlikte. |
| **OpenClaw** | Mesajlama entegrasyonları, çoklu ajan yönlendirme ve alt-senatlı bir kişisel ajan platformu. | Orkas, hazır teslimatlar için bir masaüstü çalışma alanı sağlar. Bu alanlarda Claude Code, Codex, OpenCode ve diğer CLI ajanları arasında içerikli uzmanlar ve koordinasyon bulunur. |
| **Hermes-Agent** | Nous Research'ın kendi kendini geliştirme ajanı   bir akıl ve becerisi olan bir ajan, CLI, mesajlaşma geçitleri ve masaüstü uygulaması olarak kullanılabilir. | Orkas bir ekibi koordine eder: Komutan birçok uzman ve diğer CLI ajanlarını yönlendirir ve Hermes-Agent onlardan biri olarak yer alır. |

**Orkas senin için .** Bir asistan yerine bir ajan ekibi, günlerce hareket eden bir iş ve verilerinizi, anahtarlarınızı ve ajanlarınızı kendi diskinizde.

**Senin için değil .** Sadece tek bir her amaçlı chatbot veya kendi uygulamanıza yerleştirmek için saf bir kod kütüphanesi istiyorsunuz.

**Kodlama ajanları arasında seçim mi?** [Codex vs OpenCode](https://orkas.ai/compare/codex-vs-opencode/?source=gh-orkas) · [Claude Code vs. Codex vs. OpenCode](https://orkas.ai/compare/claude-code-vs-codex-vs-opencode/?source=gh-orkas) · [Claude Code alternatifleri](https://orkas.ai/compare/claude-code-alternatives/?source=gh-orkas)

**Tam bir yan yana karşılaştırmalar →** [vs Claude Code](https://orkas.ai/compare/orkas-vs-claude-code?source=gh-orkas) · [Codex vs.](https://orkas.ai/compare/orkas-vs-codex?source=gh-orkas) · [vs. Cline](https://orkas.ai/compare/orkas-vs-cline?source=gh-orkas) · [LangChain ile karşılaştırıldığında](https://orkas.ai/compare/orkas-vs-langchain?source=gh-orkas) · [vs ChatGPT](https://orkas.ai/compare/orkas-vs-chatgpt?source=gh-orkas) · [OpenClaw ile](https://orkas.ai/compare/orkas-vs-openclaw?source=gh-orkas) · [vs Hermes-Agent](https://orkas.ai/compare/orkas-vs-hermes-agent?source=gh-orkas)

---

## Hızlı başlatma

Kurulum paketini mi tercih edersiniz? Yukarıdaki [İndir](#i̇ndir) bölümüne bakın. Aşağıda kaynak koddan çalıştırma adımları yer alır; Orkas’ı Linux’ta kullanmanın şimdilik tek yolu budur:

**Gereksinimler**: Node 22.12+ · macOS / Windows 10+ / glibc 2.34+ Linux x64 veya arm64. Python 3 ve bir C / C ++ oluşturma araç zinciri olağandışı yerel modül kaynak oluşturma geri dönüş için kullanılabilir.

```bash
git clone https://github.com/Orkas-AI/Orkas.git
cd Orkas
./run.sh           # macOS / Linux
run.cmd            # Windows
```

Linux'ta kaynak koddan çalıştırmak için glibc 2.34 veya üstü gerekir. Alpine ve diğer musl tabanlı dağıtımlar desteklenmez. Kaynak koddan ilk başlatmada, yerel konuşma dökümü için hedef mimariye uygun whisper.cpp çalışma ortamı ve çok dilli model indirilip doğrulanır.

İlk başlatmada `run.sh` / `run.cmd`, kilit dosyasında sabitlenen npm bağımlılıklarını yükler; Python, uv, Node, gömme modeli (yaklaşık 95 MB), OfficeCLI, FFmpeg, whisper.cpp ve çok dilli konuşma modelinin belirli sürümlerini hazırlar. Linux’ta uygulama açılmadan önce platforma özgü yerel modüller ile Whisper çalışma ortamının Electron ABI uyumluluğu doğrulanır. OCR ve Skill’e özel Python paketleri, ilgili özellik ilk kullanıldığında yalıtılmış bir yerel ortama kurulur. İlk başlatmada `~/.orkas/` (macOS / Linux) veya `<smallest non-system drive>:\.orkas\` (Windows) altında bir çalışma alanı oluşturulur. Ardından API anahtarını veya OAuth’u yapılandırmak için **Ayarlar → Yapay zekâ sağlayıcıları** bölümüne gidin.

Yerel bağımlılık hatalarında Node.js 24 LTS (en az 22.12.0) kullanın ve bu kaynak kod dizininde
`npm run native:repair` komutunu çalıştırın. Komut isteğe bağlı bağımlılıkları geri yükler,
Electron için SQLite derlemesini onarır, SQL'i ve sqlite-vec'i doğrular. Ayrıca
paketle gelen Node çalışma zamanını hazırlar ve başarı bildirmeden önce sharp'ı ayrı bir süreçte doğrular.
Kullanım`npm run native:check`Tesis edilmemiş bir kontrol için.
Bakın[Doğal bağımlılık doğrulama senedisi](./scripts/verify-native-dependencies.cjs)gerçekleştirilen kontroller için.

---

## Nasıl işliyor?

### Görev yönlendirme

Komutan genel işleri kendisi halleder ve uzmanlık işini üç araçla delegelerler:

- **`dispatch_to`** adı belirtilen ajanı çağırır. Commander sonucu aldıktan sonra çalışmaya devam eder. Sonucu bekleyebilir veya görevi eşzamansız çalıştırıp tamamlandığında bildirim alabilir.
- **`hand_off_to`** kalan işi adı belirtilen ajana devreder ve Commander’ın mevcut yanıt turunu bitirir. Ajan doğrudan yanıt verir. İsteğe bağlı bir takip adımı tanımlanırsa Commander daha kapsamlı göreve daha sonra devam edebilir.
- **`run_worker`** — Bu, anonim ve izole edilmiş bir alt görev çalıştırır ve özel bir sonuç gönderir.

Adlı ajan görevleri ve anonim çalışanlar ayrı bir eşzamanlılık kontrolüne sahiptir.[gönderme uygulanması](./src/main/features/group_chat/bus.ts)ve[Yaptırma kilitleri](./src/main/util/locks.ts).

### Çevre yönetimi

Çalışma zamanı bütçelerinin bağlamı seçilen modelin kullanılabilir giriş kapasitesine, isteklere, araçlara ve sürekli çalıştırma süresine karşı. Tamamlanmış diyalog sınırlı bir yakın tarih penceresini kullanır; uzun aktif görevler daha önceki süreç mesajlarını yoğunlaştırmak için kontrol noktalarını kullanırken son çalışmaları korur. Dosya okumaları, dosya değişiklikleri ve komut işlevleri de bağlam sıkıştırılmasını sağlayabilecek yapılandırılmış kayıtlara sahiptir.

Gördün mü ?[bağlamlı bütçeler](./src/core-agent/src/agent/context-budget.ts), [Oturum tarihi ve kontrol noktaları](./src/core-agent/src/agent/session.ts)ve[Çalışma alanı kayıtları](./src/core-agent/src/agent/workspace-state.ts).

### Hatıra ve Kütüphane

Kalıcı notlar, kullanıcı tercihlerini, proje gerçeklerini ve her ajansın tekrar kullanılabilir bilgilerini ayrı alanlarda tutar.

Kitaplık, belgeleri paragraflara ayırarak yerel bir SQLite vektör dizini oluşturur. Gömme modeli bilgisayarınızda çalışır. Ajanlar `library` aracıyla genel kitaplıkta veya mevcut projenin kitaplığında dosyaları listeleyebilir, ilgili bölümleri arayabilir ve kaynak içeriğini okuyabilir. Önceki görüşmeler `chat_history` ile ayrı olarak aranır.

Gördün mü ?[kapsamlı hafıza](./src/main/features/memory.ts), [Belge çıkarımı](./src/main/util/file_to_chunks.ts), [Kütüphane araçları](./src/main/model/core-agent/kb-tools.ts)ve[konuşma geri alımı](./src/main/model/core-agent/chat-history-tools.ts).

### İcra sınırları ve geri alınma

Oturum kilitleri ve eşzamanlılık sınırları paralel çalışmayı denetler. Araç çağrısı turu sınırları, ilerleme kontrol noktaları, yinelenen çağrı denetimi ve aşamaya göre boşta kalma takibi, takılan veya kendini tekrarlayan çalıştırmaları sınırlar. Adı belirtilen ajanların görevleri tek tek izlenebilir ve iptal edilebilir. Kabul edilmiş veya kuyruğa alınmış bir görev, bitmiş sayılmaz.

Gördün mü ?[Oyuncu bütçeleri](./src/main/features/group_chat/actor-budgets.ts),[ajan çalıştırma zamanı](./src/core-agent/src/agent/runner.ts)ve[masaüstü modeli adaptörü](./src/main/model/core-agent/client.ts).

### Eğitim

Arka plan incelemesi uygulama boşta olduğunda yeni ajan etkinliklerini kontrol eder; bekleme aralıklarına ve yürütme sınırlarına tabidir. Öz değerlendirmeyi (`COMPETENCE.md`), yeniden kullanılabilir yöntemleri (`LEARNING_STRATEGIES.md`) veya öğrenilen becerileri güncelleyebilir ya da kayda değer bir şey olmadığına karar verebilir. İnceleme, tamamlanan görev sayısına değil, yeni etkinliklere göre planlanır.

Bakın[refleks programcısı](./src/main/features/reflection-orchestrator.ts)ve[inceleme süresi](./src/core-agent/src/evolution/metacognition.ts).

---

## FAQ

**Orkas nedir?**
Orkas, yerel bir ilk çok ajanlı masaüstü uygulaması olan açık kaynaklı (MIT) bir uygulama. Komutanı hedefini işleme dönüştürür ve bitmiş dosyaları teslim etmek için 16 yapılmış uzman ajanı — + Claude Code, Codex, OpenCode, OpenClaw ve Hermes-Agent — koordinat eder.

**API key lazım mı?**
Hayır. Kurulum sürümü, yerleşik Orkas modeli için 500 krediyle gelir. Krediler bitince kredi satın alabilir, ücretli bir plana geçebilir veya kendi sağlayıcınızın anahtarını ekleyebilirsiniz. Sağlayıcınız kendi ücretini ayrı olarak tahsil eder.

**Orkas yerel bir büyük dil modeli (LLM) mi?**
Hayır. Orkas bilgisayarınızda çalışır ve seçtiğiniz modeli çağırır: yerleşik Orkas modelini, kendi API anahtarınızla bağlandığınız modeli veya yerel bir model uç noktasını. Ajanları ve araçları koordine eder; kendisi bir model değildir.

**Orkas, belgelerimden alıntılarla soruları cevaplayabilir mi?**
Evet. Yerel Kütüphaneye PDF'ler ve belgeler ekleyin; Orkas onları arayabilir ve kaynak pasajlarına alıntılar ile cevap verebilir, böylece orijinalini açabilir ve kontrol edebilirsiniz. İndeks makinenizde inşa edilmiştir.

**Ollama veya LM Studio gibi yerel modeller kullanabilir miyim?**
Evet. **Hesap ayarları → Modeller → Sohbet → Model ekle → Özel** bölümünü açın. **OpenAI uyumlu** veya **Anthropic uyumlu** seçeneğini seçip temel URL'yi, modelin tam kimliğini ve API anahtarını girin. Kaydettiğiniz modeli görevdeki model seçicisinden etkinleştirin.

**API anahtarlarım ve verilerim nerede saklanıyor?**
Veriler ve anahtarlar varsayılan olarak bilgisayarınızda saklanır. Kendi sağlayıcı anahtarlarınız yerel olarak şifrelenir ve bulutla eşitlenmez. Kendi anahtarınızı kullanırsanız model istekleri bilgisayarınızdan doğrudan sağlayıcıya gider; yerleşik Orkas modeli ise Orkas'ın yönettiği hizmeti kullanır. Kurulum paketinde isteğe bağlı bulut eşitleme veya paylaşılan projeleri kullanırsanız seçilen veriler Orkas sunucularında saklanır. [Güvenlik ve veri işleme →](https://orkas.ai/security/?source=gh-orkas)

**Orkas çevrimdışı çalışıyor mu?**
Kaynak yapılandırması yerel bir model son noktasına karşı tamamen çevrimdışı çalışabilir. Paketlenmiş uygulama giriş yapmalıdır ve bulut modelleri ağ bağlantısına ihtiyaç duyar.

**Bilgisayarım kapalıyken çalışıyor mu?**
Hayır. Auto-advance ve zamanlanmış otomasyonlar için bilgisayarın uyanık, Orkas’ın da çalışır durumda olması gerekir. 1.9 sürümünden itibaren, bilgisayar uyandığında veya Orkas başlatıldığında her otomasyon önceki 12 saatte kaçırdığı çalıştırmalardan yalnızca en sonuncusunu gerçekleştirir.

**Uygulamalar oluşturabilir miyim ve yayınlayabilir miyim?**
Orkas'ın içinde çalışan yerel uygulamalar ücretsizdir. Bir web uygulamasını kamu bağlantısına yayınlamak için ücretli bir plan gerekir (Lite 5, Pro 8, Max 15 uygulamalar), ve yayınlanan web uygulamalar Orkas'ın içindeki tüm özellikleri içermez.

**Orkas hesabına ihtiyacım var mı?**
Paketlenmiş masaüstü uygulaması ilk başlatıldığında giriş yapmanızı ister. Bu depotta oluşturulan kaynak, hesap katmanı hiç değil ̇ doğrudan uygulamaya başlıyor.

**Orkas Claude Code ve diğer CLI ajanlarını kullanabilir mi?**
Orkas, yerel alt işlemler olarak beş dış CLI ajanını çalıştırabilir ∙ kodlama ajanları Claude Code, Codex ve OpenCode, ek olarak kişisel ajanlar OpenClaw ve Hermes-Agent ∙ ve HyperFrames gibi açık kaynaklı projeler üzerinde aynı sohbetten yönlendirilir.

**Orkas, Claude Code / Codex / CrewAI / LangChain'den nasıl farklıdır?**
Claude Code ve Codex kodlama ajanlarıdır; Orkas ikisini de aynı takımda çalıştırabilir. CrewAI ve LangChain kod odaklı çerçevelerdir. Orkas, Commander’ın uzman ajanları ve CLI ajanlarını koordine ettiği açık kaynaklı bir masaüstü uygulamasıdır. Farklı model sağlayıcıları arasından seçim yapabilirsiniz; veriler ve anahtarlar varsayılan olarak yerelde saklanır. [Tüm karşılaştırmaları görün](https://orkas.ai/compare/?source=gh-orkas)

**Orkas hangi platformları destekler?**
macOS 12+ (Apple Silicon ve Intel) ve Windows 10+ paketleme yükleyici sahip. glibc 2.34+ Linux x64/arm64 bugün kaynaktan çalışır, henüz bir yükleyici yoktur. Yerel konuşma transkripsiyonu Linux'ta ilk başlatmada hazırlanmış sabitlenmiş whisper.cpp çalıştırma süresi aracılığıyla desteklenir. Alpine ve diğer musl tabanlı dağıtımlar desteklenmez. Kaynak bootstrap Node 22.12+ gerektirir; Python 3 ve bir C / C ++ yapılandırma araç zinciri yalnızca yerel bir npm paketi uyumlu önceden inşa edilmiş ikili olmayan ve yerel olarak yeniden inşa edilmelidir.

**Orkas ücretsiz ve açık kaynaklı mı?**
Evet. Uygulama MIT lisanslıdır ve ücretsiz kullanılabilir. Kurulum sürümünde yerleşik Orkas modeli için 500 kredi bulunur. Aylık 11,99 ABD dolarından başlayan ücretli planlar aylık kredi, bulut eşitleme, daha fazla paylaşılan proje ve web uygulaması yayımlama olanağı sağlar. Kendi anahtarınızı kullanırsanız model kullanımını sağlayıcınız faturalandırır; Orkas bunun üzerine ücret eklemez. [Fiyatlandırma →](https://orkas.ai/pricing/?source=gh-orkas)

---

## Lisans

[MIT](./LICENSE)
