---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for juli 2009
TOCTitle: MS09-JUL
ms:assetid: ms09-jul
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms09-jul(v=Security.10)
ms:contentKeyID: 61224053
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for juli 2009

Offentliggjort: 14. juli 2009 | Opdateret: 12. januar 2010

**Version:** 7.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for juli 2009.

Med udgivelsen af bulletiner for juli 2009 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 9. juli 2009. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 15. juli 2009 kl. 11:00 Pacific Time (USA og Canada). Dette webcast er tilgængeligt ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Angående den out-of-band-sikkerhedsbulletin, der er blevet tilføjet Version 2.0 af denne bulletinoversigt, MS09-034 og MS09-035, afholder Microsoft to webcasts for at behandle kundernes spørgsmål til disse bulletiner den 28. juli 28 2009 kl. 13:00 Pacific Time (USA og Canada) samt kl. 16:00 Pacific Time (USA og Canada). Tilmeld dig nu til [webcastet den 28. juli kl. 13:00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422339&culture=en-us) og [webcastet den 28. juli kl. 16:00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422341&culture=en-us). Herefter kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Embedded OpenType Font Engine kan tillade fjernudførelse af kode (961371)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Windows-komponenten, Embedded OpenType (EOT) Font Engine. Disse sårbarheder kan muliggøre fjernudførelse af kode. En hacker, som har held til at udnytte en af disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft DirectShow kan muliggøre fjernudførelse af kode (971633)</strong><br />
<br />
Denne sikkerhedsopdatering løser én offentliggjort sårbarhed og to privat rapporterede sårbarheder i Microsoft DirectShow. Sårbarhederne kan muliggøre fjernudførelse af kode, hvis en bruger har åbnet en særligt udformet QuickTime-mediefil. En hacker, som det lykkes at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157386">MS09-032</a></td>
<td style="border:1px solid black;"><strong>Samlet sikkerhedsopdatering af kill-bitter for ActiveX (973346)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed, der i øjeblikket udnyttes. Sårbarheden i Microsoft Video ActiveX Control kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside med Internet Explorer og initierer ActiveX-kontrollen. Det har aldrig været hensigten, at ActiveX-kontrol skulle instantieret i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td style="border:1px solid black;"><strong>Samlet sikkerhedsopdatering til Internet Explorer (972260)</strong><br />
<br />
Denne sikkerhedsopdatering udsendes i forbindelse med Sikkerhedsbulletin fra Microsoft MS09-035, som beskriver sårbarheder i de komponenter og objekter, der er blevet udviklet ved brug af sårbare versioner af Microsoft Active Template Library (ATL). Som gennemgribende beskyttelsesforanstaltning hjælper denne sikkerhedsopdatering til Internet Explorer med at afhjælpe kendte angrebsvektorer i Internet Explorer for de komponenter og kontroller, der er blevet udviklet ved brug af sårbare versioner af ATL som beskrevet i Microsoft-sikkerhedsmeddelelse (973882) og Sikkerhedsbulletin fra Microsoft MS09-035.<br />
<br />
Denne sikkerhedsopdatering løser også tre privat rapporterede sårbarheder i Internet Explorer. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=153891">MS09-033</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Virtual PC og Virtual Server kan muliggøre udvidelse af rettigheder (969856)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Virtual PC og Microsoft Virtual Server. En hacker, som har held til at udnytte denne sårbarhed, kan udføre arbitrær kode og få fuld kontrol over et berørt gæsteoperativsystem. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Virtual PC, Virtual Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=154993">MS09-031</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft ISA Server 2006 kan muliggøre udvidelse af rettigheder (970953)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Internet Security and Acceleration (ISA) Server 2006. Sårbarheden kan give mulighed for udvidelse af rettigheder, hvis en hacker har held til at generere en administrativ brugerkonto til en ISA- server, der er konfigureret til OTP-godkendelse (Radius One Time Password) og godkendelsesdelegation med Kerberos Constrained Delegation.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft ISA Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147424">MS09-030</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft Office Publisher kan muliggøre fjernudførelse af kode (969516)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Office Publisher, som kan muliggøre fjernudførelse af kode, når en bruger åbner en særligt udformet Publisher-fil. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Visual Studio Active Template Library kan tillade fjernudførelse af kode (969706)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i offentlige versioner af Microsoft Active Template Library (ATL), der findes i Visual Studio. Denne sikkerhedsopdatering henvender sig særligt til udviklere af komponenter og objekter. Udviklere, der opbygger og videredistribuerer komponenter og objekter ved brug af ATL, bør installere den opdatering, der medfølger i denne bulletin, og de bør følge de medfølgende retningslinjer i forhold til oprettelse og distribuering af komponenter og objekter, som ikke er sårbare overfor de sårbarheder, der er beskrevet i denne bulletin, til deres kunder.<br />
<br />
Denne sikkerhedsbulletin omhandler sårbarheder, der kan muliggør fjernudførelse af kode, hvis en bruger indlæser en komponent eller et objekt, der er blevet opbygget ved brug af sårbare versioner af ATL.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft DirectShow kan muliggøre fjernudførelse af kode (971633)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1537">CVE-2009-1537</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft DirectShow kan muliggøre fjernudførelse af kode (971633)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1538">CVE-2009-1538</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft DirectShow kan muliggøre fjernudførelse af kode (971633)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1539">CVE-2009-1539</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td style="border:1px solid black;">Sårbarheder i Embedded OpenType Font Engine kan tillade fjernudførelse af kode (961371)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0231">CVE-2009-0231</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td style="border:1px solid black;">Sårbarheder i Embedded OpenType Font Engine kan tillade fjernudførelse af kode (961371)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0232">CVE-2009-0232</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147424">MS09-030</a></td>
<td style="border:1px solid black;">En sårbarhed i Microsoft Office Publisher kan muliggøre fjernudførelse af kode (969516)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0566">CVE-2009-0566</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=154993">MS09-031</a></td>
<td style="border:1px solid black;">En sårbarhed i Microsoft ISA Server 2006 kan muliggøre udvidelse af rettigheder (970953)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1135">CVE-2009-1135</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157386">MS09-032</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering af kill-bitter for ActiveX (973346)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015">CVE-2008-0015</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=153891">MS09-033</a></td>
<td style="border:1px solid black;">En sårbarhed i Virtual PC og Virtual Server kan muliggøre udvidelse af rettigheder (969856)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1542">CVE-2009-1542</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Funktionel udførelse af kode er mulig med inkonsekvente udnyttelsesmuligheder som resultat.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (972260)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1917">CVE-2009-1917</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Funktionel udførelse af kode er nemt og pålideligt.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (972260)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1918">CVE-2009-1918</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Funktionel udførelse af kode er mulig med inkonsekvente udnyttelsesmuligheder som resultat.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (972260)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1919">CVE-2009-1919</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Funktionel udførelse af kode er mulig med inkonsekvente udnyttelsesmuligheder som resultat.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td style="border:1px solid black;">Sårbarheder i Visual Studio Active Template Library kan tillade fjernudførelse af kode (969706)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901">CVE-2009-0901</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Funktionel udførelse af kode er nemt og pålideligt.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td style="border:1px solid black;">Sårbarheder i Visual Studio Active Template Library kan tillade fjernudførelse af kode (969706)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493">CVE-2009-2493</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Funktionel udførelse af kode er nemt og pålideligt.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td style="border:1px solid black;">Sårbarheder i Visual Studio Active Template Library kan tillade fjernudførelse af kode (969706)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495">CVE-2009-2495</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Bug med offentliggørelse af oplysninger kun uden trussel om udførelse af kode.</td>
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
  </tr>
                <tr><th colspan="5" style="border:1px solid black;">Microsoft Windows 2000</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
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
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1efbbd95-cd72-43df-b1ce-7e2b0c0cb9e2">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e3e54348-6548-4162-b4c0-9910ec6e18b3">DirectX 7.0</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce297c3e-8122-4276-a9c2-d1a404f8028d">DirectX 8.1</a>\*\*\*<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=862db2ad-3c1f-4a26-af70-d8c4f5a69dda">DirectX 9.0</a>\*\*\*\*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89d941f0-3f71-46e3-8096-716561396b72">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Ingen alvorlighedsklassifikation\*\*)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50ffc8f4-7ab7-4e64-9965-5767db5f53cd">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93bd1baa-e2fb-4e8c-9dd7-738efef32282">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="5" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6914167b-6961-480c-a4d4-808cd58a035b">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09d585cb-481d-4767-875e-9c6ebe456b80">DirectX 9.0</a>****<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24701af8-b87e-4e85-9463-f50755a1b6ad">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22bed634-5227-4a22-8df5-801f3e2e232a">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c874c8f8-0449-42b1-8d8b-901040069568">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0acc8aaa-0ae1-412a-9f2b-dc7c707cae00">Windows Internet Explorer 8</a><br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b8b019e-e6d8-4ce2-8f1f-3a6399b252d1">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8cd4803-82da-467c-8cb1-520f5a6021d4">DirectX 9.0</a>****<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2cbf3699-7f79-4006-99e9-0a4c0d394c48">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35ab0c5e-df3d-4873-8139-d1d98b3ac350">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=113cc76a-c434-42ff-b594-4834989ad5ba">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29c8d9e6-2cb8-42b6-b0a6-2510fdb49eab">Windows Internet Explorer 8</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="5" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=018ef53d-f78e-4084-940d-7c86bf59d83c">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=571d57c5-1ef8-4dc4-a1e5-2211a805f0cc">DirectX 9.0</a>****<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0a458d6-c34c-41c7-964a-c130cfcb0d01">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44852619-58ad-48f2-bc55-e8e1c72b1ba9">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4112c25-9e6f-473a-bdbc-3df6dd66e6af">Windows Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4ae65a7-142f-4953-a542-315dac2ac606">Windows Internet Explorer 8</a><br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f5fc902-f5d8-4a87-a73f-68632f9a0935">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1779cbc0-0c29-4fac-a3a6-8b335ffcb98e">DirectX 9.0</a>****<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b7a7bb0-80ef-4f25-bc70-3d0ac06007c5">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd7f36c6-c5c5-4f19-ab59-39f1aaba7fe2">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a594ee0d-ec8f-47df-9125-89d0bbf2115d">Windows Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3bc0e17b-898b-4f29-aa29-607527e1c1cd">Windows Internet Explorer 8</a><br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7df0fce2-543c-4e82-85e6-012bfc8bf130">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48282a89-f849-405a-a31e-2676f45b5042">DirectX 9.0</a>****<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7be36edf-02af-402f-983a-f9ca8128b6b5">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdb70acf-77c3-40a4-b6a3-0fbc0fc0d7fc">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071">Windows Internet Explorer 7</a><br />(Moderat)</td></tr>
              
                <tr><th colspan="5" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c67d85c4-25c5-4821-8db9-91764888f893">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c90240e-c201-4dad-9835-ea71e3527b45">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Ingen alvorlighedsklassifikation**)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3be9a13-1a5b-4b74-9649-449df923f573">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b05a19f7-7412-4c2b-ad11-34396e54ca43">Windows Internet Explorer 8</a><br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f8ae651-59f7-48e1-9e8c-8e07c6806964">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2084e8d-212b-4c39-9163-a71ec6d1b1c7">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Ingen alvorlighedsklassifikation**)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b23cd74-6cf1-413b-82a7-b602347e3ce6">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=900e9a05-2f71-42de-b603-47e4ac061bcb">Windows Internet Explorer 8</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="5" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91f6ee68-0e39-4ec3-b4cd-45f05404e2fb">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0194f994-5821-4fb9-b9e1-ed6af248c995">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Ingen alvorlighedsklassifikation**)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92e3af41-71b0-4a28-afc7-123733180ead">Windows Internet Explorer 7</a>*<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30f99bda-9107-4969-90af-2a30e12acdae">Windows Internet Explorer 8</a>*<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5cdc3014-97b3-47b5-a6b7-cd0e12ec60e4">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4127b125-fdaa-489a-a80c-14b5647ac7e0">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Ingen alvorlighedsklassifikation**)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1958ec40-3b7b-43a9-9fdc-742735dcf516">Windows Internet Explorer 7</a>*<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=acd3667b-6676-4010-b23b-e8372dd55f93">Windows Internet Explorer 8</a>*<br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03330a14-9cfa-4146-a3d3-4b7a76975d2d">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4082c776-318c-4e0c-83fc-2f3f472c039a">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Ingen alvorlighedsklassifikation**)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=470387ac-6d75-4b7e-8ca5-376b67a8bd4d">Windows Internet Explorer 7</a>
                    <br />(Moderat)</td></tr>
              </table>


**Bemærkning til Windows Server 2008**

**\*\*Windows Server 2008-serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008, hvis Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkning til MS09-032**

\*\*Klassifikationer gælder ikke for denne opdatering, idet sårbarheden beskrevet i denne bulletin ikke påvirker denne software. Som en gennemgribende forholdsregel til beskyttelse mod eventuelle nye vektorer, der identificeres i fremtiden, anbefaler Microsoft imidlertid, at kunder, der har denne software, anvender denne sikkerhedsopdatering.

**Bemærkninger til MS09-028**

\*\*\*opdateringen til DirectX 8.1 er også gældende for DirectX 8.1b.

\*\*\*\*Opdateringen til DirectX 9.0 er også gældende for DirectX 9.0a, DirectX 9.0b og DirectX 9.0c.

#### Micorsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Office Suites, systemer og komponenter</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147424">
                      <strong>MS09-030</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">2007 Microsoft Office System Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4b0665d-5744-49c7-a3c0-f231fd08d3b8">Microsoft Office Publisher 2007 Service Pack 1</a>
                    <br />(KB969693)<br />(Alvorlig)</td></tr>
              </table>


#### Udviklingsværktøjer og software fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Visual Studio</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158131">
                      <strong>MS09-035</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Visual Studio .NET 2003</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63ce454e-f69c-44e3-89fb-eb23c2e2154e">Microsoft Visual Studio .NET 2003 Service Pack 1</a>
                    <br />(KB971089)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visual Studio 2005</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c8729dc-06a2-4538-a90d-ff9464dc0197">Microsoft Visual Studio 2005 Service Pack 1</a>
                    <br />(KB971090)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d7ee45b-9892-41b5-ac08-5fde9cde1b42">Microsoft Visual Studio 2005 Service Pack 1</a>*<br />(KB973673)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43f96f2a-69c6-4c5e-b72c-0edfa35f4fc2">Microsoft Visual Studio 2005 Service Pack 1 64-bit Hosted Visual C++ Tools</a><br />(KB973830)<br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Windows Embedded CE 6.0</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8">Windows Embedded CE 6.0</a>**<br />(KB974616)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visual Studio 2008</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f9da646-94dd-469d-baea-a4306270462c">Microsoft Visual Studio 2008</a>
                    <br />(KB971091)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e3bb6602-b7f4-4614-9999-77f5c6f66ccd">Microsoft Visual Studio 2008</a>*<br />(KB973674)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=294de390-3c94-49fb-a014-9a38580e64cb">Microsoft Visual Studio 2008 Service Pack 1</a><br />(KB971092)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75fbf397-5140-4961-92a9-78a88ba7228f">Microsoft Visual Studio 2008 Service Pack 1</a>*<br />(KB973675)<br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Visual C++ 2005</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=766a6af7-ec73-40ff-b072-9112bab119c2">Microsoft Visual C++ 2005 Service Pack 1 Redistributable Package</a>
                    <br />(KB973544)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visual C++ 2008</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b29655e-9da4-4b6b-9ac5-687ca0770f93">Microsoft Visual C++ 2008 Redistributable Package</a>
                    <br />(KB973551)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2051a0c1-c9b5-4b0a-a8f5-770a549fd78c">Microsoft Visual C++ 2008 Service Pack 1 Redistributable Package</a><br />(KB973552)<br />(Moderat)</td></tr>
              </table>


**Bemærkninger til MS09-035**

\*Til mobile programmer, der anvender ATL til Smart Devices

\*\*Installerer den månedlige opdatering til Windows Embedded CE 6.0 (januar 2010). Denne opdateringspakke er udelukkende tilgængelig fra Microsoft Download Center.

#### Microsoft Server og Security Software

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Internet Security and Acceleration Server </th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=154993">
                      <strong>MS09-031</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Internet Security and Acceleration Server 2006</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4e9b1dd-526d-407b-bc23-ebc2738b1b19">Microsoft Internet Security and Acceleration Server 2006</a>
                    <br />(KB970811)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8ccd770-a925-411c-b994-78e4cf5c3476">Supportopdatering til Microsoft Internet Security and Acceleration Server 2006</a><br />(KB970811)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e536cfed-c1af-4868-b2ac-79178d6355a5">Microsoft Internet Security and Acceleration Server 2006 Service Pack 1</a><br />(KB971143)<br />(Alvorlig)</td></tr>
              </table>


#### Microsoft virtualiseringssoftware

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Virtual PC</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=153891">
                      <strong>MS09-033</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Virtual PC 2004</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=56a160e1-59b5-45bc-aecf-dfe614a7efad">Microsoft Virtual PC 2004 Service Pack 1</a>
                    <br />(KB969856)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Virtual PC 2007</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a">Microsoft Virtual PC 2007</a>
                    <br />(KB969856)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0">Microsoft Virtual PC 2007 Service Pack 1</a><br />(KB969856)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Virtual PC 2007 x64 Edition</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a">Microsoft Virtual PC 2007 x64 Edition</a>
                    <br />(KB969856)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0">Microsoft Virtual PC 2007 x64 Edition Service Pack 1</a><br />(KB969856)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Virtual Server</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=153891">
                      <strong>MS09-033</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Virtual Server 2005 R2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57">Microsoft Virtual Server 2005 R2 Service Pack 1</a>
                    <br />(KB969856)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Virtual Server 2005 R2 x64 Edition</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57">Microsoft Virtual Server 2005 R2 x64 Edition Service Pack 1</a>
                    <br />(KB969856)<br />(Alvorlig)</td></tr>
              </table>


## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Bemærk** Fra 1. august 2009 stopper Microsoft supporten til Office Update og Office Update Inventory Tool. Hvis du stadig vil have de seneste opdateringer til Microsoft Office-produkter, skal du anvende [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Hvis du vil have flere oplysninger, skal du se [Om Microsoft Office Update: Ofte stillede spørgsmål](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

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

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Nye, reviderede og offentliggjorte opdateringer til Microsoft-produkter ud over Microsoft Windows](http://technet.microsoft.com/en-us/wsus/dd573344.aspx).

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

  - Thomas Garnier fra [SkyRecon](http://www.skyrecon.com/) og Zheng Wenbin, Liu Qi og Song Shenlei fra [Qihoo 360 Security Center](http://www.360.cn/) for at rapportere et problem, der er beskrevet i MS09-028
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at have rapporteret et problem, der er beskrevet i MS09-028
  - Aaron Portnoy fra [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) og en anonym forsker, der arbejder for TippingPoints [Zero Day Initiative](http://www.zerodayinitiative.com/), Thomas Garnier fra [SkyRecon](http://www.skyrecon.com/) og Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at rapportere et problem, der er beskrevet i MS09-028
  - [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret et problem, der er beskrevet i MS09-029
  - Thomas Garnier for at rapportere et problem, der er beskrevet i MS09-029
  - Lionel d'Hauenens fra [Labo Skopia](http://www.laboskopia.com/), der samarbejder med [VeriSign iDefense Labs](http://www.idefense.com), for at rapportere et problem beskrevet i MS09-030
  - Ryan Smith og Alex Wheeler fra [IBM IIS X-Force](http://www.iss.net/) for først at have rapporteret et problem, der er beskrevet i MS09-032
  - Julien Tinnes og Tavis Ormandy fra [Google Inc.](http://www.google.com/) for at rapportere et problem, der er beskrevet i MS09-033
  - Peter Vreugdenhil fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret et problem, der er beskrevet i MS09-034
  - Wushi og Ling fra [team509](http://www.team509.com/), der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at rapportere et problem beskrevet i MS09-034
  - Peter Vreugdenhi, der arbejder for [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS09-034
  - David Dewey fra [IBM ISS X-Force](http://www.iss.net/), for at have rapporteret et problem, der er beskrevet i MS09-035
  - Sean Larsson fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret to problemer, der er beskrevet i MS09-035

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (14. juli 2009): Oversigt over bulletin offentliggjort.
  - V1.1 (15. juli 2009): Opdaterede resuméet for MS09-032, korrigerede kravet om genstart for MS09-029 og udførte diverse redigeringer.
  - V2.0 (28. juli 2009): Tilføjet sikkerhedsbulletin fraMS09-034, Samlet sikkerhedsopdatering til Internet Explorer (972260) og MS09-035, Sårbarheder i Visual Studio Active Template Library kan tillade fjernudførelse af kode (969706). Tilføjede også bulletin-webcast-links til disse out-of-band-sikkerhedsbulletiner.
  - V3.0 (4. august 2009): Revideret for at annoncere genudsendelsen af opdateringen til Microsoft Internet Explorer 6 Service Pack 1 på Microsoft Windows 2000 Service Pack 4. Alle kunder, der allerede har installeret den originale opdatering til Internet Explorer 6 Service Pack 1 på Microsoft Windows 2000 Service Pack 4, er allerede beskyttede. Kunder der har den koreansksprogede version af Internet Explorer 6 Service Pack 1 bør dog geninstallere opdateringen til Internet Explorer 6 Service Pack 1 på deres Windows 2000-systemer for at opnå samme beskyttelse og løse et udskrivningsproblem. Se sikkerhedsbulletin fra Microsoft MS09-034.
  - V4.0 (11. august 2009): Revideret til annoncering af MS09-035. MS09-035 blev udgivet for at tilbyde nye opdateringer til Microsoft Visual Studio 2005 Service Pack 1 (KB973673), Microsoft Visual Studio 2008 (KB973674) og Microsoft Visual Studio 2008 Service Pack 1 (KB973675) for udviklere, der anvender Visual Studio til skabe komponenter og kontroller til mobile programmer, som anvender ATL til Smart Devices.
  - V4.1 (13. august 2009): Rettede genstartskrav for MS09-035.
  - V5.0 (19. august 2009): Tilføjet en fodnote til bulletin MS09-028 for at oplyse, hvilke programmer der påvirkes for DirectX 8.1.
  - V6.0 (25. august 2009): Revideret for at annoncere genudsendelsen af den japansksprogede opdatering til Windows XP Service Pack 2, Windows XP Service Pack 3 og Windows XP Professional x64 Edition Service Pack 2. Alle kunder, der allerede har installeret den oprindelige opdatering, er allerede beskyttet. Kunder der har den japansksprogede version af Windows XP Service Pack 2, Windows XP Service Pack 3 eller Windows XP Professional x64 Edition Service Pack 2, bør dog geninstallere opdateringen for at opnå samme beskyttelse og løse et udskrivningsproblem. Se sikkerhedsbulletin fra Microsoft MS09-029.
  - 7.0 (12. januar 2010): Revideret for at føje Windows Embedded CE 6.0 til berørt software for MS09-035. Opdateringen til Windows Embedded CE 6.0 (KB974616) er en samlet opdatering, som udelukkende er tilgængelig fra Microsoft Download Center. Kunder, der benytter platformen Windows Embedded CE 6.0, bør overveje at anvende den samlede opdatering.

*Built at 2014-04-18T01:50:00Z-07:00*

