---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for oktober 2008
TOCTitle: MS08-OCT
ms:assetid: ms08-oct
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms08-oct(v=Security.10)
ms:contentKeyID: 61224046
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for oktober 2008

Offentliggjort: 14. oktober 2008 | Opdateret: 23. oktober 2008

**Version:** 3.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for oktober 2008.

Med udgivelsen af bulletiner for oktober 2008 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindelig blev offentliggjort den 9. oktober 2008. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 15. oktober 2008 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få oktober måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374639). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede vigtige opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

#### Resuméer

Denne måneds sikkerhedsbulletiner er opstillet efter vigtighed på følgende måde:

## Kritisk \[5\]

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS08-067</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=130719"><strong>En sårbarhed i Server-tjenesten kan muliggøre fjernudførelse af kode (958644)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Server-tjenesten. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger skulle modtage en særligt udformet RPC-anmodning på et berørt system. På systemerne Microsoft Windows 2000, Windows XP og Windows Server 2003 kan en hacker udnytte denne sårbarhed uden godkendelse til at køre arbitrær kode. Det er muligt, at denne sårbarhed kan bruges til at udforme en ormelignende udnyttelse. De bedste fremgangsmåder for brug af firewalls og standardkonfigurationer af firewalls kan hjælpe med at beskytte netværksressourcer mod angreb, der kommer fra en placering uden for virksomhedsperimeteren.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-060</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128125"><strong>En sårbarhed i Active Directory kan tillade fjernudførelse af kode (957280)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed ved implementeringer af Active Directory på Microsoft Windows 2000 Server. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en hacker får adgang til et berørt netværk. Denne sårbarhed berører kun Microsoft Windows 2000-servere, der er konfigureret som domænecontrollere. Hvis en Microsoft Windows 2000-server ikke er blevet opgraderet til domænecontroller, lytter den ikke til forespørgsler fra Lightweight Directory Access Protocol (LDAP) eller LDAP over SSL (LDAPS) og bliver ikke udsat for denne sårbarhed.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-058</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060"><strong>Samlet sikkerhedsopdatering til Internet Explorer (956390)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser fem privat rapporterede sårbarheder og én offentliggjort sårbarhed. Sårbarhederne kan muliggøre offentliggørelse af oplysninger eller fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows, Internet Explorer.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-059</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125712"><strong>En sårbarhed i Host Integration Server RPC Service kan tillade fjernudførelse af kode (956695)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Host Integration Server. Sårbarheden kan tillade fjernudførelse af kode, hvis en hacker sender en særligt udformet RPC-anmodning (Remote Procedure Call) til et berørt system. Kunder, der følger de bedste fremgangsmåder og konfigurerer SNA RPC-servicekontoen, så den har færre brugerrettigheder på systemet, berøres muligvis i mindre grad end kunder, der konfigurerer SNA RPC-servicekontoen til at have administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Host Integration Server.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-057</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653"><strong>Sårbarheder i Microsoft Excel kan give mulighed for fjernudførelse af kode (956416)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser tre privat rapporterede sårbarheder i Microsoft Office Excel, som kan muliggøre fjernudførelse af kode, når en bruger åbner en særligt udformet Excel-fil. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart af computeren.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Alvorlig (6)

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-066</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125709"><strong>En sårbarhed i Microsoft Ancillary Function Driver kan tillade udvidelse af rettigheder (956803)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Ancillary Function Driver. En lokal hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Udvidelse af rettigheder</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-061</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738"><strong>Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (954211)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en offentliggjort sårbarhed og to privat rapporterede sårbarheder i Windows kernel. En lokal acker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Sårbarhederne kan ikke udnyttes vha, fjernadgang eller af anonyme brugere.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Udvidelse af rettigheder</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-062</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120829"><strong>En sårbarhed i Windows Internet Printing Service kan tillade fjernudførelse af kode (953155)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne opdatering løser en privat rapporteret sårbarhed i Windows Internet Printing Service, som kan tillade fjernudførelse af kode. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-063</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=127994"><strong>En sårbarhed i SMB kan tillade fjernudførelse af kode (957095)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Server Message Block (SMB) Protocol. Sårbarheden kan tillade fjernudførelse af kode på en server, der deler filer eller mapper. En hacker, som har held til at udnytte disse sårbarheder, kan installere programmer, se, ændre eller slette data eller oprette nye konti med komplette brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-064</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128103"><strong>En sårbarhed i Virtual Address Descriptor Manipulation kan tillade udvidelse af rettigheder (956841)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Virtual Address Descriptor. Sårbarheden kan tillade udvidelse af rettigheder, hvis en bruger kører et særligt udformet program. En hacker, som har held til at udnytte denne sårbarhed, kan få udvidede rettigheder på et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data eller oprette nye konti med komplette administrative rettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Udvidelse af rettigheder</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-065</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128102"><strong>En sårbarhed i Message Queuing kan tillade fjernudførelse af kode (951071)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Message Queuing Service (MSMQ) på Microsoft Windows 2000-systemer. Sårbarheden kan tillade fjernudførelse af kode på Microsoft Windows 2000-systemer med aktiveret MSMQ-service.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Moderat (1)

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Microsoft Security Bulletin MS08-056</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128145"><strong>En sårbarhed i Microsoft Office kan tillade offentliggørelse af oplysninger (957699)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Office. Sårbarheden kan tillade offentliggørelse af oplysninger, hvis en bruger klikker på en særligt udformet CDO URL. En hacker, som har held til at udnytte denne sårbarhed, kan indsætte et client side script i brugerens browser, som kan efterligne indhold, offentliggøre oplysninger eller udføre en hvilken som helst handling, brugeren kan udføre på det berørte websted.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Offentliggørelse af oplysninger</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart af computeren.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at høre nærmere om sandsynligheden for at der udgives fungerende exploit-kode for hver af de sikkerhedsopdateringer, du skal installere. Du bør gennemse alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/en-us/security/cc998259,aspx).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=128145">MS08-056</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128145">En sårbarhed i Microsoft Office kan tillade offentliggørelse af oplysninger (957699)</a></td>
<td>CVE-2008-4020</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">2 - Inkonsekvent exploit-kode sandsynlig</a></td>
<td>Fungerende exploit-kode kan oprettes. Der er dog begrænset alvorlighed, da sårbarheden kun tillader spoofing i en dialogboks i specifikke webprogrammer. Det vil derfor kun få lidt opmærksomhed fra hackere.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">MS08-057</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">Sårbarheder i Microsoft Excel kan tillade fjernudførelse af kode (956416)</a></td>
<td>CVE-2008-4019</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">1 - Konsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">MS08-057</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">Sårbarheder i Microsoft Excel kan tillade fjernudførelse af kode (956416)</a></td>
<td>CVE-2008-3471</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">2 - Inkonsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">MS08-057</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124653">Sårbarheder i Microsoft Excel kan tillade fjernudførelse af kode (956416)</a></td>
<td>CVE-2008-3477</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">2 - Inkonsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Samlet sikkerhedsopdatering til Internet Explorer (956390)</a></td>
<td>CVE-2008-2947</td>
<td>(Offentliggjort ved bulletinudgivelse)</td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Samlet sikkerhedsopdatering til Internet Explorer (956390)</a></td>
<td>CVE-2008-3472</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">1 - Konsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Samlet sikkerhedsopdatering til Internet Explorer (956390)</a></td>
<td>CVE-2008-3473</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">1 - Konsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Samlet sikkerhedsopdatering til Internet Explorer (956390)</a></td>
<td>CVE-2008-3475</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">2 - Inkonsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Samlet sikkerhedsopdatering til Internet Explorer (956390)</a></td>
<td>CVE-2008-3474</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">3 - Fungerende exploit-kode usandsynlig</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128060">Samlet sikkerhedsopdatering til Internet Explorer (956390)</a></td>
<td>CVE-2008-3476</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">3 - Fungerende exploit-kode usandsynlig</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125712">MS08-059</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125712">En sårbarhed i Host Integration Server RPC Service kan tillade fjernudførelse af kode (956695)</a></td>
<td>CVE-2008-3466</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">1 - Konsekvent exploit-kode sandsynlig</a></td>
<td>Da det kun er særlige typer af virksomhedskunder, der vil installere Host Integration Server, er det sandsynligt, at der oprettes fungerende exploit-kode.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128125">MS08-060</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128125">En sårbarhed i Active Directory kan tillade fjernudførelse af kode (957280)</a></td>
<td>CVE-2008-4023</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">2 - Inkonsekvent exploit-kode sandsynlig</a></td>
<td>Udløsning af sårbarheden, så der forårsages en denial of service-tilstand, er sandsynlig. Det er dog svært at oprette fungerende exploit-kode for at udføre fjernudførelse af kode, da det ikke er muligt at kontrollere en nødvendig skrive-adresse.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">MS08-061</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (954211)</a></td>
<td>CVE-2008-2250</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">1 - Konsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">MS08-061</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (954211)</a></td>
<td>CVE-2008-2252</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">1 - Konsekvent exploit-kode sandsynlig</a></td>
<td>Det er mest sandsynligt at fungerende exploit oprettes for multiprocessor-systemer.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">MS08-061</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=121738">Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (954211)</a></td>
<td>CVE-2008-2251</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">3 - Fungerende exploit-kode usandsynlig</a></td>
<td>Det kan være muligt at udløse sårbarheden, men det er meget vanskeligt at oprette fungerende exploit-kode.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=120829">MS08-062</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120829">En sårbarhed i Windows Internet Printing Service kan tillade fjernudførelse af kode (953155)</a></td>
<td>CVE-2008-1446</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">1 - Konsekvent exploit-kode sandsynlig</a></td>
<td>Der er registreret konsekvent exploit-kode i begrænsede målrettede angreb. Internet Printing Protocol-tjenesten (IPP) aktiveres som standard, men adgang til denne tjeneste vha. IIS kræver også godkendelse som standard på alle platforme.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=127994">MS08-063</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=127994">En sårbarhed i SMB kan tillade fjernudførelse af kode (957095)</a></td>
<td>CVE-2008-4038</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">2 - Inkonsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128103">MS08-064</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128103">En sårbarhed i Virtual Address Descriptor Manipulation kan tillade udvidelse af rettigheder (956841)</a></td>
<td>CVE-2008-4036</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">2 - Inkonsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128102">MS08-065</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128102">En sårbarhed i Message Queuing kan tillade fjernudførelse af kode (951071)</a></td>
<td>CVE-2008-3479</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">3 - Fungerende exploit-kode usandsynlig</a></td>
<td>Offentliggørelse af oplysninger kan være mulig, men det er ikke altid muligt at opnå brugbart indhold fra hukommelsen. Ødelæggelse af hukommelse kan udløses, men det er vanskeligt at opnå fjerneudførelse af kode.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=125709">MS08-066</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=125709">En sårbarhed i Microsoft Ancillary Function Driver kan tillade udvidelse af rettigheder (956803)</a></td>
<td>CVE-2008-3464</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">1 - Konsekvent exploit-kode sandsynlig</a></td>
<td></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=130719">MS08-067</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=130719">En sårbarhed i Server-tjenesten kan muliggøre fjernudførelse af kode (958644)</a></td>
<td>CVE-2008-4250</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259,aspx">1 - Konsekvent exploit-kode sandsynlig</a></td>
<td>Der er registreret konsekvent exploit-kode i begrænsede målrettede angreb, som berører Windows XP. Denne tjeneste er aktiveret som standard på alle berørte platforme, men udnyttelse er mest sandsynlig på Microsoft Windows 2000, Windows XP og Windows Server 2003. På Windows Vista, Windows Server 2008 kræver disse platforme godkendelse, og selv efter en godkendelse er udnyttelse vanskeligere på grund af ASLR- og DEP-udvidelser.</td>
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
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="10">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
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
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e22eb3ae-1295-4fe2-9775-6f43c5c2aed3">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ed7bb9a-4b26-49d7-8c14-60226d2bc20d">Active Directory til Microsoft Windows 2000 Server Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=257c0478-56dd-42eb-a90e-607d01613db7">Microsoft Internet Explorer 5,01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=02390258-08e9-4b75-960d-be081b749558">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a6165a6-d7e7-4526-9291-290caf0639b4">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8163d1f6-feb5-4f39-8134-3ed42326b822">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ed29c3a-0682-4586-bbc2-a73deaa18e4c">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=899e2728-2433-4ccb-a195-05b5d65e5469">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td></tr>
              
                <tr><th colspan="10">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Bulletinklassifikation</strong>
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
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d5f9b6e-9265-44b9-a376-2067b73d6a03">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7f0f47b-b1ee-4516-9fbf-bf8e579963d0">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e73de2b-05e6-4901-9bac-46d8f469e635">Windows Internet Explorer 7</a><br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b16d9dac-c430-4dd8-a1e5-9a614801f1d9">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)<br /></td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7718bf14-c26c-43f3-be67-4c79ab5b2607">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)<br /></td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7ef571f-c9e8-4e14-95a3-3eeaec55b784">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)<br /></td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7e5981-6eef-4f08-86c0-c6a7607ea5d0">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)<br /></td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25997b73-a640-49c1-b19e-768a18bbe22c">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)<br /></td><td>Ikke relevant</td></tr>
                <tr><td>Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c16a372-7bf8-4571-b982-dac6b2992b25">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=234c05fb-988b-4e02-aab6-bb23e447df3d">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ccf7a3e3-ec30-4b95-9a86-00032301513c">Windows Internet Explorer 7</a><br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b607efc-c6fb-4079-8478-e4f3262386d3">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b06d3a02-b6e4-4d40-913a-3759a31f20f3">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ae4b913-bff0-4974-b198-828ca10d2a87">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e1675eb-6b06-48e9-9765-23a2c7737bdc">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50fae854-0bde-46f8-9444-b9e0d9bfecad">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="10">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Bulletinklassifikation</strong>
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
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f26d395d-2459-4e40-8c92-3de1c52c390d">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae8d22d5-20aa-471d-a423-f54c9d75febe">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feaf2adf-7892-4dbf-a147-db4d5dbe52f3">Windows Internet Explorer 7</a><br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee88ff2d-1b12-4f4c-a081-9f27a6fba074">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e696762-d652-4a8f-ab8f-622f9746c320">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=437a9b68-6a0c-48c8-9348-0d6fda48aa21">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbbebb3f-f1c7-402c-bd16-6f88da0d042c">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8ef3d5f-dd8e-4945-92cd-9d3e30b16667">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c04d2afb-f9d0-4e42-9e1f-4b944a2de400">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=07fc88c4-2571-4a4d-b573-ae576798ab4c">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=319dba34-07ca-47f9-a1e9-20df2df7966b">Windows Internet Explorer 7</a><br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab4d94d3-458c-4946-ab7f-03a279629d25">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57ca28ea-e5e1-4191-a3d6-84aa90a3d668">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3df6508-a568-449d-ac97-fbf3f97b98ef">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=989ac6f1-515c-467d-a200-2aabe66d9319">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2e754f9-086a-494c-bc19-5feed7df8b65">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab590756-f11f-43c9-9dcc-a85a43077acf">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b68937af-f04a-4d1e-9d7f-ec92af5194de">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47381d91-4a14-4a09-96b3-3345155df52d">Windows Internet Explorer 7</a><br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63234f85-6e5d-4ef6-b7cf-d1d2c78a5517">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e6c3f81-85bb-48e6-a5af-635a7e540c93">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=748f54f1-40b9-407c-9819-909061b53743">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91589cfb-15ba-4dd2-9e3b-107899fbcba6">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a3832ec-3f8f-42c1-a603-b1330d527547">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="10">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
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
                <tr><td>Windows Vista og Windows Vista Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18fdff67-c723-42bd-ac5c-cac7d8713b21">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4756e04b-6e1c-4d78-a3c0-17f6b4b97975">Windows Internet Explorer 7</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3483b400-cedc-441f-ba8e-594e3df89190">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b5995df-a3b8-4e81-b118-9bb057e19884">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Ingen alvorlighedsklassifikation)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72dd6015-25d1-45f4-a769-88ac43074b44">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b4212db5-093e-497d-b999-2e3780f9f7c2">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a976999d-264f-4e6a-9bd6-3ad9d214a4bd">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd19c72b-4f83-47ab-93be-d2c286e732c4">Windows Internet Explorer 7</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=905ab030-14a5-4a3d-aa11-e8f957f6a1ea">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4a0fcf4b-eb8e-456a-b934-400ae18248ee">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Ingen alvorlighedsklassifikation)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f793af16-5464-4db1-a42b-1c5f17c538ed">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c20808cb-c30a-4b53-91e5-810eb6b4b2e3">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="10">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
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
                <tr><td>Windows Server 2008 til 32 bit-systemer                    </td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25c17b07-1efe-43d7-9b01-3dfdf1ce0bd7">Windows Server 2008 til 32 bit-systemer</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec73f416-2204-42d6-8932-c96578ac819f">Windows Internet Explorer 7</a>**<br />(Lav)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b97114a-71aa-47a2-b9e7-f4e158c18c80">Windows Server 2008 til 32 bit-systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d6290d8-1745-4bc0-9ca9-eeb1ad0be4a5">Windows Server 2008 til 32 bit-systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf6744e6-b54c-40f6-a78d-7ba9453133c0">Windows Server 2008 til 32 bit-systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec9eeb82-0497-4c55-94bb-9a47cb3521b4">Windows Server 2008 til 32 bit-systemer</a>*<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til x64-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b12018e-0cc1-4136-a68c-be4e1633c8df">Windows Server 2008 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=baacd1c2-9764-4fea-bd4d-c49791974fef">Windows Internet Explorer 7</a>**<br />(Lav)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e641db2-90c8-458f-9795-3e46b70a5203">Windows Server 2008 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a33c833c-d5c5-4e37-8f89-7b9079f92e59">Windows Server 2008 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=223236e8-7b19-4b47-8a90-bfc35eb9318a">Windows Server 2008 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0bc178b8-f8ae-4f41-8f88-fb6a75be1bca">Windows Server 2008 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bcf89ef-6446-406c-9c53-222e0f0baf7a">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=250a45dd-7eae-4440-bd10-02a703940976">Windows Internet Explorer 7</a>
                    <br />(Lav)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6546e1c-bf7b-4354-8574-6c16fa707de0">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31783e88-76e2-4bc6-b4ae-308443c6d223">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Ingen alvorlighedsklassifikation)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=077b697c-04a0-45bd-b08c-331d5c30cb47">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0af72663-4945-4916-8c55-090ba4d82793">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Bulletinklassifikation</strong>
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
                <tr class="alternateRow"><td /><td /><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td /><td /><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows 7 Beta til Itanium-baserede systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66646156-f3e6-48d7-be22-de1772dd1884">Windows 7 Beta til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              </table>


**\*Windows Server 2008 - serverens hovedinstallation er berørt.** For understøttede udgaver af Windows Server 2008 gælder denne opdatering med den samme klassifikation, uanset om Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core eller ej. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Windows Server 2008 - serverens hovedinstallation er ikke berørt.** De sårbarheder, disse opdateringer drejer sig om, berører ikke understøttede udgaver af Windows Server 2008, hvis Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124653">
                      <strong>MS08-057</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128145">
                      <strong>MS08-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2740e0-ecdd-48ca-84e0-eb187c31eb16">Excel 2000 Service Pack 3</a>
                    <br />(KB955461)<br />(Kritisk)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27cedef1-c47c-472c-a343-cd9b4ebc2bba">Excel 2002 Service Pack 3</a>
                    <br />(KB955464)<br />(Alvorlig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1aee2d5-bfa0-40e3-91b6-98bf65524e8c">Microsoft Office XP Service Pack 3</a>
                    <br />(KB956464)<br />(Moderat)</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 2 og Microsoft Office 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368">Excel 2003 Service Pack 2</a>
                    <br />(KB955466)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368">Excel 2003 Service Pack 3</a><br />(KB955466)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System og 2007 Microsoft Office System Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f">Excel 2007</a>
                    <br />(KB955470)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f">Excel 2007 Service Pack 1</a><br />(KB955470)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Microsoft Office til Mac</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124653">
                      <strong>MS08-057</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128145">
                      <strong>MS08-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2004 til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba4fa21a-7e01-4ef8-9b9f-9d51d00ef094">Microsoft Office 2004 til Mac</a>
                    <br />(KB958312)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e70c5ae0-2858-46de-81f8-dcd1786656b7">Microsoft Office 2008 til Mac</a>
                    <br />(KB958267)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Open XML File Format Converter til Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a8d9a3b-b8a4-43b6-82a6-a2e7d16ae11d">Open XML File Format Converter til Mac</a>
                    <br />(KB958304)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Anden Office Software</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124653">
                      <strong>MS08-057</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128145">
                      <strong>MS08-056</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b">Microsoft Office Excel Viewer 2003</a>
                    <br />(KB955468)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b">Microsoft Office Excel Viewer 2003 Service Pack 3</a><br />(KB955468)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83c88444-75b8-44d1-b280-3671394ade45">Microsoft Office Excel Viewer</a><br />(KB955935)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater</a>
                    <br />(KB955936)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9">Microsoft Office Compatibility Pack til Word-, Excel- og PowerPoint 2007-filformater Service Pack 1</a><br />(KB955936)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535">Microsoft Office SharePoint Server 2007</a>*<br />(KB955937)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535">Microsoft Office SharePoint Server 2007 Service Pack 1</a>*<br />(KB955937)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f">Microsoft Office SharePoint Server 2007 x64 Edition</a>*<br />(KB955937)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f">Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1</a>*<br />(KB955937)<br />(Alvorlig)</td><td>Ikke relevant</td></tr>
              </table>


\*Denne opdatering gælder for servere, hvor Excel Services er installeret, f.eks. standardkonfigurationen af Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 For Internet Sites. Microsoft Office SharePoint Server 2007 Standard omfatter ikke Excel Services.

#### Microsoft Server-software

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Host Integration Server</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125712">
                      <strong>MS08-059</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Bulletinklassifikation</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Host Integration Server 2000</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11cca58b-59a4-4e93-9eb1-19b07c290a10">Microsoft Host Integration Server 2000 Service Pack 2 (Server)</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41b49291-1231-4e23-aef7-818207453d56">Microsoft Host Integration Server 2000 Administrator (Klient)</a><br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Host Integration Server 2004</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ca255ed-9334-4848-af94-49ef3078cdc0">Microsoft Host Integration Server 2004 (Server)</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eca756a1-ca56-4481-b23c-53c159a4e08c">Microsoft Host Integration Server 2004 Service Pack 1 (Server)</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92cb54e7-f4ff-40a4-99cb-6257c4d8d4cd">Microsoft Host Integration Server 2004 (klient)</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d776515c-09aa-4a04-876d-606bfc26a006">Microsoft Host Integration Server 2004 Service Pack 1 (Klient)</a><br />(Kritisk)</td></tr>
                <tr><td>Microsoft Host Integration Server 2006</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ae79da3-ec17-4d4b-8011-d777a237ac93">Microsoft Host Integration Server 2006 til 32-bit systemer</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05da4540-4976-458a-a612-7385d78695a2">Microsoft Host Integration Server 2006 til x64-baserede systemer</a><br />(Kritisk)</td></tr>
              </table>


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

Oplysninger om ikke-sikkerhedsrelaterede opdateringer til Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services for 2008. Omfatter alt Windows-indhold.
  - [Nye, reviderede og offentliggjorte opdateringer til Microsoft-produkter udover Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214,aspx).

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

  - [NetAgent Co., Ltd.](http://www.netagent.co.jp/) for at rapportere et problem beskrevet i MS08-056
  - Joshua J. Drake fra [iDefense](http://labs.idefense.com/) for at rapportere et problem beskrevet i MS08-057
  - Wushi, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative,](http://www.zerodayinitiative.com/) for at rapportere et problem beskrevet i MS08-057
  - Lionel d'Hauenens fra [Labo Skopia](http://www.laboskopia.com/), der samarbejder med [iDefense VCP](http://labs.idefense.com/), for at rapportere et problem beskrevet i MS08-057
  - David Bloom for at rapportere et problem beskrevet i MS08-058
  - Gregory Rubin for at rapportere et problem beskrevet i MS08-058
  - [Ivan Fratric](http://ifsec.blogspot.com/), der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem beskrevet i MS08-045
  - Thierry Zoller fra [n.runs](http://www.nruns.com/) for at rapportere et problem beskrevet i MS08-058
  - Lee Dagon fra [Composica](http://www.composica.com/) for at rapportere et problem beskrevet i MS08-058
  - Stephen Fewer fra [Harmony Security](http://www.harmonysecurity.com/), der arbejder sammen med [iDefense VCP](http://labs.idefense.com/), for at rapportere et problem beskrevet i MS08-059
  - Paul Miseiko fra [nCircle](http://www.ncircle.com/) for at rapportere et problem beskrevet i MS08-060
  - Paul Carton fra [iShadow](http://www.ishadow.com/) for at rapportere et problem beskrevet i MS08-061
  - Thomas Garnier fra [SkyRecon](http://www.skyrecon.com/) for at have rapporteret et problem beskrevet i MS08-061
  - [CERT/CC](http://www.cert.org/) for at have rapporteret et problem beskrevet i MS08-062
  - Joshua Morin fra [Codenomicon](http://www.codenomicon.com/) for at rapportere et problem beskrevet i MS08-063
  - Cody Pierce og Aaron Portnoy fra [TippingPoint DVLabs](http://dvlabs.tippingpoint.com) for at rapportere et problem, der er beskrevet i MS08-065
  - Fabien Le Mentec fra [SkyRecon](http://www.skyrecon.com/) for at rapportere et problem beskrevet i MS08-066

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis.
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (14. oktober 2008): Oversigt over bulletin offentliggjort.
  - V2.0 (15. oktober 2008): Fjernet klassifikationen for Windows Server 2008 for Itanium-baserede systemer (MS08-062).
  - V2.1 (16. oktober 2008): Opdaterede resuméet for Microsoft Security Bulletin MS08-062.
  - V3.0 (23. oktober 2008): Tilføjet sikkerhedsbulletin fra Microsoft MS08-067, En sårbarhed i Server-tjenesten kan muliggøre fjernudførelse af kode (958644).

*Built at 2014-04-18T01:50:00Z-07:00*

