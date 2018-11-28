---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for oktober 2007
TOCTitle: MS07-OCT
ms:assetid: ms07-oct
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms07-oct(v=Security.10)
ms:contentKeyID: 61224034
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for oktober 2007

Offentliggjort: 9. oktober 2007

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for oktober 2007.

Med udgivelsen af bulletiner for oktober 2007 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindelig blev offentliggjort den 4. oktober 2007. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 10. oktober 2007 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få oktober måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344692&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede vigtige opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

#### Resuméer

Denne måneds sikkerhedsbulletiner er opstillet efter vigtighed på følgende måde:

## Kritisk (4)

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-055</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94668"><strong>Sårbarhed i Kodak Image Viewer kan muliggøre fjernudførelse af kode (923810)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser en privat rapporteret sårbarhed. Der findes en sårbarhed, som kan tillade fjernudførelse af kode, i den måde, som Kodak Image Viewer (tidligere Wang Image Viewer) håndterer særligt udformede billedfiler på. Sårbarheden kan gøre det muligt for en hacker at foretage fjernudførelse af kode på det berørte system. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
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
<td><strong>Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-056</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=96629"><strong>Sikkerhedsopdatering til Outlook Express og Windows Mail (941202)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser én privat rapporteret sårbarhed. Sårbarheden kan tillade fjernudførelse af kode på grund af et forkert håndteret forkert udformet NNTP-svar. En hacker kan udnytte sårbarheden ved at oprette en særligt udformet webside.</td>
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
<td>Microsoft Baseline Security Analyzer og Enterprise Update Scan Tool kan fastslå, om din computer skal bruge denne opdatering. Opdateringen kræver ikke genstart, med undtagelse af bestemte situationer samt for Windows Vista.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Windows, Outlook Express, Windows Mail.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-057</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=95045"><strong>Samlet sikkerhedsopdatering til Internet Explorer (939653)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser tre privat rapporterede sårbarheder og én offentliggjort sårbarhed. Sårbarheden med de mest alvorlige sikkerhedskonsekvenser kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
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
<td><strong>Windows, Internet Explorer.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-060</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=101656"><strong>En sårbarhed i Microsoft Word kan muliggøre fjernudførelse af kode (942695)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Word, der kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Word-fil med en forkert udformet streng. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
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
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Alvorlig \[2\]

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-058</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91031"><strong>Sårbarhed i RPC kan give mulighed for Denial-of-Service (933729)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne vigtige opdatering løser en privat rapporteret sårbarhed. Der findes en Denial-Of-Service-sårbarhed i RPC-funktionaliteten (remote procedure call) på grund af en fejl ved kommunikation med NTLM-sikkerhedsprovideren, når der udføres godkendelse af RPC-anmodninger.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Denial-of-Service</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-059</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=95631"><strong>Sårbarhed i Windows SharePoint Services 3.0 og Office SharePoint Server 2007 kan medføre en udvidelse af rettigheder inden for SharePoint-stedet (942017)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser en offentligt rapporteret sårbarhed i Microsoft Windows SharePoint Services 3.0 og Microsoft Office SharePoint Server 2007. Sårbarheden kan gøre det muligt for en hacker at køre et vilkårligt script, der kan medføre en udvidelse af rettigheder inden for SharePoint-stedet til forskel fra en udvidelse af rettigheder inden for arbejdsstations- eller servermiljøet. Sårbarheden kan også gøre det muligt for en hacker at køre et vilkårligt script for at ændre en brugers cache, hvilket medfører offentliggørelse af oplysninger på arbejdsstationen.</td>
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
<td>Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver ikke genstart, med undtagelse af bestemte situationer.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Windows, Office.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Berørte programmer og downloadplaceringer

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at få kendskab til de sikkerhedsopdateringer, du muligvis skal installere. Du skal se alle de anførte softwareprogrammer eller komponenter igennem for at se, om der er behov for en sikkerhedsopdatering. Hvis et program eller en komponent findes på listen, er sårbarhedens omfang også angivet, og der findes hyperlinks til tilgængelige softwareopdateringer.

**Bemærk\!** Du skal muligvis installere flere sikkerhedsopdateringer for en enkelt sårbarhed. Gennemse hele kolonnen for hvert bulletin-id på listen for at kontrollere, hvilke opdateringer du skal installere ud fra de programmer eller komponenter, der er installeret på dit system.

**Berørte programmer og downloadplaceringer**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Oplysninger        </th>
    <th>Oplysninger        </th>
    <th>Oplysninger        </th>
    <th>Oplysninger        </th>
    <th>Oplysninger        </th>
    <th>Oplysninger        </th>
  </tr>
            <tr><td>
                <strong>Bulletin-id</strong>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=94668">
                  <strong>MS07-055</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=96629">
                  <strong>MS07-056</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=95045">
                  <strong>MS07-057</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=101656">
                  <strong>MS07-060</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=91031">
                  <strong>MS07-058</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=95631">
                  <strong>MS07-059</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td>
                <strong>Klassifikation</strong>
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
              </td></tr>
          
            <tr><th colspan="7">Windows-operativsystem</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29763117-c2dc-4746-b31e-0b27350118e6">Kritisk</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c7fb9a8-1d8d-4307-b5c6-bc6c28ee09de">Lav</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=be52f740-e9c9-4228-95c0-00995213bbd0">Kritisk</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1fee539c-ab86-4298-b6f4-22ce31ee7b8b">Alvorlig</a>
              </td><td /></tr>
            <tr><td>Windows XP Professional x64 Edition</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280">Alvorlig</a>
              </td><td /></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e">Kritisk</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=011593a0-f37e-4578-bee1-a985639b521b">Alvorlig</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e">Kritisk</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=011593a0-f37e-4578-bee1-a985639b521b">Alvorlig</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Windows Server 2003 x64 Edition</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859">Alvorlig</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859">Alvorlig</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Windows Server 2003 med SP1 til Itanium-baserede systemer</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b">Alvorlig</a>
              </td><td /></tr>
            <tr><td>Windows Vista</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ceca7f8c-7b56-48fc-8c17-87ffadf25629">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7625f5a4-2921-41ce-986d-4cc0c264135c">Alvorlig</a>
              </td><td /></tr>
          
            <tr><th colspan="7">Windows-operativsystemkomponenter</th></tr>
          
            <tr><td>Outlook Express 5.5 Service Pack 2 på Microsoft Windows 2000 Service Pack 4</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5aa009c9-4edc-4f34-989b-0493549649e8">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 Service Pack 1 på Microsoft Windows 2000 Service Pack 4</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b537115d-611c-4486-960c-08d2df450579">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Outlook Express 6 på Windows XP Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ed7f466-78c7-4251-ba24-8ae71ad54e18">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 på Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6468a552-2194-4866-97d5-ff77ae205eea">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Outlook Express 6 på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=708926e4-f8af-4533-8747-22d6536ebd66">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 på Windows Server 2003 x64 Edition og Outlook Express 6 på Windows Server 2003 x64 Edition Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26720f5a-d7e9-44b9-9330-2e9faa4af0d9">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Outlook Express 6 på Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8844fbb-5b2c-41f3-80f1-dce563aa7cb7">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Mail i Windows Vista</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6ac8d93-adc3-4ec3-bad1-4990bd7d52b4">Alvorlig</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Windows Mail i Windows Vista x64 Edition</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34aaf9dd-4d63-43e2-b631-bbf492d56a26">Alvorlig</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 5.01 Service Pack 4 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95827f3f-a984-4e34-a949-d16a0614121a">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 6 Service Pack 1 ved installation på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=df3ba596-7c5b-4151-9884-6957aa884aab">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 til Windows XP Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=513a8320-6d36-4fc9-a38a-867192b55b53">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 6 til Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae8a26d8-1910-4b8c-8a73-6e2fa6b5b29f">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 til Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aefaa38-8757-4e6e-8924-57cabd1c2fc3">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 6 til Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88aba9dd-653b-4cdf-a513-cca32a7d7e41">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 for Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=309a8f10-c7ea-4961-a969-092b0c4d7bbc">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 7 til Windows XP Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ca0ac93-bf51-40fe-a1ba-cb3e0a36d8b5">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 til Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbd284d0-2664-42a4-ad16-a0535244c81c">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 7 til Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a31c451-32f4-4551-ae45-d600f8b3b11b">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 til Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1915633-d181-4ca1-a4f0-7ca0f865aa72">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 7 til Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=093a2250-3be3-494f-80e0-89ca7217030f">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 i Windows Vista</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=86392e8d-098c-427f-a233-699cdb9375ae">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 7 i Windows Vista x64 Edition</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62490e6d-0a21-4a15-90bd-63ca8f8886b6">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows SharePoint Services 3.0 på Windows Server 2003 Service Pack 1 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76fc2225-2802-46e5-a294-a842e3841877">Alvorlig</a>
              </td></tr>
            <tr><td>Windows SharePoint Services 3.0 på Windows Server 2003 Service Pack 2 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76fc2225-2802-46e5-a294-a842e3841877">Alvorlig</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows SharePoint Services 3.0 på Windows Server 2003 x64 Edition (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055">Alvorlig</a>
              </td></tr>
            <tr><td>Windows SharePoint Services 3.0 på Windows Server 2003 x64 Edition Service Pack 2 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055">Alvorlig</a>
              </td></tr>
          
            <tr><th colspan="7">Microsoft Office</th></tr>
          
            <tr class="alternateRow"><td>Microsoft Word 2000 Service Pack 3</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b3072fb-5933-47f7-a498-13a93e268e57">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td>Microsoft Word 2002 Service Pack 3</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6b787bb-03ff-4f67-8b69-6011fb18ba75">Alvorlig</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office 2004 til Mac</td><td /><td /><td /><td>
                <a Anchor="Office2004" Target="" runat="server" href="http://www.microsoft.com/mac/downloads.aspx">Alvorlig</a>
              </td><td /><td /></tr>
            <tr><td>Microsoft Office SharePoint Server 2007 (KB937832)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aaea9695-f541-4c4c-9107-81ead5cfc8c9">Alvorlig</a>
              </td></tr>
            <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007 x64 Edition (KB937832)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d319164-d133-4493-be27-1aeda62362c4">Alvorlig</a>
              </td></tr>
          </table>


**Bemærk\!**

**\[1\]** Der findes en sikkerhedsopdatering til dette operativsystem. Se den berørte software eller komponent i tabellen og i den relevante sikkerhedsbulletin for at få yderligere oplysninger. 

## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=699031). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) og [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Vejledning i registrering og implementering**

Microsoft har offentliggjort en vejledning i registrering og implementering til denne måneds sikkerhedsopdateringer. Denne vejledning forklarer også it-professionelle, hvordan de kan bruge forskellige værktøjer til at implementere sikkerhedsopdateringen, f.eks. Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office Detection Tool, SMS (Microsoft Systems Management Server), Extended Security Update Inventory Tool og EST (Enterprise Update Scan Tool). Yderligere oplysninger findes i [Knowledge Base-artiklen 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer og Enterprise Update Scan Tool**

MBSA (Microsoft Baseline Security Analyzer) giver administratorer mulighed for at søge på lokale systemer og fjernsystemer efter manglende sikkerhedsopdateringer samt almindelige fejl ved sikkerhedskonfigurationer. Hvis du ønsker yderligere oplysninger om MBSA, kan du besøge webstedet [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

Hvis MBSA 1.2.1 ikke understøtter registrering i forbindelse med en specifik sikkerhedsopdatering, udgiver Microsoft en version af Enterprise Update Scan Tool (EST) til den specifikke sikkerhedsopdatering. Yderligere oplysninger om EST finder du i [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Bemærk** Efter den 9. oktober 2007 opdateres den MSSecure.XML-fil, der bruges af MBSA 1.2.1, ikke længere. Efter denne dato vil der ikke blive føjet nye sikkerhedsopdateringer til MSSecure.XML-filen, der bruges af MBSA 1.2.1, og der vil ikke blive udgivet nye versioner af Enterprise Scan Tool. Yderligere oplysninger finder du på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

**Systems Management Server**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere. Hvis du ønsker yderligere oplysninger, om hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsopdateringer, skal du se webstedet [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brugere kan også bruge [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) som en hjælp til at implementere sikkerhedsopdateringer. Oplysninger om SMS findes på [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Bemærk\!** SMS bruger Microsoft Baseline Security Analyzer og Microsoft Office Detection Tool til at tilbyde omfattende understøttelse af registrering og anvendelse af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til at installere disse opdateringer.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede vigtige opdateringer på MU, WU og WSUS

I denne måned:

  - Microsoft har udgivet tre **ikke-sikkerhedsrelaterede** vigtige opdateringer på Microsoft Update (MU) og Windows Server Update Services (WSUS).
  - Microsoft har udgivet én **ikke-sikkerhedsrelateret** vigtig opdatering til Windows på Windows Update (WU).

Bemærk, at denne information **kun** gælder **ikke-sikkerhedsrelaterede** vigtige opdateringer på Microsoft Update, Windows Update og Windows Server Update Services, som er udgivet på samme dag som oversigten over sikkerhedsopdateringer. Der gives **ikke** information om **ikke-sikkerhedsrelaterede** opdateringer, der er udgivet på andre dage.

#### Sikkerhedsstrategier og community

**Strategier til håndtering af opdateringer**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) giver yderligere oplysninger om Microsofts anbefalinger til bedste fremgangsmåder for anvendelse af sikkerhedsopdateringer.

**Andre sikkerhedsopdateringer**

Opdateringer til andre sikkerhedsproblemer er tilgængelige på følgende placeringer:

  - Der kan hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".
  - Der kan findes opdateringer til forbrugerplatforme på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan hente de sikkerhedsopdateringer, der er gjort tilgængelige på Windows Update denne måned, fra Download Center på Security and Critical Releases ISO CD Image-filer. Yderligere oplysninger finder du i [Microsoft Knowledge Base Article 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Lær, hvordan du forbedrer sikkerheden og optimerer din it-infrastruktur og diskuterer sikkerhedsemner med andre it-fagfolk i [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164).

#### Tak til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for at hjælpe os i arbejdet med at beskytte kunderne:

  - Cu Fang for at have rapporteret et problem, der er beskrevet i MS07-055
  - Rita Schappler fra Global 360 for at arbejde sammen med os om et problem, der er beskrevet i MS07-055
  - Greg MacManus fra [VeriSign iDefense Labs](http://www.idefense.com) for at have rapporteret et problem, der er beskrevet i MS07-056
  - Pierre Geyer fra next.motion OHG for at have rapporteret et problem, der er beskrevet i MS07-057
  - Carsten Eiram fra [Secunia Research](http://secunia.com/) for at have rapporteret et problem, der er beskrevet i MS07-057
  - Jakob Balle fra [Secunia Research](http://secunia.com/) for at have rapporteret et problem, der er beskrevet i MS07-057
  - [Zero Day Initiative for at have rapporteret et problem, der er beskrevet i MS07-058](http://www.zerodayinitiative.com/)
  - Liu Kun-Hao fra Information & Communication Security Technology Center for at have rapporteret et problem, der er beskrevet i MS07-060

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis.
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V 1.0 (9. oktober 2007): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

