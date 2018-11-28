---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for august 2008
TOCTitle: MS08-AUG
ms:assetid: ms08-aug
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms08-aug(v=Security.10)
ms:contentKeyID: 61224037
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for august 2008

Offentliggjort: 12. august 2008 | Opdateret: 15. oktober 2008

**Version:** 3.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for august 2008.

Med udgivelsen af bulletiner for august 2008 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 7. august 2008. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 13. august 2008 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få august måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032374631&culture=en-us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede vigtige opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

#### Resuméer

Denne måneds sikkerhedsbulletiner er opstillet efter vigtighed på følgende måde:

## Kritisk (6)

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-046 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120576"><strong>En sårbarhed i Microsoft Windows Image Color Management System kan tillade fjernudførelse af kode (952954)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Image Color Management-systemet (ICM), som kunne tillade fjernudførelse af kode i brugerens kontekst. Hvis en bruger er logget på med administrative brugerrettigheder, kan en hacker, som har held med at udnytte denne sårbarhed, få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-045 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=122772"><strong>Samlet sikkerhedsopdatering til Internet Explorer (953838)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser fem privat rapporterede sårbarheder og én offentliggjort sårbarhed. Alle disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows, Internet Explorer.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-041 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=122912"><strong>Sårbarhed i ActiveX-objektet til Snapshot Viewer til Microsoft Access kan gøre fjernudførelse af kode mulig (955617)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i ActiveX-objektet til Snapshot Viewer til Microsoft Access. En hacker kan udnytte sårbarheden ved at oprette en særligt udformet webside. Når en bruger åbner websiden, kan sårbarheden gøre fjernudførelse af kode mulig. En hacker, som det lykkes for at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den bruger, der er logget på.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart af computeren.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-043 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124306"><strong>Sårbarheder i Microsoft Excel kan give mulighed for fjernudførelse af kode (954066)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser fire privat rapporterede sårbarheder i Microsoft Office Excel, som kan muliggøre fjernudførelse af kode, når en bruger åbner en særligt udformet Excel-fil. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart af computeren.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-051 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120394"><strong>Sårbarheder i Microsoft PowerPoint kan give mulighed for fjernudførelse af kode (949785)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser tre privat rapporterede sårbarheder i Microsoft Office PowerPoint og Microsoft Office PowerPoint Viewer, som kan give mulighed for fjernudførelse af kode, når en bruger åbner en særligt udformet PowerPoint-fil. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart af computeren.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-044 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120819"><strong>Sårbarheder i Microsoft Office Filters kan muliggøre fjernudførelse af kode (924090)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser fem privat rapporterede sårbarheder. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet billedfil med Microsoft Office. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart af computeren.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Alvorlig (5)

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-047 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120577"><strong>Sårbarhed i IPsec Policy Processing kan give mulighed for offentliggørelse af oplysninger (953733)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i den måde, hvorpå Windows Internet Protocol Security-regler (IPsec) anvendes. Denne sårbarhed kan få systemer til at ignorere IPsec-politikker og videregive netværkstrafik i klar tekst. Det vil efterfølgende offentliggøre oplysninger, der skal krypteres på netværket. En hacker, der får vist trafikken på netværket, kan få vist og muligvis ændre indholdet. Denne sårbarhed giver ikke en hacker mulighed for at udføre kode eller forbedre sine brugerrettigheder direkte. Den kan bruges til at producere nyttige oplysninger for at sætte de berørte systemer eller netværk i fare.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Offentliggørelse af oplysninger</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-049 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104923"><strong>Sårbarheder i Event System kan give mulighed for fjernudførelse af kode (950974)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denn opdatering løser to privat rapporterede sårbarheder i Microsoft Windows Event System, som kunne tillade fjernudførelse af kode. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data eller oprette nye konti med komplette administrative rettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-048 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=117705"><strong>Sikkerhedsopdatering til Outlook Express og Windows Mail (951066)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Outlook Express og Windows Mail. Sårbarheden kan muliggøre offentliggørelse af oplysninger, hvis en bruger besøger en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Offentliggørelse af oplysninger</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows, Outlook Express, Windows Mail.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-050 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108245"><strong>En sårbarhed i Windows Messenger kan give mulighed for offentliggørelse af oplysninger (955702)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i understøttede versioner af Windows Messenger. Som et resultat af denne sårbarhed kan scripting af et ActiveX-objekt udgøre risiko for offentliggørelse af oplysninger i konteksten for den bruger, der er logget på. En hacker kan ændre tilstand, få kontaktoplysninger og påbegynde lyd- og videochatsessioner uden at den bruger, der er logget på, har kendskab til det. En hacker kan også få fat på brugerens logon-ID, og logge på eksternt til brugerens Messenger-klient og give sig ud for at være brugeren.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Offentliggørelse af oplysninger</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem kun skal bruge denne opdatering til Windows Messenger 4.7 på understøttede versioner af Windows XP. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows, Windows Messenger.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin MS08-042 fra Microsoft</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=123160"><strong>En sårbarhed i Microsoft Word kan muliggøre fjernudførelse af kode (955048)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Microsoft Word. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Word-fil. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart af computeren.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Berørte programmer og downloadplaceringer

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at få kendskab til de sikkerhedsopdateringer, du muligvis skal installere. Du skal se alle de anførte softwareprogrammer eller komponenter igennem for at se, om der er behov for en sikkerhedsopdatering. Hvis et program eller en komponent findes på listen, findes der hyperlinks til tilgængelige softwareopdateringer, og sårbarhedens omfang også angivet.

**Bemærk\!** Du skal muligvis installere flere sikkerhedsopdateringer for en enkelt sårbarhed. Gennemse hele kolonnen for hvert bulletin-id på listen for at kontrollere, hvilke opdateringer du skal installere ud fra de programmer eller komponenter, der er installeret på dit system.

#### Windows-operativsystem

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="7">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=db455d17-435f-46d7-b2dd-5babb5a1eeb3">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1557b93b-ecba-4f42-b89d-db0ee067d65b">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa780735-5928-4c46-89a4-63a814954796">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2ad648-7dc9-407a-99f6-f39922746027">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6257bfae-35f0-4c0e-b960-bca7aa6f86f7">Microsoft Outlook Express 5.5 Service Pack 2</a>
                    <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab178f7-c282-41f4-acb1-a86e6aa4c91b">Microsoft Outlook Express 6 Service Pack 1</a><br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5.1</a>
                    <br />(KB899283)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d313f42c-f43f-48ea-82ef-3bc33077c7fa">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=69af2f30-138e-4b15-ab8d-4fce44cc0bc2">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e2125c7-52cb-4052-82a3-2d3c6a953752">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01a34aa4-a456-4efc-a93a-c3c682b0181c">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91469f2f-461c-4a67-8738-d42520427f6b">Microsoft Outlook Express 6</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f588f7e-c4ed-42a0-b157-54b1eda60474">Windows Messenger 4.7</a>
                    <br />(KB946648)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5,1</a><br />(KB899283)<br />(Alvorlig)</td></tr>
                <tr><td>Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3150c6b8-f50b-4b84-a7ce-c8daf77c080c">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4780b89e-9735-4d3f-8def-34e7337ff604">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39b41e4b-3237-409d-a818-ab0517c5e7cf">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=246b2686-e330-47a2-b4d4-68f218ad4021">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2220aece-79d2-426f-90ec-24a17470567a">Microsoft Outlook Express 6</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a5fc5457-832f-4ee8-be60-4cc8518d1c10">Windows Messenger 4.7</a>
                    <br />(KB946648)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5,1</a><br />(KB899283)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=828d8fdc-8534-4621-85a5-08aec255496f">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0617a5dd-dce9-4de0-b0a0-ce38efe13524">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3c2e2fd-1cb9-491b-937c-053dd59a65bf">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92a3d08f-c117-4b24-bc78-2b913d270df6">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30f2244a-f6fd-4fc1-a871-abf6958cb660">Microsoft Outlook Express 6</a>
                    <br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=302315a8-ccb2-47c2-9104-b8e1d1f49aa0">Windows Messenger 4.7</a>
                    <br />(KB954723)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5,1</a><br />(KB899283)<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a13776f-d543-41df-b904-d51e368c81cc">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=32a63f52-9fe6-48e3-bb4e-7d4dda5e0a90">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88a26b76-f7df-45c9-8ed0-7d3cd71c1987">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6bfbb6d8-5106-4adf-83cb-35ffc6e8eaf8">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3287f006-cbb2-4c6d-820c-32833e08035a">Microsoft Outlook Express 6</a>
                    <br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=be94d138-7d7b-489e-baa6-e214950be6b9">Windows Messenger 4.7</a>
                    <br />(KB954723)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5,1</a><br />(KB899283)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9566493f-4260-4072-947a-527887d2cd63">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1855997e-a3be-46b1-a0bc-bb55eb0045fe">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=97d0d37d-5d76-4bc3-8cbd-1e3976c82acf">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45356565-697f-41b3-9879-3edd11dbcb7e">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8570e40-355b-4a9b-933d-53ae021cbda5">Microsoft Outlook Express 6</a>
                    <br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e4b72618-536b-4a21-bd91-d91be9ca24e5">Windows Messenger 4.7</a>
                    <br />(KB954723)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5,1</a><br />(KB899283)<br />(Moderat)</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Vista og Windows Vista Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13cba012-dd20-48f9-8e44-e4cb104c4cad">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f21a8a2-9861-4fef-9d1e-caf5f7822c1a">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6418c78f-f008-4028-beb1-5a5ea8e797a1">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3851bcf8-f971-4d38-b27f-97396854aac0">Windows Mail</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ead919c2-d548-47b7-9cd6-80f991266428">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa04a754-fbfb-42a7-89d2-14373e3f4742">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e03ccfb0-3ea3-4c59-adcf-9882d7086013">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3bf7eb8a-b347-4661-be2d-682adc713769">Windows Mail</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 til 32 bit-systemer                    </td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b52ff2f-d2f5-4c20-b6cf-86d86c56b0f8">Windows Internet Explorer 7</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3363df6-39dc-4910-9ce5-66553155378e">Windows Server 2008 til 32 bit-systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0640f95e-1eee-4dd1-b4dd-2b82b7e984b9">Windows Server 2008 til 32 bit-systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc3c4b63-acd3-4469-8d47-e0562d99ee65">Windows Mail</a>**<br />(Lav)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til x64-baserede systemer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=df9814a6-5be0-4ac1-a767-a0eae8d5ee5d">Windows Internet Explorer 7</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39dd1722-412b-469d-a475-b6513764838c">Windows Server 2008 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51a93538-5e94-4f81-a6e0-d497a7b4899d">Windows Server 2008 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f973f54-2322-4b41-8c1a-3e712c0da8ae">Windows Mail</a>**<br />(Lav)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 til Itanium-baserede systemer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc3cfcb-73fe-4a6d-9595-e9d7a5b3d3f7">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9c6cd46-30ad-46ee-9c8b-d0b446e660c4">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=390da130-749d-4890-aad7-be91e15b32bb">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9226cd85-1445-4976-a126-757c5d142ffd">Windows Mail</a>
                    <br />(Lav)</td><td>Ikke relevant</td></tr>
              </table>


**\*Windows Server 2008 - serverens hovedinstallation er berørt.** For understøttede udgaver af Windows Server 2008 gælder denne opdatering med den samme klassifikation, uanset om Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core eller ej. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 - serverens hovedinstallation er ikke berørt.** Den sårbarhed, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008, hvis Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Micorsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="6">Microsoft Office Suites, systemer og komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122912">
                      <strong>MS08-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124306">
                      <strong>MS08-043</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120394">
                      <strong>MS08-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120819">
                      <strong>MS08-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=123160">
                      <strong>MS08-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Works 8</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=458985c3-9c6f-4049-81cd-0d0389c81f11">Microsoft Works 8</a>
                    <br />(KB955428)<br />(Alvorlig)</td><td>Ikke relevant </td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2000 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54e4031d-298f-480c-88d5-0ad3b2b62ba9">Microsoft Office Access 2000 Service Pack 3</a>
                    <br />(KB955441)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4bf8688e-e5b9-4e53-a1a1-8cf1acfdb80b">Excel 2000 Service Pack 3</a>
                    <br />(KB951582)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7c044d8-778a-4985-b25b-4f7f6e4abadd">Microsoft Office PowerPoint 2000 Service Pack 3</a>
                    <br />(KB949007)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ab323ec-9f92-453c-b7c7-9a95a9efcaea">Microsoft Office 2000 Service Pack 3</a>
                    <br />(KB921595)<br />(Kritisk)</td><td>Ikke relevant </td></tr>
                <tr><td>Microsoft Office XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34b655f8-1922-4246-94ca-ed381c3e3b13">Microsoft Office Access 2002 Service Pack 3</a>
                    <br />(KB955440)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9bbf7550-f5c4-4b9b-bd86-1e7be6c42eb5">Excel 2002 Service Pack 3</a>
                    <br />(KB951551)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8921074-7985-4d42-ac2b-d2f3b1d466ba">Microsoft Office PowerPoint 2002 Service Pack 3</a>
                    <br />(KB948995)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79">Microsoft Office XP Service Pack 3</a>
                    <br />(KB921596)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7146dfc-e1be-4d13-877b-1d9bcacc4a64">Microsoft Word 2002 Service Pack 3</a>
                    <br />(KB954463)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 2 og Microsoft Office 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd698517-a504-427d-9e5f-fde8f102142c">Microsoft Office Access 2003 Service Pack 2 og Microsoft Office Access 2003 Service Pack 3</a>
                    <br />(KB955439)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0">Excel 2003 Service Pack 2</a>
                    <br />(KB951548)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0">Excel 2003 Service Pack 3</a><br />(KB951548)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f">Microsoft Office PowerPoint 2003 Service Pack 2</a>**<br />(KB948988)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f">Microsoft Office PowerPoint 2003 Service Pack 3</a>***<br />(KB948988)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0df2f6e-1102-461d-829f-5f3e2d7eb4b3">Microsoft Office 2003 Service Pack 2</a>
                    <br />(KB921598)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13a37b76-9fec-426f-8176-3c95f934efe0">Microsoft Word 2003 Service Pack 2</a>
                    <br />(KB954464)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13a37b76-9fec-426f-8176-3c95f934efe0">Microsoft Word 2003 Service Pack 3</a><br />(KB954464)<br />(Alvorlig)</td></tr>
                <tr><td>2007 Microsoft Office System og 2007 Microsoft Office System Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd">Excel 2007</a>
                    <br />(KB951546)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd">Excel 2007 Service Pack 1</a><br />(KB951546)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef1">Microsoft Office PowerPoint 2007</a>
                    <br />(KB951338)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef1">Microsoft Office PowerPoint 2007 Service Pack 1</a><br />(KB951338)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Anden Office Software</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122912">
                      <strong>MS08-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124306">
                      <strong>MS08-043</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120394">
                      <strong>MS08-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120819">
                      <strong>MS08-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=123160">
                      <strong>MS08-042</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Project 2002 Service Pack 1</td><td>Ikke relevant </td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79">Microsoft Office Project 2002 Service Pack 1</a>
                    <br />(KB921596)<br />(Alvorlig)</td><td>Ikke relevant </td></tr>
                <tr><td>SnapShot Viewer til Microsoft Access</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c22bb32-7ce3-4ff2-8366-ba2eb5135833">SnapShot Viewer til Microsoft Access</a>
                    <br />(KB957198) <br />(Kritisk)<br /></td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office PowerPoint Viewer 2003</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=911c8872-dec8-4b8e-9708-93dcabd3e036">Microsoft Office PowerPoint Viewer 2003</a>
                    <br />(KB949041)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Excel Viewer 2003 og Microsoft Office Excel Viewer 2003 Service Pack 3</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1">Microsoft Office Excel Viewer 2003</a>
                    <br />(KB951589)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1">Microsoft Office Excel Viewer 2003 Service Pack 3</a><br />(KB951589)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b574d906-7f09-49b0-80bf-e84dee8c4583">Microsoft Office Excel Viewer</a>
                    <br />(KB955472)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Converter Pack</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=199b08c7-6d79-4930-8f0c-31034629c485">Microsoft Office Converter Pack</a>
                    <br />(KB925256)<br />(Alvorlig)</td><td>Ikke relevant </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater og Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9">Microsoft Office Compatibility Pack for Word, Excel og PowerPoint 2007 File Formats</a>
                    <br />(KB951596)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1</a><br />(KB951596)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84ce5d58-0010-4945-bce9-67a41f898f2f">Microsoft Office Compatibility Pack for Word, Excel og PowerPoint 2007 File Formats</a> (KB954038)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84ce5d58-0010-4945-bce9-67a41f898f2f">Microsoft Office Compatibility Pack for Word, Excel og PowerPoint 2007 File Formats Service Pack 1</a> (KB954038)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office SharePoint Server 2007 og Microsoft Office SharePoint Server 2007 Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7731749-b026-4765-808a-e151b990f0e1">Microsoft Office SharePoint Server 2007</a>*<br />(KB953397)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7731749-b026-4765-808a-e151b990f0e1">Microsoft Office SharePoint Server 2007 Service Pack 1</a>*<br />(KB953397)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007 x64 Edition og Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b">Microsoft Office SharePoint Server 2007 x64 Edition</a>*<br />(KB953397)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b">Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1</a>*<br />(KB953397)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Microsoft Office til Mac</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122912">
                      <strong>MS08-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124306">
                      <strong>MS08-043</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120394">
                      <strong>MS08-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120819">
                      <strong>MS08-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=123160">
                      <strong>MS08-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2004 til Mac</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5">Microsoft Office 2004 til Mac</a>
                    <br />(KB956343)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5">Microsoft Office 2004 til Mac</a>
                    <br />(KB956343)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 til Mac</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9515c70d-be80-4ade-856a-ea542f7d84e1">Microsoft Office 2008 til Mac</a>
                    <br />(KB956344)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              </table>


**\*Bemærkning til Microsoft Office SharePoint Server 2007, Microsoft Office SharePoint Server 2007 Service Pack 1, Microsoft Office SharePoint Server 2007 x64 Edition og Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1 (MS08-043):** Den opdatering, der er omfattet af sikkerhedsbulletinen MS08-043, gælder for servere, hvor Excel Services er installeret, f.eks. standardkonfigurationen af Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 For Internet Sites. Microsoft Office SharePoint Server 2007 Standard omfatter ikke Excel Services.

**\*\*Bemærkning til Microsoft Office PowerPoint 2003 Service Pack 2 og Microsoft Office PowerPoint 2003 Service Pack 3 (MS08-051):** Microsoft har offentliggjort nye opdateringspakker, kaldet Version 2, på Microsoft Download Center. Kunder, der manuelt har installeret Version 1 af denne opdatering fra Microsoft Download Center, skal geninstallere Version 2 af denne opdatering. Kunder, der har installeret denne opdatering vha. Microsoft Update eller Office Update, behøver ikke geninstallere den. Du kan finde flere oplysninger, herunder andre installations- eller omgåelsesmuligheder, i bulletin [MS08-051](http://go.microsoft.com/fwlink/?linkid=120394).

## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=699031). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) og [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Vejledning i registrering og implementering**

Microsoft har offentliggjort en vejledning i registrering og implementering til denne måneds sikkerhedsopdateringer. Denne vejledning forklarer også it-professionelle, hvordan de kan bruge forskellige værktøjer til at implementere sikkerhedsopdateringen, f.eks. Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office Detection Tool, SMS (Microsoft Systems Management Server), Extended Security Update Inventory Tool og ESUIT (Extended Security Update Inventory Tool). Yderligere oplysninger findes i [Knowledge Base-artiklen 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) giver administratorer mulighed for at søge på lokale systemer og fjernsystemer efter manglende sikkerhedsopdateringer samt almindelige fejl ved sikkerhedskonfigurationer. Hvis du ønsker yderligere oplysninger om MBSA, kan du besøge webstedet [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

**Systems Management Server**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere. Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig, se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Få mere at vide om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsoplysninger, på [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brugere kan også bruge [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) som en hjælp til at implementere sikkerhedsopdateringer. Oplysninger om SMS findes på [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Bemærk\!** SMS bruger Microsoft Baseline Security Analyzer og Microsoft Office Detection Tool til at tilbyde omfattende understøttelse af registrering og anvendelse af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til at installere disse opdateringer.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Opdateringer skriver ofte til de samme filer og registreringsdatabaseindstillinger, der er nødvendige for, at dine programmer kan køre. Dette kan udløse inkompatibilitet og forøge den tid, det tager at implementere sikkerhedsopdateringer. Du kan strømline test og validering af Windows-opdateringer mod installerede programmer med de [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponenter, der følger med [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Microsoft Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede vigtige opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede opdateringer til Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services for 2008. Omfatter alt Windows-indhold.
  - [Nye, reviderede og offentliggjorte opdateringer til Microsoft-produkter ud over Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214,aspx).

#### Sikkerhedsstrategier og community

**Strategier til håndtering af opdateringer**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) giver yderligere oplysninger om Microsofts anbefalinger til de bedste fremgangsmåder for anvendelse af sikkerhedsopdateringer.

**Andre sikkerhedsopdateringer**

Opdateringer til andre sikkerhedsproblemer er tilgængelige på følgende placeringer:

  - Der kan hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".
  - Der kan findes opdateringer til forbrugerplatforme på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan hente de sikkerhedsopdateringer, der er gjort tilgængelige på Windows Update denne måned, fra Download Center på Security and Critical Releases ISO CD Image-filer. Yderligere oplysninger finder du i [Microsoft Knowledge Base Article 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Lær, hvordan du forbedrer sikkerheden og optimerer din it-infrastruktur og diskuterer sikkerhedsemner med andre it-fagfolk i [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164).

#### Tak til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for at hjælpe os i arbejdet med at beskytte kunderne:

  - [ISC/SANS](http://isc.sans.org/) for at have rapporteret et problem, der er beskrevet i MS08-042
  - [VeriSign iDefense VCP](http://www.idefense.com/vcp) for at have rapporteret et problem, der er beskrevet i MS08-043
  - [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at have rapporteret et problem, der er beskrevet i MS08-043
  - Jeremy Funk for at have rapporteret et problem, der er beskrevet i MS08-043
  - Shaun Colley of [NGS Software](http://www.nextgenss.com/) for at have rapporteret et problem, der er beskrevet i MS08-044
  - Damian Put, der arbejder hos [Zero Day Initiative (ZDI)](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS08-044
  - En anonym forsker, der arbejder for [iDefense VCP](http://labs.idefense.com/), for at have rapporteret et problem, der er beskrevet i MS08-044.
  - Damian Put, der arbejder for [VeriSign iDefense VCP](http://labs.idefense.com/), for at have rapporteret et problem, der er beskrevet i MS08-044
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at have rapporteret et problem, der er beskrevet i MS08-045
  - Tavis Ormandy fra [Google Security Team](http://www.google.com/) for at rapportere et problem, der er beskrevet i MS08-045
  - Sam Thomas, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative,](http://www.zerodayinitiative.com/) for at have rapporteret et problem, MS08-045
  - [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at have rapporteret et problem, der er beskrevet i MS08-045
  - Jun Mao fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret et problem, der er beskrevet i MS08-046
  - Jorge Luis Alvarez Medina fra [Core Security Technologies](http://www.coresecurity.com/) for at rapportere et problem, der er beskrevet i MS08-048
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at have rapporteret et problem, der er beskrevet i MS08-049
  - Haifei Li fra Fortinets [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com) for at rapportere et problem, der er beskrevet i MS08-050
  - Vadim Pogulievsky fra Finjan's [Malicious Code Research Center](http://www.finjan.com/securitylab.aspx?id=547) for at rapportere et problem, der er beskrevet i MS08-050
  - Ruben Santamarta fra [Reversemode.com](http://reversemode.com/), i samarbejde med [iDefense Labs](http://labs.idefense.com/), for at rapportere et problem, der er beskrevet i MS08-051
  - ADLab fra [Venustech](http://www.venustech.com.cn) for at have rapporteret et problem, der er beskrevet i MS08-051

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis.
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (12. august 2008): Oversigt over bulletin offentliggjort.
  - V2.0 (20. august 2008): Tilføjet bemærkning til MS08-043 i Berørte programmer og downloadplaceringer for at tydeliggøre, at denne opdatering gælder for servere, hvor Excel Services er installeret, f.eks. standardkonfigurationen af Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 For Internet Sites. Microsoft Office SharePoint Server 2007 Standard omfatter ikke Excel Services. Endnu en tilføjet bemærkning til MS08-051 i Berørte programmer og downloadplaceringer, om at Microsoft har offentliggjort nye opdateringspakker, kaldet Version 2, til Microsoft Office PowerPoint 2003 Service Pack 2 og Microsoft Office PowerPoint 2003 Service Pack 3 på Microsoft Download Center. Kunder, der manuelt har installeret Version 1 af denne opdatering fra Microsoft Download Center, skal geninstallere Version 2 af denne opdatering. Kunder, der har installeret denne opdatering vha. Microsoft Update eller Office Update, behøver ikke geninstallere den.
  - V3.0 (15. oktober 2008): Opdateringen til Snapshot Viewer til Microsoft Access (MS08-041) medtaget. Brugere, der har installeret opdateringen til Microsoft Office 2000 Service Pack 3, Office XP Service Pack 2 eller Office 2003 Service Pack 2 eller Office 2003 Service Pack 3, behøver ikke geninstallere opdateringen til den enkeltstående Snapshot Viewer til Microsoft Access.

*Built at 2014-04-18T01:50:00Z-07:00*

