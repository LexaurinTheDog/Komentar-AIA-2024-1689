# Kapitola III, oddíly 1–2 — Klasifikace vysoce rizikových systémů a požadavky na ně (čl. 6–15)

Kapitola III nařízení (EU) 2024/1689 tvoří normativní jádro celého AI aktu: nejprve vymezuje, které systémy AI jsou „vysoce rizikové" (oddíl 1, čl. 6–7), a poté stanoví sadu povinných technických a procesních požadavků, které musí každý takový systém splňovat (oddíl 2, čl. 8–15). Klasifikace spočívá na dvou kumulativních pilířích. Prvním je zařazení do harmonizačního rámce EU podle přílohy I (bezpečnostní komponenty výrobků podléhajících posuzování shody třetí stranou). Druhým je výslovné uvedení v příloze III, která taxativně vypočítává osm oblastí zvýšeného rizika — od biometrické identifikace a kritické infrastruktury přes vzdělávání a zaměstnanost až po migraci, správu hranic a výkon spravedlnosti. Zákonodárce tak preferuje přístup regulace založené na použití (*use-case based approach*) před regulací technologie jako takové.

Požadavky oddílu 2 (čl. 8–15) představují základní sadu povinností, jejichž splnění je předpokladem pro postup k posuzování shody upraveném v oddílech 4 a 5 a pro umístění systému na trh. Jedná se o horizontální požadavky platné pro všechny kategorie vysoce rizikových systémů AI bez ohledu na odvětví; specifické povinnosti jednotlivých aktérů (poskytovatelů, zavádějících subjektů, dovozců, distributorů) jsou pak rozvedeny v oddíle 3 (čl. 16–29). Systém řízení rizik (čl. 9), správa dat (čl. 10), technická dokumentace (čl. 11), vedení záznamů (čl. 12), transparentnost vůči zavádějícím subjektům (čl. 13), lidský dohled (čl. 14) a přesnost, robustnost a kybernetická bezpečnost (čl. 15) tvoří dohromady regulatorní minimum, bez jehož naplnění není možné vystavit EU prohlášení o shodě ani připojit označení CE.

Věcná provázanost oddílu 2 s dalšími částmi nařízení je zásadní: požadavky na data (čl. 10) doplňují pravidla ochrany osobních údajů plynoucí z GDPR (nařízení (EU) 2016/679), zejména zásady minimalizace a přesnosti; technická dokumentace (čl. 11) musí obsahovat náležitosti přílohy IV a je klíčovým podkladem pro notifikované orgány; lidský dohled (čl. 14) se prolíná se zákazem nepřijatelného rizika (čl. 5) a se zárukami pro systémy všeobecného použití (čl. 51–55). Posuzování shody pro systémy přílohy III probíhá zásadně jako interní kontrola (modul A), nestanoví-li příloha I přísné harmonizační právo vyžadující třetí stranu.

---

## Kapitola III — Vysoce rizikové systémy AI

**Oddíl 1 — Klasifikace systémů AI jako vysoce rizikových**

### Čl. 6 — Pravidla klasifikace vysoce rizikových systémů AI

**Doslovné znění (EN) — Article 6 — Classification rules for high-risk AI systems:**

> 1. Irrespective of whether an AI system is placed on the market or put into service independently of the products referred to in points (a) and (b), that AI system shall be considered to be high-risk where both of the following conditions are fulfilled:
>
> (a) the AI system is intended to be used as a safety component of a product, or the AI system is itself a product, covered by the Union harmonisation legislation listed in Annex I;
>
> (b) the product whose safety component pursuant to point (a) is the AI system, or the AI system itself as a product, is required to undergo a third-party conformity assessment, with a view to the placing on the market or the putting into service of that product pursuant to the Union harmonisation legislation listed in Annex I.
>
> 2. In addition to the high-risk AI systems referred to in paragraph 1, AI systems referred to in Annex III shall be considered to be high-risk.
>
> 3. By derogation from paragraph 2, an AI system referred to in Annex III shall not be considered to be high-risk where it does not pose a significant risk of harm to the health, safety or fundamental rights of natural persons, including by not materially influencing the outcome of decision making.
>
> The first subparagraph shall apply where any of the following conditions is fulfilled:
>
> (a) the AI system is intended to perform a narrow procedural task;
>
> (b) the AI system is intended to improve the result of a previously completed human activity;
>
> (c) the AI system is intended to detect decision-making patterns or deviations from prior decision-making patterns and is not meant to replace or influence the previously completed human assessment, without proper human review; or
>
> (d) the AI system is intended to perform a preparatory task to an assessment relevant for the purposes of the use cases listed in Annex III.
>
> Notwithstanding the first subparagraph, an AI system referred to in Annex III shall always be considered to be high-risk where the AI system performs profiling of natural persons.
>
> 4. A provider who considers that an AI system referred to in Annex III is not high-risk shall document its assessment before that system is placed on the market or put into service. Such provider shall be subject to the registration obligation set out in Article 49(2). Upon request of national competent authorities, the provider shall provide the documentation of the assessment.
>
> 5. The Commission shall, after consulting the European Artificial Intelligence Board (the ‘Board’), and no later than 2 February 2026, provide guidelines specifying the practical implementation of this Article in line with Article 96 together with a comprehensive list of practical examples of use cases of AI systems that are high-risk and not high-risk.
>
> 6. The Commission is empowered to adopt delegated acts in accordance with Article 97 in order to amend paragraph 3, second subparagraph, of this Article by adding new conditions to those laid down therein, or by modifying them, where there is concrete and reliable evidence of the existence of AI systems that fall under the scope of Annex III, but do not pose a significant risk of harm to the health, safety or fundamental rights of natural persons.
>
> 7. The Commission shall adopt delegated acts in accordance with Article 97 in order to amend paragraph 3, second subparagraph, of this Article by deleting any of the conditions laid down therein, where there is concrete and reliable evidence that this is necessary to maintain the level of protection of health, safety and fundamental rights provided for by this Regulation.
>
> 8. Any amendment to the conditions laid down in paragraph 3, second subparagraph, adopted in accordance with paragraphs 6 and 7 of this Article shall not decrease the overall level of protection of health, safety and fundamental rights provided for by this Regulation and shall ensure consistency with the delegated acts adopted pursuant to Article 7(1), and take account of market and technological developments.

**Pracovní překlad (CZ):**

> 1. Bez ohledu na to, zda je systém AI uveden na trh nebo uveden do provozu nezávisle na výrobcích uvedených v písmenech a) a b), považuje se takový systém AI za vysoce rizikový, jsou-li splněny obě tyto podmínky:
>
> (a) systém AI je určen k použití jako bezpečnostní komponenta výrobku nebo je sám výrobkem, na který se vztahuje harmonizační právní předpis Unie uvedený v příloze I;
>
> (b) výrobek, jehož bezpečnostní komponentou podle písmene a) je systém AI, nebo systém AI sám jako výrobek podléhá podle harmonizačního právního předpisu Unie uvedeného v příloze I posuzování shody třetí stranou s ohledem na uvedení tohoto výrobku na trh nebo jeho uvedení do provozu.
>
> 2. Kromě vysoce rizikových systémů AI uvedených v odstavci 1 se za vysoce rizikové považují systémy AI uvedené v příloze III.
>
> 3. Odchylně od odstavce 2 se systém AI uvedený v příloze III nepovažuje za vysoce rizikový, pokud nepředstavuje značné riziko újmy na zdraví, bezpečnosti nebo základních právech fyzických osob, a to ani tím, že by podstatně ovlivňoval výsledek rozhodování.
>
> První pododstavec se použije, je-li splněna některá z těchto podmínek:
>
> (a) systém AI je určen k provádění úzce vymezené procesní úlohy;
>
> (b) systém AI je určen ke zlepšení výsledku dříve dokončené lidské činnosti;
>
> (c) systém AI je určen k zjišťování vzorců rozhodování nebo odchylek od dřívějších vzorců rozhodování a není určen k nahrazení ani ovlivnění dříve dokončeného lidského posouzení bez přiměřeného lidského přezkumu; nebo
>
> (d) systém AI je určen k provádění přípravných úloh pro posouzení relevantní pro účely případů použití uvedených v příloze III.
>
> Bez ohledu na první pododstavec se systém AI uvedený v příloze III považuje vždy za vysoce rizikový, provádí-li profilování fyzických osob.
>
> 4. Poskytovatel, který se domnívá, že systém AI uvedený v příloze III není vysoce rizikový, zdokumentuje toto posouzení před tím, než je daný systém uveden na trh nebo do provozu. Tento poskytovatel podléhá registrační povinnosti stanovené v čl. 49 odst. 2. Na žádost příslušných vnitrostátních orgánů poskytovatel dokumentaci posouzení předloží.
>
> 5. Komise po konzultaci s Evropskou radou pro umělou inteligenci (dále jen „rada") a nejpozději do 2. února 2026 vydá pokyny specifikující praktické provádění tohoto článku v souladu s článkem 96 spolu s vyčerpávajícím seznamem praktických příkladů případů použití systémů AI, které jsou vysoce rizikové, a případů použití, které vysoce rizikové nejsou.
>
> 6. Komisi je svěřena pravomoc přijímat akty v přenesené pravomoci v souladu s článkem 97 za účelem změny odstavce 3 druhého pododstavce tohoto článku přidáním nových podmínek k podmínkám v něm stanoveným nebo jejich změnou, existují-li konkrétní a spolehlivé důkazy o existenci systémů AI, které spadají do oblasti působnosti přílohy III, avšak nepředstavují značné riziko újmy na zdraví, bezpečnosti nebo základních právech fyzických osob.
>
> 7. Komise přijme akty v přenesené pravomoci v souladu s článkem 97 za účelem změny odstavce 3 druhého pododstavce tohoto článku vypuštěním některé z podmínek v něm stanovených, existují-li konkrétní a spolehlivé důkazy, že je to nezbytné pro zachování úrovně ochrany zdraví, bezpečnosti a základních práv stanovené tímto nařízením.
>
> 8. Každá změna podmínek stanovených v odstavci 3 druhém pododstavci přijatá v souladu s odstavci 6 a 7 tohoto článku nesmí snížit celkovou úroveň ochrany zdraví, bezpečnosti a základních práv stanovenou tímto nařízením a musí zajišťovat soulad s akty v přenesené pravomoci přijatými podle čl. 7 odst. 1 a přihlížet k vývoji trhu a technologickému rozvoji.

**Výklad:** Článek 6 zavádí dvojstupňový klasifikační mechanismus, který je klíčovým vstupním bodem celého regulačního rámce AI aktu. Podstatou je rozlišení dvou okruhů vysoce rizikových systémů: systémů integrovaných do výrobků podléhajících stávajícímu unijnímu harmonizačnímu právu (odst. 1, příloha I — zahrnuje například strojní zařízení, zdravotnické prostředky, výtahy, hračky či vozidla) a systémů samotných spadajících do oblastí vyjmenovaných v příloze III (odst. 2).

Odstavec 3 přináší zásadní novum oproti původnímu návrhu Komise: zákonodárce zakotvil výjimku z klasifikace, podle níž systémy přílohy III nemusejí být považovány za vysoce rizikové, pokud nepředstavují značné riziko. Podmínky výjimky (úzce vymezená procesní úloha, zlepšení dříve dokončené lidské činnosti, detekce vzorců bez nahrazení lidského posouzení, přípravná úloha) musejí být splněny restriktivně — zákonodárce výslovně vylučuje aplikaci výjimky na systémy provádějící profilování fyzických osob, neboť profilování představuje inherentně závažný zásah do základních práv (srov. recitál 55 a 56). Dokumentační povinnost poskytovatele při uplatnění výjimky (odst. 4) zajišťuje dohledatelnost a zpětnou kontrolu příslušnými orgány.

Odkaz na registrační povinnost (čl. 49 odst. 2) tvoří důležitou pojistku: poskytovatel se nemůže jednoduše vyhnout povinnostem tím, že si interně kvalifikuje systém jako nevysoce rizikový, aniž by tato kvalifikace byla přístupná veřejnému dozoru. Zmocnění Komise přijímat akty v přenesené pravomoci (odst. 6 a 7) umožňuje dynamickou adaptaci přílohy III na technologický vývoj, avšak s imperativní klauzulí, že nelze snižovat celkovou úroveň ochrany — tento princip non-regression je výslovně zakotven v odst. 8. Pokyny podle odst. 5 budou mít zásadní praktický význam pro poskytovatele zejména v hraničních případech.

#### F. Kazuistika

**1. Modelová situace.** Česká technologická společnost TalentFlow s.r.o. (poskytovatel) vyvinula systém AI pro personální agentury se dvěma moduly: modul A pouze extrahuje údaje ze zaslaných životopisů a převádí je do strukturované databáze (vzdělání, praxe, certifikace); modul B uchazeče automaticky boduje a řadí podle predikované vhodnosti pro inzerovanou pozici. TalentFlow hodlá oba moduly uvést na trh jako „nevysoce rizikové" s odůvodněním, že jde jen o přípravné úlohy a konečné rozhodnutí činí vždy personalista. Důkazně je třeba obstarat: technickou dokumentaci a funkční specifikaci obou modulů, popis určeného účelu v návodu k použití, marketingové materiály, záznam posouzení dle čl. 6 odst. 4 a doklad o registraci dle čl. 49 odst. 2.

**2. Právní otázka.** Lze systém AI hodnotící a řadící uchazeče o zaměstnání vyjmout z klasifikace vysoce rizikového systému na základě výjimky čl. 6 odst. 3, ačkoli spadá do oblasti přílohy III bodu 4?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 6 odst. 2 a 3 — klasifikace systémů přílohy III a výjimka pro systémy nepředstavující značné riziko; odst. 3 třetí pododstavec (vyloučení výjimky při profilování).
- *Související ustanovení téhož nařízení:* čl. 6 odst. 4 (dokumentace posouzení), čl. 49 odst. 2 (registrace v databázi EU), příloha III bod 4 písm. a) (nábor, třídění žádostí, hodnocení uchazečů), čl. 3 bod 52 (profilování odkazem na GDPR), čl. 96 (pokyny Komise).
- *Související předpisy:* GDPR — čl. 4 bod 4 (definice profilování: hodnocení osobních aspektů, zejm. pracovního výkonu), čl. 22 (automatizované individuální rozhodování); směrnice 2000/78/ES a antidiskriminační zákon č. 198/2009 Sb. (rovný přístup k zaměstnání).
- *Judikatura:* SDEU C-634/21 SCHUFA (7. 12. 2023) — automatizované vytvoření skóre je rozhodnutím ve smyslu čl. 22 GDPR, vychází-li z něj třetí strana rozhodujícím způsobem; závěr je přenositelný: rozhodná je faktická váha výstupu, nikoli jeho označení za pouhé „doporučení".

**4. Subsumpce.** Oba moduly spadají do oblasti přílohy III bodu 4, takže platí presumpce vysoké rizikovosti dle odst. 2. Modul A (extrakce dat) naplňuje podmínku odst. 3 písm. a) — úzce vymezená procesní úloha, případně písm. d) — přípravná úloha; neprovádí hodnocení osobních aspektů, tedy ani profilování. Modul B vyhodnocuje osobní aspekty fyzických osob (predikce pracovní vhodnosti), což je profilování dle čl. 4 bodu 4 GDPR — výjimka je dle odst. 3 třetího pododstavce vyloučena bez ohledu na splnění podmínek písm. a)–d). Sporná zůstává hranice, kde končí strukturace údajů a začíná jejich hodnocení (např. automatické označování „relevantní praxe").

**5. Řešení.** Modul A lze uvést na trh mimo režim vysoké rizikovosti jen při splnění procesních pojistek: poskytovatel posouzení zdokumentuje před uvedením na trh (odst. 4), systém zaregistruje dle čl. 49 odst. 2 a dokumentaci na žádost dozorového orgánu předloží. Modul B je vysoce rizikový vždy — TalentFlow musí splnit požadavky čl. 8–15, provést posouzení shody (čl. 43) a registrovat systém. Argument, že „rozhoduje personalista", na klasifikaci nic nemění; rozhodný je určený účel systému.

**6. Varianty.** (i) Pokud by modul B nadto automaticky vyřazoval uchazeče pod prahem skóre bez lidského přezkumu, přistoupil by vedle klasifikace i rozpor s čl. 22 GDPR. (ii) Pokud by systém pouze zpětně analyzoval vzorce již ukončených náborů pro statistiku, bez vlivu na jednotlivá posouzení, šlo by o podmínku odst. 3 písm. c) a výjimka by se uplatnila.

#### G. Protiargumenty a rizika

- „I extrakce dat je profilováním, protože selektuje relevantní údaje o osobě." Neutralizace: profilování pojmově vyžaduje *hodnocení* či predikci osobních aspektů (čl. 4 bod 4 GDPR), nikoli pouhý přepis; hranici je nutno doložit funkční specifikací — jakmile modul údaje váží či třídí podle „vhodnosti", argument poskytovatele padá.
- „Výjimka odst. 3 je samodeklaratorní, poskytovatel si ji přizná sám." Riziko zneužití je reálné; neutralizují je dokumentační a registrační povinnost (odst. 4, čl. 49 odst. 2) a možnost dozorového orgánu kvalifikaci kdykoli přezkoumat — nesprávné posouzení jde plně k tíži poskytovatele.
- Slabé místo: do vydání pokynů Komise dle odst. 5 (termín 2. 2. 2026) chybí autoritativní katalog příkladů; hraniční případy poloautomatického předtřídění zůstávají výkladově nejisté a posouzení je třeba průběžně revidovat i s ohledem na delegované akty dle odst. 6 a 7.

#### H. Praktický závěr

Čl. 6 je vstupní branou celého režimu: nejprve se zkoumá cesta přes přílohu I (odst. 1 — bezpečnostní komponenty výrobků s posuzováním shody třetí stranou), poté přes přílohu III (odst. 2) a teprve následně případná výjimka (odst. 3), která je u profilování vyloučena. Kdo výjimku uplatní, musí ji předem zdokumentovat a registrovat se.

**Checklist (poskytovatel / advokát / dozorový orgán):**
- [ ] Ověřit, zda systém je bezpečnostní komponentou výrobku dle přílohy I podléhajícího posouzení shody třetí stranou (odst. 1).
- [ ] Subsumovat určený účel pod konkrétní bod přílohy III (odst. 2).
- [ ] Vyloučit profilování fyzických osob; jinak výjimka odst. 3 nepřipadá v úvahu.
- [ ] Posouzení o neexistenci značného rizika zdokumentovat před uvedením na trh (odst. 4) a registrovat systém dle čl. 49 odst. 2.
- [ ] Sledovat pokyny Komise dle odst. 5 a akty v přenesené pravomoci dle odst. 6 a 7.

**Typicky rozhodné důkazy / podklady:** technická dokumentace a funkční specifikace, popis určeného účelu a návod k použití, marketingová komunikace, záznam posouzení dle odst. 4, doklad o registraci dle čl. 49 odst. 2.

---

### Čl. 7 — Změny přílohy III

**Doslovné znění (EN) — Article 7 — Amendments to Annex III:**

> 1. The Commission is empowered to adopt delegated acts in accordance with Article 97 to amend Annex III by adding or modifying use-cases of high-risk AI systems where both of the following conditions are fulfilled:
>
> (a) the AI systems are intended to be used in any of the areas listed in Annex III;
>
> (b) the AI systems pose a risk of harm to health and safety, or an adverse impact on fundamental rights, and that risk is equivalent to, or greater than, the risk of harm or of adverse impact posed by the high-risk AI systems already referred to in Annex III.
>
> 2. When assessing the condition under paragraph 1, point (b), the Commission shall take into account the following criteria:
>
> (a) the intended purpose of the AI system;
>
> (b) the extent to which an AI system has been used or is likely to be used;
>
> (c) the nature and amount of the data processed and used by the AI system, in particular whether special categories of personal data are processed;
>
> (d) the extent to which the AI system acts autonomously and the possibility for a human to override a decision or recommendations that may lead to potential harm;
>
> (e) the extent to which the use of an AI system has already caused harm to health and safety, has had an adverse impact on fundamental rights or has given rise to significant concerns in relation to the likelihood of such harm or adverse impact, as demonstrated, for example, by reports or documented allegations submitted to national competent authorities or by other reports, as appropriate;
>
> (f) the potential extent of such harm or such adverse impact, in particular in terms of its intensity and its ability to affect multiple persons or to disproportionately affect a particular group of persons;
>
> (g) the extent to which persons who are potentially harmed or suffer an adverse impact are dependent on the outcome produced with an AI system, in particular because for practical or legal reasons it is not reasonably possible to opt-out from that outcome;
>
> (h) the extent to which there is an imbalance of power, or the persons who are potentially harmed or suffer an adverse impact are in a vulnerable position in relation to the deployer of an AI system, in particular due to status, authority, knowledge, economic or social circumstances, or age;
>
> (i) the extent to which the outcome produced involving an AI system is easily corrigible or reversible, taking into account the technical solutions available to correct or reverse it, whereby outcomes having an adverse impact on health, safety or fundamental rights, shall not be considered to be easily corrigible or reversible;
>
> (j) the magnitude and likelihood of benefit of the deployment of the AI system for individuals, groups, or society at large, including possible improvements in product safety;
>
> (k) the extent to which existing Union law provides for:
>
> (i) effective measures of redress in relation to the risks posed by an AI system, with the exclusion of claims for damages;
>
> (ii) effective measures to prevent or substantially minimise those risks.
>
> 3. The Commission is empowered to adopt delegated acts in accordance with Article 97 to amend the list in Annex III by removing high-risk AI systems where both of the following conditions are fulfilled:
>
> (a) the high-risk AI system concerned no longer poses any significant risks to fundamental rights, health or safety, taking into account the criteria listed in paragraph 2;
>
> (b) the deletion does not decrease the overall level of protection of health, safety and fundamental rights under Union law.
>
> SECTION 2
>
> Requirements for high-risk AI systems

**Pracovní překlad (CZ):**

> 1. Komisi je svěřena pravomoc přijímat akty v přenesené pravomoci v souladu s článkem 97 za účelem změny přílohy III přidáním nebo změnou případů použití vysoce rizikových systémů AI, jsou-li splněny obě tyto podmínky:
>
> (a) systémy AI jsou určeny k použití v některé z oblastí uvedených v příloze III;
>
> (b) systémy AI představují riziko újmy na zdraví a bezpečnosti nebo nepříznivého dopadu na základní práva a toto riziko je rovnocenné nebo větší než riziko újmy nebo nepříznivého dopadu, které představují vysoce rizikové systémy AI již uvedené v příloze III.
>
> 2. Při posuzování podmínky podle odstavce 1 písm. b) přihlédne Komise k těmto kritériím:
>
> (a) určenému účelu systému AI;
>
> (b) rozsahu, v jakém byl systém AI použit nebo v jakém je pravděpodobné, že bude použit;
>
> (c) povaze a množství dat zpracovaných a použitých systémem AI, zejména zda jsou zpracovávány zvláštní kategorie osobních údajů;
>
> (d) rozsahu, v jakém systém AI jedná autonomně, a možnosti, aby člověk zvrátil rozhodnutí nebo doporučení, která mohou vést k potenciální újmě;
>
> (e) rozsahu, v jakém použití systému AI již způsobilo újmu na zdraví a bezpečnosti, mělo nepříznivý dopad na základní práva nebo vyvolalo závažné obavy ohledně pravděpodobnosti takové újmy nebo nepříznivého dopadu, jak dokládají například zprávy nebo zdokumentovaná tvrzení předložená příslušným vnitrostátním orgánům nebo jiné zprávy, je-li to vhodné;
>
> (f) potenciálním rozsahem takové újmy nebo takového nepříznivého dopadu, zejména z hlediska jeho intenzity a schopnosti postihovat více osob nebo nepřiměřeně postihovat určitou skupinu osob;
>
> (g) rozsahu, v jakém jsou osoby, které mohou utrpět újmu nebo být nepříznivě dotčeny, závislé na výsledku, který systém AI produkuje, zejména proto, že z praktických nebo právních důvodů není rozumně možné tomuto výsledku se vyhnout;
>
> (h) rozsahu, v jakém existuje nerovnováha sil nebo jsou osoby, které mohou utrpět újmu nebo být nepříznivě dotčeny, v postavení zranitelné vůči zavádějícímu subjektu systému AI, zejména z důvodu svého postavení, pravomocí, znalostí, hospodářských nebo sociálních poměrů nebo věku;
>
> (i) rozsahu, v jakém je výsledek zahrnující systém AI snadno opravitelný nebo zvrátitelný, s přihlédnutím k technickým řešením dostupným pro jeho opravu nebo zvrácení, přičemž výsledky mající nepříznivý dopad na zdraví, bezpečnost nebo základní práva se nepovažují za snadno opravitelné nebo zvrátitelné;
>
> (j) rozsahu a pravděpodobnosti přínosu nasazení systému AI pro jednotlivce, skupiny nebo společnost jako celek, včetně možného zlepšení bezpečnosti výrobků;
>
> (k) rozsahu, v jakém stávající právo Unie stanoví:
>
> (i) účinné prostředky nápravy ve vztahu k rizikům, která systém AI představuje, s výjimkou nároků na náhradu škody;
>
> (ii) účinná opatření k předcházení těmto rizikům nebo jejich podstatnému omezení.
>
> 3. Komisi je svěřena pravomoc přijímat akty v přenesené pravomoci v souladu s článkem 97 za účelem změny seznamu v příloze III odstraněním vysoce rizikových systémů AI, jsou-li splněny obě tyto podmínky:
>
> (a) dotčený vysoce rizikový systém AI již nepředstavuje žádné značné riziko pro základní práva, zdraví nebo bezpečnost, s přihlédnutím ke kritériím uvedeným v odstavci 2;
>
> (b) vypuštění nesnižuje celkovou úroveň ochrany zdraví, bezpečnosti a základních práv podle práva Unie.

**Výklad:** Článek 7 zavádí mechanismus dynamické aktualizace přílohy III prostřednictvím aktů v přenesené pravomoci přijímaných Komisí. Tím zákonodárce reaguje na rychlý technologický rozvoj v oblasti AI: statická příloha by v krátkém čase zastarala a přestala pokrývat nově vznikající případy použití s potenciálně závažnými dopady.

Kritéria odstavce 2 tvoří věcně bohatý katalog faktorů, který Komise musí vzít v úvahu při posuzování ekvivalence rizika. Zvláštní pozornost si zasluhuje kritérium pod písmenem (g) — závislost dotčených osob na výsledku systému AI — které odráží strukturální nerovnost mezi poskytovatelem či zavádějícím subjektem a osobami, o nichž systém rozhoduje. Kritérium pod písmenem (h) pak explicitně zohledňuje mocenskou asymetrii a zranitelnost, přičemž mezi relevantní faktory zranitelnosti jsou výslovně zařazeny hospodářské a sociální poměry a věk — terminologie blízká judikatuře Evropského soudu pro lidská práva a pohledu Agentury EU pro základní práva.

Kritérium pod písmenem (j) zakotvuje test proporcionality v přístupu k regulaci: přínosy nasazení systému AI musejí být brány v úvahu jako protipól k rizikům. Jde o projev přístupu tzv. „rizikově-přínosové analýzy" (*risk-benefit analysis*), který je běžný v sektorovém právu (zdravotnické prostředky, léčiva) a který zákonodárce přejímá do horizontálního rámce AI. Procesní klauzule o nemožnosti snižovat celkovou úroveň ochrany (odst. 3 písm. b) zaručuje, že vypuštění z přílohy III nebude politicky motivovaným oslabením regulace. Zmocnění k přidání i k odebrání oblastí z přílohy III vytváří symetrický, obousměrný regulatorní nástroj schopný reagovat jak na nová rizika, tak na případy, kdy riziko pominulo nebo bylo dostatečně ošetřeno jiným právním předpisem Unie.

#### F. Kazuistika

**1. Modelová situace.** Evropská spotřebitelská organizace a dozorové orgány tří členských států předloží Komisi zdokumentovaná podání, podle nichž systémy AI pro prověřování zájemců o nájemní bydlení (tzv. tenant-screening) systematicky znevýhodňují cizince, samoživitele a příjemce sociálních dávek; zájemci se proti negativnímu „doporučení" nemohou účinně bránit, protože pronajímatelé na ně bez dalšího spoléhají. Tento případ použití v příloze III dosud uveden není. Komise zvažuje akt v přenesené pravomoci, jímž by jej doplnila do oblasti přístupu k základním soukromým službám. Důkazy: zprávy a podání dle odst. 2 písm. e), statistiky rozšíření systémů, analýzy dopadů na dotčené skupiny, posouzení existující právní ochrany dle písm. k).

**2. Právní otázka.** Jsou splněny obě kumulativní podmínky čl. 7 odst. 1 pro doplnění nového případu použití do přílohy III aktem v přenesené pravomoci a jak má Komise strukturovat posouzení kritérií odst. 2?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 7 odst. 1 (kumulativní podmínky: oblast přílohy III + ekvivalence rizika), odst. 2 (katalog kritérií písm. a)–k)), odst. 3 (odstranění z přílohy).
- *Související ustanovení téhož nařízení:* čl. 97 (výkon přenesené pravomoci, námitky Parlamentu a Rady), čl. 6 odst. 2 (důsledek zařazení), čl. 6 odst. 8 (zákaz snižování úrovně ochrany), příloha III bod 5 (přístup k základním soukromým a veřejným službám).
- *Související předpisy:* čl. 290 SFEU (delegace jen nepodstatných prvků); GDPR čl. 22; směrnice 2000/43/ES; Listina základních práv EU (čl. 7, 21, 34).
- *Judikatura:* SDEU C-355/10 Parlament v. Rada (5. 9. 2012) — podstatné prvky úpravy vyžadující politická rozhodnutí jsou vyhrazeny zákonodárci a nelze je delegovat; aktualizace přílohy III v mezích zákonodárcem stanovených oblastí a kritérií je proto přípustnou změnou nepodstatných prvků.

**4. Subsumpce.** Podmínka odst. 1 písm. a): hodnocení zájemců o bydlení lze podřadit pod oblast přístupu k základním soukromým službám (příloha III bod 5) — bydlení je existenční potřebou; Komise nemůže vytvořit oblast novou, jen doplnit případ použití v rámci stávajících osmi. Podmínka písm. b): ekvivalence rizika se opírá o kritéria odst. 2 — doloženou újmu (písm. e)), závislost dotčených osob na výsledku (písm. g) — bez kladného hodnocení bydlení nelze získat), mocenskou asymetrii a zranitelnost (písm. h)), obtížnou zvrátitelnost (písm. i)). Protiváhou jsou přínosy (písm. j)) a existující ochrana (písm. k) — čl. 22 GDPR, antidiskriminační právo); ta však dle podání nepůsobí preventivně, nýbrž až následně.

**5. Řešení.** Komise může akt v přenesené pravomoci přijmout: posouzení musí být strukturované podle všech kritérií odst. 2 (nikoli jen vybraných), odůvodněné a podložené důkazy; postup dle čl. 97 zachovává kontrolu zákonodárce (právo námitky). Po nabytí účinnosti se poskytovatelé tenant-screeningových systémů stávají adresáty povinností čl. 8–15 a posuzování shody; jednotlivě mohou uplatnit výjimku čl. 6 odst. 3, nejde-li o profilování.

**6. Varianty.** (i) Pokud by případ použití nespadal pod žádnou z osmi oblastí přílohy III (např. AI v seznamovacích aplikacích), Komise jej delegovaným aktem doplnit nemůže — vyžadovala by se novelizace nařízení řádným legislativním postupem. (ii) Pokud by mezitím jiný předpis Unie zavedl účinnou prevenci týchž rizik (písm. k) bod ii), ekvivalence rizika by nemusela být dána a doplnění by neobstálo.

#### G. Protiargumenty a rizika

- „Rozšiřování přílohy III delegovanými akty obchází řádný legislativní proces a čl. 290 SFEU." Neutralizace: zákonodárce sám vymezil uzavřený okruh oblastí, kumulativní podmínky i jedenáct kritérií; Komise pouze konkretizuje nepodstatné prvky a podléhá námitkovému mechanismu čl. 97 — to odpovídá testu z věci C-355/10.
- „Doložená újma je anekdotická, nikoli systémová." Kritérium písm. e) výslovně připouští zprávy a zdokumentovaná tvrzení podaná orgánům; Komise však musí vážit jejich reprezentativnost — slabě podložený akt je napadnutelný žalobou na neplatnost (čl. 263 SFEU).
- Slabé místo: pojem „rovnocenné nebo větší riziko" postrádá metodiku kvantifikace a kritéria odst. 2 nemají stanovenou hierarchii; široká diskrece Komise je soudně přezkoumatelná jen v mezích zjevného překročení uvážení.

#### H. Praktický závěr

Čl. 7 činí z přílohy III „živý" seznam: poskytovatelé nemohou spoléhat, že jejich případ použití zůstane trvale mimo regulaci, a naopak mohou argumentovat pro vynětí, pominulo-li riziko (odst. 3) — vždy ale platí pojistka nesnižování úrovně ochrany.

**Checklist (Komise / poskytovatel / advokát):**
- [ ] Sledovat přípravu delegovaných aktů k příloze III (konzultace, zveřejněné návrhy, lhůty námitek dle čl. 97).
- [ ] Zmapovat, zda vlastní případy použití spadají do některé z osmi oblastí přílohy III (potenciál budoucího zařazení).
- [ ] U návrhu na doplnění ověřit posouzení všech kritérií odst. 2 a důkazní podklad (možnost námitek a žaloby dle čl. 263 SFEU).
- [ ] U návrhu na vynětí doložit, že riziko pominulo a celková ochrana se nesníží (odst. 3 písm. b)).
- [ ] Připravit gap-analýzu povinností čl. 8–15 pro případ zařazení.

**Typicky rozhodné důkazy / podklady:** zprávy a podání dozorovým orgánům, studie dopadů na základní práva, statistiky rozšíření a autonomie systémů, analýza existující právní ochrany, dokumentace konzultací Komise s radou pro AI.

---

**Oddíl 2 — Požadavky na vysoce rizikové systémy AI**

### Čl. 8 — Shoda s požadavky

**Doslovné znění (EN) — Article 8 — Compliance with the requirements:**

> 1. High-risk AI systems shall comply with the requirements laid down in this Section, taking into account their intended purpose as well as the generally acknowledged state of the art on AI and AI-related technologies. The risk management system referred to in Article 9 shall be taken into account when ensuring compliance with those requirements.
>
> 2. Where a product contains an AI system, to which the requirements of this Regulation as well as requirements of the Union harmonisation legislation listed in Section A of Annex I apply, providers shall be responsible for ensuring that their product is fully compliant with all applicable requirements under applicable Union harmonisation legislation. In ensuring the compliance of high-risk AI systems referred to in paragraph 1 with the requirements set out in this Section, and in order to ensure consistency, avoid duplication and minimise additional burdens, providers shall have a choice of integrating, as appropriate, the necessary testing and reporting processes, information and documentation they provide with regard to their product into documentation and procedures that already exist and are required under the Union harmonisation legislation listed in Section A of Annex I.

**Pracovní překlad (CZ):**

> 1. Vysoce rizikové systémy AI musejí splňovat požadavky stanovené v tomto oddílu, přičemž se přihlíží k jejich určenému účelu, jakož i k obecně uznávanému stavu techniky v oblasti AI a technologií souvisejících s AI. Při zajišťování souladu s těmito požadavky se přihlíží k systému řízení rizik uvedenému v článku 9.
>
> 2. Obsahuje-li výrobek systém AI, na nějž se vztahují jak požadavky tohoto nařízení, tak požadavky harmonizačního právního předpisu Unie uvedeného v části A přílohy I, jsou poskytovatelé odpovědni za zajištění plného souladu jejich výrobku se všemi platnými požadavky podle příslušného harmonizačního právního předpisu Unie. Při zajišťování souladu vysoce rizikových systémů AI uvedených v odstavci 1 s požadavky stanovenými v tomto oddílu, a s cílem zajistit soulad, zamezit zdvojování a minimalizovat dodatečné zátěže, mají poskytovatelé možnost integrovat, je-li to vhodné, nezbytné postupy testování a podávání zpráv, informace a dokumentaci, které poskytují ve vztahu ke svému výrobku, do dokumentace a postupů, které již existují a jsou vyžadovány podle harmonizačního právního předpisu Unie uvedeného v části A přílohy I.

**Výklad:** Článek 8 plní funkci horizontálního vstupního bodu do oddílu 2: stanoví, že vysoce rizikové systémy AI musejí splňovat celou sadu požadavků čl. 9–15, a jako interpretační vodítko pro posuzování souladu odkazuje na systém řízení rizik (čl. 9). Odkaz na „obecně uznávaný stav techniky" (*state of the art*) má normativní charakter — povinnosti nařízení nejsou statické, nýbrž se vyvíjejí spolu s technologickými možnostmi a průmyslovými standardy.

Odstavec 2 řeší klíčový průsečík AI aktu s odvětvovým harmonizačním právem Unie (příloha I, část A — zahrnuje nařízení o strojních zařízeních, zdravotnických prostředcích, rádiových zařízeních apod.). Zákonodárce se vyhnul duplicitnímu administrativnímu zatížení: poskytovatel smí dokumentaci a postupy testování konsolidovat, tj. splnit požadavky AI aktu i sektorového předpisu jednou dokumentační sadou. Toto pravidlo tzv. „jediného vstupu" (*single set of documentation*) je obdobné přístupu zvolenému v nařízení o zdravotnických prostředcích (EU) 2017/745. Důsledkem je, že soulad s odvětvovým právem nenahrazuje soulad s AI aktem — poskytovatel musí splnit oba soubory požadavků, avšak procesně je může sloučit. Odpovědnost poskytovatele za celkový soulad výrobku (odst. 2 věta první) zůstává nedělitelná.

#### F. Kazuistika

**1. Modelová situace.** CardioTech a.s. (poskytovatel) vyvíjí diagnostický software s AI komponentou pro analýzu EKG, který je zdravotnickým prostředkem třídy IIa dle nařízení (EU) 2017/745 (MDR) a podléhá posouzení shody notifikovanou osobou; jde tedy zároveň o vysoce rizikový systém AI dle čl. 6 odst. 1 (MDR je uvedeno v příloze I části A). Regulatorní oddělení vede oddělenou dokumentaci pro MDR a pro AI akt; představenstvo se táže, zda certifikace dle MDR požadavky AI aktu „konzumuje", případně zda lze obě agendy sloučit. Důkazy: klasifikační posouzení dle MDR i čl. 6, certifikát notifikované osoby, technická dokumentace dle přílohy II MDR a přílohy IV AI aktu, plán řízení rizik.

**2. Právní otázka.** Nahrazuje posouzení shody a dokumentace podle MDR splnění požadavků oddílu 2 AI aktu, nebo musí poskytovatel splnit oba režimy — a v jaké procesní formě?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 8 odst. 1 (povinnost souladu s čl. 9–15 s přihlédnutím k určenému účelu a stavu techniky), odst. 2 (nedělitelná odpovědnost za celkový soulad + možnost integrace dokumentace a testování).
- *Související ustanovení téhož nařízení:* čl. 6 odst. 1 a příloha I část A (klasifikace), čl. 9 (řízení rizik jako vodítko souladu), čl. 11 odst. 2 (jediný soubor technické dokumentace), čl. 43 odst. 3 (integrace posouzení shody do sektorového postupu), čl. 40 (harmonizované normy a presumpce shody).
- *Související předpisy:* nařízení (EU) 2017/745 (MDR), zejm. čl. 52 a příloha II; obdobně nařízení (EU) 2023/1230 o strojních zařízeních.
- *Judikatura:* SDEU C-613/14 James Elliott Construction (27. 10. 2016) — harmonizované normy jsou součástí práva EU a SDEU je příslušný k jejich výkladu; význam pro presumpci shody a pro obsah pojmu „stav techniky".

**4. Subsumpce.** Systém je bezpečnostní komponentou, resp. výrobkem dle přílohy I části A a MDR vyžaduje posouzení třetí stranou — obě podmínky čl. 6 odst. 1 jsou splněny, požadavky čl. 9–15 se tedy uplatní vedle MDR. Čl. 8 odst. 2 zakládá výslovně jen procesní integraci (testování, podávání zpráv, informace, dokumentace), nikoli hmotněprávní substituci; odpovědnost poskytovatele za „plný soulad se všemi požadavky" zůstává nedělitelná.

**5. Řešení.** CardioTech musí splnit oba soubory požadavků, smí však vést jediný soubor technické dokumentace (čl. 11 odst. 2) a posouzení shody dle AI aktu integrovat do postupu dle MDR (čl. 43 odst. 3) u notifikované osoby, jejíž jmenování pokrývá i AI akt. Soulad se posuzuje vždy k určenému účelu a k obecně uznávanému stavu techniky, prakticky dokládanému harmonizovanými normami, společnými specifikacemi či mezinárodními standardy. Oddělené vedení dvou dokumentačních sad není protiprávní, je však zbytečnou zátěží, kterou čl. 8 odst. 2 umožňuje odstranit.

**6. Varianty.** (i) Pokud by software spadal do režimu MDR bez účasti notifikované osoby, nebyla by splněna podmínka čl. 6 odst. 1 písm. b) a systém by nebyl vysoce rizikový z titulu přílohy I (mohl by však spadnout pod přílohu III). (ii) Pokud by tentýž systém naplňoval i bod přílohy III, klasifikace by se opírala o oba tituly; na rozsahu povinností oddílu 2 by se nic neměnilo.

#### G. Protiargumenty a rizika

- „Dvojí regulace téhož výrobku porušuje zásadu proporcionality." Neutralizace: AI akt a sektorové právo chrání odlišné aspekty (algoritmická rizika vs. klinická/mechanická bezpečnost); zátěž zákonodárce zmírnil právě integrací dokumentace a posouzení shody — jde o konsolidaci procesů, nikoli o zdvojení povinností.
- „Stav techniky je neurčitý pojem, vůči němuž nelze certifikovat." Neutralizace: konkretizují jej harmonizované normy dle čl. 40 s presumpcí shody; do jejich vydání lze vycházet z mezinárodních standardů a pokynů — posouzení je dynamické a musí být dokumentačně doloženo k okamžiku uvedení na trh.
- Slabé místo: harmonizované normy pro AI dosud nejsou kompletní a kapacity notifikovaných osob s rozšířenou působností pro AI akt jsou omezené; harmonogram certifikace je nutné plánovat s výraznou rezervou.

#### H. Praktický závěr

Čl. 8 zakládá pravidlo kumulace s procesní úsporou: sektorová certifikace nezbavuje povinností dle AI aktu, obě agendy však lze sloučit do jediné dokumentační a certifikační stopy; měřítkem souladu je určený účel a stav techniky.

**Checklist (poskytovatel / regulatorní oddělení / notifikovaná osoba):**
- [ ] Identifikovat všechny použitelné harmonizační předpisy přílohy I části A.
- [ ] Rozhodnout o integraci dokumentace (čl. 8 odst. 2, čl. 11 odst. 2) a posouzení shody (čl. 43 odst. 3).
- [ ] Ověřit, že notifikovaná osoba je oprávněna posuzovat i požadavky AI aktu.
- [ ] Doložit stav techniky (normy, specifikace, benchmarky) ke dni uvedení na trh a průběžně jej revidovat.
- [ ] Promítnout systém řízení rizik dle čl. 9 do prokazování souladu s čl. 10–15.

**Typicky rozhodné důkazy / podklady:** klasifikační posouzení dle sektorového předpisu i čl. 6, integrovaná technická dokumentace, certifikáty a zprávy notifikované osoby, rešerše norem a stavu techniky, EU prohlášení o shodě.

---

### Čl. 9 — Systém řízení rizik

**Doslovné znění (EN) — Article 9 — Risk management system:**

> 1. A risk management system shall be established, implemented, documented and maintained in relation to high-risk AI systems.
>
> 2. The risk management system shall be understood as a continuous iterative process planned and run throughout the entire lifecycle of a high-risk AI system, requiring regular systematic review and updating. It shall comprise the following steps:
>
> (a) the identification and analysis of the known and the reasonably foreseeable risks that the high-risk AI system can pose to health, safety or fundamental rights when the high-risk AI system is used in accordance with its intended purpose;
>
> (b) the estimation and evaluation of the risks that may emerge when the high-risk AI system is used in accordance with its intended purpose, and under conditions of reasonably foreseeable misuse;
>
> (c) the evaluation of other risks possibly arising, based on the analysis of data gathered from the post-market monitoring system referred to in Article 72;
>
> (d) the adoption of appropriate and targeted risk management measures designed to address the risks identified pursuant to point (a).
>
> 3. The risks referred to in this Article shall concern only those which may be reasonably mitigated or eliminated through the development or design of the high-risk AI system, or the provision of adequate technical information.
>
> 4. The risk management measures referred to in paragraph 2, point (d), shall give due consideration to the effects and possible interaction resulting from the combined application of the requirements set out in this Section, with a view to minimising risks more effectively while achieving an appropriate balance in implementing the measures to fulfil those requirements.
>
> 5. The risk management measures referred to in paragraph 2, point (d), shall be such that the relevant residual risk associated with each hazard, as well as the overall residual risk of the high-risk AI systems is judged to be acceptable.
>
> In identifying the most appropriate risk management measures, the following shall be ensured:
>
> (a) elimination or reduction of risks identified and evaluated pursuant to paragraph 2 in as far as technically feasible through adequate design and development of the high-risk AI system;
>
> (b) where appropriate, implementation of adequate mitigation and control measures addressing risks that cannot be eliminated;
>
> (c) provision of information required pursuant to Article 13 and, where appropriate, training to deployers.
>
> With a view to eliminating or reducing risks related to the use of the high-risk AI system, due consideration shall be given to the technical knowledge, experience, education, the training to be expected by the deployer, and the presumable context in which the system is intended to be used.
>
> 6. High-risk AI systems shall be tested for the purpose of identifying the most appropriate and targeted risk management measures. Testing shall ensure that high-risk AI systems perform consistently for their intended purpose and that they are in compliance with the requirements set out in this Section.
>
> 7. Testing procedures may include testing in real-world conditions in accordance with Article 60.
>
> 8. The testing of high-risk AI systems shall be performed, as appropriate, at any time throughout the development process, and, in any event, prior to their being placed on the market or put into service. Testing shall be carried out against prior defined metrics and probabilistic thresholds that are appropriate to the intended purpose of the high-risk AI system.
>
> 9. When implementing the risk management system as provided for in paragraphs 1 to 7, providers shall give consideration to whether in view of its intended purpose the high-risk AI system is likely to have an adverse impact on persons under the age of 18 and, as appropriate, other vulnerable groups.
>
> 10. For providers of high-risk AI systems that are subject to requirements regarding internal risk management processes under other relevant provisions of Union law, the aspects provided in paragraphs 1 to 9 may be part of, or combined with, the risk management procedures established pursuant to that law.

**Pracovní překlad (CZ):**

> 1. Ve vztahu k vysoce rizikovým systémům AI musí být zaveden, implementován, zdokumentován a udržován systém řízení rizik.
>
> 2. Systém řízení rizik se chápe jako nepřetržitý iterativní proces, který je plánován a prováděn po celou dobu životního cyklu vysoce rizikového systému AI, a který vyžaduje pravidelný systematický přezkum a aktualizaci. Zahrnuje tyto kroky:
>
> (a) identifikaci a analýzu známých a přiměřeně předvídatelných rizik, která může vysoce rizikový systém AI způsobit pro zdraví, bezpečnost nebo základní práva, je-li vysoce rizikový systém AI používán v souladu s jeho určeným účelem;
>
> (b) odhadování a vyhodnocování rizik, která mohou vzniknout, je-li vysoce rizikový systém AI používán v souladu s jeho určeným účelem a za podmínek přiměřeně předvídatelného zneužití;
>
> (c) vyhodnocení dalších rizik, která mohou vzniknout na základě analýzy dat shromážděných ze systému postmarketingového monitorování uvedeného v článku 72;
>
> (d) přijetí vhodných a cílených opatření pro řízení rizik určených k řešení rizik identifikovaných podle písmene a).
>
> 3. Rizika uvedená v tomto článku se týkají pouze těch rizik, která lze přiměřeně zmírnit nebo eliminovat prostřednictvím vývoje nebo návrhu vysoce rizikového systému AI nebo poskytnutím odpovídajících technických informací.
>
> 4. Opatření pro řízení rizik uvedená v odstavci 2 písm. d) náležitě zohledňují účinky a možné interakce vyplývající z kombinovaného použití požadavků stanovených v tomto oddílu s cílem účinněji minimalizovat rizika a přitom dosáhnout přiměřené rovnováhy při provádění opatření k naplnění těchto požadavků.
>
> 5. Opatření pro řízení rizik uvedená v odstavci 2 písm. d) musejí být taková, aby bylo zbývající riziko spojené s každým nebezpečím, jakož i celkové zbývající riziko vysoce rizikových systémů AI posouzeno jako přijatelné.
>
> Při určování nejvhodnějších opatření pro řízení rizik musí být zajištěno:
>
> (a) eliminace nebo snížení rizik identifikovaných a vyhodnocených podle odstavce 2 v co největší technicky proveditelné míře prostřednictvím odpovídajícího návrhu a vývoje vysoce rizikového systému AI;
>
> (b) tam kde je to vhodné, provádění odpovídajících zmírňujících a kontrolních opatření k řešení rizik, která nelze eliminovat;
>
> (c) poskytnutí informací požadovaných podle článku 13 a tam, kde je to vhodné, školení zavádějícím subjektům.
>
> S cílem eliminovat nebo snížit rizika spojená s použitím vysoce rizikového systému AI se náležitě přihlíží k odborným znalostem, zkušenostem, vzdělání, školení, která lze od zavádějícího subjektu očekávat, a k předpokládanému kontextu, v němž má být systém použit.
>
> 6. Vysoce rizikové systémy AI musejí být testovány za účelem identifikace nejvhodnějších a nejcílenějších opatření pro řízení rizik. Testování musí zajistit, aby vysoce rizikové systémy AI fungovaly konzistentně v souladu s jejich určeným účelem a aby splňovaly požadavky stanovené v tomto oddílu.
>
> 7. Postupy testování mohou zahrnovat testování v reálných podmínkách v souladu s článkem 60.
>
> 8. Testování vysoce rizikových systémů AI se provádí, je-li to vhodné, kdykoli v průběhu vývojového procesu a v každém případě před jejich uvedením na trh nebo do provozu. Testování se provádí na základě předem definovaných metrik a pravděpodobnostních prahových hodnot, které jsou vhodné pro určený účel vysoce rizikového systému AI.
>
> 9. Při zavádění systému řízení rizik stanoveného v odstavcích 1 až 7 poskytovatelé zohlední, zda s ohledem na jeho určený účel může mít vysoce rizikový systém AI nepříznivý dopad na osoby mladší 18 let a případně na jiné zranitelné skupiny.
>
> 10. Pro poskytovatele vysoce rizikových systémů AI, kteří podléhají požadavkům týkajícím se interních procesů řízení rizik podle jiných relevantních ustanovení práva Unie, mohou být aspekty stanovené v odstavcích 1 až 9 součástí nebo kombinovány s postupy řízení rizik zavedenými podle daného práva.

**Výklad:** Článek 9 představuje normativní páteř celého oddílu 2: systém řízení rizik není jednorozměrnou statickou procedurou, nýbrž kontinuálním iterativním procesem procházejícím celým životním cyklem systému AI — od počátečního návrhu přes testování a uvedení na trh až po postmarketingový monitoring. Tím zákonodárce přejímá přístup dobře zavedený v sektorovém právu (zdravotnické prostředky dle nařízení EU 2017/745, léčiva dle nařízení EU 726/2004), ale rozšiřuje ho na celou horizontální kategorii vysoce rizikových systémů AI.

Čtyřkrokový postup v odst. 2 (identifikace — odhadování a vyhodnocování — postmarketingová analýza — přijetí opatření) odpovídá normám řízení rizik, jako je ISO 31000 a ISO/IEC 23894 (rizika AI), aniž by na ně výslovně odkazoval; harmonizované normy vydané evropskými normalizačními orgány (CEN/CENELEC) na základě čl. 40 AI aktu přinesou konkrétní výkladová vodítka. Klíčové je, že opatření pro řízení rizik musejí adresovat nejen normální použití, ale i přiměřeně předvídatelné zneužití (odst. 2 písm. b) — norma je tak přísná i pro scénáře, které poskytovatel neschválil, avšak které jsou rozumně předvídatelné.

Odstavec 5 zavádí test přijatelnosti zbývajícího rizika (*acceptable residual risk*): ani po přijetí všech technicky proveditelných opatření nesmí zbývající riziko přesáhnout přijatelnou míru. Hierarchie opatření (eliminace — zmírnění — informování) sleduje logiku přístupu bezpečnosti při návrhu (*safety by design*), zákonodárce tak upřednostňuje prevenci v návrhu před kompenzatorními informačními povinnostmi. Odstavec 9 výslovně vyžaduje zohlednění dopadu na osoby mladší 18 let a jiné zranitelné skupiny — odkaz na zranitelnost je explicitní bridge k základněprávnímu rámci, zejména čl. 24 Listiny základních práv EU (práva dítěte). Odstavec 10 pak usnadňuje koordinaci s odvětvovými rámci řízení rizik (DORA, Solventnost II apod.), aniž by umožňoval jejich záměnu za specifické požadavky AI aktu.

#### F. Kazuistika

**1. Modelová situace.** FinScore s.r.o. (poskytovatel) uvádí na trh systém AI pro hodnocení úvěruschopnosti spotřebitelů (příloha III bod 5 písm. b)). Před uvedením na trh provedla jednorázovou analýzu rizik, kterou založila do dokumentace; poté systém dva roky nerevidovala. Banky (zavádějící subjekty) hlásí stížnosti žadatelů z periferních regionů na systematicky horší skóre; data z postmarketingového monitorování FinScore sbírá, avšak nevyhodnocuje. Dozorový orgán zahájí kontrolu. Důkazy: dokumentace systému řízení rizik a jeho revizí, plán a zprávy postmarketingového monitorování (čl. 72), testovací protokoly s metrikami, evidence stížností, historie verzí modelu.

**2. Právní otázka.** Splňuje jednorázové, neaktualizované posouzení rizik bez vyhodnocování postmarketingových dat požadavek „nepřetržitého iterativního procesu" řízení rizik dle čl. 9 odst. 2?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 9 odst. 1 a 2 (zavedení, dokumentace a udržování systému; kroky písm. a)–d) včetně analýzy postmarketingových dat), odst. 5 (přijatelnost zbytkového rizika, hierarchie opatření), odst. 8 (testování vůči předem definovaným metrikám a prahům), odst. 9 (zranitelné skupiny).
- *Související ustanovení téhož nařízení:* čl. 72 (postmarketingové monitorování), čl. 17 odst. 1 (řízení rizik jako součást systému řízení kvality), čl. 20 (nápravná opatření), čl. 79 (dozor), čl. 99 odst. 4 (pokuta až 15 mil. EUR nebo 3 % obratu).
- *Související předpisy:* GDPR čl. 35 (posouzení vlivu — synergie při identifikaci rizik pro základní práva); výkladově ISO 31000 a ISO/IEC 23894; směrnice (EU) 2023/2225 o smlouvách o spotřebitelském úvěru.
- *Judikatura:* SDEU C-634/21 SCHUFA — úvěrový skóring zasahuje do práv subjektů údajů již svým vytvořením; podporuje závěr, že riziko diskriminačních skóre je rizikem pro základní práva dle odst. 2 písm. a), nikoli pouhým obchodním rizikem.

**4. Subsumpce.** Krok odst. 2 písm. c) — vyhodnocení rizik na základě postmarketingových dat — není plněn (data se nevyhodnocují); chybí „pravidelný systematický přezkum a aktualizace" (dva roky bez revize). Stížnosti indikují riziko diskriminace, tedy riziko pro základní práva dle písm. a), které mělo být znovu vyhodnoceno a ošetřeno cíleným opatřením dle písm. d). Námitka, že jde o riziko nezmírnitelné návrhem (odst. 3), neobstojí — zkreslení modelu lze řešit rekalibrací, retréninkem či úpravou dat dle čl. 10.

**5. Řešení.** Porušení čl. 9 je dáno. FinScore musí neprodleně provést mimořádnou iteraci řízení rizik, vyhodnotit postmarketingová data, otestovat model vůči předem definovaným metrikám (odst. 8) a přijmout nápravná opatření (čl. 20) včetně informování zavádějících subjektů. Dozorový orgán může uložit nápravu i pokutu dle čl. 99 odst. 4; není-li zbytkové riziko přijatelné (odst. 5), nesmí být systém dále dodáván na trh.

**6. Varianty.** (i) Pokud by zjištěné riziko nebylo rozumně zmírnitelné vývojem, návrhem ani technickými informacemi (odst. 3), leželo by mimo působnost čl. 9 a řešilo by se jinak (zúžení určeného účelu, stažení z trhu). (ii) Pokud by FinScore podléhala sektorovému rámci řízení rizik (např. DORA jako ICT poskytovatel finančních institucí), mohla by procesy integrovat dle odst. 10 — integrace však nesmí vyprázdnit AI-specifické kroky (předvídatelné zneužití, zranitelné skupiny dle odst. 9).

#### G. Protiargumenty a rizika

- „Čl. 9 pokrývá jen rizika zmírnitelná návrhem (odst. 3); diskriminace plyne z historických dat třetích stran, nikoli z návrhu." Neutralizace: volba a správa trénovacích dat jsou součástí návrhu (čl. 10 odst. 2 písm. f) a g)); zkreslení je vlastnost modelu ošetřitelná technicky — argument neobstojí.
- „Přijatelnost zbytkového rizika je subjektivní kategorií poskytovatele." Neutralizace: přijatelnost musí být doložena testováním vůči předem definovaným metrikám a pravděpodobnostním prahům (odst. 8) a poměřena stavem techniky (čl. 8 odst. 1); čistě deklaratorní „akceptace rizika" před dozorem neobstojí.
- Slabé místo: nařízení nestanoví kvantitativní prahy přijatelnosti ani frekvenci iterací; do vydání harmonizovaných norem hrozí divergentní praxe dozorových orgánů — nejlepší obranou je dokumentovaná, konzistentně aplikovaná metodika.

#### H. Praktický závěr

Řízení rizik dle čl. 9 je celoživotní proces, nikoli vstupní formalita: identifikace — odhad a vyhodnocení (včetně přiměřeně předvídatelného zneužití) — postmarketingová analýza — cílená opatření, s hierarchií eliminace → zmírnění → informace a školení, a s testy vůči předem definovaným metrikám.

**Checklist (poskytovatel / dozorový orgán / advokát):**
- [ ] Zaveden a zdokumentován iterativní cyklus s definovanou periodicitou přezkumu a odpovědnostmi.
- [ ] Pokryta rizika při určeném účelu i při přiměřeně předvídatelném zneužití (odst. 2 písm. b)).
- [ ] Data z postmarketingového monitorování (čl. 72) se reálně vyhodnocují a propisují do aktualizací.
- [ ] Zbytkové riziko posouzeno jako přijatelné na základě testů (odst. 8), nikoli deklarace.
- [ ] Zohledněn dopad na osoby mladší 18 let a jiné zranitelné skupiny (odst. 9).

**Typicky rozhodné důkazy / podklady:** dokumentace systému řízení rizik a jeho revizí, testovací protokoly s metrikami a prahy, zprávy postmarketingového monitorování, evidence stížností a incidentů, záznamy o nápravných opatřeních.

---

### Čl. 10 — Data a jejich správa

**Doslovné znění (EN) — Article 10 — Data and data governance:**

> 1. High-risk AI systems which make use of techniques involving the training of AI models with data shall be developed on the basis of training, validation and testing data sets that meet the quality criteria referred to in paragraphs 2 to 5 whenever such data sets are used.
>
> 2. Training, validation and testing data sets shall be subject to data governance and management practices appropriate for the intended purpose of the high-risk AI system. Those practices shall concern in particular:
>
> (a) the relevant design choices;
>
> (b) data collection processes and the origin of data, and in the case of personal data, the original purpose of the data collection;
>
> (c) relevant data-preparation processing operations, such as annotation, labelling, cleaning, updating, enrichment and aggregation;
>
> (d) the formulation of assumptions, in particular with respect to the information that the data are supposed to measure and represent;
>
> (e) an assessment of the availability, quantity and suitability of the data sets that are needed;
>
> (f) examination in view of possible biases that are likely to affect the health and safety of persons, have a negative impact on fundamental rights or lead to discrimination prohibited under Union law, especially where data outputs influence inputs for future operations;
>
> (g) appropriate measures to detect, prevent and mitigate possible biases identified according to point (f);
>
> (h) the identification of relevant data gaps or shortcomings that prevent compliance with this Regulation, and how those gaps and shortcomings can be addressed.
>
> 3. Training, validation and testing data sets shall be relevant, sufficiently representative, and to the best extent possible, free of errors and complete in view of the intended purpose. They shall have the appropriate statistical properties, including, where applicable, as regards the persons or groups of persons in relation to whom the high-risk AI system is intended to be used. Those characteristics of the data sets may be met at the level of individual data sets or at the level of a combination thereof.
>
> 4. Data sets shall take into account, to the extent required by the intended purpose, the characteristics or elements that are particular to the specific geographical, contextual, behavioural or functional setting within which the high-risk AI system is intended to be used.
>
> 5. To the extent that it is strictly necessary for the purpose of ensuring bias detection and correction in relation to the high-risk AI systems in accordance with paragraph (2), points (f) and (g) of this Article, the providers of such systems may exceptionally process special categories of personal data, subject to appropriate safeguards for the fundamental rights and freedoms of natural persons. In addition to the provisions set out in Regulations (EU) 2016/679 and (EU) 2018/1725 and Directive (EU) 2016/680, all the following conditions must be met in order for such processing to occur:
>
> (a) the bias detection and correction cannot be effectively fulfilled by processing other data, including synthetic or anonymised data;
>
> (b) the special categories of personal data are subject to technical limitations on the re-use of the personal data, and state-of-the-art security and privacy-preserving measures, including pseudonymisation;
>
> (c) the special categories of personal data are subject to measures to ensure that the personal data processed are secured, protected, subject to suitable safeguards, including strict controls and documentation of the access, to avoid misuse and ensure that only authorised persons have access to those personal data with appropriate confidentiality obligations;
>
> (d) the special categories of personal data are not to be transmitted, transferred or otherwise accessed by other parties;
>
> (e) the special categories of personal data are deleted once the bias has been corrected or the personal data has reached the end of its retention period, whichever comes first;
>
> (f) the records of processing activities pursuant to Regulations (EU) 2016/679 and (EU) 2018/1725 and Directive (EU) 2016/680 include the reasons why the processing of special categories of personal data was strictly necessary to detect and correct biases, and why that objective could not be achieved by processing other data.
>
> 6. For the development of high-risk AI systems not using techniques involving the training of AI models, paragraphs 2 to 5 apply only to the testing data sets.

**Pracovní překlad (CZ):**

> 1. Vysoce rizikové systémy AI, které využívají techniky zahrnující trénování modelů AI s daty, musejí být vyvíjeny na základě trénovacích, validačních a testovacích datových souborů, jež splňují kritéria kvality uvedená v odstavcích 2 až 5, kdykoli jsou tyto datové soubory použity.
>
> 2. Trénovací, validační a testovací datové soubory musejí podléhat postupům správy a řízení dat, které jsou vhodné pro určený účel vysoce rizikového systému AI. Tyto postupy se týkají zejména:
>
> (a) příslušných voleb při návrhu;
>
> (b) procesů sběru dat a původu dat a v případě osobních údajů původního účelu sběru dat;
>
> (c) příslušných operací přípravy dat, jako je anotace, označování, čištění, aktualizace, obohacování a agregace;
>
> (d) formulace předpokladů, zejména s ohledem na informace, které mají data měřit a reprezentovat;
>
> (e) posouzení dostupnosti, množství a vhodnosti potřebných datových souborů;
>
> (f) zkoumání z hlediska možných zkreslení, která mohou ovlivnit zdraví a bezpečnost osob, mít negativní dopad na základní práva nebo vést k diskriminaci zakázané podle práva Unie, zejména tehdy, když výstupy dat ovlivňují vstupy pro budoucí operace;
>
> (g) přiměřených opatření k zjišťování, předcházení a zmírňování možných zkreslení identifikovaných podle písmene f);
>
> (h) identifikace relevantních nedostatků nebo mezer v datech bránících souladu s tímto nařízením a způsobu, jak lze tyto nedostatky a mezery řešit.
>
> 3. Trénovací, validační a testovací datové soubory musejí být relevantní, dostatečně reprezentativní a v co největší míře prosté chyb a úplné z hlediska určeného účelu. Musejí mít odpovídající statistické vlastnosti, včetně, je-li to relevantní, vlastností vztahujících se k osobám nebo skupinám osob, ve vztahu k nimž má být vysoce rizikový systém AI používán. Tyto vlastnosti datových souborů mohou být splněny na úrovni jednotlivých datových souborů nebo na úrovni jejich kombinace.
>
> 4. Datové soubory musejí v míře požadované určeným účelem zohledňovat charakteristiky nebo prvky specifické pro konkrétní zeměpisné, kontextuální, behaviorální nebo funkční prostředí, v němž má být vysoce rizikový systém AI používán.
>
> 5. V míře, v jaké je to nezbytně nutné pro účely zajištění zjišťování a nápravy zkreslení ve vztahu k vysoce rizikovým systémům AI v souladu s odstavcem 2 písm. f) a g) tohoto článku, mohou poskytovatelé těchto systémů výjimečně zpracovávat zvláštní kategorie osobních údajů, za předpokladu přiměřených záruk pro základní práva a svobody fyzických osob. Kromě ustanovení nařízení (EU) 2016/679 a (EU) 2018/1725 a směrnice (EU) 2016/680 musejí být pro toto zpracování splněny všechny tyto podmínky:
>
> (a) zjišťování a nápravy zkreslení nelze účinně dosáhnout zpracováním jiných dat, včetně syntetických nebo anonymizovaných dat;
>
> (b) zvláštní kategorie osobních údajů podléhají technickým omezením opakovaného použití osobních údajů a nejmodernějším bezpečnostním a soukromí chránícím opatřením, včetně pseudonymizace;
>
> (c) zvláštní kategorie osobních údajů podléhají opatřením zajišťujícím, že zpracovávané osobní údaje jsou zabezpečeny, chráněny a podléhají vhodným zárukám, včetně přísné kontroly a dokumentace přístupu, a to za účelem zamezení zneužití a zajištění přístupu k těmto osobním údajům pouze oprávněným osobám s odpovídajícími povinnostmi mlčenlivosti;
>
> (d) zvláštní kategorie osobních údajů nesmějí být předávány, přenášeny ani jinak zpřístupňovány jiným stranám;
>
> (e) zvláštní kategorie osobních údajů musejí být vymazány, jakmile bylo zkreslení napraveno nebo jakmile osobní údaje dosáhly konce doby uchovávání, podle toho, co nastane dříve;
>
> (f) záznamy o činnostech zpracování podle nařízení (EU) 2016/679 a (EU) 2018/1725 a směrnice (EU) 2016/680 obsahují důvody, proč bylo zpracování zvláštních kategorií osobních údajů nezbytně nutné pro zjišťování a nápravu zkreslení a proč tento cíl nebylo možné dosáhnout zpracováním jiných dat.
>
> 6. Pro vývoj vysoce rizikových systémů AI, které nevyužívají techniky zahrnující trénování modelů AI, se odstavce 2 až 5 vztahují pouze na testovací datové soubory.

**Výklad:** Článek 10 je jedním z nejsignifikantnějších ustanovení AI aktu z perspektivy průsečíku AI regulace a ochrany osobních údajů. Zakotvuje závazné požadavky na správu dat (*data governance*) pro vysoce rizikové systémy AI trénované na datech, čímž reaguje na empiricky doloženou skutečnost, že kvalita, reprezentativnost a vyváženost trénovacích dat zásadně ovlivňují výstupy a potenciální diskriminační efekty systémů AI.

Požadavek relevance, reprezentativnosti a pokud možno bezchybnosti datových souborů (odst. 3) je záměrně formulován jako nejlepší úsilí (*best effort*), neboť zákonodárce si uvědomuje, že absolutní podmínka by byla nesplnitelná. Zvláštní důraz na statistické vlastnosti dat ve vztahu k osobám nebo skupinám osob adresuje problém algoritmické zaujatosti (*algorithmic bias*): datové soubory, které jsou sice početně velké, ale demograficky nevyvážené, mohou vést k systematickému znevýhodňování určitých skupin.

Odstavec 2 písm. f) a g) explicitně zavazuje poskytovatele k analýze a zmírňování zkreslení v datech, a to ještě před uvedením systému na trh — preventivní přístup, nikoli následná náprava. Toto ustanovení vytváří přímou normativní vazbu na antidiskriminační právo Unie (směrnice 2000/43/ES o rasové rovnosti, směrnice 2000/78/ES o rovném zacházení v zaměstnání aj.) a na GDPR: zásada přesnosti dle čl. 5 odst. 1 písm. d) GDPR se promítá do požadavku na bezchybnost a úplnost dat, zásada minimalizace dle čl. 5 odst. 1 písm. c) pak limituje rozsah dat použitých pro trénování.

Odstavec 5 zavádí zvláštní výjimkový režim pro zpracování zvláštních kategorií osobních údajů za účelem zjišťování a nápravy zkreslení (*bias detection and correction*). Výjimka je přísně podmíněna: musí jít o zpracování nezbytně nutné, musejí být splněny kumulativně všechny podmínky pod písmeny a)–f) a musejí být respektovány záruky plynoucí z GDPR, nařízení (EU) 2018/1725 (pro instituce EU) a směrnice (EU) 2016/680 (pro zpracování v trestněprávní oblasti). Ustanovení tak konstituuje sui generis právní základ pro zpracování citlivých dat, který doplňuje obecné základy GDPR, avšak je věcně limitován na specifický účel detekce a nápravy zkreslení. Podmínka pod písmenem (e) — výmaz po dosažení účelu — odráží zásadu omezení uložení dle čl. 5 odst. 1 písm. e) GDPR. Odstavec 6 omezuje rozsah povinností na testovací datové soubory pro systémy nepoužívající trénování modelů, čímž respektuje odlišnou technickou povahu pravidlových nebo expertem navrhovaných systémů AI.

#### F. Kazuistika

**1. Modelová situace.** RecruitAI s.r.o. (poskytovatel) trénuje vysoce rizikový systém pro hodnocení uchazečů o zaměstnání (příloha III bod 4) na patnáctiletých náborových datech nadnárodní korporace. Interní audit odhalí, že model penalizuje kariérní přestávky, a nepřímo tak znevýhodňuje ženy; pro ověření podezření na etnické zkreslení chce poskytovatel výjimečně zpracovat údaje o etnickém původu uchazečů z historických spisů (zvláštní kategorie dle čl. 9 GDPR). Důkazy: dokumentace správy dat (původ, anotace, čištění), statistické analýzy reprezentativnosti, bias audit, záznamy o činnostech zpracování s odůvodněním nezbytnosti, posouzení vlivu (DPIA).

**2. Právní otázka.** Za jakých podmínek smí poskytovatel zpracovat zvláštní kategorie osobních údajů výlučně za účelem zjišťování a nápravy zkreslení dle čl. 10 odst. 5 a jaký je vztah této výjimky ke GDPR?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 10 odst. 2 písm. f) a g) (zkoumání a zmírňování zkreslení), odst. 3 (relevance, reprezentativnost, úplnost), odst. 5 písm. a)–f) (kumulativní podmínky zpracování citlivých údajů).
- *Související ustanovení téhož nařízení:* čl. 9 (zkreslení jako riziko pro základní práva), čl. 11 a příloha IV (dokumentace datových souborů), čl. 15 odst. 4 (zpětnovazební smyčky).
- *Související předpisy:* GDPR — čl. 5 odst. 1 písm. c), d), e) (minimalizace, přesnost, omezení uložení), čl. 9 odst. 2 písm. g) (významný veřejný zájem); směrnice 2000/43/ES a 2000/78/ES; antidiskriminační zákon č. 198/2009 Sb.
- *Judikatura:* SDEU C-184/20 OT (1. 8. 2022) — zvláštní kategorie údajů zahrnují i údaje, z nichž lze citlivé charakteristiky nepřímo dovodit (význam pro proxy proměnné); SDEU C-634/21 SCHUFA — závažnost automatizovaného hodnocení osob pro jejich práva.

**4. Subsumpce.** Podmínka odst. 5 písm. a): RecruitAI musí doložit, že zkreslení nelze účinně zjistit zpracováním jiných dat včetně syntetických či anonymizovaných — pouhá vyšší nákladnost alternativ nepostačuje. Písm. b) a c): pseudonymizace, technická omezení opakovaného použití, přísné řízení a dokumentace přístupů. Písm. d): zákaz předání třetím stranám (včetně mateřské korporace, jež data poskytla). Písm. e): výmaz ihned po nápravě zkreslení. Písm. f): záznamy o zpracování s odůvodněním nezbytnosti. Podmínky platí kumulativně a vedle požadavků GDPR („kromě ustanovení nařízení (EU) 2016/679"), nikoli místo nich.

**5. Řešení.** Zpracování je přípustné jen při kumulativním splnění všech podmínek písm. a)–f) při zachování záruk GDPR; systematickým výkladem tvoří čl. 10 odst. 5 ve spojení s čl. 9 odst. 2 písm. g) GDPR titul významného veřejného zájmu pro tento úzce vymezený účel. Prakticky: nejprve testovat detekci zkreslení na syntetických či proxy datech, teprve při doloženém selhání sáhnout po citlivých údajích, provést DPIA, nastavit retenci, výmaz a přístupová pravidla; nápravu zkreslení (rekalibrace, vyvážení datových souborů) promítnout do technické dokumentace a do iterace řízení rizik dle čl. 9.

**6. Varianty.** (i) Lze-li zkreslení spolehlivě odhalit bez citlivých údajů (statistická proxy analýza), podmínka písm. a) splněna není a zpracování by bylo protiprávní — s rizikem sankcí dle GDPR i AI aktu. (ii) Jde-li o systém nevyužívající trénování modelů (expertní pravidla), vztahují se odst. 2–5 jen na testovací data (odst. 6) a problém se zužuje na validaci výstupů.

#### G. Protiargumenty a rizika

- „Čl. 10 odst. 5 není samostatným právním základem dle GDPR, zpracování je proto i tak protiprávní." Jde o skutečný doktrinální spor; neutralizace: ustanovení výslovně předpokládá, že zpracování může proběhnout při splnění podmínek, a systematicky navazuje na čl. 9 odst. 2 písm. g) GDPR; obezřetný poskytovatel opře zpracování o oba předpisy současně a nezbytnost podrobně zdokumentuje.
- „Požadavek bezchybných a úplných dat je technicky nesplnitelný." Neutralizace: odst. 3 normuje výslovně jen „v co největší míře" (best effort) a připouští splnění vlastností na úrovni kombinace datových souborů; vyžaduje se doložené úsilí, nikoli absolutní výsledek.
- Slabé místo: chybí závazné metriky „dostatečné reprezentativnosti"; do přijetí harmonizovaných norem nese poskytovatel břemeno metodologické obhajitelnosti svých statistických voleb, včetně rizika odlišného posouzení dozorovým orgánem pro ochranu osobních údajů a orgánem dozoru nad AI.

#### H. Praktický závěr

Čl. 10 spojuje technickou kvalitu dat s antidiskriminační prevencí: správa dat musí být dokumentována od návrhu, zkreslení se hledá a řeší ex ante a citlivé údaje lze k tomu použít jen výjimečně, dočasně a pod přísnými kumulativními zárukami odst. 5.

**Checklist (poskytovatel / pověřenec pro ochranu osobních údajů / dozorový orgán):**
- [ ] Zdokumentován původ dat, účel původního sběru a operace přípravy (odst. 2 písm. b), c)).
- [ ] Provedena a doložena analýza reprezentativnosti a zkreslení vůči cílové populaci (odst. 2 písm. f), odst. 3 a 4).
- [ ] Přijata opatření k prevenci a zmírnění zjištěných zkreslení (odst. 2 písm. g)).
- [ ] Při užití citlivých údajů: test nezbytnosti, pseudonymizace, zákaz předání, plán výmazu, záznamy (odst. 5 písm. a)–f)) + DPIA dle GDPR.
- [ ] U systémů bez trénování aplikován režim jen na testovací data (odst. 6).

**Typicky rozhodné důkazy / podklady:** dokumentace správy dat, bias audity a statistické zprávy, záznamy o činnostech zpracování s odůvodněním nezbytnosti, DPIA, protokoly o výmazu citlivých údajů.

---

### Čl. 11 — Technická dokumentace

**Doslovné znění (EN) — Article 11 — Technical documentation:**

> 1. The technical documentation of a high-risk AI system shall be drawn up before that system is placed on the market or put into service and shall be kept up-to date.
>
> The technical documentation shall be drawn up in such a way as to demonstrate that the high-risk AI system complies with the requirements set out in this Section and to provide national competent authorities and notified bodies with the necessary information in a clear and comprehensive form to assess the compliance of the AI system with those requirements. It shall contain, at a minimum, the elements set out in Annex IV. SMEs, including start-ups, may provide the elements of the technical documentation specified in Annex IV in a simplified manner. To that end, the Commission shall establish a simplified technical documentation form targeted at the needs of small and microenterprises. Where an SME, including a start-up, opts to provide the information required in Annex IV in a simplified manner, it shall use the form referred to in this paragraph. Notified bodies shall accept the form for the purposes of the conformity assessment.
>
> 2. Where a high-risk AI system related to a product covered by the Union harmonisation legislation listed in Section A of Annex I is placed on the market or put into service, a single set of technical documentation shall be drawn up containing all the information set out in paragraph 1, as well as the information required under those legal acts.
>
> 3. The Commission is empowered to adopt delegated acts in accordance with Article 97 in order to amend Annex IV, where necessary, to ensure that, in light of technical progress, the technical documentation provides all the information necessary to assess the compliance of the system with the requirements set out in this Section.

**Pracovní překlad (CZ):**

> 1. Technická dokumentace vysoce rizikového systému AI musí být vypracována před tím, než je tento systém uveden na trh nebo do provozu, a musí být průběžně aktualizována.
>
> Technická dokumentace musí být vypracována tak, aby prokazovala, že vysoce rizikový systém AI splňuje požadavky stanovené v tomto oddílu, a aby příslušným vnitrostátním orgánům a oznámeným subjektům poskytovala potřebné informace v jasné a úplné formě pro posouzení souladu systému AI s těmito požadavky. Musí obsahovat přinejmenším prvky stanovené v příloze IV. Malé a střední podniky, včetně začínajících podniků, mohou poskytnout prvky technické dokumentace stanovené v příloze IV ve zjednodušené podobě. Za tímto účelem Komise stanoví zjednodušený formulář technické dokumentace zaměřený na potřeby malých a mikropodniků. Pokud se malý nebo střední podnik, včetně začínajícího podniku, rozhodne poskytnout informace požadované v příloze IV ve zjednodušené podobě, použije formulář uvedený v tomto odstavci. Oznámené subjekty přijmou tento formulář pro účely posuzování shody.
>
> 2. Je-li vysoce rizikový systém AI související s výrobkem, na který se vztahuje harmonizační právní předpis Unie uvedený v části A přílohy I, uveden na trh nebo do provozu, vypracuje se jeden soubor technické dokumentace obsahující veškeré informace stanovené v odstavci 1, jakož i informace požadované podle těchto právních aktů.
>
> 3. Komisi je svěřena pravomoc přijímat akty v přenesené pravomoci v souladu s článkem 97 za účelem změny přílohy IV, je-li to nezbytné s ohledem na technický pokrok, aby technická dokumentace obsahovala veškeré informace nezbytné pro posouzení souladu systému s požadavky stanovenými v tomto oddílu.

**Výklad:** Článek 11 zakotvuje povinnost vypracovat a udržovat technickou dokumentaci jako klíčový doklad pro posuzování shody vysoce rizikových systémů AI. Technická dokumentace (jejíž minimální obsah je podrobně specifikován v příloze IV nařízení) plní dvojí funkci: jednak prokazuje poskytovateli samému a vnitřně, že systém splňuje požadavky oddílu 2, jednak umožňuje příslušným vnitrostátním orgánům a oznámeným subjektům (notified bodies) nezávisle ověřit soulad systému s nařízením.

Povinnost průběžné aktualizace dokumentace je zásadní: statická dokumentace pořízená pouze při uvedení na trh by nepostačovala, neboť vysoce rizikové systémy AI se mohou v průběhu svého životního cyklu podstatně měnit (nové verze, aktualizace modelů, změny dat). Pokud změna překračuje práh „podstatné modifikace" ve smyslu čl. 83, může vyvolat novou povinnost posuzování shody.

Zvláštní pozornost si zaslouží výjimka pro malé a střední podniky (MSP) a začínající podniky: zákonodárce výslovně zohlednil nepoměrnou administrativní zátěž, kterou by plná technická dokumentace pro tyto subjekty představovala, a pověřil Komisi vypracovat zjednodušený formulář. Oznámené subjekty jsou povinny tento formulář přijmout, čímž je zajištěna procesní rovnost. Toto řešení odráží zásadu proporcionality regulace a snahy o podporu inovativních malých a středních podniků v oblasti AI, která prostupuje celým AI aktem (srov. recitál 149). Konsolidace dokumentace pro výrobky podléhající harmonizačnímu právu (odst. 2) odráží stejnou logiku jako čl. 8 odst. 2 — omezení duplicitní administrativní zátěže.

#### F. Kazuistika

**1. Modelová situace.** EduGrade s.r.o., start-up s 15 zaměstnanci (MSP), dodává školám systém AI pro automatizované hodnocení písemných zkoušek (příloha III bod 3 — vzdělávání). Plnou dokumentaci dle přílohy IV považuje za nepřiměřenou zátěž; po uvedení na trh navíc čtvrtletně nasazuje aktualizované verze modelu, aniž dokumentaci mění. Dozorový orgán si dokumentaci vyžádá a zjistí, že odpovídá dva roky staré verzi systému. Důkazy: technická dokumentace a historie jejích verzí, changelogy modelu, záznam o posouzení shody, doklad o statusu MSP, případný plán předem určených změn.

**2. Právní otázka.** Může poskytovatel v postavení MSP splnit povinnost dle čl. 11 zjednodušenou formou a jaké důsledky má neaktualizování technické dokumentace při průběžných změnách modelu?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 11 odst. 1 (vypracování před uvedením na trh, průběžná aktualizace, zjednodušený formulář pro MSP a povinnost oznámených subjektů jej akceptovat), odst. 2 (jediný soubor dokumentace u výrobků dle přílohy I), odst. 3 (delegované změny přílohy IV).
- *Související ustanovení téhož nařízení:* příloha IV (minimální obsah), čl. 3 bod 23 (podstatná změna), čl. 43 odst. 4 (nové posouzení shody při podstatné změně; předem určené změny posouzené při počátečním posouzení shody podstatnou změnou nejsou), čl. 13 odst. 3 písm. c) (předem určené změny v návodu), čl. 18 (uchovávání dokumentace 10 let), čl. 99 odst. 4 (sankce).
- *Související předpisy:* doporučení Komise 2003/361/ES (definice MSP); srovnatelná praxe předem vymezených změn (predetermined change control) u zdravotnických prostředků dle MDR.
- *Judikatura:* k normativnímu významu dokumentů Nového legislativního rámce SDEU C-613/14 James Elliott Construction; specifická judikatura k čl. 11 dosud chybí — argumentace se opírá o text a systematiku nařízení.

**4. Subsumpce.** EduGrade splňuje definici MSP, může tedy užít zjednodušený formulář Komise; obsahové prvky přílohy IV tím nejsou prominuty, mění se jen forma a hloubka popisu. Čtvrtletní aktualizace modelu: nebyly-li předem určeny při počátečním posouzení shody, je nutno u každé zkoumat, zda jde o podstatnou změnu (čl. 3 bod 23 — vliv na soulad s požadavky oddílu 2 nebo změna určeného účelu); přinejmenším však každá z nich zakládá povinnost dokumentaci aktualizovat (odst. 1 věta první). Dokumentace odpovídající dva roky staré verzi je porušením čl. 11.

**5. Řešení.** EduGrade má (i) přejít na zjednodušený formulář, (ii) zavést verzování dokumentace svázané s verzemi modelu, (iii) v dokumentaci a při posouzení shody předem vymezit očekávané změny (rozsah retréninku, metriky, výkonnostní meze) — takové změny pak nové posouzení shody nevyvolají (čl. 43 odst. 4), (iv) změny mimo předem vymezený rámec posuzovat jednotlivě jako potenciálně podstatné. Dozorovému orgánu je třeba předložit dokumentaci aktuálně dodávané verze; rozpor zakládá riziko nápravných opatření a pokuty dle čl. 99 odst. 4.

**6. Varianty.** (i) Byly-li změny modelu předem určeny a posouzeny při počátečním posouzení shody, nejde o podstatnou změnu — postačí průběžná aktualizace dokumentace. (ii) Ztratí-li poskytovatel status MSP (např. akvizicí korporací), nárok na zjednodušenou formu do budoucna odpadá a dokumentaci je nutno doplnit do plného rozsahu přílohy IV.

#### G. Protiargumenty a rizika

- „Zjednodušený formulář pro MSP snižuje úroveň ochrany a vypovídací hodnotu dokumentace." Neutralizace: formulář mění strukturu, nikoli povinnost prokázat soulad s čl. 9–15; oznámené subjekty jej musí přijmout, mohou si však v rámci posuzování shody vyžádat doplňující informace.
- „Pojetí každé aktualizace modelu jako podstatné změny by vedlo k permanentnímu posuzování shody." Neutralizace: nařízení tomu předchází institutem předem určených změn (čl. 43 odst. 4); hranici je třeba narýsovat v dokumentaci ex ante — co je v ní popsáno a posouzeno, nové řízení nevyvolá.
- Slabé místo: zjednodušený formulář musí teprve vydat Komise — do té doby MSP fakticky volí mezi plnou dokumentací a právní nejistotou; kritéria „podstatnosti" změny u průběžně aktualizovaných modelů zůstávají výkladově otevřená.

#### H. Praktický závěr

Technická dokumentace je nosným důkazem souladu: musí existovat před uvedením na trh, „žít" s každou verzí systému a pokrývat prvky přílohy IV (u MSP případně ve zjednodušené formě); předem vymezené změny šetří opakované posuzování shody.

**Checklist (poskytovatel / oznámený subjekt / dozorový orgán):**
- [ ] Dokumentace vypracována před uvedením na trh a pokrývá všechny prvky přílohy IV.
- [ ] Zavedeno verzování dokumentace navázané na verze systému/modelu.
- [ ] Předem určené změny popsány a posouzeny při počátečním posouzení shody (čl. 43 odst. 4).
- [ ] U výrobků dle přílohy I části A vedena jediná konsolidovaná dokumentační sada (odst. 2).
- [ ] Dokumentace uchovávána 10 let od uvedení na trh (čl. 18) a připravena k předložení dozoru.

**Typicky rozhodné důkazy / podklady:** technická dokumentace dle přílohy IV včetně historie verzí, changelogy a release notes modelu, záznam posouzení shody, doklad statusu MSP, plán předem určených změn.

---

### Čl. 12 — Vedení záznamů

**Doslovné znění (EN) — Article 12 — Record-keeping:**

> 1. High-risk AI systems shall technically allow for the automatic recording of events (logs) over the lifetime of the system.
>
> 2. In order to ensure a level of traceability of the functioning of a high-risk AI system that is appropriate to the intended purpose of the system, logging capabilities shall enable the recording of events relevant for:
>
> (a) identifying situations that may result in the high-risk AI system presenting a risk within the meaning of Article 79(1) or in a substantial modification;
>
> (b) facilitating the post-market monitoring referred to in Article 72; and
>
> (c) monitoring the operation of high-risk AI systems referred to in Article 26(5).
>
> 3. For high-risk AI systems referred to in point 1 (a), of Annex III, the logging capabilities shall provide, at a minimum:
>
> (a) recording of the period of each use of the system (start date and time and end date and time of each use);
>
> (b) the reference database against which input data has been checked by the system;
>
> (c) the input data for which the search has led to a match;
>
> (d) the identification of the natural persons involved in the verification of the results, as referred to in Article 14(5).

**Pracovní překlad (CZ):**

> 1. Vysoce rizikové systémy AI musejí technicky umožňovat automatické zaznamenávání událostí (protokoly) po dobu životnosti systému.
>
> 2. S cílem zajistit odpovídající úroveň sledovatelnosti fungování vysoce rizikového systému AI ve vztahu k jeho určenému účelu musejí možnosti vedení protokolů umožňovat zaznamenávání událostí relevantních pro:
>
> (a) identifikaci situací, které mohou vést k tomu, že vysoce rizikový systém AI bude představovat riziko ve smyslu čl. 79 odst. 1 nebo k podstatné modifikaci;
>
> (b) usnadnění postmarketingového monitorování uvedeného v článku 72; a
>
> (c) monitorování provozu vysoce rizikových systémů AI uvedených v čl. 26 odst. 5.
>
> 3. Pro vysoce rizikové systémy AI uvedené v bodě 1 písm. a) přílohy III musejí možnosti vedení protokolů poskytovat přinejmenším:
>
> (a) záznamy o době každého použití systému (datum a čas zahájení a datum a čas ukončení každého použití);
>
> (b) referenční databázi, vůči níž byly vstupní data systémem zkontrolovány;
>
> (c) vstupní data, pro která vyhledávání vedlo ke shodě;
>
> (d) identifikaci fyzických osob zapojených do ověřování výsledků, jak je uvedeno v čl. 14 odst. 5.

**Výklad:** Článek 12 zakotvuje požadavek na automatické vedení protokolů (logů) jako technický základ pro dohled, sledovatelnost a zpětné přezkoumání fungování vysoce rizikových systémů AI. Povinnost vést záznamy je dvojího druhu: obecná pro všechny vysoce rizikové systémy AI (odst. 1–2) a rozšířená, s konkrétními minimálními obsahovými náležitostmi, pro systémy biometrické identifikace (odst. 3, příloha III bod 1 písm. a).

Účelem obecných protokolů je zajistit sledovatelnost relevantní pro tři okruhy: identifikaci rizikových situací a podstatných modifikací (vazba na čl. 79 o dohledu nad trhem), postmarketingové monitorování (čl. 72) a plnění povinností zavádějících subjektů (čl. 26 odst. 5). Záznamy tak propojují preventivní (ex ante) požadavky oddílu 2 s reaktivními (ex post) nástroji dohledu. Vedení protokolů je rovněž předpokladem pro účinné šetření incidentů a pro výkon práv fyzických osob, jichž se rozhodnutí systémů AI týkají.

Zpřísněné požadavky pro biometrické systémy (odst. 3) odráží zvláštní rizikovost tohoto use-case: záznamy o době použití, referenční databázi, vstupních datech vedoucích ke shodě a o totožnosti osob provádějících ověření (povinnost „double check" dle čl. 14 odst. 5) umožňují zpětně rekonstruovat každé konkrétní rozhodnutí o biometrické identifikaci. Tím je zajištěna auditovatelnost jako prvek právního státu v oblasti rozhodování s využitím AI, a to zejména v kontextech donucovacích orgánů nebo hraničního řízení, kde jsou dopady na jednotlivce nejzávažnější. Z pohledu ochrany osobních údajů je třeba záznamy v protokolech považovat za osobní údaje a aplikovat na jejich zpracování příslušná pravidla GDPR nebo směrnice (EU) 2016/680 (zpracování pro účely prevence trestné činnosti).

#### F. Kazuistika

**1. Modelová situace.** Policejní orgán (zavádějící subjekt) použije systém následné vzdálené biometrické identifikace (příloha III bod 1 písm. a)) k identifikaci podezřelého ze záznamu městského kamerového systému. V trestním řízení obhajoba požaduje protokoly: kdy přesně byl systém použit, vůči jaké referenční databázi byla podoba porovnávána, jaká vstupní data vedla ke shodě a které osoby shodu ověřily dle čl. 14 odst. 5. Ukáže se, že dodaný systém zaznamenává pouze přihlášení uživatelů, nikoli náležitosti dle čl. 12 odst. 3. Důkazy: exporty protokolů a jejich metadata, technická dokumentace logovacích funkcí, návod k použití (čl. 13 odst. 3 písm. f)), interní předpisy o uchovávání záznamů.

**2. Právní otázka.** Jaké minimální záznamové schopnosti musí systém vzdálené biometrické identifikace technicky umožňovat a jaké důsledky má jejich absence pro poskytovatele a pro přezkoumatelnost konkrétní identifikace?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 12 odst. 1 (technická způsobilost automatického logování po dobu životnosti), odst. 2 (události relevantní pro rizika, postmarketing a monitoring provozu), odst. 3 písm. a)–d) (minimální náležitosti protokolů u biometrické identifikace).
- *Související ustanovení téhož nařízení:* čl. 14 odst. 5 (dvojí ověření — vazba na odst. 3 písm. d)), čl. 19 a čl. 26 odst. 6 (uchovávání protokolů poskytovatelem a zavádějícím subjektem, nejméně šest měsíců), čl. 72 (postmarketingové monitorování), čl. 79 (dozor nad trhem), čl. 86 (právo na vysvětlení).
- *Související předpisy:* směrnice (EU) 2016/680 (zpracování osobních údajů v trestněprávní oblasti — protokoly jsou osobními údaji), GDPR; trestní řád (zákon č. 141/1961 Sb.) — volné hodnocení důkazů a přezkoumatelnost postupu.
- *Judikatura:* SDEU C-205/21 Ministerstvo na vatreshnite raboti (26. 1. 2023) — shromažďování biometrických údajů v trestním kontextu podléhá testu naprosté nezbytnosti; zvýšené záruky u biometrie podporují přísný výklad odst. 3.

**4. Subsumpce.** Systém spadá pod přílohu III bod 1 písm. a), takže vedle obecné sledovatelnosti (odst. 2) platí minimální obsah protokolů dle odst. 3: doba každého použití (písm. a)), referenční databáze (písm. b)), vstupní data vedoucí ke shodě (písm. c)), identifikace ověřujících osob (písm. d)). Logování pouhých přihlášení tyto náležitosti zjevně nesplňuje — systém nebyl ve shodě s oddílem 2 již při uvedení na trh; odpovědnost nese primárně poskytovatel (čl. 16 písm. a)).

**5. Řešení.** Poskytovatel musí přijmout nápravná opatření (čl. 20) — doplnit logovací funkce, informovat zavádějící subjekty, případně systém stáhnout; dozorový orgán může postupovat dle čl. 79 a uložit pokutu (čl. 99 odst. 4). V trestním řízení absence auditní stopy znemožňuje rekonstrukci identifikace: výstup systému není nepoužitelný ex lege, avšak jeho důkazní hodnota je zásadně oslabena, neboť postup nelze přezkoumat; identifikace musí být podepřena jinými důkazy (rekognice, znalecké zkoumání).

**6. Varianty.** (i) Jde-li o pouhou biometrickou verifikaci 1:1 (potvrzení totožnosti konkrétní osoby, např. při vstupu do objektu), nejde o systém dle přílohy III bodu 1 písm. a) a uplatní se jen obecný režim odst. 1 a 2. (ii) Obsahují-li protokoly podoby a údaje třetích nezúčastněných osob, nastupují požadavky minimalizace a výmazových lhůt dle směrnice (EU) 2016/680 — rozsah logování nesmí překročit účel sledovatelnosti.

#### G. Protiargumenty a rizika

- „Rozsáhlé protokoly samy zasahují do soukromí a vytvářejí nové riziko zneužití." Neutralizace: zákonodárce vědomě upřednostnil auditovatelnost; střet se řeší zabezpečením, řízením přístupů, pseudonymizací a retenčními lhůtami (čl. 19, čl. 26 odst. 6), nikoli rezignací na logování.
- „Technicky nelze zaznamenávat vše." Neutralizace: odst. 2 vyžaduje jen události relevantní pro vyjmenované účely a v míře přiměřené určenému účelu; taxativní minimální jádro platí pouze pro biometrické systémy (odst. 3).
- Slabé místo: nařízení neharmonizuje formát protokolů ani podrobné doby uchovávání (jen minimum šesti měsíců); interoperabilita logů mezi poskytovatelem a zavádějícím subjektem závisí na smluvním a technickém nastavení — chybějící ujednání o předávání a čitelnosti logů je v praxi častou mezerou.

#### H. Praktický závěr

Bez automatických protokolů není sledovatelnosti a bez sledovatelnosti nelze doložit zákonnost jednotlivého výstupu systému — u biometrické identifikace platí taxativní minimum odst. 3 umožňující rekonstruovat každou shodu včetně toho, kdo a kdy ji ověřil.

**Checklist (poskytovatel / zavádějící subjekt / obhajoba / soud):**
- [ ] Logovací funkce navrženy pro celý životní cyklus a pokrývají účely odst. 2 písm. a)–c).
- [ ] U biometrické identifikace zaznamenávána doba použití, referenční databáze, shodová vstupní data a ověřující osoby (odst. 3).
- [ ] Nastaveno uchovávání protokolů (poskytovatel čl. 19, zavádějící subjekt čl. 26 odst. 6 — min. 6 měsíců).
- [ ] Návod k použití popisuje sběr, ukládání a interpretaci protokolů (čl. 13 odst. 3 písm. f)).
- [ ] Protokoly chráněny jako osobní údaje (GDPR / směrnice 2016/680) s řízeným přístupem.

**Typicky rozhodné důkazy / podklady:** exporty protokolů a jejich metadata, technická dokumentace logovacího modulu, návod k použití, retenční směrnice, záznamy o ověření dle čl. 14 odst. 5.

---

### Čl. 13 — Transparentnost a poskytování informací zavádějícím subjektům

**Doslovné znění (EN) — Article 13 — Transparency and provision of information to deployers:**

> 1. High-risk AI systems shall be designed and developed in such a way as to ensure that their operation is sufficiently transparent to enable deployers to interpret a system’s output and use it appropriately. An appropriate type and degree of transparency shall be ensured with a view to achieving compliance with the relevant obligations of the provider and deployer set out in Section 3.
>
> 2. High-risk AI systems shall be accompanied by instructions for use in an appropriate digital format or otherwise that include concise, complete, correct and clear information that is relevant, accessible and comprehensible to deployers.
>
> 3. The instructions for use shall contain at least the following information:
>
> (a) the identity and the contact details of the provider and, where applicable, of its authorised representative;
>
> (b) the characteristics, capabilities and limitations of performance of the high-risk AI system, including:
>
> (i) its intended purpose;
>
> (ii) the level of accuracy, including its metrics, robustness and cybersecurity referred to in Article 15 against which the high-risk AI system has been tested and validated and which can be expected, and any known and foreseeable circumstances that may have an impact on that expected level of accuracy, robustness and cybersecurity;
>
> (iii) any known or foreseeable circumstance, related to the use of the high-risk AI system in accordance with its intended purpose or under conditions of reasonably foreseeable misuse, which may lead to risks to the health and safety or fundamental rights referred to in Article 9(2);
>
> (iv) where applicable, the technical capabilities and characteristics of the high-risk AI system to provide information that is relevant to explain its output;
>
> (v) when appropriate, its performance regarding specific persons or groups of persons on which the system is intended to be used;
>
> (vi) when appropriate, specifications for the input data, or any other relevant information in terms of the training, validation and testing data sets used, taking into account the intended purpose of the high-risk AI system;
>
> (vii) where applicable, information to enable deployers to interpret the output of the high-risk AI system and use it appropriately;
>
> (c) the changes to the high-risk AI system and its performance which have been pre-determined by the provider at the moment of the initial conformity assessment, if any;
>
> (d) the human oversight measures referred to in Article 14, including the technical measures put in place to facilitate the interpretation of the outputs of the high-risk AI systems by the deployers;
>
> (e) the computational and hardware resources needed, the expected lifetime of the high-risk AI system and any necessary maintenance and care measures, including their frequency, to ensure the proper functioning of that AI system, including as regards software updates;
>
> (f) where relevant, a description of the mechanisms included within the high-risk AI system that allows deployers to properly collect, store and interpret the logs in accordance with Article 12.

**Pracovní překlad (CZ):**

> 1. Vysoce rizikové systémy AI musejí být navrženy a vyvinuty tak, aby jejich provoz byl dostatečně transparentní, aby zavádějící subjekty mohly interpretovat výstup systému a vhodně ho používat. Musí být zajištěn odpovídající druh a stupeň transparentnosti s ohledem na dosažení souladu s příslušnými povinnostmi poskytovatele a zavádějícího subjektu stanovenými v oddíle 3.
>
> 2. Vysoce rizikové systémy AI musejí být doprovázeny návodem k použití v odpovídajícím digitálním formátu nebo jinak, který obsahuje stručné, úplné, správné a jasné informace, jež jsou relevantní, přístupné a srozumitelné pro zavádějící subjekty.
>
> 3. Návod k použití musí obsahovat přinejmenším tyto informace:
>
> (a) totožnost a kontaktní údaje poskytovatele a případně jeho oprávněného zástupce;
>
> (b) charakteristiky, schopnosti a omezení výkonu vysoce rizikového systému AI, včetně:
>
> (i) jeho určeného účelu;
>
> (ii) úrovně přesnosti, včetně jejích metrik, robustnosti a kybernetické bezpečnosti uvedených v článku 15, vůči nimž byl vysoce rizikový systém AI testován a validován a které lze očekávat, a veškerých známých a předvídatelných okolností, které mohou mít dopad na tuto očekávanou úroveň přesnosti, robustnosti a kybernetické bezpečnosti;
>
> (iii) jakékoli známé nebo předvídatelné okolnosti související s použitím vysoce rizikového systému AI v souladu s jeho určeným účelem nebo za podmínek přiměřeně předvídatelného zneužití, které mohou vést k rizikům pro zdraví a bezpečnost nebo základní práva uvedeným v čl. 9 odst. 2;
>
> (iv) je-li to vhodné, technické schopnosti a charakteristiky vysoce rizikového systému AI poskytovat informace relevantní pro vysvětlení jeho výstupu;
>
> (v) je-li to vhodné, jeho výkonnost ve vztahu ke konkrétním osobám nebo skupinám osob, pro něž má být systém používán;
>
> (vi) je-li to vhodné, specifikace pro vstupní data nebo jiné relevantní informace, pokud jde o trénovací, validační a testovací datové soubory použité s přihlédnutím k určenému účelu vysoce rizikového systému AI;
>
> (vii) je-li to vhodné, informace umožňující zavádějícím subjektům interpretovat výstup vysoce rizikového systému AI a vhodně ho používat;
>
> (c) změny vysoce rizikového systému AI a jeho výkonu, které byly poskytovatelem předem určeny v okamžiku počátečního posuzování shody, pokud existují;
>
> (d) opatření pro lidský dohled uvedená v článku 14, včetně technických opatření zavedených k usnadnění interpretace výstupů vysoce rizikových systémů AI ze strany zavádějících subjektů;
>
> (e) výpočetní a hardwarové prostředky, které jsou potřebné, očekávaná životnost vysoce rizikového systému AI a veškerá nezbytná opatření pro údržbu a péči, včetně jejich četnosti, k zajištění řádného fungování tohoto systému AI, mimo jiné pokud jde o aktualizace softwaru;
>
> (f) je-li to relevantní, popis mechanismů zahrnutých v rámci vysoce rizikového systému AI, které umožňují zavádějícím subjektům správně shromažďovat, ukládat a interpretovat protokoly v souladu s článkem 12.

**Výklad:** Článek 13 konkretizuje obecnou zásadu transparentnosti pro vztah mezi poskytovatelem a zavádějícím subjektem. Zatímco obecná transparentnost vůči fyzickým osobám dotčeným systémem AI je upravena v čl. 50 a v příslušných základněprávních nástrojích, čl. 13 se zaměřuje na transparentnost ve svislé linii dodavatelského řetězce — informace, které musí poskytovatel předat zavádějícímu subjektu (operátorovi) systému.

Jádro povinnosti tvoří návod k použití (odst. 3), jehož povinný obsah je rozsáhlý a pokrývá technické parametry (přesnost, robustnost, kybernetická bezpečnost), věcné limitace (podmínky, za nichž systém nemusí fungovat spolehlivě), základněprávní aspekty (předvídatelné okolnosti vedoucí k rizikům pro základní práva), opatření pro lidský dohled a instrukce pro nakládání s protokoly. Informace o výkonnosti ve vztahu ke konkrétním demografickým skupinám (odst. 3 písm. b bod v) jsou klíčové pro prevenci diskriminace — zavádějící subjekt musí vědět, pro jaké populace byl systém validován a pro jaké nikoli.

Požadavek na informace o vysvětlitelnosti výstupu (odst. 3 písm. b bod iv a vii) je normativní odpovědí zákonodárce na technickou výzvu tzv. „černé skříňky" (*black box*): i když zákon nepožaduje plnou vysvětlitelnost modelů, vyžaduje, aby poskytovatel komunikoval, do jaké míry je systém schopen poskytnout vysvětlení svých výstupů a jak takové vysvětlení interpretovat. To je v souladu s právem na vysvětlení v kontextu automatizovaného rozhodování dle čl. 22 GDPR, avšak čl. 13 AI aktu jde dál: relace transparentnosti je povinná i tam, kde nedochází k plně automatizovanému rozhodování ve smyslu GDPR. Navod k použití musí splňovat formální požadavky (stručnost, úplnost, správnost, jasnost, přístupnost a srozumitelnost pro zavádějící subjekty), jež jsou analogické požadavkům kladeným na informace dle čl. 12 GDPR, avšak jsou adresovány profesionálnímu uživateli (zavádějícímu subjektu), nikoli konečnému spotřebiteli.

#### F. Kazuistika

**1. Modelová situace.** Banka (zavádějící subjekt) nasadí systém AI pro hodnocení úvěruschopnosti od poskytovatele CreditML GmbH (příloha III bod 5 písm. b)). Dodaný „návod k použití" je třístránkový marketingový leták: neuvádí metriky přesnosti dle čl. 15, výkonnost pro různé demografické skupiny, známé limitace ani opatření lidského dohledu. Žadatel, jemuž byl úvěr na základě výstupu systému zamítnut, žádá vysvětlení dle čl. 86; úvěráři banky nejsou schopni výstup interpretovat. Důkazy: návod k použití a smluvní dokumentace, technická dokumentace poskytovatele, interní postupy banky, korespondence o vyžádání chybějících informací.

**2. Právní otázka.** Porušuje poskytovatel čl. 13, jestliže návod k použití neobsahuje minimální náležitosti odst. 3 a neumožňuje zavádějícímu subjektu interpretovat výstup systému, a jak se tento deficit promítá do povinností a odpovědnosti banky?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 13 odst. 1 (transparentnost již od návrhu), odst. 2 (formální kvality návodu: stručnost, úplnost, správnost, jasnost), odst. 3 (minimální obsah, zejm. písm. b) body ii, iv, v a vii, písm. d) a f)).
- *Související ustanovení téhož nařízení:* čl. 15 odst. 3 (deklarace úrovní přesnosti v návodu), čl. 14 (lidský dohled — návod je jeho informačním předpokladem), čl. 26 odst. 1 a 5 (povinnost zavádějícího subjektu užívat systém dle návodu a monitorovat jej), čl. 86 (právo dotčené osoby na vysvětlení), čl. 16 písm. a) a čl. 99 odst. 4 (odpovědnost a sankce poskytovatele).
- *Související předpisy:* GDPR čl. 13–15 a 22 (informace o automatizovaném rozhodování); směrnice (EU) 2023/2225 (posouzení úvěruschopnosti spotřebitele).
- *Judikatura:* SDEU C-634/21 SCHUFA (skóring jako automatizované rozhodnutí); SDEU C-203/22 Dun & Bradstreet Austria (27. 2. 2025) — subjekt údajů má právo na srozumitelné vysvětlení postupu a zásad automatizovaného rozhodování; obchodní tajemství vysvětlení nevylučuje, řeší se kontrolovaným zpřístupněním orgánu či soudu. Závěry se prosadí i při výkladu čl. 13 a 86 AI aktu.

**4. Subsumpce.** Návod nesplňuje minimální obsah odst. 3 (chybí metriky přesnosti, výkonnost pro skupiny osob, limitace, opatření dohledu) ani kvality odst. 2 (úplnost, správnost); tím je porušen i odst. 1, neboť banka nemůže výstup interpretovat a „vhodně používat". Sekundárně je ohroženo plnění povinností banky dle čl. 26 a čl. 86 i dle GDPR — bez informací od poskytovatele nemůže žadateli poskytnout smysluplné vysvětlení.

**5. Řešení.** Primární odpovědnost nese poskytovatel: porušení čl. 13 je porušením čl. 16 písm. a) se sankcí dle čl. 99 odst. 4. Banka musí chybějící informace písemně vyžádat a do jejich obdržení systém pro rozhodování o žadatelích nepoužívat (jinak sama porušuje čl. 26 odst. 1); má rovněž smluvní nároky z vadného plnění. Žadateli je třeba poskytnout vysvětlení dle čl. 86 — jeho nemožnost jde k tíži banky i poskytovatele. Prakticky: obsahové požadavky odst. 3 promítnout do smlouvy jako výslovné povinnosti se sankcemi a s povinností součinnosti při žádostech dotčených osob.

**6. Varianty.** (i) Je-li návod úplný a banka jej ignoruje (úvěráři neproškoleni, výstup přejímán mechanicky), odpovědnostní těžiště se přesouvá na banku (čl. 26, čl. 4 — AI gramotnost). (ii) Slouží-li systém výhradně k odhalování finančních podvodů (výjimka v příloze III bodu 5 písm. b) in fine), nejde o vysoce rizikový systém a čl. 13 se neuplatní — informační povinnosti pak plynou jen z GDPR a ze smlouvy.

#### G. Protiargumenty a rizika

- „Plná vysvětlitelnost hlubokých modelů je technicky nemožná, povinnost je tedy nesplnitelná." Neutralizace: čl. 13 nevyžaduje odhalení vnitřní logiky modelu, nýbrž sdělení schopností, limitů a způsobu interpretace výstupu (odst. 3 písm. b) body iv a vii) — tedy informací, jimiž poskytovatel disponuje z validace a testování.
- „Detailní návod ohrožuje obchodní tajemství a usnadňuje obcházení systému (gaming)." Neutralizace: povinné položky odst. 3 nezahrnují zdrojový kód ani váhy modelu; judikatura (Dun & Bradstreet) ukazuje cestu vyvážení — srozumitelné vysvětlení bez vydání tajemství, případně kontrolované zpřístupnění orgánu či soudu.
- Slabé místo: řada položek odst. 3 je podmíněna obraty „je-li to vhodné/relevantní", což svádí k minimalistickému plnění; břemeno tvrzení a důkazu o nevhodnosti dané položky však nese poskytovatel.

#### H. Praktický závěr

Čl. 13 je informační páteří dodavatelského řetězce: bez řádného návodu nemůže zavádějící subjekt plnit vlastní povinnosti (čl. 26, čl. 86) a systém nelze legálně provozovat. Návod k použití je proto třeba číst i psát jako právní dokument, nikoli marketingový text.

**Checklist (poskytovatel / zavádějící subjekt / advokát):**
- [ ] Návod obsahuje všechny položky odst. 3 včetně metrik přesnosti (čl. 15 odst. 3) a výkonnosti pro skupiny osob.
- [ ] Popsány známé limitace, předvídatelné zneužití a okolnosti rizik (odst. 3 písm. b) bod iii).
- [ ] Popsána opatření lidského dohledu a interpretační nástroje (odst. 3 písm. d)).
- [ ] Zavádějící subjekt ověřil úplnost návodu před nasazením a promítl ji do smlouvy.
- [ ] Nastaven proces pro vysvětlování jednotlivých rozhodnutí (čl. 86, čl. 22 GDPR).

**Typicky rozhodné důkazy / podklady:** návod k použití a jeho verze, smluvní dokumentace, validační zprávy a metriky, korespondence stran o doplnění informací, interní směrnice a doklady o školení zavádějícího subjektu.

---

### Čl. 14 — Lidský dohled

**Doslovné znění (EN) — Article 14 — Human oversight:**

> 1. High-risk AI systems shall be designed and developed in such a way, including with appropriate human-machine interface tools, that they can be effectively overseen by natural persons during the period in which they are in use.
>
> 2. Human oversight shall aim to prevent or minimise the risks to health, safety or fundamental rights that may emerge when a high-risk AI system is used in accordance with its intended purpose or under conditions of reasonably foreseeable misuse, in particular where such risks persist despite the application of other requirements set out in this Section.
>
> 3. The oversight measures shall be commensurate with the risks, level of autonomy and context of use of the high-risk AI system, and shall be ensured through either one or both of the following types of measures:
>
> (a) measures identified and built, when technically feasible, into the high-risk AI system by the provider before it is placed on the market or put into service;
>
> (b) measures identified by the provider before placing the high-risk AI system on the market or putting it into service and that are appropriate to be implemented by the deployer.
>
> 4. For the purpose of implementing paragraphs 1, 2 and 3, the high-risk AI system shall be provided to the deployer in such a way that natural persons to whom human oversight is assigned are enabled, as appropriate and proportionate:
>
> (a) to properly understand the relevant capacities and limitations of the high-risk AI system and be able to duly monitor its operation, including in view of detecting and addressing anomalies, dysfunctions and unexpected performance;
>
> (b) to remain aware of the possible tendency of automatically relying or over-relying on the output produced by a high-risk AI system (automation bias), in particular for high-risk AI systems used to provide information or recommendations for decisions to be taken by natural persons;
>
> (c) to correctly interpret the high-risk AI system’s output, taking into account, for example, the interpretation tools and methods available;
>
> (d) to decide, in any particular situation, not to use the high-risk AI system or to otherwise disregard, override or reverse the output of the high-risk AI system;
>
> (e) to intervene in the operation of the high-risk AI system or interrupt the system through a ‘stop’ button or a similar procedure that allows the system to come to a halt in a safe state.
>
> 5. For high-risk AI systems referred to in point 1(a) of Annex III, the measures referred to in paragraph 3 of this Article shall be such as to ensure that, in addition, no action or decision is taken by the deployer on the basis of the identification resulting from the system unless that identification has been separately verified and confirmed by at least two natural persons with the necessary competence, training and authority.
>
> The requirement for a separate verification by at least two natural persons shall not apply to high-risk AI systems used for the purposes of law enforcement, migration, border control or asylum, where Union or national law considers the application of this requirement to be disproportionate.

**Pracovní překlad (CZ):**

> 1. Vysoce rizikové systémy AI musejí být navrženy a vyvinuty tak, včetně s odpovídajícími nástroji pro rozhraní člověk-stroj, aby mohly být v době, kdy jsou v provozu, účinně dohlíženy fyzickými osobami.
>
> 2. Lidský dohled musí mít za cíl předcházet rizikům pro zdraví, bezpečnost nebo základní práva, která mohou vzniknout, je-li vysoce rizikový systém AI používán v souladu s jeho určeným účelem nebo za podmínek přiměřeně předvídatelného zneužití, nebo tato rizika minimalizovat, zejména tam, kde tato rizika přetrvávají i po uplatnění jiných požadavků stanovených v tomto oddílu.
>
> 3. Opatření pro dohled musejí být přiměřená rizikům, úrovni autonomie a kontextu použití vysoce rizikového systému AI a musejí být zajištěna prostřednictvím jednoho nebo obou těchto typů opatření:
>
> (a) opatření identifikovaná a zabudovaná, je-li to technicky proveditelné, do vysoce rizikového systému AI poskytovatelem před jeho uvedením na trh nebo do provozu;
>
> (b) opatření identifikovaná poskytovatelem před uvedením vysoce rizikového systému AI na trh nebo do provozu a vhodná k implementaci ze strany zavádějícího subjektu.
>
> 4. Pro účely implementace odstavců 1, 2 a 3 musí být vysoce rizikový systém AI předán zavádějícímu subjektu takovým způsobem, aby fyzické osoby, jimž je přidělen lidský dohled, byly schopny, je-li to vhodné a přiměřené:
>
> (a) náležitě porozumět relevantním schopnostem a omezením vysoce rizikového systému AI a být schopny jeho provoz náležitě monitorovat, mimo jiné za účelem zjišťování a řešení anomálií, poruch a neočekávaného výkonu;
>
> (b) být si vědomy možné tendence automaticky spoléhat nebo nadměrně spoléhat na výstup produkovaný vysoce rizikovým systémem AI (automatizační zkreslení), a to zejména u vysoce rizikových systémů AI používaných k poskytování informací nebo doporučení pro rozhodnutí, která mají přijímat fyzické osoby;
>
> (c) správně interpretovat výstup vysoce rizikového systému AI, přičemž zohlední například dostupné nástroje a metody interpretace;
>
> (d) rozhodnout se v každé konkrétní situaci nepoužít vysoce rizikový systém AI nebo jinak ignorovat, přepsat nebo zvrátit výstup vysoce rizikového systému AI;
>
> (e) zasáhnout do provozu vysoce rizikového systému AI nebo systém přerušit prostřednictvím tlačítka „stop" nebo podobného postupu, který umožní systému přejít do bezpečného stavu.
>
> 5. Pro vysoce rizikové systémy AI uvedené v bodě 1 písm. a) přílohy III musejí být opatření uvedená v odstavci 3 tohoto článku taková, aby bylo zaručeno, že navíc žádná akce ani rozhodnutí nebudou ze strany zavádějícího subjektu přijaty na základě identifikace vyplývající ze systému, pokud tato identifikace nebyla samostatně ověřena a potvrzena alespoň dvěma fyzickými osobami s nezbytnou odbornou způsobilostí, školením a pravomocí.
>
> Požadavek na samostatné ověření alespoň dvěma fyzickými osobami se nevztahuje na vysoce rizikové systémy AI používané pro účely vymáhání práva, migrace, správy hranic nebo azylu, pokud právo Unie nebo vnitrostátní právo považuje uplatnění tohoto požadavku za nepřiměřené.

**Výklad:** Článek 14 zakotvuje požadavek lidského dohledu (*human oversight*) jako jeden z klíčových konstruktivních prvků bezpečnosti vysoce rizikových systémů AI. Lidský dohled zde není chápán jako jednorázový kontrolní mechanismus, ale jako trvalý procesní požadavek integrovaný do návrhu systému i do podmínek jeho provozu.

Normativní jádro tvoří odstavec 4, který stanoví pět konkrétních schopností, jež musejí být osobám vykonávajícím lidský dohled zajištěny: porozumění schopnostem a limitacím systému, povědomí o riziku automatizačního zkreslení (*automation bias*), schopnost správně interpretovat výstup, právo odmítnout nebo přepsat výstup a právo systém zastavit. Výslovné zakotvení práva přepsat nebo ignorovat výstup systému AI (písm. d) je normativním vyjádřením zásady, že stroj nesmí nahradit lidský úsudek při přijímání konečných rozhodnutí s dopadem na práva a zájmy fyzických osob — principu, který je z hlediska základních práv vyjádřen v čl. 22 GDPR a v obecné doktríně procesní spravedlnosti.

Výslovná zmínka o automatizačním zkreslení (písm. b) je pozoruhodnou normativní novinkou: zákonodárce výslovně pojmenovává psychologický fenomén nadměrného spoléhání na výstupy automatizovaných systémů a ukládá, aby osoby vykonávající dohled na toto riziko byly aktivně upozorňovány. Jde o most mezi kognitivní vědou a právem, který odráží empirická zjištění z oblastí jako soudní rozhodování s asistencí AI nebo algoritmické systémy pro udělování úvěrů.

Zpřísněný požadavek čtyř očí — resp. požadavek ověření alespoň dvěma osobami — pro systémy biometrické identifikace (odst. 5) je jednou z nejpřísnějších procedurálních záruk celého nařízení a odráží zvláštní závažnost chyb v biometrické identifikaci (záměna totožnosti). Výjimka pro donucovací orgány v situacích, kdy by požadavek byl nepřiměřený, je protiváhou a musí být vykládána restriktivně: musí být zakotvena v právu Unie nebo vnitrostátním právu, nikoli ponechána na uvážení zavádějícího subjektu ad hoc. Opatření pro lidský dohled musejí být přiměřená (odst. 3) — mají reagovat na konkrétní úroveň autonomie systému a kontext jeho použití, nikoli být uniformní pro všechny typy vysoce rizikových systémů AI.

#### F. Kazuistika

**1. Modelová situace.** Policejní útvar (zavádějící subjekt) nasadí systém následné vzdálené biometrické identifikace (příloha III bod 1 písm. a)). Operátor obdrží návrh shody tváře z kamerového záznamu s fotografií v databázi hledaných osob; shodu sám potvrdí a hlídka osobu zadrží. Následně vyjde najevo záměna — falešně pozitivní shoda u osoby podobného vzhledu. Druhá ověřující osoba se nezapojila (interní pokyn ji nevyžadoval) a operátoři neabsolvovali školení o riziku automatizačního zkreslení. Důkazy: protokoly systému (čl. 12 odst. 3 písm. d)), interní předpisy a workflow, doklady o školení, návod k použití, záznam o zadržení a jeho odůvodnění.

**2. Právní otázka.** Bylo zadržení založené na identifikaci potvrzené jedinou osobou v rozporu s požadavkem samostatného ověření alespoň dvěma způsobilými osobami dle čl. 14 odst. 5 a s požadavky odst. 4, a jaké jsou důsledky?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 14 odst. 1–3 (lidský dohled již od návrhu, přiměřenost opatření rizikům a autonomii), odst. 4 písm. a)–e) (schopnosti dohlížejících osob včetně povědomí o automatizačním zkreslení a práva výstup zvrátit či systém zastavit), odst. 5 (dvojí ověření u biometrické identifikace a úzká výjimka).
- *Související ustanovení téhož nařízení:* čl. 26 odst. 1 a 2 (zavádějící subjekt svěří dohled způsobilým, proškoleným osobám), čl. 4 (AI gramotnost), čl. 12 odst. 3 písm. d) (záznam ověřujících osob), čl. 13 odst. 3 písm. d) (popis opatření dohledu v návodu), čl. 86 (vysvětlení), čl. 99 (sankce).
- *Související předpisy:* Listina základních práv EU (čl. 6 — právo na svobodu); směrnice (EU) 2016/680; zákon č. 273/2008 Sb., o Policii ČR (zajištění osoby); zákon č. 82/1998 Sb. (odpovědnost státu za škodu způsobenou nesprávným úředním postupem).
- *Judikatura:* SDEU C-634/21 SCHUFA — lidské zapojení nesmí být formální („rubber-stamping"), má-li vyloučit automatizovanou povahu rozhodnutí; SDEU C-205/21 — zvýšené záruky při zpracování biometrie v trestním kontextu. Oba závěry podporují materiální, nikoli formální pojetí dohledu dle čl. 14.

**4. Subsumpce.** Systém spadá pod přílohu III bod 1 písm. a), proto dle odst. 5 nesmí být na základě identifikace přijata žádná akce ani rozhodnutí bez samostatného ověření a potvrzení nejméně dvěma způsobilými osobami. Potvrzení jediným operátorem podmínku nesplňuje; výjimka dle druhého pododstavce se neuplatní, neboť nepřiměřenost dvojího ověření nebyla stanovena právem Unie ani vnitrostátním právem — interní pokyn útvaru „právem" v tomto smyslu není. Absence školení o automatizačním zkreslení porušuje odst. 4 písm. b) ve spojení s čl. 26 odst. 2.

**5. Řešení.** Zadržení vychází z procesně vadné identifikace: dotčená osoba se může domáhat konstatování nezákonnosti zásahu a náhrady újmy (zákon č. 82/1998 Sb.); v trestním řízení je identifikace bez dvojího ověření důkazně znehodnocena a vyžaduje podepření jinými důkazy. Zavádějící subjekt musí zavést technicky vynucené dvojí ověření (workflow, v němž akci nelze potvrdit jednou osobou), školení o automatizačním zkreslení a kontrolu prostřednictvím záznamů dle čl. 12 odst. 3 písm. d). Poskytovatel odpovídá za to, že systém dvojí ověření technicky umožňuje a návod je popisuje (čl. 13 odst. 3 písm. d)).

**6. Varianty.** (i) Stanoví-li právo Unie nebo zákon výslovně, že dvojí ověření je v určitých situacích vymáhání práva nepřiměřené, uplatní se výjimka odst. 5 druhého pododstavce — i pak však platí zbývající záruky odst. 4 (interpretace, možnost výstup odmítnout). (ii) Jde-li o verifikaci 1:1 (ověření totožnosti při vstupu), odst. 5 se nepoužije a postačí obecná opatření dohledu dle odst. 3 a 4.

#### G. Protiargumenty a rizika

- „Dvojí ověření paralyzuje operativní nasazení v terénu." Neutralizace: zákonodárce výjimku předvídá, avšak podmínil ji zakotvením v právu Unie nebo vnitrostátním právu — operativní komfort nemůže nahradit legislativní rozhodnutí; do jeho přijetí platí pravidlo „čtyř očí" bezvýjimečně.
- „Lidský dohled byl splněn, protože operátor shodu potvrdil." Neutralizace: dohled musí být materiální — osoba musí rozumět limitům systému, být si vědoma automatizačního zkreslení a mít reálnou pravomoc i podklady výstup odmítnout (odst. 4 písm. d)); mechanické potvrzení návrhu je přesně tím rizikem, na něž odst. 4 písm. b) míří.
- Slabé místo: nařízení nedefinuje kvalifikační standard „nezbytné způsobilosti" ověřujících osob ani nezávislost obou ověření; bez interní metodiky hrozí, že druhé ověření bude formalitou — doporučuje se oddělené, zaslepené ověření s vlastním záznamem.

#### H. Praktický závěr

Čl. 14 vyžaduje, aby člověk mohl systém AI skutečně řídit: rozumět mu, nespoléhat na něj slepě, přepsat jeho výstup a zastavit jej; u vzdálené biometrické identifikace přistupuje dvojí ověření způsobilými osobami, nestanoví-li právní předpis výslovně jinak.

**Checklist (zavádějící subjekt / poskytovatel / soud):**
- [ ] Opatření dohledu odpovídají rizikům, autonomii a kontextu (odst. 3) a jsou popsána v návodu.
- [ ] Dohlížející osoby proškoleny o limitech systému a automatizačním zkreslení (odst. 4 písm. a), b)).
- [ ] Technicky zajištěna možnost výstup ignorovat, přepsat či systém bezpečně zastavit (odst. 4 písm. d), e)).
- [ ] U biometrické identifikace vynuceno samostatné ověření dvěma způsobilými osobami a jeho logování (odst. 5, čl. 12 odst. 3 písm. d)).
- [ ] Případná výjimka z dvojího ověření opřena o výslovný právní předpis, nikoli interní akt řízení.

**Typicky rozhodné důkazy / podklady:** protokoly o použití a ověření, interní předpisy a workflow, doklady o školení, návod k použití, záznam o zadržení či jiném úkonu a jeho odůvodnění.

---

### Čl. 15 — Přesnost, robustnost a kybernetická bezpečnost

**Doslovné znění (EN) — Article 15 — Accuracy, robustness and cybersecurity:**

> 1. High-risk AI systems shall be designed and developed in such a way that they achieve an appropriate level of accuracy, robustness, and cybersecurity, and that they perform consistently in those respects throughout their lifecycle.
>
> 2. To address the technical aspects of how to measure the appropriate levels of accuracy and robustness set out in paragraph 1 and any other relevant performance metrics, the Commission shall, in cooperation with relevant stakeholders and organisations such as metrology and benchmarking authorities, encourage, as appropriate, the development of benchmarks and measurement methodologies.
>
> 3. The levels of accuracy and the relevant accuracy metrics of high-risk AI systems shall be declared in the accompanying instructions of use.
>
> 4. High-risk AI systems shall be as resilient as possible regarding errors, faults or inconsistencies that may occur within the system or the environment in which the system operates, in particular due to their interaction with natural persons or other systems. Technical and organisational measures shall be taken in this regard.
>
> The robustness of high-risk AI systems may be achieved through technical redundancy solutions, which may include backup or fail-safe plans.
>
> High-risk AI systems that continue to learn after being placed on the market or put into service shall be developed in such a way as to eliminate or reduce as far as possible the risk of possibly biased outputs influencing input for future operations (feedback loops), and as to ensure that any such feedback loops are duly addressed with appropriate mitigation measures.
>
> 5. High-risk AI systems shall be resilient against attempts by unauthorised third parties to alter their use, outputs or performance by exploiting system vulnerabilities.
>
> The technical solutions aiming to ensure the cybersecurity of high-risk AI systems shall be appropriate to the relevant circumstances and the risks.
>
> The technical solutions to address AI specific vulnerabilities shall include, where appropriate, measures to prevent, detect, respond to, resolve and control for attacks trying to manipulate the training data set (data poisoning), or pre-trained components used in training (model poisoning), inputs designed to cause the AI model to make a mistake (adversarial examples or model evasion), confidentiality attacks or model flaws.
>
> SECTION 3
>
> Obligations of providers and deployers of high-risk AI systems and other parties

**Pracovní překlad (CZ):**

> 1. Vysoce rizikové systémy AI musejí být navrženy a vyvinuty tak, aby dosahovaly odpovídající úrovně přesnosti, robustnosti a kybernetické bezpečnosti a aby v těchto ohledech konzistentně fungovaly po celou dobu svého životního cyklu.
>
> 2. Za účelem řešení technických aspektů měření odpovídající úrovně přesnosti a robustnosti stanovené v odstavci 1 a jakýchkoli jiných relevantních ukazatelů výkonu, Komise ve spolupráci s relevantními zúčastněnými stranami a organizacemi, jako jsou metrologické orgány a orgány pro benchmarking, bude případně podporovat rozvoj referenčních hodnot a metodologií měření.
>
> 3. Úrovně přesnosti a relevantní metriky přesnosti vysoce rizikových systémů AI musejí být deklarovány v přiloženém návodu k použití.
>
> 4. Vysoce rizikové systémy AI musejí být co nejvíce odolné vůči chybám, poruchám nebo nekonzistencím, ke kterým může dojít v systému nebo v prostředí, v němž systém funguje, zejména v důsledku jejich interakce s fyzickými osobami nebo jinými systémy. V tomto ohledu musejí být přijata technická a organizační opatření.
>
> Robustnosti vysoce rizikových systémů AI může být dosaženo prostřednictvím řešení technické redundance, která mohou zahrnovat záložní nebo nouzové plány.
>
> Vysoce rizikové systémy AI, které se nadále učí po svém uvedení na trh nebo do provozu, musejí být vyvinuty tak, aby v co největší míře eliminovaly nebo redukovaly riziko, že by případně zaujatá výstupy ovlivňovaly vstupy pro budoucí operace (zpětné vazby), a aby bylo zajištěno, že tyto zpětné vazby jsou náležitě řešeny odpovídajícími zmírňujícími opatřeními.
>
> 5. Vysoce rizikové systémy AI musejí být odolné vůči pokusům neoprávněných třetích stran o změnu jejich použití, výstupů nebo výkonu prostřednictvím zneužití zranitelností systému.
>
> Technická řešení zaměřená na zajištění kybernetické bezpečnosti vysoce rizikových systémů AI musejí být přiměřená relevantním okolnostem a rizikům.
>
> Technická řešení pro řešení zranitelností specifických pro AI musejí zahrnovat, je-li to vhodné, opatření k předcházení útokům pokoušejícím se manipulovat s trénovacím datovým souborem (otrava dat), nebo předtrénovanými komponentami používanými při trénování (otrava modelu), vstupům navrženým tak, aby způsobily chybu modelu AI (nepřátelské příklady nebo vyhýbání se modelu), útokům na důvěrnost nebo chybám modelu, reagování na ně, jejich odhalování, řešení a kontrolu.

**Výklad:** Článek 15 uzavírá sadu povinných technických požadavků na vysoce rizikové systémy AI a věnuje se třem vzájemně provázaným vlastnostem: přesnosti, robustnosti a kybernetické bezpečnosti. Jejich společným jmenovatelem je odolnost a spolehlivost systému v reálných podmínkách nasazení po celou dobu jeho životního cyklu.

Přesnost (*accuracy*) je v kontextu AI chápána šíře než v metrologii: zahrnuje konzistenci výstupů ve vztahu k určenému účelu a musí být transparentně deklarována v návodu k použití (odst. 3). Zákonodárce ponechal stanovení konkrétních metrik na harmonizovaných normách a na pokynech Komise vydávaných ve spolupráci s metrologickými orgány (odst. 2) — tato volba odráží technologickou heterogenitu systémů AI, pro něž není možné stanovit jednotný numerický práh přesnosti.

Robustnost (odst. 4) řeší zejména dva problémy: odolnost vůči chybám a poruchám za provozu (hardwarové a softwarové selhání, anomální vstupy) a problém zpětnovazebních smyček u systémů schopných se nadále učit po uvedení na trh. Požadavek na aktivní řízení zpětnovazebních smyček (*feedback loops*) je podstatný: bez něj by systém mohl systematicky zesilovat a upevňovat svá vlastní zkreslení, neboť zaujatý výstup by se bez korekce stával vstupem budoucího trénování.

Kybernetická bezpečnost (odst. 5) představuje průsečík AI aktu s nařízením DORA (EU) 2022/2554 a směrnicí NIS2 (EU) 2022/2555: zákonodárce výslovně jmenuje AI-specifické kybernetické hrozby — otravu trénovacích dat (*data poisoning*), otravu modelu (*model poisoning*), nepřátelské příklady (*adversarial examples*) a útoky na důvěrnost modelu. Tato taxonomie hrozeb dosud absentovala v obecném kybernetickém právu, což odůvodňuje zahrnutí specifických opatření přímo do AI aktu. Technická řešení musejí být přiměřená konkrétním okolnostem a rizikům — zákonodárce explicitně odmítá přístup „jedna velikost pro všechny", který by byl technologicky nevhodný. Kombinace těchto tří vlastností — přesnosti, robustnosti a odolnosti vůči kybernetickým hrozbám — v průběhu celého životního cyklu systému (odst. 1) je normativní odpovědí na dynamickou povahu AI systémů, jež se liší od tradičního softwaru svou schopností měnit chování v závislosti na datech a prostředí.

#### F. Kazuistika

**1. Modelová situace.** SmartGrid Analytics s.r.o. (poskytovatel) dodává provozovateli distribuční soustavy systém AI řídící zatížení sítě — bezpečnostní komponentu kritické infrastruktury (příloha III bod 2). Systém se po nasazení dále učí z provozních dat. Útočník po několik měsíců podstrkává manipulovaná telemetrická data (data poisoning); výkonnost modelu degraduje a dojde k regionálnímu výpadku dodávek elektřiny. Šetření zjistí, že poskytovatel netestoval odolnost proti otravě dat, neimplementoval záložní (fail-safe) režim a úroveň přesnosti deklarovaná v návodu neodpovídala podmínkám reálného provozu. Důkazy: technická dokumentace (testy robustnosti, model hrozeb), protokoly systému dle čl. 12, penetrační testy, návod k použití s deklarovanými metrikami, forenzní analýza incidentu.

**2. Právní otázka.** Porušil poskytovatel požadavky čl. 15 na robustnost a kybernetickou bezpečnost, jestliže průběžně se učící systém pro kritickou infrastrukturu nebyl chráněn proti otravě dat, neměl zálohové řešení a deklarace přesnosti neodpovídala skutečnosti?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 15 odst. 1 (odpovídající úroveň přesnosti, robustnosti a kybernetické bezpečnosti po celý životní cyklus), odst. 3 (deklarace přesnosti v návodu), odst. 4 (odolnost vůči chybám, technická redundance, zpětnovazební smyčky u učících se systémů), odst. 5 (odolnost vůči AI-specifickým útokům včetně otravy dat a modelu).
- *Související ustanovení téhož nařízení:* čl. 9 (přiměřeně předvídatelné zneužití v řízení rizik), čl. 13 odst. 3 písm. b) bod ii (komunikace metrik zavádějícímu subjektu), čl. 72 a 73 (postmarketingové monitorování a hlášení závažných incidentů — narušení kritické infrastruktury je závažným incidentem), čl. 79 (dozor), čl. 99 odst. 4 (pokuty).
- *Související předpisy:* směrnice NIS2 (EU) 2022/2555 (povinnosti provozovatele včetně bezpečnosti dodavatelského řetězce), nařízení (EU) 2024/2847 o kybernetické odolnosti (CRA), směrnice (EU) 2024/2853 o odpovědnosti za vadné výrobky (vada zahrnuje i kybernetickou zranitelnost softwaru).
- *Judikatura:* specifická judikatura k čl. 15 dosud absentuje; nosné jsou závěry SDEU k odpovědnosti za vadné výrobky — C-503/13 Boston Scientific Medizintechnik (u výrobků se zvýšeným rizikem postačí prokázání potenciální vady výrobkové série; měřítkem je bezpečnost, kterou lze oprávněně očekávat).

**4. Subsumpce.** Systém se po uvedení na trh dále učí, takže platí povinnost eliminovat či omezit zpětnovazební smyčky a ošetřit je zmírňujícími opatřeními (odst. 4 třetí pododstavec) — manipulovaná telemetrie vstupující do dalšího učení je přesně tímto scénářem. Otrava dat je v odst. 5 výslovně jmenovanou hrozbou; klauzule „je-li to vhodné" nemůže u kritické infrastruktury vést k vynechání opatření — přiměřenost okolnostem a rizikům zde standard zvyšuje, nikoli snižuje. Redundance je formálně fakultativní („může zahrnovat"), avšak ve spojení s odst. 1, určeným účelem a stavem techniky je u řízení sítě bezpečný záložní režim de facto obligatorní. Nepravdivá deklarace přesnosti porušuje odst. 3 ve spojení s čl. 13.

**5. Řešení.** Je dáno porušení čl. 15 odst. 1, 3, 4 a 5 poskytovatelem (čl. 16 písm. a)): následuje hlášení závažného incidentu (čl. 73), nápravná opatření (čl. 20), dozorový postup (čl. 79) a pokuta dle čl. 99 odst. 4. Vedle veřejnoprávní odpovědnosti přichází v úvahu civilní odpovědnost za vadný výrobek (kybernetická zranitelnost jako vada) a smluvní nároky provozovatele; provozovatel sám čelí přezkumu plnění povinností dle NIS2 (řízení rizik dodavatelského řetězce).

**6. Varianty.** (i) Směřoval-li by útok výlučně na IT prostředí provozovatele (kompromitace přístupů) bez využití AI-specifické zranitelnosti, těžiště odpovědnosti se přesouvá na provozovatele dle NIS2; poskytovatel odpovídá jen za nedostatky deklarovaného zabezpečení. (ii) U systému, který se po nasazení dále neučí a běží v izolovaném prostředí, mohou být opatření proti otravě dat přiměřeně slabší — „přiměřenost rizikům" působí oběma směry.

#### G. Protiargumenty a rizika

- „Absolutní kybernetickou odolnost nelze garantovat; útok byl sofistikovaný a nepředvídatelný." Neutralizace: norma nevyžaduje absolutní odolnost, nýbrž odolnost „co nejvyšší" a opatření přiměřená rizikům dle stavu techniky; otrava dat je v odst. 5 výslovně jmenována, tedy ex lege předvídatelná — úplná absence opatření neobstojí nikdy.
- „Záložní (fail-safe) řešení jsou dle textu jen fakultativní." Neutralizace: izolovaně ano, avšak odst. 1 váže požadovanou úroveň robustnosti na určený účel; u kritické infrastruktury stav techniky bezpečný degradovaný režim standardně zahrnuje — fakultativnost se týká volby prostředku, nikoli výsledku.
- Slabé místo: benchmarky a metodiky měření dle odst. 2 mají teprve vznikat (programová norma adresovaná Komisi); do té doby chybí jednotné měřítko „odpovídající úrovně" přesnosti — poskytovatel je odkázán na vlastní, dokumentačně obhajitelnou metodiku a dostupné standardy (např. ISO/IEC, ETSI).

#### H. Praktický závěr

Čl. 15 uzavírá technické jádro oddílu 2 triádou přesnost — robustnost — kybernetická bezpečnost, poměřovanou určeným účelem a stavem techniky po celý životní cyklus; u učících se systémů přistupuje povinnost aktivně řídit zpětnovazební smyčky a bránit se AI-specifickým útokům, jejichž taxonomii nařízení samo vyjmenovává.

**Checklist (poskytovatel / provozovatel / dozorový orgán):**
- [ ] Definovány a v návodu deklarovány metriky a úrovně přesnosti odpovídající reálným podmínkám nasazení (odst. 3).
- [ ] Zpracován model hrozeb AI-specifických útoků (otrava dat/modelu, nepřátelské příklady, útoky na důvěrnost) a provedeny testy odolnosti (odst. 5).
- [ ] U průběžně se učících systémů ošetřeny zpětnovazební smyčky a validace nově příchozích dat (odst. 4).
- [ ] Implementován bezpečný degradovaný / fail-safe režim přiměřený určenému účelu.
- [ ] Nastaveno hlášení závažných incidentů (čl. 73) a koordinace s povinnostmi dle NIS2/CRA.

**Typicky rozhodné důkazy / podklady:** zprávy z testů robustnosti a penetračních testů, model hrozeb a dokumentace bezpečnostní architektury, deklarované metriky v návodu k použití, protokoly systému a forenzní analýza incidentu, hlášení dle čl. 73.

---
