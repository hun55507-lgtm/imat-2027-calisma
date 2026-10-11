# Belge 1–2 kural sisteminin iç tutarlılığı ve eksiksizliği

Kapsam: Belge 1'deki "Sorumluluk özeti", "Daraltma araçları", Dışlanan ve Sınır listeleri; Belge 2'deki matris formülü, Kural 1, 2, 3a, 3b, 3c, derinlik kuralı ve "Karakteristik". Kurallar yazıldığı gibi, Sorumluluk özetindeki sırayla (1 → 5) uygulandı. Her aday bulgu belgenin kendi tanım ve ifadeleriyle çürütülmeye çalışıldı; yalnızca sağ kalanlar bulgu olarak yazıldı.

- Doğrulama etiketi: **DOĞRULANDI** (çelişki belgenin kendi metninden çıkıyor) · **MAKUL** (sonuç görülemeyen bir soru metnine ya da bir yargıya bağlı).
- Karar etkisi: **Kapsam** (konu girer ya da çıkar) · **Derinlik** · **Saat** (Kural 3b bütçesi) · **Yalnız ifade**.
- Geri çekilmiş C2 ve C10 yeniden açılmadı. Bunlara benzeyen iki aday (Hess yasası; "isotopi" üzerinden radyoaktivite) yeni bir argüman çıkarmadığı için 8. bölümde "geri çevrilen adaylar" altında duruyor.
- Kaynak kısaltmaları: **B** = kullanıcının güncel metni ([belgeler.md](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>), satır numaralarıyla); **AA** = Allegato A ([allA.txt](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/pdf/allA.txt>)); **IND** = Indicazioni s.337–346 ([ind.txt](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/pdf/ind.txt>)); **REV** = önceki inceleme ([belge-1-2-dogrulama-2026-10-10.md](</home/user/imat-2027-calisma/inceleme/belge-1-2-dogrulama-2026-10-10.md>)); **SK** = sınav kanıtı notları ([sinav_kaniti_ncert.md](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>)); **OM** = okul müfredatı notları ([okul_mufredati_belgeleri.md](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/okul_mufredati_belgeleri.md>)).

## 1. Hangi bulgular çürütme denemesinden sağ çıktı ve karar etkileri ne?

### Takeaway
On dört bulgu sağ kaldı. Kararı en çok etkileyen üçü şunlar. (K1) "Sınır" tanımı ile prosedür, listelerde olmayan "yeni kavram" alt konularında farklı sonuç veriyor; aynı konu 0 saat, 1 saat ya da T derinliği alabiliyor. (K3) Kural 3b'nin saat bütçesinin birimi ("öğe") tanımlı değil. (K6) Belgede "kanıt" ölçütü tanımlı değil; 2024 S50 ile 2026 S58 birlikte okunduğunda, hangi ölçüt seçilirse seçilsin bir sınıflandırma yanlış çıkıyor. Kalan bulgular derinlik ya da ifade düzeyinde. Formülde ve çapraz atıflarda sonucu değiştiren bir hata yok; sorunlar biçimsel.

### Cited Findings
Sıralama karar etkisine göredir. Her satırın ayrıntısı ve alıntıları ilgili bölümdedir.

| No | Bulgu (tür) | Çatışan ifadeler | Doğrulama | Karar etkisi |
|---|---|---|---|---|
| K1 | Listede olmayan "yeni kavram" alt konuları: tanım "sınır" (1 sa) diyor, 4. adım 0 sa veriyor, "doğrudan uygulama" yargısı T veriyor (a+b) | B satır 10 "Her sınır öğesinin … 'Sınır listesi'nde yazılıdır" ↔ B satır 42 adım 4 ↔ B satır 85 "aynı kurala tabidir" | DOĞRULANDI (koligatif özellikler, Michaelis–Menten); MAKUL (açısal momentum, RMS) | Kapsam + Saat; orta |
| K2 | Kapalı sayım ve belirteçlerle kesilen öğeler için ölçüt yazılı değil ve tutarsız uygulanıyor: log tabanları kapsama alınıyor, kotanjant sınırda kalıyor; bazı kesilen öğelerin listede yeri yok (a+b) | B satır 61 ↔ satır 62, satır 79 "Diğer sayımlar kapalıdır"; satır 58 "nell'uomo" | DOĞRULANDI | Kapsam/Saat; düşük–orta |
| K3 | 3b'deki "öğe" birimi tanımsız: madde işareti mi, alt öğe mi, açık sınıf mı? (b+c) | B satır 199–200 ↔ satır 119 (karışık kanıtlı satır), satır 90 ↔ satır 204 | DOĞRULANDI | Saat + Derinlik; orta |
| K4 | Tanıma katmanının içeriği tanımsız; 3b "kapsamı … burada tanımlıdır" diyor ama yalnızca saat veriyor (b+d) | B satır 197 ↔ satır 199–200 | DOĞRULANDI | Derinlik; düşük–orta |
| K5 | Sınır satırlarında 3c bağımlılığı kayıtlı değil; kütle merkezi listeye göre 1 saat, 3c'ye göre denge probleminin istediği derinlik alıyor (a) | B satır 70 ↔ satır 113 ↔ satır 40 | MAKUL | Derinlik; düşük |
| K6 | "Kanıt" ölçütü yok: 2024 S50 "gerektirir" ölçütüyle kanıt değil, 2026 S58 "çözülebilir" ölçütüyle kanıt; belge ikisine ters yönde karar veriyor. 2026 S49 da büyük olasılıkla 2025 S55 gibi kapsam içi (c+d) | B satır 66, 100–101, 204 ↔ SK §3, §5 | DOĞRULANDI (S50/S58); MAKUL (S49) | Kapsam + Saat + Kalan risk sayısı; orta |
| K7 | Kanıtlı sınır öğesinin derinliği iki ayrı yerde iki ayrı biçimde tanımlı: "dayanağın derinliği" ve öğenin kendi min(d_T, d_Cmax) değeri (c) | B satır 198, 40 ↔ satır 170, 172 | DOĞRULANDI (biçimsel) | Derinlik; düşük |
| K8 | İki başlık altına düşen öğede 2a niteleyicisinin hangi başlıktan geleceği belirsiz: enzimler, biyomoleküller, canlılarda redoks (c) | B satır 184, 187 ↔ satır 53 | MAKUL | Derinlik; düşük–orta |
| K9 | Çıpa üst sınırı aşarsa hangisinin öncelikli olduğu yazılı değil; tek örnekte (redoks) 2a niteleyicisi sınav kanıtıyla genişletiliyor (c) | B satır 189 ↔ satır 51, 53, 172 | DOĞRULANDI | Bugün yok; gelecekte Derinlik |
| K10 | Formül: cl_r geçişli, 3c tek adımlı; kapanış kesişimden önce alınıyor; j'nin tanım kümesi iki belgede farklı; M_3/"çekirdek" anlamı kayıyor; iki yoldan giren öğenin derinliği tanımsız (c) | B satır 168–174 ↔ satır 206, 25, 45, 179, 3 | DOĞRULANDI (biçimsel) | Bugün yok; süreç |
| K11 | Adım 1 ile derinlik formülü niteleyicinin rolünü farklı anlatıyor (d) | B satır 39 ↔ satır 172, 180 | DOĞRULANDI | Yalnız ifade |
| K12 | Biyolojide sınır satırları ile 1. adım arasındaki çizgi yazılı değil: Gelişim ve insan üremesi, Mikroorganizmalar ve "I virus/Il DNA dei procarioti", Mikroskobi ve "Dimensioni cellulari" (b) | B satır 120–122 ↔ AA s.2 | MAKUL | Saat; orta–düşük (embriyoloji) |
| K13 | "İkincil kalemler sorumluluk kararlarını etkilemez" cümlesi, s.337–346'nın kendisi İkincil etiketli olduğu için kendi içinde tutarsız (d) | B satır 157 ↔ satır 143 | DOĞRULANDI | Yalnız ifade/statü |
| K14 | "sınır komşusu" ifadesi tanımlı "Sınır" terimiyle çakışıyor (ifade) | B satır 92 ↔ satır 85, 10 | DOĞRULANDI | Yalnız ifade |

Önceki incelemedeki bulguların yeniden kontrolü (REV, C bölümü):
- **C3 sağ kaldı ve güçlendi:** K6'ya bakın. Güncel metne eklenen olasılık ölçütü ("olumlu/olası durum sayımı ve kombinasyonla çözülebilen çekiliş problemleri kapsamda okunur", B satır 66) çelişkiyi doğrudan belgenin kendi cümlesine dayandırıyor.
- **C1 kısmen sağ kaldı:** K6'ya bakın. Kanıt şüpheliyse, K3'teki madde işareti birimi yüzünden saat etkisi doğar; "karar etkisi yok" hükmü bu durumda tutmaz.
- **C8 sağ kaldı** (biçimsel). K10 iki yeni alt nokta ekliyor: 3c'nin tek adımlılığı ve j'nin tanım kümesi.
- **C6 sağ kaldı** (düşük etki). Kural 1'e göre $C_{max}$ dayanağı reddedilirse 1 saatlik katman 0'a iner (bkz. 2. bölüm, konu 9).
- **C5 ve C7 sağ kaldı**, ikisi de yalnız ifade (bkz. 7. bölüm).
- **C4 ve C9 tutarlı:** C4 için 2024 S51 payında |x| var ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2024); C9'un aritmetiği K6'ya bağlı.

### Inferences
- Bulguların çoğu tek bir yapısal boşluktan çıkıyor. Prosedür (adım 1–4) yalnızca iki listeyi tanıyor; "sınır" ise listeden bağımsız, kavramsal bir ölçütle (yeni kavram) tanımlanıyor. Listelenmemiş her alt konu üç farklı sonuca açık kalıyor. En küçük onarım, tanıma şu iki şartı eklemek: (i) "C_max'ta adıyla geçen ve listede yazılı olan", ya da (ii) "listede olmayan yeni kavram alt konuları 4. adıma gider (0 sa)". Hangisi seçilirse seçilsin, "Kalan risk" cümlesi buna göre yeniden yazılmalı.
- Saat ve derinlik kararlarını en çok değiştirecek iki düzeltme: 3b için birim tanımı (K3) ve kanıt ölçütü (K6). İkisi de bir cümleyle yazılabilir.

### Gaps
- 2026 S49'un ve 2026 S35'in metni görülemedi (MUR ve LOCOMOTIVE alan adları bu oturumda çözülmedi). K6'nın S49 kısmı bu yüzden MAKUL düzeyinde.
- "Doğrudan uygulama" ile "yeni kavram" arasındaki çizgi için ders kitabı içindekiler tablolarına yalnızca örnek düzeyinde bakılabildi: Valitutti, Amaldi ve bir lise programı. Sistematik bir tarama yapılmadı.

## 2. Test konuları kurallardan geçirildiğinde her biri tek ve makul bir sonuç alıyor mu?

### Takeaway
42 konu adım 1 → 5 sırasıyla uygulandı. 19'u tek ve makul bir sonuç aldı (✓). 9'u tek sonuç aldı ama bu sonuç yazılmamış bir yargıya dayanıyor (~). 14'ünde birden fazla sonuç çıkıyor ya da sonuç tanımla çelişiyor (✗). Adım sırası birçok çakışmayı çözüyor: bağ enerjisi, parabolün tepe noktasıyla optimizasyon, viral döngüler, mantar ve protistler. ✗ ile işaretli konuların hepsi K1, K2, K3, K5, K6 ve K12'deki yapısal boşluklara düşüyor.

### Cited Findings
Kural metinleri: adım 1–4 (B satır 39–42), Sınır tanımı (B satır 10), 3b ve 3c (B satır 197–209), Daraltma araçları (B satır 51–79). Allegato A ve Indicazioni alıntıları AA ve IND'den alındı. "✓" tek ve makul sonuç, "~" tek sonuç ama yazılmamış bir yargıya dayanıyor, "✗" birden çok sonuç ya da tanımla çelişki demek.

| # | Konu | Kuralların yolu | Sonuç | Durum |
|---|---|---|---|---|
| 1 | Ozmotik basınç (π = iMRT) | Allegato A'da ve listelerde yok → adım 4 → 3c (j = zar taşınımı); dayanak Dir. 57 "proprietà colligative" (İkincil) | 3c ile, "koligatif özellik düzeyinde"; koşullu (B satır 209, 157) | ✓ Tanım gereği aynı zamanda "sınır" (bkz. K1), ama "kanıtsız + 3c" de aynı sonucu verdiği için sonuç değişmiyor. 3c'de iki derinlik ifadesi var ("j'nin gerektirdiği" ve "koligatif özellik düzeyi"); min() olarak okunmalı |
| 2 | Diğer koligatif özellikler (Raoult, ΔT_k, ΔT_d) | Adım 4 → 3c hedefi yok → 0 sa. Tanım: "Le soluzioni" + yeni kavram → sınır → 1 sa | 0 sa ya da 1 sa | ✗ K1. Valitutti'nin "Le proprietà delle soluzioni" bölümü derişim birimleri, koligatif özellikler, Raoult, ΔT_k/ΔT_d ve osmozu aynı bölümde işliyor ([Zanichelli, Valitutti concetti blu cap.17](https://online.scuola.zanichelli.it/concettimodelliblu-files/presentazioni/pdf/Valitutti_concettiblu_proprieta_soluzioni_cap17.pdf); [Valitutti Lineamenti cap.11](https://online.scuola.zanichelli.it/valituttilineamenti-files/powerpoint/valitutti_ppt_72087_c11.pdf)) |
| 3 | Hess yasası | Adım 3 ("ΔH ve ΔG hesapları", B satır 91) → 3b kanıtı yok → 3c hedefi yok | 0 sa (bağ enerjisinden tahmin adım 1'de kalır; REV C10) | ✓ Geri çekilmiş C10 okumasıyla tutarlı; bkz. 8. bölüm |
| 4 | Ksp (çözünürlük çarpımı) | Adım 1 ("Equilibri in soluzione acquosa", "solubilità") ya da Sınır "Gaz fazı ve heterojen denge" (çökelti–çözelti dengesi heterojendir) | Satır kanıtı (2025 S41) satırın tamamına yayılıyorsa T; alt öğe bazındaysa 1 sa | ✗ K3. "heterojen denge" Daraltma'da niteleyicisiz (B satır 73), 3b'de "sulu çözelti dışı" niteleyicili (B satır 204) |
| 5 | Tampon hesabı (Henderson–Hasselbalch) | Adım 1: "Soluzioni tampone", "Il pH", "Logaritmi"; $C_{max}$ s.346 "calcoli relativi" | T derinliği; çıpa 2025 S39 | ✓ |
| 6 | Radyoaktif bozunma | Bozunma türleri ve çekirdek denklemleri: adım 3 ("nükleer olaylar") → 0 sa. Yarılanma ömrü aritmetiği: adım 1 (üstel fonksiyon; IND s.340 "modelli di crescita o decrescita esponenziale") | İki alt öğe, her biri tek sonuç | ✓ |
| 7 | Evrensel kütleçekimi | Adım 3, kanıtlı (2025 S58) → 3b | En fazla 2 saatlik tanıma | ~ Kepler yasalarının da aynı 2 saate girip girmediği (K3) ve "tanıma"nın 2025 S58'deki g/16 hesabını kapsayıp kapsamadığı (K4) tanımsız |
| 8 | Açısal momentumun korunumu, eylemsizlik momenti | AA "Momento di una forza e momento angolare"; korunum adıyla yok. IND s.343 "l'affronto degli altri principi di conservazione" iki listede de yok | Adım 1 (T) ya da adım 4 (0 sa); tanıma göre sınır (1 sa) | ✗ K1. Amaldi momento angolare, momento d'inerzia ve korunumu aynı paragrafta işliyor ([Zanichelli, Amaldi Traiettorie cap.10 par.12](https://online.scuola.zanichelli.it/amalditraiettorieazzurro-files/approfondimenti/1/cap10_par12_Momento_angolare.pdf)); İtalyan giriş sınavı hazırlığında L = Iω ve korunum birlikte veriliyor ([testbuddy](https://testbuddy.it/blog/test-di-ammissione/momento-angolare-formule-e-conservazione-nei-test-.md)). Makul sonuç: adım 1 |
| 9 | Düzgün olmayan çembersel hareket | Sınır listesinde örnek olarak geçiyor (B satır 111); kanıt yok; 3c yok | 1 sa | ~ $C_{max}$ dayanağı bir yöntem cümlesi (s.342 "i moti saranno affrontati innanzitutto dal punto di vista cinematico"). Kural 1'e göre ("C_max'ta dayanağı yoksa matrise girmez", B satır 181) dayanak reddedilirse sonuç 0 sa (REV C6) |
| 10 | Kondansatörlü Ohm/Kirchhoff | Kararlı DC: adım 1 ("Principi di Kirchhoff", "condensatori"). RC zaman sabiti: listede yok, yeni kavram | Kararlı hal T; geçici rejim 0 sa ya da 1 sa | ✓ / ✗ (geçici rejim K1'e düşer) |
| 11 | AC'de etkin (RMS) değer; transformatör oranı | AA "Corrente continua e alternata", "Induzione elettromagnetica"; IND s.343 "induzione magnetica e le sue applicazioni"; listelerde yok | Adım 1 ya da adım 4 | ✗ K1 |
| 12 | Geometrik olasılık (alan oranı) | Listelerde yok. Belgenin olasılık ölçütü sayıma dayanıyor (B satır 66) | Matematikte adım 1 ya da adım 4; mantık bölümünde araç olarak serbest (adım 5, B satır 33) | ~ |
| 13 | Genetikte binom olasılığı | Dışlanan "olasılık dağılımları" → 3c (genetik) açıkça yazılı (B satır 207). Ayrıca sayımla ve AA "potenza n-esima di un binomio" ile çözülür | İki yol da "içeride" sonucunu veriyor | ✓ |
| 14 | Standart sapma | Sınır, kanıtsız, 3c yok | 1 sa | ✓ "diğer değişkenlik ölçüleri" içindeki açıklık (range), tanıma göre doğrudan uygulamadır; etkisi önemsiz |
| 15 | Polinom bölmesi, Ruffini | Adım 1 ("polinomi", "scomposizione in fattori"); $C_{max}$ s.338 "semplici casi di divisione con resto" | T, "semplici casi" tavanıyla | ✓ Ama Ruffini'nin asıl kullanımı (3. derece denklemi çarpanlarla çözmek) K2'ye düşüyor |
| 16 | Köklü denklem ve eşitsizlikler | Sınır, kanıtlı (2025 S48; kökün altında 2x olduğu cevap anahtarıyla sabit: [SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §4) | Dayanak derinliğinde T; çıpa var | ✓ |
| 17 | Logaritmada taban değiştirme | Adım 1 [Yorum] (B satır 61) | T | ✓ Ama gösterilen kanıt 2024 S49 yalnızca log₂ tanımını istiyor, taban değiştirmeyi değil ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2024). Okuma yöntemi kotanjantla çelişiyor (K2) |
| 18 | Kotanjant, sekant, kosekant | Sınır, kanıtsız | 1 sa | ✗ K2: logaritma satırındaki gerekçe uygulanırsa T |
| 19 | Konikler ve dışmerkezlik | Adım 1 (analitik konikler, "Luoghi geometrici"); sentetik inceleme dışlanan | e = c/a T; odak–doğrultman tanımı sınırda | ✓ |
| 20 | Skaler ve vektörel çarpım | IND s.338 bunları adıyla sayıyor; Dışlanan yalnızca "matris hesabı ile … doğrusal bağımlılık ve bağımsızlık" (B satır 89); "Vettori e operazioni sui vettori" adım 1 | T | ✓ "Momento di una forza" ve "Lavoro" ile tutarlı |
| 21 | Bitkilerde yaşam döngüleri | Adım 1 ("Cicli vitali"); çiçek anatomisi ve çift döllenme adım 3 ("bitki anatomi-fizyolojisi") | Bölünmüş sonuç | ~ Ayrım yazılı değil |
| 22 | Ekoloji, besin zincirleri | Adım 3 → kanıt yok → 0 sa | 0 sa | ✓ ("sınır komşusu" ifadesi için K14) |
| 23 | Mikroskobi | Sınır, kanıtsız → 1 sa. Büyütme hesabı "Dimensioni cellulari" üzerinden adım 1'e de okunabilir | 1 sa (büyütme T olabilir) | ~ K12 |
| 24 | Virüslerin çoğalması; bakteride gen aktarımı | Viral döngüler: adım 1 ("I virus"), Sınır'daki "Mikroorganizmalar"dan önce gelir. Konjugasyon ve transdüksiyon: "Il DNA dei procarioti" (adım 1) ya da "Mikroorganizmalar" (1 sa). Mantarlar ve protistler: adım 2 (sınır) adım 3'ten (biyoçeşitlilik) önce → 1 sa | Viral T; bakteriyel gen aktarımı belirsiz | ✓ / ~ |
| 25 | Gelişim, embriyoloji | Sınır "Gelişim" (dayanak "Cicli vitali", "Riproduzione"), kanıtsız → 1 sa. İnsan embriyolojisi "apparati nell'uomo" (üreme sistemi) üzerinden adım 1'e de girebilir | 1 sa ya da T | ✗ K12 |
| 26 | İnsan üremesi | Adım 1 ("Riproduzione", "apparati nell'uomo") | T | ✓ |
| 27 | Enzim kinetiği (Michaelis–Menten, Km, Vmax) | Listelerde yok; yeni kavram. Çıpa 2025 S20 kavramsal (inhibitör ve substrat aktif bölge için yarışır), Km/Vmax istemiyor ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2025) | Adım 4 (0 sa) ya da sınır (1 sa); derinlik rejimi de belirsiz (K8) | ✗ K1, K8 |
| 28 | Bohr modeli | Sınır (Kimya), kanıtsız → 1 sa; enerji düzeyi hesabı dışlanan; kabuklar ve orbitaller adım 1 | 1 sa / 0 / T | ✓ Üç yerdeki ifade (B satır 90, 117) tutarlı |
| 29 | Kuantum sayıları | Adım 1 ("struttura elettronica degli atomi"; B satır 90 "orbitaller ve elektron dizilimi … kapsamdadır") | T | ✓ Adıyla yazılması iyi olur |
| 30 | Çekirdek bağlanma enerjisi | Adım 3 ("kütle-enerji eşdeğerliği ve nükleer olaylar") | 0 sa | ✓ Kimyadaki "Energia di legame" ile karışmıyor |
| 31 | Göreli hız, Galile dönüşümü | Göreli hız: adım 1 (2025 S55). Galile: Sınır, kanıtlı (2026 S49) → satırın tamamı T | T | ~ K6: S49'un kanıt değeri şüpheli; değilse satır 1 saate düşer |
| 32 | Bağımsız olaylarda çarpım kuralı | Sınır, kanıtlı (2024 S50) → T | T | ✗ K6 |
| 33 | Hardy–Weinberg | Adım 1 ("Le basi genetiche dell'evoluzione") | T | ~ [Yorum] yazılmamış |
| 34 | Kütle merkezi; kendi ağırlığı olan çubukta tork dengesi | Denge adım 1 (B satır 70); kütle merkezi Sınır, kanıtsız; 3c koşulları sağlanıyor | 1 sa (listeye göre) ya da denge probleminin derinliği (3c'ye göre) | ✗ K5 |
| 35 | Hayvanlarda karşılaştırmalı sistem fizyolojisi | "nell'uomo" sistem düzeyini kesiyor (B satır 58); hiçbir listede yok → adım 4 → 0 sa. Tanıma göre sınır → 1 sa. Ü7 kurbağayı "genel tanıma" düzeyinde okutuyor (B satır 188) | 0 sa / 1 sa / "genel tanıma" | ✗ K2 |
| 36 | 3. derece ve iki-kareli denklemleri çarpanlarla çözmek | "di primo e secondo grado" belirteci keser; "scomposizione in fattori" adım 1'e alır; listede yalnızca "çözüm sayısı" (s.340) var | T ya da 0 sa | ✗ K2 |
| 37 | Kinetik teori (ortalama kinetik enerji ∝ T) | Adım 3 → 0 sa | 0 sa | ✓ |
| 38 | Parabolün tepe noktasıyla optimizasyon | Adım 1 ("massimi e minimi", parabol) "optimizasyon" dışlamasından önce gelir | T | ✓ Sıra çözüyor |
| 39 | Entropi | "Primo e secondo principio della termodinamica"; listelerde yok | Adım 1 büyük olasılıkla; adım 4 de okunabilir | ~ K1 |
| 40 | PCR, elektroforez, CRISPR | Adım 1 ("la tecnologia del DNA ricombinante e le sue applicazioni") | T | ✓ Bir liceo scientifico 5. sınıf programı bunları DNA ricombinante başlığı altında işliyor ([Liceo Fermi Bologna, programma 5E 2021/22](https://www.liceofermibo.edu.it/wp-content/uploads/2022/01/PROGRAMMA-SVOLTO-GRIECO-fine-anno-2021-2022-5E.pdf); [Sadava, B6 "Biotecnologie: tecniche e strumenti"](https://online.scuola.zanichelli.it/carbonioenzimidna-files/posca/Sadava_Posca_Soluzioni_B6.pdf)). Belirteç fiilen hiçbir şeyi dışarıda bırakmıyor |
| 41 | Poiseuille yasası (gerçek akışkanda akış) | "Forze viscose nei fluidi reali" yalnızca adı anıyor (B satır 68); listelerde yok | 0 sa ya da 1 sa | ✗ K2 |
| 42 | Mitokondriyal ve Y'ye bağlı kalıtım | Belirteç "malattie ereditarie autosomiche e legate al cromosoma X" keser; açık başlık "modelli di ereditarietà" geri alır | T ya da 0 sa | ✗ K2 |

### Inferences
- Adım sırası gerçek bir çözüm aracı. Sınır listesinin Dışlanan listesinden önce gelmesi (24), 1. adımın listelerden önce gelmesi (3, 38) çakışmaları tek sonuca bağlıyor. Bunlar bulgu değil.
- Belirsiz kalan konuların hepsi şu üç gruptan birine giriyor: (a) listede olmayan yeni kavram alt konuları (2, 8, 10, 11, 27, 39 → K1); (b) kesilen kısmı sınıflandırılmamış belirteçler (35, 36, 41, 42 → K2); (c) adım 1 ile bir sınır satırının çizgisi (23, 25, 34 → K5, K12).
- Öğretmen gözüyle, sonuçların "makul" olup olmadığına dair: kuralların 0 saat verdiği koligatif özellikler, açısal momentumun korunumu ve 3. derece denklemlerin çarpanlarla çözümü İtalyan lise ders kitaplarında başlık düzeyinde yer alıyor. Bu konuların Allegato A'daki adı geçen bir başlıkla aynı bölümde işlendiği kaynakla görüldü (koligatif özellikler, açısal momentum). 2024–2026 kitapçıklarında bu konulardan soru görülmedi ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §6). Bu yüzden risk düşük, ama sonuç kuraldan değil, yazılmamış bir yargıdan çıkıyor.

### Gaps
- 3. derece denklemler, Poiseuille, RMS ve kalıtım modelleri için ders kitabı içindekiler tablosu bu oturumda açılmadı; "standart lise içeriği" değerlendirmesi kaynaksız bir çıkarımdır.
- IMAT'ın Cambridge dönemindeki (≤2023) sorularında koligatif özellik, açısal momentum ya da Hardy–Weinberg sorusu çıkıp çıkmadığı aranmadı; eşleme penceresi zaten 2024–2026.

## 3. Matris formülü Kural 1–3 metniyle tutarlı mı?

### Takeaway
Formül, giren ve girmeyen öğe kümesi bakımından Kural 1–3 ile tutarlı. Kanıtlı sınır öğeleri $M_3$ üzerinden, tanıma katmanları $E_{3b}$ üzerinden, 3c öğeleri $\mathrm{cl}_r$ üzerinden giriyor; kanıtsız dışlanmış öğe hiçbir yoldan girmiyor. Dört biçimsel sorun var ve hiçbiri bugün bir kararı değiştirmiyor (K10). Derinlik formülü yalnızca $M_3$ öğelerini kapsıyor; iki yoldan giren öğenin derinliği tanımsız.

### Cited Findings
- Formül: "$M_{teori} = M_3 \cup ((\mathrm{cl}_r(M_3) \cup E_{3b}) \cap C_{max})$"; "$\mathrm{cl}_r$: r(j,k) bağımlılık ilişkisine göre kapanış (Kural 3c)"; "$M_3$: … kanıtlı sınır öğeleri de dayanakları üzerinden buraya girer" — [B satır 168–174](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- 3c: "$M_3$'te açıkça yazmayan bir k konusu, **$M_3$'teki bir j hedefini** çözmek için zorunluysa ve $C_{max}$'ta dayanağı varsa matrise girer; yalnızca j'nin gerektirdiği derinlikte." — [B satır 206](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- İlke: "Kural 3c (**bir Allegato A hedefini** çözmek için zorunlu araç bilgisi)" — [B satır 25](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- "Çekirdek $M_3$'tür" (Kural 1, B satır 179) ↔ "bilim sorularının 9'u … **çekirdek dışından** geldi; 7'si sınır türünden" (B satır 45) ↔ kanıtlı sınır öğeleri $M_3$'tedir (B satır 170) — [B](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- "2027 DM'si yayımlandığında $M_3$ farkı alınır ve matris yeniden çalıştırılır." — [B satır 3](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- "**Derinlik (her öğe için tek):** Kural 2a niteleyicisi varsa üst sınırdır; bunun içinde $d = \min(d_T, d_{C_{max}})$; $C_{max}$'ta karşılığı olmayan $M_3$ öğesinde $d = d_T$." — [B satır 172](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- Adım 3: "Sınavda sorulmuşsa … Kural 3b'deki tanıma katmanı açılır; araç olarak gerekiyorsa Kural 3c ile o hedefin istediği derinlikte girer." İki durum arasında öncelik yok. Adım 2'de ise sıra açıkça yazılı ("kanıtlıysa … ; kanıtsız ama Kural 3c … ; ikisi de yoksa …") — [B satır 40–41](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- 3c ΔG örneğinde "Kanıt: 2025 S30 … ve 2024 S17" yazıyor; 3b ise "Kanıt kararı yalnızca bu eşlemeye dayanır" diyor ve "2024'te dışlanmış bir konudan … soru yoktur" — [B satır 203–208](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>). 2024 S17 ATP hidrolizini "exergonic" diye sınıflandırıyor ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2024; [LOCOMOTIVE 2024](https://thisislocomotive.com/imat-2024-worked-solution/)).

**K10 — biçimsel sorunlar (DOĞRULANDI; bugün karar etkisi yok)**
1. **Geçişli kapanış ile tek adımlı kural.** $\mathrm{cl}_r$ bir kapanış, yani zincirleri de alır: k₂ → k₁ → j. 3c metni ise j'nin $M_3$'te olmasını şart koşuyor. Yalnızca k₁'in ihtiyaç duyduğu bir k₂ (k₁ ∉ $M_3$) formülde içeri girer, metinde girmez. Kapanış kesişimden önce alındığı için, $C_{max}$ dışındaki bir k₁ üzerinden ulaşılan k₂ de girer (REV C8). Bugünkü 3c örneklerinin hepsi doğrudan $M_3$'e bağlı, gerçek bir zincir yok.
2. **j'nin tanım kümesi.** İlke "Allegato A hedefi" diyor, 3c "$M_3$'teki j" diyor; Belge 2'de $M_3$ kanıtlı sınır öğelerini de içeriyor. Örnek: j = üre döngüsü (kanıtlı sınır), k = transaminasyon (kanıtsız sınır). Belge 2'ye göre 3c ile j'nin istediği derinlikte girer (1 saat tavanı yok); Belge 1 İlke'ye göre 3c uygulanmaz, 1 saat alır.
3. **"Çekirdek" ve $M_3$ anlam kayması.** Kural 1'e göre çekirdek $M_3$, Belge 2'ye göre kanıtlı sınır öğeleri $M_3$'te. O hâlde 7 sınır sorusu çekirdekten gelmiş olur; "Kalan risk" ise çekirdek dışından geldiklerini söylüyor. Ayrıca "$M_3$ farkı" 2027 DM'si çıkınca alınacak; bu fark, Allegato A metnindeki değişikliklerle kanıttan türeyen öğeleri birbirine karıştırır (REV C8'in ikinci yarısı sağ kaldı).
4. **Derinlik formülünün kapsamı.** Formül "her öğe için tek" diyor ama yalnızca $M_3$ öğelerini tanımlıyor. cl_r öğelerinin derinliği 3c'de ("yalnızca j'nin gerektirdiği"), $E_{3b}$ öğelerinin derinliği yalnızca saat olarak 3b'de veriliyor. Hem kanıtlı dışlanmış hem 3c aracı olan bir öğe iki yoldan girer ve iki derinlik tanımı alır; birleştirme kuralı yok. Bugünkü 3b listesinde böyle bir öğe yok. Ama 3c ΔG örneğindeki "Kanıt:" etiketi, S17 ve S30'un 3b kanıtı sanılmasına yol açabilir. O okumada ΔG tam olarak bu çift girişli duruma düşer ve "2024'te dışlanmış bir konudan soru yoktur" cümlesi yanlış olur. Doğru okuma S17 ve S30'u "Bioenergetica / l'ATP" altında, yani $M_3$ içinde sayar.

### Inferences
- $E_{3b} \cap C_{max}$ fazlalık ama zararsız. Dışlanan öğeler tanım gereği "$C_{max}$'ta olup $M_3$'te olmayan" konulardır (Kural 3a), sınır öğelerinin her birinin de bir $C_{max}$ sayfası var. Tek istisna C6 (konu 9).
- Öneri: $M_3^{AA}$ (Allegato A ve [Yorum]) ile $M_3 = M_3^{AA} \cup S_{kanıtlı}$ ayrımı yapılmalı. 3c "j ∈ $M_3$" diye yazılmalı ve formülde $\mathrm{cl}_r$ yerine tek adımlı $r(M_3) \cap C_{max}$ kullanılmalı; ya da kapanış $C_{max}$ içinde tanımlanmalı. 3c'deki "Kanıt:" kelimesi "Sınav örneği ($M_3$ içinde):" ile değiştirilmeli.

### Gaps
- Bugünkü 3c örneklerinde iki adımlı bir zincir bulunamadı. Ozmotik basıncın "koligatif özellik düzeyinde" girmesi bir zincir gibi görünüyor, ama ozmotik basınç zaten bir koligatif özelliktir, yani ayrı bir k₂ yok.

## 4. Derinlik kuralı: çıpa, 2a niteleyicisi ve $C_{max}$ çatışırsa ne olur?

### Takeaway
Biçimsel olarak çatışabilirler ve çatışırlarsa ne olacağı yazılı değil. Çıpa "alt sınır", 2a niteleyicisi ve $C_{max}$ "üst sınır". Alt sınır üst sınırı aşarsa uygun derinlik kalmaz. Ayrıca derinlik formülü çıpayı içermiyor: $d = \min(d_T, d_{C_{max}})$, $d_{C_{max}}$ küçükse çıpanın altına inebilir. Bugünkü çıpalarda böyle bir çatışma bulunmadı. Tek örnek olan redoks denkleştirmede belge, 2a niteleyicisinin ("semplici") kapsamını sınav kanıtıyla genişletiyor; yazılmamış bir öncelik kuralı bu (K9). Ek olarak kanıtlı sınır öğesinin derinliği iki yerde farklı tanımlanmış (K7) ve iki başlık altına düşen öğede hangi 2a rejiminin geçerli olacağı belirsiz (K8).

### Cited Findings
- "çıpa alt sınırdır, üst sınırı Kural 2a ve $C_{max}$ koyar" — [B satır 189](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>); "Derinlik niteleyicisi varsa sınır kesindir." — [B satır 184](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- "**Derinlik niteleyicileri (kesin sınır).**" ve aynı maddede: "'bilanciamento di semplici reazioni' sınavda redoks ve disproporsiyonlaşma denkleştirmesine kadar uzanır [Kanıt: 2026 S34, S39, S40]" — [B satır 51–53](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>). "Disproporsiyonlaşma" kaynaklarda adıyla geçmiyor ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2026).
- 3b: "Kanıt kararı yalnızca bu eşlemeye dayanır ve Allegato A merkezli ilkeyi değiştirmez." — [B satır 203](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- Kanıtlı sınır derinliği, birinci tanım: "o dayanağın derinliğinde T ile çalışılır" (B satır 198); "kanıtlıysa Allegato A dayanağının derinliğinde çalışılır" (B satır 40). İkinci tanım: öğe $M_3$'te (B satır 170) ve "her öğe için tek" formül $d = \min(d_T, d_{C_{max}})$ (B satır 172) — [B](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- Çarpım kuralının dayanakları: "'Probabilità e frequenza', 'Cenni di calcolo combinatorio'" (B satır 100); "Cenni" bir 2a niteleyicisi (B satır 52). Üre döngüsünün $C_{max}$ dayanağı s.346 "funzioni metaboliche **di base**" — [IND s.346](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/pdf/ind.txt>). 2025 S25 yalnızca döngünün nerede gerçekleştiğini soruyor ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2025).
- Çapraz başlıklar: biyolojide "Il ruolo degli enzimi", "Le molecole organiche presenti negli organismi", "Reazioni di ossidoriduzione nei viventi" (niteleyici yok); kimyada "Elementi di cinetica chimica e catalisi", "Fondamenti di chimica organica", "Elementi di nomenclatura", "Bilanciamento di semplici reazioni" (niteleyicili) — [AA s.2–3](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/pdf/allA.txt>). "Biyolojide niteleyici olmadığı için derinlik daima c) dalındadır" — [B satır 187](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- Çıpaların üst sınırla karşılaştırması:
  - 2024 S58 bir "hangisi yanlıştır" sorusu ve r ile T formüllerini tanımayı istiyor; hesap istemiyor. Çıpanın "yarıçap ve periyot" ifadesi ve Sınır satırındaki "nicel düzeyde" ifadesi kanıtın üstünde ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2024; [LOCOMOTIVE 2024](https://thisislocomotive.com/imat-2024-worked-solution/)).
  - 2024 S59'un metni görülemedi; konusu kaynaklar arasında çelişkili ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2024).
  - 2025 S20 kavramsal ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2025).
  - 2026 S58 kombinasyonla çözülüyor (C(7,2)/C(12,2) = 7/22), yani "Cenni" içinde kalıyor ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2026).

**K9 (DOĞRULANDI; bugün etki yok).** Çıpa üst sınırı aştığında ne olacağı yazılı değil. Belge 1 aynı maddede hem "kesin sınır" hem "sınavda … kadar uzanır" diyor; fiilen kanıt 2a'yı genişletiyor. Bu, "Kanıt kararı … Allegato A merkezli ilkeyi değiştirmez" cümlesiyle gerilim yaratıyor. 2027 sınavı kanıta eklendiğinde, örneğin "calcoli stechiometrici elementari"yi aşan bir hesap gelirse, hangi kuralın uygulanacağı belirsiz.
- **Çürütme denemesi:** "Redoks 2a'yı aşmıyor; 'semplici reazioni' redoksu zaten içerir." Bu doğru olabilir. Ama o zaman "[Kanıt: …]" etiketi okumanın dayanağı olmaktan çıkıp yalnızca destek olur. Genel kural yine eksik. Sağ kaldı; etkisi yalnız ifade ve gelecek.

**K7 (DOĞRULANDI, biçimsel; Derinlik, düşük).** Kanıtlı sınır öğesi "dayanağın derinliği"ni alıyor, ama aynı öğe $M_3$'te olduğu için kendi $\min(d_T, d_{C_{max}})$ değerini de alıyor. İki değer şu durumlarda ayrılır:
- Dayanakta 2a niteleyicisi varsa. Çarpım kuralı "Cenni" tavanını devralır mı?
- Öğenin kendi $C_{max}$'ı sığsa. Üre döngüsü "di base"; dayanak ise sistem fizyolojisi.
- Birden çok dayanak varsa. Hangisinin derinliği alınır?

Ek not: 2025 S25 yalnızca yer bilgisi istiyor, ama 3b kuralı üre döngüsüne tam dayanak derinliği veriyor; derinlik kanıtın çok üstünde.

**K8 (MAKUL; Derinlik, düşük–orta).** Enzim katalizi, aktivasyon enerjisi, biyomolekül yapısı (stereokimya, adlandırma) ve metabolizmadaki redoks hem biyolojide (T) hem kimyada (2a tavanı) başlık sahibi. "Her öğe için tek" derinlik ister, ama hangi başlığın geçerli olacağı yazılı değil. "Glikoliz ve Krebs ayrıntısı" çıpası biyoloji rejiminin geçerli olduğunu ima ediyor, ama kural bunu söylemiyor.
- **Çürütme denemesi:** "Öğe hangi bölümde soruluyorsa o bölümün kuralı geçerli." Belgede böyle bir cümle yok. Ayrıca derinlik sorudan önce, çalışma planında belirleniyor. Sağ kaldı.

**K11 (Yalnız ifade).** Adım 1: "derinlik niteleyicisi varsa o sınırdır; yoksa T belirler, $C_{max}$ sınırlar" (B satır 39). Bu cümle, niteleyici varken T'nin belirlemediğini ve $C_{max}$'ın sınırlamadığını ima ediyor. Formül ise "bunun içinde $d = \min(d_T, d_{C_{max}})$" diyor. Formüldeki son yan cümle ("$C_{max}$'ta karşılığı olmayan $M_3$ öğesinde $d = d_T$") 2a tavanını da düşürüyormuş gibi okunabilir. Kural 1 ise "derinliği Allegato A ifadesi ve T belirler" diyor (B satır 180).

### Inferences
- Önerilen tek cümle: "Çıpa 2a ya da $C_{max}$ tavanını aşarsa çıpa geçerlidir ve tavan, çıpanın gerektirdiği düzeye kadar genişlemiş okunur; bu yalnızca 3b eşleme penceresindeki sorular için geçerlidir." Ya da tersi yazılmalı. Hangisi seçilirse seçilsin, formüle $d = \max(\text{çıpa}, \min(\ldots))$ biçiminde girmeli.
- Kanıtlı sınır için: "derinlik = öğenin kendi $\min(d_T, d_{C_{max}})$ değeri; dayanaktaki 2a niteleyicisi devralınmaz", ya da açıkça tersi.
- Çapraz başlık için: "Bir öğe hem niteleyicisiz bir biyoloji başlığına hem niteleyicili bir kimya başlığına bağlıysa, …" kuralı yazılmalı.

### Gaps
- 2024 S59'un tam metni görülmedi. Hız x(t)'den türevle mi, düzgün çembersel hareketin izdüşümüyle mi isteniyor bilinmiyor. Türev gerekiyorsa çıpa dışlanan bir konuyu (türev) gerektirir. İzdüşüm yöntemiyle çatışma yok.

## 5. Kural 3b: saat bütçesi öğe başına mı satır başına mı? Kanıtlı dışlanmış ve 3c ile gereken öğeye ne olur?

### Takeaway
Birim tanımlı değil (K3) ve bu, saatleri birkaç kat değiştirebiliyor. Bir satırın içinde farklı kanıt durumları var (metabolizma satırı). Açık sınıflar ("ve diğer …", "dışındaki …") alt öğe bazında okunursa sınırsız sayıda 1 saatlik katman üretir. Kanıtlı satırlar satır bazında okunursa kanıtsız komşuları T derinliğine çıkar. "Tanıma katmanı"nın içeriği de tanımsız (K4). Kanıtlı dışlanmış ve aynı anda 3c ile gereken öğe için birleştirme kuralı yok; bugünkü listede böyle bir öğe yok (K10/4).

### Cited Findings
- "Kanıtsız sınır öğesi (3c bağımlılığı da yoksa): en fazla 1 saatlik tanıma katmanı ($E_{3b}$). Kanıtlı dışlanmış öğe: en fazla 2 saatlik tanıma katmanı ($E_{3b}$)." — [B satır 199–200](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- "Tanıma katmanlarının kapsamı ve süreleri yalnızca burada tanımlıdır." — [B satır 197](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>); "$E_{3b}$: … hangi öğelerin alacağı ve süreleri yalnızca Kural 3b'de yazılıdır." — [B satır 174](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- Biçim: "konu ($C_{max}$ sayfası; Allegato A dayanağı; kanıt durumu)" (B satır 97). Tek madde işaretinde karışık kanıt: "Biyoenerjetik listesi dışındaki metabolik yollar …: üre döngüsü (kanıt: 2025 S25); β-oksidasyon ve transaminasyon (kanıt yok …)" (B satır 119). Çok öğeli madde işaretleri: "Kotanjant, sekant, kosekant"; "Fonksiyon olarak |x|, parçalı doğrusal fonksiyonlar ve doğru demetleri"; "Gaz fazı ve heterojen denge, Le Chatelier"; "Dalton, Bohr ve diğer tarihsel atom modelleri"; "Standart sapma ve diğer değişkenlik ölçüleri" — [B satır 99–122](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- Dışlanan satırları ile 3b kanıtı: "evrensel kütleçekimi ve Kepler yasaları (s.343 …)" ↔ "2025 S58 evrensel kütleçekimi"; "dalgalar ve ses (s.343 …)" ↔ "2026 S54 dalgaların koherensi" — [B satır 90, 204](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- 2025 S58 bir hesap sorusu (g/16, h = 3R), 2026 S54 kavramsal (sabit faz farkı) — [REV](</home/user/imat-2027-calisma/inceleme/belge-1-2-dogrulama-2026-10-10.md>) F tablosu; [SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2025–2026
- 2025 S41: FeCl₃/FeCl₂(k) + Cl₂(g), yani katı–gaz heterojen dengesi — [REV](</home/user/imat-2027-calisma/inceleme/belge-1-2-dogrulama-2026-10-10.md>) E tablosu

**K3 (DOĞRULANDI; Saat + Derinlik, orta).** Üç okuma üç ayrı sonuç veriyor:

| Durum | Madde işareti birimi | Alt öğe birimi | Açık sınıf birimi |
|---|---|---|---|
| Metabolizma satırı | Üre döngüsü kanıtlı olduğu için satırın tamamı T: β-oksidasyon, transaminasyon, glukoneogenez, glikojen metabolizması… Bu, belgenin açıkça yazdığı "kanıt yok" ile çelişir | Üre döngüsü T, β-ox 1 sa, transaminasyon 1 sa; adı geçmeyen her yol için ayrıca 1 sa (sınırsız) | Tamamı için 1 sa |
| Gaz/heterojen denge (kanıt katı–gaz) | Homojen gaz dengesi (Kp/Kc), Ksp, Le Chatelier: hepsi T | Yalnızca katı–gaz T; homojen gaz dengesi ve Ksp 1 sa | — |
| Kütleçekimi satırı | Kepler yasaları da 2 saatlik katmanda | Yalnızca kütleçekimi 2 sa; Kepler 0 sa | — |
| Dalgalar satırı | Dalgalar ve ses 2 sa | Yalnızca koherens 2 sa | — |
| Kotanjant, sekant, kosekant | 1 sa | 3 sa | — |

- **Çürütme denemesi:** "Birim doğal olarak madde işaretidir." Ama o zaman metabolizma satırında belgenin kendi "kanıt yok" yazdığı öğeler T derinliği alır. Belge bu satırda alt öğe birimini fiilen kullanıyor. Sağ kaldı.

**K4 (DOĞRULANDI; Derinlik, düşük–orta).** 3b, tanıma katmanının "kapsamı"nın orada tanımlandığını söylüyor. Ama yalnızca hangi öğenin katman alacağını ve saat tavanını veriyor. Katmanın içeriği (tanım ve terim mi, formülü tanıma mı, tek adımlı hesap mı) yazılı değil. Kanıtlı dışlanmış kütleçekimi sorusu hesap istiyordu (g/16). İçerik "tanım ve terim" diye okunursa, 2 saatlik katman kendi kanıt sorusunu karşılamayabilir.
- **Çürütme denemesi:** "'Kapsamı' kelimesi 'hangi öğelerin alacağı' anlamında." Öyle okunursa iddia (d) düşer, ama içerik boşluğu (b) kalır. Sağ kaldı (b).

**Kanıtlı dışlanmış + 3c.** Adım 3 iki yolu da açıyor ama öncelik ya da birleştirme kuralı vermiyor (bkz. K10/4). Bugün böyle bir öğe yok. Gerçekçi adaylar 3c ile gelen ama kayıtlı olmayan bağımlılıklar. Göz fizyolojisi (adım 1) miyopi düzeltmesinde geometrik optiğe (dışlanan) ihtiyaç duyabilir; kulak fizyolojisi frekans ve şiddet için ses dalgalarına. Dalgalar 3b'de kanıtlı (koherens). O durumda "dalgalar" hem 2 saatlik katman hem 3c derinliği alır ve hangisinin geçerli olacağı tanımsız.

**K5 (MAKUL; Derinlik, düşük).** Belge 1 dengeyi kapsama alıyor: "Cisimlerin dengesi (ΣF = 0, Στ = 0) kapsamdadır" (B satır 70). Kendi ağırlığı olan bir çubuğun tork dengesi, ağırlığın kütle merkezine uygulanmasını gerektirir. Kütle merkezi Sınır listesinde "kanıt yok" diye duruyor (B satır 113) ve 3c notu yok. Koşullu olasılık satırında ise "genetik problemlerinde Kural 3c ile girer" diye yazılmış (B satır 101). Listeyi okuyan 1 saat verir; 3c'yi uygulayan denge probleminin istediği derinliği verir.
- **Çürütme denemesi:** "Simetrik cismin ağırlık merkezi zaten 'forza peso'nun doğrudan uygulaması; sınır satırı yalnızca cisim sistemlerini ve kütle merkezinin hareketini kapsar." Savunulabilir, ama bu ayrım yazılı değil. MAKUL olarak sağ kaldı.

### Inferences
- Önerilen tanım: "3b'de öğe, Sınır veya Dışlanan listesindeki bir madde işaretidir. Madde işaretinde alt öğe başına kanıt yazılıysa birim alt öğedir. 've diğer …' ya da '… dışındaki …' sınıfları tek öğe sayılır." Kanıtlı dışlanmış katmanın, kanıt sorusunu çözecek düzeyi içerdiği de yazılmalı.
- Sınır listesine bir alan daha eklenmeli: "3c: var (j = …) / yok". Böylece adım 2'nin üç dalı listeden okunabilir.

### Gaps
- Bir lise ders kitabının "tanıma" düzeyini nasıl tanımladığına dair dış kaynak aranmadı; bu bir tasarım kararı.

## 6. "Kalan risk" ifadeleri 3b listesi ve tanımlarla tutarlı mı?

### Takeaway
Aritmetik doğru: 2 + 5 + 2 = 9; 7 sınır, 2 dışlanan. Ama sayılar tanımlanmamış bir "kanıt" ölçütüne dayanıyor. Belgenin kendi olasılık ölçütü 2024 S50'yi kapsama alıyor. "Çözülebilir" ölçütü seçilirse 2026 S58 koşullu olasılık için kanıt sayılır. Belge ikisinde ters yönde karar vermiş. Ölçüt hangisi olursa olsun bir sınıflandırma yanlış çıkıyor (K6, DOĞRULANDI). 2026 S49 da belgenin 2025 S55 emsaline göre büyük olasılıkla kapsam içi (MAKUL). Ayrıca "sınır türü riski kanıtsız sınır hükmüyle karşılanır" cümlesi yalnızca listelenmiş öğeler için doğru (K1).

### Cited Findings
- "2024–2026'da bilim sorularının 9'u (yılda 2–5) çekirdek dışından geldi; 7'si sınır türünden, 2'si dışlanan fizik bloğundan (s.343). Bu konuların hiçbiri sonraki yıllarda tekrar etmedi. … Bu riskin sınır türü kısmının nasıl karşılanacağını Kural 3b'nin kanıtsız sınır öğesi hükmü belirler" — [B satır 45](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- Olasılık ölçütü: "olumlu/olası durum sayımı ve kombinasyonla çözülebilen çekiliş problemleri kapsamda okunur [Yorum; kanıt: 2026 S58]. Bağımsız olaylarda çarpım kuralı ve koşullu olasılık … ikisi de sınırdadır." — [B satır 66](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- "Koşullu olasılık (s.341; aynı dayanak; **kanıt yok**; genetik problemlerinde Kural 3c ile girer)" — [B satır 101](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- 3b listesi: "2024 S50 iadeli çekiliş, bağımsız olaylarda çarpım kuralı (sıralı sayımla da çözülür)"; "2026 S49 Galile dönüşümlerinin geçerli olduğu göreli hareket" — [B satır 204](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>); "basit göreli hız da kapsamdadır [Kanıt: 2025 S55]" — [B satır 69](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- 2024 S50: 3 kırmızı, 7 yeşil top, iadeli iki çekiliş; P(iki yeşil) = 49/100. 10 × 10 sıralı sonucun 49'u olumlu — [SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §5; [LOCOMOTIVE 2024](https://thisislocomotive.com/imat-2024-worked-solution/)
- 2026 S58: iadesiz çekiliş; LOCOMOTIVE'in çözümü 7/12 × 6/11 = 7/22, yani ardışık koşullu çarpım; kombinasyonla C(7,2)/C(12,2) = 7/22 — [SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §3; [LOCOMOTIVE 2026 analizi](https://thisislocomotive.com/imat-2026-analysis-topics-difficulty-trends-locomotive/)
- 2026 S49: LOCOMOTIVE "Galile dönüşümlerine dayanan göreli hareket" diyor; metin görülemedi — [SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2026. Galile hız dönüşümü u′ = u − v'dir, yani basit göreli hızla aynı işlem — [Save My Exams, Galilean Relativity](https://savemyexams.com/dp/physics/hl/25/revision-notes/space-time-and-motion/galilean-and-special-relativity/galilean-relativity); [TutorChase, Galilean relativity](https://www.tutorchase.com/notes/ib/physics-2025-hl/1-5-2-galilean-relativity-and-transformations-hl-only)
- 3c: "Bağımsız olaylarda çarpım kuralı 3b kanıtıyla (2024 S50) zaten kapsamdadır." — [B satır 207](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)
- Kanıtın tek tanımı: "[Kanıt]: resmî MUR soru kitapçığındaki soru." Bir sorunun bir öğeyi "gerektirdiği" ya da "onunla çözülebildiği" ölçütü yazılı değil — [B satır 9](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>)

**K6 (S50/S58 kısmı DOĞRULANDI; S49 kısmı MAKUL; Kapsam + Saat + sayım, orta).**
- **"Gerektirir" ölçütüyle:** 2024 S50 sayımla çözülüyor, belgenin olasılık ölçütüne göre kapsamda. Çarpım kuralı için kanıt sayılmaz. Sonuçlar: çarpım kuralı "kanıtsız sınır + 3c (genetik)" olur, yani genetiğin istediği derinlikte girer; Kalan risk 9 → 8 (2024: 1; "yılda 1–5"); B satır 207'deki cümle yanlış olur.
- **"Çözülebilir" ölçütüyle:** S50 kanıt kalır. Ama 2026 S58 da koşullu çarpımla çözülebildiği için koşullu olasılığın kanıtı olur. Belge "kanıt yok" diyor. Sonuçlar: koşullu olasılık kanıtlı, dayanak derinliğinde T alır; 2026 sayısı 3 olur; olasılık 2024'ten 2026'ya tekrar ettiği için "hiçbiri tekrar etmedi" cümlesi bozulur.
- **Çürütme denemesi:** "S50'nin ayırt edici becerisi iadeyi fark etmek; bu bağımsızlığın kendisi." İadenin fark edilmesi 10 × 10 sıralı sayımda da aynı biçimde gerekiyor (çeldirici 42/90). Bağımsızlık kavramını ayrıca gerektirmiyor. Sağ kaldı.
- **S49:** Belgenin kendi tarifi ("Galile dönüşümlerinin **geçerli olduğu** göreli hareket") eylemsiz olmayan çerçeve ya da v ≪ c sınırı değil, sıradan göreli hareket anlatıyor. Soru u′ = u − v hesabıysa, belge 2025 S55'i kapsamda saydığı için S49 da kapsamdadır. O durumda "Referans sistemleri ve Galile göreliliği" kanıtsız olur ve madde işareti birimiyle T yerine 1 saat alır. REV C1'deki "karar etkisi yok" hükmü bu senaryoda tutmaz. Soru metni görülmeden kesinleşmez.
- **İlişkili:** 2026 S35 (kimyasal denge) gaz fazındaysa 3b listesinde eksik bir sınır sorusu var ve "tekrar etmedi" cümlesi bozulur ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §6).

### Inferences
- Önerilen ölçüt: "Bir soru, ancak kapsam içindeki araçlarla çözülemiyorsa bir sınır ya da dışlanan öğenin kanıtıdır." Bu ölçüt 2026 S58'deki kararı korur, 2024 S50'yi çıkarır ve S49'u metne bakmaya bağlar.
- "Kalan risk" cümlesi şu biçimde yazılmalı: "sınır türü riskin listelenmiş kısmını 3b karşılar; listelenmemiş yeni kavram alt konuları (K1) için risk 4. adımda kabul edilir". Şimdiki hâliyle cümle, K1'deki konuların da karşılandığını ima ediyor.
- Sayımın aralığı ölçüte göre 7–10 arasında değişiyor: S50 çıkar, S49 çıkabilir, S58 ve S35 girebilir. Kural 3b saatleri bu sayıya bağlı olmadığı için etki, sayımın kendisinde ve iki öğenin (çarpım kuralı, Galile) derinliğinde kalıyor.

### Gaps
- 2026 S49, S35 ve 2024 S59'un MUR metni görülemedi; MUR ve LOCOMOTIVE alan adları bu oturumda çözülmedi.

## 7. Var olmayan bölüme atıf, farklı şey söyleyen atıf ya da kuralların etkileşimi hakkında yanlış ifade var mı?

### Takeaway
Var olmayan bir bölüme ya da kurala atıf yok; bütün iç atıflar doğru yere gidiyor. Dört yerde iki atıf aynı şeyi farklı söylüyor: j'nin tanım kümesi (K10/2); niteleyicinin derinlikteki rolü (K11); "kapsamı burada tanımlıdır" (K4); "İkincil kalemler kararları etkilemez" (K13). "Sınır" tanımının listenin tamamlığı hakkındaki iddiası yanlış (K1). Kapsam belirteciyle kesilen kısmın sınıflandırılması yazılı değil ve tutarsız (K2). Ayrıca iki ifade sorunu var: "sınır komşusu" (K14) ve "Dış tanımlar" listesinde metin içinde tanımlanan T ve Ü7'nin de bulunması.

### Cited Findings
- **Atıf kontrolü (hepsi doğru):**
  - "(Belge 2, Kural 2)" → çıpalar (B satır 39 → 189).
  - "(Kural 2b)" → B satır 185.
  - "Kural 3b'nin kanıtsız sınır öğesi hükmü (Belge 2)" → B satır 199.
  - "(Belge 2, 3b kanıt listesi)" → B satır 204.
  - "Liste ifade bazlıdır (Belge 1, Daraltma araçları 1)" → B satır 51–53; içerik birebir aynı.
  - "(liste: Belge 1, 'Allegato A'da olmayan konular')" → B satır 83.
  - "(Kural 2c)" → B satır 162 → 186.
  - "Bohr modelinin statüsü Sınır listesinde (Kimya) yazılıdır" → B satır 117.
  - "Yukarıda 'sınırdadır' denen her öğe … Sınır listesinde" → sekiz "sınırdadır" ifadesinin sekizi de listede (metabolik yollar, köklü, kotanjant, çarpım kuralı, koşullu olasılık, hareket ve çerçeve türleri, Lorentz, gaz/heterojen denge).
  
  Kaynak: [B](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>).
- **K1:** Tanım: "Her sınır öğesinin $C_{max}$ sayfası, Allegato A dayanağı ve kanıt durumu 'Sınır listesi'nde yazılıdır" (B satır 10). Liste ise yalnızca "Indicazioni s.337–346'da olup Allegato A'da adıyla geçmeyen konular"dan kuruluyor (B satır 85). "Teknik ve mesleki belgelerdeki ek konular da aynı kurala tabidir" (B satır 85) cümlesinden sonra adım 4 geliyor: "Allegato A'da ve listelerde olmayan konu: Kural 3c bağımlılığı yoksa çalışılmaz" (B satır 42).
  - Koligatif özellikler bu durumun en açık örneği. Allegato A'da dayanakları var: "Le soluzioni … i principali modi di esprimere la concentrazione" ([AA s.3](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/pdf/allA.txt>)). Yeni kavram gerektiriyorlar: Raoult, K_k/K_d, molalite.
  - Belge kendi 3c'sinde bunlar için bir $C_{max}$ dayanağı veriyor (Dir. 57 "proprietà colligative"). O satır Trento 2013 kopyasında "Le soluzioni: percento in peso, molarità, molalità, proprietà colligative" olarak görüldü ([OM](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/okul_mufredati_belgeleri.md>) §4; [Vivoscuola Trento](https://www.vivoscuola.it/content/download/29031/685766/file/a73aefa681d398cc4865a5d86135664e.pdf)).
  - s.337–346'da "colligat" ya da "osmo" geçmiyor ([OM](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/okul_mufredati_belgeleri.md>) §2).
  - Sonuç: tanımın bütün şartlarını sağlıyorlar ama listede değiller. Adım 4 → 0 sa; tanım → 1 sa.
- **K2:** Logaritma satırı: "'Logaritmi (in base 10 e in base e)' iki tabanı adıyla anar ama diğerlerini dışlamaz … [Yorum: 'Funzioni elementari … logaritmiche' taban sınırı koymaz; kanıt: 2024 S49, log₂16]" (B satır 61). Hemen altında: "'Seno, coseno, tangente' (kotanjant, sekant ve kosekant sınırdadır)" (B satır 62). Genel kural: "Diğer sayımlar kapalıdır." (B satır 79). Allegato A'da "Funzioni elementari: … goniometriche" ve "Formule goniometriche" fonksiyon sınırı koymuyor ([AA s.3](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/pdf/allA.txt>)).
  - Logaritma için kullanılan gerekçe trigonometriye birebir uygulanabiliyor. Belge birinde kapsam, ötekinde sınır diyor. Fark yalnızca kanıt, oysa kanıt yalnızca sınır içinde kanıtlı/kanıtsız ayrımını yapmalı (B satır 203).
  - "Diğer sayımlar kapalıdır" kuralı "(in base 10 e in base e)"yi de kapalı yapar ve logaritma satırıyla çelişir.
  - Kesilen kısmın nereye gittiği tutarsız. Bazı kesilen kısımlar sınır listesinde: kotanjant, Lorentz, gaz dengesi, metabolik yollar, hareket türleri, köklü denklemler. Biri dışlanan listesinde: bitki dokuları, "bitki anatomi-fizyolojisi" altında. Bazılarının hiçbir yerde karşılığı yok:
    - "bu düzeyi hayvanlar için dışarıda bırakır" (B satır 58) ile kesilen hayvan sistem düzeyi; IND s.346 "vegetali e animali … aspetti anatomici"de geçiyor, yani s.337–346 içinde olduğu hâlde iki listede de yok;
    - "Equazioni … di primo e secondo grado" belirteci ile çarpanlarla çözülen 3. derece denklem;
    - "Forze viscose nei fluidi reali" sınırının ötesindeki akış (Poiseuille);
    - sekiz fonksiyonel grubun dışındakiler (alkil halojenürler);
    - "principali" derişim birimlerinin dışındakiler (molalite);
    - "malattie ereditarie autosomiche e legate al cromosoma X" belirteci ile açık "modelli di ereditarietà" başlığı arasında kalan Y'ye bağlı ve mitokondriyal kalıtım.
  - Ek olarak, Sınır tanımı yalnızca "yeni kavram" ölçütünü sayıyor. Kotanjant ise sınırda çünkü kapalı sayımla kesiliyor; yeni kavram olduğu için değil (cot = cos/sin).
- **K13:** "Tablodaki İkincil ve Doğrulanmalı kalemler sorumluluk kararlarını etkilemez; bütün sınır ve 3c dayanakları ekteki s.337–346'dadır." (B satır 157). Aynı tabloda: "D.P.R. 89/2010 ve D.I. 211/2010: İkincil (metin kopyaları; birincil metin kontrolü bekliyor)" ve "Eldeki s.337–346, ordinario'nun … kısımlarıdır" (B satır 143). Yani bütün sınır ve 3c dayanaklarını taşıyan sayfalar tablodaki İkincil kalemin kendisi. Ayrıca K1'deki konular için 3c dayanağı ancak teknik ve mesleki belgelerden gelebilir. Dir. 4/2012 "metni okunmadı (Doğrulanmalı)" (B satır 145). Cümle bu yüzden yalnızca bugün listelenmiş öğeler için doğru.
- **K14:** Dışlanan girişinde "Dışlananlarda parantez içindekiler Allegato A'da kalan dayanaklar." (B satır 85); ekoloji satırında "sınır komşusu: 'Ereditarietà e ambiente', 'Selezione naturale'" (B satır 92). "Sınır" tanımlı bir terim (B satır 10). Bu ifade, adı geçen iki $M_3$ konusunun Sınır listesi öğesi (1 sa) sanılmasına yol açabilir. Bu, geri çekilen C2'den ayrı bir noktadır; parantezin anlamı değil, terim çakışması.
- **Dış tanımlar:** "T, K-kodları, Ü7, Yardımcı ve B satırı bu metnin dışında tanımlıdır." (B satır 176). Oysa "T … = K1 + K5 + K4" (B satır 175) ve Ü7 (B satır 188) metin içinde tanımlanıyor. Yalnız ifade.
- **C5 (sağ kaldı, yalnız ifade):** "Kütlenin korunumu ve sabit oranlar yasası kapsamdadır [Yorum: stokiyometrinin doğrudan uygulaması; kanıt: 2024 S45 sınırlayıcı bileşen]" (B satır 77). 2024 S45 bir sınırlayıcı bileşen sorusu: 9 g C, 36 g O₂ ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2024). Sabit oranlar yasasını değil, stokiyometriyi kanıtlıyor.
- **C7 (sağ kaldı, yalnız ifade):** "Terim içindeki 'elementare', 'elemento' veya 'fondamentale' niteleyici değildir." (B satır 184). Aynı listede "calcoli stechiometrici elementari" ve "nozioni fondamentali sulle funzioni" niteleyici sayılıyor. "Terim içindeki" ifadesi ancak Daraltma 3'teki listeyle birlikte okunursa çözülüyor.
- **Yazılmamış ölçüt:** "Ortalama, ortanca ve tepe değer … önceki öğrenimden gelir; kapsamdadır" (B satır 127). "Önceki öğrenim" kurallarda bir kapsam ölçütü değil. Aynı ölçüt besin zincirlerini de (ortaokul fen konusu) kapsama çekebilirdi; ekoloji ise dışlanan. Asıl gerekçe olan doğrudan uygulama yeterli. Yalnız ifade.

### Inferences
- K1 ve K2 aynı onarımla kapanır: "Sınır öğesi = (i) yeni kavram gerektiren ya da (ii) bir kapsam belirteci veya kapalı sayımla kesilen, Allegato A'da dayanağı olan ve s.337–346'da (ya da tabloda adı geçen başka bir $C_{max}$ belgesinde) geçen konu. Listede olmayan böyle bir konu, listeye eklenene kadar 4. adıma göre işlenir." Kapalı sayım ile açık bir kardeş ifade çatışırsa hangisinin geçerli olacağı da bir cümleyle yazılmalı.

### Gaps
- Hayvan sistem düzeyinin "genel tanıma" (Ü7) ile "dışarıda" ("nell'uomo" [Yorum]) arasında nasıl bölüştürüleceği belgeden çıkarılamadı.

## 8. Denetlenip tutarlı bulunanlar ve geri çevrilen adaylar

### Takeaway
Kural sisteminin omurgası tutarlı. Adım sırası çakışmaları çözüyor. 3b'nin 2 × 2 durumu (sınır/dışlanan × kanıtlı/kanıtsız) ve 3c'nin önceliği adım 2'de eksiksiz. Formülün giriş kümesi Kural 1–3'le aynı. Yedi aday bulgu çürütme denemesinde düştü ve rapora alınmadı.

### Cited Findings
Tutarlı bulunanlar (hepsi [B](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/belgeler.md>), [AA](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/pdf/allA.txt>) ve [IND](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/pdf/ind.txt>) üzerinde kontrol edildi):
- Adım 2'nin üç dalı (kanıtlı → kanıtsız + 3c → kanıtsız), Belge 1'in giriş paragrafı (satır 85) ve 3b (satır 198–199) birbiriyle aynı.
- Adım 3 ile 3a, 3b ve 3c aynı. 3a'daki "∅", 3b yeniden açana kadar kanıtsız sınır öğelerini de kapsıyor; bu, 3b'deki ayrımla çelişmiyor.
- Kural 1'deki "kanıtlı sınır öğeleri … $C_{max}$ koşulu zaten sağlanır" ifadesi, her sınır satırında s.337–346 sayfası bulunduğu için doğru. Tek zayıf dayanak C6.
- Dışlanan "olasılık dağılımları" ile 3c'deki binom (genetik) çelişmiyor. Adım 3 dışlanan öğeye 3c girişine açıkça izin veriyor.
- Bohr ve atomik spektrum ayrımı üç yerde aynı: Fizik Dışlanan, Kimya Sınır ve orbitallerin kapsamda olması.
- Beceri istisnası ("diziler" mantık sorularında araç olarak kullanılabilir) hem Belge 1'de (satır 33) hem 3a'da (satır 196) aynı.
- Ozmotik basınç adım 4'te (satır 42), 3c'de (satır 209) ve "Açık kalemler"de (satır 157) aynı biçimde ve koşullu işleniyor.
- Skaler ve vektörel çarpım, Ruffini, kuantum sayıları, tampon hesabı, PCR ve CRISPR 1. adımla kapsamda kalıyor ve hiçbir dışlamayla çatışmıyor.
- Belge 2'deki 2a listesi, Belge 1 Daraltma 1 ile birebir aynı.
- Kalan risk aritmetiği doğru: 2 + 5 + 2 = 9; kütleçekimi ve dalgalar ikisi de s.343'te ([IND s.343](</tmp/claude-0/-home-user-imat-2027-calisma/9571da3b-9f67-5a68-a542-7feaa2c2924a/scratchpad/pdf/ind.txt>)).
- Bugünkü çıpaların hiçbiri $C_{max}$'ı aşmıyor. S59 için düzgün çembersel hareketin izdüşümü yöntemi varsayıldı.

Geri çevrilen adaylar:
1. **Hess yasası, "Primo principio"nun doğrudan uygulaması olarak (C10'a benzer).** Entalpinin bir durum fonksiyonu olarak tanıtılması, Fizik'teki ΔU = Q − L ifadesinin ötesinde yeni bir kavram. Kabul edilen okuma (REV C10: "'ΔH hesapları' dışlaması ise Hess yasası ve oluşum entalpileri gibi … konulara kalıyor") ile tutarlı. Yeni bir argüman yok; düştü.
2. **Radyoaktivitenin "isotopi" ve "numero atomico e numero di massa" üzerinden sınır olması gerektiği (C2'ye benzer).** Yapısı geri çekilen kütleçekimi argümanıyla aynı: belge onu açıkça Dışlanan listesine koymuş ve parantezler dayanak değil, komşu konu. Düştü. Yarılanma ömrü aritmetiği matematikte üstel fonksiyon olarak zaten adım 1'de.
3. **2025 S20'nin Michaelis–Menten'i gerektirdiği (çıpa ile kapsam çatışması).** Soru kavramsal (aktif bölge için yarışma); Km ve Vmax istemiyor ([SK](</home/user/imat-2027-calisma/research_notes/IMAT 2027 belge hata denetimi/sinav_kaniti_ncert.md>) §2025). Düştü. Michaelis–Menten yalnızca K1'e düşüyor.
4. **Rosalind Franklin çıpasının dışlanan dalgalara (kırınım) ihtiyaç duyduğu.** Yöntemin adını bilmek, dalga fiziğini gerektirmiyor. Düştü.
5. **"Optimizasyon" dışlaması ile "massimi e minimi"nin çatıştığı.** Adım 1 önce uygulanıyor; parabolün tepe noktasıyla çözülen problem kapsamda. Düştü (kullanıcının adım sırası okumasıyla aynı).
6. **Mantarlar ve protistlerin hem sınır ("Mikroorganizmalar") hem dışlanan (biyoçeşitlilik) olduğu.** Adım 2, adım 3'ten önce geliyor ve 1 saat veriyor; tek sonuç. Düştü.
7. **"PCR/CRISPR'ın 'la tecnologia del DNA ricombinante' belirteciyle dışarıda kaldığı."** Lise programları bu teknikleri DNA ricombinante başlığı altında işliyor ([Liceo Fermi Bologna](https://www.liceofermibo.edu.it/wp-content/uploads/2022/01/PROGRAMMA-SVOLTO-GRIECO-fine-anno-2021-2022-5E.pdf)). Belirteç fiilen bir şey kesmiyor. Düştü.

### Inferences
- Kullanıcının adım sırası okuması kural sistemini büyük ölçüde kapatıyor. Kalan boşluklar sıra ile çözülemeyen noktalarda: listede olmayan konular, birim tanımı, kanıt ölçütü, çapraz başlıklı derinlik.

### Gaps
- Bu denetim kuralların iç mantığıyla sınırlı. T'nin (K1 + K5 + K4) içeriği belge dışında tanımlı olduğu için hiçbir konuda $d_T$ fiilen ölçülemedi. Derinlik bulguları (K7–K9) bu yüzden biçimsel düzeyde kaldı.
