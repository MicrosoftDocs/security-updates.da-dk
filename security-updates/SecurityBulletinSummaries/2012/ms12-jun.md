---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for juni 2012
TOCTitle: MS12-JUN
ms:assetid: ms12-jun
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms12-jun(v=Security.10)
ms:contentKeyID: 61224087
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for juni 2012

Offentliggjort: 12. juni 2012

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for juni 2012.

Med udgivelsen af sikkerhedsbulletiner for juni 2012 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 7. juni 2012. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål vedr. disse bulletiner den 13. juni 2012 kl. 11.00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få juni måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499671). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og webcasts](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=246927"><strong>MS12-036</strong></a></td>
<td><strong>Sårbarhed i Fjernskrivebord kan give mulighed for fjernudførelse af kode (2685939)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Remote Desktop Protocol. Sårbarheden kan tillade fjernudførelse af kode, hvis en hacker sender en serie af særligt udformede RDP-pakker til et berørt system. Remote Desktop Protocol (RDP) er som standard ikke aktiveret på noget Windows-operativsystem. Systemer, der ikke har RDP aktiveret, er ikke i risikogruppen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td><strong>Samlet sikkerhedsopdatering til Internet Explorer (2699988)</strong><br />
<br />
Denne sikkerhedsopdatering løser én offentliggjort sårbarhed og 12 privat rapporterede sårbarheder i Internet Explorer. De mest alvorlige sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside via Internet Explorer. En hacker, som det lykkes at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den nuværende bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251095"><strong>MS12-038</strong></a></td>
<td><strong>En sårbarhed i .NET Framework kan muliggøre fjernudførelse af kode (2706726)</strong><br />
<br />
Denne sikkerhedsopdatering løser én privat rapporteret sårbarhed i Microsoft NET Framework. Sårbarheden kan muliggøre fjernudførelse af kode på et klientsystem, hvis en bruger får vist en særligt udformet webside ved brug af en webbrowser, der kører XAML Browser Applications (XBAPs). Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Denne sårbarhed kan også bruges af Windows .NET-programmer til at omgå CAS-restriktioner (Code Access Security). I et webbrowsende angrebsscenarie kan hackeren hoste et websted, der indeholder en webside, som bruges til at udnytte denne sårbarhed. Dertil kommer, at kompromitterede websteder og websteder, der accepterer eller er vært for indhold leveret af brugerne eller reklamer, kan indeholde særligt udformet indhold, som kan udnytte sårbarheden. En hacker kan dog aldrig tvinge brugere til at besøge disse websteder. I stedet er hackeren nødt til at overtale brugerne til at besøge webstedet, typisk ved at få vedkommende at klikke på et link i en e-mail eller i en onlinemeddelelse, som fører brugerne til hackerens websted.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td><strong>Sårbarheder i</strong> <strong>Lync</strong> <strong>kan muliggøre fjernudførelse af kode (2707956)</strong><br />
<br />
Denne sikkerhedsopdatering løser én offentliggjort sårbarhed og tre privat rapporterede sårbarheder i Microsoft Lync. De mest alvorlige sårbarheder kan muliggøre fjernudførelse af kode, hvis en bruger får vist delt indhold, som indeholder særligt udformede TrueType-skrifttyper.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Lync</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251612"><strong>MS12-040</strong></a></td>
<td><strong>Sårbarhed i Microsoft Dynamics AX Enterprise Portal kan muliggøre udvidelse af rettigheder (2709100)</strong><br />
<br />
Denne sikkerhedsopdatering løser én privat rapporteret sårbarhed i Microsoft Dynamics AX Enterprise Portal. Sårbarheden kan muliggøre udvidelse af rettigheder, hvis en bruger klikker på en særligt udformet URL eller besøger et særligt udformet websted. I et scenarie med e-mail-angreb kan en hacker udnytte sårbarheden ved at sende en e-mail-meddelelse, som indeholder den særligt udformede URL, til brugeren af det udsatte Microsoft Dynamics AX Enterprise Portal-websted og ved at lokke brugeren til at klikke på den særligt udformede URL. Brugere af Internet Explorer 8 og Internet Explorer 9, som browser til et Microsoft Dynamics AX Enterprise Portal-websted i Internetzone, har nedsat risiko. Som standard forhindrer XSS-filteret i Internet Explorer 8 og Internet Explorer 9 dette angreb i Internetzone. XSS-filteret i Internet Explorer 8 og Internet Explorer 9 er som standard dog ikke aktiveret i intranetzonen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kan kræve genstart</td>
<td>Microsoft Dynamics AX</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td><strong>Sårbarheder i Windows-kernetilstandsdrivere kan muliggøre udvidelse af rettigheder (2709162)</strong><br />
<br />
Denne sikkerhedsopdatering løser fire privat rapporterede sårbarheder i Microsoft Windows. Sårbarhederne kan tillade udvidelse af rettigheder, hvis en hacker logger på et system og kører et særligt udformet program. En hacker skal have gyldige logon-oplysninger og kunne logge på lokalt for at udnytte nogen af disse sårbarheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td><strong>Sårbarheder i Windows Kernel kan muliggøre udvidelse af rettigheder (2711167)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed og én offentliggjort sårbarhed i Microsoft Windows. Sårbarhederne kan muliggøre udvidelse af rettigheder, hvis en hacker logger på et berørt system og har kørt et særligt udformet program, der udnytter sårbarheden. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes via fjernadgang eller af anonyme brugere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er opført i rækkefølge efter bulletin-id og derefter CVE-id. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at få kendskab til sandsynligheden for, at udførelse af kode og denial-of-service udnyttes inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Læs alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering af denne måneds opdateringer. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/security/cc998259.aspx).

I nedenstående artikelserier, refererer "Nyeste softwareversion" til den nyeste version af softwareemner, og "Ældre softwareversioner" refererer til alle ældre, understøttede versioner af softwareemner, der findes i "Berørte programmer" eller "Ikke-berørte programmer" i bulletin-tabellerne.

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Titel på sårbarhed</th>
<th>CVE ID</th>
<th>Vurdering af mulighed for udnyttelse i den nyeste softwareversion</th>
<th>Vurdering af mulighed for udnyttelse i ældre softwareversioner</th>
<th>Vurdering af mulighed for udnyttelse af Denial of Service</th>
<th>Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246927"><strong>MS12-036</strong></a></td>
<td>Sårbarhed vedr. Remote Desktop Protocol</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0173">CVE-2012-0173</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode i hovedelement</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1523">CVE-2012-1523</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed vedr. HTML-rensning</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td>Ikke relevant</td>
<td>Dette er en sårbarhed vedr. offentliggørelse af oplysninger <a href="http://go.microsoft.com/fwlink/?linkid=252488">MS12-039</a> afhjælper også denne sårbarhed.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed vedr. offentliggørelse af oplysninger i Null Byte</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1873">CVE-2012-1873</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td>Ikke relevant</td>
<td>Dette er en sårbarhed vedr. offentliggørelse af oplysninger</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode i værktøjslinjen Udviklere</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1874">CVE-2012-1874</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed vedrørende fjernudførelse af kode i forbindelse med samme id-egenskab</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1875">CVE-2012-1875</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>Microsoft er opmærksom på begrænsede angreb, som forsøger at udnytte sårbarheden.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode i Kol-element</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1876">CVE-2012-1876</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode i ændring af titelelement</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1877">CVE-2012-1877</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode ved OnBeforeDeactivate-hændelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1878">CVE-2012-1878</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode i insertAdjacentText</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1879">CVE-2012-1879</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode i insertRow</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1880">CVE-2012-1880</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sårbarhed i forbindelse med fjernudførelse af kode ved OnRowsInserted-hændelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1881">CVE-2012-1881</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251095"><strong>MS12-038</strong></a></td>
<td>Sårbarhed vedr. hukommelsesadgang for .NET Framework</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1855">CVE-2012-1855</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Sårbarhed vedr. OTF-parsing (TrueType Font)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td>Er ikke berørt</td>
<td>Permanent</td>
<td>Denne sårbarhed er blevet offentliggjort.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Sårbarhed vedr. OTF-parsing (TrueType Font)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159">CVE-2012-0159</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td>Er ikke berørt</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Sårbarhed vedrørende usikker indlæsning af Lync-bibliotek</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1849">CVE-2012-1849</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Er ikke berørt</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Sårbarhed vedr. HTML-rensning</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td>Ikke relevant</td>
<td>Dette er en sårbarhed vedr. offentliggørelse af oplysninger <a href="http://go.microsoft.com/fwlink/?linkid=249045">MS12-037</a> afhjælper også denne sårbarhed.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251612"><strong>MS12-040</strong></a></td>
<td>Sårbarhed vedrørende Dynamics AX Enterprise Portal XSS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1857">CVE-2012-1857</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Er ikke berørt</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sårbarhed vedrørende navnehåndtering af typen strengatom</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1864">CVE-2012-1864</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sårbarhed vedrørende navnehåndtering af typen strengatom</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1865">CVE-2012-1865</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sårbarhed vedrørende navnehåndtering for atom i Udklipsholder-format</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1866">CVE-2012-1866</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sårbarhed vedrørende heltalsoverløb i referencetallet for skifttyperessourcen</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1867">CVE-2012-1867</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sårbarhed vedrørende konkurrencetilstand i Win32k.sys</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1868">CVE-2012-1868</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td>Sårbarhed vedrørende defekt hukommelse i Planlægger til Brugertilstand</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0217">CVE-2012-0217</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Er ikke berørt</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td>Sårbarhed vedrørende defekt BIOS ROM</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1515">CVE-2012-1515</a></td>
<td>Er ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>Denne sårbarhed er blevet offentliggjort.</td>
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
                <tr><th colspan="6">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
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
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd2216eb-283b-4a23-b259-018a7fa5fe47">Windows XP Service Pack 3</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f222e05-2a8d-4099-851f-2044811f7425">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=07c75ac6-f92a-4204-aa58-bdf8c033df9e">Internet Explorer 7</a><br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5bc1656f-cf1d-4f77-a078-a8602401b8e1">Internet Explorer 8</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a399bd47-ffe1-4476-932c-9c119496222a">Windows XP Service Pack 3</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0efff733-4c8d-4fce-8de3-28465c6b762b">Windows XP Service Pack 3</a>
                    <br />(KB2707511) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e354955-32ae-447c-b16f-960acc01773b">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57e8bf9d-97c3-4166-a5d4-6b0c99afc6a1">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b35e90b-145d-44c2-a8bc-4f9108d46fa1">Internet Explorer 7</a><br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a386b16-74f7-4d36-93d0-75e7da9bf9b5">Internet Explorer 8</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bdb356db-bd36-4159-8e64-ecdb3dfc61bf">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                      <strong>Moderat</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e856fec-9f05-49b7-91b6-11c2636a2f1d">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1dcc826-7e96-464b-830e-39946e7802aa">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de828031-1ace-43df-80f2-db7d503fb0a2">Internet Explorer 7</a><br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e6e5589-b767-4e8a-b8b3-df7b97e002e5">Internet Explorer 8</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0b39b00-d7db-4008-8310-1258e84a72a2">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=855611a1-91ad-4d22-8c1c-fdcd6af4cef0">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2707511) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b63fa4d-b42e-43ca-9f2c-cf60c37731a5">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b060e03b-e63e-446b-9cfd-ea4e1e9383a6">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a36f7ffe-d537-4f9e-b676-22a24f50c089">Internet Explorer 7</a><br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1acb2f0-63ba-4524-94cf-42b3534e21e7">Internet Explorer 8</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk) <br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed7359ce-13e8-42b2-956d-e8be534583aa">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7dfdc5dc-54b0-49e3-bf5a-bbc40b0f159f">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=893667c4-ef9f-48d3-ab18-a0df51bd3dcc">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30a9d518-8067-44f4-90fd-09fec8a0c883">Internet Explorer 7</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2317c8d9-cae8-497b-952e-78eb4a6d585c">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
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
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f55b62bf-0571-4888-9061-3f7cc75d7f17">Windows Vista Service Pack 2</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16f4404e-e6d6-4bde-af15-3bb692412213">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=610e753a-21db-43e6-bc42-3e1227fa4bb1">Internet Explorer 8</a><br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=828fdb71-747b-481d-9683-895325331478">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9188f1eb-b568-4a99-9b39-745c760a693d">Windows Vista Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab06290c-4f57-4349-8abd-a382b9044631">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=993c5bc4-8903-4c8c-bbc9-da2e47d959f9">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87100a7e-7feb-4a18-b7aa-04fdd2d6ef52">Internet Explorer 8</a><br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b551d67-e0f1-498a-ac4f-06376a0fcf18">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b94ae42-2882-444c-ad5e-74e34b805006">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7f9ad40-d515-4224-90ff-4bd4bff9180f">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4eaeff8-7b7a-4418-a479-09b2146df2bf">Internet Explorer 8</a><br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a20c839c-ce3b-46a5-becb-588de404878d">Internet Explorer 9</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7420c9f3-8f7e-4823-aaba-b14b957408d8">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd5308b7-7430-4713-922c-f06c46886fad">Internet Explorer 8</a><br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a737d87-0689-470b-8fc0-8c874af18794">Internet Explorer 9</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4b8af1c-b483-4aed-9be5-b0f1698b2c28">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=472842c4-5fe7-4d4c-a927-05be030b5b4e">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=098607b3-9424-4440-8832-fc1de010977e">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                  </td></tr>
                <tr><td>Windows 7 til 32-bit-systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef">Windows 7 til 32-bit-systemer</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7">Windows 7 til 32-bit-systemer</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows 7 til 32-bit-systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef">Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7">Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows 7 til x64-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07">Windows 7 til x64-baserede systemer</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c">Windows 7 til x64-baserede systemer</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb">Windows 7 til x64-baserede systemer</a>
                    <br />(KB2709715) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 til x64-baserede systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07">Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c">Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb">Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2709715) <br />(Alvorlig) </td></tr>
              
                <tr><th colspan="6">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                      <strong>Moderat</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2008 R2 til x64-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 til x64-baserede systemer</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf">Internet Explorer 9</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 til x64-baserede systemer</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 til x64-baserede systemer</a>
                    <br />(KB2709715) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf">Internet Explorer 9</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2709715) <br />(Alvorlig)</td></tr>
                <tr><td>Windows Server 2008 R2 til Itanium-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc">Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c">Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Installationsindstillingen Server Core.</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 R2 til x64-baserede systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 til x64-baserede systemer</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 til x64-baserede systemer</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 til x64-baserede systemer</a>
                    <br />(KB2709715) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2709162) <br />(Alvorlig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2709715) <br />(Alvorlig)</td></tr>
              </table>


**Bemærkning** **til** **MS12-0** **3** **8**

\[1\] **.NET Framework 4 og .NET Framework 4 Client Profile er berørt.** The .NET Framework version 4 redistributable packages er tilgængelige i to profiler: .NET Framework 4 og .NET Framework 4 Client Profile. .NET Framework 4 Client Profile er et delområde af .NET Framework 4. Sårbarheden nævnt i denne opdatering berører både .NET Framework 4 og .NET Framework 4 Client Profile. For yderligere oplysninger skal du se MSDN-artiklen, [Installation af .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft kommunikationsplatforme og software

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Communicator</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252488">
                      <strong>MS12-039</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Communicator 2007 R2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75eea324-689a-4892-bdd9-03ef399c4cba">Microsoft Communicator 2007 R2</a>
                    <br />(KB2708980)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="2">Microsoft Lync</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252488">
                      <strong>MS12-039</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Lync 2010 (32-bit)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=425406ea-28b9-46f7-8c49-0c7ea46f16e3">Microsoft Lync 2010 (32-bit)</a>
                    <br />(KB2693282)<br />(Alvorlig)</td></tr>
                <tr><td>Microsoft Lync 2010 (64-bit)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06e5285f-1947-4409-b608-e0a145fadba4">Microsoft Lync 2010 (64-bit)</a>
                    <br />(KB2693282)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Lync 2010 Attendee</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c40f0d38-af90-4966-a0f0-346fa48683d0">Microsoft Lync 2010 Attendee</a>
                    <br />(installation på administratorniveau)<br />(KB2696031)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad864c0e-5850-44a3-b74f-5980a998a384">Microsoft Lync 2010 Attendee</a>[1]<br />(installation på brugerniveau)<br />(KB2693283)<br />(Alvorlig)</td></tr>
                <tr><td>Microsoft Lync 2010 Attendant (32-bit)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053">Microsoft Lync 2010 Attendant (32-bit)</a>
                    <br />(KB2702444)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Lync 2010 Attendant (64-bit)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053">Microsoft Lync 2010 Attendant (64-bit)</a>
                    <br />(KB2702444)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til MS12-0** **39**

\[1\]Denne opdatering er udelukkende tilgængelig fra Microsoft Download Center.

#### Microsoft ERP-løsninger (Enterprise Resource Planning)

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Dynamics ERP</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251612">
                      <strong>MS12-040</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Dynamics AX 2012 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45df362d-8fed-4d99-91c1-81c61878300a">Microsoft Dynamics AX 2012 Enterprise Portal</a>
                    [1]
                    <br />(KB2706738) <br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=780ddcef-19da-44c4-beca-d10b652cd22a">Microsoft Dynamics AX 2012 Enterprise Portal</a>[1]<br />(KB2710639) <br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41dc5958-c224-40f9-89c2-179607a8ee2a">Microsoft Dynamics AX 2012 Enterprise Portal</a>[1]<br />(KB2711239) <br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til MS12-040**

\[1\]Denne opdatering er udelukkende tilgængelig fra Microsoft Download Center og Microsoft Dynamics CustomerSource og Microsoft Dynamics PartnerSource.

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

**System** **Center Configuration Manager**

System Center Configuration Manager Software Update Management forenkler den komplekse opgave, det er at levere og administrere opdateringer af it-systemer på tværs af virksomheden. Med System Center Configuration Manager kan it-administratorer levere opdateringer af Microsoft-produkter til en række enheder, herunder stationære og bærbare computere, servere og mobile enheder.

Den automatiserede sårbarhedsvurdering i System Center Configuration Manager opdager behov for opdateringer og rapporterer om anbefalede forholdsregler. Software Update Management i System Center Configuration Manager er bygget på Microsoft Windows Software Update Services (WSUS), en gennemprøvet opdateringsinfrastruktur, der er kendt af it-administratorer verden over. Se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) for at få flere oplysninger om, hvordan administratorer kan bruge System Center Configuration Manager til at implementere opdateringer. Yderligere oplysninger om System Center Configuration Manager findes i [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere.

**Bemærk** System Management Server 2003 er uden for generel support fra den 12. januar 2010. Du kan få yderligere oplysninger om produktlivscyklussen på [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den næste version af SMS, System Center Configuration Manager, er nu tilgængelig; se det tidligere afsnit, **System Center Configuration Manager**.

Yderligere oplysninger om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsopdateringer, findes i [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Oplysninger om SMS findes på [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Bemærk\!** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til at installere disse opdateringer.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Opdateringer skriver ofte til de samme filer og registreringsdatabaseindstillinger, der er nødvendige for, at dine programmer kan køre. Dette kan udløse inkompatibilitet og forøge den tid, det tager at implementere sikkerhedsopdateringer. Du kan strømline test og validering af Windows-opdateringer mod installerede programmer med de [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponenter, der følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Opdateringer fra de foregående måneder for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Viser alle nye, reviderede og udgivne opdateringer til Microsoft-produkter udover Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

For at forbedre sikkerhedsbeskyttelsen for kunder giver Microsoft oplysninger om sårbarheder til store leverandører af sikkerhedssoftware før den månedlige udgivelse af sikkerhedsopdateringer. Derefter kan leverandører af sikkerhedssoftware bruge disse oplysninger om sårbarheder til at give opdateret beskyttelse til kunder via deres sikkerhedssoftware eller -enheder, f.eks. antivirus, registreringssystemer til netværksbaseret indtrængen eller forebyggelsessystemer til host-baseret indtrængen. For at afgøre om aktive beskyttelser er tilgængelige fra leverandører af sikkerhedssoftware, skal du gå ind på websteder med aktive beskyttelser, der udbydes af de programpartnere, som er angivet i [Microsoft Active Protections Program (MAPP) Partners](http://go.microsoft.com/fwlink/?linkid=215201).

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

  - En anonym forsker, der arbejder for [VeriSign iDefense Labs](http://labs.idefense.com/), for at have rapporteret et problem, der er beskrevet i MS12-037
  - Adi Cohen fra [IBM Security Systems - Application Security](http://blog.watchfire.com/) for at rapportere et problem, der er beskrevet i MS12-037
  - Masato Kinugawa for at have rapporteret et problem, der er beskrevet i MS12-037
  - Roman Shafigullin fra LinkedIn for at have rapporteret et problem, der er beskrevet i MS12-037
  - Code Audit Labs fra [VulnHunt](http://www.vulnhunt.com) for at have rapporteret et problem, der er beskrevet i MS12-037
  - Dark Son fra [VulnHunt](http://www.vulnhunt.com) for at have rapporteret et problem, der er beskrevet i MS12-037
  - [Qihoo 360 Security Center](http://www.360.cn/) for at arbejde sammen med os om et problem, der er beskrevet i MS12-037
  - Yichong Lin fra McAfee Labs for at arbejde sammen med os om et problem, der er beskrevet i MS12-037
  - [Google Inc.](http://www.google.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS12-037
  - [VUPEN Security](http://www.vupen.com), der arbejder sammen med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS12-037
  - En anonym forsker, der arbejder sammen med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS12-037
  - En anonym forsker, der arbejder sammen med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS12-037
  - En anonym forsker, der arbejder sammen med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS12-037
  - En anonym forsker, der arbejder sammen med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS12-037
  - En anonym forsker, der arbejder sammen med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS12-037
  - Vitaliy Toropov, der arbejder sammen med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS12-038
  - hamburgers maccoy via Secunia SVCRP for at have rapporteret et problem, der er beskrevet i MS12-039
  - Adi Cohen fra [IBM Security Systems - Application Security](http://blog.watchfire.com/) for at have rapporteret et problem, der er beskrevet i MS12-039
  - Alin Rad Pop, der arbejder sammen med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS12-039
  - Finian Mackin for at have rapporteret et problem, der er beskrevet i MS12-040
  - Tarjei Mandt fra [Azimuth Security](http://www.azimuthsecurity.com/) for at have rapporteret et problem, der er beskrevet i MS12-041
  - [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org) fra [Google Inc.](http://www.google.com) for at have rapporteret et problem, der er beskrevet i MS12-041
  - Rafal Wojtczuk fra [Bromium](http://www.bromium.com/) og Jan Beulich fra [SUSE](http://www.suse.com/) for at have rapporteret et problem, der er beskrevet i MS12-042

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
  - Sikkerhedsløsninger til professionelle it-fagfolk: [TechNet fejlfinding af og support til sikkerhedsproblemer](http://technet.microsoft.com/security/bb980617.aspx)
  - Vær med til at beskytte din Windows-computer mod virusser og malware: [Løsningscenter til virus og sikkerhed](http://support.microsoft.com/contactus/cu_sc_virsec_master)
  - Lokal support, landeafhængig: [International support](http://support.microsoft.com/common/international.aspx)

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (12. juni 2012): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

