---
title: Oversigt over sikkerhedsbulletiner fra Microsoft for august 2011
TOCTitle: MS11-AUG
ms:assetid: ms11-aug
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms11-aug(v=Security.10)
ms:contentKeyID: 61224073
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsbulletiner fra Microsoft for august 2011

Offentliggjort: 9. august 2011 | Opdateret: 26. oktober 2011

**Version:** 1.2

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for august 2011.

Med udgivelsen af sikkerhedsbulletiner for august 2011 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 4. august 2011. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 10. august 2011 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få august måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487857). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og webcasts](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td><strong>Samlet sikkerhedsopdatering til Internet Explorer (2559049)</strong><br />
<br />
Denne kritiske sikkerhedsopdatering løser fem privat rapporterede sårbarheder og to offentliggjorte sårbarheder i Internet Explorer. De mest alvorlige sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside via Internet Explorer. En hacker, som det lykkes at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td><strong>Sårbarheder i DNS-serveren kan give mulighed for fjernudførelse af kode (2562485)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Windows DNS-server. De mest alvorlige af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en hacker registrerer et domæne, opretter en NAPTR DNS-ressourcepost, og derefter sender en særligt udformet NAPTR-forespørgsel til DNS-serveren. Servere, som ikke har DNS-rollen aktiveret, er ikke i fare.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td><strong>Sårbarhed i Microsoft Data Access Components kan give mulighed for fjernudførelse af kode (2560656)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger åbner en legitim Excel-fil (f.eks. en .xlsx-fil), der er placeret i samme netværk som en særligt udformet biblioteksfil. En hacker, som det lykkes for at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den bruger, der er logget på. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td><strong>Sårbarheder i Microsoft Visio kan give mulighed for fjernudførelse af kode (2560978)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Windows. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Visio-fil. En hacker, som det lykkes for at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den bruger, der er logget på. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td><strong>En sårbarhed i Remote Web Access kan muliggøre udvidelse af rettigheder (2546250)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Remote Desktop Web Access. Sårbarheden er en sårbarhed over for angreb med scripts fra et andet websted (XSS), der kan give mulighed for udvidelse af rettigheder, hvilket sætter en hacker i stand til at udføre vilkårlige kommandoer på webstedet i ofrets kontekst. XSS-filteret i Internet Explorer 8 og Internet Explorer 9 beskytter brugerne mod dette angreb, når de navigerer til en Remote Desktop Web Access-server i internetzonen. XSS-filteret i Internet Explorer 8 og Internet Explorer 9 er som standard ikke aktiveret i intranetzonen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td><strong>En sårbarhed i Remote Access Service NDISTAPI Driver kan tillade udvidelse af rettigheder</strong> <strong>(2566454)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i alle understøttede udgaver af Windows XP og Windows Server 2003. Denne sikkerhedsopdatering er klassificeret som Alvorlig for alle understøttede versioner af Windows XP og Windows Server 2003. Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er ikke berørt af sårbarheden.<br />
<br />
Sårbarheden kan give mulighed for udvidelse af rettigheder, hvis en hacker logger på et berørt system og kører et særligt udformet program, som er designet til at udnytte sårbarheden og tage fuld kontrol over det berørte system. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td><strong>Sårbarhed i Windows Client/Server Run-time Subsystem kan give mulighed for udvidelse af rettigheder (2567680)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan give mulighed for udvidelse af rettigheder, hvis en hacker logger på et berørt system og kører et særligt udformet program, som er designet til at sende en enhedshændelsesbesked til en proces med højere integritet. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td><strong>Sårbarheder i TCP/IP-stakken kan give mulighed for denial-of-service (2563894)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Windows. Sårbarhederne kan muliggøre Denial-of-Service, hvis en hacker sender sekvens af særligt udformede ICMP-beskeder (Internet Control Message Protocol) til et målsystem eller sender en særligt udforme URL-forespørgsel til en server, som behandler webindhold og har den URL-baserede funktion QoS (Quality of Service) aktiveret.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial of Service</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td><strong>En sårbarhed i Remote Desktop Protocol kan give mulighed for denial-of-service (2570222)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Remote Desktop Protocol. Sårbarheden kan muliggøre Denial-of-Service, hvis et berørt system har modtaget en sekvens af særligt udformede RDP-pakker. Microsoft har også modtaget rapporter om begrænsede, målrettede angreb, der udnytter en sårbarhed. Remote Desktop Protocol (RDP) er som standard ikke aktiveret på noget Windows-operativsystem.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial of Service</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td><strong>En sårbarhed i Microsoft Chart Control kan tillade offentliggørelse af oplysninger (2567943)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i ASP.NET Chart-objekter. Sårbarheden kan tillade offentliggørelse af oplysninger, hvis en hacker har sendt en særligt udformet GET-forespørgsel til en berørt server, der hoster Chart-objekterne. Bemærk, at denne sårbarhed ikke gør det muligt for en hacker at foretage fjernudførelse af kode eller direkte at forbedre sine brugerrettigheder, men den kan bruges til at indhente oplysninger, som derefter kan bruges til at sætte det berørte system yderligere i fare. Kun webprogrammer, der anvender Microsoft Chart Control, er berørt af dette problem. Standardinstallationer af .NET Framework bliver ikke påvirket.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Afsløring af oplysninger</td>
<td>Kan kræve genstart</td>
<td>Microsoft .NET Framework,<br />
Microsoft-udviklingsværktøjer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td><strong>En sårbarhed i Microsoft Report Viewer kan tillade offentliggørelse af oplysninger (2578230)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Report Viewer. Sårbarheden kan tillade offentliggørelse af oplysninger, hvis en bruger åbner en særligt udformet webside. En hacker kan imidlertid ikke tvinge en bruger til at besøge et webstedet. I stedet er hackeren nødt til at overbevise en bruger om at besøge webstedet, typisk ved at få vedkommende til at klikke på et link i en e-mail eller onlinebesked, som fører brugeren til hackerens websted.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Afsløring af oplysninger</td>
<td>Kan kræve genstart</td>
<td>Microsoft-udviklingsværktøjer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223578">MS11-068</a></td>
<td><strong>En sårbarhed i Windows Kernel kan muliggøre Denial-of-Service (2556532)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre Denial-of-Service, hvis en bruger besøger et netværksshare (eller besøger et netværk, der peger på en netværksshare), som indeholder en særligt fremstillet fil. En hacker kan imidlertid ikke tvinge en bruger til at besøge et sådant netværksshare eller websted. I stedet er hackeren nødt til at overbevise en bruger om at gøre det, typisk ved at få brugeren til at klikke på et link i en e-mail eller onlinebesked.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderate</a><br />
Denial of Service</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221537">MS11-069</a></td>
<td><strong>En sårbarhed i .NET Framework kan muliggøre offentliggørelse af oplysninger (2567951)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft NET Framework. Sårbarheden kan tillade offentliggørelse af oplysninger, hvis en bruger åbner en særligt udformet webside med en webbrowser, som kan køre XBAP'er (XAML Browser Applications). I et webbaseret angrebsscenarie kan hackeren hoste et websted, der indeholder en webside, som bruges til at udnytte denne sårbarhed. Dertil kommer, at kompromitterede websteder og websteder, der accepterer eller er vært for indhold leveret af brugerne eller reklamer, kan indeholde særligt udformet indhold, som kan udnytte sårbarheden. En hacker kan dog aldrig tvinge brugere til at besøge disse websteder. I stedet er hackeren nødt til at overtale brugerne til at besøge webstedet, typisk ved at få dem til at klikke på et link i en e-mail eller i en onlinemeddelelse, som fører brugerne til hackerens websted. Denne sårbarhed kan også bruges af Windows .NET-programmer til at omgå CAS-restriktioner (Code Access Security).</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderate</a><br />
Afsløring af oplysninger</td>
<td>Kan kræve genstart</td>
<td>Microsoft .NET Framework</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sårbarhed vedr. åben race condition i Windows</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1257">CVE-2011-1257</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sårbarhed vedr. offentliggørelse af informationer i forb. med hændelseshåndtering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1960">CVE-2011-1960</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td>Ikke relevant</td>
<td>Dette er en sårbarhed i forbindelse med afsløring af oplysninger</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sårbarhed vedr. fjernudførelse af kode i forb. med Telnet-håndtering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1961">CVE-2011-1961</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sårbarhed vedr. defekt hukommelse i XSLT</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1963">CVE-2011-1963</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Style-objekt</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1964">CVE-2011-1964</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td>Sårbarhed vedr. DNS NAPTR-forespørgsel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1966">CVE-2011-1966</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td>Sårbarhed vedr. defekt, ikke-initialiseret DNS-hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1970">CVE-2011-1970</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td>Permanent</td>
<td>Dette er en Denial of Service-sårbarhed</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td>Sårbarhed vedr. usikker indlæsning af bibliotek i Data Access Components</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1975">CVE-2011-1975</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Er ikke berørt</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td>Sårbarhed vedr. Release RCE for pStream</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1972">CVE-2011-1972</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td>Sårbarhed vedr. Move Around the Block RCE</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1979">CVE-2011-1979</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td>Sårbarhed i Remote Desktop Web Access</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1263">CVE-2011-1263</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Er ikke berørt</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td>Sårbarhed vedr. udvidelse af NDISTAPI-rettigheder</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1974">CVE-2011-1974</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td>Sårbarhed i CSRSS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1967">CVE-2011-1967</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td>Sårbarhed vedr. ICMP Denial of Service</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1871">CVE-2011-1871</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td>Permanent</td>
<td>Dette er en Denial of Service-sårbarhed</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td>Sårbarhed vedr. TCP/IP QOS Denial of Service</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1965">CVE-2011-1965</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td>Er ikke berørt</td>
<td>Permanent</td>
<td>Dette er en Denial of Service-sårbarhed</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td>Sårbarhed vedr. Remote Desktop Protocol</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1968">CVE-2011-1968</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td>Permanent</td>
<td>Der rapporteres begrænsede målrettede angreb i forb. med denne sårbarhed<br />
<br />
Dette er en Denial of Service-sårbarhed</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td>Sårbarhed vedr. offentliggørelse af informationer i Chart Control</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1977">CVE-2011-1977</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td>Er ikke berørt</td>
<td>Ikke relevant</td>
<td>Dette er en sårbarhed i forbindelse med afsløring af oplysninger</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td>Sårbarhed vedr. Report Viewer Controls XSS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1976">CVE-2011-1976</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende exploit-kode usandsynlig</td>
<td>Ikke relevant</td>
<td>Dette er en sårbarhed i forbindelse med afsløring af oplysninger</td>
</tr>
</tbody>
</table>


## Berørte programmer og downloadplaceringer

Følgende tabel viser bulletinerne efter overordnet softwarekategori og klassifikation.

**Hvordan bruger jeg disse tabeller?**

Brug disse tabeller til at få kendskab til de sikkerhedsopdateringer, du muligvis skal installere. Du bør se alle de anførte softwareprogrammer eller komponenter igennem for at se, om der er nogen sikkerhedsopdateringer vedrørende din installation. Hvis et program eller en komponent findes på listen, findes der hyperlinks til tilgængelige softwareopdateringer, og sårbarhedens omfang også angivet.

**Bemærk\!** Du skal muligvis installere flere sikkerhedsopdateringer for en enkelt sårbarhed. Gennemse hele kolonnen for hvert bulletin-id på listen for at kontrollere, hvilke opdateringer du skal installere ud fra de programmer eller komponenter, der er installeret på dit system.

#### Windows-operativsystemet og dets komponenter

**Tabel 1**

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
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90312c78-1fbd-4143-b2e6-ae5c48af6f57">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a771c93b-55a4-456f-a315-d0d1f2696960">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5feb8ed7-99d2-4dd6-986f-57a7fd0c6f19">Internet Explorer 8</a><br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6bc1f0ac-223d-4b0b-86cd-2ba3863955c4">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0231c103-c0cb-4705-9d92-5356b8cbb265">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23d77f3b-13f8-49f3-9c3c-27ad217cd59e">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=acb14d82-a801-4ec7-84cc-9f131009ebcb">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=272c813b-bd39-4e63-9fa7-c5b8ed0b08d7">Internet Explorer 8</a><br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5ee6787-408d-4870-af70-9338158b161b">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09276f6e-e3f4-4b7e-996e-4ec376c103e1">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
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
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26b5fb48-346a-49f1-840f-03f218a41c20">Internet Explorer 6</a>
                    <br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=042552ad-f46a-4bfc-9e5c-58f095eba1de">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=648596fc-fd97-438a-97be-d5d590f1c561">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2d4aa38-9241-465d-8d65-aba73e936d0f">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8de0f2db-aa09-48cd-a13b-e26a973e9cdc">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=870fdfdd-16bf-42a2-a23b-ed6045438d5e">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9c3d14d8-6716-4423-91a9-a05373227237">Internet Explorer 6</a>
                    <br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9e283d8-d4a2-41e2-a73c-92fae957ba3d">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=470d56d1-5789-42cc-a088-a2c8ac934ab3">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2db4098a-f4f9-4211-b55d-5d0df1409c43">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f208407-4bb3-41fe-b0d6-fc8a5e30e667">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31af27b8-7b73-4090-94bd-2fb89d3970fc">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=64496a87-2225-402a-a94a-a8e92b17ac83">Internet Explorer 6</a>
                    <br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5aa3a493-4188-48a9-a549-cf9ba01ed32a">Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1934acfa-5637-4ae9-9e9a-fc7e58930b7a">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef140089-d022-4ee8-9cc4-7fb25295a39d">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=410c72d8-3b78-4c4a-ad61-acb7f854ffc2">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66ddc7ce-5280-494d-bb3c-dab06e27fb5c">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a080f36e-c24f-40ac-bb40-b26cb31bcae3">Internet Explorer 8</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c82417ec-232f-4f84-ba2c-0ffad77e9bb5">Internet Explorer 9</a><br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f25ced5-ef86-4b9d-91fb-443c9a2c1458">Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f119902-8398-4814-8229-9eb9f0980e87">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=704c1c9c-d1c1-40cb-97a7-fbb1f195f9f8">Internet Explorer 8</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a6ff7b27-bc21-4945-8b2e-757b6f83fa58">Internet Explorer 9</a><br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5b8ff09-237e-49f1-a566-e323ca11fbc3">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da9c98d1-973c-44d9-aee5-f5c4a8e8c0e1">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d65ae4cc-d82a-42da-829f-d9479e23b7a5">Internet Explorer 8</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70065bd0-7c97-4ffc-828f-2cc245d04429">Internet Explorer 9</a>**<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac2d5122-6f9b-46f5-9840-77aa7ff84308">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1fbaabb9-8601-4760-813d-aeedfdcafb8b">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9facff69-618f-4a64-8665-5dd6cde07de9">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00f28d81-3714-403c-bcd7-55f2ac97f75b">Internet Explorer 8</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ce60689-ca85-4c9f-af96-a73b1e43c10b">Internet Explorer 9</a>**<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f605f6f-3854-403d-878b-637626aef78f">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e7253d8-fdc7-4563-9714-21ca3c77e4b1">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01885624-cfb1-4918-abef-ab0ea765cb04">Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe37eb6d-b1fa-496c-a0d3-19a6d35a6cb9">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7019de24-8c58-4565-ada1-ca8755115096">Internet Explorer 8</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12292081-23f7-4968-8cd7-17aaef2aed6a">Internet Explorer 9</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6bc168d9-6664-41fb-914f-dbd7514a4b0e">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4551b77-eb09-448a-9dc5-66de846035e7">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fcdb872f-2ee2-4f74-b7ae-1b82daf66761">Internet Explorer 8</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef664114-6582-49d3-b332-078a7d075337">Internet Explorer 9</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aafeff2d-db9a-4b3b-b620-be4ec5f5bdcc">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0fc9a501-523d-4cbb-8d99-a773089afc4c">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
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
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1																		</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fe68eb-2aa6-4a59-b9d8-deeae5236af2">Internet Explorer 8</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd709da2-4cb1-482f-88eb-dfab4d3c59c6">Internet Explorer 9</a>**<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a86e2cf-4e7d-4012-88c3-6957a3842dd3">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c29deec3-4672-4658-a550-dce244434cd4">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=777f3bbe-094c-411d-879d-34a5a20ae7f3">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>**<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f4043df-c07c-4611-b06a-7fcbb7416e7d">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82403fd3-ed75-4ea8-aa3f-ed9dda75612a">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d6b8036-d38f-408a-a36c-027553faefc1">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b420cae3-de30-4c6c-8ed9-7431ad7ab4da">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Tabel 2**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="6">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c07e1630-43ba-491e-bd59-9eb53105986c">Windows XP Service Pack 3</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=797a01dc-39fb-4511-832a-42d2975133f5">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=694ba1a6-7512-497d-a572-646a6e07b13b">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=308da543-d49d-4591-8bbc-d65c524bb0ad">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b459bf0-7844-4740-895c-d149d56e781f">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=114c2835-921a-4d3e-be91-dfd217fd26a9">Windows Vista Service Pack 2</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9713b7b8-f260-440d-a994-845f17683fe9">Windows Vista Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0fcee476-8d7e-49a7-b6ea-89043304a653">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d67ec00-e86a-49b6-a9a2-85b2520fa4bb">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
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
                      <strong>Moderate</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c01d9132-af5f-4039-8195-95f6761f2d0e">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>**[1]<br />(KB2487367)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da219735-b8b7-4f97-b8a8-7c253838de6b">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>***<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>**[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70797adb-d693-4102-9e7c-ba1ea8fb07d0">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>**[1]<br />(KB2487367)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e077af5-5823-4377-a997-44b022a694d8">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>***<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>**[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9babf81a-8b21-42ae-a65c-f414793516ab">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=560efa6f-c956-47cb-a2f4-a1f45278b7cd">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=814bbdfa-7cbc-40e5-8ca3-8fed9d13ff00">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c8dd72b-abf8-4e1f-aafc-777c1a3ef3db">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Kun Windows 7 til 32-bit-systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c">Microsoft .NET Framework 3.5.1</a><br />(KB2539634)<br />(Moderat)<br /><br />Kun Windows 7 til 32-bit-systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)<br /><br />Kun Windows 7 til 32-bit-systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b">Microsoft .NET Framework 3.5.1</a><br />(KB2539635)<br />(Moderat)<br /><br />Kun Windows 7 til 32-bit-systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=085ee785-b6ad-4c68-835a-e17bc8f12a53">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d90c07c1-3c07-4989-825c-fb8453541a0e">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Kun Windows 7 til x64-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c">Microsoft .NET Framework 3.5.1</a><br />(KB2539634)<br />(Moderat)<br /><br />Kun Windows 7 til x64-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)<br /><br />Kun Windows 7 til x64-baserede systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b">Microsoft .NET Framework 3.5.1</a><br />(KB2539635)<br />(Moderat)<br /><br />Kun Windows 7 til x64-baserede systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
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
                      <strong>Moderate</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1																		</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9fd2b4ba-d98e-4ad6-99f2-c471335042d3">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>Kun Windows Server 2008 R2 til x64-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>[1]<br />(KB2487367)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 R2 til x64-baserede systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>*[1]<br />(KB2487367)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67cccd09-5b82-4546-884a-d2a9e2400820">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>***<br />(Moderat)</td><td>Kun Windows Server 2008 R2 til x64-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c">Microsoft .NET Framework 3.5.1</a>*<br />(KB2539634)<br />(Moderat)<br /><br />Kun Windows Server 2008 R2 til x64-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)<br /><br />Kun Windows Server 2008 R2 til x64-baserede systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b">Microsoft .NET Framework 3.5.1</a>*<br />(KB2539635)<br />(Moderat)<br /><br />Kun Windows Server 2008 R2 til x64-baserede systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>*[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93752c8f-5461-4e6f-9cab-6401b985ef17">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1edf843-9a2a-4334-a95f-78e75a9b3ef1">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(Moderat)</td><td>Kun Windows Server 2008 R2 til Itanium-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c">Microsoft .NET Framework 3.5.1</a><br />(KB2539634)<br />(Moderat)<br /><br />Kun Windows Server 2008 R2 til Itanium-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)<br /><br />Kun Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b">Microsoft .NET Framework 3.5.1</a><br />(KB2539635)<br />(Moderat)<br /><br />Kun Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Serverens hovedinstallation er ikke berørt.** Den sårbarhede, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, når de er installeret vha. installationsindstillingen Server Core - heller ikke selv om filer, der er berørt af disse sårbarheder, findes på systemet. Brugere med berørte filer vil dog stadig blive tilbudt denne opdatering, da opdateringsfilerne er nyere (med højere versionsnumre), end de filer, der aktuelt er på systemet. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkninger til MS11-066**

\[1\] **.NET Framework 4 Client Profile ikke berørt.** The .NET Framework version 4 redistributable packages er tilgængelige i to profiler: .NET Framework 4 og .NET Framework 4 Client Profile. .NET Framework 4 Client Profile er et delområde af .NET Framework 4. Sårbarheden nævnt i denne opdatering berører kun .NET Framework 4 og ikke .NET Framework 4 Client Profile. For yderligere oplysninger skal du se MSDN-artiklen, [Installation af .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

**Bemærkning til MS11-069**

\[1\] **.NET Framework 4 og .NET Framework 4 Client Profile er berørt.** The .NET Framework version 4 redistributable packages er tilgængelige i to profiler: .NET Framework 4 og .NET Framework 4 Client Profile. .NET Framework 4 Client Profile er et delområde af .NET Framework 4. Sårbarheden nævnt i denne opdatering berører både .NET Framework 4 og .NET Framework 4 Client Profile. For yderligere oplysninger skal du se MSDN-artiklen, [Installation af .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Visio</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223425">
                      <strong>MS11-060</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visio 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=866d64b3-7147-4b5f-80fe-4d3317f140df">Microsoft Visio 2003 Service Pack 3</a>
                    <br />(KB2553009)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visio 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0eeabde-5a92-45ae-aef6-81b7bdb4e0cd">Microsoft Visio 2007 Service Pack 2</a>
                    <br />(KB2553010)<br />(Alvorlig)</td></tr>
                <tr><td>Microsoft Visio 2010 og Microsoft Visio 2010 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6da236c2-0ef5-4c13-8393-673b70298a77">Microsoft Visio 2010 og Microsoft Visio 2010 Service Pack 1 (32-bit versioner)</a>
                    <br />(KB2553008)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7f5f2a9-116a-41ef-a19e-a7dd0947d2cb">Microsoft Visio 2010 og Microsoft Visio 2010 Service Pack 1 (64-bit versioner)</a><br />(KB2553008)<br />(Alvorlig)</td></tr>
              </table>


#### Udviklingsværktøjer og software fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Diagramobjekt</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223643">
                      <strong>MS11-067</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Chart Control til Microsoft .NET Framework 3.5 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8a80cc03-0db9-4446-9ce6-159ad02cab52">Chart Control til Microsoft .NET Framework 3.5 Service Pack 1</a>
                    <br />(KB2500170)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Microsoft Visual Studio og Microsoft Report Viewer</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223643">
                      <strong>MS11-067</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2005 Service Pack 1</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59231988-5413-4238-a3aa-32a127871430">Microsoft Visual Studio 2005 Service Pack 1</a>
                    <br />(KB2548826)<br />(Alvorlig)</td></tr>
                <tr><td>Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28bf2ae0-9e21-4201-b7f1-a207abc2866f">Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package</a>
                    <br />(KB2579115)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til MS11-066**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

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

  - Yngve N. Pettersen fra [Opera Software ASA](http://www.opera.com/) for at rapportere et problem, der er beskrevet i MS11-057
  - [Lostmon Lords](http://lostmon.blogspot.com) for at rapportere et problem, der er beskrevet i MS11-057
  - Makoto Shiotsuki fra [Security Professionals Network Inc.](http://www.sec-pro.net/) for at rapportere et problem, der er beskrevet i MS11-057
  - En anonym forsker, der samarbejder med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem, der er beskrevet i MS11-057
  - Stephen Fewer fra [Harmony Security](http://www.harmonysecurity.com/), der samarbejder med [TippingPoint's](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere to problemer, der er beskrevet i MS11-057
  - Michal Zalewski fra [Google Inc.](http://www.google.com/) for at samarbejde med os om ændringer ifm. de gennemgribende beskyttelsesforanstaltninger, der er inkluderet i MS11-057
  - Grischa Zengel ([Zengel Medizintechnik GmbH](http://www.zmt.info/)) for at rapportere et problem, der er beskrevet i MS11-058
  - Linlin Zhao fra [Baidu Security Team](http://www.baidu.com) for at rapportere to problemer, der er beskrevet i MS11-060
  - Sven Taute for at rapportere et problem, der er beskrevet i MS11-061
  - Lufeng Li fra for at rapportere et problem beskrevet i MS11-062
  - Alex Ionescu fra Winsider Seminars & Solutions Inc. for at rapportere et problem, der er beskrevet i MS11-063
  - Nico Leidecker og James Forshaw of Context Information Security for at rapportere et problem, der er beskrevet i MS11-066
  - Adam Bixby fra [Gotham Digital Science](http://www.gdssecurity.com/) for at rapportere et problem, der er beskrevet i MS11-067
  - Zheng Wenbin fra [Qihoo 360 Security Center](http://www.360.cn/) for at rapportere et problem, der er beskrevet i MS11-068
  - Michael J. Liu for at rapportere et problem, der er beskrevet i MS11-069

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger om, hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V 0.1 (9. august 2011): Oversigt over bulletin offentliggjort.
  - V1.1 (10. august 2011): For MS11-059, rettede oplysninger om genstartskrav i afsnittet **Resuméer**. For MS11-065, rettede vigtig note i **Indeks over mulighed for udnyttelse** for CVE-2011-1968. For MS11-068, reviderede hovedinstallationsnotation til Windows Server 2008 og Windows Server 2008 R2.
  - V 2.1 (26. oktober 2011): For MS11-066 og MS11-069, rettede muligheden for serverens hovedinstallation for .NET Framework 4 på Windows Server 2008 R2 for x64-baserede systemer.

*Built at 2014-04-18T01:50:00Z-07:00*

