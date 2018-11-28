---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for januar 2012
TOCTitle: MS12-JAN
ms:assetid: ms12-jan
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms12-jan(v=Security.10)
ms:contentKeyID: 61224086
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for januar 2012

Offentliggjort: 10. januar 2012 | Opdateret: 27. januar 2012

**Version:** 2.1

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for januar 2012.

Med udgivelsen af sikkerhedsbulletiner for januar 2012 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 5. januar 2012. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål vedr. disse bulletiner den 11. januar 2012 kl. 11.00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få januar måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499498). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og webcasts](http://go.microsoft.com/fwlink/?linkid=217214).

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

## Resuméer

Følgende tabel viser sikkerhedsbulletinerne for denne måned efter vigtighed.

Oplysninger om berørte programmer kan fås i næste afsnit, **Berørte programmer og downloadplaceringer**.

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Bulletinens titel og resumé</th>
<th>Klassifikation og sårbarhedens omfang</th>
<th>Krav om genstart</th>
<th>Berørte programmer</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227487">MS12-004</a></td>
<td><strong>Sårbarheder i Windows Media kan give mulighed for fjernudførelse af kode (2636391)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Windows. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet mediefil. En hacker, som har held til at udnytte disse sårbarheder, kan opnå de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235999">MS12-001</a></td>
<td><strong>En sårbarhed i Windows Kernel kan resultere i omgåelse af sikkerhedsfunktion (2644615)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarhed kan gøre det muligt for en hacker at sikkerhedsfunktion SafeSEH i et softwareprogram. Hackeren kan derefter bruge andre sårbarheder til at udnytte den strukturerede undtagelseshåndtering til at køre skadelig kode. Kun softwareprogrammer, der er kompileret med Microsoft Visual C++ .NET 2003, kan bruges til at udnytte denne sårbarhed.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Omgåelse af sikkerhedsfunktion</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229637">MS12-002</a></td>
<td><strong>En sårbarhed i Windows Object Packager kan give mulighed for fjernudførelse af kode (2603381)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger åbner en legitim fil, der er placeret i samme netværksmappe som en særligt udformet eksekverbar fil. En hacker, som det lykkes for at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den bruger, der er logget på. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235400">MS12-003</a></td>
<td><strong>En sårbarhed i Windows Client/Server Run-time Subsystem kan muliggøre udvidelse af rettigheder (2646524)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat sårbarhed i Microsoft Windows. Denne sikkerhedsopdatering er klassificeret som Alvorlig for alle understøttede versioner af Windows XP, Windows Server 2003, Windows Vista og Windows Server 2008. Alle understøttede versioner af Windows 7 og Windows Server 2008 R2 er ikke berørt af denne sårbarhed.<br />
<br />
Sårbarheden kan muliggøre en udvidelse af rettigheder, hvis en hacker logger på et berørt system og har kørt et særligt udformet program. Hackeren kan derefter overtage kontrollen med det berørte system helt og installere programmer, se, ændre eller slette data eller oprette nye konto med komplette brugerrettigheder. Denne sårbarhed kan kun udnyttes på systemer, der er konfigureret med kinesisk, japansk eller koreansksystemlandestandard.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=230777">MS12-005</a></td>
<td><strong>Sårbarhed i Microsoft Windows kan muliggøre fjernudførelse af kode (2584146)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger åbner en særligt udformet Microsoft Office-fil, der indeholder et ondsindet integreret ClickOnce-program. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232510">MS12-006</a></td>
<td><strong>En sårbarhed i SSL/TLS kan muliggøre offentliggørelse af oplysninger (2643584)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i SSL 3.0 og TLS 1.0. Denne sårbarhed berører selve protokollen og er ikke specifik for Windows-operativsystemet. Sårbarheden kan muliggøre offentliggørelse af oplysninger, hvis en hacker opfanger krypteret webtrafik fra en server, hvis system er berørt. TLS 1.1, TLS 1.2 og alle chiffersuiter, der ikke bruger CBC-tilstand, påvirkes ikke.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Afsløring af oplysninger</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227561">MS12-007</a></td>
<td><strong>Sårbarhed i</strong> <strong>AntiXSS</strong> <strong>Library kan muliggøre offentliggørelse af oplysninger (2607664)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Anti-Cross Site Scripting (AntiXSS) Library. Sårbarheden kan muliggøre offentliggørelse af oplysninger, hvis en hacker sender et ondsindet script til et websted med rensningsfunktionen i AntiXSS Library. Konsekvenserne af offentliggørelse af de pågældende oplysninger afhænger af typen af oplysninger. Bemærk, at denne sårbarhed ikke gør det muligt for en hacker at foretage fjernudførelse af kode eller direkte at forbedre hackerens brugerrettigheder, men den kan bruges til at fremskaffe yderligere oplysninger, som derefter kan bruges til at sætte det berørte system i fare. Kun websteder, der benytter rensningsmodulet i AntiXSS Library, er berørt af denne sårbarhed.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Afsløring af oplysninger</td>
<td>Kan kræve genstart</td>
<td>Udviklingsværktøjer og software fra Microsoft</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er opført i rækkefølge efter bulletin-id og derefter CVE-id. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at få kendskab til sandsynligheden for, at udførelse af kode og denial-of-service udnyttes inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Læs alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering af denne måneds opdateringer. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/security/cc998259.aspx).

I nedenstående artikelserier, refererer "Nyeste softwareversion" til den nyeste version af softwareemner, og "Ældre softwareversioner" refererer til alle ældre, understøttede versioner af softwareemner, der findes i "Berørte programmer" eller "Ikke-berørte programmer" i bulletin-tabellerne.

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Titel på sårbarhed</th>
<th>CVE ID</th>
<th>Vurdering af mulighed for udnyttelse i den nyeste softwareversion</th>
<th>Vurdering af mulighed for udnyttelse i ældre softwareversioner</th>
<th>Vurdering af mulighed for udnyttelse af Denial of Service</th>
<th>Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235999">MS12-001</a></td>
<td>Sårbarhed vedr. omgåelse af Windows Kernel SafeSEH</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0001">CVE-2012-0001</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>Dette er en sårbarhed vedrørende omgåelse af sikkerhed.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229637">MS12-002</a></td>
<td>Sårbarhed vedr. usikker start af eksekverbar fil i Object Packager</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0009">CVE-2012-0009</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=235400">MS12-003</a></td>
<td>Sårbarhed vedr. udvidelse af CSRSS-rettigheder</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0005">CVE-2012-0005</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227487">MS12-004</a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode for MIDI</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0003">CVE-2012-0003</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227487">MS12-004</a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode for Direct Show</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0004">CVE-2012-0004</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=230777">MS12-005</a></td>
<td>Sårbarhed i forbindelse med udførelse af assembly</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0013">CVE-2012-0013</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232510">MS12-006</a></td>
<td>Sårbarhed i SSL- og TLS-protokoller</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3389">CVE-2011-3389</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td>Ikke relevant</td>
<td>Dette er en sårbarhed vedr. offentliggørelse af oplysninger, som er blevet offentliggjort med begrænsede detaljer.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=227561">MS12-007</a></td>
<td>Sårbarhed vedr. omgåelse af AntiXSS Library</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0007">CVE-2012-0007</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td>Ikke relevant</td>
<td>Dette er en sårbarhed vedr. offentliggørelse af oplysninger</td>
</tr>
</tbody>
</table>


## Berørte programmer og downloadplaceringer

Følgende tabel viser bulletinerne efter overordnet softwarekategori og klassifikation.

**Hvordan bruger jeg disse tabeller?**

Brug disse tabeller til at få kendskab til de sikkerhedsopdateringer, du muligvis skal installere. Du bør se alle de anførte softwareprogrammer eller komponenter igennem for at se, om der er nogen sikkerhedsopdateringer vedrørende din installation. Hvis et program eller en komponent findes på listen, findes der hyperlinks til tilgængelige softwareopdateringer, og sårbarhedens omfang også angivet.

**Bemærk\!** Du skal muligvis installere flere sikkerhedsopdateringer for en enkelt sårbarhed. Gennemse hele kolonnen for hvert bulletin-id på listen for at kontrollere, hvilke opdateringer du skal installere ud fra de programmer eller komponenter, der er installeret på dit system.

#### Windows-operativsystemet og dets komponenter

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a142f7ba-4268-4453-a8eb-470213c028ac">Windows Multimedia Library</a>
                    <br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89b23d72-410f-4133-9c14-24eb01e5a732">Windows Multimedia Library</a><br />(KB 2628259)<br />(kun Windows XP Media Center Edition 2005 Service Pack 3)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b168ee8-eb15-4c2c-afb0-e63d62b4a6dc">DirectShow</a><br />(KB 2631813)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feaeda8c-84ee-47be-8c68-736f0e5b1fc7">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cfc38dc2-c4c7-4a44-8e5a-b98bb9bc0396">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1bcb1d1e-9261-4a36-9256-90d3df9bd4fb">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fb0360b1-254c-4ecb-a36a-807cabfec1ab">Windows XP Service Pack 3</a>
                    <br />(KB 2585542)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0928d720-ae88-40d6-b76f-636d67da8526">Windows Multimedia Library</a>
                    <br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13d74cc6-8d8e-45ea-8cdc-c15782f6626b">DirectShow</a><br />(KB 2631813)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46386269-6e37-4710-bfef-cedfe60d881c">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=211827f2-fe6a-4e16-a90c-0cc3b60a722d">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3956db98-88d9-49fc-be51-247b40bfc272">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c687796-4c41-4d17-b738-511d2fbfc126">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afe6b34d-21b1-4dfa-afa6-2c5c2a678e9e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB 2585542)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=986f1156-0190-48c2-9f39-29cacb91f0f9">Windows XP Professional x64 Edition Service Pack 2</a><br />(KB 2638806)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletin </strong>
                    <strong>-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet  </strong>
                    <strong>klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c266dfb-630d-4f32-b2ca-63955279b6a9">Windows Multimedia Library</a>
                    <br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89ae6ed0-537f-421c-b755-ef28691abd88">DirectShow</a><br />(KB 2631813)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9cdfc0fe-8f43-4e13-8a1f-2b48ff9ff472">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8e46267-7988-4fbe-ae94-68b6fdb2e7d9">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39f5f8fb-ee4d-4b7a-9cd7-3d1e9c8abd8c">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c39be84-1eab-4794-b3ed-e529643aca21">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2c503a5-3f15-4a77-9a05-9ea0fbaf4503">Windows Server 2003 Service Pack 2</a>
                    <br />(KB 2585542)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c23e7604-d489-4836-8b54-3b2b3d6a365c">Windows Server 2003 Service Pack 2</a><br />(KB 2638806)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8dd1c882-4ed1-4e47-a017-7d162bd94194">Windows Multimedia Library</a>
                    <br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08be569c-e9d1-4fc5-8670-ebe9da0a2072">DirectShow</a><br />(KB 2631813)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e5783aa-6847-404c-9b75-621fa14ebbb8">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5975b01e-139b-4b9d-a0d5-a87a279bfea1">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e27d85f8-a285-4e95-85a0-0868286cc2b9">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3cf29dfd-239e-4707-92e6-952133c1c1c2">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ad34496-40af-40cb-9f85-5d3c31543211">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB 2585542)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f36e991-4e1a-4b8c-8cfb-e7f20d97cf0b">Windows Server 2003 x64 Edition Service Pack 2</a><br />(KB 2638806)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a9b09d6-7060-47ab-9f76-c3c5acb024e6">Windows Multimedia Library</a>
                    <br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3401ac20-3701-471f-9757-097a9402d761">DirectShow</a><br />(KB 2631813)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdf8208c-d55b-428f-bdd3-26e291dfb08d">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26079c35-4b96-42fc-ad47-138be25a6bf0">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b69bd01d-9925-4ff1-bfeb-b4473631578c">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=623c1c7d-6902-4876-9614-1b6e1ef80831">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=56deb935-9226-49f8-b705-edb3d662d8aa">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(KB 2585542)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2d72cf5a-cca7-4341-b862-017e3f34a3c9">Windows Server 2003 med SP2 til Itanium-baserede systemer</a><br />(KB 2638806)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99d9b9fc-ed37-4a32-a20d-6604a1b9c4ca">Windows Multimedia Library</a>
                    <br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f345e093-336d-4464-b7f8-a14398b62ebf">Windows Media Center TV-pakke til Windows Vista (32-bit versioner)</a>[1]<br />(KB 2628642)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4818059a-52ad-4c2e-9605-4e0f5d9da5ba">DirectShow</a><br />(KB 2631813)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44eeb0a2-ae17-4971-8a7e-e25b260c582c">Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73682d4b-3179-4488-8ba9-94ed68c4896b">Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=038970b6-aeec-4e18-8dfe-887b260a7c87">Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f9269bd6-8c4f-476e-8481-fc0de52a22e6">Windows Vista Service Pack 2</a>
                    <br />(KB 2585542)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44aa8d91-2b30-4191-8965-8aee2b860d50">Windows Multimedia Library</a>
                    <br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=559d028f-9810-4c50-b65d-f567cbb15427">Windows Media Center TV-pakke til Windows Vista (64-bit versioner)</a>[1]<br />(KB 2628642)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13cc2519-860d-4c64-b7f8-8f9c0bdaefcf">DirectShow</a><br />(KB 2631813)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79ceba86-59a1-4138-a5de-8df20ad81b02">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b5c33025-13d9-43d2-a415-a8a4d683a821">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23abeb12-f2fe-43fd-9c4a-4d3d244832f8">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0403c753-d4fa-4e3d-a61b-7f816f5c352b">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB 2585542)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=787e6285-3ba5-4aae-9d8d-e3c1eca3b35d">Windows Multimedia Library</a>*<br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92df13c1-fdf6-4602-acb2-e634a1bcd9da">DirectShow</a>**<br />(KB 2631813)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ab87c6c-5802-4454-bce4-12501e5b816d">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fbf119cf-a8ed-4266-a673-442149992f7c">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d089d9cb-382c-4e64-94c5-69b9864010b1">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>**<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fe2f398-433f-4338-a273-813185b43ea8">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(KB 2585542)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9eff12b2-70a4-452b-b6bc-0d83f2edcf6c">Windows Multimedia Library</a>*<br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ff10d7f-26a6-403a-a4b7-7aff55e2fa16">DirectShow</a>**<br />(KB 2631813)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=726ff17e-ac90-4832-91e7-46f71ad2f868">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8e68f89-27f4-4142-94ca-58f086a98157">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ac8a368-4298-4c1d-9cfd-924d6df563af">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>**<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f54ac30d-8e41-4df9-bd43-db6742a24d4c">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(KB 2585542)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e2edb23-7f4e-4fe4-848c-1d744e0dce9f">Windows Multimedia Library</a>
                    <br />(KB 2598479)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e0394c9-3de4-46f6-ae7f-18d5a555532e">DirectShow</a><br />(KB 2631813)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba2c3d57-1bdd-44f2-9233-86c7ea6f0ddb">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc6491e8-6c3e-43a1-bc56-16c9a2fd2749">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e08b242-2516-4cf6-b38e-35ec2b8b788d">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3979db3b-4961-4df8-84a4-1f26672b127c">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(KB 2585542)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d736daf8-db6d-485f-b0cb-7f2d8c86f9a2">DirectShow</a>
                    <br />(KB 2631813)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ee22036-b7f4-40f5-8f40-a77e8faf48b2">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7422605b-7a02-4161-b7f8-92b3ccffef64">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f433f2c-c61d-461d-af9c-0145af4b72ab">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(KB 2585542)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21b37775-3e7b-462d-8234-7c47d52daef9">DirectShow</a>
                    <br />(KB 2631813)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7444e20c-9821-4c91-9779-2728c537dd6a">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ba46bc7-af7a-445a-84f2-b0c13674409b">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0839fec0-b6a7-4e47-9da3-2caef44a7df4">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB 2585542)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227487">
                      <strong>MS12-004</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235999">
                      <strong>MS12-001</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229637">
                      <strong>MS12-002</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=235400">
                      <strong>MS12-003</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=230777">
                      <strong>MS12-005</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232510">
                      <strong>MS12-006</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1																		</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=355c980d-ec2e-4b2d-a7d4-2e3dbd3a0dde">DirectShow</a>**<br />(KB 2631813)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c73a16d-e9fa-48de-9dca-a6360ce3d029">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=db3a4814-a409-4def-944d-4eaa540b83b0">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>**<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34542a5a-88df-4a07-b1ed-d4c845502cd8">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(KB 2585542)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4b2389e-fd9f-47c7-9afd-4077f5632c21">DirectShow</a>
                    <br />(KB 2631813)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1cc14ee8-f035-4bfc-bf38-33c6b9a2e776">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2101663a-ed3d-4850-b79a-16960ab56b45">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe661936-06e1-45d3-89f6-1093504496a7">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(KB 2585542)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkning til MS1** **2** **-0** **04**

\[1\]Windows Media Center TV-pakken til Windows Vista er kun tilgængelig på OEM-installationer (Original Equipment Manufacturer) af Home Premium- og Ultimate-versioner af Windows Vista som en valgfri komponent. Kunder, som har denne valgfri komponent installeret bør installere alle tilgængelige opdateringer til deres udgave af Windows Vista. I overensstemmelse med de bedste fremgangsmåder anbefaler Microsoft at installere de relevante operativsystemopdateringer (KB 2598479 og KB 2631813) inden installation af Windows Media Center TV-pakkeopdateringen (KB 2628642).

#### Udviklingsværktøjer og software fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Anti-Cross Site Scripting Library</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=227561">
                      <strong>MS12-007</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Anti-Cross Site Scripting Library V3.x og Microsoft Anti-Cross Site Scripting Library V4.0</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3ef05ce-70fe-4f25-9aee-cb7a42a53d11">Microsoft Anti-Cross Site Scripting Library V3.x og Microsoft Anti-Cross Site Scripting Library V4.0</a>
                    [1][2]
                  </td></tr>
              </table>


**Bemærkning til MS1** **2** **-** **0** **07**

\[1\]Dette download opgraderer Microsoft Anti-Cross Site Scripting (AntiXSS) Library til en nyere version af Microsoft Anti-Cross Site Scripting Library, som ikke er berørt af sårbarheden.

\[2\]Denne opgradering er udelukkende tilgængelig fra Microsoft Download Center.

## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

For kunder med Microsoft Office til Mac, kan Microsoft AutoUpdate til Mac hjælpe med til at holde Microsoft-software opdateret. Se [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) for at få flere oplysninger om brug af Microsoft AutoUpdate til Mac.

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Vejledning i registrering og implementering**

Microsoft giver vejledning i registrering og implementering af sikkerhedsopdateringer. Denne vejledning indeholder anbefalinger og oplysninger, som it-fagfolk kan bruge til bedre at forstå, hvordan de skal anvende forskellige værktøjer til registrering og implementering af sikkerhedsopdateringer. Yderligere oplysninger finder du i [Microsoft Knowledge Base-artikel 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) giver administratorer mulighed for at søge på lokale systemer og fjernsystemer efter manglende sikkerhedsopdateringer samt almindelige fejl ved sikkerhedskonfigurationer. Hvis du ønsker yderligere oplysninger om MBSA, kan du besøge webstedet [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Microsoft Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Yderligere oplysninger om, hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).

**System Center Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse opgave, det er at levere og administrere opdateringer af it-systemer på tværs af virksomheden. Med Configuration Manager 2007 kan it-administratorer levere opdateringer af Microsoft-produkter til en række enheder, herunder stationære og bærbare computere, servere og mobile enheder.

Den automatiserede sårbarhedsvurdering i Configuration Manager 2007 opdager behov for opdateringer og rapporterer om anbefalede forholdsregler. Software Update Management i Configuration Manager 2007 er bygget på Microsoft Windows Software Update Services (WSUS), en gennemprøvet opdateringsinfrastruktur, der er kendt af it-administratorer verden over. Se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) for at få flere oplysninger om, hvordan administratorer kan bruge Configuration Manager 2007 til at implementere opdateringer. Yderligere oplysninger om Configuration Manager findes i [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere.

**Bemærk** System Management Server 2003 er uden for generel support fra den 12. januar 2010. Du kan få yderligere oplysninger om produktlivscyklussen på [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig; se det tidligere afsnit, **System** Center Configuration Manager 2007.

Yderligere oplysninger om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsopdateringer, findes i [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Oplysninger om SMS findes på [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Bemærk\!** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til at installere disse opdateringer.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Opdateringer skriver ofte til de samme filer og registreringsdatabaseindstillinger, der er nødvendige for, at dine programmer kan køre. Dette kan udløse inkompatibilitet og forøge den tid, det tager at implementere sikkerhedsopdateringer. Du kan strømline test og validering af Windows-opdateringer mod installerede programmer med de [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponenter, der følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Microsoft Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Opdateringer fra de foregående måneder for Windows Server Update Services.](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) Viser alle nye, reviderede og udgivne opdateringer til Microsoft-produkter udover Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

For at forbedre sikkerhedsbeskyttelsen for kunder giver Microsoft oplysninger om sårbarheder til store leverandører af sikkerhedssoftware før den månedlige udgivelse af sikkerhedsopdateringer. Derefter kan leverandører af sikkerhedssoftware bruge disse oplysninger om sårbarheder til at give opdateret beskyttelse til kunder via deres sikkerhedssoftware eller -enheder, f.eks. antivirus, registreringssystemer til netværksbaseret indtrængen eller forebyggelsessystemer til host-baseret indtrængen. For at afgøre, om aktive beskyttelser er tilgængelige fra leverandører af sikkerhedssoftware, skal du gå ind på websites på aktive beskyttelser, der udbydes af de programpartnere, som er angivet i [Microsoft Active Protections Program (MAPP) Partners](http://go.microsoft.com/fwlink/?linkid=215201).

#### Sikkerhedsstrategier og community

**Strategier til håndtering af opdateringer**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) giver yderligere oplysninger om Microsofts anbefalinger til de bedste fremgangsmåder for anvendelse af sikkerhedsopdateringer.

**Andre sikkerhedsopdateringer**

Opdateringer til andre sikkerhedsproblemer er tilgængelige på følgende placeringer:

  - Der kan hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".
  - Der kan findes opdateringer til forbrugerplatforme på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan hente de sikkerhedsopdateringer, der er gjort tilgængelige på Windows Update denne måned, fra Download Center på Security and Critical Releases ISO CD Image-filer. Yderligere oplysninger finder du i [Microsoft Knowledge Base-artikel 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Lær, hvordan du forbedrer sikkerheden og optimerer din it-infrastruktur, og diskutér sikkerhedsemner med andre it-fagfolk i [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164).

#### Tak til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for at hjælpe os i arbejdet med at beskytte kunderne:

  - Joshua J. Drake fra [Accuvant LABS](http://www.accuvant.com/) for at rapportere et problem beskrevet i MS12-001
  - Parvez Anwar, der arbejder for [Secunia Research](http://secunia.com/) for at have rapporteret et problem, der er beskrevet i MS12-002
  - Kang Wu fra [Shenzhen Jowto Research Dep](http://www.jowto.com) for at have rapporteret et problem, der er beskrevet i MS12-003
  - Shane Garrett fra [IBM Security System's X-Force Research](http://xforce.iss.net/) for at have rapporteret et problem, der er beskrevet i MS12-004
  - Neel Mehta fra [Google Inc.](http://www.google.com/) for at rapportere et problem, der er beskrevet i MS12-004
  - Yorick Koster, der samarbejder med programmet [Beyond Security's SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html), for at rapportere et problem, der er beskrevet i MS12-005
  - Adi Cohen fra [IBM Rational Application Security](http://blog.watchfire.com/) for at rapportere et problem, der er beskrevet i MS12-007

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY (1-866-727-2338). Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger om, hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V 1.0 (10. januar 2012): Oversigt over bulletin offentliggjort.
  - V2.0 (11. januar 2012): For MS12-003, rettet vurdering af mulighed for udnyttelse i den nyeste softwareversion i **Udnyttelsesindeks** for CVE-2012-0005. For MS12-007, revideret for at annoncere genudsendelse af bulletin. Se bulletinen MS12-007 for at få flere oplysninger.
  - V2.1 (27. januar 2012): MS12-004, rettede den samlede klassifikation for opdateringspakken KB2631813 til alle understøttede versioner af Windows XP, Windows Server 2003, Windows Vista og Windows Server 2008. Se bulletinen MS12-004 bulletin for at få flere oplysninger.

*Built at 2014-04-18T01:50:00Z-07:00*

