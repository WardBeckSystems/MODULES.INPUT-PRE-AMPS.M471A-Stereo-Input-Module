# M471A Stereo Input Module · Input Pre Amps

Ward-Beck Systems M471A, 1978|11. Wiki page: [M471A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M471A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 24 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 20 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 170 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 2 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 11 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 28 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [2 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1985 - M471A - P003 - 1-1.jpg](MANUALS/1985%20-%20M471A%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivity** | dBm (ref. 600 ohm source} |
| **Frequency response** | +/-0.25 dB from Signal |
| **Noise ratio** | 83 dB. below +10 dBm. |
| **Harmonic distortion** | Less than 25% THD from 20 kHz +28 dBm output Less than kHz outpul Hz less +28 dBm |
| **Source impedance** | 600 ohms balanced. |
| **Input impedance** | 500 ohms |
| **Output impedance** | Less than 100 ohms (at outputs amplifiers only) 8-109B |
| **Load impedance** | 600 ohms balanced |
| **Output level** | dBm nominal +30 dBm maximum (at outputs 8-109B amplifiers only) |
| **Phasing** | Input and output terminals designated Dy numbers are phase |
| **Power requirements** | +/-25 volts dc, MA maximum. |
| **Ambient temperature** | Dimensions: degrees Celsius wide high 6.5&quot; deep (41 Mm 178 Mm 165 mm } |

## Circuit description

From [1985 - M471A - Stereo Input Module (2).pdf](MANUALS/1985%20-%20M471A%20-%20Stereo%20Input%20Module%20(2).pdf) pages 4-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

M4?lA STEREO INPUT MODULE

The M4 7 1A St......o Input Module i s designed to ace..pt s t e..eo line l eve 1 SOu &quot; Ce s. The unit p..ne.. s ses th.. inputs i g na las r-e Qu i....d and rout.. sit to th.. app..op.. iate points within the mixing console system.

The input s..ct ion consists of the CHANNEL ON switch SW3, and the PHASE REVERSALs witch SW2, which.. ff.. cts only the.. ight inputs i g nal path. The channel ON condition is ind i cat..d by the ill u min a t ion oft h e CH ON switch pu shbu llOn when d ep&quot;essed, and sim ila.. l y the phase.. eve.. sed condition is indicated by t h.. Ill u min a ti on oft h e LED, DS I, located adjacent to SW2.

FOllowing SW3, the signal i s brought out o f the module via edge connector pins 10, Land 11, M fo.. connection tot he inputs of a balanced s te r-eo fade r. The outputs oft h e fade.. are &quot; e turned to the module On pins 12, N and 13, P fo.. left and.. ight signals.. esp ectiv e ly. The inputs ide of the fade r also Se..v eS a s the pickup point fo.. the dual operational amplifier Z I which combines the left and right input signals and d.. ives the module internal p ref a d e bus. This bus i s also brought out to edge cc n n ecto rp ins Rand 14 fo.. fur the r assignment a&quot;..e Clu i..e d.

8 _ 109 B BOOSTER AMPLIFIER

The 8-10 9B Booster Amplifier operates with again of 18 dB and recover s the loss incu....ed when the fade.. isp laced i nits normal 15 dB &quot;in h and&quot; posit ion. Thee x t.. a 3 d B o f gain i s used too v e rcom e the 3 dB loss oft h e balance p o ten tiomete..&quot; at t h ei.. mid _p o s i ti o nth e..eb y maintaining the 0 dBm output levels.

BALANCE AND MAIN OUTPUTS

The outputs i gn a l of the 8 _ 10 98 amplif le.. is used to feed both left and right main outputs via the BALANCE &quot; witch SW7 and ganged BALANCE control RS through R8. I t alsop..ovides the feed fo.. dual

operational amp l i fie r Z 2, which combines the left and right output

signals and d &quot;;v est he module i nte..n alpo s tf &quot; d e bus. This bus is ·

brought out toed g e connector pins U and 17 fo.. add i t io na lass i g n

men t as..equi.. ed.

**M47 1A STEREO INPUT MODULE**

PRE/ POST SELECTOR SWITCHES AND LEVEL CONTROLS

Sw ilCh SWg aCI,. a,. Ihe p.. e/pOll I &quot;1e&lt;;: 10.. for I he AUX I OUlpUI. w i l h ganged pOlenl iom eter RJ/ R4 eee r al'ng..,. I h e AUX, ' ev elm i&quot;, CO'&quot;I&quot;OI. SWB I s I hep..../ POSI seleclor lor theA UX 2 OUIPul. with g&quot;nged potenllome I.... R ' / R2 us~ &quot; S I he AUX 2 lev.. l m i &quot; contl&quot;Ol.

Momen l.... y s wi l c h SW10 enables Ih e PFL outpu l slgn,,1 which is de r lved d l.. ec lly from Ihe module i n le.. n~1I p..eteee bus. This switCh alsop..ovl de san.. &quot;I..a set of con laC lS fo.. a PFL dc con l..o l wh l ch can be used 10 aCl iv ale e &quot; I er-n&quot; I.... lays, lamps, eiC.

POWER SUPPLY DECOUPLiN G

An aClive powe.. supply d ecoup ling net wo.. k consisting of 0 1 I h l&quot;Ou gh 06 p..ovid.. s.. hlgh de g.. eeo f I Sol a l lon belwe en I h e M47 1A and t h.. +/ _25 volt supply.. ails. Trans l sto.. s as and 06 se r-ve a s cu....en l monl to.. Sand will l lmil Ihe cu....en l flowing Ihl&quot;O ugh I h e se.. les pass t.. a n s l sto.. s 03 and 04 In the even I t h.. t e&quot;,ce ss ive p Ow.... supply d.... a nds should a,. i seas a.... su l l of component f.. ll u..e.

WAR C · S ECI&lt;. SYSTEMS LT C.

**MFG PART NUMBER**

C&gt; Capacitor-22 uF /25 V PI'l:,liPS.26ETF22 C2 22 uF /25 V CJ 22 uF/2~ V C' 22 uF /25 V

C, delete C7 delete C' delete C, Capacitor-68u F/ 10V TJ9OO686M0 10,&quot;,S COO 33 uF/ lO V T39OO336M010,&quot;,S

CO&gt; 68 uF/ l 0V TJ900 686M 0 10AS CO2 33u F/ IOV T3900 336M0 10&quot;&quot;S CO2 68 uF/ I O V T3900686M010....S C&quot; 33u F/l0V T3900336M0 10....S cis 68 uF / l 0 V T3900686M0 10&quot;&quot;S

33 uF /l 0 V

CR' Diode on IN. OO3

0&quot; L;O, R.o Fain:l'lild FLV 117 052 on ZFL-LEO-R

0' Tr-an \li,UorNational PN3569 02 PN3645 OJ TIP296 O' TlPXlB 0' National PNl569 0' PN3645

Rn Potentiomet er-. dual 0/ 8

**&quot;,1I.71A. STEREO INPUT MODULE**

'S) Potent iometer, qued AlB

., ReSistor 1/ II.W sl

R I S to

.., Resistor l /II. W si,2&lt;

delete Resistor l /II. W&quot;SI

m 33.

'53 33.

'59 33&quot;

**.OO 390**

es 390

.63 390

• OO rs•

eo, R es i,~tor l j4W&quot; 5%:;~ Phil; p s

deleted e le te

d e ie te

delete &quot;, Resistor 1! 4W 5%

**3W 5%**

SWI delete

SW2 Switch WBS 11_002 swa was 11_157 S&quot;, was 11-002

SW10 WBS 11_003

**MFG PART NUMBER**

8P inOipSock et

WBS recommends the use of replacement parts made by the specified

manufacturers for continued optimum equip men t performance.

**8 · 10 9 AMPLIFIER SERIES**

The 8 -10 9 series of amplifiers are util t zed as an internal component within various WBS series of audio console modules. Each 8-109 amplifier mounts as a plu9-fn assembly onto the module motherboard.

The 8-109 ampI ifier provfdes ana c t t vel y balanced output with a +30 dBm capability. It is employed as an output ora booster amplifier with either a balanced oran unbalanced 1nput.

The following specifications apply tot he 8-109 series of amplifiers.

Unit ~ 8-109 Balanced 15 dB 8-t09A Unbel anced 7 dB 8-1098 Balanced 18 dB 8-10ge Balanced 39 dB 8-1090 Unbalanced 29 dB 8-109E aaj aecec 29 dB 8-109F set ancee 33 dB 8-109G aal a oc e e 23 dB Frequency Response: ±0.2 dB from 20 Hz to 20 kHz. Noise: -108 dBm EIN from 20 Hz to 20 ktl z. Harmon1c p t s tort ton: less than 0.11 THD from 20 Hz to 20 kHz a t +30 dBm output Ltyp t calf y less than 0.02 Sat mfd-ba nd).

Source Impedance: 600 ohms or less, balanced or unbalanced. Input Impedances: Models with balanced t np u t: 5k ohms minimum.

8-l09A: 30k ohms.

8-1090: 4700 ohms.

p s.

Input levels: Oepend in9 on gain of particular model

and system cper-a t f nq levels. (Refer toga inspect t t c e t t cns above. ]

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYnBnNW42Z1JsR1E/view?resourcekey=0-OfHs_GY5t3Nx2MV7ngk_cA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYnBnNW42Z1JsR1E&resourcekey=0-OfHs_GY5t3Nx2MV7ngk_cA" width="240" alt="1985 - M471A - 471-04-006 - STEREO INPUT MODULE.jpg"></a><br><sub>1985|18 · 471-04-006 - STEREO INPUT MODULE · <a href="MECHANICAL/1985%20-%20M471A%20-%20471-04-006%20-%20STEREO%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaHphdVoxa2oyWGc/view?resourcekey=0-slZANKRVrgnw6v21tCWzdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaHphdVoxa2oyWGc&resourcekey=0-slZANKRVrgnw6v21tCWzdQ" width="240" alt="1985 - M471A - 471-04-007 - STEREO INPUT MODULE.jpg"></a><br><sub>1985|18 · 471-04-007 - STEREO INPUT MODULE · <a href="MECHANICAL/1985%20-%20M471A%20-%20471-04-007%20-%20STEREO%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZlI2M2ZEZnR3aFE/view?resourcekey=0-SEcbx0TDlUDlKntZVfArQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZlI2M2ZEZnR3aFE&resourcekey=0-SEcbx0TDlUDlKntZVfArQg" width="240" alt="1985 - M471A - 471-04-008 - ENG STEREO INPUT MODULE.jpg"></a><br><sub>1985|18 · 471-04-008 - ENG STEREO INPUT MODULE · <a href="MECHANICAL/1985%20-%20M471A%20-%20471-04-008%20-%20ENG%20STEREO%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1Kt3Oqf1Oet8lFtpRtUq8APb0th_FjPYO/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1Kt3Oqf1Oet8lFtpRtUq8APb0th_FjPYO" width="240" alt="19xx - M471A - DOC - 471-04-006 - STEREO INPUT MODULE.jpg"></a><br><sub>19xx - M471A - DOC - 471-04-006 - STEREO INPUT MODULE · <a href="MECHANICAL/19xx%20-%20M471A%20-%20DOC%20-%20471-04-006%20-%20STEREO%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOHVXUDFZRHBCNVk/view?resourcekey=0-BwBhCZarexgaYuYbwJt5Mg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOHVXUDFZRHBCNVk&resourcekey=0-BwBhCZarexgaYuYbwJt5Mg" width="240" alt="1985 - M471A - 471-01-002 - CONTROL COMMON PRE POST.jpg"></a><br><sub>1985|18 · 471-01-002 - CONTROL COMMON PRE POST · <a href="SCHEMATICS/1985%20-%20M471A%20-%20471-01-002%20-%20CONTROL%20COMMON%20PRE%20POST%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMEpQWC1NdGZpODA/view?resourcekey=0-mb68Xmu-WvjCVSpWvHlMZg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMEpQWC1NdGZpODA&resourcekey=0-mb68Xmu-WvjCVSpWvHlMZg" width="240" alt="1985 - M471A - 471-02-002 - UNLESS SPELIFIEO OTHERWISE.jpg"></a><br><sub>1985|18 · 471-02-002 - UNLESS SPELIFIEO OTHERWISE · <a href="SCHEMATICS/1985%20-%20M471A%20-%20471-02-002%20-%20UNLESS%20SPELIFIEO%20OTHERWISE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZDBoaTdTeEMtOXc/view?resourcekey=0-6SN6Md8EeXedzSLEHn7EEw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZDBoaTdTeEMtOXc&resourcekey=0-6SN6Md8EeXedzSLEHn7EEw" width="240" alt="1985 - M471A - 471-06-002 - FINIS INPUT MODULE.jpg"></a><br><sub>1985|18 · 471-06-002 - FINIS INPUT MODULE · <a href="SCHEMATICS/1985%20-%20M471A%20-%20471-06-002%20-%20FINIS%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcXVrVFJidkVERjg/view?resourcekey=0-WmAd8EaTDuXm1BTB6RsPUQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcXVrVFJidkVERjg&resourcekey=0-WmAd8EaTDuXm1BTB6RsPUQ" width="240" alt="1985 - M471A - 8-109-06-003 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1985|18 · 8-109-06-003 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1985%20-%20M471A%20-%208-109-06-003%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1978 - 8-109-02-003 - 8-109B BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M471A - RTO-144 Connections.pdf`

## RTO-144 pinout

22 contacts, 22 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 |  | unread |  | variant |
| 1 |  | unread |  | variant |
| 20 | COMMON RETURN FOR THE 1/-25 VOLT SUPPLIES | ground |  | variant |
| 21 | OUTPUT FROM THE PREAMPLIFIER | out |  | variant |
| 21 |  | unread |  | variant |
| 22 | COMMON RETURN FOR THE 1/-25 VOLT SUPPLIES | ground |  | variant |
| 22 |  | unread |  | variant |
| 22 |  | unread |  | variant |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSEpZS19pRkVqM2M/view?resourcekey=0-yYgrEvH-hRrHul5p-NItTA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSEpZS19pRkVqM2M&resourcekey=0-yYgrEvH-hRrHul5p-NItTA" width="240" alt="1985 - M471A - P001 - Title Page.jpg"></a><br><sub>1985|18 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSW1TTFRjLU0tVzA/view?resourcekey=0-jQa8HrmnbANh7lb3zgOYCg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSW1TTFRjLU0tVzA&resourcekey=0-jQa8HrmnbANh7lb3zgOYCg" width="240" alt="1985 - M471A - P002.jpg"></a><br><sub>1985|18 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGdJTTZpSWY5bGc/view?resourcekey=0-KnRMeQRVDm3FE9zAZhDDyg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGdJTTZpSWY5bGc&resourcekey=0-KnRMeQRVDm3FE9zAZhDDyg" width="240" alt="1985 - M471A - P003 - 1-1.jpg"></a><br><sub>1985|18 · P003 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQzZmeUd1ZnVDcEk/view?resourcekey=0-3YJqgNJ_24hxCXuHr_UzXA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQzZmeUd1ZnVDcEk&resourcekey=0-3YJqgNJ_24hxCXuHr_UzXA" width="240" alt="1985 - M471A - P004 - 2-1.jpg"></a><br><sub>1985|18 · P004 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbUJmeEJweVlOaUk/view?resourcekey=0-aac65Ve5lxhia2qI6CT-4Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbUJmeEJweVlOaUk&resourcekey=0-aac65Ve5lxhia2qI6CT-4Q" width="240" alt="1985 - M471A - P005 - 2-2.jpg"></a><br><sub>1985|18 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT0VicV9Qbll0LTQ/view?resourcekey=0-PdszQqZfsWqnD_bHD1N8dg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT0VicV9Qbll0LTQ&resourcekey=0-PdszQqZfsWqnD_bHD1N8dg" width="240" alt="1985 - M471A - P006 - 3-1.jpg"></a><br><sub>1985|18 · P006 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHJuZVJaemFJWUk/view?resourcekey=0-L2fhxRutGF5Sx4Ml_W0eKw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHJuZVJaemFJWUk&resourcekey=0-L2fhxRutGF5Sx4Ml_W0eKw" width="240" alt="1985 - M471A - P007 - 3-2.jpg"></a><br><sub>1985|18 · P007 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKalJoUzA1Vk9fcjg/view?resourcekey=0-7iWCJPZoKTiyLMoSUl5o4A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKalJoUzA1Vk9fcjg&resourcekey=0-7iWCJPZoKTiyLMoSUl5o4A" width="240" alt="1985 - M471A - P008 - 3-3.jpg"></a><br><sub>1985|18 · P008 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeFhFZDlNVzQtN28/view?resourcekey=0-MdcBYROttAaneF8pVO3chQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeFhFZDlNVzQtN28&resourcekey=0-MdcBYROttAaneF8pVO3chQ" width="240" alt="1985 - M471A - P009 - 8-109-1-1.jpg"></a><br><sub>1985|18 · P009 - 8-109-1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanNrM0tBakpKNjg/view?resourcekey=0-e1KwEXfoV5RouTwnzPvcFg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanNrM0tBakpKNjg&resourcekey=0-e1KwEXfoV5RouTwnzPvcFg" width="240" alt="1985 - M471A - P010 - 8-109-1-2.jpg"></a><br><sub>1985|18 · P010 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQnppRlNNaFBGTHM/view?resourcekey=0-SnY_Q5yPm4MXcJaJm13MdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQnppRlNNaFBGTHM&resourcekey=0-SnY_Q5yPm4MXcJaJm13MdQ" width="240" alt="1985 - M471A - P011 - 8-109-1-3.jpg"></a><br><sub>1985|18 · P011 - 8-109-1-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFVEa2M4aXBJXzg/view?resourcekey=0-CF1uUqD2B6dVBUnhl28h2A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFVEa2M4aXBJXzg&resourcekey=0-CF1uUqD2B6dVBUnhl28h2A" width="240" alt="1985 - M471A - P012 - 8-109-2-1.jpg"></a><br><sub>1985|18 · P012 - 8-109-2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeEZVRjcwbWZ2ZTQ/view?resourcekey=0-bSSjUxQEzO9znd9wnwxqFw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeEZVRjcwbWZ2ZTQ&resourcekey=0-bSSjUxQEzO9znd9wnwxqFw" width="240" alt="1985 - M471A - P013 - 8-109-2-2.jpg"></a><br><sub>1985|18 · P013 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX25DVjJxdUlrSTA/view?resourcekey=0-CSZAaD593aioF-I6Hz70tg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX25DVjJxdUlrSTA&resourcekey=0-CSZAaD593aioF-I6Hz70tg" width="240" alt="1985 - M471A - P014 - 8-109-2-3.jpg"></a><br><sub>1985|18 · P014 - 8-109-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZXN2ZzVZX2dqV00/view?resourcekey=0-yETbQzr9DraIeb_062F_aw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZXN2ZzVZX2dqV00&resourcekey=0-yETbQzr9DraIeb_062F_aw" width="240" alt="1985 - M471A - P015 - 8-109-2-4.jpg"></a><br><sub>1985|18 · P015 - 8-109-2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRFlpYjIxRmdYVTA/view?resourcekey=0-0FdgxUMKZF1w2bZmo-kw8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRFlpYjIxRmdYVTA&resourcekey=0-0FdgxUMKZF1w2bZmo-kw8w" width="240" alt="1985 - M471A - P016 - 8-109-2-5.jpg"></a><br><sub>1985|18 · P016 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeFJRQUhtRHNhb2M/view?resourcekey=0-wF-V5LnEhghWdq8yK3wRFA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeFJRQUhtRHNhb2M&resourcekey=0-wF-V5LnEhghWdq8yK3wRFA" width="240" alt="1985 - M471A - P017 - 5-1.jpg"></a><br><sub>1985|18 · P017 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbzJpLWJHQ01HWEk/view?resourcekey=0-Z8AbC_b5OqSoQjiY4t0TNA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbzJpLWJHQ01HWEk&resourcekey=0-Z8AbC_b5OqSoQjiY4t0TNA" width="240" alt="1985 - M471A - Stereo Input Module (2).pdf"></a><br><sub>1985|18 · Stereo Input Module (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcjlOcmliaFNPSzA/view?resourcekey=0-cOlK9Vm9HxJRCCzyiyeZpQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcjlOcmliaFNPSzA&resourcekey=0-cOlK9Vm9HxJRCCzyiyeZpQ" width="240" alt="1985 - M471A - Stereo Input Module.pdf"></a><br><sub>1985|18 · Stereo Input Module</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - 8-109-02-003 - 8-109B BOOSTER AMPLIFIER SCHEMATIC - DRN GEB - ENG MRW - ISS 1.kicad_sch](KICAD/1978%20-%208-109-02-003%20-%208-109B%20BOOSTER%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20GEB%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1985 - M471A - 471-01-002 - CONTROL COMMON PRE POST.kicad_sch](KICAD/1985%20-%20M471A%20-%20471-01-002%20-%20CONTROL%20COMMON%20PRE%20POST.kicad_sch)
- [1985 - M471A - 471-02-002 - UNLESS SPELIFIEO OTHERWISE.kicad_sch](KICAD/1985%20-%20M471A%20-%20471-02-002%20-%20UNLESS%20SPELIFIEO%20OTHERWISE.kicad_sch)
- [1985 - M471A - 8-109-02-003 - ISSUEDATE REVISION.kicad_sch](KICAD/1985%20-%20M471A%20-%208-109-02-003%20-%20ISSUEDATE%20REVISION.kicad_sch)
- [1985 - M471A - Stereo Input Module (2) p19.kicad_sch](KICAD/1985%20-%20M471A%20-%20Stereo%20Input%20Module%20(2)%20p19.kicad_sch)
- [1985 - M471A - Stereo Input Module (2) p22.kicad_sch](KICAD/1985%20-%20M471A%20-%20Stereo%20Input%20Module%20(2)%20p22.kicad_sch)
- [1985 - M471A - Stereo Input Module p19.kicad_sch](KICAD/1985%20-%20M471A%20-%20Stereo%20Input%20Module%20p19.kicad_sch)
- [1985 - M471A - Stereo Input Module p20.kicad_sch](KICAD/1985%20-%20M471A%20-%20Stereo%20Input%20Module%20p20.kicad_sch)
- [1985 - M471A - Stereo Input Module p22.kicad_sch](KICAD/1985%20-%20M471A%20-%20Stereo%20Input%20Module%20p22.kicad_sch)
- [M471A.kicad_sym](KICAD/M471A.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
