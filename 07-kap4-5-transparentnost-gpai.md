# Kapitoly IV–V — Transparentnost a obecné modely AI (čl. 50–56)

Kapitoly IV a V nařízení (EU) 2024/1689 (AI Act) tvoří dvě navzájem propojené, avšak věcně odlišné normativní vrstvy. Kapitola IV (čl. 50) zavádí horizontální povinnosti transparentnosti pro poskytovatele a zavádějící subjekty systémů AI s tzv. omezeným rizikem — jde o systémy interagující s fyzickými osobami (chatboti, hlasové asistenty), systémy generující syntetický obsah (text, obraz, zvuk, video), systémy rozpoznávání emocí a biometrické kategorizace a v neposlední řadě o systémy produkující deep fake (hluboce zmanipulovaný) obsah. Účelem je zajistit, aby lidé věděli, že jednají se strojem, a aby mohli rozpoznat uměle vytvořený nebo pozměněný obsah — bez ohledu na to, zda se jedná o systém vysokého rizika.

Kapitola V (čl. 51–56) zakotvuje zcela novou regulační kategorii: obecné modely AI (*general-purpose AI models*, GPAI). Na rozdíl od ostatních částí AI Act, jež se zaměřují na systémy nasazené v konkrétních kontextech, reguluje kapitola V modely jako takové — tedy mohutné základové modely trénované na rozsáhlých datech, které jsou následně integrovány do celé škály aplikací a systémů navazujícími poskytovateli. Povinnosti kapitoly V dopadají přímo na poskytovatele modelů a zahrnují dokumentaci, transparentnost vůči navazujícím poskytovatelům a soulad s autorským právem. Obecné modely AI jsou dále hierarchicky stratifikovány: modely s vysokými schopnostmi (jejichž výpočetní náročnost tréninku překračuje práh 10^25 FLOPs) jsou klasifikovány jako obecné modely AI se systémovým rizikem a podléhají přísnějšímu režimu zahrnujícímu hodnocení modelu, zvládání rizik, oznamování incidentů a kybernetickou bezpečnost. Kodifikaci postupů a standardů zajišťují kodexy správné praxe (čl. 56), které mají překlenout dobu do vydání harmonizovaných norem a stát se základním nástrojem samoregulace odvětví pod dohledem Úřadu pro AI.

---

## Kapitola IV — Povinnosti transparentnosti pro poskytovatele a zavádějící subjekty některých systémů AI

### Čl. 50 — Povinnosti transparentnosti pro poskytovatele a zavádějící subjekty některých systémů AI

**Doslovné znění (EN) — Article 50 — Transparency obligations for providers and deployers of certain AI systems:**

> 1. Providers shall ensure that AI systems intended to interact directly with natural persons are designed and developed in such a way that the natural persons concerned are informed that they are interacting with an AI system, unless this is obvious from the point of view of a natural person who is reasonably well-informed, observant and circumspect, taking into account the circumstances and the context of use. This obligation shall not apply to AI systems authorised by law to detect, prevent, investigate or prosecute criminal offences, subject to appropriate safeguards for the rights and freedoms of third parties, unless those systems are available for the public to report a criminal offence.
>
> 2. Providers of AI systems, including general-purpose AI systems, generating synthetic audio, image, video or text content, shall ensure that the outputs of the AI system are marked in a machine-readable format and detectable as artificially generated or manipulated. Providers shall ensure their technical solutions are effective, interoperable, robust and reliable as far as this is technically feasible, taking into account the specificities and limitations of various types of content, the costs of implementation and the generally acknowledged state of the art, as may be reflected in relevant technical standards. This obligation shall not apply to the extent the AI systems perform an assistive function for standard editing or do not substantially alter the input data provided by the deployer or the semantics thereof, or where authorised by law to detect, prevent, investigate or prosecute criminal offences.
>
> 3. Deployers of an emotion recognition system or a biometric categorisation system shall inform the natural persons exposed thereto of the operation of the system, and shall process the personal data in accordance with Regulations (EU) 2016/679 and (EU) 2018/1725 and Directive (EU) 2016/680, as applicable. This obligation shall not apply to AI systems used for biometric categorisation and emotion recognition, which are permitted by law to detect, prevent or investigate criminal offences, subject to appropriate safeguards for the rights and freedoms of third parties, and in accordance with Union law.
>
> 4. Deployers of an AI system that generates or manipulates image, audio or video content constituting a deep fake, shall disclose that the content has been artificially generated or manipulated. This obligation shall not apply where the use is authorised by law to detect, prevent, investigate or prosecute criminal offence. Where the content forms part of an evidently artistic, creative, satirical, fictional or analogous work or programme, the transparency obligations set out in this paragraph are limited to disclosure of the existence of such generated or manipulated content in an appropriate manner that does not hamper the display or enjoyment of the work.
>
> Deployers of an AI system that generates or manipulates text which is published with the purpose of informing the public on matters of public interest shall disclose that the text has been artificially generated or manipulated. This obligation shall not apply where the use is authorised by law to detect, prevent, investigate or prosecute criminal offences or where the AI-generated content has undergone a process of human review or editorial control and where a natural or legal person holds editorial responsibility for the publication of the content.
>
> 5. The information referred to in paragraphs 1 to 4 shall be provided to the natural persons concerned in a clear and distinguishable manner at the latest at the time of the first interaction or exposure. The information shall conform to the applicable accessibility requirements.
>
> 6. Paragraphs 1 to 4 shall not affect the requirements and obligations set out in Chapter III, and shall be without prejudice to other transparency obligations laid down in Union or national law for deployers of AI systems.
>
> 7. The AI Office shall encourage and facilitate the drawing up of codes of practice at Union level to facilitate the effective implementation of the obligations regarding the detection and labelling of artificially generated or manipulated content. The Commission may adopt implementing acts to approve those codes of practice in accordance with the procedure laid down in Article 56 (6). If it deems the code is not adequate, the Commission may adopt an implementing act specifying common rules for the implementation of those obligations in accordance with the examination procedure laid down in Article 98(2).

**Pracovní překlad (CZ):**

> 1. Poskytovatelé zajistí, aby systémy AI určené k přímé interakci s fyzickými osobami byly navrženy a vyvinuty tak, aby dotčené fyzické osoby byly informovány o tom, že komunikují se systémem AI, ledaže je to zřejmé z pohledu fyzické osoby, která je přiměřeně dobře informovaná, pozorná a obezřetná, s přihlédnutím k okolnostem a kontextu použití. Tato povinnost se nevztahuje na systémy AI povolené zákonem za účelem odhalování, předcházení, vyšetřování nebo stíhání trestných činů, s výhradou přiměřených záruk práv a svobod třetích osob, ledaže jsou tyto systémy k dispozici veřejnosti za účelem oznamování trestné činnosti.
>
> 2. Poskytovatelé systémů AI, včetně obecných modelů AI, generujících syntetický zvukový, obrazový, video nebo textový obsah, zajistí, aby výstupy systému AI byly označeny ve strojově čitelném formátu a detekovatelné jako uměle vytvořené nebo pozměněné. Poskytovatelé zajistí, aby jejich technická řešení byla účinná, interoperabilní, robustní a spolehlivá, pokud je to technicky proveditelné, s přihlédnutím ke specifikům a omezením různých typů obsahu, nákladům na realizaci a obecně uznávanému stavu techniky, jak může být odražen v příslušných technických normách. Tato povinnost se nevztahuje na případy, kdy systémy AI plní pomocnou funkci při standardní úpravě obsahu nebo kdy podstatně nemění vstupní data poskytnutá zavádějícím subjektem nebo jejich sémantiku, ani na případy, kdy jsou povoleny zákonem za účelem odhalování, předcházení, vyšetřování nebo stíhání trestných činů.
>
> 3. Zavádějící subjekty systému AI pro rozpoznávání emocí nebo systému AI pro biometrickou kategorizaci informují fyzické osoby vystavené jeho působení o provozu tohoto systému a zpracovávají osobní údaje v souladu s nařízeními (EU) 2016/679 a (EU) 2018/1725 a směrnicí (EU) 2016/680, jsou-li použitelné. Tato povinnost se nevztahuje na systémy AI používané pro biometrickou kategorizaci a rozpoznávání emocí, které jsou zákonem povoleny za účelem odhalování, předcházení nebo vyšetřování trestných činů, s výhradou přiměřených záruk práv a svobod třetích osob a v souladu s právem Unie.
>
> 4. Zavádějící subjekty systému AI, který generuje nebo pozměňuje obrazový, zvukový nebo video obsah představující deep fake, zveřejní, že obsah byl uměle vytvořen nebo pozměněn. Tato povinnost se nevztahuje na případy, kdy je použití povoleno zákonem za účelem odhalování, předcházení, vyšetřování nebo stíhání trestné činnosti. Pokud obsah tvoří součást evidentně uměleckého, tvůrčího, satirického, fiktivního nebo obdobného díla nebo pořadu, jsou povinnosti transparentnosti stanovené v tomto odstavci omezeny na zveřejnění existence takového vytvořeného nebo pozměněného obsahu přiměřeným způsobem, který nebrání zobrazení nebo požitku z díla.
>
> Zavádějící subjekty systému AI, který generuje nebo pozměňuje text zveřejněný s cílem informovat veřejnost o věcech veřejného zájmu, zveřejní, že text byl uměle vytvořen nebo pozměněn. Tato povinnost se nevztahuje na případy, kdy je použití povoleno zákonem za účelem odhalování, předcházení, vyšetřování nebo stíhání trestných činů, ani na případy, kdy obsah generovaný AI prošel procesem lidského přezkoumání nebo redakční kontroly a kdy fyzická nebo právnická osoba nese redakční odpovědnost za zveřejnění obsahu.
>
> 5. Informace uvedené v odstavcích 1 až 4 se dotčeným fyzickým osobám poskytují jasným a zřetelným způsobem nejpozději v okamžiku první interakce nebo vystavení. Informace musí splňovat platné požadavky na přístupnost.
>
> 6. Odstavce 1 až 4 se nedotýkají požadavků a povinností stanovených v kapitole III a nejsou dotčeny jinými povinnostmi transparentnosti stanovenými v právu Unie nebo vnitrostátním právu pro zavádějící subjekty systémů AI.
>
> 7. Úřad pro AI podněcuje a usnadňuje vypracování kodexů správné praxe na úrovni Unie s cílem usnadnit účinné plnění povinností týkajících se odhalování a označování uměle vytvořeného nebo pozměněného obsahu. Komise může přijímat prováděcí akty ke schválení těchto kodexů správné praxe v souladu s postupem stanoveným v čl. 56 odst. 6. Pokud dospěje k závěru, že kodex není přiměřený, může Komise přijmout prováděcí akt stanovující společná pravidla pro plnění těchto povinností v souladu s přezkumným postupem stanoveným v čl. 98 odst. 2.

**Výklad:** Článek 50 zavádí průřezové povinnosti transparentnosti pro kategorii systémů AI s omezeným rizikem, která stojí mimo režim vysokého rizika (kapitola III), ale přesto vytváří nezanedbatelné společenské riziko spočívající v klamání uživatelů nebo dezinformacích. Systematicky lze rozlišit čtyři typy povinností adresovaných různým subjektům.

První typ (odst. 1) dopadá na poskytovatele chatbotů a konverzačních agentů: povinnost informovat o tom, že uživatel jedná se systémem AI, má charakter povinnosti návrhové — musí být zabudována přímo do systému. Standard „přiměřeně informované, pozorné a obezřetné osoby" je autonomním konceptem unijního práva analogickým průměrnému spotřebiteli v právu ochrany spotřebitele; výjimka pro systémy orgánů činných v trestním řízení je systematicky provázána s kapitolou II (zakázané praktiky) a zárukami základních práv.

Druhý typ (odst. 2) se týká označování (vodoznaku) syntetického obsahu. Povinnost je technologicky neutrální: nařízení nevyžaduje konkrétní techniku označování (vodoznak, metadata, kryptografický podpis), nýbrž účinnost, interoperabilitu a robustnost. Tím se otevírá prostor pro normalizaci — Úřad pro AI v součinnosti s Evropskou komisí bude moci prostřednictvím kodexů správné praxe nebo prováděcích aktů de facto standardizovat konkrétní technická řešení. Povinnost dopadá i na poskytovatele obecných modelů AI (GPAI) a je tak jedním z mála míst, kde se kapitola IV a kapitola V průřezově protínají.

Třetí a čtvrtý typ (odst. 3 a 4) jsou povinnostmi zavádějících subjektů — zatímco odst. 3 ukládá informovat o použití systémů rozpoznávání emocí a biometrické kategorizace a odkazuje na plný soulad s GDPR a směrnicí (EU) 2016/680 (policejní výjimka), odst. 4 cílí na deep fake obsah. Pojem „deep fake" není v nařízení přímo definován, ale podle bodu odůvodnění 132 jde o obrazový, zvukový nebo video obsah, jenž se podobá existujícím osobám, předmětům, místům nebo jiným subjektům a jenž by mohl falešně vypadat jako autentický. Výjimka pro uměleckou, satirickou nebo fiktivní tvorbu odráží ústavní ochranu svobody projevu a umělecké svobody (čl. 11 a 13 Listiny základních práv EU); zveřejnění existence manipulovaného obsahu „přiměřeným způsobem, který nebrání zobrazení díla" ponechává zavádějícímu subjektu prostor pro volbu konkrétní formy označení (titulkový text, zápatí, metadata). Povinnost zveřejnění pro text ve veřejném zájmu (druhý pododstavec odst. 4) je namířena zejména na dezinformační operace a automatizovanou produkci politického obsahu; výjimka pro redakční kontrolu uznává, že novinářské použití generativní AI při zachování lidského dohledu a odpovědnosti za publikaci legitimní roli AI nevylučuje.

Odstavec 5 doplňuje procesní rozměr: informace musí být poskytnuta nejpozději při první interakci, musí být jasná a zřetelná a musí splňovat požadavky na přístupnost (čl. 4 směrnice (EU) 2019/882 o přístupnosti výrobků a služeb). Odstavec 6 zdůrazňuje, že čl. 50 je přídatnou vrstvou povinností — nenahrazuje přísnější povinnosti pro vysoce rizikové systémy a nenahrazuje ani povinnosti transparentnosti z GDPR (čl. 13–15), ePrivacy nebo DSA. Odstavec 7 předvídá rozvoj soft-law nástrojů pod vedením Úřadu pro AI (srov. čl. 64 nařízení), přičemž Komisi svěřuje záložní pravomoc přijmout závazná pravidla prostřednictvím prováděcích aktů.

#### F. Kazuistika

**1. Modelová situace.** Tuzemská banka nasadí na webu a v mobilní aplikaci konverzačního chatbota dodaného softwarovou společností (poskytovatelem systému AI). Chatbot vystupuje pod jménem „Petra", s fotografií skutečné osoby a úvodní formulací „Dobrý den, jsem vaše osobní bankéřka". Informace, že jde o systém AI, je uvedena pouze v obchodních podmínkách internetového bankovnictví. Klient po týdnech komunikace zjistí, že jednal se strojem, a podá podnět orgánu dozoru. Důkazně je třeba obstarat: snímky uživatelského rozhraní, logy první interakce, smlouvu mezi bankou a dodavatelem (rozdělení rolí poskytovatel × zavádějící subjekt), technickou dokumentaci systému a znění obchodních podmínek.

**2. Právní otázka.** Je povinnost dle čl. 50 odst. 1 a 5 splněna tím, že informace o AI povaze chatbota je obsažena v obchodních podmínkách, ačkoli rozhraní systému antropomorfním designem aktivně vyvolává dojem komunikace s člověkem?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 50 odst. 1 (návrhová povinnost poskytovatele informovat o interakci se systémem AI, ledaže je to zřejmé přiměřeně informované, pozorné a obezřetné osobě) a odst. 5 (jasné a zřetelné poskytnutí informace nejpozději při první interakci; požadavky přístupnosti).
- *Související ustanovení téhož nařízení:* čl. 3 body 3 a 4 (poskytovatel/zavádějící subjekt), čl. 50 odst. 6 (kumulace s jinými vrstvami transparentnosti), čl. 50 odst. 7 (kodexy pro označování obsahu), čl. 99 odst. 4 písm. (g) (pokuta až 15 000 000 EUR nebo 3 % celosvětového ročního obratu za porušení čl. 50).
- *Související předpisy:* GDPR čl. 13–14 (informační povinnosti při zpracování osobních údajů); směrnice 2005/29/ES o nekalých obchodních praktikách (klamavé jednání a opomenutí; § 4 a násl. zákona č. 634/1992 Sb.); směrnice (EU) 2019/882 (přístupnost).
- *Judikatura:* standard „přiměřeně informované, pozorné a obezřetné osoby" navazuje na koncept průměrného spotřebitele dle ustálené judikatury SDEU (Gut Springenheide, C-210/96) — posouzení je normativní, nikoli empirické.

**4. Subsumpce.** Chatbot je systém AI určený k přímé interakci s fyzickými osobami (odst. 1). Výjimka „zřejmosti" nedopadá: antropomorfní design (lidské jméno, fotografie, sebeprezentace „osobní bankéřka") dojem strojové povahy nejen nevyvolává, ale cíleně potlačuje. Informace ukrytá v obchodních podmínkách nesplňuje odst. 5 — není poskytnuta jasně, zřetelně ani nejpozději při první interakci. Sporné je rozdělení odpovědnosti: povinnost odst. 1 je povinností návrhovou (tíží dodavatele jako poskytovatele), avšak banka konfigurací persony „Petra" klamavost spoluzaložila a může odpovídat dle spotřebitelského práva; pokud by systém podstatně změnila a provozovala pod vlastní značkou, mohla by se sama dostat do role poskytovatele (per analogiam čl. 25).

**5. Řešení.** Čl. 50 odst. 1 a 5 je porušen. Správný postup: zabudovat oznámení přímo do rozhraní (úvodní zpráva typu „Jsem virtuální asistent využívající umělou inteligenci", trvalé označení v záhlaví konverzace), zajistit přístupnost informace a smluvně vyjasnit role v hodnotovém řetězci. Orgán dozoru může uložit nápravná opatření a pokutu dle čl. 99 odst. 4 písm. (g); paralelně přichází v úvahu postih za klamavou obchodní praktiku. Riziko alternativního výkladu: poskytovatel může tvrdit, že AI povaha webových chatů je dnes obecně zřejmá — tento argument však oslabuje právě aktivní antropomorfizace.

**6. Varianty.** (i) Byl-li by chatbot od počátku viditelně označen „AI asistent" v okně konverzace, povinnost by byla splněna designem a spor by nevznikl. (ii) Šlo-li by o systém povolený zákonem k odhalování trestné činnosti (a nikoli veřejně dostupný k oznamování trestných činů), uplatnila by se výjimka odst. 1 věty druhé. (iii) Publikovala-li by banka pomocí AI generované texty o ekonomických tématech veřejného zájmu bez redakční kontroly, dopadla by na ni samostatná povinnost dle odst. 4 druhého pododstavce.

#### G. Protiargumenty a rizika

- **„AI povaha chatbotů je dnes obecně zřejmá."** Neutralizace: výjimka se posuzuje podle okolností a kontextu konkrétního nasazení; antropomorfní design záměrně vytváří opačný dojem a ten, kdo se výjimky dovolává, nese ohledně zřejmosti argumentační břemeno.
- **„Povinnost odst. 1 tíží jen poskytovatele, zavádějící subjekt postihnout nelze."** Uvnitř čl. 50 odst. 1 částečně správné, avšak odst. 6 výslovně zachovává jiné vrstvy povinností (nekalé praktiky, GDPR) dopadající na banku; hranice rolí se navíc posuzuje materiálně.
- **Slabé místo:** k čl. 50 dosud neexistuje rozhodovací praxe; hranici „zřejmosti" i formu „přiměřeného" označení deep fake dotvoří praxe a kodexy dle odst. 7. Určení českého dozorového orgánu závisí na adaptačním předpisu, který je třeba vždy ověřit.

#### H. Praktický závěr

Čl. 50 je vrstvou transparentnosti nezávislou na klasifikaci rizika: poskytovatel musí oznámení o AI povaze vestavět do návrhu systému, zavádějící subjekt musí označovat rozpoznávání emocí, biometrickou kategorizaci, deep fake a AI texty ve veřejném zájmu. Informace schovaná v obchodních podmínkách nikdy nepostačuje.

**Checklist (poskytovatel / zavádějící subjekt / advokát / orgán dozoru):**
- [ ] Určena role každého subjektu (poskytovatel × zavádějící subjekt) pro každou povinnost odst. 1–4.
- [ ] Oznámení o AI povaze je součástí návrhu rozhraní a zobrazí se nejpozději při první interakci (odst. 1 a 5).
- [ ] Syntetické výstupy jsou označeny strojově čitelně a detekovatelně; zdokumentován stav techniky (odst. 2).
- [ ] Deep fake a AI text ve veřejném zájmu zveřejněn jako uměle vytvořený, ledaže platí výjimka (umělecké dílo, redakční odpovědnost) (odst. 4).
- [ ] Informace splňuje požadavky přístupnosti; souběžně splněny povinnosti dle GDPR (odst. 3 a 6).

**Typicky rozhodné důkazy / podklady:** snímky a záznamy rozhraní, logy první interakce, technická dokumentace označování výstupů (vodoznak/metadata), smlouvy v hodnotovém řetězci, interní směrnice k redakční kontrole.

---

## Kapitola V — Obecné modely AI

**Oddíl 1 — Klasifikační pravidla**

### Čl. 51 — Klasifikace obecných modelů AI jako modelů se systémovým rizikem

**Doslovné znění (EN) — Article 51 — Classification of general-purpose AI models as general-purpose AI models with systemic risk:**

> 1. A general-purpose AI model shall be classified as a general-purpose AI model with systemic risk if it meets any of the following conditions:
>
> (a) it has high impact capabilities evaluated on the basis of appropriate technical tools and methodologies, including indicators and benchmarks;
>
> (b) based on a decision of the Commission, ex officio or following a qualified alert from the scientific panel, it has capabilities or an impact equivalent to those set out in point (a) having regard to the criteria set out in Annex XIII.
>
> 2. A general-purpose AI model shall be presumed to have high impact capabilities pursuant to paragraph 1, point (a), when the cumulative amount of computation used for its training measured in floating point operations is greater than 1025.
>
> 3. The Commission shall adopt delegated acts in accordance with Article 97 to amend the thresholds listed in paragraphs 1 and 2 of this Article, as well as to supplement benchmarks and indicators in light of evolving technological developments, such as algorithmic improvements or increased hardware efficiency, when necessary, for these thresholds to reflect the state of the art.

**Pracovní překlad (CZ):**

> 1. Obecný model AI se klasifikuje jako obecný model AI se systémovým rizikem, splňuje-li kteroukoli z těchto podmínek:
>
> (a) má vysoce výkonné schopnosti hodnocené na základě vhodných technických nástrojů a metod, včetně ukazatelů a srovnávacích testů;
>
> (b) na základě rozhodnutí Komise, z moci úřední nebo na základě kvalifikovaného upozornění vědeckého panelu, má schopnosti nebo dopad rovnocenné těm, které jsou stanoveny v písmenu (a), s přihlédnutím ke kritériím stanoveným v příloze XIII.
>
> 2. Obecný model AI se presumuje jako model s vysoce výkonnými schopnostmi podle odst. 1 písm. (a), pokud kumulativní množství výpočetních operací použitých pro jeho trénink, měřené v operacích s pohyblivou řádovou čárkou, překračuje 10^25.
>
> 3. Komise přijme akty v přenesené pravomoci v souladu s článkem 97, aby v případě potřeby upravila prahové hodnoty uvedené v odstavcích 1 a 2 tohoto článku a doplnila srovnávací testy a ukazatele s ohledem na vývoj technologií, jako jsou zdokonalení algoritmů nebo zvýšení výkonnosti hardwaru, tak aby tyto prahové hodnoty odrážely stav techniky.

**Výklad:** Článek 51 zavádí dvoustupňový klasifikační mechanismus pro identifikaci nejrizikovějších obecných modelů AI. Primárním kritériem je výpočetní kapacita tréninku (odst. 2): práh 10^25 FLOPs je kvalitativní aproximací stavu, při němž model dosahuje schopností srovnatelných s nejpokročilejšími systémy dostupnými v době přijímání nařízení (GPT-4 a obdobné modely). Tato numerická hranice je záměrně stanovena v normativním textu jako vyvratitelná domněnka (*presumption*), nikoli jako automatické pravidlo: poskytovatel může v rámci postupu dle čl. 52 prokázat, že konkrétní model navzdory překročení prahu systémové riziko nevykazuje — například proto, že byl trénován na vysoce specializovaném korpusu s omezenou generalizovatelností.

Sekundárním kritériem (odst. 1 písm. b) je diskreční rozhodnutí Komise — buď z moci úřední (*ex officio*), nebo na základě kvalifikovaného upozornění vědeckého panelu (čl. 68). Tím je zachycena třída modelů, které prahu 10^25 FLOPs nedosahují, přesto však vykazují systémové riziko s ohledem na přílohu XIII (např. mimořádná víceúčelovost, schopnost generování CBRN obsahu nebo přístup k citlivé infrastruktuře). Kritéria přílohy XIII — rozsah dopadu, počet uživatelů, míra autonomie, potenciál k posílení biologických hrozeb — tvoří otevřený katalog, jejž Komise může akty v přenesené pravomoci rozšiřovat (odst. 3). Tím nařízení buduje adaptivní regulační rámec reagující na technologický vývoj bez nutnosti revize základního textu.

Z hlediska systematiky nařízení je čl. 51 klíčovým bifurkačním bodem: modely klasifikované jako GPAI se systémovým rizikem vstupují do násobně přísnějšího regulačního koridoru (čl. 55), zatímco ostatní GPAI podléhají pouze základním povinnostem kapitoly V (čl. 53–54). Samotná klasifikace je deklaratorní — okamžikem splnění podmínek, nikoli vydáním rozhodnutí — s výjimkou klasifikace dle odst. 1 písm. b), kde je rozhodnutí Komise konstitutivní.

#### F. Kazuistika

**1. Modelová situace.** Evropský poskytovatel vyvíjí vícejazyčný základový model; podle interního plánu tréninkových běhů kumulativní výpočet překročí 10^25 FLOPs. Model je však trénován převážně na úzce specializovaném biomedicínském korpusu a podle interních benchmarků zaostává v obecných schopnostech za frontier modely. Vedení společnosti řeší, zda se model stane „obecným modelem AI se systémovým rizikem" a od kdy. Důkazy: logy výpočetního clusteru a faktury za výpočetní kapacitu, interní metodika výpočtu kumulativních FLOPs, výsledky benchmarků a hodnocení schopností.

**2. Právní otázka.** Zakládá překročení prahu 10^25 FLOPs automaticky klasifikaci obecného modelu AI jako modelu se systémovým rizikem, nebo jde o vyvratitelnou domněnku — a k jakému okamžiku klasifikace nastává?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 51 odst. 1 písm. (a) a odst. 2 (domněnka vysoce výkonných schopností při kumulativním tréninkovém výpočtu nad 10^25 FLOPs), odst. 1 písm. (b) (konstitutivní rozhodnutí Komise dle přílohy XIII), odst. 3 (aktualizace prahů delegovanými akty).
- *Související ustanovení téhož nařízení:* čl. 3 body 63 a 65 (definice obecného modelu AI a systémového rizika), čl. 52 (oznámení a vyvracení domněnky), čl. 55 (důsledky klasifikace), příloha XIII, čl. 97 (delegované akty), čl. 101 (pokuty).
- *Související předpisy:* čl. 290 SFEU (meze delegace normotvorby na Komisi).
- *Judikatura:* k povaze vyvratitelných domněnek a rozložení důkazního břemene v unijním právu srov. judikaturu SDEU k domněnce rozhodujícího vlivu mateřské společnosti (Akzo Nobel, C-97/08 P): domněnka je slučitelná s právem na obhajobu, lze-li ji vyvrátit konkrétními důkazy.

**4. Subsumpce.** Překročením prahu 10^25 FLOPs se aktivuje domněnka dle odst. 2; klasifikace dle odst. 1 písm. (a) je deklaratorní — nastává ex lege okamžikem splnění podmínky (resp. okamžikem, kdy je zřejmé, že splněna bude), nikoli rozhodnutím Komise. Specializace korpusu a slabší obecné schopnosti jsou typově způsobilé argumenty pro vyvrácení domněnky postupem dle čl. 52 odst. 2; předtím je však nutno posoudit, zda model vůbec naplňuje definiční znak „významné obecnosti" (čl. 3 bod 63) — není-li obecným modelem AI, kapitola V nedopadá vůbec. Neprokázané zatím zůstává skutečné spektrum schopností; bez robustních benchmarků bude vyvracení domněnky neúspěšné.

**5. Řešení.** Poskytovatel musí průběžně monitorovat kumulativní výpočet, oznámit Komisi splnění podmínky do dvou týdnů (čl. 52 odst. 1) a argumenty proti klasifikaci připojit již k oznámení. Do rozhodnutí Komise o vyvrácení domněnky je třeba se připravovat na režim čl. 55 (hodnocení modelu, zmírňování rizik, incidenty, kybernetická bezpečnost). Pravděpodobný výsledek: u skutečně specializovaného modelu má vyvracení reálnou šanci, důkazní břemeno však nese poskytovatel; opomenutí oznámení je samostatně sankcionovatelné (čl. 101).

**6. Varianty.** (i) Při kumulativním výpočtu 8×10^24 FLOPs domněnka nenastane; Komise však může model označit rozhodnutím dle odst. 1 písm. (b) na základě kritérií přílohy XIII (počet uživatelů, multimodalita, dosah) — zde je rozhodnutí konstitutivní. (ii) Model určený výlučně k jediné úzké úloze (např. predikci struktury proteinů) nebude „obecným" modelem AI a čl. 51 se neuplatní.

#### G. Protiargumenty a rizika

- **„Práh FLOPs je arbitrární a rychle zastará"** (algoritmická efektivita umožní stejné schopnosti s menším výpočtem). Neutralizace: jde pouze o domněnku, nikoli definici; odst. 3 svěřuje Komisi pravomoc práh i ukazatele průběžně aktualizovat delegovanými akty.
- **„Deklaratorní klasifikace vytváří právní nejistotu"** — poskytovatel nemusí přesně vědět, kdy práh překročil. Neutralizace: lhůta dle čl. 52 běží i od okamžiku, kdy je zřejmé, že práh splněn bude; plánování tréninku tuto informaci poskytuje předem a monitoring výpočtu je součástí náležité péče.
- **Slabé místo:** chybí závazná metodika měření kumulativního výpočtu (zahrnutí doladění, syntetických dat či neúspěšných běhů); do vydání delegovaných aktů a metodik dle čl. 53 odst. 5 přetrvává nejistota.

#### H. Praktický závěr

Čl. 51 je bifurkačním bodem kapitoly V: kdo plánuje trénink poblíž prahu 10^25 FLOPs, musí výpočet měřit a dokumentovat od počátku, neboť klasifikace nastává ze zákona a spouští oznamovací povinnost i přísný režim čl. 55.

**Checklist (poskytovatel / advokát):**
- [ ] Posouzeno, zda model naplňuje definici obecného modelu AI (čl. 3 bod 63).
- [ ] Zavedena průběžná evidence kumulativního tréninkového výpočtu včetně dokumentované metodiky.
- [ ] Nastaven interní spouštěč oznámení Komisi (čl. 52 odst. 1) již ve fázi plánování tréninku.
- [ ] Připraveny podklady pro případné vyvrácení domněnky (benchmarky, popis specializace a omezené generalizovatelnosti).
- [ ] Sledovány delegované akty Komise měnící prahy a ukazatele (odst. 3) a seznam dle čl. 52 odst. 6.

**Typicky rozhodné důkazy / podklady:** logy tréninkových běhů, interní výpočty FLOPs, smlouvy a faktury za výpočetní kapacitu, benchmarková hodnocení schopností, dokumentace architektury modelu.

---

### Čl. 52 — Postup klasifikace obecných modelů AI se systémovým rizikem

**Doslovné znění (EN) — Article 52 — Procedure:**

> 1. Where a general-purpose AI model meets the condition referred to in Article 51(1), point (a), the relevant provider shall notify the Commission without delay and in any event within two weeks after that requirement is met or it becomes known that it will be met. That notification shall include the information necessary to demonstrate that the relevant requirement has been met. If the Commission becomes aware of a general-purpose AI model presenting systemic risks of which it has not been notified, it may decide to designate it as a model with systemic risk.
>
> 2. The provider of a general-purpose AI model that meets the condition referred to in Article 51(1), point (a), may present, with its notification, sufficiently substantiated arguments to demonstrate that, exceptionally, although it meets that requirement, the general-purpose AI model does not present, due to its specific characteristics, systemic risks and therefore should not be classified as a general-purpose AI model with systemic risk.
>
> 3. Where the Commission concludes that the arguments submitted pursuant to paragraph 2 are not sufficiently substantiated and the relevant provider was not able to demonstrate that the general-purpose AI model does not present, due to its specific characteristics, systemic risks, it shall reject those arguments, and the general-purpose AI model shall be considered to be a general-purpose AI model with systemic risk.
>
> 4. The Commission may designate a general-purpose AI model as presenting systemic risks, ex officio or following a qualified alert from the scientific panel pursuant to Article 90(1), point (a), on the basis of criteria set out in Annex XIII.
>
> The Commission is empowered to adopt delegated acts in accordance with Article 97 in order to amend Annex XIII by specifying and updating the criteria set out in that Annex.
>
> 5. Upon a reasoned request of a provider whose model has been designated as a general-purpose AI model with systemic risk pursuant to paragraph 4, the Commission shall take the request into account and may decide to reassess whether the general-purpose AI model can still be considered to present systemic risks on the basis of the criteria set out in Annex XIII. Such a request shall contain objective, detailed and new reasons that have arisen since the designation decision. Providers may request reassessment at the earliest six months after the designation decision. Where the Commission, following its reassessment, decides to maintain the designation as a general-purpose AI model with systemic risk, providers may request reassessment at the earliest six months after that decision.
>
> 6. The Commission shall ensure that a list of general-purpose AI models with systemic risk is published and shall keep that list up to date, without prejudice to the need to observe and protect intellectual property rights and confidential business information or trade secrets in accordance with Union and national law.
>
> SECTION 2
>
> Obligations for providers of general-purpose AI models

**Pracovní překlad (CZ):**

> 1. Splňuje-li obecný model AI podmínku uvedenou v čl. 51 odst. 1 písm. (a), příslušný poskytovatel to bez prodlení oznámí Komisi, a to v každém případě do dvou týdnů od splnění tohoto požadavku nebo od okamžiku, kdy se dozví, že bude splněn. Oznámení musí obsahovat informace nezbytné k prokázání splnění příslušného požadavku. Pokud se Komise dozví o obecném modelu AI vykazujícím systémová rizika, o němž jí nebylo oznámení zasláno, může rozhodnout o jeho označení za model se systémovým rizikem.
>
> 2. Poskytovatel obecného modelu AI, který splňuje podmínku uvedenou v čl. 51 odst. 1 písm. (a), může spolu s oznámením předložit dostatečně odůvodněné argumenty k prokázání toho, že výjimečně — ačkoli tento požadavek splňuje — obecný model AI s ohledem na své specifické vlastnosti systémová rizika nepředstavuje, a proto by neměl být klasifikován jako obecný model AI se systémovým rizikem.
>
> 3. Dospěje-li Komise k závěru, že argumenty předložené podle odstavce 2 nejsou dostatečně odůvodněné a že příslušný poskytovatel nebyl schopen prokázat, že obecný model AI s ohledem na své specifické vlastnosti systémová rizika nepředstavuje, tyto argumenty zamítne a obecný model AI se považuje za obecný model AI se systémovým rizikem.
>
> 4. Komise může označit obecný model AI jako model vykazující systémová rizika, a to z moci úřední nebo na základě kvalifikovaného upozornění vědeckého panelu podle čl. 90 odst. 1 písm. (a), na základě kritérií stanovených v příloze XIII.
>
> Komisi je svěřena pravomoc přijímat akty v přenesené pravomoci v souladu s článkem 97 za účelem změny přílohy XIII prostřednictvím upřesnění a aktualizace kritérií v ní stanovených.
>
> 5. Na základě odůvodněné žádosti poskytovatele, jehož model byl označen za obecný model AI se systémovým rizikem podle odstavce 4, Komise tuto žádost zohlední a může rozhodnout o opětovném posouzení, zda obecný model AI nadále lze považovat za model vykazující systémová rizika na základě kritérií stanovených v příloze XIII. Taková žádost musí obsahovat objektivní, podrobné a nové důvody, které nastaly po vydání rozhodnutí o označení. Poskytovatelé mohou požádat o opětovné posouzení nejdříve šest měsíců po vydání rozhodnutí o označení. Pokud se Komise po svém opětovném posouzení rozhodne zachovat označení jako obecného modelu AI se systémovým rizikem, mohou poskytovatelé požádat o opětovné posouzení nejdříve šest měsíců po tomto rozhodnutí.
>
> 6. Komise zajistí zveřejnění a průběžnou aktualizaci seznamu obecných modelů AI se systémovým rizikem, aniž jsou dotčeny povinnosti dodržovat a chránit práva duševního vlastnictví a důvěrné obchodní informace nebo obchodní tajemství v souladu s právem Unie a vnitrostátním právem.

**Výklad:** Článek 52 upravuje procesní mechanismus pro vstup obecného modelu AI do kategorie modelů se systémovým rizikem a nastavuje základní procedurální záruky jak na straně Komise, tak na straně poskytovatele.

Základní oznamovací povinnost (odst. 1) je závaznou správní procedurou s pevnou dvoutýdenní lhůtou počítanou od okamžiku, kdy je splněn (nebo je zřejmé, že bude splněn) práh 10^25 FLOPs. Lhůta je krátká a úmyslně tak tlačí na průběžné monitorování výpočetní náročnosti tréninku; pochybení při oznámení může být předmětem sankcí dle čl. 101. Iniciativa Komise *ex officio* je pojistným ventilem pro případ, kdy se poskytovatel oznamovací povinnosti vyhne nebo si ji neuvědomí.

Odstavce 2 a 3 zavádějí institut vyvratitelné domněnky a *rebuttal* procedury: poskytovatel může polemizovat s klasifikací a argumentovat specifickými vlastnostmi modelu (úzký záběr, omezená distribuce, technické zábrany). Tato výjimka je striktně individuální a navázána na konkrétní posouzení Komise — nejde o obecnou výjimku pro celou třídu modelů. Komise musí argumenty věcně posoudit a případné zamítnutí odůvodnit, což zakládá přezkumný základ pro správní soudnictví Unie.

Odstavec 4 (klasifikace *ex officio* na základě přílohy XIII) doplňuje řízení o diskreční pravomoc Komise, jíž může zachytit modely nepřekračující numerický práh, avšak jinak nebezpečné. Vědecký panel (čl. 68) zde plní roli odborného poradce a zároveň aktivačního mechanismu — jeho „kvalifikované upozornění" není pro Komisi závazné, ale vytváří procedurální impuls k zahájení šetření.

Mechanismus přezkumu (odst. 5) zavádí stabilizační ochrannou dobu šesti měsíců: dokud tato lhůta neuplyne, nemůže poskytovatel opakovaně zahltit Komisi žádostmi o přezkum. Podmínka, že žádost musí obsahovat „objektivní, podrobné a nové důvody", brání čistě účelovým žádostem; analogii lze nalézt v právu na přezkum rozhodnutí o mezinárodní ochraně dle směrnice (EU) 2013/32.

Zveřejnění a udržování aktuálního seznamu (odst. 6) je základním nástrojem právní jistoty a transparentnosti trhu: navazující poskytovatelé a zavádějící subjekty potřebují vědět, s jakým modelem pracují, aby mohli plnit vlastní povinnosti. Ochrana obchodního tajemství a práv duševního vlastnictví je explicitně vyvažována povinností zveřejnění, přičemž rozsah uveřejňovaných informací určí Komise v praxi.

#### F. Kazuistika

**1. Modelová situace.** Poskytovatel usazený mimo EU dokončí 1. března tréninkový běh, jímž kumulativní výpočet modelu překročí 10^25 FLOPs; interní tým o tom má od počátku přehled. Oznámení Komisi však odešle až v polovině dubna a připojí k němu argumentaci, že model systémové riziko nepředstavuje (bezpečnostní doladění, přístup pouze přes API s filtry, omezený kontext nasazení). Komise argumenty posoudí jako nedostatečně podložené a zamítne je. Důkazy: záznamy o průběhu tréninku a okamžiku překročení prahu, interní komunikace dokládající vědomost, podané oznámení s přílohami, zamítavé rozhodnutí Komise.

**2. Právní otázka.** Od kterého okamžiku běží dvoutýdenní lhůta k oznámení dle čl. 52 odst. 1 a jaké právní důsledky má její zmeškání a následné zamítnutí argumentů poskytovatele dle čl. 52 odst. 3?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 52 odst. 1 (oznámení „bez prodlení, nejpozději do dvou týdnů" od splnění podmínky nebo od vědomosti, že splněna bude), odst. 2–3 (vyvracení domněnky a jeho zamítnutí), odst. 4 (označení ex officio dle přílohy XIII), odst. 5 (opětovné posouzení nejdříve po šesti měsících), odst. 6 (veřejný seznam).
- *Související ustanovení téhož nařízení:* čl. 51 (hmotněprávní kritéria klasifikace), čl. 55 (povinnosti po klasifikaci), čl. 90 odst. 1 písm. (a) (kvalifikované upozornění vědeckého panelu), čl. 101 (pokuty pro poskytovatele obecných modelů AI až 3 % celosvětového ročního obratu nebo 15 000 000 EUR).
- *Související předpisy:* čl. 41 Listiny základních práv EU (právo na řádnou správu, povinnost odůvodnění); čl. 263 SFEU (žaloba na neplatnost rozhodnutí Komise).
- *Judikatura:* podle ustálené judikatury SDEU k čl. 263 SFEU je napadnutelným aktem každý akt se závaznými právními účinky měnící právní postavení žalobce (IBM v. Komise, 60/81) — zamítnutí argumentů dle odst. 3 i designace dle odst. 4 tento test splňují.

**4. Subsumpce.** Práh byl splněn 1. března a poskytovatel o tom věděl (resp. věděl již dříve, že splněn bude); lhůta uplynula v polovině března a dubnové oznámení je opožděné — porušení oznamovací povinnosti je sankcionovatelné dle čl. 101 odst. 1. Argumenty o „specifických vlastnostech" (API s filtry, bezpečnostní doladění) jsou typově způsobilé, musí však být „dostatečně odůvodněné" — paušální tvrzení bez měřitelných dokladů Komise zamítne a model se poté bez dalšího považuje za model se systémovým rizikem (odst. 3). Mechanismus opětovného posouzení dle odst. 5 zde nedopadá: je vyhrazen modelům označeným rozhodnutím Komise dle odst. 4, nikoli klasifikaci ex lege dle čl. 51 odst. 1 písm. (a).

**5. Řešení.** I opožděné oznámení je nutné podat — pokračující prodlení zvyšuje riziko sankce i designace z moci úřední (odst. 1 věta třetí). Proti zamítavému rozhodnutí Komise se lze bránit žalobou k Tribunálu; žaloba nemá odkladný účinek, povinnosti čl. 55 je proto třeba plnit od klasifikace. Prakticky: dokumentovat okamžik vědomosti o splnění prahu, oznámení podávat preventivně před dokončením tréninku a vyvracení domněnky koncipovat jako doložený technický spis, nikoli právní polemiku.

**6. Varianty.** (i) Zjistí-li Komise existenci neoznámeného modelu sama (např. z kvalifikovaného upozornění vědeckého panelu), může jej označit přímo — poskytovatel ztrácí výhodu řízeného procesu i možnost současného rebuttalu. (ii) Byl-li model označen rozhodnutím dle odst. 4, může poskytovatel po šesti měsících žádat o přezkum, avšak jen na základě objektivních, podrobných a nových důvodů (např. trvalého stažení nejschopnější verze z trhu).

#### G. Protiargumenty a rizika

- **„Dvoutýdenní lhůta je nepřiměřeně krátká a okamžik splnění prahu nelze určit."** Neutralizace: lhůta běží již od okamžiku, kdy je zřejmé, že práh splněn bude — u plánovaných tréninkových běhů tedy fakticky předem; požadavkem je průběžný monitoring, nikoli dodatečné dopočítávání.
- **„Zamítnutí rebuttalu bez podrobných kritérií porušuje právo na řádnou správu."** Neutralizace: Komise je vázána povinností odůvodnění (čl. 41 Listiny EU) a podléhá soudnímu přezkumu; procesní vady lze namítat před Tribunálem.
- **Slabé místo:** nařízení nestanoví lhůtu, v níž Komise musí o argumentech rozhodnout, ani výslovný mezitímní režim — z konstrukce domněnky však plyne, že do jejího vyvrácení se model za systémově rizikový považuje. Rozhodovací praxe zatím chybí.

#### H. Praktický závěr

Čl. 52 je procesní branou režimu systémového rizika: rozhodující je včasné oznámení (dva týdny od splnění či předvídatelnosti splnění prahu) a kvalita důkazně podloženého vyvracení domněnky podaného nejlépe současně s oznámením.

**Checklist (poskytovatel / advokát):**
- [ ] Průběžný monitoring kumulativního výpočtu s eskalací na compliance tým.
- [ ] Oznámení Komisi připraveno před dokončením tréninku; obsahuje informace prokazující splnění podmínky.
- [ ] Případné vyvracení domněnky (odst. 2) podáno spolu s oznámením a podloženo technickými důkazy.
- [ ] Evidence šestiměsíčních lhůt pro žádost o opětovné posouzení u designace dle odst. 4.
- [ ] Pravidelná kontrola zveřejněného seznamu modelů se systémovým rizikem (odst. 6).

**Typicky rozhodné důkazy / podklady:** záznamy o tréninkových bězích a výpočtu FLOPs, interní komunikace o dosažení prahu, podané oznámení s přílohami, korespondence a rozhodnutí Komise, technické zprávy o vlastnostech modelu.

---

**Oddíl 2 — Povinnosti poskytovatelů obecných modelů AI**

### Čl. 53 — Povinnosti poskytovatelů obecných modelů AI

**Doslovné znění (EN) — Article 53 — Obligations for providers of general-purpose AI models:**

> 1. Providers of general-purpose AI models shall:
>
> (a) draw up and keep up-to-date the technical documentation of the model, including its training and testing process and the results of its evaluation, which shall contain, at a minimum, the information set out in Annex XI for the purpose of providing it, upon request, to the AI Office and the national competent authorities;
>
> (b) draw up, keep up-to-date and make available information and documentation to providers of AI systems who intend to integrate the general-purpose AI model into their AI systems. Without prejudice to the need to observe and protect intellectual property rights and confidential business information or trade secrets in accordance with Union and national law, the information and documentation shall:
>
> (i) enable providers of AI systems to have a good understanding of the capabilities and limitations of the general-purpose AI model and to comply with their obligations pursuant to this Regulation; and
>
> (ii) contain, at a minimum, the elements set out in Annex XII;
>
> (c) put in place a policy to comply with Union law on copyright and related rights, and in particular to identify and comply with, including through state-of-the-art technologies, a reservation of rights expressed pursuant to Article 4(3) of Directive (EU) 2019/790;
>
> (d) draw up and make publicly available a sufficiently detailed summary about the content used for training of the general-purpose AI model, according to a template provided by the AI Office.
>
> 2. The obligations set out in paragraph 1, points (a) and (b), shall not apply to providers of AI models that are released under a free and open-source licence that allows for the access, usage, modification, and distribution of the model, and whose parameters, including the weights, the information on the model architecture, and the information on model usage, are made publicly available. This exception shall not apply to general-purpose AI models with systemic risks.
>
> 3. Providers of general-purpose AI models shall cooperate as necessary with the Commission and the national competent authorities in the exercise of their competences and powers pursuant to this Regulation.
>
> 4. Providers of general-purpose AI models may rely on codes of practice within the meaning of Article 56 to demonstrate compliance with the obligations set out in paragraph 1 of this Article, until a harmonised standard is published. Compliance with European harmonised standards grants providers the presumption of conformity to the extent that those standards cover those obligations. Providers of general-purpose AI models who do not adhere to an approved code of practice or do not comply with a European harmonised standard shall demonstrate alternative adequate means of compliance for assessment by the Commission.
>
> 5. For the purpose of facilitating compliance with Annex XI, in particular points 2 (d) and (e) thereof, the Commission is empowered to adopt delegated acts in accordance with Article 97 to detail measurement and calculation methodologies with a view to allowing for comparable and verifiable documentation.
>
> 6. The Commission is empowered to adopt delegated acts in accordance with Article 97(2) to amend Annexes XI and XII in light of evolving technological developments.
>
> 7. Any information or documentation obtained pursuant to this Article, including trade secrets, shall be treated in accordance with the confidentiality obligations set out in Article 78.

**Pracovní překlad (CZ):**

> 1. Poskytovatelé obecných modelů AI:
>
> (a) vypracují a průběžně aktualizují technickou dokumentaci modelu, včetně jeho procesu tréninku a testování a výsledků jeho hodnocení, která musí obsahovat alespoň informace stanovené v příloze XI za účelem jejich poskytování na žádost Úřadu pro AI a příslušným vnitrostátním orgánům;
>
> (b) vypracují, průběžně aktualizují a zpřístupní informace a dokumentaci poskytovatelům systémů AI, kteří hodlají integrovat obecný model AI do svých systémů AI. Aniž jsou dotčeny povinnosti dodržovat a chránit práva duševního vlastnictví a důvěrné obchodní informace nebo obchodní tajemství v souladu s právem Unie a vnitrostátním právem, informace a dokumentace musí:
>
> (i) umožnit poskytovatelům systémů AI dobré pochopení schopností a omezení obecného modelu AI a plnění jejich povinností podle tohoto nařízení; a
>
> (ii) obsahovat alespoň prvky stanovené v příloze XII;
>
> (c) zavedou politiku k dodržování práva Unie v oblasti autorského práva a práv s ním souvisejících, a to zejména ke zjišťování a dodržování — i prostřednictvím technologií nejmodernějšího stavu techniky — vyhrazení práv vyjádřeného podle čl. 4 odst. 3 směrnice (EU) 2019/790;
>
> (d) vypracují a veřejně zpřístupní dostatečně podrobný souhrn obsahu použitého pro trénink obecného modelu AI podle šablony poskytnuté Úřadem pro AI.
>
> 2. Povinnosti stanovené v odst. 1 písm. (a) a (b) se nevztahují na poskytovatele modelů AI vydaných pod licencí svobodného a otevřeného zdrojového kódu, která umožňuje přístup k modelu, jeho použití, úpravu a distribuci, a jejichž parametry, včetně vah, informací o architektuře modelu a informací o použití modelu, jsou veřejně dostupné. Tato výjimka se nevztahuje na obecné modely AI se systémovým rizikem.
>
> 3. Poskytovatelé obecných modelů AI spolupracují s Komisí a příslušnými vnitrostátními orgány v nezbytném rozsahu při výkonu jejich pravomocí a oprávnění podle tohoto nařízení.
>
> 4. Poskytovatelé obecných modelů AI se mohou při prokazování souladu s povinnostmi stanovenými v odstavci 1 tohoto článku opřít o kodexy správné praxe ve smyslu článku 56, a to do doby zveřejnění harmonizované normy. Soulad s evropskými harmonizovanými normami zakládá pro poskytovatele presumpci shody v rozsahu, v jakém tyto normy pokrývají příslušné povinnosti. Poskytovatelé obecných modelů AI, kteří nepřistoupí ke schválenému kodexu správné praxe nebo nesplňují evropskou harmonizovanou normu, musí Komisi prokázat alternativní přiměřené prostředky zajištění souladu.
>
> 5. Za účelem usnadnění souladu s přílohou XI, zejména s body 2 písm. (d) a (e) této přílohy, je Komisi svěřena pravomoc přijímat akty v přenesené pravomoci v souladu s článkem 97, jimiž podrobně stanoví metody měření a výpočtu s cílem umožnit srovnatelnou a ověřitelnou dokumentaci.
>
> 6. Komisi je svěřena pravomoc přijímat akty v přenesené pravomoci v souladu s čl. 97 odst. 2 za účelem změny příloh XI a XII s ohledem na vývoj technologií.
>
> 7. Veškeré informace nebo dokumentace získané podle tohoto článku, včetně obchodních tajemství, se zpracovávají v souladu s povinnostmi mlčenlivosti stanovenými v článku 78.

**Výklad:** Článek 53 je základní normou povinností pro všechny poskytovatele obecných modelů AI — bez ohledu na to, zda jsou klasifikovány jako modely se systémovým rizikem. Povinnosti dopadají na poskytovatele jako takové (tj. na subjekt, který model vyvíjí a uvádí na trh), nikoli na navazující poskytovatele systémů AI ani na zavádějící subjekty.

Povinnost technické dokumentace dle přílohy XI je strukturálně analogická technické dokumentaci pro vysoce rizikové systémy AI (příloha IV), avšak její obsah je přizpůsoben specifice základových modelů: zachycuje tréninkové sady, metodologii, hodnocení výkonu a bezpečnostní testování. Dokumentace je primárně určena Úřadu pro AI (čl. 64) a vnitrostátním orgánům — jde tedy o interní (neveřejnou) povinnost, na rozdíl od souhrnu tréninkových dat (odst. 1 písm. d), který je veřejný.

Povinnost zpřístupnění informací navazujícím poskytovatelům (odst. 1 písm. b) ve spojení s přílohou XII představuje zásadní nástroj pro přenesení odpovědnosti v hodnotovém řetězci AI: navazující poskytovatel, který integruje GPAI do svého systému AI, musí obdržet informace dostatečné k tomu, aby mohl plnit vlastní povinnosti — zejména ty plynoucí z kapitoly III, je-li integrující systém systémem vysokého rizika. Ochrana obchodního tajemství je explicitně připuštěna, avšak nesmí sloužit jako blanketní odmítnutí sdílení: rozsah sdílení musí být dostatečný k naplnění účelu povinnosti.

Povinnost autorsko-právní politiky (odst. 1 písm. c) je přímým průsečíkem AI Act a autorského práva EU — konkrétně čl. 4 odst. 3 směrnice (EU) 2019/790 (DSM směrnice), který poskytovatelům obsahu umožňuje vyhradit si právo k text-and-data-miningu (*opt-out*). Poskytovatel GPAI je povinen tato vyhrazení aktivně vyhledávat a respektovat, a to prostředky „nejmodernějšího stavu techniky" — například identifikací strojově čitelných metadat (robots.txt, rezervace práv dle iniciativ Rightsreserved). Jde o jednu z nejvíce diskutovaných povinností nařízení, neboť zasahuje přímo do tréninkového procesu; její praktická vymahatelnost je podmíněna vytvořením ověřitelného záznamu o přijatých opatřeních.

Veřejný souhrn tréninkových dat (odst. 1 písm. d) je kompromisem mezi transparentností a ochranou obchodního tajemství: šablona vypracovaná Úřadem pro AI určí, jaká míra granularity se požaduje. Osvobození modelů s otevřeným zdrojovým kódem (odst. 2) — specificky modelů, jejichž váhy i architektura jsou veřejně dostupné — je politicky citlivou výjimkou, která reaguje na obavy výzkumné a open-source komunity; výjimka se však výslovně nevztahuje na GPAI se systémovým rizikem, aby bylo zabráněno obejití přísnějšího režimu pouhým uvolněním vah modelu. Soulad s požadavky lze prokazovat adhezí ke kódexu správné praxe (čl. 56) nebo — po jejich vydání — harmonizovanými normami, přičemž alternativní prostředky souladu musí být Komisi prokázány ad hoc (odst. 4).

#### F. Kazuistika

**1. Modelová situace.** Česká technologická společnost vyvine obecný model AI (jazykový model pod prahem 10^25 FLOPs), zpřístupní jej na trhu Unie přes placené API a část vah uvolní pod licencí zakazující komerční užití. Tuzemský vydavatelský dům zjistí, že model byl trénován i na jeho zpravodajských článcích, ačkoli na svém webu strojově čitelně vyhradil práva k vytěžování textů a dat (robots.txt, TDM Reservation Protocol). Souběžně fintech integrující model do systému hodnocení úvěruschopnosti (vysoce rizikový systém) žádá dokumentaci dle přílohy XII; poskytovatel ji odmítá vydat s odkazem na obchodní tajemství. Důkazy: crawl logy a seznam tréninkových zdrojů, podoba strojově čitelné výhrady, autorskoprávní politika poskytovatele, zveřejněný souhrn tréninkového obsahu, korespondence s navazujícím poskytovatelem.

**2. Právní otázka.** Porušuje poskytovatel obecného modelu AI čl. 53 odst. 1 písm. (c), jestliže při tréninku nerespektoval strojově čitelnou výhradu práv dle čl. 4 odst. 3 směrnice (EU) 2019/790, a může se s odkazem na částečné uvolnění vah či obchodní tajemství zprostit povinností dle odst. 1 písm. (a), (b) a (d)?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 53 odst. 1 písm. (a)–(d) (technická dokumentace dle přílohy XI; informace navazujícím poskytovatelům dle přílohy XII; autorskoprávní politika; veřejný souhrn tréninkového obsahu), odst. 2 (výjimka pro svobodné a otevřené modely — jen pro písm. (a) a (b)), odst. 4 (kodexy a presumpce shody), odst. 7 (důvěrnost dle čl. 78).
- *Související ustanovení téhož nařízení:* čl. 56 (kodex správné praxe pro GPAI), čl. 91 (pravomoc Komise vyžádat informace), čl. 101 (pokuty), bod odůvodnění 106 (povinnost respektovat výhrady bez ohledu na místo tréninku).
- *Související předpisy:* čl. 4 odst. 3 směrnice (EU) 2019/790 (výhrada práv k TDM) a její transpozice v § 39c a 39d autorského zákona (zák. č. 121/2000 Sb., ve znění zák. č. 429/2022 Sb.); § 2976 o. z. (nekalá soutěž).
- *Judikatura:* SDEU vykládá výjimky z autorského práva restriktivně a v rámci tříkrokového testu (Infopaq, C-5/08; ACI Adam, C-435/12); první vnitrostátní rozhodnutí k TDM výjimkám při tvorbě tréninkových datasetů (LG Hamburg ve věci LAION, 2024) aplikovalo výzkumnou výjimku a obiter se vyjádřilo ke strojové čitelnosti výhrad.

**4. Subsumpce.** Model je obecným modelem AI uváděným na trh Unie, čl. 53 tedy dopadá. Licence zakazující komerční užití není „svobodnou a otevřenou licencí" ve smyslu odst. 2 — výjimka z písm. (a) a (b) se neuplatní; nadto se výjimka nikdy nevztahuje na písm. (c) a (d). Strojově čitelná výhrada na webu vydavatele je výhradou dle čl. 4 odst. 3 DSM směrnice; poskytovatel ji byl povinen prostředky odpovídajícími stavu techniky „zjišťovat a dodržovat" — její ignorace zakládá porušení písm. (c). Odmítnutí dokumentace navazujícímu poskytovateli paušálním odkazem na obchodní tajemství neobstojí: minimální obsah přílohy XII musí být poskytnut tak, aby fintech mohl plnit povinnosti kapitoly III; ochrana tajemství se řeší smluvně (závazkem důvěrnosti), nikoli odepřením.

**5. Řešení.** Komise (Úřad pro AI) může vyžádat dokumentaci, vymáhat nápravu a uložit pokutu dle čl. 101; veřejnoprávní vymáhání nevylučuje souběžné soukromoprávní nároky vydavatele z autorského práva (zdržení, bezdůvodné obohacení, náhrada škody) před českými soudy. Správný postup poskytovatele: zavést dokumentovanou autorskoprávní politiku (respektování robots.txt a obdobných protokolů, proces vyřizování výhrad a stížností), zveřejnit souhrn tréninkového obsahu podle šablony Úřadu pro AI, zpřístupnit fintechu dokumentaci dle přílohy XII pod závazkem důvěrnosti a doplnit technickou dokumentaci dle přílohy XI.

**6. Varianty.** (i) Byl-li by model uvolněn plně otevřeně (váhy, architektura i informace o užití veřejně dostupné) a nešlo o model se systémovým rizikem, odpadly by povinnosti písm. (a) a (b) — povinnosti písm. (c) a (d) však trvají vždy. (ii) Byl-li by model klasifikován jako model se systémovým rizikem, výjimka odst. 2 by se neuplatnila vůbec a přistoupily by povinnosti čl. 55.

#### G. Protiargumenty a rizika

- **„AI Act nezakládá vydavateli soukromá práva — porušení písm. (c) vymáhá jen Komise."** Z hlediska nařízení správné, avšak autorskoprávní nároky existují nezávisle na AI Act; porušení veřejnoprávní povinnosti může nadto indikovat nekalosoutěžní jednání.
- **„Trénink proběhl mimo EU, unijní autorské právo nedopadá."** Neutralizace: dle bodu odůvodnění 106 musí poskytovatel uvádějící model na trh Unie zavést politiku respektující výhrady bez ohledu na jurisdikci tréninku (level playing field); extrateritoriální přesah je předmětem odborné kritiky, pro praxi je s ním však třeba počítat.
- **Slabé místo:** granularita „dostatečně podrobného souhrnu" dle písm. (d) závisí na šabloně Úřadu pro AI; technická účinnost robots.txt jako výhrady u obsahu šířeného třetími stranami zůstává sporná.

#### H. Praktický závěr

Čl. 53 je základním compliance balíčkem každého poskytovatele GPAI: dvě dokumentační povinnosti (interní dle přílohy XI, navazující dle přílohy XII), autorskoprávní politika s aktivním respektováním TDM výhrad a veřejný souhrn tréninkového obsahu. Open-source výjimka je úzká a nikdy nepokrývá autorskoprávní politiku ani souhrn.

**Checklist (poskytovatel / navazující poskytovatel / advokát):**
- [ ] Ověřeno, zda model spadá pod definici GPAI a zda licence splňuje znaky odst. 2.
- [ ] Technická dokumentace dle přílohy XI vypracována a průběžně aktualizována.
- [ ] Dokumentace dle přílohy XII připravena pro navazující poskytovatele (včetně režimu důvěrnosti).
- [ ] Zavedena a dokumentována politika dodržování autorského práva včetně detekce výhrad dle čl. 4 odst. 3 DSM směrnice.
- [ ] Zveřejněn souhrn tréninkového obsahu podle šablony Úřadu pro AI; zvážena adheze ke kodexu dle čl. 56.

**Typicky rozhodné důkazy / podklady:** crawl logy a seznamy zdrojů, záznamy o respektování opt-outů, verze technické dokumentace, zveřejněný souhrn, smlouvy s navazujícími poskytovateli, korespondence s Úřadem pro AI.

---

### Čl. 54 — Zplnomocnění zástupci poskytovatelů obecných modelů AI

**Doslovné znění (EN) — Article 54 — Authorised representatives of providers of general-purpose AI models:**

> 1. Prior to placing a general-purpose AI model on the Union market, providers established in third countries shall, by written mandate, appoint an authorised representative which is established in the Union.
>
> 2. The provider shall enable its authorised representative to perform the tasks specified in the mandate received from the provider.
>
> 3. The authorised representative shall perform the tasks specified in the mandate received from the provider. It shall provide a copy of the mandate to the AI Office upon request, in one of the official languages of the institutions of the Union. For the purposes of this Regulation, the mandate shall empower the authorised representative to carry out the following tasks:
>
> (a) verify that the technical documentation specified in Annex XI has been drawn up and all obligations referred to in Article 53 and, where applicable, Article 55 have been fulfilled by the provider;
>
> (b) keep a copy of the technical documentation specified in Annex XI at the disposal of the AI Office and national competent authorities, for a period of 10 years after the general-purpose AI model has been placed on the market, and the contact details of the provider that appointed the authorised representative;
>
> (c) provide the AI Office, upon a reasoned request, with all the information and documentation, including that referred to in point (b), necessary to demonstrate compliance with the obligations in this Chapter;
>
> (d) cooperate with the AI Office and competent authorities, upon a reasoned request, in any action they take in relation to the general-purpose AI model, including when the model is integrated into AI systems placed on the market or put into service in the Union.
>
> 4. The mandate shall empower the authorised representative to be addressed, in addition to or instead of the provider, by the AI Office or the competent authorities, on all issues related to ensuring compliance with this Regulation.
>
> 5. The authorised representative shall terminate the mandate if it considers or has reason to consider the provider to be acting contrary to its obligations pursuant to this Regulation. In such a case, it shall also immediately inform the AI Office about the termination of the mandate and the reasons therefor.
>
> 6. The obligation set out in this Article shall not apply to providers of general-purpose AI models that are released under a free and open-source licence that allows for the access, usage, modification, and distribution of the model, and whose parameters, including the weights, the information on the model architecture, and the information on model usage, are made publicly available, unless the general-purpose AI models present systemic risks.
>
> SECTION 3
>
> Obligations of providers of general-purpose AI models with systemic risk

**Pracovní překlad (CZ):**

> 1. Dříve než uvedou obecný model AI na trh Unie, poskytovatelé usazení ve třetích zemích jmenují písemnou plnou mocí zplnomocněného zástupce usazeného v Unii.
>
> 2. Poskytovatel umožní svému zplnomocněnému zástupci plnit úkoly specifikované v plné moci přijaté od poskytovatele.
>
> 3. Zplnomocněný zástupce plní úkoly specifikované v plné moci přijaté od poskytovatele. Na žádost poskytne Úřadu pro AI kopii plné moci v jednom z úředních jazyků orgánů Unie. Pro účely tohoto nařízení plná moc opravňuje zplnomocněného zástupce k plnění těchto úkolů:
>
> (a) ověřit, že technická dokumentace specifikovaná v příloze XI byla vypracována a že poskytovatel splnil všechny povinnosti uvedené v článku 53 a — je-li to relevantní — v článku 55;
>
> (b) uchovávat kopii technické dokumentace specifikované v příloze XI k dispozici Úřadu pro AI a příslušným vnitrostátním orgánům po dobu deseti let od uvedení obecného modelu AI na trh a kontaktní údaje poskytovatele, který jmenoval zplnomocněného zástupce;
>
> (c) poskytnout Úřadu pro AI na základě odůvodněné žádosti veškeré informace a dokumentaci, včetně té uvedené v písmenu (b), nezbytné k prokázání souladu s povinnostmi stanovenými v této kapitole;
>
> (d) spolupracovat s Úřadem pro AI a příslušnými orgány na základě odůvodněné žádosti při veškerých opatřeních, která přijmou ve vztahu k obecnému modelu AI, včetně případů, kdy je model integrován do systémů AI uvedených na trh nebo uvedených do provozu v Unii.
>
> 4. Plná moc opravňuje zplnomocněného zástupce k tomu, aby byl vedle poskytovatele nebo namísto poskytovatele osloven Úřadem pro AI nebo příslušnými orgány ve všech věcech týkajících se zajišťování souladu s tímto nařízením.
>
> 5. Zplnomocněný zástupce vypoví plnou moc, pokud dospěje k závěru nebo má důvod se domnívat, že poskytovatel jedná v rozporu se svými povinnostmi podle tohoto nařízení. V takovém případě o výpovědi plné moci a jejích důvodech okamžitě informuje Úřad pro AI.
>
> 6. Povinnost stanovená v tomto článku se nevztahuje na poskytovatele obecných modelů AI vydaných pod licencí svobodného a otevřeného zdrojového kódu, která umožňuje přístup k modelu, jeho použití, úpravu a distribuci, a jejichž parametry, včetně vah, informací o architektuře modelu a informací o použití modelu, jsou veřejně dostupné, ledaže obecné modely AI vykazují systémová rizika.

**Výklad:** Článek 54 přenáší do oblasti GPAI mechanismus zplnomocněného zástupce dobře známý z práva výrobků (nař. (EU) 2019/1020) a z AI Act pro vysoce rizikové systémy (čl. 22). Základní ratio je stejné: pokud je poskytovatel usazen mimo Unii, musí existovat v Unii subjekt, který může být adresátem regulatorních opatření, odpovídat za soulad a být kontaktní osobou pro Úřad pro AI a vnitrostátní orgány.

Plná moc (mandát) musí být písemná a na žádost předložena v úředním jazyce Unie: tyto formální požadavky zabraňují faktickým zástupcům bez dostatečného oprávnění a zajišťují, že rozsah pověření je jednoznačně vymezen. Klíčovým prvkem je autorizace zástupce stát se náhradním adresátem (odst. 4): Úřad pro AI nebo vnitrostátní orgán může jednat přímo se zástupcem bez nutnosti komunikace s poskytovatelem v třetí zemi, čímž se výrazně zrychluje dohledová a nápravná akce.

Povinnost uchování dokumentace po dobu deseti let od uvedení modelu na trh (odst. 3 písm. b) je srovnatelná s archivační dobou pro vysoce rizikové systémy AI a reflektuje délku potenciálního regulatorního šetření nebo soudního přezkumu. Povinnost výpovědi mandátu v případě protiprávního jednání poskytovatele (odst. 5) je jedním z mála ustanovení AI Act, která vytvářejí reflexivní odpovědnostní mechanismus ve prospěch orgánů: zástupce se stává quasi-whistleblowerem, přičemž jeho odpovědnost za neplnění by jinak mohla být konstruována jako sekundární.

Výjimka pro open-source modely (odst. 6) je analogická výjimce dle čl. 53 odst. 2 — avšak s týmž zpřesněním: modely s open-source licencí, které jsou současně klasifikovány jako GPAI se systémovým rizikem, výjimku nepožívají. Tím nařízení vylučuje, aby pouhé uvolnění zdrojového kódu sloužilo jako štít před regulatorní odpovědností v případě nejvýkonnějších modelů.

#### F. Kazuistika

**1. Modelová situace.** Poskytovatel usazený v USA zpřístupní svůj obecný model AI evropským zákazníkům přes placené API, aniž předtím jmenoval zplnomocněného zástupce v Unii. Po výzvě Úřadu pro AI dodatečně pověří advokátní kancelář v Dublinu, avšak plná moc nezahrnuje oprávnění poskytovat Úřadu dokumentaci dle přílohy XI a zástupce ji nemá k dispozici. Zástupce posléze zjistí, že poskytovatel nezveřejnil souhrn tréninkového obsahu dle čl. 53 odst. 1 písm. (d). Důkazy: plná moc a její rozsah, doklady o datu prvního zpřístupnění modelu na trhu Unie, korespondence s Úřadem pro AI, kopie technické dokumentace.

**2. Právní otázka.** Jaké důsledky má uvedení obecného modelu AI na trh Unie poskytovatelem ze třetí země bez řádně zmocněného zplnomocněného zástupce a jaké povinnosti stíhají zástupce, který zjistí, že poskytovatel porušuje nařízení?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 54 odst. 1 (povinnost jmenovat zástupce před uvedením na trh), odst. 3 (povinný obsah mandátu — ověření dokumentace a souladu, archivace 10 let, součinnost), odst. 4 (zástupce jako náhradní adresát), odst. 5 (povinná výpověď mandátu a informování Úřadu), odst. 6 (open-source výjimka).
- *Související ustanovení téhož nařízení:* čl. 53 a 55 (povinnosti, jejichž plnění zástupce ověřuje), čl. 22 (paralelní úprava pro vysoce rizikové systémy), čl. 3 body 9–11 (uvedení na trh, dodání na trh, uvedení do provozu), čl. 101 (pokuty).
- *Související předpisy:* nařízení (EU) 2019/1020 (čl. 4 — hospodářský subjekt usazený v Unii jako podmínka dodávání výrobku), rozhodnutí č. 768/2008/ES (modelová architektura zplnomocněného zástupce v právu výrobků).
- *Judikatura:* k pojmu „uvedení na trh" v harmonizačním právu SDEU ustáleně dovozuje, že jde o první zpřístupnění výrobku k distribuci nebo používání v Unii v rámci obchodní činnosti; rozhodné je cílení nabídky na unijní trh, nikoli místo usazení dodavatele.

**4. Subsumpce.** Úplatné zpřístupnění modelu zákazníkům v Unii je uvedením na trh Unie; povinnost jmenovat zástupce vznikla již před tímto okamžikem — dodatečné jmenování porušení neodčiňuje, pouze ukončuje protiprávní stav. Mandát nepokrývající úkoly dle odst. 3 písm. (a)–(d) nevyhovuje: výčet je obligatorním minimálním obsahem plné moci („plná moc opravňuje zástupce k plnění těchto úkolů"). Zástupce bez kopie dokumentace neplní písm. (b). Zjištění, že poskytovatel neplní čl. 53, zakládá povinnost zástupce mandát vypovědět a neprodleně informovat Úřad pro AI s uvedením důvodů (odst. 5).

**5. Řešení.** Poskytovatel musí bezodkladně udělit úplný mandát, předat zástupci dokumentaci dle přílohy XI a kontaktní údaje a zajistit desetiletou archivaci; Úřad pro AI může jednat přímo se zástupcem (odst. 4) a porušení povinností kapitoly V postihovat pokutou dle čl. 101. Pro zástupce z toho plyne praktické pravidlo: před přijetím mandátu provést prověrku souladu poskytovatele, smluvně si zajistit přístup k dokumentaci a sjednat odškodnění — role nese kvazioznamovací povinnost vůči Úřadu a reputační rizika.

**6. Varianty.** (i) Byl-li by model uvolněn pod svobodnou a otevřenou licencí s veřejně dostupnými vahami, architekturou i informacemi o užití a nešlo by o model se systémovým rizikem, povinnost jmenovat zástupce odpadá (odst. 6). (ii) U modelu se systémovým rizikem výjimka neplatí a mandát musí pokrývat i ověření povinností dle čl. 55.

#### G. Protiargumenty a rizika

- **„Pouhá dostupnost API z Unie není uvedením na trh Unie."** Neutralizace: rozhodné je úplatné zpřístupnění v rámci obchodní činnosti cílené na unijní zákazníky (fakturace, unijní zákaznická podpora, smluvní podmínky pro EHP); čistě pasivní dostupnost bez cílení je hraniční, v modelové situaci je však cílení dáno.
- **„Zástupce neodpovídá za porušení, jichž se dopustil poskytovatel."** Správné — odpovědnost zástupce je omezena na vlastní úkoly dle mandátu; právě proto však odst. 5 konstruuje výpovědní a informační povinnost, jejíž nesplnění už je vlastním porušením zástupce.
- **Slabé místo:** vymahatelnost vůči poskytovateli zcela mimo Unii fakticky závisí na jeho zájmu o unijní trh; nařízení výslovně neřeší situaci, kdy zástupce v Unii vůbec neexistuje — faktické omezení dodávání plyne až z dozorových opatření.

#### H. Praktický závěr

Bez zplnomocněného zástupce usazeného v Unii nesmí poskytovatel ze třetí země obecný model AI na trh Unie vůbec uvést. Mandát musí pokrývat celý zákonný katalog úkolů a zástupce musí mít dokumentaci reálně k dispozici po dobu deseti let.

**Checklist (poskytovatel ze třetí země / zástupce / advokát):**
- [ ] Zástupce jmenován písemnou plnou mocí před uvedením modelu na trh Unie.
- [ ] Mandát pokrývá všechny úkoly dle odst. 3 písm. (a)–(d) a počítá s rolí náhradního adresáta (odst. 4).
- [ ] Zástupce disponuje kopií dokumentace dle přílohy XI a kontaktními údaji poskytovatele; zajištěna archivace 10 let.
- [ ] Nastaven interní postup zástupce pro případ zjištění porušení (výpověď mandátu + informování Úřadu, odst. 5).
- [ ] Posouzena použitelnost open-source výjimky (odst. 6) včetně jejího vyloučení u systémového rizika.

**Typicky rozhodné důkazy / podklady:** písemná plná moc, doklady o datu prvního zpřístupnění na trhu Unie, kopie technické dokumentace, korespondence zástupce s Úřadem pro AI.

---

**Oddíl 3 — Povinnosti poskytovatelů obecných modelů AI se systémovým rizikem**

### Čl. 55 — Povinnosti poskytovatelů obecných modelů AI se systémovým rizikem

**Doslovné znění (EN) — Article 55 — Obligations of providers of general-purpose AI models with systemic risk:**

> 1. In addition to the obligations listed in Articles 53 and 54, providers of general-purpose AI models with systemic risk shall:
>
> (a) perform model evaluation in accordance with standardised protocols and tools reflecting the state of the art, including conducting and documenting adversarial testing of the model with a view to identifying and mitigating systemic risks;
>
> (b) assess and mitigate possible systemic risks at Union level, including their sources, that may stem from the development, the placing on the market, or the use of general-purpose AI models with systemic risk;
>
> (c) keep track of, document, and report, without undue delay, to the AI Office and, as appropriate, to national competent authorities, relevant information about serious incidents and possible corrective measures to address them;
>
> (d) ensure an adequate level of cybersecurity protection for the general-purpose AI model with systemic risk and the physical infrastructure of the model.
>
> 2. Providers of general-purpose AI models with systemic risk may rely on codes of practice within the meaning of Article 56 to demonstrate compliance with the obligations set out in paragraph 1 of this Article, until a harmonised standard is published. Compliance with European harmonised standards grants providers the presumption of conformity to the extent that those standards cover those obligations. Providers of general-purpose AI models with systemic risks who do not adhere to an approved code of practice or do not comply with a European harmonised standard shall demonstrate alternative adequate means of compliance for assessment by the Commission.
>
> 3. Any information or documentation obtained pursuant to this Article, including trade secrets, shall be treated in accordance with the confidentiality obligations set out in Article 78.
>
> SECTION 4
>
> Codes of practice

**Pracovní překlad (CZ):**

> 1. Kromě povinností uvedených v článcích 53 a 54, poskytovatelé obecných modelů AI se systémovým rizikem:
>
> (a) provádějí hodnocení modelu v souladu se standardizovanými protokoly a nástroji odrážejícími stav techniky, včetně provádění a dokumentování adversariálního testování modelu s cílem identifikovat a zmírňovat systémová rizika;
>
> (b) posuzují a zmírňují možná systémová rizika na úrovni Unie, včetně jejich zdrojů, jež mohou plynout z vývoje, uvádění na trh nebo používání obecných modelů AI se systémovým rizikem;
>
> (c) sledují, dokumentují a bez zbytečného prodlení oznamují Úřadu pro AI a — je-li to vhodné — příslušným vnitrostátním orgánům příslušné informace o závažných incidentech a možných nápravných opatřeních k jejich řešení;
>
> (d) zajišťují přiměřenou úroveň kybernetické bezpečnosti obecného modelu AI se systémovým rizikem a fyzické infrastruktury modelu.
>
> 2. Poskytovatelé obecných modelů AI se systémovým rizikem se mohou při prokazování souladu s povinnostmi stanovenými v odstavci 1 tohoto článku opřít o kodexy správné praxe ve smyslu článku 56, a to do doby zveřejnění harmonizované normy. Soulad s evropskými harmonizovanými normami zakládá pro poskytovatele presumpci shody v rozsahu, v jakém tyto normy pokrývají příslušné povinnosti. Poskytovatelé obecných modelů AI se systémovými riziky, kteří nepřistoupí ke schválenému kodexu správné praxe nebo nesplňují evropskou harmonizovanou normu, musí Komisi prokázat alternativní přiměřené prostředky zajištění souladu.
>
> 3. Veškeré informace nebo dokumentace získané podle tohoto článku, včetně obchodních tajemství, se zpracovávají v souladu s povinnostmi mlčenlivosti stanovenými v článku 78.

**Výklad:** Článek 55 představuje jádro zpřísněného regulačního režimu pro obecné modely AI se systémovým rizikem a doplňuje základní povinnosti čl. 53 a 54 o čtyři specifické povinnosti adresující nejvýznamnější rizika plynoucí z nasazení nejschopnějších modelů.

Povinnost hodnocení modelu (odst. 1 písm. a) prostřednictvím adversariálního testování (*red-teaming*) je normou procesní a metodologické kvality: nařízení nevyžaduje konkrétní výsledky testů, nýbrž provedení testů v souladu s „protokoly a nástroji odrážejícími stav techniky". Tím se otevírá prostor pro normalizaci a standardizaci, již rozvíjí zejména NIST AI RMF a iniciativy Frontier Model Forum, jež ovlivňují i kodexy správné praxe dle čl. 56. Dokumentace testů musí prokazovat systematičnost — ad hoc testování bez záznamu o metodologii nepostačuje.

Povinnost posuzování a zmírňování systémových rizik (odst. 1 písm. b) je kontinuální: nevztahuje se jen na okamžik uvedení modelu na trh, ale trvá po celou dobu jeho dostupnosti. Zdrojem systémového rizika mohou být jak vlastnosti samotného modelu (schopnost generovat instrukce k výrobě chemických zbraní, rozsáhlá dezinformační kapacita), tak způsob jeho nasazení v hodnotovém řetězci (agregace rizik přes množství navazujících aplikací). Pojem „systémové riziko na úrovni Unie" je autonomní konceptem nařízení; příloha XIII poskytuje orientační výčet kritérií, avšak posouzení musí být provedeno pro konkrétní model a konkrétní kontext.

Oznamovací povinnost závažných incidentů (odst. 1 písm. c) je konstruována jako lhůtně neurčená povinnost „bez zbytečného prodlení", analogická oznamování incidentů dle směrnice NIS2 nebo DORA. Podrobnější pravidla o tom, co se považuje za závažný incident a v jaké formě má být oznámení podáno, budou pravděpodobně součástí kódexů správné praxe (čl. 56). Paralelní oznamovací povinnost vůči vnitrostátním orgánům (je-li to vhodné) odráží skutečnost, že dopad incidentu může být primárně lokalizován v konkrétním členském státě.

Povinnost kybernetické bezpečnosti (odst. 1 písm. d) je technologicky neutrálně formulována a zahrnuje jak ochranu samotného modelu (váh, parametrů, API), tak fyzické infrastruktury datových center. Odkaz na „přiměřenou úroveň" dává prostor pro proporcionální přístup — nicméně u modelů tréninkem na 10^25 FLOPs bude standard požadované ochrany vysoký. V kontextu narůstajících geopolitických rizik (model jako strategický prostředek státní moci) jde o jednu z nejprakticky naléhavějších povinností celé kapitoly V.

#### F. Kazuistika

**1. Modelová situace.** Poskytovatel obecného modelu AI klasifikovaného jako model se systémovým rizikem zaznamená kompromitaci interní infrastruktury, při níž útočník exfiltruje část vah modelu; krátce nato nezávislí výzkumníci zveřejní jailbreak umožňující z modelu získávat návody ke zvýšení nebezpečnosti biologických agens. Poskytovatel incident interně vyšetřuje, Úřadu pro AI jej však oznámí až po šesti týdnech. Adversariální testování před uvedením modelu na trh sice proběhlo, ale bez záznamu metodologie a výsledků. Důkazy: forenzní zpráva o průniku, časová osa detekce a oznámení, protokoly red-teamingu (resp. jejich absence), dokumentace bezpečnostních opatření chránících váhy.

**2. Právní otázka.** Splnil poskytovatel povinnosti dle čl. 55 odst. 1 písm. (a), (c) a (d) — tj. dokumentované adversariální testování, oznámení závažného incidentu „bez zbytečného prodlení" a přiměřenou kybernetickou ochranu modelu a jeho infrastruktury?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 55 odst. 1 písm. (a) (hodnocení modelu dle stavu techniky včetně dokumentovaného adversariálního testování), písm. (b) (kontinuální posuzování a zmírňování systémových rizik), písm. (c) (evidence a oznamování závažných incidentů), písm. (d) (kybernetická bezpečnost modelu i fyzické infrastruktury); odst. 2 (kodexy a presumpce shody).
- *Související ustanovení téhož nařízení:* čl. 51–52 (klasifikace), čl. 53–54 (základní povinnosti), čl. 3 bod 49 (definice závažného incidentu u systémů AI — výkladové vodítko), čl. 73 (paralelní incidentní režim u vysoce rizikových systémů), čl. 78 (mlčenlivost), čl. 101 (pokuty až 3 % celosvětového ročního obratu nebo 15 000 000 EUR).
- *Související předpisy:* směrnice (EU) 2022/2555 (NIS2 — včasné varování do 24 hodin a hlášení do 72 hodin jako srovnávací standard rychlosti), nařízení (EU) 2022/2554 (DORA); kodex správné praxe pro GPAI dle čl. 56 (kapitola bezpečnosti a zabezpečení).
- *Judikatura:* k výkladu „bez zbytečného odkladu/prodlení" srov. rozhodovací praxi Nejvyššího soudu ČR (např. sp. zn. 32 Cdo 2484/2012): jde o lhůtu v řádu dnů, jejíž delší čerpání musí být objektivně ospravedlněno povahou věci.

**4. Subsumpce.** Exfiltrace vah modelu se systémovým rizikem je závažným incidentem: umožňuje obejití bezpečnostních zábran a nekontrolovanou proliferaci schopností, jež byly důvodem klasifikace; jailbreak umožňující CBRN výstupy je materializací systémového rizika dle písm. (b). Šestitýdenní prodleva zjevně překračuje standard „bez zbytečného prodlení" — interní vyšetřování oznámení neodkládá, lze je podat předběžně a průběžně doplňovat. Nedokumentovaný red-teaming nesplňuje písm. (a): povinnost zahrnuje provedení i zdokumentování testů dle standardizovaných protokolů. U písm. (d) naopak platí, že úspěšný útok sám o sobě porušení nezakládá — měřítkem je přiměřenost opatření vzhledem ke stavu techniky, nikoli absolutní neprolomitelnost; rozhodné bude, zda ochrana vah odpovídala uznávaným standardům (segmentace, řízení přístupu, monitoring).

**5. Řešení.** Poskytovatel musí incident neprodleně (byť dodatečně) oznámit Úřadu pro AI včetně přijatých nápravných opatření (rotace přístupů, posílení zábran, součinnost při omezování šíření uniklých vah), doplnit dokumentaci testování a aktualizovat posouzení systémových rizik. Souběžně je třeba vyhodnotit oznamovací povinnosti dle NIS2/DORA a GDPR (byly-li dotčeny osobní údaje). Hrozí pokuta dle čl. 101; doložené plnění závazků kodexu správné praxe je nejúčinnější cestou, jak prokázat náležitou péči.

**6. Varianty.** (i) Šlo-li by o neúspěšný pokus o průnik bez úniku a dopadu, práh závažného incidentu zpravidla dosažen není — interní evidence dle písm. (c) je však namístě. (ii) Plnil-li by poskytovatel dokumentované protokoly schváleného kodexu (odst. 2), svědčil by mu silný důkaz řádného plnění písm. (a) a (b) a posouzení by dopadlo odlišně.

#### G. Protiargumenty a rizika

- **„Pojem závažného incidentu není pro GPAI definován, sankce za pozdní oznámení je proto nepřípustná."** Neutralizace: obsah pojmu lze určit výkladem z čl. 3 bodu 49 mutatis mutandis, z účelu kapitoly V a z kodexu správné praxe; zásada určitosti velí postupovat zdrženlivě u hraničních případů — exfiltrace vah však hraniční není.
- **„Útok provedl vysoce sofistikovaný (státem podporovaný) aktér, žádná přiměřená ochrana by neobstála."** Částečně relevantní: písm. (d) požaduje přiměřenost, nikoli absolutní bezpečnost; u modelů se systémovým rizikem je však očekávaný standard mimořádně vysoký a důkazní břemeno náležité péče nese poskytovatel.
- **Slabé místo:** vztah písm. (c) k čl. 73 (dva paralelní incidentní režimy s odlišnými adresáty) a absence prováděcích lhůt; do ustálení praxe hrozí jak podhlašování, tak duplicitní hlášení.

#### H. Praktický závěr

Čl. 55 vyžaduje od poskytovatelů modelů se systémovým rizikem živý, dokumentovaný bezpečnostní systém: red-teaming dle stavu techniky se záznamem metodologie, průběžné řízení systémových rizik, incident-response proces s okamžitou notifikací Úřadu pro AI a kybernetickou ochranu vah i infrastruktury.

**Checklist (poskytovatel / advokát / Úřad pro AI):**
- [ ] Zaveden dokumentovaný program hodnocení a adversariálního testování modelu (protokoly, výsledky, mitigace).
- [ ] Průběžné posuzování systémových rizik na úrovni Unie včetně jejich zdrojů a hodnotového řetězce.
- [ ] Incident-response plán s interními lhůtami pro oznámení Úřadu pro AI „bez zbytečného prodlení".
- [ ] Kybernetická ochrana vah, API a fyzické infrastruktury odpovídající stavu techniky; pravidelné audity.
- [ ] Zvážena adheze ke kodexu správné praxe (odst. 2) jako nástroj prokazování souladu.

**Typicky rozhodné důkazy / podklady:** protokoly red-teamingu, registr rizik, forenzní zprávy, časové osy detekce a oznámení incidentů, bezpečnostní politiky a audity, záznamy o plnění kodexu.

---

**Oddíl 4 — Kodexy správné praxe**

### Čl. 56 — Kodexy správné praxe

**Doslovné znění (EN) — Article 56 — Codes of practice:**

> 1. The AI Office shall encourage and facilitate the drawing up of codes of practice at Union level in order to contribute to the proper application of this Regulation, taking into account international approaches.
>
> 2. The AI Office and the Board shall aim to ensure that the codes of practice cover at least the obligations provided for in Articles 53 and 55, including the following issues:
>
> (a) the means to ensure that the information referred to in Article 53(1), points (a) and (b), is kept up to date in light of market and technological developments;
>
> (b) the adequate level of detail for the summary about the content used for training;
>
> (c) the identification of the type and nature of the systemic risks at Union level, including their sources, where appropriate;
>
> (d) the measures, procedures and modalities for the assessment and management of the systemic risks at Union level, including the documentation thereof, which shall be proportionate to the risks, take into consideration their severity and probability and take into account the specific challenges of tackling those risks in light of the possible ways in which such risks may emerge and materialise along the AI value chain.
>
> 3. The AI Office may invite all providers of general-purpose AI models, as well as relevant national competent authorities, to participate in the drawing-up of codes of practice. Civil society organisations, industry, academia and other relevant stakeholders, such as downstream providers and independent experts, may support the process.
>
> 4. The AI Office and the Board shall aim to ensure that the codes of practice clearly set out their specific objectives and contain commitments or measures, including key performance indicators as appropriate, to ensure the achievement of those objectives, and that they take due account of the needs and interests of all interested parties, including affected persons, at Union level.
>
> 5. The AI Office shall aim to ensure that participants to the codes of practice report regularly to the AI Office on the implementation of the commitments and the measures taken and their outcomes, including as measured against the key performance indicators as appropriate. Key performance indicators and reporting commitments shall reflect differences in size and capacity between various participants.
>
> 6. The AI Office and the Board shall regularly monitor and evaluate the achievement of the objectives of the codes of practice by the participants and their contribution to the proper application of this Regulation. The AI Office and the Board shall assess whether the codes of practice cover the obligations provided for in Articles 53 and 55, and shall regularly monitor and evaluate the achievement of their objectives. They shall publish their assessment of the adequacy of the codes of practice.
>
> The Commission may, by way of an implementing act, approve a code of practice and give it a general validity within the Union. That implementing act shall be adopted in accordance with the examination procedure referred to in Article 98(2).
>
> 7. The AI Office may invite all providers of general-purpose AI models to adhere to the codes of practice. For providers of general-purpose AI models not presenting systemic risks this adherence may be limited to the obligations provided for in Article 53, unless they declare explicitly their interest to join the full code.
>
> 8. The AI Office shall, as appropriate, also encourage and facilitate the review and adaptation of the codes of practice, in particular in light of emerging standards. The AI Office shall assist in the assessment of available standards.
>
> 9. Codes of practice shall be ready at the latest by 2 May 2025. The AI Office shall take the necessary steps, including inviting providers pursuant to paragraph 7.
>
> If, by 2 August 2025, a code of practice cannot be finalised, or if the AI Office deems it is not adequate following its assessment under paragraph 6 of this Article, the Commission may provide, by means of implementing acts, common rules for the implementation of the obligations provided for in Articles 53 and 55, including the issues set out in paragraph 2 of this Article. Those implementing acts shall be adopted in accordance with the examination procedure referred to in Article 98(2).

**Pracovní překlad (CZ):**

> 1. Úřad pro AI podněcuje a usnadňuje vypracování kodexů správné praxe na úrovni Unie s cílem přispět k řádnému uplatňování tohoto nařízení s přihlédnutím k mezinárodním přístupům.
>
> 2. Úřad pro AI a sbor usilují o to, aby kodexy správné praxe pokrývaly alespoň povinnosti stanovené v článcích 53 a 55, včetně těchto otázek:
>
> (a) prostředky zajišťující, aby informace uvedené v čl. 53 odst. 1 písm. (a) a (b) byly průběžně aktualizovány s ohledem na vývoj trhu a technologií;
>
> (b) přiměřenou úroveň podrobnosti souhrnu o obsahu použitém pro trénink;
>
> (c) identifikaci druhu a povahy systémových rizik na úrovni Unie, včetně jejich zdrojů, je-li to vhodné;
>
> (d) opatření, postupy a modality pro posuzování a řízení systémových rizik na úrovni Unie, včetně jejich dokumentace, jež musí být přiměřené rizikům, přihlížet k jejich závažnosti a pravděpodobnosti a brát v úvahu specifické výzvy spojené s jejich řešením s ohledem na možné způsoby, jakými taková rizika mohou vzniknout a projevit se podél hodnotového řetězce AI.
>
> 3. Úřad pro AI může vyzvat všechny poskytovatele obecných modelů AI, jakož i příslušné vnitrostátní příslušné orgány, k účasti na vypracování kodexů správné praxe. Organizace občanské společnosti, průmysl, akademická obec a další příslušné zúčastněné strany, jako jsou navazující poskytovatelé a nezávislí odborníci, mohou daný proces podporovat.
>
> 4. Úřad pro AI a sbor usilují o to, aby kodexy správné praxe jasně vymezily své konkrétní cíle a obsahovaly závazky nebo opatření, včetně klíčových ukazatelů výkonnosti, je-li to vhodné, k zajištění dosažení těchto cílů, a aby náležitě zohledňovaly potřeby a zájmy všech zainteresovaných stran, včetně dotčených osob, na úrovni Unie.
>
> 5. Úřad pro AI usiluje o to, aby účastníci kodexů správné praxe pravidelně podávali Úřadu pro AI zprávy o plnění závazků, přijatých opatřeních a jejich výsledcích, a to i v porovnání s klíčovými ukazateli výkonnosti, je-li to vhodné. Klíčové ukazatele výkonnosti a zpravodajské závazky musí odrážet rozdíly ve velikosti a kapacitě různých účastníků.
>
> 6. Úřad pro AI a sbor pravidelně sledují a hodnotí, nakolik účastníci dosahují cílů kodexů správné praxe a jak přispívají k řádnému uplatňování tohoto nařízení. Úřad pro AI a sbor posuzují, zda kodexy správné praxe pokrývají povinnosti stanovené v článcích 53 a 55, a pravidelně sledují a hodnotí dosahování jejich cílů. Zveřejní své posouzení přiměřenosti kodexů správné praxe.
>
> Komise může prostřednictvím prováděcího aktu schválit kodex správné praxe a přiznat mu obecnou závaznost v Unii. Tento prováděcí akt se přijme v souladu s přezkumným postupem uvedeným v čl. 98 odst. 2.
>
> 7. Úřad pro AI může vyzvat všechny poskytovatele obecných modelů AI k přistoupení ke kodexům správné praxe. U poskytovatelů obecných modelů AI, kteří nevykazují systémová rizika, může být toto přistoupení omezeno na povinnosti stanovené v článku 53, ledaže výslovně projeví zájem přistoupit k úplnému kodexu.
>
> 8. Úřad pro AI také podněcuje a usnadňuje přezkum a přizpůsobení kodexů správné praxe, zejména s ohledem na vznikající normy. Úřad pro AI napomáhá posuzování dostupných norem.
>
> 9. Kodexy správné praxe jsou připraveny nejpozději do 2. května 2025. Úřad pro AI přijme nezbytná opatření, včetně výzev poskytovatelům podle odstavce 7.
>
> Pokud nelze kodex správné praxe dokončit do 2. srpna 2025 nebo pokud Úřad pro AI po svém posouzení podle odstavce 6 tohoto článku dospěje k závěru, že není přiměřený, může Komise prostřednictvím prováděcích aktů stanovit společná pravidla pro plnění povinností stanovených v článcích 53 a 55, včetně otázek uvedených v odstavci 2 tohoto článku. Tyto prováděcí akty se přijmou v souladu s přezkumným postupem uvedeným v čl. 98 odst. 2.

**Výklad:** Článek 56 zakotvuje kodexy správné praxe jako klíčový nástroj ko-regulace v oblasti obecných modelů AI — mechanismus, který kombinuje samoregulační závazky soukromého sektoru s veřejnou autoritou Úřadu pro AI a Komise. Kodex správné praxe tvoří most mezi abstraktními normativními požadavky čl. 53 a 55 a konkrétní operacionalizací v praxi: definuje, co „odpovídající" dokumentace nebo „přiměřená" ochrana před systémovými riziky v daném technologickém kontextu znamená.

Institucionální architektura procesu je vícestupňová: iniciátor a facilitátor je Úřad pro AI (čl. 64), věcné ukotvení poskytuje sbor (čl. 65), přičemž participace je otevřená — do procesu jsou zvány vnitrostátní orgány, průmysl, akademická obec, organizace občanské společnosti i navazující poskytovatelé. Tato inkluzivní metodologie odpovídá modelu kodexů správné praxe dle DSA (čl. 45 nař. (EU) 2022/2065), od nichž si AI Act přebírá inspiraci; zároveň je však odlišná v tom, že AI Act spojuje kodexy s presumpcí souladu — přistoupení ke schválenému kodexu je alternativní cestou k prokázání souladu vedle harmonizovaných norem.

Schválení kodexu Komisí prostřednictvím prováděcího aktu (odst. 6 druhý pododstavec) mu přiznává „obecnou závaznost" v Unii — v praxi jde o kvalitativně vyšší stupeň právní relevance než u nezávazného kodexu; schválený kodex se stává referenčním rámcem pro dohledová posouzení Úřadu pro AI i pro vnitrostátní orgány. Nepřistoupení ke schválenému kodexu není samo o sobě porušením nařízení, avšak poskytovatel musí prokázat alternativní přiměřené prostředky souladu, což je důkazní břemeno, které v praxi může být obtížné splnit.

Záložní pravomoc Komise přijmout prováděcí akty se společnými pravidly (odst. 9 druhý pododstavec) je „stick" k „carrot" kodexů: pokud proces samoregulace selže nebo výsledný kodex bude shledán nepřiměřeným, Komise převezme iniciativu a vydá závazná pravidla. Termín 2. května 2025 pro první kodexy a záchranná lhůta do 2. srpna 2025 jsou procesními zárukami, které zajišťují, že právní vakuum nebude trvat déle, než je nezbytné. Flexibilní ukazatele výkonnosti a diferenciace dle velikosti a kapacity účastníků (odst. 5) jsou odrazem principu proporcionality a zásady, že stejné materiální požadavky nemohou být identicky nákladné pro globálního technologického giganta a pro středoevropský výzkumný ústav.

#### F. Kazuistika

**1. Modelová situace.** Středně velký evropský poskytovatel obecného modelu AI (bez systémového rizika) se rozhoduje, zda přistoupí ke kodexu správné praxe pro obecné modely AI vypracovanému pod vedením Úřadu pro AI. Adhezi odmítne s tím, že soulad s čl. 53 zajistí vlastními interními směrnicemi. Úřad pro AI jej následně vyzve, aby prokázal „alternativní přiměřené prostředky souladu"; poskytovatel předloží obecně formulovanou interní politiku bez měřitelných opatření. Důkazy: znění kodexu a posouzení jeho přiměřenosti, interní směrnice poskytovatele, mapování povinností čl. 53 na konkrétní opatření, korespondence s Úřadem.

**2. Právní otázka.** Jaké právní důsledky má pro poskytovatele obecného modelu AI nepřistoupení ke kodexu správné praxe — zejména jaké důkazní břemeno nese při prokazování alternativních přiměřených prostředků souladu dle čl. 53 odst. 4 (resp. čl. 55 odst. 2)?

**3. Použitelné právo.**
- *Komentované ustanovení:* čl. 56 odst. 1–9 (vypracování kodexů pod vedením Úřadu pro AI, minimální obsah, participace, klíčové ukazatele výkonnosti, posuzování přiměřenosti, schválení prováděcím aktem, lhůty 2. 5. 2025 / 2. 8. 2025 a záložní pravomoc Komise).
- *Související ustanovení téhož nařízení:* čl. 53 odst. 4 a čl. 55 odst. 2 (adheze jako prostředek prokazování souladu do vydání harmonizovaných norem), čl. 50 odst. 7 (samostatné kodexy pro označování obsahu), čl. 64–65 (Úřad pro AI a sbor), čl. 98 odst. 2 (přezkumný postup), čl. 101 (pokuty).
- *Související předpisy:* nařízení (EU) č. 1025/2012 (harmonizované normy); čl. 45 nařízení (EU) 2022/2065 (DSA — inspirační model kodexů chování); čl. 291 SFEU (prováděcí akty).
- *Judikatura:* SDEU, James Elliott Construction (C-613/14): harmonizované normy jsou pro své právní účinky součástí práva EU a podléhají výkladové pravomoci SDEU — závěr přenositelný na kodexy, jimž Komise prováděcím aktem přizná obecnou závaznost.

**4. Subsumpce.** Poskytovatel bez systémového rizika může adhezi omezit na povinnosti čl. 53 (odst. 7). Nepřistoupení není porušením nařízení; aktivuje však povinnost prokázat Komisi alternativní přiměřené prostředky souladu. Obecná interní politika bez konkrétních, ověřitelných opatření (režim aktualizace dokumentace, podoba souhrnu tréninkového obsahu, autorskoprávní politika) tomuto standardu nedostojí — alternativa musí věcně pokrýt tytéž oblasti jako kodex (odst. 2 písm. (a)–(d)) a být doložitelná. Sporná zůstává intenzita přezkumu Komise; z konstrukce „prokázat … k posouzení Komisí" však plyne aktivní důkazní břemeno poskytovatele.

**5. Řešení.** Pro většinu poskytovatelů je adheze ke kodexu racionální volbou: snižuje důkazní břemeno, vytváří fakticky bezpečný přístav v dohledové praxi a do vydání harmonizovaných norem je jediným standardizovaným prokazovacím nástrojem. Zvolí-li poskytovatel alternativní cestu, musí vypracovat mapovací dokumentaci (povinnost → opatření → důkaz), průběžně ji aktualizovat a počítat s přísným posouzením. Pravděpodobný výsledek modelové situace: Úřad shledá předloženou politiku nedostatečnou a poskytovatel bude muset opatření doplnit, jinak riskuje postup dle čl. 101.

**6. Varianty.** (i) Schválí-li Komise kodex prováděcím aktem s obecnou platností (odst. 6), stane se referenčním rámcem dohledu — i nepřistoupivší poskytovatel bude fakticky poměřován jeho obsahem. (ii) Nebyl-li by kodex včas dokončen nebo byl shledán nepřiměřeným, stanoví Komise společná pravidla prováděcím aktem (odst. 9) — prostor pro alternativní prostředky se podstatně zúží, neboť pravidla budou závazná erga omnes.

#### G. Protiargumenty a rizika

- **„Kodex je dobrovolné soft law; jeho nedodržení nemůže mít právní následky."** Formálně správné, materiálně zavádějící: čl. 53 odst. 4 a čl. 55 odst. 2 přesouvají na neadherujícího poskytovatele důkazní břemeno alternativního souladu — kodex tak působí jako fakticky vynucený standard („carrot and stick").
- **„Tvorbu kodexu ovládnou největší poskytovatelé (regulatory capture) a obsah nebude přiměřený menším hráčům."** Neutralizace: odst. 3 zajišťuje inkluzivní participaci a odst. 5 výslovně přikazuje diferencovat ukazatele výkonnosti a reporting dle velikosti a kapacity účastníků; riziko však zcela vyloučit nelze.
- **Slabé místo:** soudní přezkoumatelnost posouzení přiměřenosti kodexu a přechod mezi kodexem a pozdějšími harmonizovanými normami (okamžik zániku prokazovací funkce kodexu) nejsou výslovně upraveny.

#### H. Praktický závěr

Kodexy správné praxe jsou v období do vydání harmonizovaných norem ústředním nástrojem prokazování souladu s čl. 53 a 55. Adheze je dobrovolná, ale prakticky výhodná; alternativní cesta vyžaduje plnohodnotnou, dokumentovanou náhradu posuzovanou Komisí.

**Checklist (poskytovatel GPAI / advokát):**
- [ ] Přijato a zdokumentováno rozhodnutí o adhezi ke kodexu (včetně rozsahu — jen čl. 53, či plný kodex).
- [ ] Provedena gap analýza povinností čl. 53/55 vůči závazkům kodexu.
- [ ] Při neadhezi vypracována mapovací dokumentace alternativních prostředků souladu pro posouzení Komisí.
- [ ] Nastaven pravidelný reporting Úřadu pro AI včetně klíčových ukazatelů výkonnosti (odst. 5).
- [ ] Sledovány revize kodexu, posouzení jeho přiměřenosti a nástup harmonizovaných norem (odst. 6 a 8).

**Typicky rozhodné důkazy / podklady:** prohlášení o adhezi, zprávy o plnění závazků a ukazatelů výkonnosti, gap analýza, mapovací dokumentace alternativního souladu, korespondence s Úřadem pro AI.

---
