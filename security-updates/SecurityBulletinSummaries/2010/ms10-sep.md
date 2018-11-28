---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for september 2010
TOCTitle: MS10-SEP
ms:assetid: ms10-sep
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms10-sep(v=Security.10)
ms:contentKeyID: 61224071
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for september 2010

Offentliggjort: 14. september 2010 | Opdateret: 26. oktober 2011

**Version:** 6.1

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for september 2010.

Med udgivelsen af bulletiner for september 2010 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 9. september 2010. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 15. september 2010 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få september måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454433&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og webcasts](http://technet.microsoft.com/security/bulletin/summary).

I forbindelse med den out-of-band-sikkerhedsbulletin, der er blevet tilføjet Version 3.0 af denne bulletinoversigt, MS10-070, afholder Microsoft et webcast for at behandle kundernes spørgsmål omkring denne bulletin. Den afholdes den 28 september 2010 kl. 13:00 Pacific Time (USA og Canada). [Tilmeld dig nu til webcast den 28. september kl.13:00](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032464130&culture=en-us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i Oversigt over sikkerhedsbulletiner fra Microsoft og webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede vigtige opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=200505">MS10-061</a></td>
<td><strong>Sårbarhed i tjenesten Print Spooler kan tillade fjernudførelse af kode (2347290)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Print Spooler-tjenesteprotokollen. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en hacker sender en særligt udformet udskriftsanmodning til et sårbart system, som har en printerspooler-grænseflade, der er eksponeret over RPC. Som standard deles printere ikke på noget aktuelt understøttet Windows-operativsystem.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190884">MS10-062</a></td>
<td><strong>En sårbarhed i MPEG-4 Codec kan muliggøre fjernudførelse af kode (975558)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i MPEG-4 Codec. Disse sårbarheder kan muliggøre fjernudførelse af kode, hvis en bruger åbner en særligt udformet mediefil eller modtager særligt udformet streamingindhold fra et websted eller et program, der leverer webindhold. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=200378">MS10-063</a></td>
<td><strong>En sårbarhed i Unicode Scripts Processor (USP) kan tillade fjernudførelse af kode (2320113)</strong><br />
<br />
Denne vigtige sikkerhedsopdatering løser en privat rapporteret sårbarhed i USP. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist et særligt udformet dokument eller en webside med et program, der understøtter EOT-skrifttyper. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=200727">MS10-064</a></td>
<td><strong>En sårbarhed i Microsoft Outlook kan give mulighed for fjernudførelse af kode (2315011)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed. Sårbarheden kan give mulighed for fjernudførelse af kode, hvis en bruger åbner eller får vist en særligt udformet e-mail vha. en berørt version af Microsoft Outlook, der er forbundet med en Exchange-server via onlinetilstand. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=199537">MS10-065</a></td>
<td><strong>Sårbarheder</strong> <strong>i Microsoft Internet Information Services (IIS) kan give mulighed for fjernudførelse af kode (2267960)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder og én offentliggjort sårbarhed i Internet Information Services (IIS). Den mest alvorlige af disse sårbarheder kan tillade fjernudførelse af kode, hvis en klient sender en særligt udformet HTTP-forespørgsel til serveren. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197105">MS10-066</a></td>
<td><strong>En sårbarhed i Remote Procedure Call (RPC) kan</strong> <strong>muliggøre fjernudførelse af kode (982802)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Denne sikkerhedsopdatering er klassificeret som Alvorlig for alle understøttede versioner af Windows XP og Windows Server 2003. Alle understøttede versioner af Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er ikke berørt af sårbarheden.<br />
<br />
Sårbarheden kan give mulighed for fjernudførelse af kode, hvis en hacker sender et særligt udformet RPC-svar til en klientinitieret RPC-anmodning. En hacker, som har held til at udnytte denne sårbarhed, kan udføre arbitrær kode og få fuld kontrol over et berørt system. En hacker skal overbevise brugeren om at starte en RPC-forbindelse til en ondsindet server, der er under hackerens kontrol. En hacker kan ikke udnytte denne sårbarhed via fjernadgang uden brugerinteraktion.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197102">MS10-067</a></td>
<td><strong>En sårbarhed i tekstkonvertere til WordPad kan muliggøre fjernudførelse af kode (2259922)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Denne sikkerhedsopdatering er klassificeret som Alvorlig for alle understøttede versioner af Windows XP og Windows Server 2003. Alle understøttede versioner af Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er ikke berørt af sårbarheden.<br />
<br />
Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet fil via WordPad. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190509">MS10-068</a></td>
<td><strong>En sårbarhed i Local Security Authority Subsystem Service kan give mulighed for udvidelse af rettigheder (983539)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Active Directory, Active Directory Application Mode (ADAM) og Active Directory Lightweight Directory Service (AD LDS). Denne sårbarhed kan give mulighed for udvidelse af rettigheder, hvis en godkendt hacker sender særligt udformede Lightweight Directory Access Protocol (LDAP)-meddelelser til en lyttende LSASS-server. For at kunne udnytte denne sårbarhed skal en hacker have en medlemskonto inden for det Windows-domæne, der er målet. Hackeren behøver dog ikke have en arbejdsstation, der er forbundet til Windows-domænet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197093">MS10-069</a></td>
<td><strong>En sårbarhed i Windows Client/Server Runtime Subsystem kan give mulighed for udvidelse af rettigheder (2121546)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Denne sikkerhedsopdatering er klassificeret som Alvorlig for alle understøttede versioner af Windows XP og Windows Server 2003. Alle understøttede versioner af Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er ikke berørt af sårbarheden.<br />
<br />
Sårbarheden kan give mulighed for udvidelse af rettigheder, hvis en hacker logger på et berørt system, der er konfigureret med kinesisk, japansk eller koreansk systemlandestandard. En hacker, som har held til at udnytte denne sårbarhed, kan derefter installere programmer, se, ændre eller slette data eller oprette nye konti med komplette brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=202409">MS10-070</a></td>
<td><strong>En sårbarhed i ASP.NET kan muliggøre offentliggørelse af oplysninger (2418042)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i ASP.NET. Sårbarheden kan tillade offentliggørelse af oplysninger. En hacker, der med held har udnyttet denne sårbarhed, kan læse data såsom visningstilstand, der er blevet krypteret af serveren. Denne sårbarhed kan også anvendes til datamanipulation, der kan benyttes til at kryptere og manipulere med data krypteret fra serveren, hvis udnyttelsen lykkes. Versioner af Microsoft .NET Framework før Microsoft .NET Framework 3.5 Service Pack 1 er ikke berørt af den del af sårbarheden, der medfører offentliggørelse af filindhold.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Afsløring af oplysninger</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er anført i faldende rækkefølge i forhold til CVE ID's vurderingsniveau for udnyttelse. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

**Hvordan anvender jeg** **denne tabel?**

Brug denne tabel til at få kendskab til sandsynligheden for, at fungerende exploit-kode udgives inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Du bør gennemse alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Titel på sårbarhed</th>
<th>CVE ID</th>
<th>Vurdering af mulighed for udnyttelse</th>
<th>Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190884">MS10-062</a></td>
<td>Sårbarhed vedr. MPEG-4 Codec</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0818">CVE-2010-0818</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Udførelse af kode er mindre sandsynlig på Windows Vista pga. ekstra heap-afhjælpninger</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190509">MS10-068</a></td>
<td>Sårbarhed vedr. LSASS-heapoverløb</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0820">CVE-2010-0820</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197093">MS10-069</a></td>
<td>Sårbarhed vedr. lokal udvidelse af CSRSS-rettigheder</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1891">CVE-2010-1891</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197102">MS10-067</a></td>
<td>Sårbarhed vedr. defekt hukommelse i tekstkonverteringsprogrammet til WordPad og Office</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2563">CVE-2010-2563</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197105">MS10-066</a></td>
<td>Sårbarhed vedr. defekt hukommelse i RPC</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2567">CVE-2010-2567</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=200505">MS10-061</a></td>
<td>Sårbarhed vedr. repræsentation i Print Spooler Service</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2729">CVE-2010-2729</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td><strong>Denne sårbarhed bliver i øjeblikket udnyttet</strong> <strong>i internet-økosystemet</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=202409">MS10-070</a></td>
<td>ASP.NET Padding Oracle-sårbarhed</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3332">CVE-2010-3332</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=199537">MS10-065</a></td>
<td>Sårbarhed vedr. omgåelse af godkendelse mappe</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2731">CVE-2010-2731</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td><strong>Denne sårbarhed er blevet offentliggjort</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=200378">MS10-063</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Uniscribe-fontparser</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2738">CVE-2010-2738</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=200727">MS10-064</a></td>
<td>Sårbarhed vedr. heapbaseret bufferoverløb i Outlook</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2728">CVE-2010-2728</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=199537">MS10-065</a></td>
<td>Sårbarhed vedr. bufferoverløb i forespørgselsheader</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2730">CVE-2010-2730</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=199537">MS10-065</a></td>
<td>Denial-of-Service-sårbarhed vedr. IIS gentaget parameterforespørgsel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1899">CVE-2010-1899</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Dette er kun en Denial-of-Service-sårbarhed</td>
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
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="10">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletin </strong>
                    <strong>-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200505">
                      <strong>MS10-</strong>
                      <strong>061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190884">
                      <strong>MS10-</strong>
                      <strong>062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200378">
                      <strong>MS10-</strong>
                      <strong>063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=199537">
                      <strong>MS10-</strong>
                      <strong>065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197105">
                      <strong>MS10-</strong>
                      <strong>066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197102">
                      <strong>MS10-</strong>
                      <strong>067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190509">
                      <strong>MS10-</strong>
                      <strong>068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197093">
                      <strong>MS10-</strong>
                      <strong>069</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=202409">
                      <strong>MS10-</strong>
                      <strong>070</strong>
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
                      <strong>Krit</strong>
                      <strong>isk</strong>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93faba6b-0a85-4acc-b527-a012bbf56b13">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2084a01c-2a91-4650-8665-7053015f2083">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1d47f30-c1fc-4b9d-8829-3bad1224006a">Windows XP Service Pack 3</a>
                    <br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=555864c3-9114-4988-8526-7bf545a27706">Internet Information Services 5.1</a><br />(KB2124261)<br />(Alvorlig)<br /><br />IIS-godkendelse:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae55787e-4a5c-48d5-aedf-0abada514938">Internet Information Services 5.1</a><br />(KB2290570)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ad0f2cf-03dc-49a0-a16e-17fed0c01cc6">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc4369ec-864a-42ae-a850-b006872241fe">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6554f98f-4dc5-4784-b92c-b0aae1fa22ca">Active Directory Application Mode (ADAM)</a>
                    <br />(KB982000)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20091358-7127-4ace-bf96-4319461ad305">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2416447)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2418241)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780">Microsoft .NET Framework 3.5</a><br />(KB2416468)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a><br />(KB2418240)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f7f3737-056d-44bd-b644-51093b5b501b">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=284a0e80-fd03-4909-b354-0478f04585a1">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b27f310f-6ecc-4abb-8944-9fc24c66e077">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b28bfac-783d-4c89-988b-4123c0343855">Internet Information Services 6.0</a><br />(KB2124261)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3349b12b-621e-48bc-9c57-489c7a56920d">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7567986a-261d-4def-9fa5-c667994c7844">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5bc00f9a-3028-4c9d-be06-f2b78fa444c4">Active Directory Application Mode (ADAM)</a>
                    <br />(KB982000)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=107eb958-b60f-40ae-a785-5d5b4d13d8c6">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2416447)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2418241)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780">Microsoft .NET Framework 3.5</a><br />(KB2416468)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a><br />(KB2418240)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="10">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200505">
                      <strong>MS10-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190884">
                      <strong>MS10-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200378">
                      <strong>MS10-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=199537">
                      <strong>MS10-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197105">
                      <strong>MS10-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197102">
                      <strong>MS10-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190509">
                      <strong>MS10-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197093">
                      <strong>MS10-069</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=202409">
                      <strong>MS10-</strong>
                      <strong>070</strong>
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
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d79680b-c071-462f-9cea-551fbd42edf0">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a942985-081f-455c-bf9d-4345392c91b0">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ff7de2f-3e37-4aff-a8e4-5ed21b83575c">Windows Server 2003 Service Pack 2</a>
                    <br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29e6cf4f-446b-461c-82f7-cfa8478cf739">Internet Information Services 6.0</a><br />(KB2124261)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8b3004b-07db-4638-a9b7-224ff829081c">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3290e7ee-1e4a-464c-abfd-17fc4108601e">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3fe6e78c-c60a-4903-9273-27b37e129f0a">Active Directory</a>
                    <br />(KB981550)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c42731f1-6393-42ed-b59f-5310c832fdc4">Active Directory Application Mode (ADAM)</a><br />(KB982000)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd46ba66-8ca1-4aa2-b91b-9e5861a173f7">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71f0daad-e2df-421c-9818-58e1e40cdb65">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2416451)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2418241)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780">Microsoft .NET Framework 3.5</a><br />(KB2416468)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a><br />(KB2418240)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=073b3305-4a81-4ef8-b6aa-e53b31a936b4">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=284a0e80-fd03-4909-b354-0478f04585a1">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8382c1f2-e16d-475c-a8a0-e378696808f1">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=750e4a79-11bf-4726-9eb4-5dd3d029a717">Internet Information Services 6.0</a><br />(KB2124261)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=612b2096-bd82-47ca-8b99-454c2f158d39">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b21570cc-4f90-4ed8-b901-a34584d44a63">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22412eed-33cd-4dfc-8ef7-b74dcd7c5faf">Active Directory</a>
                    <br />(KB981550)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79fb639d-2cc1-4bea-9df6-c67ed95890e3">Active Directory Application Mode (ADAM)</a><br />(KB982000)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ff5976e0-579c-4e6e-a225-c0d3913cdc85">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2416447)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2418241)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780">Microsoft .NET Framework 3.5</a><br />(KB2416468)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a><br />(KB2418240)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ca35a520-c4da-41bb-abcc-d5bc534ff19a">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=be7b3310-ffb7-4528-9c9e-aebe14d264d6">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6841057-1745-44e9-a16a-c180dd941ddf">Internet Information Services 6.0</a><br />(KB2124261)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f04f151-330a-4b6c-826e-76def35daa73">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9c4427d-54c8-4f3c-9a94-818196cd5180">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cab75c8a-0d12-4a91-82b2-9f9b70610f67">Active Directory</a>
                    <br />(KB981550)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e450ca08-1d75-4419-ad9f-c5e5efb55cd5">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2416447)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d31fd37-eb58-4169-b6b9-4cf854524e46">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2418241)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d284237b-e4d9-460a-98f0-7a18252f5780">Microsoft .NET Framework 3.5</a><br />(KB2416468)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a><br />(KB2418240)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="10">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200505">
                      <strong>MS10-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190884">
                      <strong>MS10-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200378">
                      <strong>MS10-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=199537">
                      <strong>MS10-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197105">
                      <strong>MS10-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197102">
                      <strong>MS10-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190509">
                      <strong>MS10-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197093">
                      <strong>MS10-069</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=202409">
                      <strong>MS10-070</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
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
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=028977fd-0f39-42d4-9fee-0d90a2931cfd">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84629c25-7827-40c1-86fb-7ffa247202a0">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac1b0260-3802-45d4-985e-ac827d784e4f">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75059175-9c59-45d5-81ce-09b964640e5f">Internet Information Services 7.0</a><br />(KB2124261)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Kun Windows Vista Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=853a71f3-fb0d-43af-a2b8-45bf8ca1a588">Active Directory Lightweight Directory Service (AD LDS)</a><br />(KB981550)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2416447)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a><br />(KB2418240)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)<br /><br />Kun Windows Vista Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB2416469)<br />(Alvorlig)<br /><br />Kun Windows Vista Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416474)<br />(Alvorlig)<br /><br />Kun Windows Vista Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04">Microsoft .NET Framework 2.0 Service Pack 2, Microsoft .NET Framework 3.5 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416470)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c68b9337-883d-4e98-ba0a-90b5cad46184">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=36e2a74b-e5c6-47d5-9cd9-b9171be63c7d">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebfdcd6d-413e-4359-8863-e992327a607f">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9864c590-10a7-4971-a717-924ed0d6cace">Internet Information Services 7.0</a><br />(KB2124261)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Kun Windows Vista x64 Edition Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=566f468b-22b6-400a-a656-ae64cfcb52df">Active Directory Lightweight Directory Service (AD LDS)</a><br />(KB981550)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2416447)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a><br />(KB2418240)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)<br /><br />Kun Windows Vista x64 Edition Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB2416469)<br />(Alvorlig)<br /><br />Kun Windows Vista x64 Edition Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416474)<br />(Alvorlig)<br /><br />Kun Windows Vista x64 Edition Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04">Microsoft .NET Framework 2.0 Service Pack 2, Microsoft .NET Framework 3.5 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416470)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="10">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200505">
                      <strong>MS10-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190884">
                      <strong>MS10-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200378">
                      <strong>MS10-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=199537">
                      <strong>MS10-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197105">
                      <strong>MS10-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197102">
                      <strong>MS10-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190509">
                      <strong>MS10-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197093">
                      <strong>MS10-069</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=202409">
                      <strong>MS10-070</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
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
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2e788de-8400-4bf6-b96b-a915154aa20a">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fdfc393e-a54d-44dd-ba45-c2a550ffd2a1">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>**<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b679fe0c-5498-4fc5-84c8-0cd24b625907">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d798dc8e-ae64-4a1d-abda-f58cf69779d8">Internet Information Services 7.0</a>*<br />(KB2124261)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1452befe-b7b8-4131-b36f-dded2bd16d5e">Active Directory og Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB981550)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB2416447)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a>**<br />(KB2418240)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2416472)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til 32 bit-systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB2416469)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til 32 bit-systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2416474)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til 32-bit-systemer Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04">Microsoft .NET Framework 2.0 Service Pack 2, Microsoft .NET Framework 3.5 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2416470)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e08d4f49-5a13-4e1d-b0a7-27b314c2edb5">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b7af424-6286-4a80-827c-c4df4f92fe43">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>**<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1b38b87-24f6-4aaa-afa9-40f4015d6694">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e29f01dc-b00d-4c12-a13e-63aa0b09d919">Internet Information Services 7.0</a>*<br />(KB2124261)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38eb875f-1869-401b-b7d3-9f18f4ba4f24">Active Directory og Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB981550)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB2416447)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a>**<br />(KB2418240)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2416472)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til x64-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB2416469)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til x64-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2416474)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til x64-baserede systemer Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04">Microsoft .NET Framework 2.0 Service Pack 2, Microsoft .NET Framework 3.5 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2416470)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til x64-baserede systemer Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00d95a85-f3e8-464d-a10c-85c6d91b4aae">Microsoft .NET Framework 3.5</a>**<br />(KB2418240)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=098537d5-bf6e-4e04-ad33-1cde697e062f">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ceb856e8-f4a6-4229-bd26-b1a763d7d443">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(KB981322)<br />(Kritisk)</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d595c8d2-90b1-46e4-bb9f-60efd0bf3a02">Internet Information Services 7.0</a><br />(KB2124261)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7990e61-21fd-4942-9dfe-af7961cb0282">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2416447)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae42d6cc-6d4e-425a-9b4f-379f66fc506a">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416473)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til Itanium-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ad59265-9dca-4731-ac09-46c162c1832a">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB2416469)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til Itanium-baserede systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac1c77df-34d5-48d4-9a9d-33dc017ffe93">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416474)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til Itanium-baserede systemer Service Pack 2:                 <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45aa5666-3454-443c-a224-2076215fef04">Microsoft .NET Framework 2.0 Service Pack 2, Microsoft .NET Framework 3.5 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2416470)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="10">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200505">
                      <strong>MS10-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190884">
                      <strong>MS10-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200378">
                      <strong>MS10-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=199537">
                      <strong>MS10-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197105">
                      <strong>MS10-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197102">
                      <strong>MS10-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190509">
                      <strong>MS10-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197093">
                      <strong>MS10-069</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=202409">
                      <strong>MS10-070</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 til 32-bit-systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34619e9e-1f00-40e4-be6f-5bbf5e3c801b">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b2d42da-4dbc-4fbb-be22-09ca7dec5aa3">Internet Information Services 7.5</a><br />(KB2124261)<br />(Alvorlig)<br /><br />IIS-FastCGI:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c843afd9-b6f2-48de-91cc-1c0d481c2be4">Internet Information Services 7.5</a><br />(KB2271195)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=454fc025-bfa2-4552-9522-3585f523ecb2">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB981550)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2416471)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 til 32-bit-systemer Service Pack 1</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>
                    [1]
                    <br />(KB2416472)<br />(Alvorlig)</td></tr>
                <tr><td>Windows 7 til x64-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbb747a5-658d-44cf-bd49-425d1700157f">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66b64374-95e4-4b99-80e6-98dc63cd272b">Internet Information Services 7.5</a><br />(KB2124261)<br />(Alvorlig)<br /><br />IIS-FastCGI:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f0c0454-cbb6-47ed-9227-98aa45b8cbdb">Internet Information Services 7.5</a><br />(KB2271195)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b15ad533-3cf1-4dcf-847c-05ebffb84e26">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB981550)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2416471)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472) (Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 til x64-baserede systemer Service Pack 1</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>
                    [1]
                    <br />(KB2416472) (Alvorlig)</td></tr>
              
                <tr><th colspan="10">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200505">
                      <strong>MS10-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190884">
                      <strong>MS10-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200378">
                      <strong>MS10-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=199537">
                      <strong>MS10-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197105">
                      <strong>MS10-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197102">
                      <strong>MS10-067</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190509">
                      <strong>MS10-</strong>
                      <strong>068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=197093">
                      <strong>MS10-069</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=202409">
                      <strong>MS10-070</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 til x64-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11e20088-1be2-4166-9c97-234b7e9f1c4f">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21458cce-f67e-4e95-a067-8311afefc261">Internet Information Services 7.5</a>*<br />(KB2124261)<br />(Alvorlig)<br /><br />IIS-FastCGI:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9578b1de-f2c1-4b37-9d82-69e929cab6f3">Internet Information Services 7.5</a>*<br />(KB2271195)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54f36389-8be4-4a0c-9640-dc32addac9d7">Active Directory og Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB981550)<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7">Microsoft .NET Framework 3.5.1</a>*<br />(KB2416471)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>*[1]<br />(KB2416472)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 R2 til Itanium-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8c635f8-8978-44bf-b457-e07368f08ef4">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>IIS-ASP:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b8f3fd1-1ef4-4e9f-9bce-0c68f10519d1">Internet Information Services 7.5</a><br />(KB2124261)<br />(Alvorlig)<br /><br />IIS-FastCGI:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21adf80d-267f-47cd-9c03-4b4854ba159f">Internet Information Services 7.5</a><br />(KB2271195)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e7dcf51-74f1-43cc-aece-0cd5df05ddb7">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2416471)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>[1]<br />(KB2416472)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ce703b7-08a5-4eff-a062-d5dc720908f6">Microsoft .NET Framework 4.0</a>
                    [1]
                    <br />(KB2416472)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er** **berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, som denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkning til MS10-063**

Se også andre softwarekategorier under dette afsnit, Berørte programmer og downloadplaceringer, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

**Bemærkning til MS10-070**

\[1\] **.NET Framework 4.0 Client Profile ikke berørt.** The .NET Framework version 4 redistributable packages er tilgængelige i to profiler: .NET Framework 4.0 og .NET Framework 4.0 Client Profile. .NET Framework 4.0 Client Profile er et undersæt af .NET Framework 4.0. Sårbarheden nævnt i denne opdatering berører kun .NET Framework 4.0 og ikke .NET Framework 4.0 Client Profile. Yderligere oplysninger findes i: [Installation af .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft Office Suites, systemer og komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200378">
                      <strong>MS10-063</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=200727">
                      <strong>MS10-064</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b56f85f-d39b-410a-857a-799a5d714de7">Microsoft Office XP Service Pack 3</a>
                    <br />(KB2288608)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5e85841-9dea-4776-9e0e-3cd272066f37">Microsoft Outlook 2002 Service Pack 3</a>
                    <br />(KB2293422)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb7783b1-b396-4254-b317-f2292b305cfc">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB2288613)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec8ed81e-05d0-4c20-b5fb-ebc72230a8bd">Microsoft Outlook 2003 Service Pack 3</a>
                    <br />(KB2293428)<br />(Alvorlig)</td></tr>
                <tr><td>Microsoft Office 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44c5bccf-66dd-4796-9089-e6171d8c9785">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2288621)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6009d507-135c-4ce8-a830-925134f214dc">Microsoft Outlook 2007 Service Pack 2</a>
                    <br />(KB2288953)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til MS10-063**

Se også andre softwarekategorier under dette afsnit, Berørte programmer og downloadplaceringer, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Vejledning i registrering og implementering**

Microsoft giver vejledning i registrering og implementering af sikkerhedsopdateringer. Denne vejledning indeholder anbefalinger og oplysninger, som it-fagfolk kan bruge til bedre at forstå, hvordan de skal anvende forskellige værktøjer til registrering og implementering af sikkerhedsopdateringer. Yderligere oplysninger finder du i [Microsoft Knowledge Base-artikel 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) giver administratorer mulighed for at søge på lokale systemer og fjernsystemer efter manglende sikkerhedsopdateringer samt almindelige fejl ved sikkerhedskonfigurationer. Hvis du ønsker yderligere oplysninger om MBSA, kan du besøge webstedet [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Microsoft Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Yderligere oplysninger om, hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere. Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig, se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Få mere at vide om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsoplysninger, på [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brugere kan også bruge SUIT (Security Update Inventory Tool) ved implementering af sikkerhedsopdateringer. Oplysninger om SMS findes på [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Bemærk\!** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til at installere disse opdateringer.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Opdateringer skriver ofte til de samme filer og registreringsdatabaseindstillinger, der er nødvendige for, at dine programmer kan køre. Dette kan udløse inkompatibilitet og forøge den tid, det tager at implementere sikkerhedsopdateringer. Du kan strømline test og validering af Windows-opdateringer mod installerede programmer med de [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponenter, der følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Microsoft Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede vigtige opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Opdateringer fra de foregående måneder for Windows Server Update Services.](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) Viser alle nye, reviderede og udgivne opdateringer til Microsoft-produkter udover Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

For at forbedre sikkerhedsbeskyttelsen for kunder giver Microsoft oplysninger om sårbarheder til store leverandører af sikkerhedssoftware før den månedlige udgivelse af sikkerhedsopdateringer. Derefter kan leverandører af sikkerhedssoftware bruge disse oplysninger om sårbarheder til at give opdateret beskyttelse til kunder via deres sikkerhedssoftware eller -enheder, f.eks. antivirus, registreringssystemer til netværksbaseret indtrængen eller forebyggelsessystemer til host-baseret indtrængen. For at afgøre, om aktive beskyttelser er tilgængelige fra leverandører af sikkerhedssoftware, skal du gå ind på websites på aktive beskyttelser, der udbydes af de programpartnere, som er angivet i [Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

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

  - Sergey Golovanov, Alexander Gostev, Maxim Golovkin og Alexey Monastyrsky fra [Kaspersky Lab](http://www.kaspersky.com/) og Vitaly Kiktenko og Alexander Saprykin fra [Design and Test Lab](http://www.dnt-lab.com/) for at rapportere et problem, der er beskrevet i MS10-061
  - Liam O Morchu fra [Symantec](http://www.symantec.com/index.jsp) for at rapportere et problem, der er beskrevet i MS10-061
  - Matthew Watchinski fra [Sourcefire VRT](http://www.sourcefire.com/services/sf_vrt.html) for at rapportere et problem, der er beskrevet i MS10-062
  - Carsten Book fra for at rapportere et problem, der er beskrevet i MS10-063
  - Marc Schoenefeld fra Red Hat Security Response Team for at rapportere et problem, der er beskrevet i MS10-063
  - Carsten H. Eiram fra [Secunia](http://secunia.com/) for at rapportere oplysninger, der førte til en ændring i udnyttelsesindeks for CVE-2010-2738 i MS10-063
  - Dyon Balding fra [Secunia](http://secunia.com/) for at rapportere et problem, der er beskrevet i MS10-064.
  - Jinsik Shim for at rapportere et problem, der er beskrevet i MS10-065
  - Travis Raybold fra Rubicon West for at rapportere et problem, der er beskrevet i MS10-065
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at rapportere et problem, der er beskrevet i MS10-066
  - S0lute fra [iDefense Labs](http://labs.idefense.com/) for at rapportere et problem, der er beskrevet i MS10-067
  - [IBM Japan](http://www.ibm.com/jp/ja/) for at rapportere et problem, der er beskrevet i MS10-069

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger om, hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (14. september 2010): Oversigt over bulletin offentliggjort.
  - V2.0 (22. september 2010): Hævede udnyttelsesindeksklassifikation for CVE-2010-2738, sænkede udnyttelsesindeksklassifikation for CVE-2010-2730, og reviderede vigtig note til udnyttelsesindeks for CVE-2010-0818.
  - V3.0 (28. september 2010): Tilføjede sikkerhedsbulletin fra Microsoft MS10-070, En sårbarhed i ASP.NET kan give mulighed for offentliggørelse af oplysninger (2418042). Tilføjede også bulletin-webcast-linket til denne out-of-band-sikkerhedsbulletin.
  - V4.0 (30. september 2010): Denne oversigt over bulletin er revideret for at annoncere, at opdateringer til MS10-070 nu er tilgængelige via alle distributionskanaler, inklusive Windows Update og Microsoft Update. Oplysninger om opdateringerne KB2418240, KB2418241, KB2416470 og KB2416474 for MS10-070 er også revideret.
  - V4.1 (3. november 2010): For MS10-070 er der tilføjet en bemærkning til tabellen Berørte programmer for at forklare, at .NET Framework 4.0 Client Profile ikke er berørt.
  - V5.0 (14. december 2010): Denne oversigt over bulletiner er revideret for at annoncere, at der i forbindelse med MS10-070 nu er nye opdateringspakker tilgængelige til .NET Framework 4.0 (KB2416472) for at løse et problem i opsætningen, der kunne føre til problemer med installation af andre opdateringer og/eller produkter. Kunder, der allerede har opdateret deres systemer uden problemer, behøver ikke at foretage sig noget.
  - V6.0 (22. februar 2011): For MS10-070, en registreringsændring tilbyder nu Microsoft .NET Framework 4.0 (KB2416472) opdateringspakker til kunder, der installerer Microsoft .NET Framework 4.0, efter de har installeret Windows 7 til 32-bit-systemer Service Pack 1, Windows 7 til x64-baserede systemer Service Pack 1, Windows Server 2008 R2 til x64-baserede systemer Service Pack 1, eller Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1. Kunder, der allerede har opdateret deres systemer uden problemer, behøver ikke at foretage sig noget.
  - V6.1 (26. oktober 2011): For MS10-070, rettede muligheden for serverens hovedinstallation for .NET Framework 4 på Windows Server 2008 R2 for x64-baserede systemer.

*Built at 2014-04-18T01:50:00Z-07:00*

