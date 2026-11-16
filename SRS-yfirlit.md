# Staðsetning krafna í SRS

Þetta skjal sýnir staðsetningu endurbættra virknikrafna Vaktaskiptakerfisins í SRS samkvæmt uppbyggingu Wiegers og Beatty. Kröfunum er raðað eftir virkni kerfisins svo þróunaraðilar geti auðveldlega fundið þær kröfur sem tengjast tilteknum aðgerðum, prófarar geti tengt prófunartilvik við viðeigandi kröfur og stjórnendur fengið yfirsýn yfir virkni kerfisins.

## Kröfur


| SRS-kafli eða undirkafli | Auðkenni og tenglar í kröfuskjöl | Rök fyrir staðsetningu og þörf lesenda |
| --- | --- | --- |
| 3.5.1 Lausar vaktir | [FR-4](requirements/FR-4.md) | Krafan fjallar um birtingu lausra vakta. Þróunaraðilar og prófarar geta auðveldlega fundið upplýsingar um hvaða vaktir eiga að birtast starfsmönnum. |
| 3.5.2 Yfirlit beiðna | [FR-3](requirements/FR-3.md), [FR-7](requirements/FR-7.md), [FR-8](requirements/FR-8.md), [FR-9](requirements/FR-9.md) | Kröfurnar fjalla um birtingu beiðna, stöðu þeirra og tengdar upplýsingar. Sameiginleg staðsetning auðveldar þróunaraðilum og prófurum að finna og sannprófa kröfur um upplýsingabirtingu. |
| 3.5.3 Afgreiðsla beiðna | [FR-10](requirements/FR-10.md), [FR-11](requirements/FR-11.md) | Kröfurnar fjalla um samþykki og höfnun beiðna. Þær eru hafðar saman til að auðvelda þróunaraðilum og prófurum að skoða og sannprófa breytingar á stöðu beiðna. |
| 3.5.4 Vaktaplan og ábyrgð | [FR-14](requirements/FR-14.md) | Krafan fjallar um birtingu ábyrgðaraðila vakta í vaktaplani. Staðsetningin auðveldar þróunaraðilum og prófurum að finna kröfur um upplýsingar í vaktaplaninu. |



## Tengdar upplýsingar

| Upplýsingar | Staðsetning / auðkenni / tengill | Tengsl við kröfur eða sýnileg eyða og eftirfylgni |
| --- | --- | --- |
| Samhengi kerfisins | [Verkefni 1](https://github.com/GabrielKalli/HBV301G-Verkefni-1) | Vaktaskiptakerfið gerir starfsmönnum kleift að óska eftir afleysingum og stjórnendum að afgreiða beiðnir. Samhengið tengist öllum átta virknikröfunum. |
| Notendahlutverk | [Verkefni 1](https://github.com/GabrielKalli/HBV301G-Verkefni-1) | Helstu hlutverk eru starfsmaður og stjórnandi. FR-3 og FR-4 tengjast starfsmönnum, FR-7, FR-8, FR-9, FR-10 og FR-11 stjórnendum og FR-14 öllum notendum. |
| Orðasafn | [Verkefni 1](https://github.com/GabrielKalli/HBV301G-Verkefni-1) | Hugtökin vakt, afleysing, vaktaskipti og beiðni tengjast öllum kröfunum. TBD: Staðfesta hvort skilgreiningar hugtakanna séu skráðar og samræmdar. Ábyrgð: verkefnishópurinn. Næsta skref: yfirfara gögn úr verkefni 1. |
| Viðskiptareglur | [Verkefni 5](https://github.com/edilinga/HBV301G-Verkefni-5) | Reglur um heimildir og afgreiðslu beiðna tengjast sérstaklega FR-7, FR-8, FR-9, FR-10 og FR-11. TBD: Staðfesta hvaða viðskiptareglur eiga við og skrá nákvæm auðkenni þeirra. Ábyrgð: verkefnishópurinn. Næsta skref: yfirfara viðskiptareglur úr verkefni 5. |
| Gæðakröfur | [Verkefni 5](https://github.com/edilinga/HBV301G-Verkefni-5) | Gæðakröfur um meðal annars nothæfi og afköst geta haft áhrif á birtingu vakta og beiðna í FR-3, FR-4, FR-7, FR-8, FR-9 og FR-14. TBD: Staðfesta tengsl við einstakar gæðakröfur og skrá auðkenni þeirra. Ábyrgð: verkefnishópurinn. Næsta skref: yfirfara gæðakröfur úr verkefni 5. |
| Forsendur | [Verkefni 1](https://github.com/GabrielKalli/HBV301G-Verkefni-1) | Gert er ráð fyrir að upplýsingar um vaktir, starfsmenn og beiðnir séu tiltækar í kerfinu. Þetta tengist öllum átta kröfunum. TBD: Staðfesta forsendur um aðgangsheimildir stjórnenda og skráningu ábyrgðaraðila vakta. Ábyrgð: verkefnishópurinn. Næsta skref: yfirfara fyrirliggjandi kröfur og viðskiptareglur. |

