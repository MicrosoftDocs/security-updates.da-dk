---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for juni 2009
TOCTitle: MS09-JUN
ms:assetid: ms09-jun
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms09-jun(v=Security.10)
ms:contentKeyID: 61224054
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for juni 2009

Offentliggjort: 9. juni 2009

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for juni 2009.

Med udgivelsen af sikkerhedsbulletiner for juni 2009 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 4. juni 2009. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 10. juni 2009 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få juni måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032395225). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=151361">MS09-018</a></td>
<td><strong>Sårbarheder i Active Directory kan tillade fjernudførelse af kode (971055)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder ved implementeringer af Active Directory på Microsoft Windows 2000 Server og Windows Server 2003 samt Active Directory Application Mode (ADAM), når det installeres på Windows XP Professional og Windows Server 2003. Den mest alvorlige sårbarhed kan muliggøre fjernudførelse af kode. En hacker, som har held til at udnytte denne sårbarhed, kan få fuldstændig fjernkontrol over det berørte system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. De bedste fremgangsmåder for brug af firewalls og standardkonfigurationer af firewalls kan hjælpe med at beskytte netværk mod angreb, der kommer fra en placering uden for virksomhedsperimeteren. De bedste fremgangsmåder anbefaler, at systemer med forbindelse til internettet har mindst mulig antal åbne porte.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141786">MS09-022</a></td>
<td><strong>Sårbarheder i Windows Print Spooler kan tillade fjernudførelse af kode (961501)</strong><br />
<br />
Denne kritiske sikkerhedsopdatering løser tre privat rapporterede sårbarheder i Windows Print Spooler. Den mest alvorlige sårbarhed kan muliggøre fjernudførelse af kode, hvis en berørt server har modtaget en særligt udformet RPC-anmodning. De bedste fremgangsmåder for brug af firewalls og standardkonfigurationer af firewalls kan hjælpe med at beskytte netværk mod angreb, der kommer fra en placering uden for virksomhedsperimeteren. De bedste fremgangsmåder anbefaler, at systemer med forbindelse til internettet har mindst mulig antal åbne porte.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td><strong>Samlet sikkerhedsopdatering til Internet Explorer (969897)</strong><br />
<br />
Denne kritiske sikkerhedsopdatering løser syv privat rapporterede sårbarheder og to offentliggjorte sårbarheder i Internet Explorer. De mest alvorlige sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147416">MS09-027</a></td>
<td><strong>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (969514)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder, som kan muliggøre fjernudførelse af kode, hvis en bruger åbner en særligt udformet Word-fil. En hacker, som har held til at udnytte en af disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td><strong>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (969462)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder, som kan muliggøre fjernudførelse af kode, når en bruger åbner en særligt udformet Excel-fil, der indeholder et forkert udformet registreringsobjekt. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128104">MS09-024</a></td>
<td><strong>En sårbarhed i Microsoft Works Converters kan tillade fjernudførelse af kode (957632)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Works-konverteringsprogrammerne. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Works-fil. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150174">MS09-026</a></td>
<td><strong>En sårbarhed i RPC kan muliggøre udvidelse af rettigheder (970238)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Windows Remote Procedure Call (RPC), hvor RPC Marshalling Engine ikke opdaterer sin interne tilstand korrekt. Sårbarheden kan gøre det muligt for en hacker at udføre arbitrær kode og få fuld kontrol over et berørt system. Understøttede versioner af Microsoft Windows leveres ikke med nogen RPC-servere eller -klienter, der udviser denne sårbarhed. Med en standardkonfiguration kan brugerne ikke udnyttes via denne sårbarhed. Sårbarheden er dog tilstedeværende i Microsoft Windows RPC Runtime og kan påvirke RPC-applikationer for tredjeparter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td><strong>Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (968537)</strong><br />
<br />
Denne sikkerhedsopdatering løser to offentliggjorte sårbarheder og to privat rapporterede sårbarheder i Windows Kernel, der kan give mulighed for udvidelse af rettigheder. En hacker, som har held til at udnytte disse sårbarheder, kan udføre arbitrær kode og få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte disse sårbarheder. Sårbarhederne kan ikke udnyttes vha, fjernadgang eller af anonyme brugere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150568">MS09-020</a></td>
<td><strong>Sårbarheder i Internet Information Services (IIS) kan give mulighed for udvidelse af rettigheder (970483)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed og en privat rapporteret sårbarhed i Microsoft Internet Information Services (IIS). Disse sårbarheder kan give mulighed for udvidelse af rettigheder, hvis en hacker sender en særligt udformet HTTP-forespørgsel til et websted, der kræver godkendelse. Disse sårbarheder gør det muligt for en hacker at komme uden om den IIS-konfiguration, der specificerer, hvilken type godkendelse der er tilladt, men ikke den filsystembaserede adgangskontrolliste (ACL), der bekræfter, om en fil er tilgængelig for en given bruger. Selvom det lykkes hackeren at udnytte disse sårbarheder, vil vedkommende stadig være begrænset til de tilladelser, der tildeles den anonyme brugerkonto af filsystemets ACL'er.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=143550">MS09-023</a></td>
<td><strong>En sårbarhed Windows Search kan give mulighed for offentliggørelse af oplysninger (963093)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Search. Sårbarheden kan muliggøre offentliggørelse af oplysninger, hvis en bruger udfører en søgning, der resulterer i en særligt udformet fil som det første resultat, eller hvis brugeren får vist en særligt udformet fil blandt søgeresultaterne. Som standard er komponenten Windows Search ikke forudinstalleret på Microsoft Windows XP og Windows Server 2003. Dette er en valgfri komponent, der kan downloades. Windows Search installeret på Windows Vista og Windows Server 2008 er ikke berørt af denne sårbarhed.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Offentliggørelse af oplysninger</td>
<td>Kræver genstart</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=151361">MS09-018</a></td>
<td>Sårbarheder i Active Directory kan tillade fjernudførelse af kode (971055)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1138">CVE-2009-1138</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Det er muligt at fjernudføre kode på Windows 2000-servere, som fremviser LDAP-tjenesten (standard tcp/389) på netværket.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=151361">MS09-018</a></td>
<td>Sårbarheder i Active Directory kan tillade fjernudførelse af kode (971055)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1139">CVE-2009-1139</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Sikkerhedseffekten af denne sårbarhed er en hukommelsesfejl, som i sidste ende kan føre til Denial of Service. Udførelse af kode er ikke mulig.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2007-3091">CVE-2007-3091</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1140">CVE-2009-1140</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Dette er en sårbarhed på tværs af domæner vedr. adgang til oplysninger, som sandsynligvis vil føre til offentliggørelse af oplysninger, ikke udførelse af kode.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1141">CVE-2009-1141</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1528">CVE-2009-1528</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1529">CVE-2009-1529</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1530">CVE-2009-1530</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1531">CVE-2009-1531</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Samlet sikkerhedsopdatering til Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1532">CVE-2009-1532</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150568">MS09-020</a></td>
<td>Sårbarheder i Internet Information Services (IIS) kan give mulighed for udvidelse af rettigheder (970483)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1122">CVE-2009-1122</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Lille sandsynlighed for udførelse af kode, men stor sandsynlighed for offentliggørelse af oplysninger pga. betingelserne for omgåelse af godkendelse.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150568">MS09-020</a></td>
<td>Sårbarheder i Internet Information Services (IIS) kan give mulighed for udvidelse af rettigheder (970483)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1535">CVE-2009-1535</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Offentliggjort kode er tilgængelig for offentliggørelse af oplysninger.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0549">CVE-2009-0549</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0557">CVE-2009-0557</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0558">CVE-2009-0558</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0559">CVE-2009-0559</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Kun Office 2000 er berørt af kodeudførelsestruslen. Det er usandsynligt, at angreb mod nyere versioner af Office vil resultere i udførelse af kode.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0560">CVE-2009-0560</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0561">CVE-2009-0561</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sårbarheder i Microsoft Office Excel kan muliggøre fjernudførelse af kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1134">CVE-2009-1134</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141786">MS09-022</a></td>
<td>Sårbarheder i Windows Print Spooler kan tillade fjernudførelse af kode (961501)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0228">CVE-2009-0228</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141786">MS09-022</a></td>
<td>Sårbarheder i Windows Print Spooler kan tillade fjernudførelse af kode (961501)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0229">CVE-2009-0229</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>Dette er en sårbarhed vedr. offentliggørelse af oplysninger, som ikke muliggør udførelse af kode.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141786">MS09-022</a></td>
<td>Sårbarheder i Windows Print Spooler kan tillade fjernudførelse af kode (961501)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0230">CVE-2009-0230</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=143550">MS09-023</a></td>
<td>En sårbarhed i Windows Search kan give mulighed for offentliggørelse af oplysninger (963093)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0239">CVE-2009-0239</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128104">MS09-024</a></td>
<td>En sårbarhed i Microsoft Works-konverteringsprogrammer kan tillade fjernudførelse af kode (957632)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1533">CVE-2009-1533</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td>Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (968537)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1123">CVE-2009-1123</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td>Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (968537)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1124">CVE-2009-1124</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td>Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (968537)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1125">CVE-2009-1125</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td>Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (968537)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1126">CVE-2009-1126</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td>Konsekvent exploit-kode er mest sandsynlig i forbindelse med Windows 2000. Sandsynligheden for udførelse af kode fra denne sårbarhed i forbindelse med stakbufferoverløb er mindre på Windows XP og Windows Server 2003 pga. /GS-beskyttelse.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150174">MS09-026</a></td>
<td>En sårbarhed i RPC kan muliggøre udvidelse af rettigheder (970238)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0568">CVE-2009-0568</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Microsofts programmer er ikke direkte berørt af denne sårbarhed. Arbejdsstationer, hvor der er implementeret RPC-tjenester fra uafhængige softwareleverandører, kan imidlertid være sårbare over for fjernudførelse af kode, hvis denne sikkerhedsopdatering ikke installeres.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147416">MS09-027</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (969514)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0563">CVE-2009-0563</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147416">MS09-027</a></td>
<td>Sårbarheder i Microsoft Office Word kan muliggøre fjernudførelse af kode (969514)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0565">CVE-2009-0565</a></td>
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
  </tr>
                <tr><th colspan="8">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                  </td><td>Ingen</td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bba6e20a-0345-46ae-a6f1-fd27fdee7c21">Active Directory til Microsoft Windows 2000 Server Service Pack 44</a>
                    <br />(KB969805)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=86378753-db24-44c2-a27d-cc0239f40ab8">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d645ad82-13c3-4030-808b-834e86ed3298">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe8b3796-a407-4f41-89eb-35b4bcc24ff6">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=155a79c1-e5e4-4f62-b4b0-53aca59f20ac">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79b0481d-a3d7-477b-928a-a98cc79374af">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8515a294-4f25-4dc5-860a-e7ad9b6c1c01">Microsoft Internet Information Services 5,0</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="8">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                      <strong>Moderat</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb2c9b76-0c65-4754-9941-d45a7c74a29a">Active Directory Application Mode (ADAM) på Windows XP Professional Service Pack 2 og Windows XP Professional Service Pack 3</a>
                    <br />(KB970437)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f2119aca-a98e-4810-be52-f38241443baf">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d7f63ee-d7c3-48a5-902e-60625405e97d">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=827b735c-660b-4723-b688-3297e107153a">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9e27ce1-4e7c-437f-9477-e7805a33da08">Windows Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f033fa78-c451-44f8-aa6c-a49622c37f40">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6349e046-a3f8-4ae5-b8c3-c9879cc99e8f">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=97da589f-4534-42f6-9f29-967b5a33c542">Microsoft Internet Information Services 5.1 til Windows XP Professional Service Pack 2 og Windows XP Professional Service Pack 3</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=759f22cb-ea7f-49dd-a200-19cb83fffd8d">Windows Search 4.0</a>
                    <br />(Moderat)</td></tr>
                <tr><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ef3aaf0-a2a9-4c17-99ab-a0dc3d3f7e86">Active Directory Application Mode (ADAM)</a>
                    <br />(KB970437)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22699d09-1e68-456a-8733-bfad6667ebf5">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=088f70eb-c5c5-426a-880a-18ed386d0b56">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5d2c81e-ffab-4e3b-a59a-a55000597213">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a24aedf0-7a31-4ee8-a9a6-998f1160c700">Windows Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20734b70-37f1-47dd-bc09-d56f93577a55">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3769800e-af93-4a44-8a1e-b30cc54b226f">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8982e6d2-e1f7-4208-88e3-80b159a8e21a">Microsoft Internet Information Services 6.0</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50c56dd6-c34d-4632-a779-8bcf8fdb341b">Windows Search 4.0</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="8">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                      <strong>Moderat</strong>
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
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d814ce65-a193-4027-a6cd-106d388830a6">Active Directory</a> <br />(KB969805)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6f99957-f74f-4446-8734-a468283eebae">Active Directory Application Mode (ADAM)</a> <br />(KB970437)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=865414f8-3f77-4fee-acc6-6684a3dc0aa4">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72a23752-86fb-4cc9-ab8e-63ffdfae5bec">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a980b867-c67f-4c61-b6db-e55c2ca68dc0">Windows Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=298143f2-f37a-4a2c-86ac-9804d4ff1dad">Windows Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62bb9e22-4f4b-4ffc-ba76-f626e94c79d5">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9356404c-d89a-4de0-b9b4-f6e1bdadf745">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bd4e410-dbd8-431a-b316-e1e2f1825c3a">Microsoft Internet Information Services 6.0</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e72ef31f-5161-4fe6-8ed3-6206e02cef31">Windows Search 4.0</a>
                    <br />(Moderat)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d1f23c8-06eb-4996-92eb-0eb635fd6a42">Active Directory</a>
                    <br />(KB969805)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a2badc7-c0a5-4032-a009-73ebe9d76313">Active Directory Application Mode (ADAM)</a><br />(KB970437)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=197a6cc7-4ba3-4d2e-b621-0ef3da645ef2">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a03d3c4-e39d-43a3-8d42-216e9551be96">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e7d6372-9c8c-449d-88fd-afd4f92ad9e6">Windows Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4a5401d7-ca97-4734-a0e9-d7ffe0777e34">Windows Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=888b8dd8-d76c-42f5-a377-1f1750d3cf56">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a3123af-173d-49eb-9997-14e82e764aee">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ea363223-535d-4142-9aba-3890960c6259">Microsoft Internet Information Services 6.0</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ffc3680-f9bf-423b-96a7-102f4cc9c240">Windows Search 4.0</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92e7808b-92ff-449d-bb73-ee8638e9ccd1">Active Directory</a>
                    <br />(KB969805)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=719efd62-fb33-447d-b6dd-2aaafbbad881">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58efde2c-e0b8-4259-b19e-80564b834882">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a2d2907e-67ae-44a4-a805-8670e659ea57">Windows Internet Explorer 7</a><br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3084f46e-02b9-4d99-a7a1-033817f9bd9f">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13b50993-410f-4e7a-a33a-6d9b48dbb4d1">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6b806eb-e2c4-4436-8964-720db593055d">Microsoft Internet Information Services 6.0</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="8">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                  </td><td>Ingen</td><td>Ingen</td></tr>
                <tr><td>Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ad8f037-2434-4dea-bfc3-9d3b4008b828">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e60215c3-b8b9-4e45-9d9f-b3fb0b47cce1">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f2730e9-b4fc-4f20-96cf-73f1be63f374">Windows Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ca227c0-f2dd-429c-a542-e08e93527214">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c31b36f8-330c-4a0c-9a3d-7cbe9a1ab8c8">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85c317cd-2a14-4747-9f50-3af3ddd3ae1b">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88185088-8c2c-4bc6-89b2-87f4d4849cf7">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5edb14f7-11ec-4180-9f0f-b2673f1c8d83">Windows Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=188adafe-1feb-46ad-b237-a88d35104dcd">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d70a65f-07ce-4992-8bec-28fefd7587bc">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="8">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                  </td><td>Ingen</td><td>Ingen</td></tr>
                <tr><td>Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f18356d-9f09-4d24-8361-970c0d1ccac4">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0e3f975-57da-43fa-ac12-3d14fd6ce939">Windows Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aaad301c-d232-4733-a0df-8e5d41bbfde8">Windows Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eaa26c6c-5bf7-4099-bb21-1e03de3a25ca">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98ba52b2-da1a-4939-a10e-d43b3a7e7ed4">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d0a6e8d-a31d-4f3d-a7d7-e61215bfebed">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=758edce7-2a82-4b2e-bd71-5b7075cc4b17">Windows Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faac92d4-4a2b-4bb5-8bd1-1519a9fa8147">Windows Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=447aaa4f-946b-4f23-b151-dcf46ea9f80e">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbaa5a72-c267-4907-a207-525c2803d7b9">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbac3deb-6c93-45aa-832c-02b915ac7f44">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67d4c189-030d-42eb-98b9-7957ccd92592">Windows Internet Explorer 7</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f33012b9-5d5b-4f72-8d49-a8e1c8bc1337">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0e3ad56-a363-44ba-af4d-b7f551c88afd">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              </table>


**Bemærkninger til Windows Server 2008**

**\*Windows Server 2008 - serverens hovedinstallation er berørt.** For understøttede udgaver af Windows Server 2008 gælder denne opdatering med den samme klassifikation, uanset om Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core eller ej. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 - serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008, hvis Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Micorsoft Office-pakker og -programmer

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
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147416">
                      <strong>MS09-027</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147294">
                      <strong>MS09-021</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128104">
                      <strong>MS09-024</strong>
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
                  </td></tr>
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3663e9f2-a952-4238-b902-90b5b09feb38">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB969600)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd16e243-b8e2-4afb-86b6-4d60214598eb">Microsoft Office Excel 2000 Service Pack 3</a>
                    <br />(KB969683)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4bf95806-3d32-411b-9779-a81aebad45e9">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB957838)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1323be1-15f2-491b-abae-c03ba1394398">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB969602)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd80ce95-0aec-4493-b9d1-c3dad95c3415">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB969680)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0ba8c9e-75ee-46bd-9e92-d4e6599309ad">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB957646)<br />(Alvorlig)</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cbc2587-2c8c-49b4-9f40-e4cdccb61ecd">Microsoft Office Word 2003 Service Pack 3</a>
                    <br />(KB969603)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=10156044-a5a4-4312-98a7-1b1ced625ddb">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB969681)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7ba3ea7-d06a-4c14-9107-9b92ef68fcae">Microsoft Office Word 2003 Service Pack 3 med Microsoft Works 6–9 File Converter</a>***<br />(KB968326)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e205108-4c28-4cab-a4d0-4ed3fd696473">Microsoft Office Excel 2007 Service Pack 1 og Microsoft Office Excel 2007 Service Pack 2</a>
                    <br />(KB969604)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bcd565a-6acb-407d-80da-0398526ddf99">icrosoft Office Excel 2007 Service Pack 1 og Microsoft Office Excel 2007 Service Pack 2</a>*<br />(KB969682)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd47e1e5-cd2e-4c08-9864-471e97f38ca3">Microsoft Office Word 2007 Service Pack 1</a>
                    <br />(KB969559)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="4">Microsoft Office til Mac</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147416">
                      <strong>MS09-027</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147294">
                      <strong>MS09-021</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128104">
                      <strong>MS09-024</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Microsoft Office 2004 til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550">Microsoft Office 2004 til Mac</a>
                    <br />(KB969661)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550">Microsoft Office 2004 til Mac</a>
                    <br />(KB969661)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58">Microsoft Office 2008 til Mac</a>
                    <br />(KB971822)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58">Microsoft Office 2008 til Mac</a>
                    <br />(KB971822)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Open XML File Format Converter til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6">Open XML File Format Converter til Mac</a>
                    <br />(KB971824)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6">Open XML File Format Converter til Mac</a>
                    <br />(KB971824)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="4">Anden Office Software</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147416">
                      <strong>MS09-027</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147294">
                      <strong>MS09-021</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128104">
                      <strong>MS09-024</strong>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20e6933d-85f8-4cec-9534-893789cd053e">Microsoft Office Excel Viewer 2003 Service Pack 3</a>
                    <br />(KB969685)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac0530dc-7f63-4ad0-85c1-784ad28156cf">Microsoft Office Excel Viewer</a><br />(KB969686)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Word Viewer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b">Microsoft Office Word Viewer 2003 Service Pack 3</a>
                    <br />(KB969614)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b">Microsoft Office Word Viewer</a><br />(KB969614)<br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63bd8f14-e736-46ce-af66-d30f17461e5a">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1 og Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack </a>
                    <br />(KB969613)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8be8457-b0b6-455e-907e-d13be883adf2">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1 og Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack </a>
                    <br />(KB969679)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Works 8.5</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=628280fe-e035-4274-85f2-393d9bad543c">Microsoft Works 8.5</a>
                    <br />(KB967043)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Works 9</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6fa110e-45c6-450f-ae47-c89a06e3f762">Microsoft Works 9</a>
                    <br />(KB967044)<br />(Alvorlig)</td></tr>
                <tr><td>Microsoft Office SharePoint Server</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=862e6ad1-8124-4060-93b1-2b882ef5ce3d">Microsoft Office SharePoint Server 2007 Service Pack 1 og Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bit-versioner)</a>**<br />(KB969737)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7b6e611-2c5d-4639-add9-972055789ecd">Microsoft Office SharePoint Server 2007 Service Pack 1 og Microsoft Office SharePoint Server 2007 Service Pack 2 (64-bit-versioner)</a>**<br />(KB969737)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              </table>


**Bemærkninger til MS09-021**

\*Til Microsoft Office PowerPoint 2007 Service Pack 1 og Microsoft Office PowerPoint 2007 Service Pack 2 skal brugerne ud over KB969682, installere sikkerhedsopdateringen til [Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1 og Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a8be8457-b0b6-455e-907e-d13be883adf2) (KB969679) for at være beskyttet mod de sårbarheder, der beskrives i denne bulletin.

\*Denne opdatering gælder for servere, hvor Excel Services er installeret, f.eks. standardkonfigurationen af Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 For Internet Sites. Microsoft Office SharePoint Server 2007 Standard omfatter ikke Excel Services.

**Bemærkning til MS09-024**

\*\*\*Microsoft Office Word 2003 påvirkes, hvis en sårbar Works Converter er installeret. Works Convertere er tilgængelige til Microsoft Office Word 2003 som en download fra [Microsoft Works 6–9 File Converter](http://www.microsoft.com/downloads/details.aspx?familyid=bf41401e-70fa-465d-ae2e-cf44dbf05297&displaylang=en).

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

  - Joshua J. Drake fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem beskrevet i MS09-018
  - Justin Wyatt fra [Beaverton School District](http://www.beaverton.k12.or.us/home/) for at rapportere et problem, der er beskrevet i MS09-018
  - David Bloom fra [Google Inc.](http://www.google.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS09-019
  - Jorge Luis Alvarez Medina fra [Core Security Technologies](http://www.coresecurity.com/) for at rapportere et problem, der er beskrevet i MS09-019
  - Bing Liu fra [Fortinet](http://www.fortinet.com/) for at rapportere et problem, der er beskrevet i MS09-019
  - [Tippingpoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at have rapporteret et problem beskrevet i MS09-019
  - Peter Vreugdenhi, der arbejder for [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS09-0199
  - Wushi, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere to problemer beskrevet i MS09-019
  - Wushi, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative,](http://www.zerodayinitiative.com/) for at rapportere et problem beskrevet i MS09-019
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at have rapporteret et problem, der er beskrevet i MS09-020
  - Bing Liu hos Fortinets [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) for at have rapporteret tre problemer i MS09-021
  - Carsten H. Eiram fra [Secunia](http://secunia.com/) for at have rapporteret to problemer, der er beskrevet i MS09-021
  - [TELUS Security Labs Vulnerability Research Team](http://telussecuritylabs.com/) for at have rapporteret et problem, der er beskrevet i MS09-021
  - Sean Larsson og JJoshua Drake fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem, der er beskrevet i MS09-021
  - [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at have rapporteret et problem beskrevet i MS09-021
  - Jun Mao fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret et problem, der er beskrevet i MS09-022
  - Yair Amit fra [IBM Rational Application Security](http://blog.watchfire.com/) for at have rapporteret et problem, der er beskrevet i MS09-023
  - Shaun Colley of [NGS Software](http://www.ngssoftware.com/) for at have rapporteret et problem, der er beskrevet i MS09-024
  - Thomas Garnier for at have rapporteret to problemer, der er beskrevet i MS09-025
  - Wushi fra [team509](http://www.team509.com/), der arbejder sammen med [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS09-027
  - Nicolas Joly fra [VUPEN Security](http://www.vupen.com/), for at have rapporteret et problem, der er beskrevet i MS09-027

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (9. juni 2009): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

