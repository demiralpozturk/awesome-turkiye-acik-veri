# Awesome Türkiye Açık Veri [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Open data sources, public APIs and datasets about Türkiye, for developers.
> *Geliştiriciler için Türkiye'nin açık veri kaynakları, kamu API'leri ve veri setleri.*

**Community-curated, unofficial.** This list is not affiliated with or endorsed by any institution listed. Every link was checked for status and content before it was added. Notes such as "API key required" or license names describe what was found at the time of checking, so always read each source's own terms of use.

**Topluluk tarafından derlenmiştir, resmî değildir.** Listelenen kurumlarla bir bağlantısı yoktur. Her bağlantı eklenmeden önce kontrol edilmiştir; kullanım koşulları için her kaynağın kendi sayfasını okuyun.

## Contents

- [Statistics and National Portals](#statistics-and-national-portals)
- [Economy and Finance](#economy-and-finance)
- [Energy](#energy)
- [Legislation and Justice](#legislation-and-justice)
- [Trade and Customs](#trade-and-customs)

## Statistics and National Portals

- [TÜİK Veri Portalı](https://veriportali.tuik.gov.tr/) - Turkish Statistical Institute's data portal with official statistics, tables and bulletins grouped by theme. *TÜİK'in temalara göre gruplanmış resmî istatistikleri, tabloları ve bültenleri.*
- [TÜİK MEDAS](https://biruni.tuik.gov.tr/medas/) - Central dissemination system for building custom tables by indicator, regional level and period. *Gösterge, bölge düzeyi ve döneme göre özel tablo oluşturma sistemi.*
- [Resmî İstatistik Portalı](https://www.resmiistatistik.gov.tr/) - Portal of the Official Statistics Programme, gathering official statistics from the institutions that produce them. *Resmî İstatistik Programı kapsamındaki istatistiklerin ortak portalı.*
- [SGK Veri Portalı](https://veri.sgk.gov.tr/) - Social Security Institution statistics that can be filtered by geographic or statistical region and exported to Excel. *SGK istatistiklerini coğrafi veya istatistiki bölgeye göre sorgulama ve Excel'e aktarma.*
- [Turizm İstatistikleri](https://yigm.ktb.gov.tr/TR-9851/turizm-istatistikleri.html) - Ministry of Culture and Tourism border statistics, including monthly border bulletins. *Kültür ve Turizm Bakanlığı sınır istatistikleri ve aylık sınır bültenleri.*
- [CEİD Veri Portalı](https://veriportali.ceid.org.tr/) - Gender equality indicators compiled by the Association for Monitoring Gender Equality, an NGO. *Cinsiyet Eşitliği İzleme Derneği'nin toplumsal cinsiyet eşitliği göstergeleri.*

## Economy and Finance

- [TCMB Döviz Kurları XML](https://www.tcmb.gov.tr/kurlar/today.xml) - Central Bank's daily indicative exchange rates as XML; past days follow the pattern `kurlar/YYYYMM/DDMMYYYY.xml`. No key required. *TCMB'nin günlük gösterge döviz kurları; geçmiş günler aynı adres kalıbıyla erişilebilir.*
- [EVDS](https://evds3.tcmb.gov.tr/) - Central Bank's Electronic Data Delivery System for time series on the Turkish economy, with a web service and an MCP server. A free account and API key are required for programmatic access. *TCMB Elektronik Veri Dağıtım Sistemi; web servisi için ücretsiz hesap ve API anahtarı gerekir.*
- [KAP](https://www.kap.org.tr/) - Public Disclosure Platform with filings, financial statements and material event disclosures of listed companies and funds. *Kamuyu Aydınlatma Platformu: şirket ve fon bildirimleri, finansal tablolar.*
- [SPK İstatistiksel Veriler](https://spk.gov.tr/istatistikler/istatistiksel-veriler) - Capital Markets Board statistics on Turkish capital markets. *Sermaye Piyasası Kurulu istatistiksel verileri.*
- [BDDK Aylık Bülten](https://www.bddk.org.tr/BultenAylik) - Banking regulator's monthly banking sector bulletin with interactive tables. *BDDK'nın aylık bankacılık sektörü bülteni.*
- [BDDK FinTürk](https://www.bddk.org.tr/BultenFinturk) - Province-level banking data on loans, deposits, branches and staff. *İl bazında kredi, mevduat, şube ve personel verileri.*
- [TBB Veri Sorgulama Sistemi](https://verisistemi.tbb.org.tr/) - Banks Association of Türkiye's query system for bank-level financial and statistical data. *Türkiye Bankalar Birliği banka bazlı veri sorgulama sistemi.*
- [Borsa İstanbul DataStore](https://datastore.borsaistanbul.com/) - Official store for historical Borsa İstanbul market data. Paid, with discounts and free older data for academic use. *Borsa İstanbul tarihsel veri satış platformu; akademik kullanıma indirim.*
- [MKK Veri Analiz Platformu](https://www.vap.org.tr/) - Central Registry Agency statistics on custody values, investor counts by province and nationality, and foreign ownership. *Merkezi Kayıt Kuruluşu saklama ve yatırımcı istatistikleri.*
- [Temel Ekonomik Göstergeler](https://www.sbb.gov.tr/temel-ekonomik-gostergeler/) - Presidency of Strategy and Budget's tables of key economic indicators. *Strateji ve Bütçe Başkanlığı temel ekonomik gösterge tabloları.*

## Energy

- [EPİAŞ Şeffaflık Platformu](https://seffaflik.epias.com.tr/) - Electricity and natural gas market transparency data such as prices, generation and consumption, with documented REST APIs ([electricity](https://seffaflik.epias.com.tr/electricity-service/technical/tr/index.html), [natural gas](https://seffaflik.epias.com.tr/natural-gas-service/technical/tr/index.html)). API access requires a free account and a TGT token. *Elektrik ve doğal gaz piyasası şeffaflık verileri; API için üyelik ve TGT gerekir.*
- [EPDK Akaryakıt Fiyatları](https://www.epdk.gov.tr/Detay/Icerik/3-0-158/akaryak%C4%B1tfiyat) - Energy Market Regulatory Authority reports on daily fuel prices of the eight highest-volume distributors since 2016. *En yüksek işlem hacimli 8 dağıtıcının 2016'dan bu yana günlük akaryakıt fiyatları.*

## Legislation and Justice

- [Resmî Gazete](https://www.resmigazete.gov.tr/) - Official Gazette of the Republic of Türkiye; each day's index is at `eskiler/YYYY/MM/YYYYMMDD.htm`. *Günlük Resmî Gazete; her günün fihristi sabit bir adres kalıbında.*
- [Mevzuat Bilgi Sistemi](https://www.mevzuat.gov.tr/) - Consolidated texts of laws, presidential decrees, regulations and communiqués. *Kanun, Cumhurbaşkanlığı kararnamesi, yönetmelik ve tebliğlerin güncel metinleri.*
- [TBMM](https://www.tbmm.gov.tr/) - Grand National Assembly with bills, laws, parliamentary questions and lists of MPs. *Kanun teklifleri, kanunlar, soru önergeleri ve milletvekili listeleri.*
- [Anayasa Mahkemesi Kararlar Bilgi Bankası](https://kararlarbilgibankasi.anayasa.gov.tr/) - Searchable database of Constitutional Court decisions. *Anayasa Mahkemesi kararları arama.*
- [Yargıtay Karar Arama](https://karararama.yargitay.gov.tr/) - Court of Cassation decision search. Web interface only. *Yargıtay kararları arama; yalnızca web arayüzü.*
- [Danıştay Karar Arama](https://karararama.danistay.gov.tr/) - Council of State decision search. Web interface only. *Danıştay kararları arama; yalnızca web arayüzü.*
- [UYAP Emsal Karar Arama](https://emsal.uyap.gov.tr/) - Precedent decision search of the national judiciary informatics system. *Ulusal Yargı Ağı emsal karar arama.*
- [Rekabet Kurulu Kararları](https://www.rekabet.gov.tr/tr/Kararlar) - Competition Board decision search. *Rekabet Kurulu kararları arama.*
- [Sayıştay Raporları](https://www.sayistay.gov.tr/reports) - Court of Accounts audit reports on public administrations. *Kamu idarelerine ait Sayıştay denetim raporları.*
- [EKAP](https://ekap.kik.gov.tr/) - Electronic Public Procurement Platform with tender announcements and results. *Elektronik Kamu Alımları Platformu; ihale ilanları ve sonuçları.*

## Trade and Customs

- [Ticaret Bakanlığı Dış Ticaret İstatistikleri](https://ticaret.gov.tr/istatistikler/dis-ticaret-istatistikleri) - Ministry of Trade monthly foreign trade figures and data bulletins. *Ticaret Bakanlığı aylık dış ticaret verileri ve bültenleri.*
- [TÜİK Dış Ticaret İstatistikleri](https://biruni.tuik.gov.tr/disticaretapp/menu.zul) - Interactive query tool for official foreign trade statistics. *Resmî dış ticaret istatistikleri için etkileşimli sorgulama aracı.*
- [TARA](https://uygulama.gtb.gov.tr/Tara/) - Integrated customs tariff search by keyword or GTİP (HS) code. *Kelime veya GTİP koduyla Türkiye entegre gümrük tarifesi arama.*
- [Hal Kayıt Sistemi Fiyatları](https://www.hal.gov.tr/Sayfalar/FiyatDetaylari.aspx) - Product price details from the wholesale produce market registry. *Hal Kayıt Sistemi ürün fiyat detayları.*
- [TİM İhracat Rakamları](https://tim.org.tr/tr/ihracat-rakamlari) - Turkish Exporters Assembly monthly export figures by sector. *Türkiye İhracatçılar Meclisi aylık sektörel ihracat rakamları.*
- [Market Fiyatı](https://marketfiyati.org.tr/) - Grocery price comparison across thousands of products in many stores. No documented public API. *Birçok mağazada binlerce ürünün fiyat karşılaştırması.*
- [TOBB Kurulan ve Kapanan Şirket İstatistikleri](https://www.tobb.org.tr/BilgiErisimMudurlugu/Sayfalar/KurulanKapananSirketistatistikleri.php) - Official statistics on companies founded and closed, published by the Union of Chambers and Commodity Exchanges. *Kurulan ve kapanan şirketlere ilişkin resmî istatistikler.*

## Contributing

Suggestions are welcome in English or Turkish. Open an issue with the "Kaynak öner / Suggest a source" template, or send a pull request after reading the [contribution guidelines](contributing.md).

Öneriler Türkçe veya İngilizce olabilir. "Kaynak öner / Suggest a source" şablonuyla bir konu açın ya da katkı rehberini okuduktan sonra çekme isteği gönderin.

---

Creator: **Demiralp Öztürk** · [GitHub](https://github.com/demiralpozturk) · [LinkedIn](https://www.linkedin.com/in/demiralp-%C3%B6zt%C3%BCrk/)
