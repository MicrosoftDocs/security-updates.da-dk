---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for december 2008
TOCTitle: MS08-DEC
ms:assetid: ms08-dec
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms08-dec(v=Security.10)
ms:contentKeyID: 61224038
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for december 2008

Offentliggjort: 9. december 2008 | Opdateret: 28. januar 2009

**Version:** 5.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for december 2008.

Med udgivelsen af bulletiner for december 2008 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 4. december 2008. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 10. december 2008 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få december måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374647). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Angående den out-of-band-sikkerhedsbulletin, der er blevet tilføjet version 3.0 af denne bulletinoversigt, MS08-078, afholder Microsoft to webcasts for at behandle kundernes spørgsmål til disse bulletiner: den 17. december 2008, kl. 13.00 Pacific Time (USA og Canada) og den 18. december 2008 kl. 11:00 Pacific Time. Tilmeld dig nu for at få [webcasten den 17. december](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399448&culture=en-us) og [webcasten den 18. december](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399449&culture=en-us). Herefter kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td><strong>Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (956802)</strong><br />
<br />
Denne vigtige sikkerhedsopdatering løser to privat rapporterede sårbarheder i GDI. Udnyttelse af en af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet WMF-billedfil. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td><strong>Sårbarheder i Windows Search kan give mulighed for fjernudførelse af kode (959349)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Windows Search. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner og gemmer en særligt udformet gemt søgefil i Windows Stifinder, eller hvis en bruger klikker på en særligt udformet søge-URL. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td><strong>Samlet sikkerhedsopdatering til Internet Explorer (958215)</strong><br />
<br />
Denne sikkerhedsopdatering løser fire privat rapporterede sårbarheder. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=137335">MS08-078</a></td>
<td><strong>Sikkerhedsopdatering til Internet Explorer (960714)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td><strong>Sårbarheder i Visual Basic 6.0 Runtime Extended Files (ActiveX Controls) kan muliggøre fjernudførelse af kode (932349)</strong><br />
<br />
Denne sikkerhedsopdatering løser fem privat rapporterede sårbarheder og en offentliggjort sårbarhed i ActiveX-objekter til Microsoft Visual Basic 6.0 Runtime Extended Files. Disse sårbarheder kan muliggøre fjernudførelse af kode, hvis en bruger har fået vist et websted med særligt udformet indhold. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft-udviklingsværktøjer og software, Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td><strong>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (957173)</strong><br />
<br />
Denne sikkerhedsopdatering løser otte privat rapporterede sårbarheder i Microsoft Office Word og Microsoft Office Outlook, som kan muliggøre fjernudførelse af kode, hvis en bruger åbner en særligt udformet Word- eller RTF-fil (Rich Text Format). En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td><strong>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (959070)</strong><br />
<br />
Denne kritiske sikkerhedsopdatering løser tre privat rapporterede sårbarheder i Microsoft Office Excel, som kan muliggøre fjernudførelse af kode, når en bruger åbner en særligt udformet Excel-fil. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126307">MS08-077</a></td>
<td><strong>Sårbarhed i Microsoft Office SharePoint Server kan give mulighed for udvidelse af rettigheder (957175)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed. Sårbarheden kan give mulighed for udvidelse af rettigheder, hvis en hacker omgår godkendelse ved at gå til en administrativ URL-adresse på et SharePoint-websted. Et succesfuldt angreb, der fører til udvidelse af rettigheder, kan resultere i Denial-Of-Service eller offentliggørelse af oplysninger.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office, Microsoft Server Software</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td><strong>Sårbarheder i Windows Media Components kan give mulighed for fjernudførelse af kode (959807)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i følgende Windows Media Components. Windows Media Player, Windows Media Format Runtime og Windows Media Services. Den mest alvorlige sårbarhed kan muliggøre fjernudførelse af kode. Hvis en bruger er logget på med administrative brugerrettigheder, kan en hacker, som har held med at udnytte denne sårbarhed, få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Sårbarheder i Visual Basic 6.0 Runtime Extended Files (ActiveX Controls) kan muliggøre fjernudførelse af kode (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3704">CVE-2008-3704</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Konsekvent exploit-kode er offentligt tilgængelig</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Sårbarheder i Visual Basic 6.0 Runtime Extended Files (ActiveX Controls) kan muliggøre fjernudførelse af kode (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4252">CVE-2008-4252</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Sårbarheder i Visual Basic 6.0 Runtime Extended Files (ActiveX Controls) kan muliggøre fjernudførelse af kode (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4256">CVE-2008-4256</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Sårbarheder i Visual Basic 6.0 Runtime Extended Files (ActiveX Controls) kan muliggøre fjernudførelse af kode (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4253">CVE-2008-4253</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Sårbarheder i Visual Basic 6.0 Runtime Extended Files (ActiveX Controls) kan muliggøre fjernudførelse af kode (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4254">CVE-2008-4254</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td>Sårbarheder i Visual Basic 6.0 Runtime Extended Files (ActiveX Controls) kan muliggøre fjernudførelse af kode (932349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4255">CVE-2008-4255</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Windows 2000-systemer er mest udsatte. Windows XP SP2, Windows Server 2003 SP1 og nyere operativsystemer påvirkes formentlig ikke af den funktionelle exploit-kode pga. stærkere massebeskyttelse.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td>Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (956802)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3465">CVE-2008-3465</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td>Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (956802)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2249">CVE-2008-2249</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4024">CVE-2008-4024</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4025">CVE-2008-4025</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4026">CVE-2008-4026</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4027">CVE-2008-4027</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4028">CVE-2008-4028</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4030">CVE-2008-4030</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4837">CVE-2008-4837</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (957173)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4031">CVE-2008-4031</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (958215)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4258">CVE-2008-4258</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (958215)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4259">CVE-2008-4259</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (958215)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4261">CVE-2008-4261</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (958215)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4260">CVE-2008-4260</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (959070)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4265">CVE-2008-4265</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (959070)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4266">CVE-2008-4266</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (959070)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4264">CVE-2008-4264</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td>Sårbarheder i Windows Search kan give mulighed for fjernudførelse af kode (959349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4269">CVE-2008-4269</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td>Sårbarheder i Windows Search kan give mulighed for fjernudførelse af kode (959349)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4268">CVE-2008-4268</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td>Sårbarheder i Windows Media Components kan muliggøre fjernudførelse af kode (959807)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3009">CVE-2008-3009</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Der kan oprettes sammenhængende exploit-kode for dette problem. Angrebsscenariers begrænsede adfærd gør dog faktiske angreb usandsynlige.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td>Sårbarheder i Windows Media Components kan muliggøre fjernudførelse af kode (959807)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3010">CVE-2008-3010</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Der kan oprettes sammenhængende exploit-kode for dette problem. Angrebsscenariers begrænsede adfærd gør dog faktiske angreb usandsynlige.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=126307">MS08-077</a></td>
<td>Sårbarhed i Microsoft Office SharePoint Server kan give mulighed for udvidelse af rettigheder (957175)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4032">CVE-2008-4032</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Der kan oprettes sammenhængende exploit-kode for dette problem. Angreb, der udnytter denne svaghed, vil dog normalt kun resultere i afsløring af oplysninger, ikke fjernudførelse.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=137335">MS08-078</a></td>
<td>Sikkerhedsopdatering til Internet Explorer (960714)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4844">CVE-2008-4844</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig<br />
(Offentliggjort ved bulletinudgivelse)</td>
<td>Der er registreret konsekvent exploit-kode i aktive angreb. Men Internet Explorer kører i beskyttende tilstand med standardinstallationer af Windows Vista og Windows Server 2008, hvilket vanskeliggør udnyttelse.</td>
</tr>
</tbody>
</table>


## Berørte programmer og downloadplaceringer

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at få kendskab til de sikkerhedsopdateringer, du muligvis skal installere. Du skal se alle de anførte softwareprogrammer eller komponenter igennem for at se, om der er behov for en sikkerhedsopdatering. Hvis et program eller en komponent findes på listen, findes der hyperlinks til tilgængelige softwareopdateringer, og sårbarhedens omfang også angivet.

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
  </tr>
                <tr><th colspan="6">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
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
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b775fb1-1077-455d-af4a-4ccb5237974f">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)<br /></td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c242ba42-556b-4c87-bf33-9d99166ff096">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c0583745-7e57-4265-9429-c3415cb8465f">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3e18732-47f1-40ce-999c-d1fd283bf138">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=124c14b6-9323-4f6f-902b-727aa56444bc">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c33d558e-45f9-4e85-b48c-03bd0e8cb4bc">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a459497-0ab8-41cb-87d0-b551631d8d8a">Windows Media Format Runtime 7.1 og Windows Media Format Runtime 9.0</a><br />(KB952069)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58b7d241-cef6-48fa-aa52-017695f71db1">Windows Media Services 4.1</a><br />(KB952068)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="6">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2151fbba-c464-4d1e-82d4-5b096e82bed0">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)<br /></td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=af9a6cb0-725d-490c-9858-16ec40e98560">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b582695-b3cc-4c65-bc4b-d673c9a6d82a">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d83e0af-46fa-4bfc-ba57-635435a7ef2d">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0190a289-164e-41a7-8c01-fa1aaed3f531">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99241309-e644-4088-a8f3-38837fab4037">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=504f816c-f554-4b93-ac28-b085574d9bac">Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 og Windows Media Format Runtime 11</a><br />(Kun Windows XP Service Pack 2)<br />(KB952069)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad76fcf3-a2f9-4e36-bd1b-c1536749173c">Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 og Windows Media Format Runtime 11</a><br />(Kun Windows XP Service Pack 3)<br />(KB952069)<br />(Alvorlig)<br /></td></tr>
                <tr><td>Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2247f6a5-aa33-4c68-9ea8-a63488d126d3">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)<br /></td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60bf9851-24fe-4658-8333-d353e82063c7">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=107cf54b-29d4-4c54-b091-2b5b3ffbf49d">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a585cb73-2c1a-4fa8-862a-ad6aeaeaf2f8">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ba71e23-8cef-4399-b215-983b0dcf5cb5">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=946d47c9-b208-4fab-8ef6-774413d61bc8">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=644ef023-ee40-45b0-9c9d-c76d9fab0005">Windows Media Format Runtime 9.5</a><br />(KB952069)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524">Windows Media Format Runtime 9.5 x64 Edition</a><br />(KB952069)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2dadc017-2be5-4240-ab8f-0291756dca6b">Windows Media Format Runtime 11</a><br />(KB952069)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="6">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c396796-0929-4cd2-99e8-3c0f7075a89e">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)<br /></td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d53adf6f-9501-4862-a1ca-57eb4d40cd75">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9cdd4f9e-c578-405c-af9e-628f2d77fdf4">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d81e9cf9-ce0c-463a-a359-49a348cb89ae">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=388847ec-817e-45cf-8fa7-32c7e1f57f80">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2315ce20-2f46-42c2-bb40-045f003409d7">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8958248-c889-499e-a6a9-3b394cdb27ea">Windows Media Format Runtime 9.5</a><br />(KB952069)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e71abc2d-d60e-444a-9b7b-062c5805fe9e">Windows Media Services 9-serien</a><br />(KB952068)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6d5c7d2f-1a82-4cdf-b3f2-b2c2390c6a64">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)<br /></td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e37cb34-32be-4bbe-87f3-c4e1974e4d00">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c36f92c-d8a0-4b70-b85f-83588a0299a0">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=015df302-d79f-43a1-b5c5-32ac04de0510">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ae17caf-6204-470e-8480-380d3d505657">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c29bed9-1b88-4d2f-80a5-305c2bedd89f">Windows Media Player 6.4</a>
                    <br />(KB954600)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2278022e-a716-46c0-bedf-d626933bd815">Windows Media Format Runtime 9.5</a><br />(KB952069)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524">Windows Media Format Runtime 9.5 x64 Edition</a><br />(KB952069)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0030155-1a9a-46cc-bbc8-6d0d1ed65c1f">Windows Media Services 9-serien</a><br />(KB952068)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1edb62b4-3d0f-4891-b4b3-8f8bc4e7bdfe">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)<br /></td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0da4e424-4682-4401-a226-7d8f1be19d44">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3811030d-5958-4b91-b5b8-20587dc7c4d6">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18016305-7f72-47f6-ab4c-94282289bf5f">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=97d6c093-f68d-4ddf-8e3c-f29662a1940f">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Vista og Windows Vista Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cddf9cf6-bdeb-4429-823a-879387a428d7">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Kritisk)<br /></td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0dcc5373-0435-42d5-864d-298e5bb122d9">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(KB958623)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b1b65f0-6848-47c6-bdd5-be3c0621b323">Windows Vista og Windows Vista Service Pack 1</a><br />(KB958624)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f62030a-9ce2-4c92-b948-143a6881921e">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7887111d-4fac-4823-bdd2-a18d9468fdf0">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1fcdc8dd-26d9-4d1a-8b3f-7b6a21a95999">Windows Media Format Runtime 11</a>
                    <br />(KB952069)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73dc3775-b6f0-40f1-bd36-6b5fb80eb2fa">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Kritisk)<br /></td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2112c5c8-7c9f-4491-b127-b1093085e105">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(KB958623)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eb1d0ffe-1644-457b-9e82-768bd4c7f7ab">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />(KB958624)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8800493-fba4-41f8-bde5-a53eeaf89d54">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=69979d92-8d45-47fe-ac4c-c2f1f23cf1fb">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8839f6cd-dfbf-448c-bf1e-1da9bb5f3f25">Windows Media Format Runtime 11</a>
                    <br />(KB952069)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="6">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125440">
                      <strong>MS08-071</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132148">
                      <strong>MS08-075</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133437">
                      <strong>MS08-073</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=137335">
                      <strong>MS08-078</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125419">
                      <strong>MS08-076</strong>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 til 32 bit-systemer                    </td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbed9e8b-e75e-44ef-ba1d-fd6f852c1f67">Windows Server 2008 til 32 bit-systemer</a>*<br />(Kritisk)<br /></td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90ab7e6f-5ae7-4f55-8838-868fc98d8a16">Windows Server 2008 til 32 bit-systemer</a>***<br />(KB958623)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=470d506f-77ae-4a44-8598-df645f484295">Windows Server 2008 til 32 bit-systemer</a>***<br />(KB958624)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45a0de3c-c7d1-4314-a456-1f7428b7c90a">Windows Internet Explorer 7</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5552e564-dd1c-4e2a-9a42-6317522c884d">Windows Internet Explorer 7</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91ec4195-bc1c-444e-a7b0-ebde46c088fa">Windows Media Format Runtime 11</a>
                    <br />(KB952069)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffb5d945-7f98-4849-b020-ed4873fa42df">Windows Media Services 2008</a>*<br />(KB952068)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til x64-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48aecf4c-1296-490d-ba37-a28e3ec19bd6">Windows Server 2008 til x64-baserede systemer</a>*<br />(Kritisk)<br /></td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1deab57-ada2-4b12-9157-5615e7b0071d">Windows Server 2008 til x64-baserede systemer</a>***<br />(KB958623)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e41f23e4-6a2f-4ebb-b425-d241a08da316">Windows Server 2008 til x64-baserede systemer</a>***<br />(KB958624)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=405b28db-47d7-4d6b-90e6-834c0a409323">Windows Internet Explorer 7</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=889c6eb1-7d1f-4e60-b637-535cb6e4e443">Windows Internet Explorer 7</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8cab6fe8-161d-4d8c-9772-eb3174a2c3c3">Windows Media Format Runtime 11</a>
                    <br />(KB952069)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72">Windows Media Services 2008</a>*<br />(KB952068)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9bfe15cd-02ff-45cf-85c8-5ff1e6c1a871">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Kritisk)<br /></td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48bed90d-c243-4969-8e54-326d9a7af343">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(KB958623)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83de2263-de2a-4c13-96ba-ecfebdaf0bb9">Windows Server 2008 til Itanium-baserede systemer</a><br />(KB958624)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f0d4f321-941e-4da7-958f-582c75542ee8">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06cb502a-6818-4599-aa24-6eddb83e4b84">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td></tr>
              </table>


**Bemærkning til MS08-078**

Den sårbarhed, som MS08-078 drejer sig om, blev rapporteret efter udgivelsen af Windows Internet Explorer 8 Beta 2. Kunder, der kører Internet Explorer 8 Beta 2, opfordres til at downloade og installere opdateringen på deres systemer.

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Der kan også hentes sikkerhedsopdateringer fra [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

**Bemærkninger til Windows Server 2008**

**\*Windows Server 2008 - serverens hovedinstallation er berørt.** For understøttede udgaver af Windows Server 2008 gælder denne opdatering med den samme klassifikation, uanset om Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core eller ej. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 - serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008, hvis Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Windows Server 2008-serverens hovedinstallation er ikke berørt.** De sårbarheder, der behandles i disse opdateringer, påvirker ikke understøttede versioner af Windows Server 2008, hvis Windows Server 2008 blev installeret vha. Server Core-installationsmuligheden – heller ikke selv om filer, der er berørt af disse sårbarheder, findes på systemet. Brugere med berørte filer vil dog stadig blive tilbudt denne opdatering, da opdateringsfilerne er nyere (med højere versionsnumre), end de filer, der aktuelt er på systemet. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Micorsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="5">Microsoft Office Suites, systemer og komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130478">
                      <strong>MS08-070</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=126306">
                      <strong>MS08-072</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=131481">
                      <strong>MS08-074</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=126307">
                      <strong>MS08-077</strong>
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
                  </td><td>Ingen</td></tr>
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43e8c4d8-307b-48f6-ac99-a9617421d40a">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB956328)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f39d2a49-f861-4f2d-bf91-94a8a85af40c">Microsoft Office Excel 2000 Service Pack 3</a>
                    <br />(KB958435)<br />(Kritisk)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ef41412-50b3-4077-b0e3-9a3704d2f876">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB956329)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72076e21-2aa3-48e8-883a-c3cb756fc72a">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB958372)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45c81c60-4b1b-4246-839b-198ebc4eeae2">Microsoft Office Word 2003 Service Pack 3</a>
                    <br />(KB956357)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c0771e5-fcd4-4365-b903-1a3bd95d9e66">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB958436)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37">Microsoft Office Word 2007</a>
                    <br />(KB956358)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37">Microsoft Office Outlook 2007</a><br />(KB956358)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf">Microsoft Office Excel 2007</a>
                    <br />(KB958437)**** <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>2007 Microsoft Office System Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37">Microsoft Office Word 2007 Service Pack 1</a>
                    <br />(KB956358)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37">Microsoft Office Outlook 2007 Service Pack 1</a><br />(KB956358)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf">Microsoft Office Excel 2007 Service Pack 1</a>
                    <br />(KB958437)****<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office FrontPage</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a6130ae-c5b4-43cb-afe3-ab6a55b9d9ea">Microsoft Office FrontPage 2002 Service Pack 3</a>*<br />(KB957797)<br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Project</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89a44042-a629-40f3-800a-0bb45fc36591">Microsoft Office Project 2003 Service Pack 3</a>
                    <br />(KB949045)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6">Microsoft Office Project 2007</a><br />(KB949046)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6">Microsoft Office Project 2007 Service Pack 1</a><br />(KB949046)<br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="5">Microsoft Office til Mac</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130478">
                      <strong>MS08-070</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=126306">
                      <strong>MS08-072</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=131481">
                      <strong>MS08-074</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=126307">
                      <strong>MS08-077</strong>
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
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2004 til Mac</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820">Microsoft Office 2004 for Mac</a>**<br />(KB960402)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820">Microsoft Office 2004 for Mac</a>**<br />(KB960402)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office 2008 til Mac</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62">Microsoft Office 2008 til Mac</a>**<br />(KB960401)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62">Microsoft Office 2008 til Mac</a>**<br />(KB960401)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Open XML File Format Converter til Mac</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7">Open XML File Format Converter til Mac</a>**<br />(KB960403)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7">Open XML File Format Converter til Mac</a>**<br />(KB960403)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="5">Anden Office Software</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130478">
                      <strong>MS08-070</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=126306">
                      <strong>MS08-072</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=131481">
                      <strong>MS08-074</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=126307">
                      <strong>MS08-077</strong>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Works</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1537d181-90d9-4bb5-b5ae-8d9990a349af">Microsoft Works 8</a>***<br />(KB959487)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e">Microsoft Office Excel Viewer 2003</a>
                    <br />(KB958434)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e">Microsoft Office Excel Viewer 2003 Service Pack 3</a><br />(KB958434)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9dbb35c1-aa7a-481b-a330-8ba916ddd443">Microsoft Office Excel Viewer</a><br />(KB958442)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Word Viewer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70de7c3c-519f-4f4a-a03f-027f80b5415c">Microsoft Office Word Viewer 2003 Service Pack 3 og Microsoft Office Word Viewer</a>
                    <br />(KB956366)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970">Microsoft Office Compatibility Pack for Word, Excel og PowerPoint 2007 File Formats</a>
                    <br />(KB956828)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1</a><br />(KB956828)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f">Microsoft Office Compatibility Pack for Word, Excel og PowerPoint 2007 File Formats</a>
                    <br />(KB958439)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1</a><br />(KB958439)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office SharePoint Server 2007</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e">Microsoft Office SharePoint Server 2007 (32-bit versioner)</a>
                    <br />(KB956716)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e">Microsoft Office SharePoint Server 2007 Service Pack 1 (32-bit versioner)</a><br />(KB956716)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86">Microsoft Office SharePoint Server 2007 (64-bit versioner)</a><br />(KB956716)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86">Microsoft Office SharePoint Server 2007 Service Pack 1 (64-bit versioner)</a><br />(KB956716)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til MS08-070**  
Se også næste afsnit, **Microsoft-udviklingsværktøjer og software**, for at få flere opdateringsfiler. Denne bulletin omhandler både Microsoft Office og Microsoft-udviklingsværktøjer og software.

**Bemærkning til MS08-077**  
Se også næste afsnit, **Microsoft Server-software**, for at få flere opdateringsfiler. Denne bulletin omhandler både Microsoft Office Suites og software samt Microsoft Server-software.

**Bemærkning til Microsoft Office FrontPage i MS08-070**  
\*Denne opdatering gælder kun for FrontPage 2002 Service Pack 3-versioner på forenklet kinesisk (Kina), pan-kinesisk (Hongkong), traditionel kinesisk (Taiwan) og koreansk.

**Bemærkning til Microsoft Office til Mac i MS08-072 og MS08-074**  
\*\*De tilsvarende opdateringer er identiske mellem MS08-072 og MS08-074. Da sårbarhederne er i samme filer, er disse opdateringer ens for begge bulletiner.

**Bemærkning Works 8 i MS08-072**  
\*\*\*Før denne sikkerhedsopdatering kan tilbydes, skal brugere, der kører Microsoft Works 8.0, først opdatere til Works 8.5 som beskrevet i [Opdatering af Microsoft Works](http://www.microsoft.com/products/works/international/update_1001.mspx). Det omfatter alle brugere, der anvender Microsoft Works 8.0, Works Suite 2004 og Works Suite 2005. For kunder, der benytter Works Suite 2006, er Works 8.5 allerede inkluderet.

**Bemærkning til Microsoft Office Excel 2007 og Microsoft Office Excel 2007 Service Pack 1 i MS08-074**  
\*\*\*\*I forbindelse med Microsoft Office Excel 2007 og Microsoft Office Excel 2007 Service Pack 1 er det ud over sikkerhedsopdatering KB958437 nødvendigt for kunderne at installere sikkerhedsopdateringen til [Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f) (KB958439), så de er beskyttet mod de sårbarheder, der er beskrevet i MS08-074. Kunder, der på forhånd har installeret opdateringerne KB958437 og KB958439, behøver ikke at geninstallere.

#### Udviklingsværktøjer og software fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Visual Studio</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130478">
                      <strong>MS08-070</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visual Basic</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e27eebcb-095d-43ec-a19e-4a46e591715c">Microsoft Visual Basic 6.0 Runtime Extended Files</a>
                    <br />(KB926857)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio .NET</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afad980d-7f27-49d9-aa23-b762c7b94cd6">Microsoft Visual Studio .NET 2002 Service Pack 1</a>
                    <br />(KB958392)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ac7cf8f-d046-43a8-b4ef-253153d65aed">Microsoft Visual Studio .NET 2003 Service Pack 1</a><br />(KB958393)<br />(Kritisk)</td></tr>
                <tr><td>Microsoft Visual FoxPro</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a6977f81-f7f6-486b-96ad-8d296d79f205">Microsoft Visual FoxPro 8.0 Service Pack 1</a>
                    <br />(KB958369)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=386d27a6-b2c7-4acc-bf3e-edcbc7358172">Microsoft Visual FoxPro 9.0 Service Pack 1</a><br />(KB958370)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b1f28a9-da8d-463a-8ae4-dfc8fcc6c41a">Microsoft Visual FoxPro 9.0 Service Pack 2</a><br />(KB958371)<br />(Kritisk)</td></tr>
              </table>


**Bemærkning til MS08-070**  
Se også forrige afsnit, **Microsoft Office Suites og software**, for at få flere opdateringsfiler. Denne bulletin omhandler både Microsoft Office Suites og software samt Microsoft-udviklingsværktøjer og software.

#### Microsoft Server-software

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Search-server</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=126307">
                      <strong>MS08-077</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Search Server</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e">Microsoft Search Server 2008 (32-bit versioner)</a>*<br />(KB956716)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86">Microsoft Search Server 2008 (64-bit versioner)</a>**<br />(KB956716)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til MS08-077**

\*Omfatter Microsoft Search Server 2008 Express (32-bit)

\*\*Omfatter Microsoft Search Server 2008 Express (64-bit)

Se også afsnittet, **Microsoft Office Suites og software**, for at få flere opdateringsfiler. Denne bulletin omhandler både Microsoft Office Suites og software samt Microsoft Server-software.

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

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services for 2008. Omfatter alt Windows-indhold.
  - [Nye, reviderede og offentliggjorte opdateringer til Microsoft-produkter ud over Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

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

  - ADLab fra [VenusTech](http://www.venustech.com.cn) for at have rapporteret flere problemer, der er beskrevet i MS08-070
  - Jason Medeiros fra [Affiliated Computer Services](http://www.acs-inc.com/) for at have rapporteret et problem, der er beskrevet i MS08-070
  - Carsten Eiram fra [Secunia Research](http://secunia.com/) for at have rapporteret et problem, der er beskrevet i MS08-070.
  - Mark Dowd i samarbejde med [McAfee Avert Labs](http://www.avertlabs.com/) for at have rapporteret et problem, der er beskrevet i MS08-070
  - Brett Moore fra [Insomnia Security](http://www.insomniasec.com/) for at rapportere et problem, der er beskrevet i MS08-070
  - CHkr\_D591, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at have rapporteret et problem, der er beskrevet i MS08-070
  - Michal Bucko, der arbejder sammen med [CERT/CC](http://www.cert.org/), for at have rapporteret et problem, der er beskrevet i MS08-070
  - Symantecs [Security Intelligence Analysis Team](http://www.symantec.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS08-070
  - Jun Mao fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret et problem, der er beskrevet i MS08-071
  - Juan Caballero fra [Bitblaze group ved Carnegie Mellon University/UC Berkeley](http://bitblaze.cs.berkeley.edu/) for at rapportere et problem, der er beskrevet i MS08-071
  - Ricardo Narvaja fra [Core Security Technologies](http://www.coresecurity.com/) for at rapportere et problem, der er beskrevet i MS08-072
  - Dyon Balding fra [Secunia Research](http://secunia.com/) for at have rapporteret et problem, der er beskrevet i MS08-072.
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at have rapporteret et problem, der er beskrevet i MS08-072
  - Wushi, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative,](http://www.zerodayinitiative.com/) for at rapportere et problem beskrevet i MS08-072
  - Aaron Portnoy fra [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) for at rapportere problemer, der er beskrevet i MS08-072
  - Wushi fra [team509](http://www.team509.com/), der arbejder sammen med [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS08-072
  - Wushi og Ling, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at rapportere et problem beskrevet i MS08-072
  - Carlo Di Dato (aka shinnai) for at rapportere et problem, der er beskrevet i MS08-073
  - Zero Day InitiativeBrett Moore, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem beskrevet i MS08-073
  - Chris Weber fra [Casaba Security](http://www.casabasecurity.com/) for at rapportere et problem beskrevet i MS08-073
  - Jun Mao fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret et problem, der er beskrevet i MS08-073
  - Joshua J. Drake fra [Verisign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem beskrevet i MS08-074.
  - Claes M Nyberg fra [signedness.org](http://www.signedness.org/) for at rapportere et problem beskrevet i MS08-074
  - Dyon Balding fra [Secunia](http://secunia.com/) for at rapportere et problem beskrevet i MS08-074.
  - Andre Protas fra [eEye Digital Security](http://www.eeye.com/) for at rapportere et problem beskrevet i MS08-075
  - Nate McFeters for at rapportere et problem beskrevet i MS08-075
  - En anonym bruger for at rapportere et problem beskrevet i MS08-077

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis.
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (9. december 2008): Oversigt over bulletin offentliggjort.
  - V2.0 (10. december 2008): Rettede berørte programmer til MS08-076 for at anføre Windows Media Format Runtime 9.5 og Windows Media Format Runtime 11 som separate opdateringer på Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2. Der er desuden fjernet fejlagtige henvisninger til Windows Media Format Runtime 11 x64 Edition på Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2 til MS08-076.
  - V3.0 (17. december 2008): Tilføjet sikkerhedsbulletin fra Microsoft MS08-078, sikkerhedsopdatering til Internet Explorer (960714). Tilføjede også bulletin-webcast-links til denne out-of-band-sikkerhedsbulletin.
  - V3.1 (18. december 2008): Der er til MS08-078 tilføjet en uberørt hovedinstallationsnotation til Windows Internet Explorer 7 i Windows Server 2008 til 32-bit-systemer og i Windows Server 2008 til x64-baserede systemer.
  - V3.2 (7. januar 2009): Microsoft Office Word Viewer 2003 er fjernet fra listen over berørte programmer for MS08-072.
  - V4.0 (13. januar 2009): Microsoft har genudgivet MS08-076 for at tilbyde nye opdateringspakker til Windows Media Format Runtime 9.5 på Windows XP Service Pack 2 (KB952069) og på Windows XP Service Pack 3 (KB952069). Kunder med andre understøttede og berørte versioner af Windows Media-komponenter, som allerede har anvendt de oprindelige MS08-076-sikkerhedsopdateringspakker, behøver ikke foretage sig yderligere. Desuden tilføjes Windows Media Player 6.4 og Windows Media Services 4.1 som berørte på alle udgaver af Microsoft Windows 2000 Service Pack 4 for MS08-076. Kunder, der har fået tilbudt denne opdatering, KB954600 til Windows Media Player 6.4 eller KB952068 til Windows Media Services 4.1, men ikke har anvendt den, bør anvende den. Sluttelig tilføjes Microsoft Office Word Viewer som berørt for MS08-072. Kunder, der allerede har installeret sikkerhedopdatering KB956366 behøver ikke geninstallere.
  - V5.0 (28. januar 2009): Tilføjet en fodnote til MS08-074 i oversigten over **Berørte programmer**, der vedrører sikkerhedsopdateringerne KB958437 og KB958439 til understøttede versioner af Microsoft Office Excel 2007. Der er ikke foretaget ændringer i sikkerhedsopdateringens binære koder eller i registreringen. Kunder med Microsoft Office Excel 2007 eller Microsoft Office Excel 2007 Service Pack 1, der på forhånd har installeret KB958437 og KB958439, behøver ikke at geninstallere.

*Built at 2014-04-18T01:50:00Z-07:00*

