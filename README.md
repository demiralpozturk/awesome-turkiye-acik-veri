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
- [Municipalities](#municipalities)
  - [Metropolitan Municipalities](#metropolitan-municipalities)
  - [District Municipalities](#district-municipalities)
- [Transport](#transport)
- [Earthquake and Disaster](#earthquake-and-disaster)
- [Weather and Environment](#weather-and-environment)
- [Health](#health)
- [Education and Research](#education-and-research)
- [Elections](#elections)
- [Maps and Geodata](#maps-and-geodata)
- [Turkish NLP and Language Resources](#turkish-nlp-and-language-resources)
  - [Tools and Models](#tools-and-models)
  - [Corpora and Datasets](#corpora-and-datasets)
- [Developer Libraries](#developer-libraries)
- [Community and Related Lists](#community-and-related-lists)
- [Related Open Projects](#related-open-projects)

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

## Municipalities

Portals marked CKAN expose the standard [CKAN Action API](https://docs.ckan.org/en/latest/api/), for example `/api/3/action/package_list`.

### Metropolitan Municipalities

- [İBB Açık Veri Portalı](https://data.ibb.gov.tr/) - Istanbul Metropolitan Municipality's portal with hundreds of datasets on mobility, environment, economy, energy and governance. CKAN. *İstanbul Büyükşehir Belediyesi açık veri portalı; CKAN API.*
- [İzmir Büyükşehir Belediyesi Açık Veri Portalı](https://acikveri.bizizmir.com/) - İzmir Metropolitan Municipality datasets on infrastructure, GIS, mobility, environment, health and more. CKAN. *İzmir Büyükşehir Belediyesi açık veri portalı; CKAN API.*
- [Şeffaf Ankara](https://seffaf.ankara.bel.tr/) - Ankara Metropolitan Municipality transparency portal built on a GIS infrastructure. *Ankara Büyükşehir Belediyesi'nin CBS tabanlı şeffaflık portalı.*
- [Konya Açık Veri Platformu](https://acikveri.konya.bel.tr/) - Konya Metropolitan Municipality datasets. CKAN. *Konya Büyükşehir Belediyesi açık veri platformu; CKAN API.*
- [Bursa Açık Yeşil](https://acikyesil.bursa.bel.tr/) - Bursa Metropolitan Municipality open data platform. CKAN. *Bursa Büyükşehir Belediyesi açık veri platformu; CKAN API.*
- [Gaziantep Açık Veri Platformu](https://acikveri.gaziantep.bel.tr/) - Gaziantep Metropolitan Municipality datasets. CKAN. *Gaziantep Büyükşehir Belediyesi açık veri platformu; CKAN API.*
- [Açık Veri Balıkesir](https://acikveri.balikesir.bel.tr/) - Balıkesir Metropolitan Municipality datasets. CKAN. *Balıkesir Büyükşehir Belediyesi açık veri platformu; CKAN API.*
- [Trabzon Açık Veri Platformu](https://acikveri.trabzon.bel.tr/) - Trabzon Metropolitan Municipality datasets. CKAN. *Trabzon Büyükşehir Belediyesi açık veri platformu; CKAN API.*
- [Denizli Açık Veri Platformu](https://acikveri.denizli.bel.tr/) - Denizli Metropolitan Municipality datasets. CKAN. *Denizli Büyükşehir Belediyesi açık veri platformu; CKAN API.*
- [Çanakkale Açık Veri Platformu](https://acikveri.canakkale.bel.tr/) - Çanakkale municipal datasets. CKAN. *Çanakkale açık veri platformu; CKAN API.*
- [Kayseri Açık Veri](https://acikveri.kayseri.bel.tr/) - Kayseri Metropolitan Municipality datasets by category, with data requests. *Kayseri Büyükşehir Belediyesi açık veri platformu.*
- [Kocaeli Açık Veri](https://veri.kocaeli.bel.tr/) - Kocaeli Metropolitan Municipality open data portal. *Kocaeli Büyükşehir Belediyesi açık veri portalı.*
- [MBB Açık Veri Portalı](https://data.marmara.gov.tr/) - Marmara Municipalities Union's regional datasets on urbanisation, culture, environment and disaster management. *Marmara Belediyeler Birliği bölgesel veri setleri.*

### District Municipalities

- [Küçükçekmece Açık Veri Platformu](https://acikveri.kucukcekmece.bel.tr/) - Küçükçekmece (Istanbul) district datasets. *Küçükçekmece Belediyesi açık veri platformu.*
- [Tuzla Açık Veri Portalı](https://veri.tuzla.bel.tr/) - Tuzla (Istanbul) district datasets. CKAN. *Tuzla Belediyesi açık veri portalı; CKAN API.*
- [Eyüpsultan Açık Veri](https://acikveri.eyupsultan.bel.tr/) - Eyüpsultan (Istanbul) district datasets. *Eyüpsultan Belediyesi açık veri portalı.*
- [Nilüfer Açık Veri Portalı](https://acikveri.nilufer.bel.tr/) - Nilüfer (Bursa) district datasets. CKAN. *Nilüfer Belediyesi açık veri portalı; CKAN API.*

## Transport

- [İBB Toplu Ulaşım GTFS Verisi](https://data.ibb.gov.tr/dataset/public-transport-gtfs-data) - GTFS feed for Istanbul public transport. İBB Open Data License. *İstanbul toplu ulaşım GTFS verisi.*
- [İzmir Toplu Ulaşım GTFS Verileri](https://acikveri.bizizmir.com/dataset/toplu-ulasim-gtfs-verileri) - GTFS feed for İzmir public transport. İzmir Open Data License. *İzmir toplu ulaşım GTFS verisi.*
- [İBB Ulaşım Yönetim Merkezi](https://uym.ibb.gov.tr/) - Istanbul traffic density map and traffic bulletins. *İstanbul trafik yoğunluk haritası ve trafik bültenleri.*
- [KGM Trafik Hacim Haritaları](https://www.kgm.gov.tr/Sayfalar/KGM/SiteTr/Trafik/TrafikHacimHaritasi.aspx) - General Directorate of Highways traffic volume maps for the national road network. *Karayolları Genel Müdürlüğü trafik hacim haritaları.*
- [DHMİ İstatistikleri](https://www.dhmi.gov.tr/Sayfalar/Istatistikler.aspx) - Monthly aircraft, passenger and cargo statistics for Turkish airports, downloadable. *Havalimanları uçak, yolcu ve yük istatistikleri.*

## Earthquake and Disaster

- [AFAD Deprem Web Servisi](https://deprem.afad.gov.tr/event-service) - Documented web service for the latest 1,000 earthquakes recorded by AFAD, with time, area, depth and magnitude filters and JSON, XML, CSV, KML or GeoJSON output. No key required. *AFAD'ın kaydettiği son 1000 deprem; filtreli, JSON/XML/CSV/KML/GeoJSON.*
- [Kandilli Son Depremler](http://www.koeri.boun.edu.tr/scripts/lst0.asp) - Boğaziçi University Kandilli Observatory's plain-text list of the latest earthquakes. *Kandilli Rasathanesi son depremler listesi (düz metin).*
- [KOERI FDSN Web Services](https://eida.koeri.boun.edu.tr/fdsnws/) - FDSN station and dataselect services for metadata and waveforms of the Kandilli (KO) seismic network. *Kandilli sismik ağının istasyon ve dalga formu verileri (FDSN).*
- [MTA Yer Bilimleri Harita Görüntüleyici](https://yerbilimleri.mta.gov.tr/) - Earth sciences map viewer of the General Directorate of Mineral Research and Exploration. *Maden Tetkik ve Arama Genel Müdürlüğü yer bilimleri harita görüntüleyicisi.*
- [Kandilli Rasathanesi API](https://github.com/orhanayd/kandilli-rasathanesi-api) - Community API that merges Kandilli and AFAD earthquake data, with GeoJSON output and filters. Custom non-commercial license. *Kandilli ve AFAD verilerini birleştiren topluluk API'si; ticari olmayan özel lisans.*

## Weather and Environment

- [Meteoroloji Genel Müdürlüğü](https://www.mgm.gov.tr/) - Official forecasts, observations and warnings from the Turkish State Meteorological Service. No public API. *Resmî hava tahminleri, gözlemler ve uyarılar.*
- [MGM İl ve İlçe İstatistikleri](https://mgm.gov.tr/veridegerlendirme/il-ve-ilceler-istatistik.aspx) - General climate statistics and 1991-2020 seasonal normals by province. *İllere ait genel istatistiki veriler ve 1991-2020 mevsim normalleri.*
- [Hava Kalitesi Veri Bankası](https://sim.csb.gov.tr/STN/STN_Report/DataBank) - Station measurements from the National Air Quality Monitoring Network, with data download and charts. *Ulusal Hava Kalitesi İzleme Ağı istasyon verileri ve indirme.*
- [Çevresel Göstergeler](https://cevreselgostergeler.csb.gov.tr/) - Environmental indicators published by the Ministry of Environment, Urbanisation and Climate Change. *Çevre, Şehircilik ve İklim Değişikliği Bakanlığı çevresel göstergeleri.*
- [İSKİ Baraj Doluluk Oranları](https://iski.istanbul/baraj-doluluk/) - Istanbul dam occupancy rates with overall and per-dam charts. *İstanbul baraj doluluk oranları ve grafikleri.*

## Health

- [Sağlık Bakanlığı Açık Veri Portalı](https://acikveri.saglik.gov.tr/) - Ministry of Health open data portal, mostly annotated medical imaging datasets such as those released for TEKNOFEST competitions. *Sağlık Bakanlığı açık veri portalı; ağırlıklı olarak etiketli tıbbi görüntü veri setleri.*
- [Sağlık İstatistikleri](https://sbsgm.saglik.gov.tr/TR-93554/istatistikler.html) - Ministry of Health statistics pages, including the annual Health Statistics Yearbook. *Sağlık İstatistikleri Yıllığı ve diğer istatistikler.*
- [TİTCK İlaç Fiyat Listesi](https://www.titck.gov.tr/dinamikmodul/100) - Reference-based drug price lists from the Turkish Medicines and Medical Devices Agency, as XLSX files. *Referans bazlı ilaç fiyat listeleri (XLSX).*
- [TİTCK E-Reçete İlaç Listesi](https://www.titck.gov.tr/dinamikmodul/43) - Regularly updated XLSX list of drugs and pharmaceutical products for e-prescriptions. *Düzenli güncellenen e-reçete ilaç ve farmasötik ürün listesi (XLSX).*

## Education and Research

- [Yükseköğretim Bilgi Yönetim Sistemi](https://istatistik.yok.gov.tr/) - Council of Higher Education statistics system for universities, students and academic staff. *YÖK yükseköğretim istatistikleri sistemi.*
- [YÖK Atlas](https://yokatlas.yok.gov.tr/) - Higher education programme atlas with placement statistics for each university programme. *Üniversite programlarının yerleştirme istatistikleri.*
- [MEB Resmî İstatistikler](https://sgb.meb.gov.tr/www/resmi-istatistikler/icerik/64) - Ministry of National Education official statistics publications. *Millî Eğitim Bakanlığı resmî istatistik yayınları.*
- [ULAKBİM Üniversite Veri Portalı](https://veri.ulakbim.gov.tr/index) - TÜBİTAK ULAKBİM portal sharing university outputs collected from its information systems. *TÜBİTAK ULAKBİM'in üniversite kazanımlarını paylaştığı veri portalı.*
- [Ulusal Tez Merkezi](https://tez.yok.gov.tr/UlusalTezMerkezi/) - National Thesis Center for searching graduate theses. *Lisansüstü tezler için ulusal tez arama merkezi.*
- [DergiPark](https://dergipark.org.tr/) - Hosting platform for Turkish academic journals, with an OAI-PMH endpoint at `dergipark.org.tr/api/public/oai/`. *Türk akademik dergileri platformu; OAI-PMH desteği.*
- [TR Dizin](https://trdizin.gov.tr/) - TÜBİTAK ULAKBİM's national index of Turkish academic journals. *TÜBİTAK ULAKBİM ulusal akademik dergi dizini.*
- [Aperta](https://aperta.ulakbim.gov.tr/) - TÜBİTAK open archive for publications and research data, with a JSON REST API at `/api/records`. *TÜBİTAK açık arşivi; yayın ve araştırma verileri, REST API.*

## Elections

- [YSK Açık Veri Portalı](https://acikveri.ysk.gov.tr/anasayfa) - Supreme Election Council dashboards on voters, candidates, parties and results, exportable to Excel. *Yüksek Seçim Kurulu seçmen, aday, parti ve sonuç panoları; Excel'e aktarılabilir.*
- [YSK Sandık Sonuçları ve Tutanaklar](https://sonuc.ysk.gov.tr/) - Ballot-box level election results and tally sheets. *Sandık bazında seçim sonuçları ve tutanaklar.*
- [turkeyelections](https://cran.r-project.org/package=turkeyelections) - R package with general, local and presidential election results from 1995 to 2024 by province. MIT License. *1995-2024 seçim sonuçlarını il bazında içeren R paketi.*

## Maps and Geodata

- [TUCBS](https://tucbs.gov.tr/) - Türkiye National Geographic Information System portal with a geodata viewer, data dictionary, metadata catalogue and geographic open data portal. *Türkiye Ulusal Coğrafi Bilgi Sistemi; coğrafi veri görüntüleme ve açık veri portalı.*
- [HGM Atlas](https://atlas.harita.gov.tr/) - Map viewer of the General Directorate of Mapping. *Harita Genel Müdürlüğü harita görüntüleyicisi.*
- [Harita İstanbul](https://harita.istanbul/) - Istanbul Metropolitan Municipality's city map. *İBB şehir haritası.*
- [Geofabrik Türkiye](https://download.geofabrik.de/europe/turkey.html) - Frequently updated OpenStreetMap extracts for Türkiye in PBF, shapefile and GeoPackage formats. ODbL. *Türkiye OpenStreetMap verisi; PBF, shapefile ve GeoPackage.*
- [OpenStreetMap WikiProject Turkey](https://wiki.openstreetmap.org/wiki/Turkey) - Community wiki with Türkiye mapping conventions and resources. *Türkiye haritalama kuralları ve kaynakları.*
- [geoBoundaries](https://www.geoboundaries.org/) - Open administrative boundary data, including Türkiye's province and district layers with the license stated per layer. *İl ve ilçe sınırları dahil açık idari sınır verisi.*
- [GADM](https://gadm.org/download_country.html) - Administrative boundaries for every country, including Türkiye. Free for academic and other non-commercial use only. *İdari sınırlar; yalnızca akademik ve ticari olmayan kullanım.*
- [PTT Posta Kodu Sorgulama](https://www.ptt.gov.tr/posta-kodu) - Official postal code lookup. *Resmî posta kodu sorgulama.*

## Turkish NLP and Language Resources

### Tools and Models

- [Zemberek-NLP](https://github.com/ahmetaa/zemberek-nlp) - Java toolkit for Turkish morphology, tokenization, normalization and more. Apache-2.0. *Türkçe biçimbilim, sözcükleme ve normalleştirme araçları (Java).*
- [zemberek-python](https://github.com/Loodos/zemberek-python) - Python implementation of Zemberek. Apache-2.0. *Zemberek'in Python uygulaması.*
- [BERTurk](https://huggingface.co/dbmdz/bert-base-turkish-cased) - Cased BERT model for Turkish; more variants in the [turkish-bert](https://github.com/stefan-it/turkish-bert) repository. MIT. *Türkçe BERT modeli.*
- [VNLP](https://github.com/vngrs-ai/vnlp) - Lightweight Turkish NLP tools for tasks such as NER, POS tagging and sentiment analysis. AGPL-3.0. *Hafif Türkçe doğal dil işleme araçları.*
- [Turkish spaCy Models](https://github.com/turkish-nlp-suite/turkish-spacy-models) - spaCy pipelines for Turkish by the Turkish NLP Suite. CC BY-SA 4.0. *Türkçe spaCy modelleri.*
- [turkish-morphology](https://github.com/google-research/turkish-morphology) - Two-level morphological analyzer for Turkish from Google Research (archived). Apache-2.0. *Türkçe iki düzeyli biçimbilimsel çözümleyici.*
- [Mukayese](https://github.com/alisafaya/mukayese) - Datasets, benchmarks and baselines for several Turkish NLP tasks. MIT. *Türkçe NLP görevleri için veri setleri ve karşılaştırmalı değerlendirmeler.*
- [Turkish GPT-2](https://huggingface.co/ytu-ce-cosmos/turkish-gpt2) - Text generation model for Turkish based on GPT-2, from the YTU COSMOS group. MIT. *YTÜ COSMOS'un Türkçe GPT-2 modeli.*
- [Trendyol LLM](https://huggingface.co/Trendyol/Trendyol-LLM-7b-chat-v1.8) - Mistral-7B-based chat model trained mainly on Turkish and English. Apache-2.0. *Ağırlıklı olarak Türkçe ve İngilizce eğitilmiş, Mistral 7B tabanlı sohbet modeli.*
- [Turkcell-LLM-7b-v1](https://huggingface.co/TURKCELL/Turkcell-LLM-7b-v1) - Mistral-7B-based model with a Turkish-extended tokenizer, trained on 5 billion Turkish tokens. Apache-2.0. *Türkçe için genişletilmiş, Mistral 7B tabanlı dil modeli.*

### Corpora and Datasets

- [UD Turkish-BOUN](https://github.com/UniversalDependencies/UD_Turkish-BOUN) - Universal Dependencies treebank of Turkish from Boğaziçi University. CC BY-SA 4.0. *Boğaziçi Üniversitesi Türkçe bağlılık ağaç bankası.*
- [BellaTurca](https://huggingface.co/datasets/turkish-nlp-suite/BellaTurca) - Large Turkish text corpus collection by the Turkish NLP Suite. CC BY-SA 4.0. *Büyük ölçekli Türkçe metin derlemi.*
- [TS Corpus](https://tscorpus.com/) - Free, independent project building Turkish corpora, lexical tools and linguistic datasets since 2011. *2011'den beri Türkçe derlem, sözlük araçları ve dilbilimsel veri setleri.*
- [TULAP](https://tulap.cmpe.bogazici.edu.tr/) - Boğaziçi University's Turkish NLP platform hosting corpora and tools with demos. *Boğaziçi Üniversitesi Türkçe Doğal Dil İşleme Platformu.*
- [İTÜ NLP Datasets](http://tools.nlp.itu.edu.tr/Datasets) - Turkish NLP datasets from Istanbul Technical University's NLP group. *İTÜ Doğal Dil İşleme grubunun Türkçe veri setleri.*
- [YTÜ Kemik Veri Kümeleri](http://www.kemik.yildiz.edu.tr/veri_kumelerimiz.html) - Turkish text datasets from Yıldız Technical University's Kemik NLP group. *YTÜ Kemik grubunun Türkçe metin veri kümeleri.*
- [Turkish Wikipedia Dumps](https://dumps.wikimedia.org/trwiki/) - Regular dumps of Turkish Wikipedia. CC BY-SA. *Türkçe Vikipedi dökümleri.*
- [Common Voice Turkish](https://commonvoice.mozilla.org/tr/datasets) - Crowd-sourced Turkish speech dataset. CC0-1.0. *Gönüllülerce toplanan Türkçe konuşma veri seti.*
- [TDK Güncel Türkçe Sözlük](https://sozluk.gov.tr/) - Turkish Language Association's official dictionary. Website only; no documented public API. *Türk Dil Kurumu resmî sözlüğü.*

## Developer Libraries

- [python-stdnum](https://github.com/arthurdejong/python-stdnum) - Python validators for standard numbers, including Turkish identity numbers (`tr.tckimlik`), tax numbers (`tr.vkn`) and IBAN. LGPL-2.1. *TCKN, VKN ve IBAN doğrulama (Python).*
- [stdnum-js](https://github.com/koblas/stdnum-js) - JavaScript validators for standard numbers, including Turkish TCKN and VKN. MIT. *TCKN ve VKN doğrulama (JavaScript).*
- [TurkiyeAPI](https://github.com/ubeydeozdmr/turkiye-api) - REST API for provinces, districts, municipalities, neighbourhoods and villages, with a hosted version and OpenAPI docs. MIT. *İl, ilçe, mahalle ve köy verileri için REST API.*
- [turkey-neighbourhoods](https://github.com/muratgozel/turkey-neighbourhoods) - Names of cities, districts and neighbourhoods with postal codes, plate codes and city distances. MIT. *İl, ilçe, mahalle, posta kodu, plaka ve şehirlerarası mesafe verileri.*
- [holidays](https://github.com/vacanza/holidays) - Python library for public holidays with Türkiye support. MIT. *Türkiye destekli resmî tatil kütüphanesi (Python).*
- [date-holidays](https://github.com/commenthol/date-holidays) - JavaScript holiday library with Türkiye support. ISC code, CC BY-SA 4.0 data. *Türkiye destekli tatil kütüphanesi (JavaScript).*
- [Nager.Holidays API](https://nagerholidays.com/api) - Free public holiday REST API that covers Türkiye. MIT. *Türkiye'yi kapsayan ücretsiz resmî tatil API'si.*
- [Faker](https://github.com/joke2k/faker) - Python fake data generator with a `tr_TR` locale. MIT. *Türkçe yerel ayarlı sahte veri üretici (Python).*
- [Faker.js](https://github.com/faker-js/faker) - JavaScript fake data generator with a `tr` locale. MIT. *Türkçe yerel ayarlı sahte veri üretici (JavaScript).*
- [tcmb](https://github.com/kaymal/tcmb-py) - Python client for the Central Bank's EVDS web service. MIT. *EVDS için Python istemcisi.*
- [evds](https://github.com/fatihmete/evds) - Python package for accessing EVDS statistics. MIT. *EVDS verileri için Python paketi.*
- [CBRT](https://cran.r-project.org/package=CBRT) - R package for EVDS data series. GPL-3.0. *EVDS veri serileri için R paketi.*

## Community and Related Lists

- [AVTED](https://avted.org.tr/) - Open Data and Technology Association, publisher of the Open Data Index for Türkiye. *Açık Veri ve Teknoloji Derneği; Açık Veri Endeksi.*
- [OpenStreetMap Türkiye Forum](https://community.openstreetmap.org/c/communities/tr/118) - Turkish OpenStreetMap community forum. *Türkiye OpenStreetMap topluluk forumu.*
- [Türkiye'deki Açık Veri Portalları](https://github.com/ozancanozdemir/Turkiye-deki-Acik-Veri-Portallari-Open-Data-Portals-in-Turkey-) - Bilingual catalogue of open data portals in and about Türkiye. *Türkiye'deki ve Türkiye ile ilgili açık veri portalları kataloğu.*
- [Açık Veri Kaynakları](https://github.com/kaymal/acik-veri) - Curated list of Turkish open data platforms. *Türkiye'nin açık veri platformları listesi.*
- [Turkish NLP Resources](https://github.com/agmmnn/turkish-nlp-resources) - Tools, libraries, models and datasets for Turkish NLP. *Türkçe doğal dil işleme kaynakları listesi.*

## Related Open Projects

Open-source projects built on the sources above.

- [resmi-gazete-takip](https://github.com/demiralpozturk/resmi-gazete-takip) - Turns the daily Resmî Gazete into open JSON data, an RSS feed and a searchable site, highlighting customs and foreign trade items. By the list creator. MIT. *Resmî Gazete'yi günlük açık veriye, RSS'e ve aranabilir siteye dönüştürür; liste yazarının projesi.*
- [market-scraper](https://github.com/demiralpozturk/market-scraper) - Supermarket price comparison for Türkiye with open JSON data refreshed every six hours by GitHub Actions. By the list creator. MIT. *Market fiyat karşılaştırması ve açık JSON verisi; liste yazarının projesi.*

## Contributing

Suggestions are welcome in English or Turkish. Open an issue with the "Kaynak öner / Suggest a source" template, or send a pull request after reading the [contribution guidelines](contributing.md).

Öneriler Türkçe veya İngilizce olabilir. "Kaynak öner / Suggest a source" şablonuyla bir konu açın ya da katkı rehberini okuduktan sonra çekme isteği gönderin.

---

Creator: **Demiralp Öztürk** · [GitHub](https://github.com/demiralpozturk) · [LinkedIn](https://www.linkedin.com/in/demiralp-%C3%B6zt%C3%BCrk/)
