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

---
