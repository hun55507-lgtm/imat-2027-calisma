# Belge 2 ($C_{max}$ dış çiti): İtalyan okul müfredatı iddiaları ve NCERT Ü7 denetimi

**Tarih:** 11 Ekim 2026. **Hedef kohort:** 2022/23'te birinci sınıfa başlayıp 2027'de bitiren öğrenciler.
**Denetlenen metin:** `belgeler.md` içindeki Belge 2 başlığı ("Tanımlanan dosya"), dört satırlı tablo, "Karakteristik" (Bileşim, Kontrol sırası), Kural 2 "Ü7" maddesi ve Kural 3c (ozmotik basınç).
**Önceki inceleme** (`inceleme/belge-1-2-dogrulama-2026-10-10.md`) ve aynı klasördeki `okul_mufredati_belgeleri.md`, kanıt değil, yeniden kontrol edilecek iddia olarak ele alındı.

**Yöntem ve sınırlar:**
- **Yerel birincil metinler:** `scratchpad/pdf/ind.txt` (ekteki Word-PDF'in s.337–346'sı) ve `scratchpad/pdf/allA.txt` (D.M. 1005/2026 Allegato A). Bu oturumda `grep` ve `sed` ile yeniden okundu.
- **Ağ:** WebFetch bütün alanlarda DNS hatası verdi (indire.it, snals.it, edscuola.eu, collegedunia vb. için `getaddrinfo ENOTFOUND`). ncert.nic.in, normattiva.it ve gazzettaufficiale.it zaten engelli. Bütün web kanıtı WebSearch sonuç özetlerinden geliyor.
- **Statü ölçeği:**
  - **Birincil\*:** resmî alandaki metin (gazzettaufficiale.it, normattiva.it, ncert.nic.in, MIM), ama yalnızca arama özetinden okundu.
  - **İkincil:** kopya, basın veya okul belgesi.
  - **Doğrulanamadı.**
- **Hüküm ölçeği:** doğru / yanlış / kısmen doğru / doğrulanamadı.
- **Karar etkisi:** bulgu matrise bir konu ekliyor ya da çıkarıyor mu, derinliği ya da saati değiştiriyor mu? Değiştirmiyorsa "yalnızca atıf".

---

## 0. Toplu hüküm: tablo, başlık, Karakteristik, 3c ve Ü7

### Takeaway
Tablodaki belge kimliklerinin ve rollerin neredeyse tamamı doğru. Hiçbir bulgu matrise konu eklemiyor ya da çıkarmıyor, derinliği veya saati de değiştirmiyor; hepsi atıf, statü veya ifade düzeltmesi. Düzeltilmesi gerekenler dört başlıkta toplanıyor:
1. Yeni lise Indicazioni'si için "Schema di D.P.R." nitelemesi kanıtlanamıyor. Kaynaklar "schema di regolamento" diyor ve biçim büyük olasılıkla bakanlık kararnamesi.
2. Liceo sportivo'da Matematik, Fizik ve Fen için "ayrı OSA" iddiası doğrulanamadı; okul kaynakları birbiriyle çelişiyor.
3. Tablodan Dir. 69/2012 (teknik enstitü opzioni) eksik.
4. Ü7 "Birincil" etiketi fazla güçlü; doğru etiket "Birincil\*" (resmî PDF'in arama özeti).

Kural 3c'nin "proprietà colligative" dayanağı bu oturumda güçlendi. İfade Dir. 57/2010'un hem teknolojik alan (All. A.2) hem ekonomik alan (All. A.1) eklerinde, iki bağımsız kopyada görüldü.

### Cited Findings
Her satırın kanıtı aşağıdaki 1–9. bölümlerdedir. Tablo bunların özetidir.

### Inferences

**Satır satır hüküm tablosu**

| # | İddia (Belge 2) | Hüküm | Statü (kanıtın) | Düzeltilmiş ifade | Karar etkisi |
|---|---|---|---|---|---|
| H1 | Tanımlanan dosya: D.I. 211/2010, liceo scientifico ordinario s.337–346; Mat. s.337–341, Fiz. s.342–344, Doğa Bil. s.344–346 | Doğru | Birincil (yerel PDF) | "s.337–346 MIUR'un derlenmiş Word dosyasının sayfalarıdır, GU sayfası değildir" eklenebilir | Yok |
| L1 | D.P.R. 89/2010: lise türleri, PECUP, "orario annuale"; OSA içermez | Doğru | Birincil\* + İkincil | "Indicazioni'yi m.13 c.10 lett. a) öngörür (D.I. 211/2010 m.1)" eklenmeli | Yalnızca atıf |
| L2 | D.I. 211/2010 = Indicazioni, disiplin bazlı OSA | Doğru | Birincil\* (Normattiva özeti) | All. A nota introduttiva, All. B–G OSA; GU n.291, 14.12.2010, S.O. n.275; yürürlük 29.12.2010 | Yalnızca atıf |
| L3 | Liceo scientifico ve "scienze applicate" seçeneği Allegato F'de | Doğru | İkincil (önceki notlar; B–E eşleşmesi bu oturumda) | — | Yok |
| L4 | s.337–346 ordinario'nun Mat., Fiz. ve Doğa Bil. kısımlarıdır | Doğru | Birincil (yerel iç kanıt) | — | Yok |
| L5 | D.P.R. 89 ve D.I. 211 statüsü "İkincil" | Kısmen doğru: etiket aşağıda kalıyor | — | "Birincil\* (Normattiva/GU özeti) + yerel MIUR derlemesi" | Yalnızca atıf |
| L6 | Yürürlükte; 2027 kohortu bu metinle okudu | Doğru | Çıkarım (yeni metin 2027/28 birinci sınıflarından başlıyor) | — | Yok |
| L7 | Yeni Indicazioni: "Schema di D.P.R." | Kısmen doğru / biçim büyük olasılıkla yanlış | İkincil | "Schema di regolamento (biçimi: büyük olasılıkla bakanlık kararnamesi; doğrulanmalı)" | Yalnızca atıf |
| L8 | CSPI görüşü 14.07.2026, 22 evet, 12 hayır | Doğru | İkincil (çoklu) | — | Yok |
| L9 | Başlangıç 2027/28 birinci sınıflar | Doğru ("salvo modifiche dell'iter") | İkincil | — | Yok |
| L10 | (Eksik) Ekim 2026 durumu | Doğrulanamadı | — | "Ekim 2026: Consiglio di Stato görüşü ve GU yayımı görülmedi; süreç izleniyor" | Yok (2027 kohortunu etkilemez) |
| S1 | Liceo sportivo: D.P.R. 5 marzo 2013, n. 52 | Doğru | Birincil\* (GU özeti) | GU n.113, 16.5.2013 eklenmeli; "7 marzo" yazan kaynaklar hatalı | Yalnızca atıf |
| S2 | m.2 c.4: OSA Allegato A'da | Doğru | Birincil\* (GU m.2 sayfası) | — | Yok |
| S3 | "Ayrı OSA"; "en az Fizik için ayrı OSA görüldü" | Doğrulanamadı (kaynaklar çelişkili) | İkincil | "m.2 c.4 OSA'yı All. A'ya koyar; Mat./Fiz./Fen için All. A'nın kendi metni mi yoksa liceo scientifico'ya atıf mı olduğu doğrulanmadı" | Yok |
| S4 | 2027 mezunları var | Doğru (çıkarım) | Çıkarım | — | Yok |
| T1 | Teknik: D.P.R. 88/2010 | Doğru | İkincil | — | Yok |
| T2 | Dir. 57/2010 (ilk iki yıl Linee guida) | Doğru; ekler A.1 ekonomik, A.2 teknolojik | İkincil (INDIRE ve Pearson kopyaları) | "All. A.1 ve A.2" eklenebilir | Yok |
| T3 | Dir. 4/2012 (ikinci iki yıl ve beşinci yıl) | Doğru | İkincil (sonraki resmî kararnamelerdeki atıf) | — | Yok |
| T4 | "Varlık ve rol Birincil (USR Lombardia decreto 36/2026, MIM DD 92/2024)" | Kısmen doğru | Decreto 36 (8.1.2026) iki direttiva'yı anıyor; çıkaran kurum teyit edilmedi. DD 92/2024'ün bu atfı içerdiği görülmedi | DD 92/2024'ü kaldır ya da "doğrulanmalı" yaz | Yalnızca atıf |
| T5 | Dir. 4/2012 metni okunmadı | Doğru (hâlâ okunmadı) | Doğrulanamadı | — | Yok |
| T6 | (Eksik) Dir. 69/2012, opzioni Linee guida'sı | Eksik | İkincil (önceki notlar) | Satıra "Dir. 69 del 1° agosto 2012 (opzioni)" eklenmeli | Yok (opzioni dersleri 3a ile dışlanır) |
| T7 | D.M. 29/2026: 2026/27 birinci sınıflar; saatler, profiller, öğrenme sonuçları; adı Linee guida değil | Doğru; tarih 19.2.2026 | İkincil (basın + MIM notu kopyası) | "D.M. 19 febbraio 2026, n. 29 (indirizzi, articolazioni, quadri orari, risultati di apprendimento); yeni Linee guida Eylül 2026'da hâlâ hazırlanıyordu (MIM nota 2306, 3.9.2026)". Statü "Birincil" → "İkincil" | Yok |
| T8 | Beşinci sınıflara 2030/31'de ulaşır | Doğru (çıkarım) | Çıkarım | — | Yok |
| P1 | Mesleki: D.Lgs. 61/2017 | Doğru | İkincil | — | Yok |
| P2 | D.P.R. 87/2010, D.Lgs. 61/2017 m.13 c.1 ile 2022/23'ten itibaren kalktı | Doğru (önceki notta lafız var; bu oturumda yeniden görülmedi) | İkincil | — | Yok |
| P3 | D.I. 92/2018: çıkış profilleri | Doğru (D.Lgs. 61/2017 m.3 c.3 uyarınca regolamento) | İkincil | Statü "Doğrulanmalı" → "İkincil" | Yok |
| P4 | D.M. 766/2019: Linee guida | Doğru (D.I. 92/2018 m.4 c.4 uyarınca) | İkincil (resmî ve bölgesel atıflar) | Statü "Doğrulanmalı" → "İkincil" | Yok |
| P5 | 2027 mezunları tamamen yeni düzende | Doğru | İkincil + çıkarım | — | Yok |
| P6 | Allegato A'nın andığı Linee guida = D.M. 766/2019 [Yorum] | Doğru (makul yorum) | Birincil (Allegato A lafzı) + İkincil | — | Yok |
| P7 | "İçerik tanımı D.I. 92/2018'in eklerindedir" | Kısmen doğru / doğrulanamadı | — | "Profiller ve öğrenme sonuçları D.I. 92/2018 eklerinde; ayrıntılı açılım D.M. 766/2019 eklerinde olabilir (doğrulanmadı)" | Yok |
| K1 | Bileşim: Licei ∪ Tecnici ∪ Professionali; Licei = 2010 Indicazioni'deki bütün liseler + sportivo | Doğru | Birincil (Allegato A lafzı) | Liceo del Made in Italy'nin 2027'de mezunu olmadığı için dışarıda kaldığını yaz | Yok |
| K2 | Kontrol sırası: ordinario → scienze applicate → sportivo → "yalnızca birleşimde" | Doğru (mantık) | — | Scienze applicate kimyası ordinario'dan geniş; sportivo OSA'sı belirsiz | Yok |
| R3c | Ozmotik basınç dayanağı: Dir. 57/2010 "proprietà colligative"; "pressione osmotica" adıyla geçmiyor | Doğru | İkincil (iki bağımsız kopya, arama özeti) | "Dir. 57/2010 All. A.2 (teknolojik) ve All. A.1 (ekonomik), Scienze integrate (Chimica)" | Yok (öğe zaten koligatif düzeyde giriyor; dayanak güçlendi) |
| Ü7a | kebo107 (Reprint 2026-27): yalnızca 7.1 Organ and Organ System ve 7.2 Frogs | Doğru | Birincil\* (ncert.nic.in PDF'inin arama özeti) | Statü "Birincil" → "Birincil\*" | Yok |
| Ü7b | Dokular yalnızca geçerken anılır | Doğru | İkincil (önceki not + çalışma sitesi) | — | Yok |
| Ü7c | Alternatif: "7.1 Animal Tissues (sinir dokusu hariç) hâlâ var, kurbağa 7.3" | Yanlış (güncel baskı için) | İkincil (MTG silinenler listesi) | — | Yok |
| Ü7d | Eski baskıda toprak solucanı ve hamamböceği atlanır | Doğru ama eksik | İkincil | "Eski baskıda 7.1 Animal Tissue de vardır; 'I tessuti animali' nedeniyle atlanmaz" | Yok (kaynak kullanım notu) |

### Gaps
- Hiçbir resmî metin (Normattiva, GU, MIM, NCERT) doğrudan açılamadı. "Birincil\*" etiketli bütün hükümler arama özetine dayanıyor.

---

## 1. D.P.R. 15 marzo 2010, n. 89: PECUP, quadri orari, OSA'nın yokluğu ve Indicazioni'yi öngören madde

### Takeaway
Belge 2'nin hücresi ("lise türleri, PECUP ve yıllık ders saatleri; OSA içermez") **doğru**. Disiplin bazlı OSA'yı öngören hüküm **D.P.R. 89/2010 m.13 c.10 lett. a)**'dır. D.I. 211/2010 m.1 bu maddeye doğrudan atıf yapar. D.I. 211/2010'un başlığı ise ders planlarına (m.10 c.3) ve m.2 c.1 ile c.3'e atıf yapar. Belge 2 bu maddeyi anmıyor. Eksik yalnızca atıf düzeyinde, karar etkisi yok.

### Cited Findings
- D.I. 211/2010 m.1: "Le Indicazioni nazionali di cui al decreto del Presidente della Repubblica 15 marzo 2010, n. 89, articolo 13, comma 10, lettera a), comprendono la nota introduttiva di cui all'allegato A e la declinazione degli obiettivi di apprendimento di cui agli allegati B, C, D, E, F, G del presente decreto del quale fanno parte integrante." Birincil\* (Normattiva özeti); Astrid kopyası. — [Normattiva, D.I. 211/2010 konsolide](https://www.normattiva.it/eli/id/2010/12/14//010G0232/CONSOLIDATED); [Astrid, Miur decreto 07.10.10 n.211](https://www.astrid-online.it/static/upload/protected/Miur/Miur_decreto-07_10_10-n211.pdf)
- D.I. 211/2010'un başlığı: "…percorsi liceali di cui all'articolo 10, comma 3, del decreto del Presidente della Repubblica 15 marzo 2010, n. 89, in relazione all'articolo 2, commi 1 e 3, del medesimo regolamento". Önceki notta GU özetinden alıntılandı; bu oturumda Normattiva özeti aynı yapıyı gösteriyor. — [Gazzetta Ufficiale, 010G0232](https://www.gazzettaufficiale.it/eli/id/2010/12/14/010G0232/sg)
- D.P.R. 222/2024 (Liceo del Made in Italy) hâlâ D.I. 211/2010'u anıyor: "Visto il decreto del Ministro dell'istruzione, dell'universita' e della ricerca 7 ottobre 2010, n. 211". İkincil (FLC CGIL kopyası). — [FLC CGIL, D.P.R. 222/2024](https://flcgil.it/files/pdf/20250220/decreto-del-presidente-della-repubblica-222-del-25-novembre-2024-regolamento-del-percorso-liceale-del-made-in-italy.pdf)
- D.P.R. 89/2010'un ders planları yıllık saatle verilir. Liceo sportivo'nun (D.P.R. 52/2013 All. A) GU kopyası da aynı biçimi kullanıyor: Matematica 165, Fisica 66, Scienze naturali 99 saat (birinci iki yıl). İkincil (e-santoni'deki GU kopyası, arama özeti). — [e-santoni, GU kopyası D.P.R. 52/2013](https://www.e-santoni.org/Linee_guida/secondo_ciclo/licei_Indicazioni_nazionali/Decreto%20Presidente%20della%20Repubblica%2052%20del%205%20marzo%202013%20-%20Regolamento%20Liceo%20Sportivo.pdf)

### Inferences
- İş bölümü şöyle: D.P.R. 89/2010 türleri, PECUP'ı (Allegato A; her lise için genel öğrenme sonuçları dahil) ve ders planlarını verir. Disiplin bazlı OSA ise m.13 c.10 lett. a) uyarınca D.I. 211/2010'dadır. "OSA içermez" doğru.
- Önerilen ek: "Indicazioni'nin dayanağı D.P.R. 89/2010 m.13 c.10 lett. a)'dır (D.I. 211/2010 m.1)." **Yalnızca atıf.**

### Gaps
- m.13 c.10 lett. a)'nın ve m.10 c.3'ün kendi lafzı okunamadı; hüküm D.I. 211/2010 m.1'in özetine dayanıyor.
- D.P.R. 89/2010 eklerinin harf eşleşmesi (piani degli studi hangi ekte) bu oturumda kaynakla teyit edilmedi.

---

## 2. D.I. 7 ottobre 2010, n. 211: ek yapısı, GU kaydı, s.337–346'nın kimliği ve scienze applicate kimyası

### Takeaway
- **Ek yapısı doğru:** Allegato A nota introduttiva, Allegati B–G lise OSA'ları. B artistico, C classico, D linguistico, E musicale e coreutico (özetle teyit edildi), F liceo scientifico ve scienze applicate seçeneği (ikincil), G scienze umane (eleme yoluyla çıkarım).
- **GU kaydı:** GU n. 291, 14.12.2010, Suppl. Ordinario n. 275; yürürlük 29.12.2010. Önceki notta açık kalan S.O. 275 bu oturumda Normattiva özetiyle kapandı.
- **s.337–346 ordinario'dur;** iç kanıt kesin.
- **Scienze applicate kimyası** ordinario'dan geniştir: tam elektrokimya, ikinci iki yılda temel organik kimya, beşinci yılda malzeme bilimi (ikincil, önceki notlar). "Colligative" ya da "osmotica" ifadesine dair hiçbir işaret yok. Termokimya için ordinario s.346 zaten "scambi energetici … fondamenti degli aspetti termodinamici" diyor.

### Cited Findings
- **GU kaydı:** "GU n. 291 del 14-12-2010 - Suppl. Ordinario n.275"; Normattiva'ya göre yürürlük 29.12.2010. Birincil\* (Normattiva özeti). — [Normattiva](https://www.normattiva.it/eli/id/2010/12/14//010G0232/CONSOLIDATED)
- **Ek eşleşmesi:** liceo artistico (allegato B), liceo classico (allegato C), liceo linguistico (allegato D), liceo musicale e coreutico (allegato E). Astrid kopyasının arama özeti; G'nin eşleşmesi özette görünmedi. — [Astrid](https://www.astrid-online.it/static/upload/protected/Miur/Miur_decreto-07_10_10-n211.pdf)
- **Allegato F:** scienze applicate'in OSA'sı "nell'Allegato F al D.M. n. 211/2010". İkincil (önceki notlar). — [Notizie della scuola, Scienze Naturali (scienze applicate)](https://www.notiziedellascuola.it/istruzione-e-formazione/riforma-della-scuola-secondaria-superiore/piani-degli-studi/licei/materie/scienze-naturali-scienze-applicate); [Galilei Crema, IINN Liceo SA](https://www.galileicrema.edu.it/extra/documenti/riforma/IINN_LiceoSA.pdf)
- **Adlandırma:** Normattiva ve D.P.R. 222/2024 metni kararnameyi "decreto del Ministro … 7 ottobre 2010, n. 211" olarak anıyor; MEF ile birlikte çıkarıldığı için yaygın kısaltma "D.I." Yalnızca adlandırma meselesi. — [FLC CGIL, D.P.R. 222/2024](https://flcgil.it/files/pdf/20250220/decreto-del-presidente-della-repubblica-222-del-25-novembre-2024-regolamento-del-percorso-liceale-del-made-in-italy.pdf)
- **Yerel birincil, sayfa düzeni** (`ind.txt` sayfa altı numaralarına göre):
  - MATEMATICA 2–278. satırlar: s.337–341.
  - FISICA 280. satırda başlar: s.342–344.
  - SCIENZE NATURALI 411. satırda başlar: s.344–346.
  - Belge 2'deki sayfa aralıkları birebir tutuyor.
- **Yerel birincil, ordinario olduğunun iç kanıtı:**
  - s.337 "Al termine del percorso del liceo scientifico lo studente conoscerà…" ile başlıyor.
  - "Elementi di informatica" Matematik OSA'sının içinde (179. satır). Matematik ile Fizik arasında ayrı bir INFORMATICA bölümü yok; scienze applicate'te Informatica ayrı bir derstir.
  - s.346 kimya: "insieme agli equilibri, anche in soluzione (reazioni acido-base e ossidoriduzioni), e a cenni di elettrochimica".
  - s.346 beşinci yıl: "Il percorso di chimica e quello di biologia si intrecciano poi nella biochimica e nei biomateriali".
  - Kaynak: ekteki PDF, `ind.txt` 2, 6, 179, 280, 411, 515–540. satırlar.
- **Yerel birincil, ordinario'da çözelti ve koligatif:**
  - Birinci iki yıl kimyası (s.345) çözelti, koligatif özellik ya da osmoz anmıyor: "stati di aggregazione … modello particellare … classificazione della materia (miscugli omogenei ed eterogenei…) … leggi fondamentali e il modello atomico di Dalton…".
  - İkinci iki yıl (s.346) yalnızca "equilibri, anche in soluzione" diyor.
  - `colligat|osmo` araması sıfır sonuç verdi.
- **Scienze applicate, ikinci iki yıl kimya:** "…insieme agli equilibri, anche in soluzione, all'elettrochimica e alla chimica organica di base"; beşinci yıl "…concetti basilari della scienza dei materiali…". İkincil, önceki notlar (Notizie della scuola "bozza" etiketli sayfası ve INDIRE kopyası); bu oturumda INDIRE PDF'i açılamadı. — [INDIRE, Liceo scientifico opzione Scienze Applicate](https://www.indire.it/lucabas/lkmw_file/licei2010/indicazioni_nuovo_impaginato/_Liceo%20scientifico%20opzione%20Scienze%20Applicate.pdf)

### Inferences
- **"Eldeki s.337–346 ordinario'nun Mat., Fiz. ve Doğa Bil. kısımlarıdır": doğru.** Karar etkisi yok.
- **Scienze applicate farkı** elektrokimya ve malzeme bilimi yönünde. İkisi de Allegato A'da bir ifadeye dayanmadığı için 3a ile dışlanmış kalıyor. 3b/3c'den gelen hiçbir öğe bunlara bağlı değil. Ozmotik basınç ve koligatif özellik için scienze applicate'te bir işaret yok. Bu sonuç 3c'yi etkilemiyor, çünkü dayanak zaten Dir. 57/2010'da (bölüm 5). **Karar etkisi yok.**
- **ΔH/ΔG (3c, hücresel solunum):** ordinario s.346 zaten "scambi energetici associati alle trasformazioni chimiche e … fondamenti degli aspetti termodinamici" diyor. 3c'nin bu öğe için $C_{max}$ dayanağı scienze applicate'e gerek kalmadan ordinario'da var.

### Gaps
- Allegato G'nin scienze umane olduğu eleme yoluyla çıkarıldı; doğrudan görülmedi.
- Scienze applicate'in birinci iki yıl kimyası ile Matematik ve Fizik OSA'larının ordinario ile birebir aynı olup olmadığı bu oturumda okunamadı (INDIRE PDF'i açılamadı).

---

## 3. Yeni lise Indicazioni'si: biçim, CSPI, başlangıç ve Ekim 2026 durumu

### Takeaway
- CSPI görüşü (14.07.2026, 22 olumlu, 12 olumsuz) ve 2027/28 birinci sınıflarından kademeli başlangıç **doğru** (çoklu ikincil kaynak).
- **"Schema di D.P.R." kanıtlanamıyor.** Bütün kaynaklar "schema di regolamento" diyor. Öncül metin (D.I. 211/2010) bakanlık kararnamesiydi. Birinci kademenin yeni Indicazioni'si de Consiglio di Stato görüşünden sonra bakan imzasıyla çıktı. Biçim büyük olasılıkla bakanlık kararnamesi (regolamento); bu bir çıkarımdır.
- **Ekim 2026 durumu:** lise metni için Consiglio di Stato görüşüne, nihai imzaya ya da GU yayımına dair kaynak bulunamadı.
- 2027 kohortu için $C_{max}$ değişmez.

### Cited Findings
- CSPI 14.07.2026: "schema" üzerine parere, 22 favorevoli, 12 contrari; FLC CGIL karşı oy verdi. İkincil. — [FLC CGIL](https://www.flcgil.it/scuola/nuove-indicazioni-nazionali-per-i-licei-il-cspi-approva-il-parere-la-flc-cgil-vota-contro.flc); [Tecnica della Scuola, bozza approvata dal Cspi: si parte nel 2027?](https://www.tecnicadellascuola.it/indicazioni-nazionali-licei-bozza-approvata-dal-cspi-si-parte-nel-2027); [Newsistruzione 16.7.2026](https://www.newsistruzione.it/2026/07/16/licei-nuove-indicazioni-nazionali-cspi); [Orizzonte Scuola, parere CSPI](https://www.orizzontescuola.it/nuove-indicazioni-nazionali-per-i-licei-arriva-il-parere-del-cspi-si-allinnovazione-attenzione-a-equita-intelligenza-artificiale-e-fragilita-degli-studenti/)
- Biçim: kaynaklar "schema di Regolamento" diyor. Bir kaynağa göre CSPI'dan sonra Consiglio di Stato aşaması geliyor ve hedef "a inizio settembre" nihai kararnameyi yayımlamaktı. Başlangıç 2027/28 birinci sınıfları. İkincil. — [Confronto Scuola, via libera del CSPI, partenza dal 2027/28](https://www.confrontoscuola.it/post/nuove-indicazioni-nazionali-per-i-licei-via-libera-del-cspi-partenza-dal-2027-28-ecco-cosa-cambia); [Newsistruzione 6.7.2026](https://www.newsistruzione.it/2026/07/06/indicazioni-nazionali-licei-cosa-cambia-2027-2028)
- Taslak (Nisan 2026) bir nota introduttiva ve her lise türü için bir ek olmak üzere yedi ekten oluşuyor. İkincil (arama özeti). — [Scuola7, Le nuove Indicazioni nazionali per i Licei](https://www.scuola7.it/2026/478/le-nuove-indicazioni-nazionali-per-i-licei/)
- MIM'in 15.07.2026 tarihli notu yeni "Indicazioni nazionali concernenti gli obiettivi specifici di apprendimento per i licei"yi D.I. 211/2010'u gözden geçirip yerine geçen metin olarak anıyor. Birincil\* (UMI'deki kopya, arama özeti). — [MIM notu, UMI kopyası](https://umi.dm.unibo.it/wp-content/uploads/2026/07/m_pi.AOODGOSV.REGISTRO-UFFICIALEE.0141907.15-07-2026.pdf)
- Paralel süreç (birinci kademe): Consiglio di Stato önce görüşünü askıya aldı (parere n. 1017/2025, 17.9.2025), sonra olumlu görüş verdi (bir kaynağa göre 12.11.2025). Bakanın nihai imzası Aralık 2025'te bildirildi; yürürlük 2026/27. Bu, metnin D.P.R. değil bakanlık düzenlemesi olarak çıktığını gösteriyor. İkincil. — [Tuttoscuola, ok Consiglio di Stato](https://www.tuttoscuola.com/indicazioni-nazionali-ok-consiglio-di-stato/); [Orizzonte Scuola, Valditara annuncia la firma](https://www.orizzontescuola.it/nuove-indicazioni-nazionali-infanzia-primaria-e-media-in-vigore-da-settembre-2026-valditara-annuncia-la-firma-definitiva-nei-prossimi-giorni/); [Giustoscuola, sospeso il parere](https://www.giustoscuola.it/archivio-notizie/3880-il-consiglio-di-stato-frena-le-nuove-indicazioni-nazionali-sospeso-il-parere-sul-regolamento.html)
- **Çelişkili/yanıltıcı kaynak:** "Valditara firma, in vigore dal 2026/27" başlıklı sayfa birinci kademeye ait görünüyor. Lise metni için kullanılmamalı. — [La Scuola Oggi](https://www.lascuolaoggi.it/nuove-indicazioni-nazionali-2026-decreto/)

### Inferences
- **L7 ("Schema di D.P.R.") kısmen doğru:** "schema" ve "regolamento" doğru, "D.P.R." desteksiz. Önerilen ifade: "Schema di regolamento (Indicazioni nazionali per i licei; biçim büyük olasılıkla bakanlık kararnamesi, doğrulanmalı)". Önceki incelemedeki "'Schema di D.P.R.' doğru" hükmü kaynakla desteklenmiyor. **Yalnızca atıf.**
- **L10 (eksik):** Ekim 2026 itibarıyla nihai kabul görülmedi. Hücreye şu eklenebilir: "Consiglio di Stato görüşü ve GU yayımı 11.10.2026 itibarıyla görülmedi." 2027 kohortu (2022/23 başlangıç) her senaryoda D.I. 211/2010 ile okudu. **Karar etkisi yok.**

### Gaps
- Lise metninin Consiglio di Stato'ya gönderilip gönderilmediği ve görüş tarihi bulunamadı. Arama sonuçlarındaki en yeni lise kaynağı Temmuz 2026 tarihli.
- Nihai biçim (D.M. mi, D.I. mi) birincil kaynakla görülmedi.

---

## 4. Liceo sportivo: D.P.R. 5 marzo 2013, n. 52, m.2 c.4 ve Allegato A

### Takeaway
- **Kimlik doğru:** D.P.R. 5 marzo 2013, n. 52; GU n.113, 16.5.2013 (codice redazionale 13G00095). "7 marzo" yazan kaynaklar hatalı.
- **m.2 c.4 doğru:** OSA, risultati di apprendimento ve piano degli studi Allegato A'da.
- **"Ayrı OSA" ve "en az Fizik için ayrı OSA görüldü" doğrulanamadı; kaynaklar çelişkili.** İki okul, sportivo'daki derslerin OSA'sının "quelli … del Liceo Scientifico" olduğunu yazıyor. Diğer okullar ise sporla uyarlanmış ortak cümleler kullanıyor. Allegato A'nın Matematik, Fizik ve Fen metni hiçbir kaynakta görülmedi.
- Yeni bir kimya ya da fizik kavramı (ör. koligatif özellik) getirdiğine dair işaret yok.

### Cited Findings
- **GU m.2:** bölüm "approfondimento delle scienze motorie e sportive e di una o più discipline sportive … all'interno di un quadro culturale che favorisce, in particolare, l'acquisizione delle conoscenze e dei metodi propri delle scienze matematiche, fisiche e naturali nonché dell'economia e del diritto" amaçlıdır. m.2 c.4: "I risultati di apprendimento, il piano degli studi e gli obiettivi specifici di apprendimento relativi alla sezione ad indirizzo sportivo sono riportati nell'allegato A". Birincil\* (GU m.2 sayfası, arama özeti). — [Gazzetta Ufficiale, D.P.R. 52/2013 m.2](https://www.gazzettaufficiale.it/atto/serie_generale/caricaArticolo?art.versione=1&art.idGruppo=0&art.flagTipoArticolo=0&art.codiceRedazionale=13G00095&art.idArticolo=2&art.idSottoArticolo=1&art.idSottoArticolo1=10&art.dataPubblicazioneGazzetta=2013-05-16&art.progressivo=0)
- **Tarih:** okul kopyası başlığı "DECRETO DEL PRESIDENTE DELLA REPUBBLICA 5 marzo 2013, n. 52". FLC CGIL dosya adında "7 marzo" geçiyor. — [Liceo Savoia, D.P.R. 52/2013](https://liceosavoia.edu.it/wp-content/uploads/2018/12/DPR52-2013.pdf); [FLC CGIL, liceo sportivo regolamento](https://m.flcgil.it/scuola/liceo-sportivo-pubblicato-il-regolamento.flc)
- **Dayanak ve diploma:** yönetmelik D.P.R. 89/2010 m.3 c.2 uyarınca çıkarıldı. Diploma "liceo scientifico – sezione ad indirizzo sportivo" adını taşır. İkincil. — [FLC CGIL](https://m.flcgil.it/scuola/liceo-sportivo-pubblicato-il-regolamento.flc); [Notizie della scuola](https://www.notiziedellascuola.it/legislazione-e-dottrina/indice-cronologico/2013/marzo/DPR_20130305_52)
- **Ders saatleri (All. A, birinci iki yıl):** Matematica 165, Fisica 66, Scienze naturali 99 yıllık saat. İkincil (GU kopyası özeti). — [e-santoni, GU kopyası](https://www.e-santoni.org/Linee_guida/secondo_ciclo/licei_Indicazioni_nazionali/Decreto%20Presidente%20della%20Repubblica%2052%20del%205%20marzo%202013%20-%20Regolamento%20Liceo%20Sportivo.pdf)
- **Çelişki A (liceo scientifico'ya atıf):** "i contenuti disciplinari e gli obiettivi specifici di apprendimento degli insegnamenti presenti nel piano degli studi del Liceo Sportivo sono quelli riportati nelle 'Indicazioni nazionali' del corrispondente piano di studi del Liceo Scientifico". İkincil (iki okul). — [Licei Camerino](http://www.liceicamerino.gov.it/index.php/component/content/article/2-non-categorizzato/86-liceo-sportivo); [Istituto Volta, sezione ad indirizzo sportivo](https://istitutovolta.it/wp-content/uploads/2025/07/Liceo-scientifico-opzione-Scienze-Applicate.pdf)
- **Çelişki B (sporla uyarlanmış ortak cümleler):**
  - Fizik: "cinematica, meccanica e statica" ile "competenze specifiche sul tema della misura e in materia di teoria degli errori, con riferimento alle applicazioni in campo sportivo".
  - Fen: "lo studio della chimica organica è orientato alla comprensione dei meccanismi chimico-biologici dell'apparato umano impegnato nel gesto atletico"; genetikte atletik potansiyel ve doping.
  - İkincil (okul sayfaları ve programları).
  - Kaynaklar: [IIS Calamandrei, Liceo Scientifico Sportivo](https://www.iisscalamandrei.edu.it/pagine/sportivo); [Liceo Antonelli Novara, programmazione scienze](https://www.liceoantonellinovara.edu.it/wp-content/uploads/2024/02/Programmazione-Dipartimento-scienze.pdf); [Liceo Grassi Latina](https://www.liceograssilatina.edu.it/liceo-scientifico-sportivo/)
- **Yeni dersler için All. A'dan alınmış OSA dosyası:** Liceo Antonelli'nin "DIRITTO ED ECONOMIA DELLO SPORT Obiettivi specifici…" belgesi yıllara göre hedef ve içerik veriyor. Bu, All. A'nın en azından yeni dersler için kendi OSA'sını içerdiğine işaret ediyor. İkincil. — [Liceo Antonelli Novara, Obiettivi diritto ed economia dello sport](https://www.liceoantonellinovara.edu.it/wp-content/uploads/2024/02/Obiettivi-diritto-ed-economia-dello-sport.pdf)

### Inferences
- **S1, S2 doğru;** etiket "Birincil\*" olarak kalabilir. GU n.113, 16.5.2013 hücreye eklenmeli.
- **S3 ("ayrı OSA", "Fizik için ayrı OSA görüldü") doğrulanamadı.** En olası okuma: All. A yeni dersler (Scienze motorie e sportive, Discipline sportive, Diritto ed economia dello sport) için kendi OSA'sını veriyor. Matematik, Fizik ve Fen için liceo scientifico'ya dayanıyor ya da yalnızca uyarlama vurguları ekliyor. Bu bir çıkarımdır. Önerilen hücre: "Birincil\* (m.2 c.4: OSA All. A'da). Mat./Fiz./Fen için All. A'nın içeriği doğrulanmadı; okul kaynakları çelişkili."
- **Karar etkisi yok.** Sportivo uyarlamaları (hareket fizyolojisi, biyomekanik, doping) yeni bir kimya veya fizik kavramı getirmiyor; biyolojide derinliği zaten T veriyor (Kural 2c). 3c'nin ozmotik basınç dayanağı sportivo'ya muhtaç değil (bölüm 5).
- **S4 ("2027 mezunları var") doğru, çıkarım olarak:** 2013 yönetmeliği; 2022/23 birinci sınıfları 2027'de bitiriyor.

### Gaps
- D.P.R. 52/2013 Allegato A'nın Matematik, Fizik ve Doğa Bilimleri bölümleri okunamadı. e-santoni'deki GU kopyasının özeti bu bölümlerin "okunaksız" olduğunu söylüyor.

---

## 5. Teknik enstitüler: D.P.R. 88/2010, Dir. 57/2010, Dir. 4/2012, (eksik) Dir. 69/2012, D.M. 29/2026 ve Kural 3c'deki "proprietà colligative"

### Takeaway
- **Belgeler ve rolleri doğru.** Dir. 57/2010 ilk iki yıl Linee guida'sıdır (All. A.1 ekonomik, A.2 teknolojik); Dir. 4/2012 ikinci iki yıl ve beşinci yıl.
- **3c dayanağı doğru:** "Scienze integrate (Chimica)" bilgi listesinde A.2'de "Le soluzioni: percento in peso, molarità, molalità, proprietà colligative.", A.1'de "Le concentrazioni delle soluzioni: percento in peso, molarità, molalità, proprietà colligative delle soluzioni." geçiyor. "Pressione osmotica" görülen satırlarda adıyla yok.
- **D.M. 29/2026 doğru:** 19.2.2026; 2026/27 birinci sınıflarından itibaren; indirizzi, articolazioni, quadri orari ve risultati di apprendimento; yeni Linee guida Eylül 2026'da hâlâ hazırlanıyordu. 2027 kohortunu etkilemez.
- **Eksik:** Dir. 69/2012 (opzioni).
- **Statü:** "USR Lombardia decreto 36/2026, MIM DD 92/2024" atıflarından yalnızca decreto 36 (8.1.2026) teyit edildi.

### Cited Findings
- **Dir. 57/2010, All. A.2 (teknolojik), Scienze integrate (Chimica):**
  - Bilgi: "Le soluzioni: percento in peso, molarità, molalità, proprietà colligative."
  - Beceri: "Preparare soluzioni di data concentrazione (percento in peso, molarità, molalità)."
  - Genel not: "Le conoscenze e le abilità che seguono sono da declinarsi in relazione all'indirizzo e all'articolazione."
  - İkincil (INDIRE ve Pearson kopyaları, arama özeti; iki kopyada aynı satır).
  - Kaynaklar: [INDIRE, 25_A2_ALLEGATO, "Allegato A.2 SETTORE TECNOLOGICO Primo biennio"](https://www.indire.it/lucabas/lkmw_file/nuovi_tecnici/25_A2_ALLEGATO.pdf); [Pearson, "Allegato A.A.2 SETTORE TECNOLOGICO"](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/diritto-economia/programmi-ministeriali/istituti-tecnici/AREE%20DISCIPLINARI%20-%20PARAMOND%20-%20PROG%20-%20PDF%20-%20Linee%20guida%20primo%20biennio%20istituti%20tecnici%20settore%20tecnologico.pdf)
- **Dir. 57/2010, All. A.1 (ekonomik), Scienze integrate (Chimica):** "Le concentrazioni delle soluzioni: percento in peso, molarità, molalità, proprietà colligative delle soluzioni." İkincil (Pearson kopyası, arama özeti). — [Pearson, "Allegato A.A.1 SETTORE ECONOMICO"](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/diritto-economia/programmi-ministeriali/istituti-tecnici/AREE%20DISCIPLINARI%20-%20PARAMOND%20-%20PROG%20-%20PDF%20-%20Linee%20guida%20primo%20biennio%20istituti%20tecnici%20settore%20economico.pdf)
- **Aynı satırın il düzeyindeki uyarlaması:** Trento'nun "Linee guida per l'elaborazione dei piani di studio" (2013) belgesi. İkincil. — [Vivoscuola (Trento)](https://www.vivoscuola.it/content/download/29031/685766/file/a73aefa681d398cc4865a5d86135664e.pdf)
- **Okul programları ilk iki yılda ozmotik basıncı açıkça işliyor:** "innalzamento ebullioscopico e abbassamento crioscopico, la pressione osmotica". Uygulama bağlamı; ulusal metin değil. — [IIS Badoni, programma chimica 2D](https://vecchiosito.iisbadoni.edu.it/sites/default/files/programmi/2020-2021-Programma%20svolto-chimica%20e%20laboratorio-2%20D%20it.pdf)
- **Dir. 57/2010 ve Dir. 4/2012'nin rolü:** sonraki bir kararnamede "direttiva 15 luglio 2010, n. 57 … primo biennio degli Istituti tecnici" ve "direttiva 16 gennaio 2012, n. 4, concernente le Linee Guida relative al secondo biennio e al quinto anno degli Istituti tecnici" diye anılıyor. Bu atıfları içeren belgeler "decreto 36 del 8.1.2026" ve bir USR Sicilia ilanı. Decreto 36'yı çıkaran kurumun USR Lombardia olduğu bu oturumda görülmedi. İkincil/Birincil\* (resmî kararname metni, özet). — [Decreto 36 del 8.1.2026](https://cloud.municipiumapp.it/s3/20287/allegati/area-documentale/mod-istruzione-e-formazione-prof/decreto-36-del-8-1-2026-con-allegato.pdf); [USR Sicilia, avviso n. 2608 del 7.12.2023](https://www.usr.sicilia.it/download/1156/10139/10145/avviso-n-2608-07-12-2023.pdf)
- **DD 92/2024:** MIM DG Ordinamenti'nin 19.1.2024 tarihli kararnamesi; "filiera tecnologico-professionale" dört yıllık deneysel programlarının 2024/25 birinci sınıflarını başlatıyor. İki direttiva'yı andığı özette görülmedi. — [DD n. 92 del 19 gen 2024](https://www.istruzioneatprc.it/wp-content/uploads/2024/01/DD-n_92-del-19-gen-2024-Filiera.pdf)
- **D.M. 29/2026:**
  - "DM n. 29 del 19 febbraio 2026": D.L. 144/2022 m.26 ve 26-bis'i uygular; "ridefinisce indirizzi, articolazioni, quadri orari e risultati di apprendimento"; 2026/27 birinci sınıflarından itibaren uygulanır.
  - Linee guida Eylül 2026'da yayımlanmamıştı. MIM nota 2306 (3.9.2026): "Poiché le Linee Guida sono ancora in fase di redazione…"
  - Yeni planlarda "Scienze sperimentali" tek ders oluyor.
  - İkincil (basın) + Birincil\* (MIM notunun kopyası).
  - Kaynaklar: [Orizzonte Scuola, riforma al via 2026/27](https://www.orizzontescuola.it/riforma-istituti-tecnici-al-via-dal-2026-27-come-cambia-la-struttura-oraria-cosa-cambia-per-docenti-scuole-e-studenti/); [Orizzonte Scuola, primi orientamenti](https://www.orizzontescuola.it/riforma-2026-istruzione-tecnica-ministero-invia-alle-scuole-i-primi-orientamenti-per-la-progettazione-centrali-unita-di-apprendimento-e-compiti-di-realta/); [MIM Nota prot. 2306 del 03.09.2026](https://www.orizzontescuola.it/wp-content/uploads/2026/09/Nota-prot.-n.-2306-del-03-09-2026.pdf); [Tecnica della Scuola, guida operativa](https://www.tecnicadellascuola.it/riforma-istituti-tecnici-la-guida-operativa-e-il-kit-per-accompagnare-le-scuole); [Orizzonte Scuola, scienze sperimentali disciplina unica](https://www.orizzontescuola.it/quadri-orario-nuovi-istituti-tecnici-dalle-classi-prime-del-2026-27-scienze-sperimentali-disciplina-unica-modifiche-anche-alle-classi-di-concorso/)
- **Dir. 69/2012:** teknik enstitü opzioni için ikinci iki yıl ve beşinci yıl Linee guida'sı; GU n. 253, 29.10.2012, S.O. n. 200. İkincil (önceki notlar; bu oturumda yeniden açılmadı). — [Dir. 69/2012 metni (Meucci-Fanoli)](https://www.meuccifanoli.edu.it/images/Normativa/direttiva-ministeriale-69-del-1-agosto-2012-linee-guida-opzioni-istituti-tecnici.pdf); [CNOS-FAP, scheda di sintesi](https://www.cnos-fap.it/sites/default/files/newsletter/2013/December/Scheda%20di%20sintesi.pdf)

### Inferences
- **R3c (ozmotik basınç dayanağı) doğru.** Belge 2'deki "yayınevi kopyası" (Pearson) şimdi INDIRE kopyası ve ekonomik alan eki (A.1) ile de destekleniyor. Önerilen ifade: "Dayanak: Dir. 57/2010, ilk iki yıl, All. A.2 (settore tecnologico) ve All. A.1 (settore economico), Scienze integrate (Chimica): 'proprietà colligative' [Statü: İkincil — INDIRE ve Pearson kopyaları]." Ozmotik basınç tanım gereği dört koligatif özellikten biri ve satırda adıyla geçmiyor. Bu yüzden Belge'nin "koligatif özellik düzeyinde girer" ifadesi doğru.
- **Karar etkisi yok.** Dayanak $C_{max}$'ta zaten var, birleşimde teknik enstitüler de yer alıyor. Scienze applicate ve sportivo kontrolü yalnızca "yalnızca birleşimde" etiketini değiştirebilir, matrisi değil.
- **T7, D.M. 29/2026:** satır doğru; tarih eklenmeli; statü "Birincil" değil "İkincil" olmalı (resmî metin görülmedi). Yeni ders adlarının (Scienze sperimentali) 2027 kohortuyla ilgisi yok.
- **T6:** Dir. 69/2012 eklenmeli. Opzioni dersleri teknik uzmanlık içeriği ekler ve 3a ile dışlanır. **Karar etkisi yok.**
- **T4:** "MIM DD 92/2024" atfı ya kaldırılmalı ya da "doğrulanmalı" yazılmalı. Bu kararname filiera deneyiyle ilgili ve Linee guida atfı içerdiği görülmedi.

### Gaps
- Dir. 57/2010'un resmî metni (MIUR/MIM) açılamadı; INDIRE ve Pearson kopyaları da yalnızca özetten okundu.
- Dir. 4/2012'de ozmotik basıncın adıyla geçip geçmediği (ör. "Chimica analitica", "Biologia, microbiologia" kartlarında) kontrol edilemedi. Geçiyorsa 3c için daha güçlü bir dayanak olur, ama karar değişmez.
- D.M. 29/2026'nın resmî metni ve ekleri görülmedi.

---

## 6. Mesleki enstitüler: D.Lgs. 61/2017, D.I. 92/2018, D.M. 766/2019

### Takeaway
Satır **doğru**. D.Lgs. 61/2017 m.13 c.1, D.P.R. 87/2010'u 2022/23'ten itibaren kaldırır (lafız önceki notta kopyalardan alındı, bu oturumda yeniden görülmedi). D.I. 92/2018, m.3 c.3 uyarınca çıkış profilleri yönetmeliğidir. D.M. 766/2019 ise D.I. 92/2018 m.4 c.4 uyarınca çıkarılmış Linee guida'dır (bu oturumda resmî ve bölgesel atıflarla teyit edildi). 2027 mezunları (2022/23 girişli) tamamen yeni düzende. "İçerik tanımı D.I. 92/2018'in eklerindedir" ifadesi **kısmen doğru**.

### Cited Findings
- D.M. 23 agosto 2019, n. 766 = "Linee guida per favorire e sostenere il nuovo assetto didattico e organizzativo dei percorsi di istruzione professionale". Atıflar onu "in attuazione dell'articolo 4, comma 4" D.I. 92/2018 olarak tanımlıyor. D.I. 92/2018 = "Regolamento recante la disciplina dei profili di uscita degli indirizzi di studio dei percorsi di istruzione professionale", D.Lgs. 61/2017 m.3 c.3 uyarınca. İkincil (MIM notu, USR ve bölge belgeleri). — [MIM nota 5726 del 10.4.2020 (USR Veneto)](https://istruzioneveneto.gov.it/wp-content/uploads/2020/04/protocollo-.AOODGOSV.REGISTRO-UFFICIALEU.0005726.10-04-2020.pdf); [regioni.it](https://www.regioni.it/download/news/644869/); [Regione Piemonte](https://www.regione.piemonte.it/web/media/49171/download); [MIM–E.N.I.P. protokolü](https://rovigo.istruzioneveneto.gov.it/wp-content/uploads/2024/11/102708-REG-1732276088670-12.11.2024-Protocollo-di-intesa-MIM-E.N.I.P.-G.C.T.pdf)
- D.Lgs. 61/2017 m.13 c.1: "A decorrere dall'anno scolastico 2022/2023 il decreto del Presidente della Repubblica 15 marzo 2010, n. 87, e successive modificazioni, e' abrogato." İkincil (önceki notta CISL Scuola ve USR Emilia-Romagna kopyaları; bu oturumda arama lafzı döndürmedi). — [CISL Scuola, D.Lgs. 61/2017](https://www.cislscuola.it/uploads/media/Dlvo61_2017_IstruzioneProfessionale.pdf); [USR Emilia-Romagna kopyası](https://www.istruzioneer.gov.it/wp-content/uploads/2019/02/dlgs-61-2017.pdf)
- Yeni düzen 2018/19 birinci sınıflarından başladı ve 2022/23'te bütün sınıflara ulaştı. İkincil (önceki notlar). — [INDIRE, I Nuovi professionali](https://nuoviprofessionali.indire.it/wp-content/uploads/2019/06/I-Nuovi-professionali-perPTOF.pdf)
- **Allegato A lafzı (yerel birincil):** "…coerenti con le Indicazioni nazionali per i licei e con le Linee guida per gli istituti tecnici e per gli istituti professionali, soprattutto in vista degli Esami di Stato." — `allA.txt` 13–15. satırlar

### Inferences
- **P3, P4:** "Doğrulanmalı" yerine "İkincil (resmî atıflarla teyit)" yazılmalı. **Yalnızca atıf.**
- **P5:** 2022/23'te giren kohort hiçbir sınıfta eski D.P.R. 87/2010 düzenine tabi olmadı. Doğru.
- **P6:** Yeni düzende "Linee guida" adını taşıyan metin D.M. 766/2019'dur. Eski düzenin Linee guida'sı (Dir. 65/2010, Dir. 5/2012, Dir. 70/2012) D.P.R. 87/2010 ile birlikte bu kohort için geçersiz. Yorum makul. **Yok.**
- **P7:** Profiller ve öğrenme sonuçları D.I. 92/2018 eklerinde. Bilgi ve beceri düzeyindeki açılım ise büyük olasılıkla D.M. 766/2019 eklerinde; bu doğrulanmadı. Önerilen ifade: "İçerik tanımı D.I. 92/2018 ekleri ve D.M. 766/2019 eklerindedir." Mesleki ayağa bağlı bir sınır ya da 3c öğesi olmadığı için **karar etkisi yok.**

### Gaps
- D.M. 766/2019 eklerinin içeriği (yetkinlik, beceri, bilgi açılımı) ve D.I. 92/2018 m.4 c.4'ün lafzı okunamadı.
- D.Lgs. 61/2017 m.13 c.1 lafzı bu oturumda yeniden görülemedi.

---

## 7. "Karakteristik": Bileşim ve Kontrol sırası

### Takeaway
"Bileşim" Allegato A'nın lafzıyla doğru: liseler için Indicazioni, teknik ve mesleki enstitüler için Linee guida. Lise tarafının kapsamı da doğru: 2010 Indicazioni'sindeki bütün liseler ve sportivo. Liceo del Made in Italy (D.P.R. 222/2024) 2027'de mezun vermediği için dışarıda kalır; bu belirtilmeli. "Kontrol sırası" mantıklı. Ancak scienze applicate kimyada ordinario'dan geniş, sportivo'nun OSA'sı ise belirsiz. Bu yüzden 3c'deki "koşullu" ibaresi bilgi amaçlı kalmalı; karar değişmiyor.

### Cited Findings
- Allegato A, ikinci paragraf: "Indicazioni nazionali per i licei … Linee guida per gli istituti tecnici e per gli istituti professionali". — `allA.txt` 13–15. satırlar (yerel birincil)
- D.P.R. 222/2024, D.P.R. 89/2010'a yeni bir lise (Made in Italy) ve "allegato A-ter" ekliyor. İkincil (FLC CGIL kopyası). — [FLC CGIL, D.P.R. 222/2024](https://flcgil.it/files/pdf/20250220/decreto-del-presidente-della-repubblica-222-del-25-novembre-2024-regolamento-del-percorso-liceale-del-made-in-italy.pdf)
- Scienze applicate kimya farkı: bölüm 2. Sportivo belirsizliği: bölüm 4.

### Inferences
- "Licei = 2010 Indicazioni'deki bütün lise türleri ve liceo sportivo" ifadesine şu eklenebilir: "Liceo del Made in Italy (D.P.R. 222/2024) 2024/25'te başladı, 2027'de mezunu yok; $C_{max}$'a girmez." D.P.R. 222/2024'ün yürürlük yılı bu oturumda doğrudan görülmedi; "2024/25" çıkarımdır.
- Kontrol sırasındaki "yalnızca birleşimde" işareti, R3c'de ozmotik basınç için şimdilik doğru: ordinario'da yok, Dir. 57/2010'da var. Scienze applicate ve sportivo'da bulunsa bile işaret değişir ama öğe matriste aynı derinlikte kalır.

### Gaps
- Dört yıllık deneysel lise ve teknik programlar (2027'de mezun verebilecek, 2023/24 girişli dört yıllık sınıflar) aynı Indicazioni ve Linee guida'yı mı kullanıyor? Bu araştırılmadı; Allegato A bunları ayrıca anmıyor.

---

## 8. Tabloda eksik olup önemli olanlar

### Takeaway
Eksiklerin hiçbiri çalışma kararını değiştirmiyor. Hepsi atıf bütünlüğü ve gelecekteki güncelleme izlemesi içindir.

### Cited Findings
- **Indicazioni'yi öngören hüküm:** D.P.R. 89/2010 m.13 c.10 lett. a). — [Normattiva](https://www.normattiva.it/eli/id/2010/12/14//010G0232/CONSOLIDATED)
- **D.I. 211/2010 GU kaydı:** GU n.291, 14.12.2010, S.O. n.275. — [Normattiva](https://www.normattiva.it/eli/id/2010/12/14//010G0232/CONSOLIDATED)
- **D.P.R. 52/2013 GU kaydı:** GU n.113, 16.5.2013. — [Gazzetta Ufficiale](https://www.gazzettaufficiale.it/atto/serie_generale/caricaArticolo?art.versione=1&art.idGruppo=0&art.flagTipoArticolo=0&art.codiceRedazionale=13G00095&art.idArticolo=2&art.idSottoArticolo=1&art.idSottoArticolo1=10&art.dataPubblicazioneGazzetta=2013-05-16&art.progressivo=0)
- **Dir. 69/2012** (teknik opzioni Linee guida'sı). — [Meucci-Fanoli kopyası](https://www.meuccifanoli.edu.it/images/Normativa/direttiva-ministeriale-69-del-1-agosto-2012-linee-guida-opzioni-istituti-tecnici.pdf)
- **D.M. 29/2026 tarihi** (19.2.2026) ve Linee guida'nın durumu (nota 2306, 3.9.2026). — [Orizzonte Scuola](https://www.orizzontescuola.it/riforma-2026-istruzione-tecnica-ministero-invia-alle-scuole-i-primi-orientamenti-per-la-progettazione-centrali-unita-di-apprendimento-e-compiti-di-realta/)
- **Yeni lise Indicazioni'sinin Ekim 2026 durumu:** Consiglio di Stato görüşü ve GU yayımı görülmedi (bölüm 3).
- **Liceo del Made in Italy'nin dışarıda kalması** (bölüm 7).

### Inferences
- Tablonun "Statü ve zaman damgası" sütununa her satır için bir GU veya tarih referansı eklemek, 2027 DM'si çıktığında yapılacak karşılaştırmayı kolaylaştırır.

### Gaps
- Dir. 4/2012 ve D.M. 766/2019 metinleri açılamadığı için bu belgelerde Allegato A'ya yakın ama tabloda izlenmeyen bir kimya veya biyoloji öğesi olup olmadığı bilinmiyor. Birleşim zaten çok geniş kabul edildiği ve 3a uygulandığı için karar riski düşük.

---

## 9. NCERT Ü7: Sınıf 11 Biyoloji, Bölüm 7 "Structural Organisation in Animals"

### Takeaway
Belge 2'nin iddiası **doğru**. ncert.nic.in'deki kebo107.pdf (Reprint 2026-27) yalnızca **7.1 Organ and Organ System** ve **7.2 Frogs** bölümlerini içeriyor. Dokular yalnızca geçerken anılıyor.

Alternatif okuma güncel baskı için **yanlış**: "7.1 Animal Tissues (sinir dokusu hariç) duruyor, kurbağa 7.3". Rasyonelleştirmede şunlar tamamen silindi:
- 7.1 Animal Tissues ve alt bölümleri 7.1.1–7.1.4 (sinir dokusu dahil),
- 7.3 Earthworm,
- 7.4 Cockroach.

Statü "Birincil" değil "Birincil\*": resmî PDF'in yalnızca arama özeti görüldü. NCERT'in resmî "rationalised content" listesi bulunamadı.

### Cited Findings
- **Güncel baskı:** ncert.nic.in/textbook/pdf/kebo107.pdf, "STRUCTURAL ORGANISATION IN ANIMALS"; arama özetine göre bölümler 7.1 "Organ and Organ System" ve 7.2 "Frogs"; etiket "Reprint 2026-27". Birincil\*. — [NCERT, kebo107.pdf](https://ncert.nic.in/textbook/pdf/kebo107.pdf)
- **Diğer kopyalar:** Collegedunia "Reprint 2025-26" etiketli. Jupiter Academy kopyası 2022-23 tarihli ve toprak solucanı ile hamamböceğini içeriyor (rasyonelleştirme öncesi). İkincil. — [Collegedunia kopyası](https://image-static.collegedunia.com/public/image/kebo107_7ecd6984399cdd4d59e15d69123dde29.pdf); [Jupiter Academy kopyası](https://jupiteracademy.co.in/wp-content/uploads/2022/07/kebo107.pdf)
- **Silinenler listesi** (2023-24 ve 2024-25 oturumları): "7.1 Animal Tissues; 7.1.1 Epithelial Tissue; 7.1.2 Connective Tissue; 7.1.3 Muscle Tissue; 7.1.4 Neural Tissue; 7.3 Earthworm; 7.3.1 Morphology; 7.3.2 Anatomy; 7.4 Cockroach", ayrıca özet ve alıştırma parçaları. İkincil (yayınevi). — [MTG, Deleted Syllabus of Class 11 Biology (2023-24)](https://blog.mtg.in/deleted-syllabus-of-class-11-biology/); [CareerOrbits, NCERT rationalised syllabus for NEET](https://www.careerorbits.com/neet/ncert-rationalised-syllabus-for-neet-2025)
- **Rasyonelleştirme öncesi yapı:** 7.1 Animal Tissue, 7.2 Organ and organ system, 7.3 Earthworm, 7.4 Cockroach, 7.5 Frogs. İkincil. — [BYJU'S, Chapter 7](https://byjus.com/ncert-solutions-class-11-biology/chapter-7-structural-organisation-in-animals/)
- **Dokuların geçerken anılması:** "our heart consists of all the four types of tissues, i.e., epithelial, connective, muscular and neural". Önceki notta resmî PDF'in özetinden alıntılandı. Bu oturumda yalnızca ikincil bir çalışma sitesi kurbağa kalbi bağlamında aynı dörtlü listeyi aktardı. — [Canvas Classes, frog](https://www.canvasclasses.in/teach/class11-biology/frog-natural-history-and-morphology); [NCERT, kebo107.pdf](https://ncert.nic.in/textbook/pdf/kebo107.pdf)
- **Ayrı bir olayla karıştırılmamalı:** CBSE'nin 2020-21 pandemi dönemi "Deleted portions" listesi Bölüm 7'den hamamböceği sistemlerini çıkarıyordu. Bu, 2022-23 NCERT rasyonelleştirmesinden ayrı ve daha eski bir kesintidir. — [CBSE, Deleted portions Class XI 2020-21](https://cbseacademic.nic.in/web_material/CurriculumMain21/revisedsyllabi/Deduction/DELETEDBiology_2020-21.pdf)
- **CBSE Learning Framework:** 2023-24 müfredatına göre "*" kısmen rasyonelleştirilmiş, "**" tamamen silinmiş birimleri gösteriyor; özet hangi Bölüm 7 öğesinin hangi işareti taşıdığını göstermedi. — [CBSE, Biology Learning Framework](https://cbseacademic.nic.in/web_material/Manuals/Biology_LF.pdf)

### Inferences
- **Ü7a ve Ü7b doğru;** Ü7c'deki alternatif okuma güncel baskı için yanlış. Statü "Birincil\* (ncert.nic.in PDF'inin arama özeti; silinenler listesi ikincil)" olarak düzeltilmeli. **Yalnızca atıf.**
- **Ü7d (eski baskı) için eksik bir uyarı var.** "Eski baskı kullanılıyorsa toprak solucanı ve hamamböceği atlanır" doğru. Ama eski baskıda 7.1 Animal Tissue de var ve Allegato A "I tessuti animali" dediği için bu bölüm **atlanmamalı**: eski baskı, dokular için T'deki "başka kaynak"ın yerini tutabilir. Önerilen ek cümle: "Eski baskıda 7.1 Animal Tissue hayvan dokuları kaynağı olarak kullanılabilir." Matrise konu eklemiyor (dokular zaten $M_3$'te), yalnızca kaynak kullanım notu. **Karar etkisi yok.**
- "Kurbağa genel tanıma düzeyinde okunur" bir derinlik yorumudur ve dış kaynakla doğrulanacak bir iddia değildir. "nell'uomo" kapsam belirteciyle tutarlı.

### Gaps
- NCERT'in resmî "Rationalised Content in the Textbooks" listesi (2022) ve kebo107.pdf'in tam içerik tablosu doğrudan açılamadı; ncert.nic.in ağ politikasıyla engelli.
- Sınıf 11 için yeni NCF-SE kitabının hangi yıl çıkacağı bu oturumda araştırılmadı. Önceki notta kaynaklar çelişkiliydi (2026-27 ya da 2027-28). Ü7 atfı "Reprint 2026-27" baskısına sabit tutulmalı.
