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

---
