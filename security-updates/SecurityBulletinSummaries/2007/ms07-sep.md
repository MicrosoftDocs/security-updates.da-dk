---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for september 2007
TOCTitle: MS07-SEP
ms:assetid: ms07-sep
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms07-sep(v=Security.10)
ms:contentKeyID: 61224035
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for september 2007

Offentliggjort: 11. september 2007 | Opdateret: 12. september 2007

**Version:** 1.1

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for september 2007.

Med udgivelsen af bulletiner for september 2007 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 6. september 2007. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 12. september 2007 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få september måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344690&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede vigtige opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

#### Resuméer

Denne måneds sikkerhedsbulletiner er opstillet efter vigtighed på følgende måde:

## Kritisk (1)

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-051</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94667"><strong>Sårbarhed i Microsoft Agent kan give mulighed for fjernudførelse af kode (938827)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne kritiske sikkerhedsopdatering løser en privat rapporteret sårbarhed. Der findes en sårbarhed i Microsoft Agent, der kan muliggøre fjernudførelse af kode, hvilket skyldes den måde særligt udformede URL-adresser håndteres på. Sårbarheden kan gøre det muligt for en hacker at foretage fjernudførelse af kode på det berørte system. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Kritisk</a></td>
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


## Alvorlig \[3\]

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-052</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=98460"><strong>Sårbarhed i Crystal Reports til Visual Studio kan tillade fjernudførelse af kode (941522)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne vigtige sikkerhedsopdatering løser en offentliggjort sårbarhed. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet RPT-fil. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer og Enterprise Update Scan Tool kan fastslå, om din computer skal bruge denne opdatering. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Visual Studio.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-053</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94467"><strong>Sårbarhed i Windows Services til UNIX kan tillade udvidelse af rettigheder (939778)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne vigtige sikkerhedsopdatering løser én offentligt rapporteret sårbarhed. Der findes en sårbarhed i Windows Services til UNIX 3.0, Windows Services til UNIX 3.5 og subsystem til UNIX-baserede programmer, hvor kørsel af visse setuid binære filer kan gøre det muligt for en hacker at opnå udvidelse af rettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Udvidelse af rettigheder</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Microsoft Baseline Security Analyzer og Enterprise Update Scan Tool kan fastslå, om din computer skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>Windows Services til UNIX, subsystem til UNIX-baserede programmer.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Sikkerhedsbulletin fra Microsoft MS07-054</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletinens titel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=100148"><strong>Sårbarhed i MSN Messenger og Windows Live Messenger kan tillade fjernudførelse af kode (942099)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Resumé</strong></td>
<td>Denne sikkerhedsopdatering løser problemet med en offentliggjort sårbarhed i MSN Messenger og Windows Live Messenger. Sårbarheden kan tillade fjernudførelse af kode, når en bruger accepterer en webkamera- eller videochatinvitation fra en hacker. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over det berørte system. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td><strong>Klassifikation</strong></td>
<td><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Alvorlig</a></td>
</tr>
<tr class="even">
<td><strong>Sårbarhedens omfang</strong></td>
<td>Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td><strong>Registrering</strong></td>
<td>Disse produkter har indbyggede mekanismer til automatisk registrering og implementering af opdateringer. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td><strong>Berørte programmer</strong></td>
<td><strong>MSN Messenger, Windows Live Messenger.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
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
  </tr>
            <tr><td>
                <strong>Bulletin-id</strong>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=94667">
                  <strong>MS07-051</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=98460">
                  <strong>MS07-052</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=94467">
                  <strong>MS07-053</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=100148">
                  <strong>MS07-054</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td>
                <strong>Klassifikation</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Kritisk</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Alvorlig</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Alvorlig</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Alvorlig</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="5">Windows-operativsystem</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cd248ed-d154-4dce-89ef-ceefd2700965">Kritisk</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Windows Server 2003 x64 Edition</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td>Windows Vista</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /></tr>
          
            <tr><th colspan="5">Windows-operativsystemkomponenter</th></tr>
          
            <tr><td>Windows Services til UNIX 3.0 i Windows 2000 Service Pack 4</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Services til UNIX 3.5 på Windows 2000 Service Pack 4</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663">Alvorlig</a>
              </td><td /></tr>
            <tr><td>Windows Services til UNIX 3.0 på Windows XP Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Services til UNIX 3.5 på Windows XP Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663">Alvorlig</a>
              </td><td /></tr>
            <tr><td>Windows Services til UNIX 3.0 på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Services til UNIX 3.5 på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663">Alvorlig</a>
              </td><td /></tr>
            <tr><td>Subsystem til UNIX-baserede programmer på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ab5cc43-0b9c-45eb-aa51-47568ab6ce3f">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Subsystem til UNIX-baserede programmer på Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d21e3e8-b5f6-4044-9db6-054af836492b">Alvorlig</a>
              </td><td /></tr>
            <tr><td>Subsystem til UNIX-baserede programmer i Windows Vista</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d52e4f4-2888-42df-8163-85c648e65b29">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Subsystem til UNIX-baserede programmer i Windows Vista x64 Edition</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4be667cc-c239-480b-a9a0-939bcd27f0de">Alvorlig</a>
              </td><td /></tr>
          
            <tr><th colspan="5">Udviklingsværktøjer og -platforme</th></tr>
          
            <tr><td>Visual Studio .NET 2002 Service Pack 1<br />(KB937057)</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2608c83b-e1b2-4449-9a0e-1e566aac3d76">Alvorlig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Visual Studio .NET 2003<br />(KB937058)</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d612ad41-5a0d-4e13-99ea-d6a5589786d6">Alvorlig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr><td>Visual Studio .NET 2003 Service Pack 1<br />(KB937059)</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b10b04b-932c-4bff-9cbc-b3eeb15064b1">Alvorlig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Visual Studio 2005<br />(KB937060)</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21073cc2-919c-40df-8ebb-aa3db06050d2">Alvorlig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr><td>Visual Studio 2005 Service Pack 1<br />(KB937061)</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=967d43c8-efba-4221-beb0-981e7deef33a">Alvorlig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
          
            <tr><th colspan="5">Andre berørte programmer</th></tr>
          
            <tr class="alternateRow"><td>MSN Messenger 6.2 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&amp;displaylang=en">Alvorlig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr><td>MSN Messenger 7.0 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&amp;displaylang=en">Alvorlig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr class="alternateRow"><td>MSN Messenger 6.2 på Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista og Windows Vista x64 Edition</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&amp;displaylang=en">Alvorlig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr><td>MSN Messenger 7.0 på Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista og Windows Vista x64 Edition</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&amp;displaylang=en">Alvorlig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr class="alternateRow"><td>MSN Messenger 7.5 på Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista og Windows Vista x64 Edition</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&amp;displaylang=en">Alvorlig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr><td>Windows Live Messenger 8.0 på Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista og Windows Vista x64 Edition</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&amp;displaylang=en">Alvorlig</a>
                <strong>[3]</strong>
              </td></tr>
          </table>


**Bemærk\!**

**\[1\]** Der findes en sikkerhedsopdatering til dette operativsystem. Se den berørte software eller komponent i tabellen og i den relevante sikkerhedsbulletin for at få yderligere oplysninger. 

**\[2\]** Det er ikke alle udgaver af denne version af Visual Studio, der er berørt. Se den relevante sikkerhedsbulletin for at få vist en speciel oversigt over berørte udgaver. 

**\[3\]** En mulighed for at foretage en onlineopgradering via tjenesterne MSN Messenger eller Windows Live Messenger er også tilgængelig for denne software. Se den relevante sikkerhedsbulletin, hvis du ønsker yderligere oplysninger.

## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) og [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering". Endelig kan sikkerhedsopdateringer hentes fra Windows Update-kataloget. Du kan få yderligere oplysninger om Windows Update-katalog ved at se [Microsoft Knowledge Base-artikel 323166](http://support.microsoft.com/kb/323166).

**Vejledning i registrering og implementering**

Microsoft har offentliggjort en vejledning i registrering og implementering til denne måneds sikkerhedsopdateringer. Denne vejledning forklarer også it-professionelle, hvordan de kan bruge forskellige værktøjer til at implementere sikkerhedsopdateringen, f.eks. Windows Update, Microsoft Update, Office Update, MBSA (Microsoft Baseline Security Analyzer), Office Detection Tool, SMS (Microsoft Systems Management Server), Extended Security Update Inventory Tool og EST (Enterprise Update Scan Tool). Yderligere oplysninger findes i [Knowledge Base-artiklen 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer og** **Enterprise** **Update Scan Tool**

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

  - Microsoft har udgivet nul **ikke-sikkerhedsrelaterede** vigtige opdateringer på Microsoft Update (MU) og Windows Server Update Services (WSUS).
  - Microsoft har udgivet nul **ikke-sikkerhedsrelaterede**, vigtige opdateringer til Windows i Windows Update (WU).

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

  - Vulnerability Research-teamet fra [Assurent Secure Technologies](http://www.assurent.com/) for at have rapporteret et problem, der er beskrevet i [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667)
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at have rapporteret et problem, der er beskrevet i [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667)
  - En anonym forsker, der arbejder for [iDefense VCP](http://labs.idefense.com/), for at have rapporteret et problem, der er beskrevet i [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667).
  - Brian A. Reiter fra WolfeReiter for at arbejde sammen med os om et problem, der er beskrevet i [MS07-053](http://go.microsoft.com/fwlink/?linkid=94467)
  - Woo Shi fra [team 509](http://www.team509.com/) for at have rapporteret et problem, der er beskrevet i [MS07-054](http://go.microsoft.com/fwlink/?linkid=100148)

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis.
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V 1.0 (11. september 2007): Oversigt over bulletin offentliggjort.
  - V1.1 (12. september 2007): Krav om genstart gentaget ,og links til overførsel tilføjet for MS07-054.

*Built at 2014-04-18T01:50:00Z-07:00*

