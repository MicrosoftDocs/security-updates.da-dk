---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for marts 2011
TOCTitle: MS11-MAR
ms:assetid: ms11-mar
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms11-mar(v=Security.10)
ms:contentKeyID: 61224079
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for marts 2011

Offentliggjort: 8. marts 2011

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for marts 2011.

Med udgivelsen af sikkerhedsbulletiner for marts 2011 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 3. marts 2011. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 9. marts 2011 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få marts måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032455049&eventcategory=4). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

## Resuméer

Følgende tabel viser sikkerhedsbulletinerne for denne måned efter vigtighed.

Oplysninger om berørte programmer kan fås i næste afsnit, **Berørte programmer og downloadplaceringer**.

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Bulletinens titel og resumé</th>
<th style="border:1px solid black;">Klassifikation og sårbarhedens omfang</th>
<th style="border:1px solid black;">Krav om genstart</th>
<th style="border:1px solid black;">Berørte programmer</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207841">MS11-015</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Windows Media kan give mulighed for fjernudførelse af kode (2510030)</strong><br />
<br />
Denne sikkerhedsopdatering løser én offentliggjort sårbarhed i DirectShow og en privat rapporteret sårbarhed i Windows Media Player og Windows Media Center. De mere alvorlige af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Microsoft Digital Video Recording-fil (.dvr-ms). I alle tilfælde kan brugeren ikke tvinges til at åbne filen; for at angrebet skal kunne lykkes, skal brugeren bringes til dette af egen fri vilje.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207892">MS11-017</a></td>
<td style="border:1px solid black;"><strong>Sårbarhed i Fjernskrivebordsklienten kan give mulighed for fjernudførelse af kode (2508062)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows-Fjernskrivebordsklient. Sårbarheden kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en legitim Fjernskrivebordskonfigurationsfil (.rdp), der er placeret i den samme netværksmappe som en særligt udformet biblioteksfil. For at et angreb skal lykkes, skal en bruger besøge en fjernplacering på et filsystem, der ikke er tillid til, eller en WebDAV-deling og åbne et dokument fra denne placering, der derefter indlæses med et sårbart program.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=209774">MS11-016</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft Groove kan muliggøre fjernudførelse af kode (2494047)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Microsoft Groove som kan muliggøre fjernudførelse af kode, hvis en bruger åbner en legitim Groove-relateret fil, der er placeret i samme netværk som en særligt udformet biblioteksfil. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er anført i faldende rækkefølge i forhold til CVE ID's vurderingsniveau for udnyttelse. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

**Hvordan anvender jeg denne tabel?**  

Brug denne tabel til at få kendskab til sandsynligheden for, at fungerende exploit-kode udgives inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Du bør gennemse alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Titel på sårbarhed</th>
<th style="border:1px solid black;">CVE ID</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse</th>
<th style="border:1px solid black;">Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207892">MS11-017</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende usikker indlæsning af Fjernskrivebordsbibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0029">CVE-2011-0029</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207841">MS11-015</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende usikker indlæsning af DirectShow-bibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0032">CVE-2011-0032</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed er blevet offentliggjort, og PoC-kode er muligvis tilgængelig</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207841">MS11-015</a></td>
<td style="border:1px solid black;">DVR-MS-sårbarhed</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0042">CVE-2011-0042</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=209774">MS11-016</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende usikker indlæsning af Microsoft Groove-bibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0108">CVE-2011-0108</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed er blevet offentliggjort, og PoC-kode er muligvis tilgængelig</strong></td>
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
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="3" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207841">
                      <strong>MS11-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207892">
                      <strong>MS11-017</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8284bfa-ed6c-4647-9fb0-588e53173775">Kun Windows XP Service Pack 3</a>
                    [1]
                    <br />(KB2479943)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1be30de-7e88-467d-aee2-68f88e6a7355">Windows XP Media Center Edition 2005 Service Pack 3</a><br />(KB2502898)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1aed6080-feab-4b5e-9d26-6a3f4b92434d">Forbindelse til Fjernskrivebord 5.2-klient</a>
                    <br />(KB2483618)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d67e4d8c-aeb9-45e6-9555-7456c5540475">Forbindelse til Fjernskrivebord 6.1-klient</a><br />(KB2481109) <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a01992e-c9a1-4dc9-a3ef-7410b81f17e6">Forbindelse til Fjernskrivebord 7.0-klient</a><br />(KB2483614) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5270b5d3-3720-42a2-a8cf-67089c0cc658">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2479943) <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6d4539ef-4a05-4c7d-9489-436f7b7a3ebe">Forbindelse til Fjernskrivebord 6.0-klient</a>
                    [1]
                    <br />(KB2481109) <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207841">
                      <strong>MS11-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207892">
                      <strong>MS11-017</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=641d5d12-0790-4551-831a-e78febad17a7">Forbindelse til Fjernskrivebord 6.0-klient</a>
                    [1]
                    <br />(KB2481109) <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6fec0d06-042d-4e55-9843-009edd7d26ce">Forbindelse til Fjernskrivebord 6.0-klient-MUI (Multilingual User Interface )</a>[2]<br />(KB2483619) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78dbb9cf-8a18-4f0a-8edf-f1ce0c993c63">Forbindelse til Fjernskrivebord 6.0-klient</a>
                    [1]
                    <br />(KB2481109) <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207841">
                      <strong>MS11-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207892">
                      <strong>MS11-017</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f9f1dde2-2219-4bf1-a497-edd011577b96">Windows Vista Service Pack 2 og Windows Vista Service Pack 2</a>
                    [2]
                    <br />(KB2479943)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1bc240b3-1938-4350-b26f-67b81a79f8a0">Windows Media Center TV-pakke til Windows Vista (32-bit versioner</a>)[3]<br />(KB2494132) <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e3ea7690-386b-4cdf-889f-b3914921c56f">Forbindelse til Fjernskrivebord 6.1-klient</a>
                    <br />(KB2481109) <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c30f67e-7c31-4553-ba3e-e056df1bf8eb">Forbindelse til Fjernskrivebord 7.0-klient</a><br />(KB2483614) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e11d00df-d1cf-4a33-a1be-6721cdff5995">Windows Vista x64 Edition Service Pack 2 og Windows Vista x64 Edition Service Pack 2</a>
                    [2]
                    <br />(KB2479943) <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd4c5a80-db24-4696-a248-1286c3b9f550">Windows Media Center TV-pakke til Windows Vista (64-bit versioner</a>)[3]<br />(KB2494132) <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5735bed6-0e3d-46a4-85d0-14ec34a82edd">Forbindelse til Fjernskrivebord 6.1-klient</a>
                    <br />(KB2481109) <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8025482b-f58f-4f5a-a133-5563c65b21f6">Forbindelse til Fjernskrivebord 7.0-klient</a><br />(KB2483614) <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207841">
                      <strong>MS11-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207892">
                      <strong>MS11-017</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31d790c9-92f9-4a2b-800b-8e8d2b570bb9">Forbindelse til Fjernskrivebord 6.1-klient</a>**<br />(KB2481109) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b0a8eb5-4bc2-4054-b952-58aa645afcf5">Forbindelse til Fjernskrivebord 6.1-klient</a>**<br />(KB2481109) <br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25da7e00-745d-4d98-9dd8-52a8a4340404">Forbindelse til Fjernskrivebord 6.1-klient</a>
                    <br />(KB2481109) <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207841">
                      <strong>MS11-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207892">
                      <strong>MS11-017</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1be77daa-29b1-4dae-a87f-2cb8f7e6a305">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(KB2479943) <br />(Kritisk)</td><td style="border:1px solid black;">Kun Windows 7 til 32-bit-systemer:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0768a5f4-da28-4b2e-8aff-d68f890df3e6">Forbindelse til Fjernskrivebord 7.0-klient</a><br />(KB2483614) <br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=56fb24ce-65c7-4573-b613-e424ccc1a3a6">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2479943) <br />(Kritisk)</td><td style="border:1px solid black;">Kun Windows 7 til x64-baserede systemer:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=935adb10-1e7e-4501-b543-8247b88f6d18">Forbindelse til Fjernskrivebord 7.0-klient</a><br />(KB2483614) <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207841">
                      <strong>MS11-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207892">
                      <strong>MS11-017</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1																		</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f45658a-1db8-4ef5-b840-4d0180d4d90e">Windows Server 2008 R2 til x64-baserede systemer  og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>**<br />(KB2479943) <br />(Alvorlig)</td><td style="border:1px solid black;">Kun Windows Server 2008 R2 til x64-baserede systemer:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3fcb2e11-591e-484a-a992-2f1d563e6d17">Forbindelse til Fjernskrivebord 7.0-klient</a>**<br />(KB2483614) <br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 til Itanium-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c29b6487-78f0-421c-810c-c5e45d6a2352">Forbindelse til Fjernskrivebord 7.0-klient</a>
                    <br />(KB2483614) <br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til Windows Server 2008 og Windows Server 2008 R2**

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkninger til MS11-015**

\[1\]Gælder alle versioner undtagen Windows XP Home Edition Service Pack 3 og Windows XP Tablet PC Edition Service Pack 3, som ikke påvirkes.

\[2\]Se note \[3\] nedenfor om Windows Media Center TV-pakke til Windows Vista.

\[3\]Windows Media Center TV-pakken til Windows Vista er kun tilgængelig på OEM-installationer (Original Equipment Manufacturer) af Home Premium- og Ultimate-versioner af Windows Vista som en valgfri komponent. Kunder, som har denne valgfri komponent installeret på deres systemer, bør installere begge tilgængelige opdateringer. I overensstemmelse med de bedste fremgangsmåder anbefaler Microsoft at installere operativsystemet (KB2479943) inden installation af Windows Media Center TV-pakkeopdateringen (KB2494132).

**Bemærkninger til MS11-017**

\[1\]Denne download opgraderer Forbindelse til Fjernskrivebord 6.0-klienten til en ikke-berørt version af Forbindelse til Fjernskrivebord 6.1-klienten.

\[2\]Denne download opgraderer Forbindelse til Fjernskrivebord 6.0-klient-MUI (Multilingual User Interface) til en ikke-berørt version af Forbindelse til Fjernskrivebord 6.1-klient-MUI (Multilingual User Interface).

#### Microsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Office-programmer</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=209774">
                      <strong>MS11-016</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Groove 2007</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3981ab53-1082-4155-9000-11d8a976ff33">Microsoft Groove 2007 Service Pack 2</a>
                    <br />(KB2494047)<br />(Alvorlig)</td></tr>
              </table>


## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

For kunder med Microsoft Office til Mac, kan Microsoft AutoUpdate til Mac hjælpe med til at holde Microsoft-software opdateret. Se [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) for at få flere oplysninger om brug af Microsoft AutoUpdate til Mac

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Vejledning i registrering og implementering**

Microsoft giver vejledning i registrering og implementering af sikkerhedsopdateringer. Denne vejledning indeholder anbefalinger og oplysninger, som it-fagfolk kan bruge til bedre at forstå, hvordan de skal anvende forskellige værktøjer til registrering og implementering af sikkerhedsopdateringer. Yderligere oplysninger finder du i [Microsoft Knowledge Base-artiklen 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) giver administratorer mulighed for at søge på lokale systemer og fjernsystemer efter manglende sikkerhedsopdateringer samt almindelige fejl ved sikkerhedskonfigurationer. Hvis du ønsker yderligere oplysninger om MBSA, kan du besøge webstedet [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Microsoft Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

**System Center Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse opgave, det er at levere og administrere opdateringer af it-systemer på tværs af virksomheden. Med Configuration Manager 2007 kan it-administratorer levere opdateringer af Microsoft-produkter til en række enheder, herunder stationære og bærbare computere, servere og mobile enheder.

Den automatiserede sårbarhedsvurdering i Configuration Manager 2007 opdager behov for opdateringer og rapporterer om anbefalede forholdsregler. Software Update Management i Configuration Manager 2007 er bygget på Microsoft Windows Software Update Services (WSUS), en gennemprøvet opdateringsinfrastruktur, der er kendt af it-administratorer verden over. Se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) for at få flere oplysninger om, hvordan administratorer kan bruge Configuration Manager 2007 til at implementere opdateringer. Yderligere oplysninger om Configuration Manager findes i [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere.

**Bemærk** System Management Server 2003 er uden for generel support fra 12. januar 2010. Du kan få yderligere oplysninger om produktlivscyklussen på [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig; se det tidligere afsnit, **System Center Configuration Manager 2007**.

Yderligere oplysninger om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsopdateringer, findes i [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Oplysninger om SMS findes på [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Bemærk** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til at installere disse opdateringer.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Opdateringer skriver ofte til de samme filer og registreringsdatabaseindstillinger, der er nødvendige for, at dine programmer kan køre. Dette kan udløse inkompatibilitet og forøge den tid, det tager at implementere sikkerhedsopdateringer. Du kan strømline test og validering af Windows-opdateringer mod installerede programmer med de [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponenter, der følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Microsoft Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Opdateringer fra de foregående måneder for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Viser alle nye, reviderede og udgivne opdateringer til Microsoft-produkter udover Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

For at forbedre sikkerhedsbeskyttelsen for kunder giver Microsoft oplysninger om sårbarheder til store leverandører af sikkerhedssoftware før den månedlige udgivelse af sikkerhedsopdateringer. Derefter kan leverandører af sikkerhedssoftware bruge disse oplysninger om sårbarheder til at give opdateret beskyttelse til kunder via deres sikkerhedssoftware eller -enheder, f.eks. antivirus, registreringssystemer til netværksbaseret indtrængen eller forebyggelsessystemer til host-baseret indtrængen. For at afgøre om aktive beskyttelser er tilgængelige fra leverandører af sikkerhedssoftware skal du gå ind på websites på aktive beskyttelser, der udbydes af de programpartnere, som er angivet i [Microsoft Active Protections Program (MAPP)](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

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

  - Matthew Watchinski fra [Sourcefire VRT](http://www.sourcefire.com/services/sf_vrt.html) for at rapportere et problem beskrevet i MS11-015
  - HD Moore fra [Rapid 7](http://www.rapid7.com/) for at rapportere et problem beskrevet i MS11-016
  - Eyal Gruner fra [Versafe Anti Fraud](http://www.versafe-login.com/) for at rapportere et problem beskrevet i MS11-017

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (8. marts 2011): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

