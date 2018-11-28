---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for april 2008
TOCTitle: MS08-APR
ms:assetid: ms08-apr
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms08-apr(v=Security.10)
ms:contentKeyID: 61224036
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for april 2008

Offentliggjort: 8. april 2008 | Opdateret: 18. februar 2009

**Version:** 1.3

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for april 2008.

Med udgivelsen af bulletiner for april 2008 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 3. april 2008. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 9. april 2008 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få april måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357219&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede vigtige opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

#### Resuméer

Denne måneds sikkerhedsbulletiner er opstillet efter vigtighed på følgende måde:

## Kritisk \[5\]

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS08-018</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115454"><strong>En sårbarhed i Microsoft Project kan give mulighed for fjernudførelse af kode (950183)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Project, som kan muliggøre fjernudførelse af kode, når en bruger åbner en særligt udformet Project-fil. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
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


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS08-021</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>Sårbarheder i GDI kan give mulighed for fjernudførelse af kode (948590)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne vigtige sikkerhedsopdatering løser to privat rapporterede sårbarheder i GDI. Begge af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet EMF- eller WMF-billedfil. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder.</td>
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
<th>Sikkerhedsbulletin fra Microsoft MS08-022</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>En sårbarhed i VBScript og JScript Scripting Engines kan muliggøre fjernudførelse af kode (944338)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser en privat rapporteret sårbarhed i VBScript og JScript Scripting Engines i Windows. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder.</td>
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
<td><strong>Microsoft Windows. </strong>Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra MS08-023</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>Sikkerhedsopdatering af kill-bitter for ActiveX (948881)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser én privat rapporteret sårbarhed for et Microsoft-produkt. Denne opdatering indeholder også en kill-bit for produktet Yahoo! Music Jukebox. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
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
<td><strong>Microsoft Windows, Internet Explorer.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsift MS08-024</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>Samlet sikkerhedsopdatering til Internet Explorer (947864)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser én privat rapporteret sårbarhed. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
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


## Alvorlig \[3\]

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra MS08-020</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>En sårbarhed i DNS Client kan tillade spoofing (forfalskning) (945553)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed. Denne forfalskningssårbarhed findes i Windows DNS-servere og kan gøre det muligt for en hacker at sende særligt udformede svar på DNS-anmodninger og derved forfalske eller omdirigere internettrafik fra legitime steder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Spoofing (forfalskning)</td>
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
<th>Sikkerhedsbulletin fra MS08-025</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>En sårbarhed i Windows Kernel kan give mulighed for udvidelse af rettigheder (941693)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne vigtige sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows Kernel. En lokal hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti.</td>
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
<th>Sikkerhedsbulletin fra MS08-019</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115455"><strong>Sårbarheder i Microsoft Visio kan give mulighed for fjernudførelse af kode (949032)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser privat rapporterede sårbarheder i Microsoft Office Visio, som kan muliggøre fjernudførelse af kode, når en bruger åbner en særligt udformet Visio-fil. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
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
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart af computeren.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Microsoft Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Berørte programmer og downloadplaceringer

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at få kendskab til de sikkerhedsopdateringer, du muligvis skal installere. Du skal se alle de anførte softwareprogrammer eller komponenter igennem for at se, om der er behov for en sikkerhedsopdatering. Hvis et program eller en komponent findes på listen, findes der hyperlinks til tilgængelige softwareopdateringer, og sårbarhedens omfang også angivet.

**Bemærk\!** Du skal muligvis installere flere sikkerhedsopdateringer for en enkelt sårbarhed. Gennemse hele kolonnen for hvert bulletin-id på listen for at kontrollere, hvilke opdateringer du skal installere ud fra de programmer eller komponenter, der er installeret på dit system.

#### Windows-operativsystemet og dets komponenter

<table>
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletin-id</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Windows 2000 Service Pack 4</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=caac000a-22b6-48cb-aa00-1a0bfe886de2">Microsoft Windows 2000 Service Pack 4</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.1 og JScript 5.1</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0395451f-b719-4f71-a7b4-403d0c7e8fcc">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=ba6d3aeb-e35a-47cc-bace-7bd9d58a9d3f">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b051ae04-fe81-440d-9136-d6b239ca954e">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=75d2dc78-e3a4-4ff6-9e2d-bf1935003e8e">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=41326ade-96b6-47ce-9291-d4e3039471c4">Microsoft Windows 2000 Service Pack 4</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8db9f328-da0e-4fb8-96c4-6d368b47c224">Microsoft Windows 2000 Service Pack 4</a><br />
(Alvorlig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletin-id</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
</tr>
<tr class="odd">
<td>Windows XP Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c2763dd8-a03e-4a48-aa86-a7ec00250a7a">Windows XP Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c0124698-3b94-4474-9473-22a2f39a4a56">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9dbf002f-fe53-4cc7-a430-35f45c520d10">Windows XP Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=36c641ad-953f-4b09-ba1c-9c383295e180">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=e771efe8-8881-4f23-b5b0-15651a390ba9">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=893f4cef-0395-4c44-ba28-7a10b6e7dd48">Windows XP Service Pack 2</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0e937f65-abd0-46dd-8883-5bfd70ea1178">Windows XP Service Pack 2</a><br />
(Alvorlig)</td>
</tr>
<tr class="even">
<td>Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=166f2ab5-913c-47a9-86fe-b814797b751e">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=87b80ae3-e299-4d15-a135-3b1bcf943652">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=01400970-df68-4daf-aa39-2fc4f969974c">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=85beacc0-8ca2-4ded-9c24-23348d05c735">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=9364bf81-6505-4788-958d-a4bd29dc98ad">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8fdd1207-6e93-4c43-bacc-fe3623a6ebe7">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a29bbd13-761f-44fa-8948-e1a8c244bd7a">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />
(Alvorlig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletin-id</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bee91d80-d49a-4d3d-82d6-d5aa63f54979">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=88518aa6-e334-4529-aa63-0bf2ef417ce3">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ad384fea-53be-4be3-8acb-1cd23a7f5405">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />
(Moderat)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0444b76e-93fa-43c2-b1bc-a5c054529eb5">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=9acd2a03-5530-49c8-9ea1-0bfaf259700d">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=214bd8f5-6eb2-414c-b013-c516a306d692">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d3b855a6-4648-4771-826d-11a151828eac">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />
(Alvorlig)</td>
</tr>
<tr class="even">
<td>Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e3dde449-e062-4ce0-a9f4-433bff23e224">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=12cefefc-8553-4dca-9850-c653371de61e">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc5c893-cb24-4875-b0a7-6d5c7aa4d642">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Moderat)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5ebb5ef9-615f-4cab-bac5-6f45f1b94952">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a9e406aa-33e2-49b8-ab54-4a7328e46147">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fd123394-a5d6-4b55-be74-2938f52ce922">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=320fd100-35e1-4345-9399-796393235cbc">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Alvorlig)</td>
</tr>
<tr class="odd">
<td>Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7886a802-f2b5-489c-b14b-631f4c4c0742">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fe22a828-cca4-4b51-bbd5-995c65fead21">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=94cf78d3-b6c3-41bc-993e-3af3be0d70f1">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a><br />
(Moderat)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=63da8040-fda2-42c7-8543-26ad6f9811f2">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=75a05d3a-92a0-4a00-95d4-e2b2f6755180">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e0e63f03-904d-47ee-94fc-51a8dea668eb">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=126426a7-be38-4327-89db-02d99d76589d">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a><br />
(Alvorlig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Vista</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletin-id</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Vista og Windows Vista Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9b51deb8-3873-4146-977f-7e3d0840a4c5">Windows Vista og Windows Vista Service Pack 1</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d7f14001-7f42-4ca0-9193-cdf061179b59">Windows Vista og Windows Vista Service Pack 1</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d4e24966-6530-463a-9ee2-f6a9d000f998">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8203d303-c855-4579-9bbf-b06ddf5c1b87">Windows Vista</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9640cd8b-d749-4ddd-8af9-b298cebed969">Windows Vista og Windows Vista Service Pack 1</a><br />
(Alvorlig)</td>
</tr>
<tr class="even">
<td>Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4ad6dcd1-6ea5-43bf-8bee-a5f507beadc6">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d33462b6-7391-482d-babe-fb4cd0beaa21">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=295cf8f2-265e-4570-b708-21033337fe05">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=73f3a234-3973-4467-be7e-69efa7ee978c">Windows Vista x64 Edition</a><br />
(Alvorlig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d56bb4fe-304e-45e0-95f2-fde2f47b2a04">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />
(Alvorlig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Server 2008</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletin-id</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Server 2008 til 32 bit-systemer</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=006d5c47-53e6-4ee1-932c-497611804938">Windows Server 2008 til 32 bit-systemer</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=95691924-2813-4a86-9e11-99d853f8e606">Windows Server 2008 til 32 bit-systemer</a><br />
(Lav)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e57b4d94-19ad-4818-8311-a3f94be01a4b">Windows Internet Explorer 7</a>*<br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4497333c-9418-4b91-83dc-0155735421c0">Windows Server 2008 til 32 bit-systemer</a><br />
(Alvorlig)</td>
</tr>
<tr class="even">
<td>Windows Server 2008 til x64-baserede systemer</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8909f144-655b-4f07-916f-fd967f1efb2b">Windows Server 2008 til x64-baserede systemer</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=920ae29b-19d0-4089-ac79-f2da824a2256">Windows Server 2008 til x64-baserede systemer</a><br />
(Lav)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=93e9f52a-c7d0-4033-9c12-740665a219af">Windows Internet Explorer 7</a>*<br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5aefc7a6-79a4-45a2-b534-35d0ec400dda">Windows Server 2008 til x64-baserede systemer</a><br />
(Alvorlig)</td>
</tr>
<tr class="odd">
<td>Windows Server 2008 til Itanium-baserede systemer</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b7771a4a-4e4f-48d1-8551-bb8b778ca5a7">Windows Server 2008 for Itanium-baserede systemer</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=66df79ac-8364-4922-9688-ebc7ec76d89f">Windows Server 2008 for Itanium-baserede systemer</a><br />
(Lav)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=acf948e8-c4a9-40da-b282-f5e584e77b05">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3080c26b-7456-41ef-8668-28f15bc7b8ce">Windows Server 2008 for Itanium-baserede systemer</a><br />
(Alvorlig)</td>
</tr>
</tbody>
</table>


**\*\*Windows Server 2008-serverens hovedinstallation er ikke berørt.** De sårbarheder, der behandles i disse opdateringer, påvirker ikke understøttede versioner af Windows Server 2008, hvis Windows Server 2008 blev installeret vha. Server Core-installationsmuligheden – heller ikke selv om filer, der er berørt af disse sårbarheder, findes på systemet. Brugere med berørte filer vil dog stadig blive tilbudt denne opdatering, da opdateringsfilerne er nyere (med højere versionsnumre), end de filer, der aktuelt er på systemet. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Micorsoft Office-pakker og -programmer

<table>
<caption>Microsoft Project</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletin-id</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115454"><strong>MS08-018</strong></a></td>
</tr>
<tr class="even">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Project 2000 Service Release 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fbe46241-b9da-40c6-803d-42eb6234be77">Project 2000 Service Release 1</a><br />
(KB949043)<br />
(Kritisk)</td>
</tr>
<tr class="even">
<td>Microsoft Project 2002 Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=07a90718-6597-426d-9dca-a336d60c01b8">Project 2002 Service Pack 1</a><br />
(KB949005)<br />
(Alvorlig)</td>
</tr>
<tr class="odd">
<td>Microsoft Project 2003 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=aaba07d6-e972-4e85-bccd-406aa2c4a4f4">Project 2003 Service Pack 2</a><br />
(KB948962)<br />
(Alvorlig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Microsoft Visio</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletin-id</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115455"><strong>MS08-019</strong></a></td>
</tr>
<tr class="even">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Alvorlig</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Visio 2002 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0056a936-def5-40fa-bcfc-0ab0dd5c3964">Visio 2002 Service Pack 2</a><br />
(KB947896)<br />
(Alvorlig)</td>
</tr>
<tr class="even">
<td>Microsoft Visio 2003 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 2</a><br />
(KB947650)<br />
(Alvorlig)</td>
</tr>
<tr class="odd">
<td>Microsoft Visio 2003 Service Pack 3</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 3</a><br />
(KB947650)<br />
(Alvorlig)</td>
</tr>
<tr class="even">
<td>Microsoft Visio 2007</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007</a><br />
(KB947590)<br />
(Alvorlig)</td>
</tr>
<tr class="odd">
<td>Microsoft Visio 2007 Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007 Service Pack 1</a><br />
(KB947590)<br />
(Alvorlig)</td>
</tr>
</tbody>
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

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede vigtige opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede opdateringer til Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services for 2008. Omfatter alt Windows-indhold.
  - [Nye, reviderede og offentliggjorte opdateringer til Microsoft-produkter ud over Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

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

  - [National Cyber Security Center](http://www.ncsc.go.kr/eng/), Sydkorea, for at rapportere et problem, der er beskrevet i MS08-018
  - En anonym bruger for at rapportere et problem, der er beskrevet i MS08-019
  - En anonym bruger for at rapportere et problem, der er beskrevet i MS08-019
  - Amit Klein fra [Trusteer](http://www.trusteer.com/) for at have rapporteret et problem, der er beskrevet i MS08-020
  - Alla Berzroutchko fra [Scanit](http://www.scanit.be/) for at have rapporteret et problem, der er beskrevet i MS08-020
  - Roy Arends of [Nominet UK](http://www.nominet.org.uk/) for at rapportere et problem, der er beskrevet MS08-020
  - Greg MacManus fra [iDefense Labs](http://labs.idefense.com/) for at rapportere et problem, der er beskrevet i MS08-021.
  - Sebastian Apelt fra [Zero Day Initiative](http://www.zerodayinitiative.com/) for at rapportere et problem, der er beskrevet i MS08-021
  - Thomas Garnier fra [SkyRecon](http://www.skyrecon.com/) for at have rapporteret et problem, der er beskrevet i MS08-021
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at have rapporteret et problem, der er beskrevet i MS08-021
  - Peter Ferrie fra [Symantec](http://www.symantec.com/) for at have rapporteret et problem, der er beskrevet i MS08-022
  - En anonym forsker, der arbejder for [iDefense VCP](http://labs.idefense.com/vcp/), for at have rapporteret et problem, der er beskrevet i MS08-023.
  - Carsten Eiram fra [Secunia](http://secunia.com/) for at have rapporteret et problem, der er beskrevet i MS08-024.
  - Thomas Garnier fra [SkyRecon](http://www.skyrecon.com/) for at have rapporteret et problem, der er beskrevet i MS08-025

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis.
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (8. april 2008): Oversigt over bulletin offentliggjort.
  - V1.1 (9. april 2008): Resumé af sikkerhedsbulletin fra Microsoft MS08-018 er blevet opdateret.
  - V1.2 (16. april 2008): Finderoplysninger for MS08-021 er blevet opdateret, og oplysningerne om berørte programmer for Microsoft Office Suites og software er blevet præciseret.
  - V1.3 (18. februar 2009): Tilføjet uberørt hovedinstallationsnotation til Windows Server 2008 til 32-bit systemer og Windows Server 2008 til x64-baserede systemer til MS08-024.

*Built at 2014-04-18T01:50:00Z-07:00*

