---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for september 2011
TOCTitle: MS11-SEP
ms:assetid: ms11-sep
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms11-sep(v=Security.10)
ms:contentKeyID: 61224083
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for september 2011

Offentliggjort: 13. september 2011 | Opdateret: 13. september 2011

**Version:** 1.1

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for september 2011.

Med udgivelsen af sikkerhedsbulletiner for september 2011 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 8. september 2011. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 14. september 2011 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få september måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487951). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://go.microsoft.com/fwlink/?linkid=217214)webcasts.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i WINS kan muliggøre udvidelse af rettigheder (2571621)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i WINS (Windows Internet Name Service). Sårbarheden kan muliggøre udvidelse af rettigheder, hvis en bruger skulle modtage en særligt udformet WINS-replikeringspakke på et berørt system, der anvender WINS-tjenesten. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Windows Components kan muliggøre fjernudførelse af kode (2570947)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger åbner en legitim rich text format-fil (.rtf), tekstfil (.txt) eller et Word-dokument (.doc), der er placeret i samme netværksmappe som en særligt udformet DLL-fil (Dynamic Link Library). En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft Excel kan muliggøre fjernudførelse af kode (2587505)</strong><br />
<br />
Denne sikkerhedsopdatering løser fem privat rapporterede sårbarheder i Microsoft Office. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Excel-fil. En hacker, som det lykkes at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Installation og konfiguration af Office File Validation (OFV) for at forhindre åbning af mistænkelige filer, blokerer angrebsvektorerne for udnyttelse af de sårbarheder, der er beskrevet i CVE-2011-1986 og CVE-2011-1987.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft Office kan muliggøre fjernudførelse af kode (2587634)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Office. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Office-fil, eller hvis en bruger åbner en legitim Office-fil, der er placeret i samme netværksmappe som en særligt udformet biblioteksfil. En hacker, som det lykkes at udnytte en af sårbarhederne, vil kunne få de samme brugerrettigheder som den bruger, der er logget på. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft SharePoint kan muliggøre udvidelse af rettigheder (2451858)</strong><br />
<br />
Denne sikkerhedsopdatering løser fem privat rapporterede og en offentliggjort sårbarhed i Microsoft SharePoint og Windows SharePoint Services. De mest alvorlige sårbarheder kan muliggøre udvidelse af rettigheder, hvis en bruger har klikket på en særligt udformet URL eller besøgt et særligt udformet websted. For de mest alvorlige sårbarheder har brugere af Internet Explorer 8 og Internet Explorer 9, som navigerer til et SharePoint-websted i internetzonen, reduceret risiko, fordi XSS-filteret i Internet Explorer 8 og Internet Explorer 9 blokerer angrebet i internetzonen. XSS-filteret i Internet Explorer 8 og Internet Explorer 9 er imidlertid som standard ikke aktiveret i intranetzonen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er opført i rækkefølge efter bulletin-id og derefter CVE-id. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

**Hvordan anvender jeg denne tabel?**  

Brug denne tabel til at få kendskab til sandsynligheden for, at udførelse af kode og denial-of-service udnyttes inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Læs alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering af denne måneds opdateringer. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/security/cc998259.aspx).

I nedenstående artikelserier, refererer "Nyeste softwareversion" til den nyeste version af softwareemner, og "Ældre softwareversioner" refererer til alle ældre, understøttede versioner af softwareemner, der findes i "Berørte programmer" eller "Ikke-berørte programmer" i bulletin-tabellerne.

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Titel på sårbarhed</th>
<th style="border:1px solid black;">CVE ID</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse af kodeudførelse i nyeste softwareversion</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse af kodeudførelse i ældre softwareversioner</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse af Denial of Service</th>
<th style="border:1px solid black;">Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. lokal udvidelse af WINS-rettigheder</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1984">CVE-2011-1984</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. usikker indlæsning af Windows Component-bibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1991">CVE-2011-1991</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Denne sårbarhed er blevet offentliggjort</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. gratis WriteAV i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1986">CVE-2011-1986</a></td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. adgang til array uden for rækkevidde ved indeksering af Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1987">CVE-2011-1987</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. fejl i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1988">CVE-2011-1988</a></td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. parsing af betinget udtryk i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1989">CVE-2011-1989</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. adgang til array uden for rækkevidde ved indeksering af Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1990">CVE-2011-1990</a></td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende usikker indlæsning af Office Component-bibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1980">CVE-2011-1980</a></td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. ikke-initialiseret objektpointer i Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1982">CVE-2011-1982</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. XSS i SharePoint-kalender</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0653">CVE-2011-0653</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. HTML-rensning</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette er en sårbarhed i forbindelse med afsløring af oplysninger<br />
<br />
Denne sårbarhed er blevet offentliggjort</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. scriptindsætning i Editform</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1890">CVE-2011-1890</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. videresendelse af kontaktoplysninger i XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1891">CVE-2011-1891</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. fjernafsløring af filer i SharePoint</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1892">CVE-2011-1892</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette er en sårbarhed i forbindelse med afsløring af oplysninger</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. SharePoint XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1893">CVE-2011-1893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
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
                <tr><th colspan="3" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows XP Service Pack 3</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70f944b0-9bf0-4168-b150-67d2ff68df2d">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b9debed-edbb-43e1-b755-0faf01980289">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e6ac3b2-752e-49a0-84e5-5a8dfe955299">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d44274d2-0401-4fd8-bc4f-c59f6d81c34f">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f9378339-c58e-4e84-9427-85aeb35b0d99">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=935720ee-cee0-42c2-965e-ce1b07e95e1a">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c35c71a8-13b4-47a6-9763-06f6f65327b1">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78c2ac72-da89-42a4-bff9-79551b5d3c4e">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=15840336-4886-4a1b-8c1e-2c535c3938f7">Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e80739b4-89bb-4317-8381-991244a71cb8">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a9039660-3cc2-470d-a0a5-a70f78074495">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05c39ab3-7b57-4147-8913-df5df6005799">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ea78a9b-b1f7-4e94-b69e-c984e1622ae9">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1499d988-fd55-4317-b859-ec170907d547">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e2d2ea9-0af6-4d23-875d-3211722cd62f">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76b99ab2-7e99-4aad-a419-7996bae05c48">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f6d32de-d3ff-4af9-9b26-a4f12581f5fe">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1																		</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f58cf343-946c-4e74-bd9c-40ac934a4986">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8a451bd-3e5c-4845-9941-daabd9418776">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0fdfb1f9-20b3-4d61-8019-33d1003290c8">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1</a>
                    <br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="4" style="border:1px solid black;">Microsoft Office-pakker og komponenter</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225103">
                      <strong>MS11-073</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dee4f3d7-bc4b-47fd-8e3f-9d2b0e82d0f6">Microsoft Excel 2003 Service Pack 3</a>
                    <br />(KB2553072)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7faa2f90-2e64-4dbf-ac93-bb8cffc9b5fe">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB2584052)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2007 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=498ac241-d728-4944-abac-ec8444ca6418">Microsoft Excel 2007 Service Pack 2</a>
                    <br />(KB2553073)[1]<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=df04b9ce-2daa-4b4d-a944-a873075656f9">Microsoft Office 2007 Service Pack 2</a><br />(KB2553089)[1]<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90eef02b-db1f-4fdd-bb1d-408063671e4d">Microsoft Office 2007 Service Pack 2</a><br />(KB2553090)[1]<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34bbee95-0e83-4705-8bfe-02e4fb22f8e7">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2584063)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (32-bit versioner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4612c6e4-ac29-4cc4-9da5-88779ea3643e">Microsoft Excel 2010 og Microsoft Excel 2010 Service Pack 1 (32-bit versioner</a>
                    <br />(KB2553070)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1fd15144-5547-4927-8583-8d9b06819226">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (32-bit versioner)</a><br />(KB2553091)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18840d78-944f-400a-addc-dce7e570a569">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (32-bit versioner)</a><br />(KB2553096)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c8fd04a-9df6-4726-a9bc-811f49665981">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (32-bit versioner)</a>
                    <br />(KB2584066)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (64-bit versioner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d40db27b-1318-4ca7-b44f-c90bb6342109">Microsoft Excel 2010 og Microsoft Excel 2010 Service Pack 1 (64-bit versioner</a>
                    <br />(KB2553070)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f83800aa-6403-4341-afea-d363e54d5831">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (64-bit versioner)</a><br />(KB2553091)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92787e00-6f30-4020-9c1a-70270be5a623">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (64-bit versioner)</a><br />(KB2553096)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85360dc1-99e7-4e3e-be6f-3795e8a8122f">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (64-bit versioner)</a>
                    <br />(KB2584066)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Microsoft Office til Mac</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225103">
                      <strong>MS11-073</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2004 til Mac</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=868f4d9f-3498-4d59-a017-59204553889c">Microsoft Office 2004 til Mac</a>
                    <br />(KB2598782)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2008 til Mac</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa79cfc-6e8a-4d0b-88aa-0d7e05031e44">Microsoft Office 2008 til Mac</a>
                    <br />(KB2598781)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office til Mac 2011</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=535fcf4a-eeb2-44eb-b2a6-9c512509c49d">Microsoft Office til Mac 2011</a>
                    <br />(KB2598783)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Open XML File Format Converter til Mac</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9796588d-238f-4694-9598-1aa8d2becb55">Open XML File Format Converter til Mac</a>
                    <br />(KB2598785)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Microsoft Office Groove og Microsoft SharePoint Workspace</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225103">
                      <strong>MS11-073</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Groove 2007 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ea6192b-55e5-4ca4-8d91-cc768ede8277">Microsoft Office Groove 2007 Service Pack 2</a>
                    <br />(KB2552997)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SharePoint Workspace 2010 og Microsoft SharePoint Workspace 2010 Service Pack 1 (32-bit versioner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6ee7e43-9da9-4b96-abd0-390cfcacb885">Microsoft SharePoint Workspace 2010 og Microsoft SharePoint Workspace 2010 Service Pack 1 (32-bit versioner)</a>
                    <br />(KB2566445)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SharePoint Workspace 2010 og Microsoft SharePoint Workspace 2010 Service Pack 1 (64-bit-versioner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=234efac1-4f09-41f5-90a9-4a3c2e81c05e">Microsoft SharePoint Workspace 2010 og Microsoft SharePoint Workspace 2010 Service Pack 1 (64-bit versioner)</a>
                    <br />(KB2566445)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Øvrigt Microsoft Office-software</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225103">
                      <strong>MS11-073</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Excel Viewer Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f82ca5da-a55a-487c-8170-46a40000c8e3">Microsoft Excel Viewer Service Pack 2</a>
                    <br />(KB2553075)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Compatibility Pack til filformaterne Word, Excel og PowerPoint 2007 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01093f22-06b7-4c9b-bff9-f54ac5d73bf8">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 2</a>
                    <br />(KB2553074)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**Bemærkninger til MS11-072**

\[1\]Til Microsoft Office Excel 2007 Service Pack 2 skal brugerne ud over sikkerhedsopdateringspakken KB2553073, KB2553089 og KB2553090 også installere sikkerhedsopdateringen til Microsoft Office Compatibility Pack til filformaterne Word, Excel og PowerPoint 2007-filformater Service Pack 2 (KB2553074) for at være beskyttet mod de sårbarheder, der er beskrevet i denne bulletin.

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

**Bemærkning til MS11-074**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Microsoft Server-software

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="3" style="border:1px solid black;">Microsoft SharePoint Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bit versioner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd532201-485c-4270-88d3-63bd3f24327e">Microsoft Excel Services</a>
                    <br />(KB2553093)[2]<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad52c341-13ce-4b53-87b4-269cb3f41275">Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (32-bit versioner)</a>
                    <br />(KB2508964)[1]<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd6189c9-ab3b-441f-a901-6ac7f3b202aa">Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (32-bit versioner)</a><br />(KB2553001)[1]<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9601fae-4a80-45cd-a49b-ef441856d7e4">Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (32-bit versioner)</a><br />(KB2553002)[1]<br />(Important)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55b60e2f-ec68-4ccb-803a-5d03add8a1f1">Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (32-bit versioner)</a><br />(KB2553003)[1]<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 Service Pack 2 (64-bit versioner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1086a5b0-e441-4e26-a8d1-924a20121dde">Microsoft Excel Services</a>
                    <br />(KB2553093)[2]<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5e60751-242a-4fdb-9852-6d94050d3d0e">Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (64-bit versioner)</a>
                    <br />(KB2508964)[1]<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1466366-e2ae-498e-b964-135e034e7348">Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (64-bit versioner)</a><br />(KB2553001)[1]<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb788c8d-8383-4e53-ac05-2a7dd9b83e70">Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (64-bit versioner)</a><br />(KB2553002)[1]<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8e1a5bb-a552-45fe-8e81-e05fbfbb57ee">Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (64-bit versioner)</a>[1]<br />(Alvorlig)<br />(KB2553003)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c150328-6a15-4852-a09c-4063142bd946">Microsoft Excel Services</a>
                    <br />(KB2553094)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c17eb04d-cbbc-457e-a424-4ee26b7a9654">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (osrchwfe)</a>
                    <br />(KB2494022)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a80a849-b712-47d4-9def-9395ee54a265">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (osrv)</a><br />(KB2560885)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b84c2bcb-0327-4916-871e-7a5c19b8c41b">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe)</a><br />(KB2560890) <br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1597f295-02a9-4479-9d52-f18f0e83eaba">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmawfe)</a><br />(KB2566456)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6b666a4-a795-441c-9bda-23e2de2e7b05">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (dlc)</a><br />(KB2566954)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57592ce4-5d99-45c2-830f-380d67af8899">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmamui)</a><br />(KB2566958)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd64a635-1e55-4b4d-9718-9b94c31c5625">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (wosrv)</a><br />(KB2566960)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office Forms Server</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet  </strong>
                    <strong>klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Forms Server 2007 Service Pack 2 (32-bit editions)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4c8ad7e-50bd-460e-9678-d8c72c6ee7ab">Microsoft Office Forms Server 2007 Service Pack 2 (32-bit versioner)</a>
                    <br />(KB2553005)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Forms Server 2007 Service Pack 2 (64-bit versioner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7390b526-f411-45a4-8587-8077b473ac17">Microsoft Office Forms Server 2007 Service Pack 2 (64-bit versioner)</a>
                    <br />(KB2553005)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Groove Server</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Groove Data Bridge Server 2007 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5958247e-204e-409c-bdc1-7aff06e854b8">Microsoft Office Groove Data Bridge Server 2007 Service Pack 2</a>
                    <br />(KB2552999)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Groove Management Server 2007 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b5b4caf-6a95-487d-ac17-c4435225af3a">Microsoft Office Groove Management Server 2007 Service Pack 2</a>
                    <br />(KB2552998)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Groove Server 2010 og Microsoft Groove Server 2010 Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71c0f217-5112-4dca-b9aa-46c69f6099e4">Microsoft Groove Server 2010 og Microsoft Groove Server 2010 Service Pack 1</a>
                    <br />(KB2508965)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office Web Apps</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Web Apps 2010 og Microsoft Office Web Apps 2010 Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73d49094-a9cf-407e-8921-1b22fbc30427">Microsoft Excel Web App 2010 og Microsoft Excel Web App 2010 Service Pack 1</a>
                    <br />(KB2553095)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=288a7394-b8d5-4445-bd4c-65bbf4b10eaf">Microsoft Office Web Apps 2010 og Microsoft Office Web Apps 2010 Service Pack 1</a>
                    <br />(KB2566449)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=152ff9f4-d720-41af-8f89-793133ece037">Microsoft Word Web App 2010 og Microsoft Word Web App 2010 Service Pack 1</a><br />(KB2566450)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows SharePoint Services og Microsoft SharePoint Foundation</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Windows SharePoint Services 2.0</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71e32745-cb05-4b87-a447-741ccdac7450">Microsoft Windows SharePoint Services 2.0</a>
                    <br />(KB2494007)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32-bit-versioner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f306cbd-a652-4e77-b394-1a6dc38ba83c">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32-bit versioner)</a>
                    <br />(KB2493987)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64-bit-versioner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3137e4c6-783d-4461-88bd-90da064e3105">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64-bit versioner)</a>
                    <br />(KB2493987)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SharePoint Foundation 2010 og Microsoft SharePoint Foundation 2010 Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0db799e2-896f-464b-8cd5-ecf2014f0588">Microsoft SharePoint Foundation 2010 og Microsoft SharePoint Foundation 2010 Service Pack 1</a>
                    <br />(KB2494001)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til MS11-072**

\[2\]Denne opdatering gælder for servere, hvor Excel Services er installeret, f.eks. standardkonfigurationen af Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 for Internet Sites. Microsoft Office SharePoint Server 2007 Standard omfatter ikke Excel Services.

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

**Bemærkninger til MS11-074**

\[1\]For understøttede versioner af Microsoft Office SharePoint Server 2007 skal brugerne ud over sikkerhedsopdateringspakkerne til Microsoft Office SharePoint 2007 (KB2508964, KB2553001, KB2553002 og KB2553003) installere sikkerhedsopdateringen til Microsoft Windows SharePoint Services 3.0 (KB2493987) for at være beskyttet mod de sårbarheder, der beskrives i denne bulletin.

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

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

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://technet.microsoft.com/en-us/wsus/default.aspx)

**System Center Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse opgave, det er at levere og administrere opdateringer af it-systemer på tværs af virksomheden. Med Configuration Manager 2007 kan it-administratorer levere opdateringer af Microsoft-produkter til en række enheder, herunder stationære og bærbare computere, servere og mobile enheder.

Den automatiserede sårbarhedsvurdering i Configuration Manager 2007 opdager behov for opdateringer og rapporterer om anbefalede forholdsregler. Software Update Management i Configuration Manager 2007 er bygget på Microsoft Windows Software Update Services (WSUS), en gennemprøvet opdateringsinfrastruktur, der er kendt af it-administratorer verden over. Se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) for at få flere oplysninger om, hvordan administratorer kan bruge Configuration Manager 2007 til at implementere opdateringer. Yderligere oplysninger om Configuration Manager findes i [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere.

**Bemærk** System Management Server 2003 er uden for generel support fra 12. januar 2010. Du kan få yderligere oplysninger om produktlivscyklussen på [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig; se det tidligere afsnit, **System** Center Configuration Manager 2007.

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

For at forbedre sikkerhedsbeskyttelsen for kunder giver Microsoft oplysninger om sårbarheder til store leverandører af sikkerhedssoftware før den månedlige udgivelse af sikkerhedsopdateringer. Derefter kan leverandører af sikkerhedssoftware bruge disse oplysninger om sårbarheder til at give opdateret beskyttelse til kunder via deres sikkerhedssoftware eller -enheder, f.eks. antivirus, registreringssystemer til netværksbaseret indtrængen eller forebyggelsessystemer til host-baseret indtrængen. For at afgøre om aktive beskyttelser er tilgængelige fra leverandører af sikkerhedssoftware skal du gå ind på websites på aktive beskyttelser, der udbydes af de programpartnere, som er angivet i [Microsoft Active Protections Program (MAPP)](http://go.microsoft.com/fwlink/?linkid=215201).

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

  - Nicolas Economou fra [Core Security Technologies](http://www.coresecurity.com/) for at have rapporteret et problem beskrevet i MS11-070
  - En anonym forsker, der arbejder for [VeriSign iDefense Labs](http://labs.idefense.com/), for at have rapporteret et problem, der er beskrevet i MS11-072.
  - Sean Larsson fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret et problem, der er beskrevet i MS11-072
  - En anonym forsker, der arbejder for [VeriSign iDefense Labs](http://labs.idefense.com/), for at have rapporteret et problem, der er beskrevet i MS11-072.
  - En anonym forsker, der samarbejder med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS11-072
  - Omair, der samarbejder med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS11-072
  - Parvez Anwar, der arbejder for [Secunia Research](http://secunia.com/) for at have rapporteret et problem, der er beskrevet i MS11-073
  - David Warren hos [CERT/CC](http://www.cert.org/) for at have rapporteret et problem, der er beskrevet i MS11-073
  - Andrew Connell fra [Critical Path Training, LLC](http://www.criticalpathtraining.com/) for at have rapporteret et problem, der er beskrevet i MS11-074
  - David Feldman fra [Raytheon](http://www.raytheon.com/) for at have rapporteret et problem, der er beskrevet i MS11-074
  - Adi Cohen fra [IBM Rational Application Security](http://blog.watchfire.com/) for at have rapporteret et problem, der er beskrevet i MS11-074
  - [Trend Micro](http://www.trendmicro.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS11-074
  - Pedro Jimenez fra [ITT](http://www.itt.com/) for at have rapporteret et problem, der er beskrevet i MS11-074
  - [Seekers løsning til automatisk test af programsikkerhed](http://www.seekersec.com/) for at have rapporteret et problem, der er beskrevet i MS11-074
  - Nicolas Grégoire fra [Agarri](http://www.agarri.fr/) for at have rapporteret et problem, der er beskrevet i MS11-074
  - Jim LaValley fra [LaValley Consulting, LLC](http://www.lavalley.net) for at have rapporteret et problem, der er beskrevet i MS11-074
  - Irene Abezgauz fra [Seeker](http://www.seekersec.com) for at samarbejde med os om en opdatering af gennemgribende beskyttelsesforanstaltninger i MS11-074

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V 1.0 (13. september 2011): Oversigt over bulletin offentliggjort.
  - V 1.1 (13. september 2011): Til MS11-074, tilføjet opdateret link til opdatering af Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe) (KB2560890).

*Built at 2014-04-18T01:50:00Z-07:00*

