---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for august 2009
TOCTitle: MS09-AUG
ms:assetid: ms09-aug
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms09-aug(v=Security.10)
ms:contentKeyID: 61224049
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for august 2009

Offentliggjort: 11. august 2009 | Opdateret: 27. oktober 2009

**Version:** 4.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for august 2009.

Med udgivelsen af bulletiner for august 2009 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 6. august 2009. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 12. august 2009 kl. 11.00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få august måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407484&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=128110">MS09-043</a></td>
<td><strong>Sårbarheder i Microsoft Office Web Components kan give mulighed for fjernudførelse af kode (957638)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i Microsoft Office Web Components, som kan muliggøre fjernudførelse af kode, når en bruger får vist en særligt udformet webside. En hacker, som har held til at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office, Microsoft Visual Studio, Microsoft ISA Server, Microsoft BizTalk Server</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157861">MS09-044</a></td>
<td><strong>Sårbarheder i Forbindelse til Fjernskrivebord kan muliggøre fjernudførelse af kode (970927)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Forbindelse til Fjernskrivebord. Sårbarhederne kan muliggøre fjernudførelse af kode, hvis en hacker har held til at overbevise en bruger af Terminal Services om at oprette forbindelse til en fjendtlig RDP-server, eller hvis en bruger besøger et særligt udformet websted, som udnytter denne sårbarhed. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows, Remote Desktop Connection Client til Mac</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155974">MS09-039</a></td>
<td><strong>Sårbarheder i WINS kan give mulighed for fjernudførelse af kode (969883)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Windows Internet Name Service (WINS). Begge sårbarheder kan muliggøre fjernudførelse af kode, hvis en bruger skulle modtage en særligt udformet WINS-replikeringspakke på et berørt system, der anvender WINS-tjenesten. Som standard er WINS ikke installeret på nogen berørte operativsystemversioner. Kun kunder, der manuelt installerer denne komponent, er berørt af dette problem.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155975">MS09-038</a></td>
<td><strong>Sårbarheder i Windows Media File Processing kan give mulighed for fjernudførelse af kode (971557</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Windows Media File Processing. Begge sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet AVI-fil. Hvis en bruger er logget på med administrative brugerrettigheder, kan en hacker, som har held med at udnytte denne sårbarhed, få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158695">MS09-037</a></td>
<td><strong>Sårbarheder i Microsoft Active Template Library (ATL) kan tillade fjernudførelse af kode (973908)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i Microsoft Active Template Library (ATL). Sårbarhederne kan muliggøre fjernudførelse af kode, hvis en bruger har indlæst en særligt udformet komponent eller et særligt udformet objekt fra et særligt udformet websted. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155977">MS09-041</a></td>
<td><strong>En sårbarhed i Workstation Service kan give mulighed for udvidelse af rettigheder (971657)</strong><br />
<br />
Denne vigtige sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows Workstation Service. Sårbarheden kan tillade udvidelse af rettigheder, hvis en hacker opretter en særligt udformet RPC-meddelelse og sender den til et berørt system. En hacker, som har held til at udnytte denne sårbarhed, kan udføre arbitrær kode og få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. En hacker skal have gyldige logonoplysninger for at kunne udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes af anonyme brugere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155979">MS09-040</a></td>
<td><strong>En sårbarhed i Message Queuing kan give mulighed for udvidelse af rettigheder (971032)</strong><br />
<br />
Denne vigtige sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows Message Queuing Service (MSMQ). Sårbarheden kan tillade udvidelse af rettigheder, hvis en bruger modtager en særligt udformet anmodning til en berørt MSMQ-tjeneste. Som standard er Message Queuing-komponenten ikke installeret på nogen version af et berørt operativsystem og kan kun aktiveres af en bruger med administratorrettigheder. Kun kunder, som manuelt installerer Message Queuing-komponenten, vil være sårbare over for dette problem.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157296">MS09-036</a></td>
<td><strong>Sårbarhed i ASP.NET i Microsoft Windows kan muliggøre Denial-of-Service (970957</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret Denial of Service-sårbarhed i Microsoft .NET Framework-komponenten i Microsoft Windows. Denne sårbarhed kan kun udnyttes, hvis Internet Information Services (IIS) 7.0 er installeret, og ASP.NET er konfigureret til at bruge integreret tilstand på berørte versioner af Microsoft Windows. En hacker kan oprette særligt udformede anonyme HTTP-forespørgsler, som kan få den berørte internetserver til ikke at svare, før den tilknyttede programpulje genstartes. Kunder, der kører IIS 7.0-programpuljer i klassisk tilstand, er ikke berørt af denne sårbarhed.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial-of-Service</td>
<td>Kræver ikke genstart</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157140">MS09-042</a></td>
<td><strong>En sårbarhed i Telnet kan muliggøre fjernudførelse af kode (960859)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Microsoft Telnet-tjenesteprotokollen. Sårbarheden kan gøre det muligt for en hacker et opnå rettigheder og derefter bruge dem til igen at logge på berørte systemer. Hackeren kan derefter opnå brugerrettigheder på et system, der er identiske med brugerrettighederne for den bruger, der er logget på. Scenariet kan i sidste instans resultere fjernudførelse af kode på berørte systemer. En hacker, som har held til at udnytte denne sårbarhed, kan installere programmer, se, ændre eller slette data eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er opført i rækkefølge efter bulletin-id og CVE-id.

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at få kendskab til sandsynligheden for, at fungerende exploit-kode udgives inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Du bør gennemse alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Bulletinens titel</th>
<th>CVE ID</th>
<th>Vurdering af mulighed for udnyttelse</th>
<th>Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157296">MS09-036</a></td>
<td>Sårbarhed i ASP.NET i Microsoft Windows kan muliggøre Denial-of-Service (970957)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1536">CVE-2009-1536</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Et værktøj til denial of service er sandsynligt. En fungerende exploit-kode til fjernudførelse af kode er usandsynlig.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158695">MS09-037</a></td>
<td>Sårbarheder i Microsoft Active Template Library (ATL) kan tillade fjernudførelse af kode (973908)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015">CVE-2008-0015</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158695">MS09-037</a></td>
<td>Sårbarheder i Microsoft Active Template Library (ATL) kan tillade fjernudførelse af kode (973908)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0020">CVE-2008-0020</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158695">MS09-037</a></td>
<td>Sårbarheder i Microsoft Active Template Library (ATL) kan tillade fjernudførelse af kode (973908)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901">CVE-2009-0901</a></td>
<td>Ingen</td>
<td>(Denne sårbarhed er allerede blevet tildelt en vurdering under udnyttelsesindekset i <a href="http://technet.microsoft.com/security/bulletin/ms09-jul">oversigten over bulletin for juli</a>. Dette skyldes, at denne sårbarhed først blev behandlet i <a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a>.)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158695">MS09-037</a></td>
<td>Sårbarheder i Microsoft Active Template Library (ATL) kan tillade fjernudførelse af kode (973908)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493">CVE-2009-2493</a></td>
<td>Ingen</td>
<td>(Denne sårbarhed er allerede blevet tildelt en vurdering under udnyttelsesindekset i <a href="http://technet.microsoft.com/security/bulletin/ms09-jul">oversigten over bulletin for juli</a>. Dette skyldes, at denne sårbarhed først blev behandlet i <a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a>.)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158695">MS09-037</a></td>
<td>Sårbarheder i Microsoft Active Template Library (ATL) kan tillade fjernudførelse af kode (973908)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2494">CVE-2009-2494</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155975">MS09-038</a></td>
<td>Sårbarheder i Windows Media File Processing kan give mulighed for fjernudførelse af kode (971557)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1545">CVE-2009-1545</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155975">MS09-038</a></td>
<td>Sårbarheder i Windows Media File Processing kan give mulighed for fjernudførelse af kode (971557)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1546">CVE-2009-1546</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155974">MS09-039</a></td>
<td>Sårbarheder i WINS kan give mulighed for fjernudførelse af kode (969883)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1923">CVE-2009-1923</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155974">MS09-039</a></td>
<td>Sårbarheder i WINS kan give mulighed for fjernudførelse af kode (969883)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1924">CVE-2009-1924</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Der er større risiko for udnyttelse på et Windows 2000-mål.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155979">MS09-040</a></td>
<td>En sårbarhed i Message Queuing kan give mulighed for udvidelse af rettigheder (971032)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1922">CVE-2009-1922</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Et fjernangreb på denne sårbarhed er ikke muligt.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=155977">MS09-041</a></td>
<td>En sårbarhed i Workstation Service kan give mulighed for udvidelse af rettigheder (971657)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1544">CVE-2009-1544</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>En hacker har brug for godkendelse for at kunne udnytte denne sårbarhed.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157140">MS09-042</a></td>
<td>En sårbarhed i Telnet kan muliggøre fjernudførelse af kode (960859)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1930">CVE-2009-1930</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Denne sårbarhed minder om de tidligere sårbarheder ved NTLM-rettighedsreflektioner, som der allerede eksiterer udnyttelseskode for.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128110">MS09-043</a></td>
<td>Sårbarheder i Microsoft Office Web Components kan give mulighed for fjernudførelse af kode (957638)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0562">CVE-2009-0562</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128110">MS09-043</a></td>
<td>Sårbarheder i Microsoft Office Web Components kan give mulighed for fjernudførelse af kode (957638)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1136">CVE-2009-1136</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Udnyttelseskode for denne sårbarhed er blevet offentliggjort.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128110">MS09-043</a></td>
<td>Sårbarheder i Microsoft Office Web Components kan give mulighed for fjernudførelse af kode (957638)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1534">CVE-2009-1534</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128110">MS09-043</a></td>
<td>Sårbarheder i Microsoft Office Web Components kan give mulighed for fjernudførelse af kode (957638)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2496">CVE-2009-2496</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157861">MS09-044</a></td>
<td>Sårbarheder i Forbindelse til Fjernskrivebord kan muliggøre fjernudførelse af kode (970927)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1133">CVE-2009-1133</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157861">MS09-044</a></td>
<td>Sårbarheder i Forbindelse til Fjernskrivebord kan muliggøre fjernudførelse af kode (970927)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1929">CVE-2009-1929</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
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
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="9">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157861">
                      <strong>MS09-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155974">
                      <strong>MS09-039</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155975">
                      <strong>MS09-038</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158695">
                      <strong>MS09-037</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155977">
                      <strong>MS09-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155979">
                      <strong>MS09-040</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157296">
                      <strong>MS09-036</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157140">
                      <strong>MS09-042</strong>
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
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=027e757d-08d5-4932-b8c4-52ee1be1c864">RDP Version 5.0</a>***<br />(KB958471) og <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2">RDP Version 5.0</a> (KB958470)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2">RDP Version 5.1</a>****<br />(KB958470)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae72782e-920f-4176-a27b-c3b91d50c7d2">RDP Version 5.2</a>****<br />(KB958470)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b5b9228a-66c0-49e6-afde-cc2825a6851f">Microsoft Windows 2000 Server Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f80bf0b-898c-46ca-b20c-21e0e729c332">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f9fcbe9-8496-4d23-8a16-b334157688c2">Microsoft Outlook Express 5.5 Service Pack 2</a>
                    <br />(KB973354)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f340af34-b9a0-44fb-b595-dbb346c727bf">Microsoft Outlook Express 6 Service Pack 1</a><br />(KB973354)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd7c9fc4-61cb-4c23-9961-6d63f234731c">Windows Media Player 9</a><br />(KB973540)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c773149a-f4fc-486a-b718-6b8ff7a36ae2">Windows ATL-komponent</a><br />(KB973507)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=223e25d2-83d7-4cb7-85c4-46a42b8110e0">DHTML-redigeringskomponenten ActiveX Control</a><br />(KB973869)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ed8bad7-2885-452c-9c34-3982cd498be8">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=240977d6-3581-4058-b9f1-7847e4edcf8a">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="9">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157861">
                      <strong>MS09-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155974">
                      <strong>MS09-039</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155975">
                      <strong>MS09-038</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158695">
                      <strong>MS09-037</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155977">
                      <strong>MS09-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155979">
                      <strong>MS09-040</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157296">
                      <strong>MS09-036</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157140">
                      <strong>MS09-042</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
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
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a8830dd-8fb3-4556-a6e7-2c237235357f">RDP Version 5.1 på Windows XP Service Pack 2</a>
                    <br />(KB958470)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf9f9898-10c8-45ab-9df3-85e0b37e6046">RDP Version 5.2 for Windows XP Service Pack 2</a>****<br />(KB958469)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf9f9898-10c8-45ab-9df3-85e0b37e6046">RDP Version 5.2 til Windows XP Service Pack 2</a>****<br />(KB958469)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719">RDP Version 6.0 for Windows XP Service Pack 2</a>****<br />(KB956744)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1f82d76-eeb2-4ff4-9d2c-46882f214719">RDP Version 6.1</a>****<br />(KB956744)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e8a68ee-eb24-424c-b084-450636ccaeec">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c67b5506-00ea-47cc-a0e8-897057b7380c">Microsoft Outlook Express 6</a>
                    <br />(KB973354)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34b2b14d-5811-4635-ba83-f837dcb03d04">Windows Media Player 9, Windows Media Player 10 og Windows Media Player 11</a><br />(KB973540)<br />(Kritisk)<br />(Kun Windows XP Service Pack 2)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec84c98b-6bc7-442f-9280-d6e204280b2f">Windows Media Player 9, Windows Media Player 10 og Windows Media Player 11</a><br />(KB973540)<br />(Kritisk)<br />(Kun Windows XP Service Pack 3)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b4c6fc5-e8e6-4d89-a181-e231240468f9">Windows ATL-komponent</a><br />(KB973507)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bdfcd0c3-7c18-4e63-91dd-d8f82cd89592">DHTML-redigeringskomponenten ActiveX Control</a><br />(KB973869)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b71bcc9-5146-4afc-8847-0af21d7fad36">Microsoft MSWebDVD ActiveX Control</a><br />(KB973815)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46aa443c-4e7b-4bd5-8b4e-0068c3dc0e79">HTML-inputobjektet ActiveX Control</a><br />(KB973768)<br />(Kritisk)<br />(Kun Media Center Edition 2005)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9c0e5bff-c248-4e87-a83b-82ba52f5299d">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93490aa7-9985-4658-b0d7-88fb3f27ada0">Windows XP Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3331388-1e52-4924-b512-23275a8fde84">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=948da99a-44ed-4390-b1b4-7ed3f15a9cda">RDP Version 5.2 på Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB958469)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5061615f-fa8f-465f-ac8f-393998b7e91b">RDP Version 6.0 til Windows XP Professional x64 Edition Service Pack 2</a>****<br />(KB956744)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1ff2ace-b9dc-4cf3-a151-ac6959bcb3a6">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ede1a73a-e303-435e-a2c7-0281ce2370da">Microsoft Outlook Express 6</a>
                    <br />(KB973354)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb98187a-8db9-47e4-88ac-15544c5268f6">Windows Media Player 10</a><br />(KB973540)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e8b9027-4407-4c31-a2ba-9e094557d467">Windows Media Player 11</a><br />(KB973540)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f2b93fc-f977-4f23-af90-c27f744fad0a">Windows ATL-komponent</a><br />(KB973507)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d04a6959-41a4-4a87-b3ad-7455d8fe8b99">DHTML-redigeringskomponenten ActiveX Control</a><br />(KB973869)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85b2dcdb-cea9-4c4a-8ebd-50264e781ade">Microsoft MSWebDVD ActiveX Control</a><br />(KB973815)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b64a454-d383-47e3-b469-b87e2b3c1a9f">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12e6be68-dc87-450e-927b-3c9b6873eb13">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a6ee7af3-3e39-4866-a893-92bf1c786cd4">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="9">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157861">
                      <strong>MS09-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155974">
                      <strong>MS09-039</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155975">
                      <strong>MS09-038</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158695">
                      <strong>MS09-037</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155977">
                      <strong>MS09-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155979">
                      <strong>MS09-040</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157296">
                      <strong>MS09-036</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157140">
                      <strong>MS09-042</strong>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60c79729-ef01-4630-bd67-ec63e7f8b56b">RDP Version 5.2</a>
                    <br />(KB958469)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a37a2d8a-a5ce-4f06-bf07-8cafa16e7a59">RDP Version 6.0</a>****<br />(KB956744)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a8d8ef9-ad41-4237-9cbb-daecfd8f216c">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cba78658-899c-428f-8b04-cfe14ce3c255">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3119ab1e-6729-40a1-b28f-0dab50502be6">Microsoft Outlook Express 6</a>
                    <br />(KB973354)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab054890-983b-4414-ad0a-da1b2d2a4895">Windows Media Player 10</a><br />(KB973540)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d9369b5-0c54-4c17-bc62-fba0a7b4728c">Windows ATL-komponent</a><br />(KB973507)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfc474c2-e3c5-40df-85d4-4ac666ff0561">DHTML-redigeringskomponenten ActiveX Control</a><br />(KB973869)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=301ad191-8d3f-41d3-b41c-e2e863893f73">Microsoft MSWebDVD ActiveX Control</a><br />(KB973815)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9cb0477f-0656-47f5-bd35-5716e0572fbd">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52f59c56-2aba-4626-a90e-311e0e73c813">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3fe9c745-d87c-43b0-9b2a-356fb34282b4">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57393588-dc96-4bda-ab1e-ae550961e5d4">RDP Version 5.2</a>
                    <br />(KB958469)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=957c2e01-89a1-4550-aacb-de8ff896d762">RDP Version 6.0</a>****<br />(KB956744)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e132d051-4444-4ef1-9b6f-2d7da9d2e88e">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58a7c8d9-ec36-46a6-a89b-d8dfd989fda4">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17bd00e3-810c-4a72-bd13-1b55ffb52a5e">Microsoft Outlook Express 6</a>
                    <br />(KB973354)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5890233a-d8f7-490c-8bf5-3ed4bd1c6991">Windows Media Player 10</a><br />(KB973540)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90e0e014-ed7e-498a-9f61-18bb09a384b3">Windows ATL-komponent</a><br />(KB973507)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f502d79-99a8-45dc-9876-2df27e14ffaa">DHTML-redigeringskomponenten ActiveX Control</a><br />(KB973869)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ae71a65-5eee-4dd2-bc79-b7c5a73022bc">Microsoft MSWebDVD ActiveX Control</a><br />(KB973815)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96fbf65f-1db2-432d-92a0-6669d8abaeb0">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f77ef7b-54f8-4260-b6a6-d62a0f85ef45">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2a788e7-a9d1-4574-b106-f8ab44c6c4a2">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f88a714-b917-4193-9002-19fa65722028">RDP Version 5.2</a>
                    <br />(KB958469)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96c3f496-7b2f-4dbc-b484-216c9943c2b1">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=187b02bd-73d6-4f72-81d1-d9477d495499">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7978b921-c5b5-461f-a284-b9848f568aa9">Microsoft Outlook Express 6</a>
                    <br />(KB973354)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad1791b3-8553-4433-a9f7-8b4f857665be">Windows ATL-komponent</a><br />(KB973507)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82c0bb02-70ad-4605-a1f4-4698adf9f4ac">DHTML-redigeringskomponenten ActiveX Control</a><br />(KB973869)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b8a8958-c3cd-4b24-85a2-1baacf92d218">Microsoft MSWebDVD ActiveX Control</a><br />(KB973815)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11321f48-8997-4b99-982a-3ba4ad3f5992">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad55c653-ee6b-4c92-b7f4-3923bb916546">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f625d39-29d4-44f9-b4bd-cd99f1ea422d">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="9">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157861">
                      <strong>MS09-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155974">
                      <strong>MS09-039</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155975">
                      <strong>MS09-038</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158695">
                      <strong>MS09-037</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155977">
                      <strong>MS09-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155979">
                      <strong>MS09-040</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157296">
                      <strong>MS09-036</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157140">
                      <strong>MS09-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf95a552-f6fd-4e35-815a-d16c015cd3ea">RDP Version 6.0 på Windows Vista</a>
                    <br />(KB956744)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf95a552-f6fd-4e35-815a-d16c015cd3ea">RDP Version 6.1 for Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a><br />(KB956744)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81fce7bd-f33c-4586-949d-ac40d415f755">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3766aed9-93f5-478e-a5bf-b7ee0b577088">Windows Media Player 11</a>
                    <br />(KB973540)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80de158d-157e-4c21-9154-c1dbd6e57cb3">Windows ATL-komponent</a><br />(KB973507)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59fefa17-0ad4-4a62-82be-e6a2b7a0aec3">HTML-inputobjektet ActiveX Control</a><br />(KB973768)<br />(Kritisk)<br />(Kun Media Center Edition 2005)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=979ac9da-940f-49e7-91a2-b12db3708076">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00afd94c-b483-4155-884f-b617acca6e7d">Windows Vista</a>
                    <br />(Alvorlig)</td><td>Kun Windows Vista: <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB972591) og <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>***** (KB972592)<br />(Alvorlig)<br /><br />Kun Windows Vista Service Pack 1:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB972593) og <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>***** (KB972594)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d77f406d-11cb-4d19-94ec-938b356c3427">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad">RDP Version 6.0 på Windows Vista x64 Edition</a>
                    <br />(KB956744)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e19cef7-2413-4575-9597-c6273a097aad">RDP Version 6.1 on Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a><br />(KB956744)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a6cea61a-4ad9-4e18-bf18-348ae4ae51c4">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=64edbd64-9faa-4f54-b0d5-836c683ca7cd">Windows Media Player 11</a>
                    <br />(KB973540)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82940d30-6a30-47ca-b184-2ac96e35c294">Windows ATL-komponent</a><br />(KB973507)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92de8a2e-2d50-4278-937e-ccb862c5ab8f">HTML-inputobjektet ActiveX Control</a><br />(KB973768)<br />(Kritisk)<br />(Kun Media Center Edition 2005)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9aa04cc-a5c5-47ae-bf0f-250cff275d26">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0c698aa-a913-4981-8798-6bbb8cacfb86">Windows Vista x64 Edition</a>
                    <br />(Alvorlig)</td><td>Kun Windows Vista x64 Edition: <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d42444bb-5030-4b47-87fa-9df3a8c640ff">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB972591) og <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=310f3aa6-c264-45a2-b24a-3f178b41830e">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>***** (KB972592)<br />(Alvorlig)<br /><br />Kun Windows Vista x64 Edition Service Pack 1:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB972593) og <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB972594)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a41b8c1-f955-474e-a08e-5e73964327d1">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="9">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157861">
                      <strong>MS09-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155974">
                      <strong>MS09-039</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155975">
                      <strong>MS09-038</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158695">
                      <strong>MS09-037</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155977">
                      <strong>MS09-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155979">
                      <strong>MS09-040</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157296">
                      <strong>MS09-036</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157140">
                      <strong>MS09-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71c17a87-710b-434d-9b2a-2f471674915a">RDP Version 6.1</a>**<br />(KB956744)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fdc96a07-ed79-4798-8077-b2e9ca64cd0f">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack  </a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85d9e69f-99a2-467f-bf37-4b47466a12d4">Windows Media Player 11</a>**<br />(KB973540)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba423491-6c29-49f2-811b-ac3f9bbc58fc">Windows ATL Component</a>*<br />(KB973507)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24c77c27-0b7d-4a35-a871-b453f90e5913">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Moderat)</td><td>Ikke relevant</td><td>Kun Windows Server 2008 til 32 bit-systemer: <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB972593) og <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB972594)**<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62f2e0a6-5e68-41c7-a851-d99bcff6ff3e">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f095d2d5-4513-4ae1-96c7-cbcf83304261">RDP Version 6.1</a>**<br />(KB956744)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3afba4-6761-4b3d-98bb-4b4145e27b7f">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9501c8c2-a526-4661-8cba-7847bace1aa0">Windows Media Player 11</a>**<br />(KB973540)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9311953-889a-415f-a396-250a005e95cd">Windows ATL Component</a>*<br />(KB973507)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48d0432e-704a-4bbb-b0a1-cd14069a8e93">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>*<br />(Moderat)</td><td>Ikke relevant</td><td>Kun Windows Server 2008 til x64-baserede systemer: <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB972593) og <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB972594)**<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e5d1db9-efef-4112-8138-62f14670cf0d">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>*<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=65d0af4e-22a2-4524-a003-2f4858012fa8">RDP Version 6.1</a>
                    <br />(KB956744)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa1bb13a-5905-48c4-8e74-a41104593046">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5612bb4-5f37-4b38-bd2e-f198c413371c">Windows ATL-komponent</a>
                    <br />(KB973507)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c119223c-f4e0-449b-8e7b-a6bf11c98f94">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>Kun Windows Server 2008 til Itanium-baserede systemer: <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbf40800-f3b3-43da-ace1-d942d3378ccd">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB972593) og <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87c4a868-b3b5-467d-96a4-633532ab548f">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB972594)<br />(Alvorlig</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b813c74-b2ae-4962-9ebb-1311193d9e2d">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Moderat)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008**

**\*Windows Server 2008 - serverens hovedinstallation er berørt.** For understøttede udgaver af Windows Server 2008 gælder denne opdatering med den samme klassifikation, uanset om Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core eller ej. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 - serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008, hvis Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkninger til MS09-044**

**\*\*\***Brugere af RDP Version 5.0 på Microsoft Windows 2000 Service Pack 4 skal både installere KB958471 og KB958470.

**\*\*\*\***Administratorer har muligvis installeret denne download direkte fra produktpakken.

Se også underafsnittet "Klientsoftware til Mac" under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

**Bemærkning til MS09-036**

**\*\*\*\*\***Da IIS 7.0 ikke kører på Windows Vista Starter og Windows Vista Home Basic, er følgende versioner ikke berørt: Windows Vista Starter (32-bit), Windows Vista Home Basic (32-bit) og Windows Vista Home Basic (64-bit).

#### Klientsoftware til Mac

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Fjernskrivebord</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157861">
                      <strong>MS09-044</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Klient til Forbindelse til Fjernskrivebord til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd9ec77e-5b07-4332-849f-046611458871">Klient til Forbindelse til Fjernskrivebord til Mac 2.0</a>
                    <strong>*</strong>
                    <br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til MS09-044**

**\***Dette download opgraderer Klient til Forbindelse til Fjernskrivebord til Mac 2.0 til Klient til Forbindelse til Fjernskrivebord til Mac 2.0.1, hvilket løser sårbarheden.

Se også underafsnittet "Windows-operativsystemet og dets komponenter" under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Micorsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Office Suites, systemer og komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128110">
                      <strong>MS09-043</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office XP</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580">Microsoft Office XP Service Pack 3</a>
                    <br />(KB947320)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB947319)<br />(Kritisk)</td></tr>
              
                <tr><th colspan="2">Office Web Components</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128110">
                      <strong>MS09-043</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2000 Web Components</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580">Microsoft Office 2000 Web Components Service Pack 3</a>
                    <br />(KB947320)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Web Components</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60e2e4e7-aa75-441d-b6fc-7e850bf8e580">Microsoft Office XP Web Components Service Pack 3</a>
                    <br />(KB947320)<br />(Kritisk)</td></tr>
                <tr><td>Microsoft Office 2003 Web Components</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95c94c9a-6aca-42fb-9679-3234f06c72f7">Microsoft Office 2003 Web Components Service Pack 3</a>
                    <br />(KB947319)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=644008e0-77c9-4a02-ac9b-e30d0930c4be">Microsoft Office 2003 Web Components Service Pack 1 til 2007 Microsoft Office System</a>*<br />(KB947318)<br />(Kritisk)</td></tr>
              
                <tr><th colspan="2">Anden Office Software</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128110">
                      <strong>MS09-043</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Small Business Accounting 2006</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d77ddb3-4d34-4cfe-913b-d05981f59a82">Microsoft Office Small Business Accounting 2006</a>
                    <br />(KB968377)<br />(Kritisk)</td></tr>
              </table>


**Bemærkninger til MS09-043**

**\***SQL Server 2008 og Microsoft Forefront Threat Management Gateway Medium Business Edition gendistribuerer de berørte Office 2003 Web-komponenter til 2007 Microsoft Office-systemet. Opdateringen til Office 2003 Web Components til 2007 Microsoft Office System-komponenten søger efter SQL Server 2008 og Microsoft Forefront Threat Management Gateway Medium Business Edition og tilbyder kunderne opdateringen.

Se også de øvrige underafsnit under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Udviklingsværktøjer og software fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Visual Studio</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128110">
                      <strong>MS09-043</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visual Studio .NET 2003 </td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba2915a0-f5f4-4e18-b0c0-534d2a948585">Microsoft Visual Studio .NET 2003 Service Pack 1</a>
                    <br />(KB969172)<br />(Kritisk)</td></tr>
              </table>


**Bemærkning til MS09-043**

Se også de øvrige underafsnit under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Microsoft Server og Security Software

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Internet Security and Acceleration Server </th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128110">
                      <strong>MS09-043</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Internet Security and Acceleration Server 2004</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326">Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3</a>*<br />(KB947826)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326">Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3</a><br />(KB947826)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Internet Security and Acceleration Server 2006</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326">Microsoft Internet Security og Acceleration Server 2006 Standard Edition Service Pack 3</a>
                    <br />(KB947826)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f79a073-27e8-46ef-87d8-f09b93521326">Microsoft Internet Security og Acceleration Server 2004 Enterprise Edition Service Pack 3</a><br />(KB947826)<br />(Kritisk)</td></tr>
              
                <tr><th colspan="2">Microsoft BizTalk Server </th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128110">
                      <strong>MS09-043</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft BizTalk Server 2002</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=495839b6-0322-4755-997d-4a7762c53333">Microsoft BizTalk Server 2002</a>
                    <br />(KB971388)<br />(Kritisk)</td></tr>
              </table>


**Bemærkninger til MS09-043**

\*Microsoft ISA Server 2004 Standard Edition leveres som et separat produkt. Microsoft ISA Server 2004 Standard Edition leveres både som en komponent til Windows Small Business Server 2003 Premium Edition Service Pack 1 og Windows Small Business Server 2003 R2 Premium Edition.

Se også de øvrige underafsnit under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Bemærk** Fra 1. august 2009 stopper Microsoft supporten til Office Update og Office Update Inventory Tool. Hvis du stadig vil have de seneste opdateringer til Microsoft Office-produkter, skal du anvende [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Hvis du vil have flere oplysninger, skal du se [Om Microsoft Office Update: Ofte stillede spørgsmål](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Vejledning i registrering og implementering**

Microsoft giver vejledning i registrering og implementering af sikkerhedsopdateringer. Denne vejledning indeholder anbefalinger og oplysninger, som it-fagfolk kan bruge til bedre at forstå, hvordan de skal anvende forskellige værktøjer til registrering og implementering af sikkerhedsopdateringer. Yderligere oplysninger finder du i [Microsoft Knowledge Base-artiklen 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) giver administratorer mulighed for at søge på lokale systemer og fjernsystemer efter manglende sikkerhedsopdateringer samt almindelige fejl ved sikkerhedskonfigurationer. Hvis du ønsker yderligere oplysninger om MBSA, kan du besøge webstedet [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

**Systems Management Server**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere. Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig, se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Få mere at vide om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsoplysninger, på [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brugere kan også bruge SUIT (Security Update Inventory Tool) ved implementering af sikkerhedsopdateringer. Oplysninger om SMS findes på [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Bemærk** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til at installere disse opdateringer.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Opdateringer skriver ofte til de samme filer og registreringsdatabaseindstillinger, der er nødvendige for, at dine programmer kan køre. Dette kan udløse inkompatibilitet og forøge den tid, det tager at implementere sikkerhedsopdateringer. Du kan strømline test og validering af Windows-opdateringer mod installerede programmer med de [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponenter, der følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Microsoft Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede vigtige opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Nye, reviderede og offentliggjorte opdateringer til Microsoft-produkter udover Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

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

  - Alexander Pfandt of [Digitiria](http://www.digitaria.com/) for at have rapporteret et problem, der er beskrevet i MS09-036
  - Ryan Smith og Alex Wheeler fra [IBM IIS X-Force](http://www.iss.net/) for først at have rapporteret et problem, der er beskrevet i MS09-037
  - Robert Freeman fra [IBM ISS X-Force](http://www.iss.net/) for at have rapporteret et problem, der er beskrevet i MS09-037
  - David Dewey fra [IBM ISS X-Force](http://www.iss.net/) for at have rapporteret et problem, der er beskrevet i MS09-037
  - Ryan Smith fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret to problemer, der er beskrevet i MS09-037
  - Vinay Anantharaman fra [Adobe Systems, Inc.](http://www.adobe.com/) for at have rapporteret to problemer, der er beskrevet i MS09-038
  - [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at have rapporteret et problem, der er beskrevet i MS09-039
  - LiGen fra [National University of Defense Technology](http://english.nudt.edu.cn/) for at have rapporteret et problem, der er beskrevet i MS09-039
  - Nikita Tarakanov fra [Positive Technologies Research Team](http://en.securitylab.ru/lab/) for at have rapporteret et problem, der er beskrevet i MS09-040
  - Cody Pierce fra [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) for at have rapporteret et problem, der er beskrevet i MS09-041
  - Peter Vreugdenhil fra [Zero Day Initiative](http://www.zerodayinitiative.com/) for at have rapporteret to problemer, der er beskrevet i MS09-043
  - Peter Vreugdenhil fra [Zero Day Initiative](http://www.zerodayinitiative.com/) og Haifei Li fra Fortinets [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) for at have rapporteret et problem, der er beskrevet i MS09-043
  - Sean Larsson fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret et problem, der er beskrevet i MS09-043
  - Wushi fra [Team509](http://www.team509.com/), der arbejder sammen med Zero Day Initiative, for at have rapporteret et problem, der er beskrevet i MS09-044
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at have rapporteret et problem, der er beskrevet i MS09-044

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (11. august 2009): Oversigt over bulletin offentliggjort.
  - V1.1 (13. august 2009): Har rettet listen over RDP-opdateringer til Windows XP Service Pack 2 og Windows XP Service Pack 3 til MS09-044, så den er magen til bulletinen. Ændrede genstartskrav for MS09-037, MS09-042, og MS09-044.
  - V2.0 (25. august 2009): For MS09-044 er downloadlink for RDP Version 5.2 for Windows XP Service Pack 2 (KB958469) korrigeret. Fodnoten, som beskrev en fejlagtig installationsrækkefølge for KB958471 og KB958470, er også blevet korrigeret. Kunder, der allerede har installeret disse opdateringer, behøver ikke installere dem igen.
  - V3.0 (8. september 2009): Microsoft har udsendt MS09-037 med henblik på at tilbyde nye opdateringer til HTML-indputobjektet ActiveX Control på Windows XP Media Center Edition 2005 samt alle understøttede versioner af Windows Vista.
  - V4.0 (27. oktober 2009): Microsoft har genudsendt MS09-043 med henblik på igen at tilbyde opdateringen til Microsoft Office 2003 Service Pack 3 og Microsoft Office 2003 Web Components Service Pack 3 til løsning af et registreringsproblem. Dette er udelukkende en registreringsændring. Der er ikke foretaget ændringer i de binære koder. Kunder, der har opdateret deres systemer uden problemer, behøver ikke at geninstallere denne opdatering.

*Built at 2014-04-18T01:50:00Z-07:00*

