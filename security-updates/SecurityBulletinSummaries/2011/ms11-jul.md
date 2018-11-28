---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for juli 2011
TOCTitle: MS11-JUL
ms:assetid: ms11-jul
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms11-jul(v=Security.10)
ms:contentKeyID: 61224077
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for juli 2011

Offentliggjort: 12. juli 2011

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for juli 2011.

Med udgivelsen af sikkerhedsbulletiner for juli 2011 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 7. juli 2011. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 13. juli 2011 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få juli måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032487855&eventcategory=4). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://go.microsoft.com/fwlink/?linkid=217214)webcasts.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=217102">MS11-053</a></td>
<td><strong>En sårbarhed i Bluetooth Stack kan muliggøre fjernudførelse af kode (2566220)</strong> <br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows Bluetooth Stack. Sårbarheden kan tillade fjernudførelse af kode, hvis en hacker sender en serie af særligt udformede Bluetooth-pakker til et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Denne sårbarhed berører kun systemer med Bluetooth-funktionalitet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td><strong>Sårbarheder i Windows-kernetilstandsdrivere kan give mulighed for udvidelse af rettigheder (2555917)</strong> <br />
<br />
Denne sikkerhedsopdatering løser 15 privat rapporterede sårbarheder i Microsoft Windows. De mest alvorlige af disse sårbarheder kan tillade en udvidelse af rettigheder, hvis en hacker er logget på lokalt og har kørt et særligt udformet program. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte disse sårbarheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217465">MS11-056</a></td>
<td><strong>Sårbarheder i Windows Client/Server Run-time Subsystem kan give mulighed for udvidelse af rettigheder (2507938)</strong><br />
<br />
Denne sikkerhedsopdatering løser fem privat rapporterede sårbarheder i Microsoft Windows Client/Server Run-time Subsystem (CSRSS). Sårbarhederne kan tillade udvidelse af rettigheder, hvis en hacker logger på en brugers system og kører et særligt udformet program. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte sårbarhederne.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220276">MS11-055</a></td>
<td><strong>En sårbarhed i Microsoft Visio kan give mulighed for fjernudførelse af kode (2560847)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Microsoft Visio. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger åbner en legitim Visio-fil, der er placeret i samme netværk som en særligt udformet biblioteksfil. En hacker, som det lykkes for at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den bruger, der er logget på. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er opført i rækkefølge efter bulletin-id og derefter CVE-id. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at få kendskab til sandsynligheden for, at udførelse af kode og denial-of-service udnyttes inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Læs alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering af denne måneds opdateringer. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/en-us/security/cc998259.aspx).

I nedenstående artikelserier, refererer "Nyeste softwareversion" til den nyeste version af softwareemner, og "Ældre softwareversioner" refererer til alle ældre, understøttede versioner af softwareemner, der findes i "Berørte programmer" eller "Ikke-berørte programmer" i bulletin-tabellerne.

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Titel på sårbarhed</th>
<th>CVE ID</th>
<th>Vurdering af mulighed for udnyttelse af kodeudførelse i nyeste softwareversion</th>
<th>Vurdering af mulighed for udnyttelse af kodeudførelse i ældre softwareversioner</th>
<th>Vurdering af mulighed for udnyttelse af Denial of Service</th>
<th>Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217102">MS11-053</a></td>
<td>Bluetooth Stack-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1265">CVE-2011-1265</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>Denne sårbarhed påvirker kun klientsystemer (supportede udgivelser af Windows Vista og Windows 7) Bluetooth-funktionalitet</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Use-after-free Win32k-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1874">CVE-2011-1874</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Use-after-free Win32k-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1875">CVE-2011-1875</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Use-after-free Win32k-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1876">CVE-2011-1876</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Inkonsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Use-after-free Win32k-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1877">CVE-2011-1877</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Inkonsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Use-after-free Win32k-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1878">CVE-2011-1878</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Use-after-free Win32k-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1879">CVE-2011-1879</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Sårbarhed vedr. fjernelse af reference til Null Pointer for Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1880">CVE-2011-1880</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Sårbarhed vedr. fjernelse af reference til Null Pointer for Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1881">CVE-2011-1881</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Use-after-free Win32k-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1882">CVE-2011-1882</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Use-after-free Win32k-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1883">CVE-2011-1883</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Use-after-free Win32k-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1884">CVE-2011-1884</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Sårbarhed vedr. fjernelse af reference til Null Pointer for Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1885">CVE-2011-1885</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Sårbarhed vedrørende forkert parameter muliggør afsløring af oplysninger for Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1886">CVE-2011-1886</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td>Permanent</td>
<td>Dette er en sårbarhed i forbindelse med afsløring af oplysninger</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Sårbarhed vedr. fjernelse af reference til Null Pointer for Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1887">CVE-2011-1887</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220172">MS11-054</a></td>
<td>Sårbarhed vedr. fjernelse af reference til Null Pointer for Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1888">CVE-2011-1888</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=220276">MS11-055</a></td>
<td>Sårbarhed vedrørende usikker indlæsning af Microsoft Visio-bibliotek</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3148">CVE-2010-3148</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>Denne sårbarhed er blevet offentliggjort</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217465">MS11-056</a></td>
<td>CSRSS Local EOP AllocConsole sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1281">CVE-2011-1281</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217465">MS11-056</a></td>
<td>CSRSS Local EOP SrvSetConsoleLocalEUDC sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1282">CVE-2011-1282</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217465">MS11-056</a></td>
<td>CSRSS Local EOP SrvSetConsoleNumberOfCommand sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1283">CVE-2011-1283</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217465">MS11-056</a></td>
<td>CSRSS Local EOP SrvWriteConsoleOutput sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1284">CVE-2011-1284</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217465">MS11-056</a></td>
<td>CSRSS Local EOP SrvWriteConsoleOutputString sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1870">CVE-2011-1870</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
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
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="4">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217102">
                      <strong>MS11-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=220172">
                      <strong>MS11-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217465">
                      <strong>MS11-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7a47370-f415-46ea-9a82-a943f743c8b6">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=425c705e-94f2-4fa6-9df2-dc71897215fa">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=db89d88f-d0d4-4ed6-8589-bf27557c0304">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c389fa20-677e-49b6-af44-781e5522d08b">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="4">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217102">
                      <strong>MS11-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=220172">
                      <strong>MS11-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217465">
                      <strong>MS11-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a26a437-a705-4d48-8389-50f159a39891">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dff4c67a-8c8b-4d7d-84c7-57429becf0ff">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95393f89-0b05-4243-95ed-17bcdad24bfb">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1615a995-9a04-440a-ae52-5917738f0ecb">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b094bdb-4150-44f2-a638-afd5f41b00a3">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a81c011d-eeea-4383-9efb-df70515ab357">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="4">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217102">
                      <strong>MS11-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=220172">
                      <strong>MS11-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217465">
                      <strong>MS11-056</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6bff74ac-45f3-4585-92da-316921b458fa">Windows Vista Service Pack 1</a>
                    [1]
                    <br />(KB2561109)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1e5aa7d-5f38-4ce2-9575-4b4cb7520160">Windows Vista Service Pack 2</a><br />(KB2532531)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1fe1e53-34d5-497e-8ba2-50caa8dc1158">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a5e192af-dae5-47ef-a9d0-f761a8caa974">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=849d2694-c8b3-4670-8203-912661bccabf">Windows Vista x64 Edition Service Pack 1</a>
                    [1]
                    <br />(KB2561109)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4287eeb4-ab29-4727-83f2-260d838b44d4">Windows Vista x64 Edition Service Pack 2</a><br />(KB2532531)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7bc0a285-cc32-4c6b-abee-d92130d459b7">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1007f5d3-9be1-4f03-a3f0-12ddb555653c">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="4">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217102">
                      <strong>MS11-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=220172">
                      <strong>MS11-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217465">
                      <strong>MS11-056</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b88d0471-4427-4835-9446-db71116481f0">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=36e3dbaf-36f5-4c74-8f11-ecbef46f58e1">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3df6184-3e3c-4949-a1ee-293ec68f8149">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b43d2ab5-e281-4c6b-bb37-1f1b5d86ac82">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e021d69-7f0c-457f-af86-07e760d8f421">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b70209f2-1c51-45af-b3c4-3473aebcdb35">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="4">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217102">
                      <strong>MS11-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=220172">
                      <strong>MS11-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217465">
                      <strong>MS11-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
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
                  </td></tr>
                <tr><td>Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f811b75-c3ff-411a-aaa9-126dce34cc01">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(KB2532531)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41db1b2f-f862-43bb-89bc-4b97737e5cb9">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac3b435c-8caf-40cc-8f13-b52261b3b9e6">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90b2da71-18f9-46ee-9e3d-b08620ca06aa">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2532531)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=211abdc6-40c7-4bfc-8c2d-be72981f311e">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=64e5f889-fa46-4884-9b22-3ba4e2fba1b9">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="4">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217102">
                      <strong>MS11-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=220172">
                      <strong>MS11-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=217465">
                      <strong>MS11-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1																		</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f54e498-3825-407d-a036-1900a65d34f1">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b99a40cf-8a31-43d9-bd0b-a458a533068b">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7ae39e8-1154-4a13-8598-29d4a6358762">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=784efc20-3a41-42ab-b48d-51fd59d71523">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Pack 1</a>
                    <br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkning til MS11-053**

\[1\]Windows Vista Service Pack 1 berøres kun, når den valgfri Windows Vista Feature Pack for Wireless er installeret.

#### Microsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Office-pakker og komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=220276">
                      <strong>MS11-055</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visio 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c7b2a5b-4aa6-4006-90bf-89f8b2b7becd">Microsoft Visio 2003 Service Pack 3</a>
                    <br />(KB2493523)<br />(Alvorlig)</td></tr>
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

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://technet.microsoft.com/en-us/wsus/default.aspx)

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

  - Tarjei Mandt fra [Norman](http://www.norman.com) for at have rapporteret 14 problemer, der er beskrevet i ms11-054
  - Mr. Liang Yin, Professor. Sihan Qing og Weiping Wen, og Mr. Husheng Zhou, [Department of Information Security, Beijing University](http://www.ss.pku.edu.cn/en/), for at have rapporteret et problem i ms11-054
  - Matthew 'j00ru' Jurczyk fra [Hispasec](http://www.hispasec.com/)[Virustotal](http://www.virustotal.com/) for at have rapporteret fem problemer, der er beskrevet i ms11-056

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (12. juli 2011): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

