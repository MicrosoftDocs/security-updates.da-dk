---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for oktober 2009
TOCTitle: MS09-OCT
ms:assetid: ms09-oct
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms09-oct(v=Security.10)
ms:contentKeyID: 61224058
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for oktober 2009

Offentliggjort: 13. oktober 2009 | Opdateret: 12. januar 2010

**Version:** 4.1

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for oktober 2009.

Med udgivelsen af bulletiner for oktober 2009 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindelig blev offentliggjort den 8. oktober 2009. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 14. oktober 2009 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få oktober måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407488&culture=en-us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede vigtige opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163970">MS09-050</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i SMBv2 kan give mulighed for fjernudførelse af kode (975517)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed og to privat rapporterede sårbarheder i Server Message Block Version 2 (SMBv2). Den mest alvorlige af disse sårbarheder kan tillade fjernudførelse af kode, hvis en hacker sender en særligt udformet SMB-pakke til en computer, der kører Server-tjenesten. De bedste fremgangsmåder for brug af firewalls og standardkonfigurationer af firewalls kan hjælpe med at beskytte netværk mod angreb, der kommer fra en placering uden for virksomheden. De bedste fremgangsmåder anbefaler, at systemer med forbindelse til internettet har mindst mulig antal åbne porte.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125438">MS09-051</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Windows Media Runtime kan give mulighed for fjernudførelse af kode (975682)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Windows Media Runtime. Sårbarhederne kan muliggøre fjernudførelse af kode, hvis en bruger har åbnet en særligt udformet mediefil eller modtaget særligt udformet streamingindhold fra et websted eller et program, der leverer webindhold. En hacker, som har held til at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163913">MS09-052</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Windows Media Player kan muliggøre fjernudførelse af kode (974112)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows Media Player. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en særligt udformet ASF-fil afspilles ved brug af Windows Media Player 6.4. En hacker, som har held til at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163979">MS09-054</a></td>
<td style="border:1px solid black;"><strong>Samlet sikkerhedsopdatering til Internet Explorer (974455)</strong><br />
<br />
Denne sikkerhedsopdatering løser tre privat rapporterede sårbarheder og én offentliggjort sårbarhed i Internet Explorer. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Firefox-brugere, der kører Windows Presentation Foundation (WPF)-plug-in og ikke har deaktiveret den, bør også anvende denne sikkerhedsopdatering. Hvis du ønsker flere oplysninger om dette problem, skal du se afsnittet med ofte stillede spørgsmål om sårbarhed i forbindelse med håndtering af HTML-komponent – CVE-2009-2529.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158202">MS09-055</a></td>
<td style="border:1px solid black;"><strong>Samlet sikkerhedsopdatering af kill-bitter for ActiveX (973525)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed, som er almindelig i flere ActiveX-objekter, og som i øjeblikket udnyttes. Den sårbarhed, der vedrører i ActiveX-objekter, som blev samlet ved brug af den sårbare version af Microsoft Active Template Library (ATL), kan muliggøre fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside med Internet Explorer, og dermed instantierer ActiveX-objektet. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160633">MS09-060</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i ATL-ActiveX-objekter til Microsoft Office kan muliggøre fjernudførelse af kode (973965)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i ActiveX-objekter til Microsoft Office, som blev samlet ved brug af en sårbar version af Microsoft Active Template Library (ATL). Sårbarhederne kan muliggøre fjernudførelse af kode, hvis en bruger har indlæst en særligt udformet komponent eller et særligt udformet objekt. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160527">MS09-061</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft .NET Common Language Runtime kan muliggøre fjernudførelse af kode (974378)</strong><br />
<br />
Denne sikkerhedsopdatering løser tre privat rapporterede sårbarheder i Microsoft .NET Framework og Microsoft Silverlight. Sårbarhederne kan muliggøre fjernudførelse af kode på et klientsystem, hvis en bruger får vist en særligt udformet webside ved brug af en webbrowser, der kører XAML Browser Applications (XBAP'er) eller Silverlight-programmer, eller hvis det lykkes en hacker at overtale en bruger til køre et særligt udformet Microsoft .NET-program. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Sårbarhederne kan derudover muliggøre fjernudførelse af kode på et serversystem, der kører IIS, hvis denne server giver mulighed for behandling af ASP.NET-sider, og det lykkes en hacker at uploade en særligt udformet ASP.NET-side til den pågældende server og køre den, som det f.eks. kan være tilfældet i et webhosting-scenarie. Microsoft .NET-programmer, Silverlight-programmer, XBAP'er og ASP.NET-sider, der ikke er skadelige, risikerer ikke at blive kompromitteret på grund af denne sårbarhed.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i GDI+ kan give mulighed for fjernudførelse af kode (957488)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i Microsoft Windows GDI+. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet billedfil med den pågælende software eller browser på en webside, der indeholder særligt udformet indhold. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer,<br />
Microsoft .NET Framework,<br />
Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft-udviklingsværktøjer,<br />
Microsoft Forefront</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=164004">MS09-053</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i FTP-tjenesten i Internet Information Services kan muliggøre fjernudførelse af kode (975254)</strong><br />
<br />
Denne sikkerhedsopdatering løser to offentliggjorte sårbarheder i FTP-tjenesten i Microsoft Internet Information Services (IIS) 5.0, Microsoft Internet Information Services (IIS) 5.1, Microsoft Internet Information Services (IIS) 6.0 og Microsoft Internet Information Services (IIS) 7.0. I IIS 7.0 berøres kun FTP Service 6.0. Sårbarhederne kan muliggøre fjernudførelse af kode (RCE) på systemer, der kører FTP-tjenesten på IIS 5.0, eller Denial-of-Service (DoS) på systemer, der kører FTP-tjenesten på IIS 5.0, IIS 5.1, IIS 6.0 eller IIS 7.0.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163830">MS09-056</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Windows CryptoAPI kan tillade spoofing (forfalskning) (974571)</strong><br />
<br />
Denne sikkerhedsopdatering løser to offentliggjorte sårbarheder i Microsoft Windows. Sårbarhederne kan give mulighed for spoofing, hvis en hacker får adgang til det certifikat, som slutbrugeren anvender til godkendelse.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Spoofing (forfalskning)</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163832">MS09-057</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i indekseringstjenesten kan give mulighed for fjernudførelse af kode (969059)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en hacker konfigurerer en skadelig webside, der aktiverer indekseringstjenesten via et opkald til dens ActiveX-komponent. Dette opkald kan omfatte en skadelig URL og udnytte sårbarheden, så hackeren får adgang til klientsystemet med de rettigheder, som den bruger, der gennemser websiden, har. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=162442">MS09-058</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Windows Kernel kan give mulighed for udvidelse af rettigheder (971486)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i Windows Kernel. Den mest alvorlige af sårbarhederne kan tillade en udvidelse af rettigheder, hvis en hacker er logget på systemet og har kørt et særligt udformet program. En hacker skal have gyldige logon-oplysninger og kunne logge på lokalt for at udnytte nogen af disse sårbarheder. Sårbarhederne kan ikke udnyttes vha. fjernadgang eller af anonyme brugere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163843">MS09-059</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Local Security Authority Subsystem Service kan give mulighed for Denial-of-Service (975467)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre Denial-of-Service, hvis en hacker har sendt en skadelig pakke under NTLM-godkendelsesprocessen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial-of-Service</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er opført i rækkefølge efter bulletin-id og CVE-id.

**Hvordan anvender jeg denne tabel?**  

Brug denne tabel til at få kendskab til sandsynligheden for, at fungerende exploit-kode udgives inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Du bør gennemse alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Bulletinens titel</th>
<th style="border:1px solid black;">CVE ID</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse</th>
<th style="border:1px solid black;">Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163970">MS09-050</a></td>
<td style="border:1px solid black;">Sårbarheder i SMBv2 kan give mulighed for fjernudførelse af kode (975517)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2526">CVE-2009-2526</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er en begrænset Denial-of-Service-sårbarhed.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163970">MS09-050</a></td>
<td style="border:1px solid black;">Sårbarheder i SMBv2 kan give mulighed for fjernudførelse af kode (975517)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2532">CVE-2009-2532</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163970">MS09-050</a></td>
<td style="border:1px solid black;">Sårbarheder i SMBv2 kan give mulighed for fjernudførelse af kode (975517)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3103">CVE-2009-3103</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Exploit-kode er blevet offentliggjort.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125438">MS09-051</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows Media Runtime kan give mulighed for fjernudførelse af kode (975682)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0555">CVE-2009-0555</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125438">MS09-051</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows Media Runtime kan give mulighed for fjernudførelse af kode (975682)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2525">CVE-2009-2525</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163913">MS09-052</a></td>
<td style="border:1px solid black;">En sårbarhed i Windows Media Player kan muliggøre fjernudførelse af kode (974112)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2527">CVE-2009-2527</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=164004">MS09-053</a></td>
<td style="border:1px solid black;">Sårbarheder i FTP-tjenesten i Internet Information Services kan muliggøre fjernudførelse af kode (975254)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2521">CVE-2009-2521</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er en Denial of Service-sårbarhed. Exploit-kode er blevet offentliggjort.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=164004">MS09-053</a></td>
<td style="border:1px solid black;">Sårbarheder i FTP-tjenesten i Internet Information Services kan muliggøre fjernudførelse af kode (975254)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3023">CVE-2009-3023</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Exploit-kode er blevet offentliggjort.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163979">MS09-054</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (974455)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1547">CVE-2009-1547</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163979">MS09-054</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (974455)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2529">CVE-2009-2529</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163979">MS09-054</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (974455)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2530">CVE-2009-2530</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">På Microsoft Windows 2000-systemer forøger manglende massebeskyttelse udnyttelsesindekset til <a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163979">MS09-054</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (974455)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2531">CVE-2009-2531</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158202">MS09-055</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering af kill-bitter for ActiveX (973525)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493">CVE-2009-2493</a></td>
<td style="border:1px solid black;">Ingen</td>
<td style="border:1px solid black;">(Denne sårbarhed er allerede blevet tildelt en vurdering under udnyttelsesindekset i <a href="http://technet.microsoft.com/security/bulletin/ms09-jul">oversigten over bulletin for juli</a>. Dette skyldes, at denne sårbarhed først blev behandlet i <a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a>). Se også det samme CVE-tal i <a href="http://go.microsoft.com/fwlink/?linkid=160633">MS09-060</a>.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163830">MS09-056</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows CryptoAPI kan tillade spoofing (forfalskning) (974571)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2510">CVE-2009-2510</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er en spoofing-sårbarhed (forfalskning).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163830">MS09-056</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows CryptoAPI kan tillade spoofing (forfalskning) (974571)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2511">CVE-2009-2511</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er en spoofing-sårbarhed (forfalskning).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163832">MS09-057</a></td>
<td style="border:1px solid black;">En sårbarhed i indekseringstjenesten kan muliggøre fjernudførelse af kode (969059)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2507">CVE-2009-2507</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=162442">MS09-058</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows Kernel kan give mulighed for udvidelse af rettigheder (971486)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2515">CVE-2009-2515</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=162442">MS09-058</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows Kernel kan give mulighed for udvidelse af rettigheder (971486)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2516">CVE-2009-2516</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Denne sårbarhed forårsager en Denial-of-Service-betingelse, når den målrettes ved brug af netværksdeling, samt en udvidelse af rettigheder, når den anvendes lokalt til at målrette et lokalt system.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=162442">MS09-058</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows Kernel kan give mulighed for udvidelse af rettigheder (971486)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2517">CVE-2009-2517</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er en Denial of Service-sårbarhed.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163843">MS09-059</a></td>
<td style="border:1px solid black;">En sårbarhed i Local Security Authority Subsystem Service kan give mulighed for Denial-of-Service (975467)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2524">CVE-2009-2524</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er en begrænset Denial-of-Service-sårbarhed.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160633">MS09-060</a></td>
<td style="border:1px solid black;">Sårbarheder i ATL-ActiveX-objekter til Microsoft Office kan muliggøre fjernudførelse af kode (973965)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901">CVE-2009-0901</a></td>
<td style="border:1px solid black;">Ingen</td>
<td style="border:1px solid black;">(Denne sårbarhed er allerede blevet tildelt en vurdering under udnyttelsesindekset i <a href="http://technet.microsoft.com/security/bulletin/ms09-jul">oversigten over bulletin for juli</a>. Dette skyldes, at denne sårbarhed først blev behandlet i <a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a>.)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160633">MS09-060</a></td>
<td style="border:1px solid black;">Sårbarheder i ATL-ActiveX-objekter til Microsoft Office kan muliggøre fjernudførelse af kode (973965)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493">CVE-2009-2493</a></td>
<td style="border:1px solid black;">Ingen</td>
<td style="border:1px solid black;">(Denne sårbarhed er allerede blevet tildelt en vurdering under udnyttelsesindekset i <a href="http://technet.microsoft.com/security/bulletin/ms09-jul">oversigten over bulletin for juli</a>. Dette skyldes, at denne sårbarhed først blev behandlet i <a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a>). Se også det samme CVE-tal i <a href="http://go.microsoft.com/fwlink/?linkid=158202">MS09-055</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160633">MS09-060</a></td>
<td style="border:1px solid black;">Sårbarheder i ATL-ActiveX-objekter til Microsoft Office kan muliggøre fjernudførelse af kode (973965)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495">CVE-2009-2495</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er en sårbarhed i forbindelse med afsløring af oplysninger.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160527">MS09-061</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft .NET Common Language Runtime kan muliggøre fjernudførelse af kode (974378)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0090">CVE-2009-0090</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160527">MS09-061</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft .NET Common Language Runtime kan muliggøre fjernudførelse af kode (974378)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0091">CVE-2009-0091</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=160527">MS09-061</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft .NET Common Language Runtime kan muliggøre fjernudførelse af kode (974378)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2497">CVE-2009-2497</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Der er risiko for internetpåvirkende angreb.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;">Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (957488)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2500">CVE-2009-2500</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;">Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (957488)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2501">CVE-2009-2501</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;">Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (957488)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2502">CVE-2009-2502</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;">Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (957488)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2503">CVE-2009-2503</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;">Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (957488)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2504">CVE-2009-2504</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;">Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (957488)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2518">CVE-2009-2518</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;">Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (957488)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2528">CVE-2009-2528</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=161342">MS09-062</a></td>
<td style="border:1px solid black;">Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (957488)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3126">CVE-2009-3126</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
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
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="13" style="border:1px solid black;">Microsoft Windows 2000</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163970">
                      <strong>MS09-050</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125438">
                      <strong>MS09-051</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163913">
                      <strong>MS09-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163979">
                      <strong>MS09-054</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158202">
                      <strong>MS09-055</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=164004">
                      <strong>MS09-053</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163830">
                      <strong>MS09-056</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163832">
                      <strong>MS09-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=162442">
                      <strong>MS09-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163843">
                      <strong>MS09-059</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Ingen</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b">DirectShow WMA Voice Codec</a>
                    <br />(KB969878)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f850a82-61f9-447b-a0aa-a2c192cc5d2e">Windows Media Audio Voice Decoder</a><br />(KB954155)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6dfd5405-cabe-4bd7-9330-b6bde1d99194">Audio Compression Manager</a><br />(KB975025)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13035ef7-7e47-487c-8b7c-7795d33ce7de">Microsoft Windows Media Player 6.4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26515c7b-d7a6-4405-96b5-a518dcb39d38">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8154ba37-0fbc-4d31-9d6e-0b21586ad65a">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=edfea805-9544-4dc0-a52c-d7594205657b">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01">Microsoft .NET Framework 2.0 Service Pack 1</a> (KB953300)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e">Microsoft .NET Framework 2.0 Service Pack 2</a> (KB974417)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3fef608-dafb-4b37-a65a-9cc4ae8e2c4c">Microsoft Internet Explorer 6 Service Pack 1</a>
                    <br />(KB958869)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ecf78619-80fa-417d-852b-1b5b2cf574e2">Microsoft .NET Framework 1.1 Service Pack 1</a><br />(KB971108)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e534aa8-29c2-4379-9f57-931a6ff47418">Microsoft .NET Framework 2.0 Service Pack 1</a><br />(KB971110)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6f5e730-85cc-4c08-a50d-c456b1e9f5bc">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB971111)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7fecd367-aaff-458b-91bc-8925c8e57528">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52b9198d-b65f-467a-a5ab-141e23d64a86">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b34d94b5-b828-4e16-a636-04344c60d945">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bdfa6583-28a2-4d6b-91d2-157a8518b664">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="13" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163970">
                      <strong>MS09-050</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125438">
                      <strong>MS09-051</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163913">
                      <strong>MS09-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163979">
                      <strong>MS09-054</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158202">
                      <strong>MS09-055</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=164004">
                      <strong>MS09-053</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163830">
                      <strong>MS09-056</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163832">
                      <strong>MS09-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=162442">
                      <strong>MS09-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163843">
                      <strong>MS09-059</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b">DirectShow WMA Voice Codec</a>
                    <br />(KB969878)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4516c219-e357-485e-a52b-23dcb8ee49d8">Windows Media Audio Voice Decoder</a><br />(KB954155)<br />(Kritisk)<br />(Kun Windows XP Service Pack 2)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=746d3440-5a6a-421e-9286-7b534a1dfe54">Windows Media Audio Voice Decoder</a><br />(KB954155)<br />(Kritisk)<br />(Kun Windows XP Service Pack 3)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ecc7129-8caa-4daf-a8e2-8f3536225fb3">Audio Compression Manager</a><br />(KB975025)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b2efe1ac-d8d7-41bb-b87d-fc5e22afef0f">Microsoft Windows Media Player 6.4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9aacf890-afb4-46a7-a13f-dd9fe3c0ca4a">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc166dc6-577f-4d8d-94df-dd963233dd85">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8799159d-df69-49f6-9db5-49147690ce0c">Windows Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=171d43d3-669c-4923-b266-e47591833c05">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1bc56c26-1c7c-47e3-94f4-37af7e00392c">Microsoft .NET Framework 1.0 Service Pack 3</a>
                    <br />(KB953295)<br />(Kritisk)<br />(Kun Tablet PC Edition 2005 og Media Center Edition 2005)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB953300)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB974417)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2acde20-a6d3-4135-b6eb-1214f743d474">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ae0bdd4-f8b2-420a-b1ac-d2cdaa87c828">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9c5ab624-e37b-418a-a919-d8f652b15679">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=768fd74e-0a2f-4353-ac22-65d0d6321739">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cece4c55-0756-4357-9d2d-6709e8426068">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e997ea40-668e-40df-bd50-0ca53437b375">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    [1]
                    <br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a">DirectShow WMA Voice Codec</a>
                    <br />(KB969878)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4729de51-8fd8-46c6-b4ad-9c9f25202684">Windows Media Audio Voice Decoder</a><br />(KB954155)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2">Windows Media Audio Voice Decoder</a> i Windows Media Format SDK 9.5 x64 Edition<br />(KB954155)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a866a490-6d3a-4ecd-acf4-770312ba2fd6">Windows Media Audio Voice Decoder</a> i Windows Media Format SDK 11<br />(KB954155)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b">Audio Compression Manager</a><br />(KB975025)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a9e7dfd8-7ba1-4f14-8e60-92ef00d91467">Microsoft Windows Media Player 6.4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89a2cf2a-a7a2-4d4b-aa6f-24dde288d500">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd54e595-25f2-4839-a838-2a0f809bde2b">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77b18fc2-e769-47c6-8e72-916716a49e58">Windows Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c08623bf-94bc-4c50-8c10-f50fb8448a0b">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB953300)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB974417)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad92503a-8c91-4d73-98b0-942d7961637d">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=819dd2d1-cad5-4784-9baf-185d8a76df5d">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad29696d-4611-4a12-9dfa-74fa6866b759">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=270ec100-5ba1-4f8c-aa36-105d30ad57bf">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5459b7d4-1fab-4a04-ab9d-b8323505c1e2">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17008892-7950-44c4-850d-002c8d73495f">Windows XP Professional x64 Edition Service Pack 2</a>
                    [1]
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="13" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163970">
                      <strong>MS09-050</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125438">
                      <strong>MS09-051</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163913">
                      <strong>MS09-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163979">
                      <strong>MS09-054</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158202">
                      <strong>MS09-055</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=164004">
                      <strong>MS09-053</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163830">
                      <strong>MS09-056</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163832">
                      <strong>MS09-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=162442">
                      <strong>MS09-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163843">
                      <strong>MS09-059</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4fe0dff5-04d9-4409-8d1d-52419537126b">DirectShow WMA Voice Codec</a>
                    <br />(KB969878)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00b3cb86-c9eb-4fbe-987e-2b0d94271d87">Windows Media Audio Voice Decoder</a><br />(KB954155)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab1803ff-2371-487f-a7b6-95747c46ba4e">Audio Compression Manager</a><br />(KB975025)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f82d01c-573e-425e-b9f2-86a54f377b19">Microsoft Windows Media Player 6.4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8101625d-ee93-46e5-aec2-3bdbf2d86472">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4647bcf1-69fb-4ad6-9e03-7bc22d8a914b">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9eae7eca-1a6f-4397-a6e2-7dda6b9d5276">Windows Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3249c99-82e4-45dc-a254-28e647e822c8">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1b4a58b-f0b1-4400-a6e6-0255b0513bd1">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953298)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB953300)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB974417)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=414466a4-39a0-476d-9a43-ae7674cbd6a0">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48256ea3-b433-4e84-9019-22300069cfc1">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78072164-84d1-44da-8ede-2a9d212d47a9">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3f3842-f8fd-4969-a2cf-706db38d7580">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9dff4662-7771-4bdc-87ec-7899d79b3a55">Windows Server 2003 Service Pack 2</a>
                    [1]
                    <br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a">DirectShow WMA Voice Codec</a>
                    <br />(KB969878)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13ba4839-7fa9-4bbb-95f6-3fafb6c49f20">Windows Media Audio Voice Decoder</a><br />(KB954155)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2">Windows Media Audio Voice Decoder</a> i Windows Media Format SDK 9.5 x64 Edition<br />(KB954155)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b">Audio Compression Manager</a><br />(KB975025)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=65e9036e-2e1b-40ff-a84b-c507107bcce8">Microsoft Windows Media Player 6.4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f966053-01eb-4a23-a9d5-71deac2498ea">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7d77bd9-8317-42f3-9ad1-a0b8bfa65b53">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=708a549d-11fd-43bf-a6e1-309e3205d59d">Windows Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ad3f7b3-58d5-4507-ae20-a265e47cee9c">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB953300)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB974417)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eb95e8d9-6ef5-4526-99d2-507e50de049b">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=61bded07-201e-4815-ac1e-468bf907e063">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8aa1f97d-ad53-4450-bb93-4a147dd10a87">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95286b8d-4b53-4e6c-af59-e9e18fad3559">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8df7a2d9-2f97-4f18-84e8-415a1632cf09">Windows Server 2003 x64 Edition Service Pack 2</a>
                    [1]
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79a1a94d-3b47-47e9-9476-2f591c3f6a59">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=07e66c09-2cd7-47ba-bf87-d3da602184b4">Windows Internet Explorer 7</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=575e75d9-e348-4fbb-9eaa-43240e4d715e">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB953300)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=491874d4-5eea-4545-9b7d-3861857c862e">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB974417)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a678ceb9-a37a-4c29-8bd1-f209922990e5">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b99d4d9b-e0cc-4a8c-ad99-6a53958b37c8">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ede1eb9-7f5f-411d-bbc3-5db46d80e0bb">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fb5678b9-5ef1-42db-902e-c9ea02880e0a">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faef714b-5f46-47f2-bea7-881df05a1bc0">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83c77015-7f96-4c0d-bd56-60aef90ea2f8">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    [1]
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="13" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163970">
                      <strong>MS09-050</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125438">
                      <strong>MS09-051</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163913">
                      <strong>MS09-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163979">
                      <strong>MS09-054</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158202">
                      <strong>MS09-055</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=164004">
                      <strong>MS09-053</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163830">
                      <strong>MS09-056</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163832">
                      <strong>MS09-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=162442">
                      <strong>MS09-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163843">
                      <strong>MS09-059</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Vista</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29842c0c-8930-4b5f-83c6-1a718974b63f">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f17ee0ea-f1e2-49f4-9f90-60296246ddfe">Windows Media Audio Voice Decoder</a>
                    <br />(KB954155)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6995616-2a84-4c26-9599-26f1314873ed">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8f6014f-950b-4e11-a105-51d298069f1a">Windows Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7313c03b-8844-4086-a0cc-43dfdb3ca48c">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63">Microsoft .NET Framework 2.0</a> (KB974468)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB974292)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB974467)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19aa01f3-026d-4264-85f8-216d0597969b">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb96eb1c-66a2-4276-9773-eea22179bcd4">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b5a9a95-9439-40c8-acef-000b919daa04">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04ae306b-0d0d-4767-ab54-cc11aec477ed">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista Service Pack 1</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda">Microsoft .NET Framework 2.0 Service Pack 1</a> (KB974291)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB974469)<br />(Kritisk)</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista Service Pack 2</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4">Microsoft .NET Framework 2.0 Service Pack 2</a> (KB974470)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97">Windows Vista Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Som anført ovenfor</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62ed5d0a-5ca6-4942-80c9-7808b14cb6b5">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26905f12-92c7-4d45-99e7-227f03d2cb82">Windows Media Audio Voice Decoder</a>
                    <br />(KB954155)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3de5236-afdd-436e-8648-5382d564cc99">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85978f28-5fc0-481b-9b03-2021c785889b">Windows Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7216bcb1-ff16-402b-ad1b-1500d46d0157">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f99521e-86b3-4083-9132-e5ac06d40b63">Microsoft .NET Framework 2.0</a> (KB974468)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a> (KB974292)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB974467)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f5f0c1d-1dd6-47fa-aef2-d3c96c8fc06e">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bce096c8-833b-45c8-99cd-1280f0744f2f">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4a60f789-1a4a-49a8-8d13-fda989ed40be">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58c995ca-f308-4e07-8e60-2e542384d95d">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 1</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda">Microsoft .NET Framework 2.0 Service Pack 1</a> (KB974291)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB974469)<br />(Kritisk)</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a> (KB953297)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4">Microsoft .NET Framework 2.0 Service Pack 2</a> (KB974470)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Som anført ovenfor</td></tr>
              
                <tr><th colspan="13" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163970">
                      <strong>MS09-050</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125438">
                      <strong>MS09-051</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163913">
                      <strong>MS09-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163979">
                      <strong>MS09-054</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158202">
                      <strong>MS09-055</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=164004">
                      <strong>MS09-053</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163830">
                      <strong>MS09-056</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163832">
                      <strong>MS09-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=162442">
                      <strong>MS09-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163843">
                      <strong>MS09-059</strong>
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
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til 32 bit-systemer </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ff6bfcf3-76c9-4c45-b57d-22f94458dd6e">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eaa9857-a147-4f31-9bf4-b9e2cf4c15c3">Windows Media Audio Voice Decoder</a>**<br />(KB954155)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72dd580e-eb53-41da-a5c0-a392ad388bfc">Windows Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1baf7e96-ba3e-47e7-8ea3-eb092e653a39">Windows Internet Explorer 8</a>**<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51eb56fa-8204-45f3-86d7-6d03a2c8d78d">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>**<br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB953297)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda">Microsoft .NET Framework 2.0 Service Pack 1</a>**<br />(KB974291)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB974469)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd1694af-8873-43aa-9243-91f7cde452b7">Windows Server 2008 til 32 bit-systemer</a>**<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9c5039f-d0cf-4d84-850f-f2f7701dcb79">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f9b487af-fe73-42a8-b240-d59c4321f95b">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423">Windows Server 2008 til 32 bit-systemer</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f2f617c2-f149-4e9b-bfdd-08ed0f3f99db">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB953297)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB974470)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71aec6f6-a36b-465e-8885-b094dfd30423">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Moderat)</td><td style="border:1px solid black;">Som anført ovenfor</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aff6f9c7-4a72-48f2-b750-204d796c7daa">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70aabba3-53d6-4b52-be83-6d3f3869ecbd">Windows Media Audio Voice Decoder</a>**<br />(KB954155)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0111d741-bda4-4a50-a12b-d3337ff4441d">Windows Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a4b755b-7fa0-43aa-8862-c1d0c7d94c2c">Windows Internet Explorer 8</a>**<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=131b047a-ae93-4a99-83e5-71d5a79e96ea">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>**<br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB953297)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda">Microsoft .NET Framework 2.0 Service Pack 1</a>**<br />(KB974291)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB974469)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41bc4cdb-273a-4a6e-80d9-c8ce20e32da9">Windows Server 2008 til x64-baserede systemer</a>**<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=db969ddc-708e-42b7-9956-6c27bf346bbb">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d8a2a3e-d7d4-47fb-8364-16fce28e4d38">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94">Windows Server 2008 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=deb84cb8-2ba3-47e3-9185-2bbc5b0a7e18">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB953297)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB974470)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88f4189f-71fe-404a-869e-3f76692acf94">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Moderat)</td><td style="border:1px solid black;">Som anført ovenfor</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b70108b-7f59-4898-ab4e-76be990de878">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e81f30b7-ef05-4488-b62a-d330e17129cf">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d16c5bf-ee5c-4220-9755-5cb92eac2aae">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB953297)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30e5410d-0942-4964-9037-52330488efda">Microsoft .NET Framework 2.0 Service Pack 1</a><br />(KB974291)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB974469)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a4f42085-1cb9-4b8d-a931-85be71fdf06d">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a221451a-cb4e-4a43-a225-4b1e86e87525">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8962f0b6-f346-4e88-9d83-4d15b699dd9d">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aac0e3e-9b49-4a4a-ab17-707ff03b4d9b">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB953297)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB974470)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Som anført ovenfor</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Som anført ovenfor</td></tr>
              
                <tr><th colspan="13" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163970">
                      <strong>MS09-050</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125438">
                      <strong>MS09-051</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163913">
                      <strong>MS09-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163979">
                      <strong>MS09-054</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158202">
                      <strong>MS09-055</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=164004">
                      <strong>MS09-053</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163830">
                      <strong>MS09-056</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163832">
                      <strong>MS09-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=162442">
                      <strong>MS09-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163843">
                      <strong>MS09-059</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows 7 Beta til 32-bit-systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89d1fb78-68cd-48dd-afc2-15a79ebe9fde">Windows Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b64bcc14-38a7-45b9-8f85-acc573777506">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB953297)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad6f06d5-27db-445d-a8b2-c42adc90afc0">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35b85783-90df-4f67-a3cb-02351432133e">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 til x64-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=10d9f7ac-65f4-437c-91cc-171632c69b0e">Windows Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=809e29f3-ec68-4a2b-b04e-11759dd16001">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB953297)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70cd0270-77e9-492a-82d9-798364640c10">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=97010f2c-6c10-4fda-84fd-6c8749968db5">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="13" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163970">
                      <strong>MS09-050</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125438">
                      <strong>MS09-051</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163913">
                      <strong>MS09-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163979">
                      <strong>MS09-054</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158202">
                      <strong>MS09-055</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=164004">
                      <strong>MS09-053</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163830">
                      <strong>MS09-056</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163832">
                      <strong>MS09-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=162442">
                      <strong>MS09-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163843">
                      <strong>MS09-059</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f50307d6-7869-4996-9ff7-23f87d08994b">Windows Internet Explorer 8</a>**<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bcd2b944-6852-48f2-820b-cce7d195e391">Windows Server 2008 R2 til x64-baserede systemer</a>**<br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB953297)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce78c019-ec08-4ec6-abec-334f5ec5cb76">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=597ac3a7-e02d-49a5-9b8e-d097e867acea">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 til Itanium-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b6a28ae-b3f2-42b0-8209-e3950ec37abb">Windows Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85e76e55-3766-4ffe-9a18-8655de935b7c">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB953297)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6442a77a-3c0d-4beb-b2d2-2885376c2135">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=abc94857-37d8-4bb8-ad9e-46e687fca40e">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i MSDN-artiklerne [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core til Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i MSDN-artiklerne [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core til Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkning til MS09-061**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

**Bemærkninger til MS09-062**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

**Bemærkning til MS09-059**

\[1\]Dette operativsystem berøres kun, når KB968389, Udvidet beskyttelse til godkendelse (se [Microsoft-sikkerhedsmeddelelse 973811](microsoft-security-advisory-973811.md)), er installeret. Yderligere oplysninger finder du i den post i Ofte stillede spørgsmål, der vedrører denne sikkerhedsopdatering i [MS09-059](http://go.microsoft.com/fwlink/?linkid=163843).

#### Micorsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office Suites, systemer og komponenter</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160633">
                      <strong>MS09-060</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
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
                <tr><td style="border:1px solid black;">Microsoft Office XP</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04878c2c-eb97-426f-be08-89036a6799db">Microsoft Outlook 2002 Service Pack 3</a>
                    <br />(KB973702)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d">Microsoft Office XP Service Pack 3</a>
                    [2]
                    <br />(KB974811)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2003</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79e2b2e8-d5e8-4014-b489-720af2b5083d">Microsoft Office Outlook 2003 Service Pack 3</a>
                    <br />(KB973705)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7">Microsoft Office 2003 Service Pack 3</a>
                    [3]
                    <br />(KB972580)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">2007 Microsoft Office System</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d39234a3-c62c-44ba-a626-3179a183ca09">Microsoft Office Outlook 2007 Service Pack 1 og Microsoft Office Outlook 2007 Service Pack 2</a>
                    <br />(KB972363)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec">2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2</a>
                    [4]
                    <br />(KB972581)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Øvrigt Microsoft Office-software</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160633">
                      <strong>MS09-060</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
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
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visio</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=920ee70b-c5c1-47b5-8f33-938ffe14eea4">Microsoft Visio 2002 Service Pack 2</a>
                    <br />(KB975365)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Visio Viewer</td><td style="border:1px solid black;">Microsoft Visio 2002 Viewer[1]<br />(Kritisk)<br /><br />Microsoft Office Visio 2003 Viewer[1]<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d20004c5-dd01-459e-8120-5f127e20c085">Microsoft Office Visio Viewer 2007 Service Pack 1 og Microsoft Office Visio Viewer 2007 Service Pack 2</a><br />(KB973709)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec">Microsoft Office Visio Viewer 2007 Service Pack 1 og Microsoft Office Visio Viewer 2007 Service Pack 2</a>
                    [4]
                    <br />(KB972581)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Project</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d">Microsoft Office Project 2002 Service Pack 1</a>
                    [2]
                    <br />(KB974811)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Word Viewer, Microsoft Office Excel Viewer og Microsoft PowerPoint Viewer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48752ab4-5928-476d-a8bc-e998d188b1f7">Microsoft Word Viewer 2003 Service Pack 3 og Microsoft Office Excel Viewer 2003 Service Pack 3</a>
                    [3]
                    <br />(KB972580)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec">Microsoft Office Excel Viewer Service Pack 2</a>[4]<br />(KB972581)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec">PowerPoint Viewer 2007 Service Pack 2</a>[4]<br />(KB972581)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1 og Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 2</a>
                    [4]
                    <br />(KB972581)<br />Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Works</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f96de9a-62d8-428f-9567-51d55c129be6">Microsoft Works 8.5</a>
                    <br />(KB973636)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til MS09-060**

\[1\]Microsoft anbefaler, at brugere af Microsoft Visio Viewer 2002 og Microsoft Visio Viewer 2003 opgraderer til Microsoft Office Visio Viewer 2007 Service Pack 2.

**Bemærkninger til MS09-062**

\[2\]Disse opdateringer er identiske.

\[3\]Disse opdateringer er identiske.

\[4\]Disse opdateringer er identiske.

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Microsoft Server-software

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="2" style="border:1px solid black;">Microsoft SQL Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2000 Reporting Services Service Pack 2</td><td style="border:1px solid black;">GDR-opdatering<br />Ikke relevant<br /><br />QFE-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=33554f96-5af7-4683-a537-9db293b67b8d">SQL Server 2000 Reporting Services Service Pack 2</a><br />(KB970899)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 Service Pack 2</td><td style="border:1px solid black;">GDR-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23">SQL Server 2005 Service Pack 2</a>[1]<br />(KB970895)<br />(Kritisk)<br /><br />QFE-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235">SQL Server 2005 Service Pack 2</a>[1]<br />(KB970896)<br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 x64 Edition Service Pack 2</td><td style="border:1px solid black;">GDR-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23">SQL Server 2005 x64 Edition Service Pack 2</a>[1]<br />(KB970895)<br />(Kritisk)<br /><br />QFE-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235">SQL Server 2005 x64 Edition Service Pack 2</a>[1]<br />(KB970896)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 for Itanium-baserede systemer med Service Pack 2</td><td style="border:1px solid black;">GDR-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23">SQL Server 2005 til Itanium-baserede systemer med Service Pack 2</a>[1]<br />(KB970895)<br />(Kritisk)<br /><br />QFE-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235">SQL Server 2005 til Itanium-baserede systemer med Service Pack 2</a>[1]<br />(KB970896)<br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 Service Pack 3</td><td style="border:1px solid black;">GDR-opdatering<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce">SQL Server 2005 Service Pack 3</a>[2]<br />(KB970892)<br />(Kritisk)<br /><br />QFE-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f">SQL Server 2005 Service Pack 3</a>[2]<br />(KB970894)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 x64 Edition Service Pack 3</td><td style="border:1px solid black;">GDR-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce">SQL Server 2005 x64 Edition Service Pack 3</a>[2]<br />(KB970892)<br />(Kritisk)<br /><br />QFE-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f">SQL Server 2005 x64 Edition Service Pack 3</a>[2]<br />(KB970894)<br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 til Itanium-baserede systemer Service Pack 3</td><td style="border:1px solid black;">GDR-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d878f4b-71e8-4170-9a14-1bce684811ce">SQL Server 2005 til Itanium-baserede systemer Service Pack 3</a>[2]<br />(KB970892)<br />(Kritisk)<br /><br />QFE-opdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f">SQL Server 2005 til Itanium-baserede systemer Service Pack 3</a>[2]<br />(KB970894)<br />(Kritisk)</td></tr>
              </table>


**Bemærkning til MS09-062**

\[1\]SQL Server 2005 Service Pack 2-kunder med en Reporting Services SharePoint-afhængighed skal også installere [Microsoft SQL Server 2005 Reporting Services Add-in for Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=%20f4d4d0ae-e5d4-4ed1-8d78-7137578161ce&displaylang=en) fra Microsoft Download Center.

\[2\]SQL Server 2005 Service Pack 3-kunder med en Reporting Services SharePoint-afhængighed skal også installere [Microsoft SQL Server 2005 Reporting Services Add-in for Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=%20648766ac-2a35-4238-a3f4-c26d7077f2a9&displaylang=en) fra Microsoft Download Center.

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Udviklingsværktøjer og software fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Silverlight</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Silverlight</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/silverlight/get-started/install/default.aspx">Microsoft Silverlight 2</a>
                    [1] når det installeres på Mac<br />(KB970363)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Silverlight</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/silverlight/get-started/install/default.aspx">Microsoft Silverlight 2</a>
                    [1] når det installeres på alle udgivelser af Microsoft Windows-klienter<br />(KB970363)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Silverlight</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/silverlight/get-started/install/default.aspx">Microsoft Silverlight 2</a>
                    [1] når det installeres på alle udgivelser af Microsoft Windows-servere**<br />(KB970363)<br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Visual Studio</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visual Studio .NET 2003 Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e3b52d3-b211-4d62-891c-ae8f2e4ffc6c">Microsoft Visual Studio .NET 2003 Service Pack 1</a>
                    <br />(KB971022)<br />(Ingen klassifikation[2])</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Visual Studio 2005 Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e186aeed-e9d7-4a02-84b3-bbed116ca060">Microsoft Visual Studio 2005 Service Pack 1</a>
                    <br />(KB971023)<br />(Ingen klassifikation[2])</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visual Studio 2008</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4fa10c93-ce20-43df-a725-ef4c77353747">Microsoft Visual Studio 2008</a>
                    <br />(KB972221)<br />(Ingen klassifikation[2])</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Visual Studio 2008 Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b904dee8-8a26-43f8-8ca9-86ad12cfdb52">Microsoft Visual Studio 2008 Service Pack 1</a>
                    <br />(KB972222)<br />(Ingen klassifikation[2])</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visual FoxPro 8.0 Service Pack 1 ved installation på Microsoft Windows 2000 Service Pack 4<br />(KB971104)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5d0d515-4b36-4025-bc6f-1c5cdf09e1af">Microsoft Visual FoxPro 8.0 Service Pack 1</a>
                    <br />ved installation på Microsoft Windows 2000 Service Pack 4<br />(KB971104)<br />(Ingen klassifikation[2])</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Visual FoxPro 9.0 Service Pack 2 ved installation på Microsoft Windows 2000 Service Pack 4<br />(KB971105)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a930f56-59ac-49a6-830f-bfae7c540ec7">Microsoft Visual FoxPro 9.0 Service Pack 2</a>
                    <br />ved installation på Microsoft Windows 2000 Service Pack 4<br />(KB971105)<br />(Ingen klassifikation[2])</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Report Viewer</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=160527">
                      <strong>MS09-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0dfaf300-2b53-4678-a779-0d805ddfe538">Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package</a>
                    <br />(KB971117)<br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Report Viewer 2008 Redistributable Package</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=42ed040f-cf94-4754-b0b3-c8016fbcbe22">Microsoft Report Viewer 2008 Redistributable Package</a>
                    <br />(KB971118)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Report Viewer 2008 Redistributable Package Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6aaa74bd-a46e-4478-b4e1-2063d18d2d42">Microsoft Report Viewer 2008 Redistributable Package Service Pack 1</a>
                    <br />(KB971119)<br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Platform SDK Redistributable: GDI+</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a">Microsoft Platform SDK Redistributable: GDI+</a>
                    <br />(KB975337)<br />(Ingen klassifikation[2])</td></tr>
              </table>


**Bemærkninger til MS09-061**

\[1\]Denne opdatering opgraderer Microsoft Silverlight 2 til Microsoft Silverlight 3, hvilket løser den sårbarhed, der beskrives i bulletinen.

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i MSDN-artiklerne [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core til Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

**Bemærkninger til MS09-062**

\[2\]Klassifikationer gælder ikke for denne opdatering, idet Microsoft ikke har identificeret nogen angrebsvektorer i forbindelse med de sårbarheder, der omtales i denne bulletin, specifikt for denne software. Denne sikkerhedsopdatering tilbydes imidlertid til udviklere, der bruger denne software, så de kan udsende deres egen opdaterede version af deres programmer.

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Microsoft Security Software

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Forefront Security</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=161342">
                      <strong>MS09-062</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Forefront Client Security 1.0</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c0ce624c-8df3-4223-8a7a-5cba4ac334a8">Microsoft Forefront Client Security 1.0</a>
                    <br />ved installation på Microsoft Windows 2000 Service Pack 4<br />(KB975962)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til MS09-062**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Bemærk**\! Fra 1. august 2009 stopper Microsoft supporten til Office Update og Office Update Inventory Tool. Hvis du stadig vil have de seneste opdateringer til Microsoft Office-produkter, skal du anvende [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Hvis du vil have flere oplysninger, skal du se [Om Microsoft Office Update: Ofte stillede spørgsmål](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Vejledning i registrering og implementering**

Microsoft giver vejledning i registrering og implementering af sikkerhedsopdateringer. Denne vejledning indeholder anbefalinger og oplysninger, som it-fagfolk kan bruge til bedre at forstå, hvordan de skal anvende forskellige værktøjer til registrering og implementering af sikkerhedsopdateringer. Yderligere oplysninger finder du i [Microsoft Knowledge Base-artiklen 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) giver administratorer mulighed for at søge på lokale systemer og fjernsystemer efter manglende sikkerhedsopdateringer samt almindelige fejl ved sikkerhedskonfigurationer. Hvis du ønsker yderligere oplysninger om MBSA, kan du besøge webstedet [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

**Systems Management Server**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere. Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig, se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Få mere at vide om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsoplysninger, på [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brugere kan også bruge SUIT (Security Update Inventory Tool) ved implementering af sikkerhedsopdateringer. Oplysninger om SMS findes på [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Bemærk\!** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til at installere disse opdateringer.

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

  - [Matthieu Suiche](http://www.msuiche.net/) fra [Netherlands Forensics Institute](http://www.nederlandsforensischinstituut.nl/) for at rapportere et problem, der er beskrevet i MS09-050
  - Ivan Fratric fra [Zero Day Initiative](http://www.zerodayinitiative.com/) og Jun Xie fra [McAfee Avert Labs](http://www.avertlabs.com/) for at rapportere et problem, der er beskrevet i MS09-051
  - Vinay Anantharaman fra [Adobe Systems, Inc.](http://www.adobe.com/) for at rapportere et problem, der er beskrevet i MS09-051
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at rapportere et problem, der er beskrevet i MS09-052
  - SkyLined fra [Google Inc.](http://www.google.com/) for at rapportere et problem, der er beskrevet i MS09-054
  - Mark Dowd fra [IBM ISS X-Force](http://www.iss.net/) for at have rapporteret et problem, der er beskrevet i MS09-054
  - [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at rapportere et problem, der er beskrevet i MS09-054
  - Sam Thomas eshu.co.uk, der arbejder med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS09-054
  - Ian Wright og Jean-Luc Giraud fra [Citrix](http://www.citrix.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS09-056
  - Dan Kaminsky fra [IOActive](http://www.ioactive.com/) for at have rapporteret to problemer beskrevet i MS09-056
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at rapportere et problem, der er beskrevet i MS09-057
  - Tavis Ormandy og Neel Mehta fra [Google Inc.](http://www.google.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS09-058
  - [NSFocus Security Team](http://www.nsfocus.com/) for at rapportere et problem, der er beskrevet i MS09-058
  - David Dewey fra [IBM ISS X-Force](http://www.iss.net/) for at rapportere et problem, der er beskrevet i MS09-060
  - Ryan Smith fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS09-060
  - [Pavel Minaev](http://int19h.org/) for at rapportere et problem, der er beskrevet i MS09-061
  - Jeroen Frijters fra [Sumatra](http://www.sumatra.nl/) for at rapportere et problem, der er beskrevet i MS09-061
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at rapportere et problem, der er beskrevet i MS09-062
  - Thomas Garnier fra [SkyRecon](http://www.skyrecon.com/) for at rapportere et problem, der er beskrevet i MS09-062
  - Wushi fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem, der er beskrevet i MS09-062
  - Ivan Fratric fra [Zero Day Initiative](http://www.zerodayinitiative.com/) for at rapportere et problem, der er beskrevet i MS09-062
  - Tavis Ormandy fra [Google Inc.](http://www.google.com/) for at arbejde sammen med os om to problemer, der er beskrevet i MS09-062
  - Carlo Di Dato (aka shinnai) for at rapportere et problem, der er beskrevet i MS09-062
  - Marsu Pilami fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem, der er beskrevet i MS09-062
  - Carsten H. Eiram fra [Secunia](http://secunia.com/) for at rapportere et problem, der er beskrevet i MS09-062

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (13. oktober 2009): Oversigt over bulletin offentliggjort.
  - V1.1 (14. oktober 2009): Download-link til Windows XP x64 Edition Service Pack 2 til MS09-055 er korrigeret.
  - V1.2 (18. oktober 2009): Reviderede resumé for MS09-054 for at give vejledning til Firefox-brugere.
  - V2.0 (28. oktober 2009): Tilføjet Microsoft Office Visio Viewer 2007, Microsoft Office Visio Viewer 2007 Service Pack 1 og Microsoft Office Visio Viewer 2007 Service Pack 2 som software, der er berørt af MS09-062, og yderligere bemærkninger til MS09-062 vedr. SQL Server 2005-kunder med Reporting Services SharePoint-afhængighed.
  - V3.0 (2. november 2009): Revideret for at annoncere tilgængeligheden af et hotfix til MS09-054 til løsning af problemer med programkompatibilitet. Kunder, der allerede har benyttet denne opdatering, kan installere hotfix'et fra Microsoft Knowledge Base-artikel 976749.
  - V3.1 (4. november 2009): Fjernede fejlagtig henvisning til den oprindeligt udsendte version af Microsoft Office Visio Viewer 2007 som berørt software i MS09-060 og MS09-062.
  - V4.0 (10. november 2009): Bulletinen er blevet revideret for at oplyse om genudsendelsen af opdateringen til Audio Compression Manager på Microsoft Windows 2000 Service Pack 4 i MS09-051 til løsning af et registreringsproblem. Dette er udelukkende en registreringsændring. Der er ikke foretaget ændringer i de binære koder. Kunder, der har opdateret deres systemer uden problemer, behøver ikke at geninstallere denne opdatering.
  - V4.1 (12. januar 2010): Microsoft Expression Web, Microsoft Expression Web 2, Microsoft Office Groove 2007 og Microsoft Office Groove 2007 Service Pack 1 er blevet fjernet som berørte programmer for MS09-062.

*Built at 2014-04-18T01:50:00Z-07:00*

