---
title: Oversigt over sikkerhedsbulletiner fra Microsoft for juni 2010
TOCTitle: MS10-JUN
ms:assetid: ms10-jun
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms10-jun(v=Security.10)
ms:contentKeyID: 61224066
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsbulletiner fra Microsoft for juni 2010

Offentliggjort: 8. juni 2010 | Opdateret: 13. september 2011

**Version:** 2.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for juni 2010.

Med udgivelsen af sikkerhedsbulletiner for juni 2010 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 3. juni 2010. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 9. juni 2010 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få juni måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427727&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td><strong>Sårbarheder i mediedekomprimering kan give mulighed for fjernudførelse af kode (979902)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Windows. Disse sårbarheder kan muliggøre fjernudførelse af kode, hvis en bruger åbner en særligt udformet mediefil eller modtager særligt udformet streamingindhold fra et websted eller et program, der leverer webindhold. En hacker, som har held til at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=185159">MS10-034</a></td>
<td><strong>Samlet sikkerhedsopdatering af kill-bitter for ActiveX (980195)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft-software. Denne sikkerhedsopdatering er klassificeret som Kritisk for alle understøttede versioner af Microsoft Windows 2000, Windows XP, Windows Vista og Windows 7 samt Moderat for alle understøttede udgaver af Windows Server 2008 og Windows Server 2008 R2.<br />
<br />
Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside, der aktiverer et specifikt ActiveX-objekt i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Denne opdatering omfatter også killbitter til fire ActiveX-objekter fra tredjepart.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td><strong>Samlet sikkerhedsopdatering til Internet Explorer (982381)</strong><br />
<br />
Denne sikkerhedsopdatering løser fem privat rapporterede sårbarheder og én offentliggjort sårbarhed i Internet Explorer. De mest alvorlige sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside via Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td><strong>Sårbarheder i Windows-kernetilstandsdrivere kan give mulighed for udvidelse af rettigheder (979559)</strong><br />
<br />
Denne sikkerhedsopdatering løser to offentliggjorte sårbarheder og en privat rapporteret sårbarhed i Windows-kernetilstandsdrivere. Sårbarheden kan tillade udvidelse af rettigheder, hvis en bruger får vist indhold gengivet med en særlig udformet TrueType-skrifttype.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190554">MS10-036</a></td>
<td><strong>Sårbarhed i COM-validering i Microsoft Office kan give mulighed for fjernudførelse af kode (983235)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i COM-validering i Microsoft Office. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet fil i Excel, Word, Visio, Publisher, eller PowerPoint med en berørt version af Microsoft Office. Sårbarheden kan ikke udnyttes automatisk via e-mail. For at et angreb skal lykkes, skal en bruger åbne en vedhæftet fil, der sendes i en e-mail-meddelelse.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190508">MS10-037</a></td>
<td><strong>Sårbarhed i OpenType CFF-driveren (Compact Font Format) kan give mulighed for udvidelse af rettigheder (980218)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows OpenType CFF-driveren (Compact Font Format). Sårbarheden kan tillade udvidelse af rettigheder, hvis en bruger får vist indhold gengivet med en særlig udformet CFF-skrifttype. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes via fjernadgang eller af anonyme brugere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td><strong>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (2027452)</strong><br />
<br />
Denne sikkerhedsopdatering løser fjorten privat rapporterede sårbarheder i Microsoft Office. De mere alvorlige sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Excel-fil. En hacker, som det lykkes at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td><strong>Sårbarheder i Microsoft SharePoint kan muliggøre udvidelse af rettigheder (2028554)</strong><br />
<br />
Denne sikkerhedsopdatering løser én offentliggjort sårbarhed og to privat rapporterede sårbarheder i Microsoft SharePoint. Den mest alvorlige af sårbarhederne kan tillade en udvidelse af rettigheder, hvis en hacker overbeviser en bruger af et målrettet SharePoint-site om at klikke på et særligt udformet hyperlink.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office, Microsoft Server Software</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191788">MS10-040</a></td>
<td><strong>En sårbarhed i Internet Information Services kan muliggøre fjernudførelse af kode (982666)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Internet Information Services (IIS). Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger har modtaget en særligt udformet HTTP-forespørgsel. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=185042">MS10-041</a></td>
<td><strong>Sårbarheder i Microsoft .NET Framework kan give muligheder for uautoriserede ændringer (981343)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Microsoft NET Framework. Sårbarheden kan muliggøre uautoriserede ændringer i signeret XML-indhold uden registrering. I tilpassede programmer afhænger sikkerhedspåvirkningen af, hvordan det signerede indhold anvendes i det specifikke program. Scenarier, hvor signerede XML-meddelelser overføres over en sikker kanal (som f.eks. SSL), påvirkes ikke af denne sårbarhed.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Uautoriserede ændringer</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er anført i faldende rækkefølge i forhold til CVE ID's vurderingsniveau for udnyttelse. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

**Hvordan anvender jeg denne tabel?**

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td>Sårbarhed vedr. vinduesoprettelse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0485">CVE-2010-0485</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td>Sårbarhed i Help.aspx XSS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0817">CVE-2010-0817</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Denne sårbarhed blev rapporteret første gang i <a href="microsoft-security-advisory-983438.md">Microsoft Security Advisory 983438</a></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. stakoverflow i Excel-objekt</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0822">CVE-2010-0822</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Excel-post</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0824">CVE-2010-0824</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Excel-post</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1245">CVE-2010-1245</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Excel RTD</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1246">CVE-2010-1246</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1247">CVE-2010-1247</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Excel HFPicture</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1248">CVE-2010-1248</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1249">CVE-2010-1249</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Excel EDG</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1250">CVE-2010-1250</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. Excel ADO-objekt</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1253">CVE-2010-1253</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. Mac Office Open XML-tilladelser</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1254">CVE-2010-1254</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td>Sårbarhed vedr. defekt, ikke-initialiseret hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1259">CVE-2010-1259</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td>Sårbarhed vedr. defekt hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1262">CVE-2010-1262</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190554">MS10-036</a></td>
<td>Sårbarhed i COM-validering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263">CVE-2010-1263</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td>Sårbarhed i mediedekomprimering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1879">CVE-2010-1879</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td>Sårbarhed vedr. offentliggørelse af oplysninger på tværs af domæner</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0255">CVE-2010-0255</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Denne sårbarhed blev rapporteret første gang i <a href="microsoft-security-advisory-980088.md">Microsoft Security Advisory 980088</a></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td>Sårbarhed vedr. forkert datavalidering i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0484">CVE-2010-0484</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190508">MS10-037</a></td>
<td>Sårbarhed vedr. defekt hukommelse i driver til OpenType CFF-skrifttype</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0819">CVE-2010-0819</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt parsing-hukommelse i Excel-post</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0821">CVE-2010-0821</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0823">CVE-2010-0823</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. defekt stakhukommelse i Excel-post</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1251">CVE-2010-1251</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td>Sårbarhed vedr. Excel-strengvariabel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1252">CVE-2010-1252</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td>Sårbarhed vedr. skrifttype-parsing i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1255">CVE-2010-1255</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191788">MS10-040</a></td>
<td>Sårbarhed vedr. defekt hukommelse for IIS-godkendelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1256">CVE-2010-1256</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td>Sårbarhed i MJPEG-mediedekomprimering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1880">CVE-2010-1880</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=185042">MS10-041</a></td>
<td>Sårbarhed vedr. XML-signatur i forbindelse med omgåelse af godkendelse af HMAC-afkortelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0217">CVE-2009-0217</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Dette er en sårbarhed over for spoofing og uautoriserede ændringer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td>Sårbarhed vedr. offentliggørelse af oplysninger i toStaticHTML</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257">CVE-2010-1257</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Denne sårbarhed påvirker <a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td>Sårbarhed vedr. offentliggørelse af oplysninger i toStaticHTML</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257">CVE-2010-1257</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Denne sårbarhed påvirker <a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td>Sårbarhed vedr. Sharepoint-hjælpeside Denial-of-Service</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1264">CVE-2010-1264</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
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
  </tr>
                <tr><th colspan="8">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Kritisk</strong>
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
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60c8579b-1540-40d8-80a0-956edadd63ce">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a51c53bd-f9c1-4d53-8ed2-034fd57bc75a">Quartz.dll (DirectShow) (DirectX 9)</a>
                    [1]
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8417c0ac-bb6d-48f1-8237-77a4bdd8ccb2">Windows Media Format Runtime 9</a>[2]<br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f929739-08a1-4faf-9ccf-5f1f43c5bb9e">Asycfilt.dll (COM component)</a><br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3955983-0079-476e-a488-99713097259c">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a6c09e5-c655-41a0-a133-78d55267a527">Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Ingen alvorlighedsklassifikation)[1]<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2f27eeb-54be-40be-a00e-72867090b8e7">Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d645891-31e9-42c4-b12b-eb351473fd0c">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB979909)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="8">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Kritisk</strong>
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
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=023a777a-3d83-4a4e-8029-da8b095b074b">Windows XP Service Pack 2 and Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e77d5af8-e8e0-425c-a809-4cf274e17cc5">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br />Kun Windows XP Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf8b9b46-ba28-4f48-9dac-6a90b7d592d3">Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 og Windows Media Format Runtime 11</a><br />(KB978695)<br />(Kritisk)<br /><br />Kun Windows XP Service Pack 3:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebbccd82-c637-4c88-86ea-d39ae713c085">Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 og Windows Media Format Runtime 11</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55c05cb8-aa6c-460b-9aa7-084842dab280">Asycfilt.dll (COM component)</a><br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8c3f2e81-c0ea-494a-a47c-4f8982effb49">Windows XP Service Pack 2 and Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfe87761-ed9e-4fec-a393-d7fddb919db4">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc02fc7e-ee85-4377-b54c-012fa60a8c9c">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9cff9aba-7743-4c33-87c7-37d06ed60a21">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b42a17c5-997e-4504-ba5b-bfa62166b460">Windows XP Service Pack 2 and Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Kun Windows XP Media Center Edition 2005: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394">Microsoft .NET Framework 1.0 Service Pack 3</a><br />(KB979904) <br />(Alvorlig)<br /><br />Kun Windows XP Media Center Edition 2005 og Windows XP Tablet PC Edition 2005: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394">Microsoft .NET Framework 1.0 Service Pack 3</a><br />(KB979904)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />(KB979906)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />(KB982865)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 and Microsoft .NET 3.5 Service Pack 1</a><br />(KB979909)<br />(Alvorlig)</td></tr>
                <tr><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3aac9d-7747-435f-9678-f621e314e070">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7914fdae-9a7a-4a10-8ce7-c621eb903452">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b56839e3-e7d3-48da-b90c-d403d8dbeed2">Windows Media Format Runtime 9.5</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555">Windows Media Format Runtime 9.5 x64 Edition</a>[3]<br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2887448-9d3c-472f-a0bd-ab083a65eafc">Windows Media Format Runtime 11</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7">Windows Media Encoder 9 x64</a><br />(KB979332)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c110d26e-9a1e-4e47-9ce2-4068f2733a2f">Asycfilt.dll (COM component)</a><br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3e462fb-df95-4b79-a8bc-5359c2967503">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7780af61-a206-49aa-a805-a49bdcbb5419">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c7cda29-161e-49b4-976a-c718c0aa11a0">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37cd7533-ddad-4d0d-85c0-1491308e1ff8">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc835b94-3368-4c1c-8f29-40517c73540e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />(KB982865)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 and Microsoft .NET Framework 3.5 Service Pack 1</a> (KB979909)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="8">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Moderate</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
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
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79a11dcd-5d88-4d83-beae-6580ef6fc2c0">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc15c43b-d48f-4872-8f9d-ed973170db9a">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb580e94-8c02-46f1-b7f6-e7d4373cb1c5">Windows Media Format Runtime 9,5</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ddf95ac-dd49-4cb1-b6f6-bd4e987b0f06">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c0bd349-aa77-47de-ba1d-1fcc72dcad28">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfb9acdb-2d9c-4c22-963c-8b9ce247350f">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f0187b69-3ed9-494c-89f1-90a35e22078c">Internet Explorer 7</a><br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebab6101-fcf1-4842-b22d-893a20c1c10f">Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ca49b5b5-db8e-4ebc-9a3c-b1ace09ac3c0">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0761c207-5465-4f42-b61f-bd02efcef27d">Internet Information Services 6,0</a>
                    [1]
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f82e1b73-7f8b-4f4c-8187-4050a11db44c">Microsoft .NET Framework 1,1 Service Pack 1</a>
                    <br />(KB979907)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3,5</a><br />(KB982865)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2,0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979909)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f42cc5d4-1bea-4a4a-8a08-b3eb92503588">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d28ecdf7-9fd4-437e-9db7-c6b579248abe">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41faf16f-c7a8-4ce0-b388-a65478576163">Windows Media Format Runtime 9,5</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555">Windows Media Format Runtime 9.5 x64 Edition</a>[3]<br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7">Windows Media Encoder 9 x64</a><br />(KB979332)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77b1d55c-b015-4863-aab0-6463b90d4bf7">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aa0ec4f-5502-4f2a-9732-975518c34444">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81644c43-22c0-4c61-b395-3264516516a6">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50b8ee2e-31f8-473d-83d1-822c89c28070">Internet Explorer 7</a><br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87e13912-f861-4985-ab9d-260a5898dfd4">Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0794e7e-c925-4672-b7a5-4bb3f847f045">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=023572ff-ce5d-4428-a96b-1245db6ff312">Internet Information Services 6,0</a>
                    [1]
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1,1 Service Pack 1</a>
                    <br />(KB979906)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3,5</a><br />(KB982865)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2,0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979909)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50efb1cf-9d89-4522-929d-f87fd98d6fe8">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f101f4c-dcc8-474c-a844-fe0c45d6697c">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f34bc115-022b-46b0-9517-806bd0fc73c5">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55d9d7f0-f9d9-4833-b5cc-eb87a62da6a8">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=abcdc3bb-4659-4b63-a9bd-e448f8bed90a">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=123bf547-9005-451f-9eba-97a68037304e">Internet Explorer 7</a><br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e76ebea-bde1-4352-a283-dd71c2cc51a1">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1f3e524-8ac6-4210-a3a8-4ffc58a606ea">Internet Information Services 6,0</a>
                    [1]
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />(KB982865)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979909)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="8">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                  </td></tr>
                <tr><td>Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cb64633-d2a0-4e38-be35-ec32ea655a04">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Kun Windows Vista Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b64107f2-990a-42df-a75a-5bf371709fd6">Quartz.dll (DirectShow)</a><br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75e4c9cb-a55a-4e2a-9c97-60a40353cae3">Asycfilt.dll (COM component)</a><br />(KB979482)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9fab91da-1528-4df9-a2dd-90e57a3c24cf">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ddaa4b3-1a98-4183-94af-ebdae4e7b76a">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=661c9528-917d-4df6-a330-c89f39dc5ce4">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=640f9216-3e99-46b6-aac8-cd051eedad3c">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=363b503a-2e1e-4284-a029-9695d2acfcb6">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01382926-2313-4769-a0a5-262c4f9f18a1">Internet Information Services 7.0</a>
                    [1]
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Alvorlig)<br /><br />Kun Windows Vista Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB979913)<br />(Alvorlig)<br /><br />Kun Windows Vista Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979911)<br />(Alvorlig)<br /><br />Kun Windows Vista Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB979910)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbfc4d80-67eb-4deb-9595-cb67942a0df2">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Kun Windows Vista x64 Edition Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0754addb-2f04-45c9-8594-174b8b8b297c">Quartz.dll (DirectShow)</a><br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9f033f6-f587-494d-b968-1316f1deed06">Asycfilt.dll (COM component)</a><br />(KB979482)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63bba49e-6d80-47b3-b109-fa9b2392af4f">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e19aeef8-6bef-45ee-bc9f-3e4b81a58e33">Windows Media Encoder 9 x64</a><br />(KB979332)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ddf55e74-dbaa-45f7-ac5b-ae3da24e0e33">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9f5feb0-fa1a-40c1-9971-9b8af6f0b4a5">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3076d1ea-7716-4b54-8ec4-660374f14dcb">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f512b86-3a99-47f7-a90e-1ae9b291385c">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7fb6f2b8-c7a6-4239-99f3-cf3aacf89b0f">Internet Information Services 7.0</a>
                    [1]
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Alvorlig)<br /><br />Kun Windows Vista x64 Edition Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB979913)<br />(Alvorlig)<br /><br />Kun Windows Vista x64 Edition Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979911)<br />(Alvorlig)<br /><br />Kun Windows Vista x64 Edition Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979910)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="8">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Moderate</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
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
                <tr><td>Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22d550fe-ba35-4750-a9d6-624858b67c94">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Kun Windows Server 2008 til 32 bit-systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18fd814b-51f3-470b-a5bd-97be752298d9">Quartz.dll (DirectShow)</a>**<br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c5e2dfc-0078-4f2a-9c2e-75e45bb7638e">Asycfilt.dll (COM-komponent)</a>*<br />(KB979482)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ce1e47f-b1c3-4480-bafd-74f8b12e2171">Windows Media Encoder 9 x86</a>**<br />(KB979332)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a06b9f42-47ac-4ff2-ac32-e4958cdb611e">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>**<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bed14484-7fc5-455d-b996-3192467543cc">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24ed08c7-a474-4458-8269-3b9de5e22385">Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e78ad607-d209-48c4-b0f3-ed4c70993174">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84a54246-5d9e-49e2-8170-af48b43f984d">Internet Information Services 7,0</a>*[1]<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB979906)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til 32-bit-systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB979913)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til 32-bit-systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB979911)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til 32-bit-systemer Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack </a>**<br />(KB979910)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09025626-4116-4a31-8700-215382898ee2">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Kun Windows Server 2008 til x64-baserede systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e40da51-23ee-44f0-9ea0-99bda8cca731">Quartz.dll (DirectShow)</a>**<br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfc0b62c-2d79-48dd-896f-d05057c02e8c">Asycfilt.dll (COM-component)</a>*<br />(KB979482)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93cc5ace-6382-4a2f-875b-9348b7e198a6">Windows Media Encoder 9 x86</a>**<br />(KB979332)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d650a7d7-5620-4bb7-a7ad-0848dd28dae3">Windows Media Encoder 9 x64</a>**<br />(KB979332)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6d0a3f7c-2617-4bc6-a4c7-cda26c6471e1">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>**<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a24554e8-213b-4c24-b062-ec424d64128e">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf84469b-ce6d-45e8-8336-7b4501c6cf91">Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85f6fc5d-efd1-4351-b4c0-b9b7080e6173">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38286e43-89a6-4895-8ff9-69452df38706">Internet Information Services 7,0</a>*[1]<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB979906)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til x64-baserede systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB979913)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til x64-baserede systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB979911)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til x64-baserede systemer Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack </a>**<br />(KB979910)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0035cfe2-d38d-41cd-b704-ec1feda307d8">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Kun Windows Server 2008 til Itanium-baserede systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=120c68f5-4575-4e2a-912a-eed52736c403">Quartz.dll (DirectShow)</a><br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e5753ab-848d-475f-917d-ba70f70b65f5">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38347fa6-5946-4bb5-9fea-a5b2f4e7c1f2">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dee5c0c0-b844-490d-8daf-6e6ec8a39e35">Internet Explorer 7</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c6f1aae5-e8fd-4121-89b2-b97c571e8223">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ad19eba-9821-48b4-a942-4ee4f002f913">Internet Information Services 7.0</a>
                    [1]
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB979906)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til Itanium-baserede systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB979913)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til Itanium-baserede systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979911)<br />(Alvorlig)<br /><br />Kun Windows Server 2008 til Itanium-baserede systemer Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979910)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="8">Windows 7</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                  </td></tr>
                <tr class="alternateRow"><td>Windows 7 til 32-bit-systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e0ff389-4612-4c92-bbff-bb45b5bdfc6a">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63567e99-087d-4804-953a-f23bdeba7772">Asycfilt.dll (COM-komponent)</a>
                    <br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5bce87fe-dcbb-4638-b248-3f0755537b00">Windows 7 til 32-bit-systemer</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c835885-9375-4882-a92f-4d4cfcacc005">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=969af8d6-f6da-4dd1-a7d7-2de54a5a8978">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=588167cb-f62a-4fb8-8a18-ac15dc322495">Internet Information Services 7.5</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB979916)<br />(Alvorlig)</td></tr>
                <tr><td>Windows 7 til x64-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b1e4aff-605a-4e94-88f9-135ce35f0646">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c261dbf-14c6-4071-8523-e8ba8059fa54">Asycfilt.dll (COM-komponent)</a>
                    <br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee68ecd0-5b8a-4c1e-bdee-bd8616558d43">Windows 7 til x64-baserede systemer</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5cfc5776-0c6b-4092-bc98-94df077c60d8">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b069e5b2-aa2d-452e-b687-8734b5ba0051">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c45d0c8-1629-470b-8167-c6bf66054595">Internet Information Services 7.5</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB979916)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="8">Windows Server 2008 R2</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Moderate</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
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
                <tr class="alternateRow"><td>Windows Server 2008 R2 til x64-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4272277f-b2dd-4406-8bbd-bc461c9923b8">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1331f2bc-7479-4be7-a413-52afb488a330">Asycfilt.dll (COM-komponent)</a>*<br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=901f7c89-02af-4f87-8592-dad318997d77">Windows Server 2008 R2 til x64-baserede systemer</a>**<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c4ff5ae-eadd-431e-b982-d5f179efb8c0">Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45242c7c-3752-44bf-a766-024ad7d28f53">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d9b7705-6280-4d2e-94fa-3160b3ce5cfa">Internet Information Services 7,5</a>*<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3,5.1</a>*<br />(KB979916)<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 R2 til Itanium-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d636f82-e828-468c-ac36-808ff9d37c7f">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a1ee54f-3f73-4557-9071-5af236e70937">Asycfilt.dll (COM-komponent)</a>
                    <br />(KB979482)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4958b221-2776-43d7-9e1c-1e1cb318a694">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52c04d85-911f-47be-852e-c9bb4934744d">Internet Explorer 8</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a271fb5-da5b-4a17-9593-e56b9a843b8f">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=869e900a-0063-4d8b-9b7c-7d12f6be12cd">Internet Information Services 7.5</a>
                    <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB979916)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i MSDN-artiklerne [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core til Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i MSDN-artiklerne [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core til Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkning til MS10-033**

\[1\]Opdateringen til Quartz.dll (Direct Show) (DirectX 9) er også gældende for DirectX 9.0a, DirectX 9.0b, and DirectX 9.0c.

\[2\]Denne opdateringspakke er relevant for Windows Media Format 9 SDK Runtime på Microsoft Windows 2000 med opdateringen til DRM-aktiverede medieafspillere (KB891122). Yderligere oplysninger finder du i [Microsoft Knowledge Base Article 974316](http://support.microsoft.com/kb/974316).

\[3\]Hvis du har installeret Windows Media Format Runtime 9.5 x64 Edition, skal du installere sikkerhedsopdateringerne til Windows Media Format Runtime 9.5 og Windows Media Format Runtime 9.5 x64 Edition for at være fuldt beskyttet mod den sårbarhed, der er beskrevet i MS10-033.

**Bemærkning til MS10-035**

\[1\]Klassifikationer gælder ikke for denne opdatering, idet sårbarhederne, der er beskrevet i denne bulletin, ikke påvirker denne software. Denne opdatering tilbydes til løsning af et regressionsproblem, der stammer fra [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979). Se [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) for yderligere oplysninger.

**Bemærkning til MS10-040**

\[1\]Dette operativsystem berøres kun, når udvidet beskyttelse til godkendelse er installeret. Se [Microsoft Knowledge Base-artiklen 973917](http://support.microsoft.com/kb/973917).

#### Microsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="4">Microsoft Office Suites, systemer og komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190554">
                      <strong>MS10-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191053">
                      <strong>MS10-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191905">
                      <strong>MS10-039</strong>
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
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Microsoft Office XP Service Pack 3</td><td>Microsoft Office XP Service Pack 3[1]<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fec14a92-79a1-4281-8ee2-659b2dfd283f">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB982299)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80fdd134-2a86-4115-aea1-841f19af92e3">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB982311)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1">Microsoft Office Excel 2003 Service Pack 3</a>[2]<br />(KB982133)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b6204c1-559f-45a5-8f6c-a1e216192efc">Microsoft Office PowerPoint 2003 Service Pack 3</a>[2]<br />(KB982157)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87bac893-81ec-4ede-aca1-a9aa48b92cd4">Microsoft Office Publisher 2003 Service Pack 3</a>[2]<br />(KB982122)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1595ada3-bb4f-40f6-8137-23eba918bc8a">Microsoft Office Visio 2003 Service Pack 3</a>[2]<br />(KB982126)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2c40eb5-1149-4466-840c-84f406f64245">Microsoft Office Word 2003 Service Pack 3</a>[2]<br />(KB982134)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB982133)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6deb4fb0-cbfc-40df-8f62-35fa1db0e167">2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2</a>
                    <br />(KB982312)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec">Microsoft Office Excel 2007 Service Pack 1 og Microsoft Office Excel 2007 Service Pack 2</a>[3]<br />(KB982308)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=decb834d-3958-45cc-a5ae-4283adb2462a">Microsoft Office PowerPoint 2007 Service Pack 1 og Microsoft Office PowerPoint 2007 Service Pack 2</a>[3]<br />(KB982158)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a74b986-1e99-4aa1-828f-757a36896f65">Microsoft Office Publisher 2007 Service Pack 1 og Microsoft Office Publisher 2007 Service Pack 2</a>[3]<br />(KB982124)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5df052e-1f38-4308-bcca-296cff22729b">Microsoft Office Visio 2007 Service Pack 1 og Microsoft Office Visio 2007 Service Pack 2</a>[3]<br />(KB982127)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e9708f0-8cd6-4f0b-8585-bccc54fa2755">Microsoft Office Word 2007 Service Pack 1 og Microsoft Office Word 2007 Service Pack 2</a>[3]<br />(KB982135)<br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec">Microsoft Office Excel 2007 Service Pack 1 og Microsoft Office Excel 2007 Service Pack 2</a>
                    [1]
                    <br />(KB982308)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="4">Microsoft Office til Mac</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190554">
                      <strong>MS10-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191053">
                      <strong>MS10-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191905">
                      <strong>MS10-039</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2004 til Mac</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16c71ab8-9284-407a-856a-93c67995f125">Microsoft Office 2004 til Mac</a>
                    <br />(KB2028866)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office 2008 til Mac</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d46255bd-6470-4106-9fe2-ea67acd3f1bd">Microsoft Office 2008 til Mac</a>
                    <br />(KB2028864)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Open XML File Format Converter til Mac</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6ca7b05-cf97-43a2-95eb-7b5caf7c1528">Open XML File Format Converter til Mac</a>
                    <br />(KB2078051)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="4">Anden Office Software</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190554">
                      <strong>MS10-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191053">
                      <strong>MS10-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191905">
                      <strong>MS10-039</strong>
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
                  </td></tr>
                <tr><td>Microsoft Excel Viewer Service Pack 1 og Microsoft Office Excel Viewer Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=033b3bf3-7826-4064-b001-11e4dce2d91a">Microsoft Office Excel Viewer Service Pack 1 og Microsoft Office Excel Viewer Service Pack 2</a>
                    <br />(KB982333)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Compatibility Pack til Word, Excel og PowerPoint 2007-filformater Service Pack 1 og Microsoft Office Compatibility Pack til Word, Excel og PowerPoint 2007 filformater Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f89a734-cda4-4abb-9a10-f6dfe560e8d0">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1 og Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 2</a>
                    <br />(KB982331)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office InfoPath 2003 Service Pack 3</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f79d376-0ea2-4218-9200-3c34c83ba336">Microsoft Office InfoPath 2003 Service Pack 3</a>
                    <br />(KB980923)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office InfoPath 2007 Service Pack 1 og Microsoft Office InfoPath 2007 Service Pack 2</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfa8765a-7970-4feb-996c-7c27d71c97c6">Microsoft Office InfoPath 2007 Service Pack 1 og Microsoft Office InfoPath 2007 Service Pack 2</a>
                    <br />(KB979441)<br />(Alvorlig)</td></tr>
                <tr><td>Microsoft Office SharePoint Server 2007 Service Pack 1 og Microsoft Office SharePoint Server 2007 Service Pack 2</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df">Microsoft Office SharePoint Server 2007 Service Pack 1 (32-bit-versioner)</a>
                    [1]
                    <br />(KB979445)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df">Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bit-versioner)</a>[1]<br />(KB979445)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90">Microsoft Office SharePoint Server 2007 Service Pack 1 (64-bit-versioner)</a>[1]<br />(KB979445)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90">Microsoft Office SharePoint Server 2007 Service Pack 2 (64-bit-versioner)</a>[1]<br />(KB979445)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til MS10-036**

\[1\]Ingen opdatering tilgængelig. Se bulletin for yderligere oplysninger.

\[2\]Ud over denne opdatering skal kunder også installere opdateringen til Microsoft Office 2003 Service Pack 3 (KB982311) for at være beskyttet mod den sårbarhed, der beskrives i denne bulletin.

\[3\]Ud over denne opdatering skal kunder også installere opdateringen til 2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2 (KB982312) for at være beskyttet mod den sårbarhed, der beskrives i denne bulletin.

**Bemærkning til MS10-038**

\[1\]Ud over denne opdatering skal kunder også installere sikkerhedsopdateringen til Microsoft Office Compatibility Pack til filformaterne Word, Excel og PowerPoint 2007 Service Pack 1 og Microsoft Office Compatibility Pack til filformaterne Word, Excel og PowerPoint 2007 Service Pack 2 (KB982308) for at være beskyttet mod sårbarhederne, der beskrives i denne bulletin.

**Bemærkninger til MS10-039**

\[1\]For understøttede versioner af Microsoft Office SharePoint Server 2007 skal brugerne ud over KB979445 installere sikkerhedsopdateringen til Microsoft Windows SharePoint Services 3.0 (KB983444) for at være beskyttet mod de sårbarheder, der beskrives i denne bulletin.

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Microsoft Server-software

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Windows SharePoint-services</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191905">
                      <strong>MS10-039</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Windows SharePoint Services 3.0 Service Pack 1 og Microsoft Windows SharePoint Services 3.0 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3841ceda-d0af-4e5e-8a1a-7dd954850783">Microsoft Windows SharePoint Services 3.0 Service Pack 1 og Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32-bit-versioner)</a>
                    <br />(KB983444)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94bc76d4-78e4-4bda-8922-36c3a9d3854f">Microsoft Windows SharePoint Services 3.0 Service Pack 1 og Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64-bit-versioner)</a><br />(KB983444)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til MS10-039**

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

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Microsoft Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

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

  - Sebastien Renaud fra [VUPEN Vulnerability Research Team](http://www.vupen.com/) for at rapportere et problem, der er beskrevet i MS10-032
  - [Secunia Research](http://secunia.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS10-032
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at rapportere et problem, der er beskrevet i MS10-033
  - Shaun Colley fra [NGSSoftware](http://www.ngssoftware.com/) for at have rapporteret et problem, der er beskrevet i MS10-034
  - Chris Ries fra Carnegie Mellon University Computing Services for at rapportere et problem, der er beskrevet i MS10-034
  - Chris Weber fra [Casaba Security](http://www.casabasecurity.com/) for at rapportere et problem beskrevet i MS10-035 og MS10-039
  - Takeshi Terada fra [Mitsui Bussan Secure Directions, Inc.](http://www.mbsd.jp/) for at rapportere et problem, der er beskrevet i MS10-035
  - Michal Zalewski fra [Google Inc.](http://www.google.com/) for at rapportere et problem, der er beskrevet i MS10-035
  - Chris Rohlf fra [Matasano Security](http://www.matasano.com/) for at have rapporteret to problemer, der er beskrevet i MS10-035
  - Peter Vreugdenhi, der samarbejder med [TippingPoint's](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS10-035
  - David Dewey fra [IBM ISS X-Force](http://www.iss.net/) og Ryan Smith fra [Accuvant](http://www.accuvant.com/), tidligere [VeriSign iDefense Labs](http://labs.idefense.com/), for at samarbejde med os om de ændringer ifm. de gennemgribende beskyttelsesforanstaltninger, der er inkluderet i MS10-036
  - Chris Carton fra Laserforce International, der samarbejder med [Secunia](http://secunia.com/), for at rapportere et problem, der er beskrevet i MS10-037
  - En anonym forsker, der samarbejder med [TippingPoint](http://www.tippingpoint.com/)s [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS10-038
  - Nicolas Joly fra [VUPEN Vulnerability Research Team](http://www.vupen.com/) for at rapportere otte problemer, der er beskrevet i MS10-038
  - Bing Liu fra [Fortinet's FortiGuard Labs](http://www.fortiguard.com/) for at have rapporteret et problem, der er beskrevet i MS10-038
  - Carsten Eiram fra [Secunia](http://secunia.com/) for at have rapporteret to problemer, der er beskrevet i MS10-038
  - En anonym forsker, der samarbejder med [TippingPoint](http://www.tippingpoint.com/)s [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS10-038
  - Rick Glaspie fra Gilbert Public Schools i Gilbert, AZ for at rapportere et problem, der er beskrevet i MS10-038
  - Rik Jones fra Dallas County Community College District for at rapportere et problem, der er beskrevet i MS10-039
  - Arian Evans fra [WhiteHat Security](http://www.whitehatsec.com) for at rapportere problemet med omgåelse af valideringsanmodning i ASP.NET, som behandles i MS10-041 ved hjælp af en ændring ifm. gennemgribende beskyttelsesforanstaltninger

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (8. juni 2010): Oversigt over bulletin offentliggjort.
  - V1.1 (9. juni 2010): Reviderede noterne til MS10-033 i afsnittet **Berørte programmer og downloadplaceringer**.
  - V2.0 (13. september 2011): Bulletinen MS10-035 er blevet genudsendt med henblik på igen at tilbyde opdateringen til Internet Explorer på Microsoft Windows 2000 og Windows XP for at afhjælpe et registreringsproblem. Der er ikke foretaget ændringer i sikkerhedsopdateringsfilerne. Kunder, der allerede har opdateret deres systemer uden problemer, behøver ikke at foretage sig noget.

*Built at 2014-04-18T01:50:00Z-07:00*

