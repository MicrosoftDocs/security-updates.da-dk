---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for april 2009
TOCTitle: MS09-APR
ms:assetid: ms09-apr
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms09-apr(v=Security.10)
ms:contentKeyID: 61224048
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for april 2009

Offentliggjort: 14. april 2009

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for april 2009.

Med udgivelsen af bulletiner for april 2009 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 9. april 2008. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 9. april 2009 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få april måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395126). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i tekstkonvertere til WordPad og Office kan muliggøre fjernudførelse af kode (960477)</strong><br />
<br />
Denne sikkerhedsopdatering løser to offentliggjorte sårbarheder og to privat rapporterede sårbarheder i tekstkonvertere til WordPad og Office fra Microsoft. Sårbarhederne kan muliggøre fjernudførelse af kode, hvis en særligt udformet fil åbnes i WordPad eller Microsoft Office Word. Åbn ikke filer til Microsoft Office, RTF, Write eller WordPerfect fra ukendte kilder, der anvender de pågældende versioner af WordPad eller Microsoft Office Word.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139852">MS09-013</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i HTTP-tjenester fra Windows kan muliggøre fjernudførelse af kode (960803)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed og to privat rapporterede sårbarheder i HTTP-tjenester fra Microsoft (WinHTTP). Den mest alvorlige sårbarhed kan muliggøre fjernudførelse af kode. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139107">MS09-011</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft DirectShow kan muliggøre fjernudførelse af kode (961373)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft DirectX. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger har åbnet en særligt udformet MJPEG-fil. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td style="border:1px solid black;"><strong>Samlet sikkerhedsopdatering til Internet Explorer (963027)</strong><br />
<br />
Denne kritiske sikkerhedsopdatering løser fire privat rapporterede sårbarheder og to offentliggjorte sårbarheder i Internet Explorer. Sårbarhederne kan muliggøre fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside i Internet Explorer, eller hvis en bruger opretter forbindelse til en hackers server ved brug af en HTTP-protokol. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=143568">MS09-009</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (968557)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret og en offentliggjort sårbarhed. Sårbarhederne kan muliggøre fjernudførelse af kode, hvis en bruger åbner en særligt udformet Excel file. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Windows kan tillade udvidelse af rettigheder (959454)</strong><br />
<br />
Denne sikkerhedsopdatering løser fire offentliggjorte sårbarheder i Microsoft Windows. Sårbarhederne kan tillade en udvidelse af rettigheder, hvis en hacker får mulighed for at logge på systemet og køre et særligt udformet program. Hackeren skal være i stand til at køre koden på den lokale maskine, før denne svaghed kan udnyttes. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over det berørte system.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141639">MS09-016</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft ISA Server and Forefront Threat Management Gateway (Medium Business Edition) kan forårsage en Denial-of-Service (961759)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret og en offentliggjort sårbarhed som publiceret i Microsoft Internet Security and Acceleration (ISA) Server samt Microsoft Forefront Threat Management Gateway (TMG), Medium Business Edition (MBE). Disse sårbarheder kan forårsage denial-of-service, hvis en hacker sender særligt udformede netværkspakker til det berørte system, eller afsløring af oplysninger, hvis en bruger klikker på et skadeligt URL eller besøger et websted, der indeholder indhold kontrolleret af hackeren.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial-of-Service</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Forefront Edge Security</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146803">MS09-015</a></td>
<td style="border:1px solid black;"><strong>Blandet trusselssårbarhed i SearchPath kan give mulighed for udvidelse af rettigheder (959426)</strong><br />
<br />
Denne sikkerhedsopdatering løser problemet med en offentliggjort sårbarhed i søgestifunktionen i Windows og kan give mulighed for udvidelse af rettigheder, hvis en bruger downloader en særligt udformet fil på et bestemt sted og derefter åbner et program, der er i stand til at indlæse filen under visse omstændigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Udvidelse af rettigheder</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=143568">MS09-009</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (968557)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0100">CVE-2009-0100</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=143568">MS09-009</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (968557)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0238">CVE-2009-0238</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td style="border:1px solid black;">Sårbarheder i tekstkonvertere til WordPad og Office kan muliggøre fjernudførelse af kode (960477)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4841">CVE-2008-4841</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td style="border:1px solid black;">Sårbarheder i tekstkonvertere til WordPad og Office kan muliggøre fjernudførelse af kode (960477)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0087">CVE-2009-0087</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Dette er en kompliceret sårbarhed pga. adskillige kodestier. Det meste exploit-kode vil give inkonsekvente resultater. Forebyggende standardfaktorer beskytter mod denne vektor.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td style="border:1px solid black;">Sårbarheder i tekstkonvertere til WordPad og Office kan muliggøre fjernudførelse af kode (960477)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0088">CVE-2009-0088</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Denne sårbarhed kan udnyttes, men påvirker kun ældre versioner og ældre, ikke-udbredte filformater. Nyere versioner som f.eks. Microsoft Office-systemet fra 2007 og Microsoft Office 2003 Service Pack 3 er ikke påvirket.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td style="border:1px solid black;">Sårbarheder i tekstkonvertere til WordPad og Office kan muliggøre fjernudførelse af kode (960477)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0235">CVE-2009-0235</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Denne sårbarhed i forbindelse med beskadigelse af hukommelsen er nem at udnytte.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139107">MS09-011</a></td>
<td style="border:1px solid black;">En sårbarhed i Microsoft DirectShow kan muliggøre fjernudførelse af kode (961373)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0084">CVE-2009-0084</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows kan tillade udvidelse af rettigheder (959454)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-1436">CVE-2008-1436</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows kan tillade udvidelse af rettigheder (959454)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0078">CVE-2009-0078</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows kan tillade udvidelse af rettigheder (959454)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0079">CVE-2009-0079</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td style="border:1px solid black;">Sårbarheder i Windows kan tillade udvidelse af rettigheder (959454)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0080">CVE-2009-0080</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139852">MS09-013</a></td>
<td style="border:1px solid black;">Sårbarheder i HTTP-tjenester fra Windows kan muliggøre fjernudførelse af kode (960803)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0086">CVE-2009-0086</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Dette er en sårbarhed i forbindelse med hukommelsen, der er nem at kontrollere og med mange angrebsvektorer og muligheder for udnyttelse pga. den udbredte brug af denne teknologi.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139852">MS09-013</a></td>
<td style="border:1px solid black;">Sårbarheder i HTTP-tjenester fra Windows kan muliggøre fjernudførelse af kode (960803)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0089">CVE-2009-0089</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Exploit-værktøjer er blevet offentliggjort</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139852">MS09-013</a></td>
<td style="border:1px solid black;">Sårbarheder i HTTP-tjenester fra Windows kan muliggøre fjernudførelse af kode (960803)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550">CVE-2009-0550</a>**</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Exploit-kode er blevet offentliggjort.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (963027)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540">CVE-2008-2540</a>*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Der eksisterer ingen kendte angrebsvektorer for dette problem i øjeblikket, da sårbarheden kræver et andet program for at tillade, at en fil bliver gemt på et system uden brugerens kendskab. </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (963027)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550">CVE-2009-0550</a>**</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Exploit-kode er blevet offentliggjort.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (963027)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0551">CVE-2009-0551</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (963027)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0552">CVE-2009-0552</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Forebyggende faktorer for Internet Explorer 7 forhindrer udførelse af kode. Internet Explorer 6 og tidligere versioner har højere risiko for at blive udnyttet, hvis de ikke er udstyret med alle sikkerhedsopdateringer.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (963027)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0553">CVE-2009-0553</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td style="border:1px solid black;">Samlet sikkerhedsopdatering til Internet Explorer (963027)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0554">CVE-2009-0554</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=146803">MS09-015</a></td>
<td style="border:1px solid black;">Blandet trusselssårbarhed i SearchPath kan give mulighed for udvidelse af rettigheder (959426)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540">CVE-2008-2540</a>*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Angrebsoplysninger er blevet offentliggjort.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141639">MS09-016</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft ISA Server og Forefront Threat Management Gateway (Medium Business Edition) kan forårsage en Denial-of-Service (961759)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0077">CVE-2009-0077</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Tjenestebaseret Denial-of-Service er meget sandsynligt. Udførelse af kode er dog ikke mulig.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141639">MS09-016</a></td>
<td style="border:1px solid black;">Sårbarheder i Microsoft ISA Server og Forefront Threat Management Gateway (Medium Business Edition) kan forårsage en Denial-of-Service (961759)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-0237">CVE-2009-0237</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Offentliggørelse af oplysninger er mulig. Udførelse af kode er meget usandsynlig.</td>
</tr>
</tbody>
</table>


\*Disse sårbarheder, med identisk CVE-nummer, løses i to sikkerhedsopdateringer. Se de respektive bulletiner for at få yderligere oplysninger.

\*\*Disse sårbarheder, med identisk CVE-nummer, løses i to sikkerhedsopdateringer. Se de respektive bulletiner for at få yderligere oplysninger.

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
  </tr>
                <tr><th colspan="7" style="border:1px solid black;">Microsoft Windows 2000</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">(Ingen alvorlighedsklassifikation)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=552d322a-5282-42c7-9c1e-1d8c494a7318">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39d5468e-5733-4c3e-9e75-3adac8ac8cb9">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ec5b7c7-13d3-467a-b24e-3cc6fb47adf6">DirectX 8.1</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b98ed5c-a3ab-45a7-a61e-349eae304bc6">DirectX 9.0</a>***<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7799fd05-5b26-449f-8a14-50227c9164d1">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87f0c380-5c31-4099-a6a9-c12f9d69b03b">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52b756e7-636f-4d9e-8a17-dbf467bfbe4d">Microsoft Windows 2000 Service Pack 4</a><br />(KB952004)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4e408d7-6716-4a12-ad3a-8029667f5c84">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Ingen alvorlighedsklassifikation)</td></tr>
              
                <tr><th colspan="7" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50a8519a-503e-43dd-a78a-c1bc764fd213">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35af4151-1858-4c9a-85e4-9ff45feca1a4">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feb5d821-f210-40e8-b1aa-2ca3170df8df">DirectX 9.0</a>***<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=052c29fc-e8df-402c-9ab1-1079bc738e1b">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55d6729a-9f96-4da4-b564-676c0a0c9390">Windows Internet Explorer 7</a><br />(Kritisk)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90fe715e-8190-43e9-9c43-df5be564d923">Windows XP Service Pack 2 og Windows XP Service Pack 3</a><br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73d2324f-be59-4b0c-b1ac-9876a13c2c03">Windows XP Service Pack 2 og Windows XP Service Pack 3</a><br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3de0684d-605c-489b-bdc7-08bce9b2d4f6">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49b16f0f-f6c3-4ca8-8041-392f4f7b5bbb">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1be8b7c-4874-4342-99b3-76ff725fbb9a">DirectX 9.0</a>***<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84c62211-2e82-4ccc-9f9b-26462b026d86">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=191c2f20-89ae-4e1c-bdd4-24b4abfe6b6c">Windows Internet Explorer 7</a><br />(Kritisk)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a794c32a-9a0c-47d9-9c57-ff5d4a8e4944">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b2f12ae5-0e46-47e1-ac5b-93550d030189">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b743a7fe-7bf4-420d-a72e-39471e5659fa">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="7" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2233a4d2-7c8a-4c89-b020-100d9afb43c8">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=42509f5a-d0f9-444a-9445-5eabdb555011">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1b4cd76-1dd6-43fa-bb9a-20c428985bfd">DirectX 9.0</a>***<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f73a3669-c17f-4b18-8456-96cb7d52ed86">Microsoft Internet Explorer 6</a>
                    <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a45dbd0-0520-4d9b-b76e-3f5109dd310d">Windows Internet Explorer 7</a><br />(Alvorlig)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25adec10-db8c-4cac-bf74-2c784678150a">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=42aba890-8b76-4c5a-8fb6-609797d19831">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=992bb0cd-fbc7-4a7c-9088-f7f9d9a3ead0">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7373ea32-bc2e-49f1-8b9f-4eeda5acc74c">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f0e1e1db-94a5-451c-ab11-6b431fa065f1">DirectX 9.0</a>***<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03a9d581-2bd5-4151-9826-17b96e16f606">Microsoft Internet Explorer 6</a>
                    <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60ccc1d6-ea31-420c-b630-d7878a8dc527">Windows Internet Explorer 7</a><br />(Alvorlig)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b014c399-f404-4cb2-8f9d-864df382efeb">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0609f65-82d9-4d82-9f48-f3266e8de123">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f0a58e8c-7d63-4d7d-ba95-b3787cf408f0">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e840b9cb-f1f4-482a-aa07-eb6b42b477c4">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05e33cc5-cff6-4c71-be71-285f66a95e01">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f36c215-fa8a-40c2-b680-6b1fece03b8d">DirectX 9.0</a>***<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=53d13c07-80b0-4f05-b372-a2dac17e6157">Microsoft Internet Explorer 6</a>
                    <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0abaa2fb-7c4f-4149-993d-1575888bfc84">Windows Internet Explorer 7</a><br />(Alvorlig)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ada372b-ba17-433e-b022-d2c57b35af8a">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a><br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fda8837c-e5d2-4489-9b44-4c24a1102e77">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a><br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00c6479d-f81f-445d-b8e4-7b71d77d540a">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="7" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
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
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Vista og Windows Vista Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f071d770-3b6b-4040-9911-d4de8cde4c68">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d743849d-f3b5-4114-adef-ade2716d55ac">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f111b99a-e555-4f29-8d1f-e9ec03d5cf1f">Windows Vista og Windows Vista Service Pack 1</a><br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0ea1598-45cb-4c79-8945-caae98969675">Windows Vista og Windows Vista Service Pack 1</a><br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b672d45-f33b-4edc-9f22-2f2c8c726a8b">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ceef2d0-f316-48d1-aecc-d74f91cc5e1f">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d191c8dc-a965-4a6a-b6d8-1470505eb55f">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa153bdc-6b48-4df2-9e5e-abacd6da782c">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6dd82f4b-bb33-41ec-90a7-9ef91329b240">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7576e7d5-5bb1-4a53-b568-1ee0500ce721">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="7" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til 32 bit-systemer                    </td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c36548f-c8c9-4318-91e2-9e0501339548">Windows Server 2008 til 32 bit-systemer</a>*<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2c6313c-3ba9-4f7c-b259-b4582a390146">Windows Internet Explorer 7</a>**<br />(Alvorlig)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e3c7b52-65a7-42fb-beb5-1b374934737f">Windows Server 2008 til 32 bit-systemer</a>*<br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d58702af-bbf8-4f1b-ae72-ced9ef23d581">Windows Server 2008 til 32 bit-systemer</a>*<br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b73cf5e-66fe-4b7d-95fc-91a1c262c1e5">Windows Server 2008 til 32 bit-systemer</a>*<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c3f0997-a8a9-4340-ae0c-2c4d6792c65c">Windows Server 2008 til x64-baserede systemer</a>*<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebbade9d-704c-440b-8796-6d64225ac01a">Windows Internet Explorer 7</a>**<br />(Alvorlig)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eebb4d4d-29d2-4247-8cbb-63a3b17585ec">Windows Server 2008 til x64-baserede systemer</a>*<br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20bf4e9b-909b-4bc3-ae43-322d74a4f1c3">Windows Server 2008 til x64-baserede systemer</a>*<br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e60847c-b341-4c38-bc25-2e3cf2d4ae14">Windows Server 2008 til x64-baserede systemer</a>*<br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0885b3b0-b78e-4980-902d-dff3886bcaac">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b04aa6f-b787-4122-bf82-0d150618fe7a">Windows Internet Explorer 7</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Opdatering af MSDTC Transaction Facility:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cc383c24-b0f6-47c1-9e89-6a378b09e82f">Windows Server 2008 til Itanium-baserede systemer</a><br />(KB952004)<br />(Alvorlig)<br /><br />Opdatering til Windows Service Isolation:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bcc2b18f-67db-4109-a9f4-764f985423ee">Windows Server 2008 til Itanium-baserede systemer</a><br />(KB956572)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de1c2b4b-af47-4b9a-8363-720e5527573c">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Moderat)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008**

**\*Windows Server 2008 - serverens hovedinstallation er berørt.** For understøttede udgaver af Windows Server 2008 gælder denne opdatering med den samme klassifikation, uanset om Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core eller ej. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 - serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008, hvis Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkning til MS09-010**

Se også afsnittet, **Microsoft Office Suites og software**, for at få flere opdateringsfiler. Denne bulletin omhandler både Windows-operativsystem og komponenter og Microsoft Office-suiten og softwaren.

**Bemærkning til MS09-011**

\*\*\*Opdateringen til DirectX 9.0 er også gældende for DirectX 9.0a, DirectX 9.0b og DirectX 9.0c.

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
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143568">
                      <strong>MS09-009</strong>
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
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2000 Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95876927-e612-414c-bdec-3632a3100415">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB921606)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3dc8b670-25a5-4f46-b7de-12bc693b628a">Microsoft Office Excel 2000 Service Pack 3</a>
                    <br />(KB959964)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1db55c6-78fb-498d-89a5-9ad54d971546">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB933399)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a52bf4b-05f6-4b73-94b9-28ed7e20f86c">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB959988)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9dbfa63-c0cb-4c84-9b8a-6e52568045b0">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB959995)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">2007 Microsoft Office System Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50d8630b-1365-4007-81a0-18c0d6d4b86e">Microsoft Office Excel 2007 Service Pack 1</a>*<br />(KB959997)<br />(Alvorlig)<br /></td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office til Mac</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143568">
                      <strong>MS09-009</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2004 til Mac</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52271140-89be-4b9c-baa2-cea09097d703">Microsoft Office 2004 til Mac</a>
                    <br />(KB968695)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2008 til Mac</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6e407eb-11a5-433f-8006-4b822953ca98">Microsoft Office 2008 til Mac</a>
                    <br />(KB968694)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Anden Office Software</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143568">
                      <strong>MS09-009</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Excel Viewer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72e6087-b48f-4d2d-8366-01d9f5ff6b6c">Microsoft Office Excel Viewer 2003 Service Pack 3</a>
                    <br />(KB959993)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58b3929c-5373-47a4-aa97-66d179758792">Microsoft Office Excel Viewer</a><br />(KB960000)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05f7c517-e551-4dcd-b24a-5d548f2d09cf">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1</a>
                    <br />(KB960003)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Converter Pack</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d763fae3-b2af-47f9-a554-ec786766b3c3">Microsoft Office Converter Pack</a>
                    <br />(KB960476)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**Bemærkning til MS09-010**

Se også afsnittet **Windows-operativsystemer og komponenter** for mere opdaterede filer. Denne bulletin omhandler både Windows-operativsystem og komponenter og Microsoft Server Software.

**Bemærkning til MS09-009**

\*Hvad angår Microsoft Office Excel 2007 Service Pack 1, skal brugere også installere sikkerhedsopdateringen til Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformaterne, Service Pack 1, for at være beskyttet imod de sårbarheder, der er beskrevet i denne bulletin.

#### Microsoft Server og Security Software

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Forefront</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141639">
                      <strong>MS09-016</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Forefront Threat Management Gateway</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6abf9fb4-42d0-4c67-935f-8dc67850148b">Microsoft Forefront Threat Management Gateway, Medium Business Edition</a>*<br />(KB968075)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="2" style="border:1px solid black;">Internet Security and Acceleration Server</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141639">
                      <strong>MS09-016</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Internet Security and Acceleration Server 2004</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=adf623fa-2d74-4f2a-9835-4b8debdb0e1b">Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3</a>**<br />(KB960995)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1d55ab6-3de5-4811-9693-8d43f49f5fe8">Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3</a><br />(KB960995)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Internet Security and Acceleration Server 2006</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770">Microsoft Internet Security and Acceleration Server 2006</a>
                    <br />(KB968078)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770">Supportopdatering til Microsoft Internet Security and Acceleration Server 2006</a><br />(KB968078)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770">Microsoft Internet Security and Acceleration Server 2006 Service Pack 1</a><br />(KB968078)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til MS09-016**

\*Microsoft Forefront Threat Management Gateway, Medium Business Edition, leveres både som et separat produkt og som en komponent tilhørende Windows Essential Business Server 2008.

\*\*Microsoft ISA Server 2004 Standard Edition leveres som et separat produkt. Microsoft ISA Server 2004 Standard Edition leveres både som en komponent til Windows Small Business Server 2003 Enterprise Edition Service Pack 1 og Windows Small Business Server 2003 R2 Enterprise Edition.

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

  - Haifei Li fra Fortinets [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) for at rapportere et problem, der er beskrevet i ms09-009
  - Sean Larsson og Jun Mao fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem, der er beskrevet i MS09-010
  - En forsker hos Fortinets [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) for at rapportere et problem, der er beskrevet i MS09-010
  - En forsker hos [VeriSign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem, der er beskrevet i MS09-010
  - Piotr Bania fra [Kryptos Logic](http://www.kryptoslogic.com/) for at rapportere et problem, der er beskrevet i MS09-011
  - Cesar Cerrudo fra [Argeniss](http://www.argeniss.com/) for at rapportere flere problemer, der er beskrevet i MS09-012
  - Greg MacManus fra [iSIGHT Partners Labs](http://www.isightpartners.com/) for at rapportere et problem, der er beskrevet i MS09-013
  - Wan-Teh Chang og Cem Paya fra [Google Inc.](http://www.google.com/) for at rapportere et problem, der er beskrevet i MS09-013
  - [Aviv Raff](http://aviv.raffon.net/) for at rapportere et problem, der er beskrevet i MS09-014
  - Michal Zalewski fra [Google Inc.](http://www.google.com/) for at rapportere et problem, der er beskrevet i MS09-014
  - Ivan Fratric fra [iSIGHT Partners Labs](http://www.isightpartners.com/) for at rapportere et problem, der er beskrevet i MS09-014
  - Skylined fra [Google Inc.](http://www.google.com/) for at rapportere et problem, der er beskrevet i MS09-014
  - ADLab fra [Venustech](http://www.venustech.com.cn) for at have rapporteret et problem, der er beskrevet i MS09-014
  - [Aviv Raff](http://aviv.raffon.net/) for at rapportere et problem, der er beskrevet i MS09-015
  - Informationsdirektøren for New York State/teknologisk institut for at rapportere et problem, der er beskrevet i MS09-016

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (14. april 2009): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

