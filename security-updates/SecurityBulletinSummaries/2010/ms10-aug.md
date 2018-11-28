---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for august 2010
TOCTitle: MS10-AUG
ms:assetid: ms10-aug
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms10-aug(v=Security.10)
ms:contentKeyID: 61224061
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for august 2010

Offentliggjort: 2. august 2010 | Opdateret: 10. august 2010

**Version:** 2.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for august 2010.

Med udgivelsen af bulletiner for august 2010 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 5. august 2010. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 11. august 2010 kl. 11:00 Pacific Time (USA og Canada). Tilmeld dig nu for at få [august måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454431&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

I forbindelse med den out-of-band-sikkerhedsbulletin, [MS10-046](http://go.microsoft.com/fwlink/?linkid=197393), der oprindeligt blev annonceret i version 1.0 af denne oversigt over bulletiner, har Microsoft udsendt en tilsvarende forhåndsmeddelelse om bulletiner den 30. juli 2010 og været vært for et bulletin-webcast den 2. august 2010. Adgang til dette [webcast den 2. august 2010](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032456779&culture=en-us) kan fås efter anmodning. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=197393">MS10-046</a></td>
<td><strong>En sårbarhed i Windows Shell kan give mulighed for fjernudførelse af kode (923191)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Windows Shell. Sårbarheden kan muliggøre fjernudførelse af kode, hvis ikonet for en særligt udformet genvej vises. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197104">MS10-049</a></td>
<td><strong>Sårbarheder i Schannel kan give mulighed for fjernudførelse af kode (980436)</strong><br />
<br />
Denne sikkerhedsopdatering løser én offentliggjort sårbarhed og én privat rapporteret sårbarhed i Secure Channel (Schannel)-sikkerhedspakken i Windows. De mere alvorlige af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger besøger et særligt udformet websted, der er beregnet til at udnytte sårbarhederne gennem en internetbrowser. En hacker kan dog aldrig tvinge brugere til at besøge disse websteder. I stedet er hackeren nødt til at overbevise brugerne om, at de skal besøge webstedet, typisk ved at få dem til at klikke på et link i en e-mail eller onlinebesked, som fører brugeren til hackerens websted.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196268">MS10-051</a></td>
<td><strong>Sårbarhed i Microsoft XML Core Services kan give mulighed for fjernudførelse af kode (2079403)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft XML Core Services. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet webside i Internet Explorer. En hacker kan ikke tvinge brugere til at besøge disse websteder. I stedet er hackeren nødt til at overtale brugerne til at besøge webstedet, typisk ved at få dem til at klikke på et link i en e-mail eller i en onlinemeddelelse, som fører brugerne til hackerens websted.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194432">MS10-052</a></td>
<td><strong>En sårbarhed i Microsoft MPEG Layer-3 Codecs kan muliggøre fjernudførelse af kode (2115168)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft MPEG Layer-3-lyd-codecs. Disse sårbarheder kan muliggøre fjernudførelse af kode, hvis en bruger åbner en særligt udformet mediefil eller modtager særligt udformet streamingindhold fra et websted eller et program, der leverer webindhold. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196549">MS10-053</a></td>
<td><strong>Samlet sikkerhedsopdatering til Internet Explorer (2183461)</strong><br />
<br />
Denne sikkerhedsopdatering løser seks privat rapporterede sårbarheder i Internet Explorer. De mest alvorlige sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside via Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190318">MS10-054</a></td>
<td><strong>Sårbarheder i SMB-serveren kan give mulighed for fjernudførelse af kode (982214)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i Microsoft Windows. De mest alvorlige af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en hacker har oprettet en særligt udformet SMB-pakke og sendt pakken til et påvirket system. De bedste fremgangsmåder for brug af firewall og standardkonfigurationer af firewall kan hjælpe med at beskytte netværk mod angreb, der kommer fra en placering uden for virksomhedsperimeteren, og som vil forsøge at udnytte disse sårbarheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194906">MS10-055</a></td>
<td><strong>En sårbarhed i Cinepak kan give mulighed for fjernudførelse af kode (982665)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Cinepak Codec. Disse sårbarheder kan muliggøre fjernudførelse af kode, hvis en bruger åbner en særligt udformet mediefil eller modtager særligt udformet streamingindhold fra et websted eller et program, der leverer webindhold. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196938">MS10-056</a></td>
<td><strong>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (2269638)</strong><br />
<br />
Denne kritiske sikkerhedsopdatering løser fire privat rapporterede sårbarheder i Microsoft Office. De mest alvorlige sårbarheder kan muliggøre fjernudførelse af kode, hvis en bruger åbner eller får vist en særligt udformet RTF e-mail-meddelelse. En hacker, som det lykkes at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=179830">MS10-060</a></td>
<td><strong>Sårbarheder i Microsoft .NET Common Language Runtime og Microsoft Silverlight kan muliggøre fjernudførelse af kode (2265906)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft .NET Framework og Microsoft Silverlight. Sårbarhederne kan muliggøre fjernudførelse af kode på et klientsystem, hvis en bruger får vist en særligt udformet webside ved brug af en webbrowser, der kører XAML Browser Applications (XBAP'er) eller Silverlight-programmer, eller hvis det lykkes en hacker at overtale en bruger til køre et særligt udformet Microsoft .NET-program. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Sårbarhederne kan derudover muliggøre fjernudførelse af kode på et serversystem, der kører IIS, hvis denne server giver mulighed for behandling af ASP.NET-sider, og det lykkes en hacker at uploade en særligt udformet ASP.NET-side til den pågældende server og køre den, som det f.eks. kan være tilfældet i et webhosting-scenarie.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows, Microsoft .NET Framework, Microsoft Silverlight</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=195812">MS10-047</a></td>
<td><strong>Sårbarheder i Windows Kernel kan give mulighed for udvidelse af rettigheder (981852)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i Microsoft Windows. De mest alvorlige af disse sårbarheder kan tillade en udvidelse af rettigheder, hvis en hacker er logget på lokalt og har kørt et særligt udformet program. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte disse sårbarheder. Sårbarhederne kan ikke udnyttes vha. fjernadgang eller af anonyme brugere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194552">MS10-048</a></td>
<td><strong>Sårbarheder i Windows-kernetilstandsdrivere kan give mulighed for udvidelse af rettigheder (2160329)</strong><br />
<br />
Denne sikkerhedsopdatering løser én offentliggjort sårbarhed og fire privat rapporterede sårbarheder i Windows-kernetilstandsdrivere. Den mest alvorlige af sårbarhederne kan muliggøre en udvidelse af rettigheder, hvis en hacker er logget på et berørt system og har kørt et særligt udformet program. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes via fjernadgang eller af anonyme brugere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197103">MS10-050</a></td>
<td><strong>En sårbarhed i Windows Movie Maker kan muliggøre fjernudførelse af kode (981997)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows Movie Maker. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en hacker sender en særligt udformet projektfil til Movie Maker og overtaler brugeren til at åbne den særligt udformede fil. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196275">MS10-057</a></td>
<td><strong>En sårbarhed i Microsoft Office Excel kan muliggøre fjernudførelse af kode (2269707)</strong> <br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Office. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Excel-fil. En hacker, som det lykkes for at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den bruger, der er logget på. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194562">MS10-058</a></td>
<td><strong>Sårbarheder i TCP/IP kan muliggøre udvidelse af rettigheder (978886)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Windows. De mere alvorlige af disse sårbarheder kan muliggøre udvidelse af rettigheder pga. en fejl i bearbejdningen af en bestemt input-buffer. En hacker, som er i stand til at logge på målsystemet, kan udnytte denne sårbarhed og køre arbitrær kode med adgangsrettigheder på systemniveau. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data eller oprette nye konti med komplette brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196444">MS10-059</a></td>
<td><strong>Sårbarheder i Tracing Feature for Services kan muliggøre en udvidelse af rettigheder (982799)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed og en privat rapporteret sårbarhed i Tracing Feature for Services. Sårbarhederne kan muliggøre udvidelse af rettigheder, hvis en bruger kører et særligt udformet program. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes via fjernadgang eller af anonyme brugere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=179830">MS10-060</a></td>
<td>Sårbarhed vedr. defekt Microsoft Silverlight-hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0019">CVE-2010-0019</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194432">MS10-052</a></td>
<td>Sårbarhed vedr. stakoverløb for MPEG Layer-3-lyddekoder</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1882">CVE-2010-1882</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=195812">MS10-047</a></td>
<td>Sårbarhed i Windows Kernel-datainitalisering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1888">CVE-2010-1888</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194562">MS10-058</a></td>
<td>Sårbarhed vedr. heltalsoverløb i Windows Networking</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1893">CVE-2010-1893</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194552">MS10-048</a></td>
<td>Sårbarhed vedr. håndtering af Win32k-undtagelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1894">CVE-2010-1894</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td><strong>Denne sårbarhed er blevet offentliggjort.</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194552">MS10-048</a></td>
<td>Sårbarhed vedr. Win32k-pooloverløb</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1895">CVE-2010-1895</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194552">MS10-048</a></td>
<td>Sårbarhed vedr. validering af Win32k-brugerinput</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1896">CVE-2010-1896</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194552">MS10-048</a></td>
<td>Sårbarhed vedr. vinduesoprettelse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1897">CVE-2010-1897</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=179830">MS10-060</a></td>
<td>Sårbarhed vedr. virtuel metodedelegering for Microsoft Silverlight og Microsoft .NET Framework CLR</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1898">CVE-2010-1898</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196938">MS10-056</a></td>
<td>Sårbarhed vedr. parsing af Word-registrering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1900">CVE-2010-1900</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196938">MS10-056</a></td>
<td>Sårbarhed vedr. defekt hukommelse for Word RTF-parsing</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1901">CVE-2010-1901</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194906">MS10-055</a></td>
<td>Sårbarhed vedr. dekomprimering af Cinepak-codec</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2553">CVE-2010-2553</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196444">MS10-059</a></td>
<td>Sårbarhed vedr. defekt sporing af hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2555">CVE-2010-2555</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196549">MS10-053</a></td>
<td>Sårbarhed vedr. defekt, ikke-initialiseret hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2557">CVE-2010-2557</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Denne sårbarhed kan med større sandsynlighed udnyttes på Internet Explorer 6 pga. manglende forebyggelse af dataudførelse som afhjælpning.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196549">MS10-053</a></td>
<td>Sårbarhed vedr. defekt hukommelse i HTML-layout</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2560">CVE-2010-2560</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196275">MS10-057</a></td>
<td>Sårbarhed vedr. defekt hukommelse i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2562">CVE-2010-2562</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197103">MS10-050</a></td>
<td>Sårbarhed vedr. defekt Movie Maker-hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2564">CVE-2010-2564</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197393">MS10-046</a></td>
<td>Sårbarhed vedr. indlæsning af genvejsikon</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0483">CVE-2010-2568</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=195812">MS10-047</a></td>
<td>Sårbarhed vedr. Windows Kernel Double Free</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1889">CVE-2010-1889</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196938">MS10-056</a></td>
<td>Sårbarhed vedr. bufferoverløb for Word RTF-parsing</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1902">CVE-2010-1902</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Windows Vista og Windows 7 er mindre sårbare overfor yderligere masseafhjælpningsmekanismer.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196938">MS10-056</a></td>
<td>Sårbarhed vedr. defekt hukommelse for HTML-linkede objekter i Word</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1903">CVE-2010-1903</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190318">MS10-054</a></td>
<td>Sårbarhed vedr. SMB-pooloverløb</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2550">CVE-2010-2550</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Udnyttelse ved med større sandsynlighed resultere i Denial-of-Service snarere end udførelse af kode.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196549">MS10-053</a></td>
<td>Sårbarhed vedr. defekt, ikke-initialiseret hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2556">CVE-2010-2556</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196549">MS10-053</a></td>
<td>Sårbarhed vedr. defekt race condition-hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2558">CVE-2010-2558</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196549">MS10-053</a></td>
<td>Sårbarhed vedr. defekt, ikke-initialiseret hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2559">CVE-2010-2559</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196268">MS10-051</a></td>
<td>Sårbarhed vedr. håndtering af hukommelse for Msxml2.XMLHTTP.3.0-respons</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0483">CVE-2010-2561</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197104">MS10-049</a></td>
<td>Sårbarhed vedr. forkert udformet SChannel-certifikat for udførelse af fjernkode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0483">CVE-2010-2566</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Udnyttelse kan med sandsynlighed resultere i Denial-of-Service. Fjernkodeudførelse er usandsynlig.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=197104">MS10-049</a></td>
<td>Sårbarhed vedr. TLS/SSL-regenerering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3555">CVE-2009-3555</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Dette er en spoofing-sårbarhed (forfalskning). Emnet er beskrevet i <a href="microsoft-security-advisory-977377.md">Microsoft Security Advisory 977377</a>.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=196549">MS10-053</a></td>
<td>Sårbarhed vedr. krydsdomæne for hændelseshåndtering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1258">CVE-2010-1258</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Dette er en sårbarhed i forbindelse med afsløring af oplysninger.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=194562">MS10-058</a></td>
<td>Sårbarhed vedr.defekt IPv6-hukommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1892">CVE-2010-1892</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Dette er en Denial of Service-sårbarhed.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190318">MS10-054</a></td>
<td>Sårbarhed vedr. SMB-validering af variabel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2551">CVE-2010-2551</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Dette er en Denial of Service-sårbarhed.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=190318">MS10-054</a></td>
<td>Sårbarhed vedr. SMB-stakudkommelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2552">CVE-2010-2552</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Dette er en Denial of Service-sårbarhed.</td>
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
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="14">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197393">
                      <strong>MS10-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197104">
                      <strong>MS10-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196268">
                      <strong>MS10-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194432">
                      <strong>MS10-052</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196549">
                      <strong>MS10-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=190318">
                      <strong>MS10-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194906">
                      <strong>MS10-055</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179830">
                      <strong>MS10-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=195812">
                      <strong>MS10-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194552">
                      <strong>MS10-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197103">
                      <strong>MS10-050</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194562">
                      <strong>MS10-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196444">
                      <strong>MS10-059</strong>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12361875-b453-45e8-852b-90f2727894fd">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ff00381c-e74b-48e5-9dd9-34dbedd906a2">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbdbbe5e-2ef9-4704-80c4-27ef28fd95ef">Microsoft XML Core Services 3.0</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08159149-17de-4640-8818-cb7bd4811531">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc949915-4e16-4897-a295-2f99102548ab">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b489f8c-ada0-4051-8284-0a941c04d2ed">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1662780f-370a-425b-9917-c601eb54a375">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e5e16f8-c140-4a1d-b898-8417a6bfd4d8">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ddb5e34-f97a-47c6-96c8-ba2ed06ccb77">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9">Microsoft .NET Framework 3.5</a>
                    <br />(KB983582)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983583) <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e3574047-5ce5-4461-94aa-4eb3258d5e71">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=deeac521-d3a2-4019-8176-c9228e733cf4">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b211664b-434d-4626-816f-c77510cfd44d">Movie Maker 2.1</a>
                    [1]
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b44bd67-48e2-497f-9165-42a702e2cc0d">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eaffa70c-6f2b-4e66-b1bc-64bdbbbcd34f">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d4e8eeb-a0b2-41c6-9ee4-3f4beb44195e">Microsoft XML Core Services 3.0</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7f28d7a-6b27-4059-865b-5fd55edb6299">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96b7a562-af16-4f0d-840c-838fb12e7419">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5296fb82-c446-4681-a9a0-0f80a2e248be">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8ae3978-bad6-4201-8357-2d212ab703ef">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd6cc359-e72e-46ec-a08b-763934e3e115">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/my%20documents/release/5cff5d6e-11a5-40ed-92ac-e12d287919e6">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9">Microsoft .NET Framework 3.5</a>
                    <br />(KB983582) <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983583) <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6c5455e-bc31-4842-aef4-ebff92324323">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=decb1fe6-adc8-44f7-89c5-f25767f0cefe">Movie Maker 2.1</a>
                    [1]
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="14">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197393">
                      <strong>MS10-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197104">
                      <strong>MS10-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196268">
                      <strong>MS10-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194432">
                      <strong>MS10-052</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196549">
                      <strong>MS10-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=190318">
                      <strong>MS10-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194906">
                      <strong>MS10-055</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179830">
                      <strong>MS10-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=195812">
                      <strong>MS10-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194552">
                      <strong>MS10-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197103">
                      <strong>MS10-050</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194562">
                      <strong>MS10-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196444">
                      <strong>MS10-059</strong>
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
                      <strong>Moderat</strong>
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
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=32fe91ef-5a8d-4095-90ee-2ca216696b09">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f76d68df-97e5-489c-a5f6-0c378c1f62ae">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31ce233e-4d2d-404b-84a8-683319ba8ef7">Microsoft XML Core Services 3.0</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9c2110ec-7e6c-4e73-9785-0a8196095ea0">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0370e1e-dedf-4fe8-a06c-0e0f0a674205">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8753ae27-60a4-475a-b8bc-6a7764480295">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=772e765d-0502-4b0b-bde8-d4f62b96db64">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=230e8559-e6df-49d5-acb5-b0cd4bde0bf4">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9">Microsoft .NET Framework 3.5</a>
                    <br />(KB983582) <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983583) <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59395f00-90f4-4b68-8dd3-03ff611c1bc8">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=923de214-c4fa-41e6-8307-2c5a37f13e8e">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4543bcf0-3505-407b-a5a9-6250ece6fbac">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d784b57-8564-4e7e-8f61-f897398e7ea5">Microsoft XML Core Services 3.0</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fdfad4ca-37c4-4ac5-bebc-a5ad61299503">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d92f5e69-43cf-4615-aa3b-41f9f40bb57b">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd3e9d06-1f8b-4ef7-84f6-61e85a1767b8">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=863edf45-0d3b-4408-a47c-258dc4a4fd94">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03804f59-748e-4832-98e4-2d88564bd10a">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9">Microsoft .NET Framework 3.5</a>
                    <br />(KB983582) <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983583) <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ef1c600-bb93-4800-81b8-8c64b369c194">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63aa5f8a-fe47-4892-b905-b54e4f3b6580">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ef992c3-96e9-4533-b844-07424a6054b3">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d87ac8b3-41fb-4cdd-b305-181a0024d85c">Microsoft XML Core Services 3.0</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=782e2963-4a52-4a1d-b99a-34ba841038a7">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e730064-8270-4d63-b497-c5ebeddea1fc">Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e4f4f8b3-7a39-4d77-a46b-02c86ad159c3">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9">Microsoft .NET Framework 3.5</a>
                    <br />(KB983582) <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983583) <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f96b8154-9976-41b0-b9d7-d79887fe9364">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="14">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197393">
                      <strong>MS10-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197104">
                      <strong>MS10-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196268">
                      <strong>MS10-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194432">
                      <strong>MS10-052</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196549">
                      <strong>MS10-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=190318">
                      <strong>MS10-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194906">
                      <strong>MS10-055</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179830">
                      <strong>MS10-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=195812">
                      <strong>MS10-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194552">
                      <strong>MS10-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197103">
                      <strong>MS10-050</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194562">
                      <strong>MS10-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196444">
                      <strong>MS10-059</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
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
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52748886-6280-4247-8cbd-f64db229ee66">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aca69406-f795-4398-968f-959fe3a74e89">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbfaadf8-ab38-456c-956a-ea18c64236c9">Microsoft XML Core Services 3.0</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=535c563e-cdac-4e3d-96b0-9947ea22deca">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2062566b-8b81-43c2-875d-9c06d4e3fa82">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9087a3aa-aa55-41f6-8c4c-f322e4aa8681">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60c81415-b61e-44a4-8dd9-cedec99eb70f">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>Kun Windows Vista Service Pack 1:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB983587)<br />(Kritisk)<br /><br />Kun Windows Vista Service Pack 1:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983588)<br />(Kritisk)<br /><br />Kun Windows Vista Service Pack 2:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983589) <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4486f97c-4cf8-4236-bfc3-b50e72e2a5c1">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9345207-7242-4b71-bf80-b52031e08f8c">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8aded9dd-08d6-4b19-955f-0d8414868cf9">Movie Maker 6.0</a>
                    [1]
                    <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1d8ed0d-a3b5-416a-ab8b-77501da62132">Movie Maker 2.6</a>[2]<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4684c4df-0a5c-4dba-82e5-059378737118">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dfb31aa2-7457-4581-9e28-7984a360edf4">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37648e95-05c2-4802-9a0f-660200baa229">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2835ed1-5ca6-4347-8ff1-e694b1ac49ff">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=577131cd-1229-4746-89d7-84d75f29e1f0">Microsoft XML Core Services 3.0</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd1185e3-ca22-4197-a53b-e7a2806ac352">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=65b04e29-8e39-46de-94e8-b653969b1ffd">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=10c9d5f1-53ed-459b-a663-e69bdb845a6b">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=469b732d-ca62-4a48-bb55-99f2ae4ddcf5">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>Kun Windows Vista x64 Edition Service Pack 1:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB983587)<br />(Kritisk)<br /><br />Kun Windows Vista x64 Edition Service Pack 1:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983588)<br />(Kritisk)<br /><br />Kun Windows Vista x64 Edition Service Pack 2:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983589) <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b547898e-f8a9-49dc-b49d-cffec5a001bc">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1620e7ac-3913-478d-8120-e9f46d98f453">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4baff9ae-dd25-4942-b45e-f281d0e1f4ac">Movie Maker 6.0</a>
                    [1]
                    <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a226592-8f98-4f67-ac60-1d00cbc56598">Movie Maker 2.6</a>[2]<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18152cd4-815f-425f-8694-fbabcbe80609">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=110f932f-d13c-4486-a295-e6068d5d8d7a">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="14">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197393">
                      <strong>MS10-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197104">
                      <strong>MS10-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196268">
                      <strong>MS10-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194432">
                      <strong>MS10-052</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196549">
                      <strong>MS10-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=190318">
                      <strong>MS10-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194906">
                      <strong>MS10-055</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179830">
                      <strong>MS10-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=195812">
                      <strong>MS10-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194552">
                      <strong>MS10-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197103">
                      <strong>MS10-050</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194562">
                      <strong>MS10-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196444">
                      <strong>MS10-059</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3aabd189-7d4c-4c9f-8854-f33127b1c309">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e0253d4-f0c0-4f28-ba08-6907c2fcb339">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73b5f45c-c9d6-491f-8483-98838b2a7c04">Microsoft XML Core Services 3,0</a>*<br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8239cb9e-bb5a-4157-8038-33d0b329eaee">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=409b9298-1e7d-48cf-9872-ffbdc56ebe53">Internet Explorer 8</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a94e2e38-116a-4b63-9328-6c33e63bbbfe">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>Kun Windows Server 2008 til 32 bit-systemer:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB983587) <br />(Kritisk)<br /><br />Kun Windows Server 2008 til 32 bit-systemer:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB983588) <br />(Kritisk)<br /><br />Kun Windows Server 2008 til 32-bit-systemer Service Pack 2:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB983589)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=611765ab-b3f3-45db-92b2-ee040b9cfd27">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8b1a3f7-7147-494e-bfc0-b1979b9578e6">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=844404be-f2e8-47bc-9650-9e2bbe383814">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9b3e60-e166-40c9-8938-3cba0a399c47">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29c6fc2d-d318-4a63-9ab2-82e84272aaf2">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>*<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a96891ff-8771-47b3-81bb-8640adb6c098">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43ece408-4aa7-4819-b3f6-7f0719ed3213">Microsoft XML Core Services 3,0</a>*<br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ef8abf0-c89e-4911-8d77-42400d9a398f">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b869bab-0797-4f83-8c64-23dda9983c8d">Internet Explorer 8</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=602dd3f6-0d09-4546-b1db-d7b6b04edb66">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>Kun Windows Server 2008 til x64-baserede systemer:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB983587)<br />(Kritisk)<br /><br />Kun Windows Server 2008 til x64-baserede systemer:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB983588) <br />(Kritisk)<br /><br />Kun Windows Server 2008 til x64-baserede systemer Service Pack 2:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB983589)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=131f3512-1585-462e-a4f1-3f359aac44bd">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1c25cb7-7e82-4c14-9666-aff52dd308b4">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08491c73-66b1-4c4c-8740-ea596a730fc1">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa84e547-2190-402f-9467-2450deeff565">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack </a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cfe227b5-6660-49f8-9d71-a997dd83de0b">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b16a422-0ee9-4eab-9cfe-e7688ffa0d76">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6faee94-e821-432d-bfa2-9008664566af">Microsoft XML Core Services 3.0</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f1eee63-2cca-4ec5-b196-36de3c0054cf">Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24d8f0a3-51a9-46c1-b870-a2239bf600e4">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Kun Windows Server 2008 til Itanium-baserede systemer:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB983587)<br />(Kritisk)<br /><br />Kun Windows Server 2008 til Itanium-baserede systemer:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=155bbb5c-247e-4bed-a287-527d978b7967">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983588) <br />(Kritisk)<br /><br />Kun Windows Server 2008 til Itanium-baserede systemer Service Pack 2:                 <br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB983589) <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=972efd3a-ec1e-49b2-835e-76f4b21b5b79">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45fe5135-aa89-4f60-8cdb-ec0edc9a7e77">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8aa12902-c234-4fd9-bba3-6767eafc38fc">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84f89dca-108c-4956-9aa2-866e17a872fc">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="14">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197393">
                      <strong>MS10-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197104">
                      <strong>MS10-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196268">
                      <strong>MS10-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194432">
                      <strong>MS10-052</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196549">
                      <strong>MS10-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=190318">
                      <strong>MS10-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194906">
                      <strong>MS10-055</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179830">
                      <strong>MS10-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=195812">
                      <strong>MS10-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194552">
                      <strong>MS10-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197103">
                      <strong>MS10-050</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194562">
                      <strong>MS10-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196444">
                      <strong>MS10-059</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 Beta til 32-bit-systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22e62b5c-e4c1-47d0-ae4a-8bd2d70d0a0a">Windows 7 til 32-bit-systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71716507-7080-4102-991e-6afc7cc377d5">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31d0f5ac-2cff-42a1-8f18-128bbfc4e57d">Microsoft XML Core Services 3.0</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ecaf42e0-a288-40c1-8602-21e967a87408">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8d58ebc4-a5f9-4318-a6f1-168c1bcdae3c">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e782ac9-b5d5-490e-a01a-7d4481eab224">Windows 7 til 32-bit-systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB983590) <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7d60864-5942-47ed-a6f3-1c07b4833a14">Windows 7 til 32-bit-systemer</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68bddf4b-b597-477e-80e4-9293d7160496">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a5a088e-644a-4a0e-9a09-0370bcd97688">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce6233f3-2ee5-4329-908d-ba9b28ecc553">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 til x64-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9499f771-c388-4de3-a5c7-8cc8b00b4395">Windows 7 til x64-baserede systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c457d8ec-83b7-446f-b77c-e47d4187e616">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a4f6d7c2-b475-4900-82f0-75f5be0b7b63">Microsoft XML Core Services 3.0</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ca57a47a-9111-4abe-9356-4962ca2c1d65">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad1ddf94-d714-4b36-8256-42bf79d03a90">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24751193-592f-4c44-a8d6-f4112d4f011b">Windows 7 til x64-baserede systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB983590) <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b00ec47c-402e-4207-a4c9-6c1900f254f8">Windows 7 til x64-baserede systemer</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ff09e03-d662-4b23-ab26-d25ca2ba58df">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=163fe2bd-f999-47c1-9a35-c4fc868bda51">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=146270fa-cd6f-440a-aa3e-e93af0bff447">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="14">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197393">
                      <strong>MS10-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197104">
                      <strong>MS10-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196268">
                      <strong>MS10-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194432">
                      <strong>MS10-052</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196549">
                      <strong>MS10-053</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=190318">
                      <strong>MS10-054</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194906">
                      <strong>MS10-055</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179830">
                      <strong>MS10-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=195812">
                      <strong>MS10-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194552">
                      <strong>MS10-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=197103">
                      <strong>MS10-050</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=194562">
                      <strong>MS10-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196444">
                      <strong>MS10-059</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td><td>
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
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 til x64-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d9dd09b-db40-462b-88b0-4dbb8180e81f">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9aeea25-ca14-4b42-9018-a27c9d8899c4">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a48cdac5-4d78-49b5-a6d8-ecf6c58cace2">Microsoft XML Core Services 3,0</a>*<br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7757bbc-3ef0-421d-ab57-0083a302c77b">Internet Explorer 8</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52642a8d-1081-4496-848e-9b03baf3fdac">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8">Microsoft .NET Framework 3.5.1</a>*<br />(KB983590) <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1ad1248-07f1-42d4-baa4-8a20837ec7b4">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6bbc9cb1-0b59-4473-adf9-2ce2f0f94c0a">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1f95600-34e5-44b3-b2cb-b2b2cbf645cb">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=333fb6e4-f867-4dcb-beb3-2d88e428ca2e">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce2bb5d4-f661-44e3-ac28-0b81f7b72670">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7c2e91f-ca8a-4237-99c8-ca53c91cf73e">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b4d3210e-f3ad-4dbb-9390-6e98eeb99eaa">Microsoft XML Core Services 3.0</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b457d04-03a9-4eb0-ba6a-ab45267e4f74">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=783fb42c-3698-4b1d-a692-3ff319578931">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77d0c428-237c-4dab-9645-6400dd9e65f8">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB983590) <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f23dec0f-a33b-4d8c-a86d-0e9368ae7ff5">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2543191a-09cb-4417-bbb2-aac4d9a2a756">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3cd7f2f-e198-4fbd-a65d-21a1bf51eb61">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62034ecb-a6bd-46c5-a03d-9642880bc2d6">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkninger til MS10-050**

\[1\]\]Disse versioner af Windows Movie Maker leveres sammen med de anførte operativsystemer.

\[2\]Windows Movie Maker 2.6 er en valgfri download, der kan installeres på de anførte operativsystemer.

**Bemærkning vedr. MS10-060**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Micorsoft Office-pakker og -programmer

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
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196938">
                      <strong>MS10-056</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196275">
                      <strong>MS10-057</strong>
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
                  </td></tr>
                <tr><td>Microsoft Office XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=978eb887-25b6-4dde-a2ec-d2d1e7f1a434">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB2251389)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=032e1530-8736-4e1c-a704-967679227619">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB2264397)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4360bcec-0731-4d4a-89eb-7d28a4607f06">Microsoft Office Word 2003 Service Pack 3</a>
                    <br />(KB2251399)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cecbce3-bbb7-47d1-bda3-64d7e0f69f62">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB2264403) <br />(Alvorlig)</td></tr>
                <tr><td>2007 Microsoft Office System Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d7210a3-662e-41e7-affc-ae94f9d89388">Microsoft Office Word 2007 Service Pack 2</a>
                    <br />(KB2251419)<br />(Kritisk)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Microsoft Office til Mac</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196938">
                      <strong>MS10-056</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196275">
                      <strong>MS10-057</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2004 til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2f44d4a-7cd8-4514-b3ff-1770bc47d595">Microsoft Office 2004 til Mac</a>
                    <br />(KB2284171)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2f44d4a-7cd8-4514-b3ff-1770bc47d595">Microsoft Office 2004 til Mac</a>
                    <br />(KB2284171) <br />(Alvorlig)</td></tr>
                <tr><td>Microsoft Office 2008 til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ece112f-0ca7-4b1f-ad20-603950edee66">Microsoft Office 2008 til Mac</a>
                    <br />(KB2284162) <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ece112f-0ca7-4b1f-ad20-603950edee66">Microsoft Office 2008 til Mac</a>
                    <br />(KB2284162) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Open XML File Format Converter til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7b834a3-5a44-42d4-afe9-6ef207333834">Open XML File Format Converter til Mac</a>
                    <br />(KB2284179) <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7b834a3-5a44-42d4-afe9-6ef207333834">Open XML File Format Converter til Mac</a>
                    <br />(KB2284179) <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3">Anden Office Software</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196938">
                      <strong>MS10-056</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=196275">
                      <strong>MS10-057</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Microsoft Office Word Viewer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39fe2229-9201-4270-bdc1-20bc8e30a766">Microsoft Office Word Viewer</a>
                    <br />(KB2251437)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Compatibility Pack til filformaterne Word, Excel og PowerPoint 2007 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed5b9671-651d-41f3-aed3-93ee8a28657f">Microsoft Office Compatibility Pack til filformaterne Word, Excel, og PowerPoint 2007 Service Pack 2</a>
                    <br />(KB2277947)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Works 9</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feb121ad-e5f6-40e2-bf12-045ae5c2a754">Microsoft Works 9</a>
                    <br />(KB2092914)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              </table>


#### Udviklingsværktøjer og software fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Silverlight</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179830">
                      <strong>MS10-060</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Silverlight 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/getsilverlight/get-started/install/default.aspx">Microsoft Silverlight 2</a>
                    [1] ved installation på Mac<br />(KB982926)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/getsilverlight/get-started/install/default.aspx">Microsoft Silverlight 2</a>[1] ved installation på alle udgaver af Microsoft Windows-klienter<br />(KB982926) <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/getsilverlight/get-started/install/default.aspx">Microsoft Silverlight 2</a>[1] ved installation på alle udgaver af Microsoft Windows-servere**<br />(KB982926) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Silverlight 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850">Microsoft Silverlight 3</a>
                    [1] ved installation på Mac<br />(KB978464)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850">Microsoft Silverlight 3</a>[2] ved installation på alle udgaver af Microsoft Windows-klienter<br />(KB978464)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850">Microsoft Silverlight 3</a>[2] ved installation på alle udgaver af Microsoft Windows-servere**<br />(KB978464)<br />(Kritisk)</td></tr>
              </table>


**Bemærkninger til MS10-060**

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

\[1\]Denne download opgraderer Microsoft Silverlight 2 til en nyere version, der ikke beskrevet i bulletinen.

\[2\]Denne download opgraderer Microsoft Silverlight til en nyere version, der ikke beskrevet i bulletinen.

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

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

Windows Server Update Services (WSUS) giver administratorer af informationsteknologi mulighed for at implementere de nyeste Microsoft-produktopdateringer for computere, der kører et Windows-operativsystem. Yderligere oplysninger, om hvordan du implementerer sikkerhedsopdateringer med Windows Server Update Services, finder du i TechNet-artiklen, [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).

**Systems Management Server**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere. Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig, se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Få mere at vide om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsoplysninger, på [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brugere kan også bruge SUIT (Security Update Inventory Tool) ved implementering af sikkerhedsopdateringer. Oplysninger om SMS findes på [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Bemærk** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til at installere disse opdateringer.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Opdateringer skriver ofte til de samme filer og registreringsdatabaseindstillinger, der er nødvendige for, at dine programmer kan køre. Dette kan udløse inkompatibilitet og forøge den tid, det tager at implementere sikkerhedsopdateringer. Du kan strømline test og validering af Windows-opdateringer mod installerede programmer med de [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponenter, der følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Microsoft Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede vigtige opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Opdateringer fra de foregående måneder for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Viser alle nye, reviderede og udgivne opdateringer til Microsoft-produkter udover Microsoft Windows.

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

  - Sergey I. Ulasen og Uleg Kopreev fra [VirusBlokAda](http://www.anti-virus.by/) for at rapportere et problem beskrevet i MS10-046
  - Andreas Marx og Maik Morgenstern fra [AV-Test](http://www.av-test.org/) for at rapportere et problem, der er beskrevet i MS10-046
  - Will Dormann fra [CERT/CC](http://www.cert.org) for at arbejde sammen med os om et problem, der er beskrevet i MS10-046
  - Niels Teusink for at arbejde sammen med os om et problem, der er beskrevet i MS10-046
  - Stefan Kanthak for at arbejde sammen med os om et problem, der er beskrevet i MS10-046
  - Tavis Ormandy fra [Google Inc.](http://www.google.com/) for at arbejde sammen med os om to problemer, der er beskrevet i MS10-047
  - Tavis Ormandy fra [Google Inc.](http://www.google.com/) for at rapporte et problem beskrevet i MS10-048
  - Matthieu Suiche fra [MoonSols](http://moonsols.com/) for at rapportere to emner, der er beskrevet i MS10-048
  - Matthieu Suiche fra [MoonSols](http://moonsols.com/) for samarbejde vedr. de omfattende ændringer som omtalt i MS10-048
  - Damián Frizza fra [Core Security Technologies](http://www.coresecurity.com/) for at rapportere et problem beskrevet i MS10-048
  - Marsh Ray og Steve Dispensa fra [PhoneFactor](http://www.phonefactor.com/) for at rapportere et problem beskrevet i MS10-049
  - Dyon Balding fra [Secunia](http://secunia.com/) for at rapportere et problem beskrevet i MS08-050
  - SkyLined fra [Google Inc.](http://www.google.com/) for at rapportere et problem beskrevet i MS09-051
  - Moritz Jodeit fra n.runs AG, der arbejder for [TippingPoints](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem beskrevet i MS10-052
  - Michal Zalewski fra [Google Inc.](http://www.google.com/) for at rapportere et problem beskrevet i MS10-053
  - Nicolas Joly fra [VUPEN Vulnerability Research Team](http://www.vupen.com) for at rapportere fire problemer, der er beskrevet i MS10-053
  - Gambino ZaDarkSide for at rapportere et problem beskrevet i MS10-053
  - Laurent Gaffié fra [stratsec](http://www.stratsec.net/), for at rapportere et problem beskrevet i MS10-054
  - Todd Wease og Richard Johnson fra [Sourcefire VRT](http://www.sourcefire.com/services/sf_vrt.html), for at rapportere et problem beskrevet i MS10-054
  - Riku Hietamaki og Joshua Morin fra [Codenomicon](http://www.codenomicon.com/), for at rapportere et problem beskrevet i MS10-054
  - En anonym forsker, der samarbejder med [TippingPoint](http://www.tippingpoint.com/)s [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem beskrevet i MS10-055
  - L.W.Z fra [team509](http://www.team509.com/), der samarbejder med [TippingPoints](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem beskrevet i MS10-056
  - Wushi fra [team509](http://www.team509.com/), der samarbejder med [VeriSign iDefense Labs](http://labs.idefense.com/), for at rapportere et problem beskrevet i MS10-056
  - [team509](http://www.team509.com/), der samarbejder med [VeriSign iDefense Labs](http://labs.idefense.com/), for at rapportere et problem beskrevet i MS10-056
  - Rodrigo Rubira Branco fra [Check Point](http://www.checkpoint.com/) IPS Research Team for at rapportere et problem beskrevet i MS10-056
  - Damián Frizza fra [Core Security Technologies](http://www.coresecurity.com/) for at rapportere et problem beskrevet i MS10-057
  - Darren Willis fra [Fourteenforty Research Institute, Inc.](http://www.fourteenforty.jp/) for at rapportere et problem beskrevet i MS10-058
  - Matthieu Suiche fra [MoonSols](http://moonsols.com/) for at rapportere et problem beskrevet i MS10-058
  - Cesar Cerrudo fra [Argeniss](http://www.argeniss.com/) for samarbejde om to problemer som beskrevet i MS10-059
  - Carsten Book fra for at rapportere et problem beskrevet i MS10-060
  - [Eamon Nerbonne](http://eamon.nerbonne.org/) for at rapportere et problem beskrevet i MS10-060

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (2. august 2010): Oversigt over bulletin offentliggjort.
  - V2.0 (10. august 2010): Tilføjede bulletinerne MS10-047 til MS10-060.

*Built at 2014-04-18T01:50:00Z-07:00*

