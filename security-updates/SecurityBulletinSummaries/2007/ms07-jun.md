---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for juni 2007
TOCTitle: MS07-JUN
ms:assetid: ms07-jun
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms07-jun(v=Security.10)
ms:contentKeyID: 61224030
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for juni 2007

Offentliggjort: 12. juni 2007

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for juni 2007.

Med udgivelsen af sikkerhedsbulletiner for juni 2007 erstatter denne oversigt over bulletin den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 7. juni 2007. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Abonner på [teknisk sikkerhedsinformation fra Microsoft](http://go.microsoft.com/fwlink/?linkid=21163) for at modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft.

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner onsdag den 13. juni 2007 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få juni måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032327013&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede vigtige opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

#### Resuméer

Denne måneds sikkerhedsbulletiner er opstillet efter vigtighed på følgende måde:

## Kritisk (4)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Sikkerhedsbulletin fra Microsoft MS07-031</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletinens titel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=91396"><strong>En sårbarhed i Windows Schannel-sikkerhedspakken kan give mulighed for fjernudførelse af kode (935840)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Resumé</strong></td>
<td style="border:1px solid black;">Denne kritiske sikkerhedsopdatering løser en privat rapporteret sårbarhed i &quot;Secure Channel (Schannel)&quot;-sikkerhedspakken i Windows. Schannel-sikkerhedspakken implementerer SSL (Secure Sockets Layer) og TLS (Transport Layer Security) standard internetgodkendelsesprotokoller. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet webside ved hjælp af en webbrowser eller brugt et program, som gør brug af SSL/TLS. Forsøg på at udnytte denne sårbarhed vil imidlertid sandsynligvis resultere i, at webbrowseren eller programmet afsluttes. Systemet vil ikke kunne oprette forbindelse til websteder eller ressourcer, der bruger SSL eller TLS, indtil systemet er blevet genstartet.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Klassifikation</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Kritisk</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Sårbarhedens omfang</strong></td>
<td style="border:1px solid black;">Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Registrering</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørte programmer</strong></td>
<td style="border:1px solid black;"><strong>Windows</strong>. Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Sikkerhedsbulletin fra Microsoft MS07-033</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletinens titel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=83835"><strong>Samlet sikkerhedsopdatering til Internet Explorer (933566)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Resumé</strong></td>
<td style="border:1px solid black;">Denne kritiske sikkerhedsopdatering løser fem privat rapporterede sårbarheder og en offentliggjort sårbarhed. Alle disse sårbarheder på nær én kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet webside i Internet Explorer. Én sårbarhed kan give mulighed for spoofing (forfalskning), og involverer også en særligt udformet webside. I alle tilfælde af fjernudførelse af kode gælder det, at brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, muligvis rammes i mildere grad end brugere, der opererer med administrative brugerrettigheder. I tilfældet med spoofing (forfalskning) kræves brugerinteraktion, hvis sårbarheden skal udnyttes.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Klassifikation</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Kritisk</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Sårbarhedens omfang</strong></td>
<td style="border:1px solid black;">Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Registrering</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørte programmer</strong></td>
<td style="border:1px solid black;"><strong>Windows, Internet Explorer</strong>. Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Sikkerhedsbulletin fra Microsoft MS07-034</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletinens titel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=88627"><strong>Samlet sikkerhedsopdatering til Outlook Express og Windows Mail (929123)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Resumé</strong></td>
<td style="border:1px solid black;">Denne kritiske sikkerhedsopdatering løser to privat rapporterede sårbarheder og to offentliggjorte sårbarheder. Den ene af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet e-mail vha. Windows Mail i Windows Vista. De andre sårbarheder kan give mulighed for offentliggørelse af oplysninger, hvis en bruger besøger en særligt udformet webside i Internet Explorer, og kan ikke udnyttes direkte i Outlook Express. I tilfælde af sårbarheder i forbindelse med offentliggørelse af oplysninger gælder det, at brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, muligvis rammes i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Klassifikation</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Kritisk</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Sårbarhedens omfang</strong></td>
<td style="border:1px solid black;">Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Registrering</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer og Enterprise Scan Tool kan fastslå, om din computer skal bruge denne opdatering. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørte programmer</strong></td>
<td style="border:1px solid black;"><strong>Windows, Outlook Express, Windows Mail</strong>. Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Sikkerhedsbulletin fra Microsoft MS07-035</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletinens titel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=91397"><strong>Sårbarhed i Win32 API kan give mulighed for fjernudførelse af kode (935839)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Resumé</strong></td>
<td style="border:1px solid black;">Denne kritiske sikkerhedsopdatering løser en privat rapporteret sårbarhed i en Win32 API. Denne sårbarhed kan give mulighed for fjernudførelse af kode eller udvidelse af rettigheder, hvis den berørte API bruges lokalt af et særligt udformet program. Programmer, der bruger denne komponent fra Win32 API'en, kan således blive brugt som vektor for denne sårbarhed. For eksempel bruger Internet Explorer denne Win32 API-funktion i forbindelse med parsing af særligt udformede websider.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Klassifikation</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Kritisk</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Sårbarhedens omfang</strong></td>
<td style="border:1px solid black;">Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Registrering</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørte programmer</strong></td>
<td style="border:1px solid black;"><strong>Windows</strong>. Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Alvorlig (1)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Sikkerhedsbulletin fra Microsoft MS07-030</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletinens titel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=76089"><strong>Sårbarheder i Microsoft Visio kan give mulighed for fjernudførelse af kode (927051)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Resumé</strong></td>
<td style="border:1px solid black;">Denne vigtige sikkerhedsopdatering løser to privat opdagede og på ansvarlig vis rapporterede sårbarheder ud over andre sikkerhedsproblemer, som er blevet registreret i løbet af undersøgelsen. De privat rapporterede sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger har åbnet en særligt udformet Visio-fil. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Der kræves brugerinteraktion for at udnytte disse sårbarheder.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Klassifikation</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Alvorlig</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Sårbarhedens omfang</strong></td>
<td style="border:1px solid black;">Fjernudførelse af kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Registrering</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørte programmer</strong></td>
<td style="border:1px solid black;"><strong>Office, Visio</strong>. Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Moderat (1)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Sikkerhedsbulletin fra Microsoft MS07-032</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletinens titel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=84693"><strong>En sårbarhed i Windows Vista kan give mulighed for offentliggørelse af oplysninger (931213)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Resumé</strong></td>
<td style="border:1px solid black;">Denne moderate sikkerhedsopdatering løser en privat rapporteret sårbarhed. Denne sårbarhed kan give mulighed for, at brugere uden rettigheder får adgang til lokal brugerinformation, inklusive administratoradgangskoder, der er registreret i registreringsdatabasen og det lokale filsystem.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Klassifikation</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Moderat</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Sårbarhedens omfang</strong></td>
<td style="border:1px solid black;">Offentliggørelse af oplysninger</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Registrering</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver muligvis, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørte programmer</strong></td>
<td style="border:1px solid black;"><strong>Windows</strong>. Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
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
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;">Oplysninger        </th>
    <th style="border:1px solid black;">Oplysninger        </th>
    <th style="border:1px solid black;">Oplysninger        </th>
    <th style="border:1px solid black;">Oplysninger        </th>
    <th style="border:1px solid black;">Oplysninger        </th>
    <th style="border:1px solid black;">Oplysninger        </th>
  </tr>
            <tr><td style="border:1px solid black;">
                <strong>Bulletin-id</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=76089">
                  <strong>MS07-030</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=91396">
                  <strong>MS07-031</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=84693">
                  <strong>MS07-032</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=83835">
                  <strong>MS07-033</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=88627">
                  <strong>MS07-034</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=91397">
                  <strong>MS07-035</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">
                <strong>Klassifikation</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Alvorlig</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Kritisk</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Moderat</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Kritisk</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Kritisk</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Kritisk</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="7" style="border:1px solid black;">Berørte Windows-programmer</th></tr>
          
            <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b8e728c-cb9f-4176-93a0-bf42d6387f93">Moderat</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3918ac76-ebb6-4886-9a9e-808eafb96b1b">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8615e6f3-415b-4c23-ba52-7eef70a11d77">Kritisk</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27c7f1b9-2d1d-40cb-ad7e-bfedb6156a9c">Kritisk</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a">Kritisk</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a">Kritisk</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2">Kritisk</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 1</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f">Alvorlig</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f">Alvorlig</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610">Kritisk</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79">Alvorlig</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79">Alvorlig</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182">Kritisk</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 med SP1 til Itanium-baserede systemer</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4">Alvorlig</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4">Alvorlig</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99">Kritisk</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Vista</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdf79d00-6f34-404b-8ad5-a2801ff35443">Moderat</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89dde3f4-4123-4c97-86d8-00a83462c34b">Moderat</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
          
            <tr><th colspan="7" style="border:1px solid black;">Berørte systemkomponenter i Windows</th></tr>
          
            <tr><td style="border:1px solid black;">Internet Explorer 5.01 Service Pack 4 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b49f1ed-abe3-4dbd-a91d-973415658f6b">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 6 Service Pack 1 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c958650-28d2-4dd0-96a8-dbfe79ce3f68">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 6 til Windows XP Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60fb294e-a8e1-405e-a289-2d2723edf7ee">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 6 til Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=086d6d6e-4703-4c6c-a7af-b6dafeeede5d">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 6 til Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ed19127-5c2d-48e4-a8d1-090dc69fd68b">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 6 til Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1449eb5d-6e4c-4332-8cb6-ab9ee59c9a95">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 6 for Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b628a3cc-a70c-478a-a10c-eee254ee34ab">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 7 til Windows XP Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2191703-8cbd-4959-9f84-e13f21173926">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 7 til Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=69c526b8-8b07-42bc-9bed-e18deae21c8e">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 7 til Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a074d9c0-1fed-4753-845e-073cfce99f45">Moderat</a>
              </td><td /><td /></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 7 til Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=744acb43-64da-48cc-ae69-9386b597eabc">Moderat</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 7 til Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=069c1560-b5e5-4dfe-a18d-e0507d406028">Moderat</a>
              </td><td /><td /></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 7 i Windows Vista</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77287386-48eb-4aa9-9537-626a3093aaf7">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 7 i Windows Vista x64 Edition</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77287386-48eb-4aa9-9537-626a3093aaf7">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td style="border:1px solid black;">Outlook Express 6 til Windows XP Service Pack 2</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27cca556-0872-4803-b610-4c895ceb99aa">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Outlook Express 6 til Windows XP Professional x64 Edition</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7">Alvorlig</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Outlook Express 6 til Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7">Alvorlig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Outlook Express 6 til Windows Server 2003 Service Pack 1</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be">Lav</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Outlook Express 6 til Windows Server 2003 Service Pack 2</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be">Lav</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Outlook Express 6 til Windows Server 2003 x64 Edition</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3">Moderat</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Outlook Express 6 til Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3">Moderat</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Outlook Express 6 til Windows Server 2003 med SP1 til Itanium-baserede systemer</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025">Lav</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Outlook Express 6 til Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025">Lav</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Mail i Windows Vista</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee57de19-44ea-48f2-ae28-e76fd2018633">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Mail i Windows Vista x64 Edition</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=343db20f-7794-4423-b11d-885329fbdf78">Kritisk</a>
              </td><td /></tr>
          
            <tr><th colspan="7" style="border:1px solid black;">Berørte Office-programmer</th></tr>
          
            <tr class="alternateRow"><td style="border:1px solid black;">Visio 2002 Service Pack 2</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc1d0483-27e8-4541-b81d-4a47973bea30">Alvorlig</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td style="border:1px solid black;">Visio 2003 Service Pack 2</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c47f432e-8538-42fd-92c9-7e0f1d643e8e">Alvorlig</a>
              </td><td /><td /><td /><td /><td /></tr>
          </table>


**Bemærk\!**

**\[1\]** Der findes en sikkerhedsopdatering til dette operativsystem. Se den berørte software eller komponent i tabellen og i den relevante sikkerhedsbulletin for at få yderligere oplysninger.

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

**Software Update Services**

Med Microsoft Software Update Services (SUS) kan administratorer hurtigt og sikkert implementere de seneste kritiske opdateringer og sikkerhedsopdateringer på Windows 2000- og Windows Server 2003-baserede servere samt på stationære computere, der kører Windows 2000 Professional eller Windows XP Professional.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Software Update Services, finder du på webstedet [Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

**Systems Management Server**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere. Hvis du ønsker yderligere oplysninger, om hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsopdateringer, skal du se webstedet [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brugere kan også bruge [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) som en hjælp til at implementere sikkerhedsopdateringer. Oplysninger om SMS findes på [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Bemærk\!** SMS bruger Microsoft Baseline Security Analyzer og Microsoft Office Detection Tool til at tilbyde omfattende understøttelse af registrering og anvendelse af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til at installere disse opdateringer.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

Bemærk, at dette værktøj **ikke** distribueres ved hjælp af Software Update Services (SUS).

#### Ikke-sikkerhedsrelaterede vigtige opdateringer på MU, WU, WSUS og SUS

I denne måned:

  - Microsoft har udgivet syv **ikke-sikkerhedsrelaterede** vigtige opdateringer på Microsoft Update (MU) og Windows Server Update Services (WSUS).
  - Microsoft har ikke udgivet nogen **ikke-sikkerhedsrelaterede** vigtige opdateringer til Windows på Windows Update (WU) og Software Update Services (SUS).

Bemærk, at denne information **kun** gælder **ikke-sikkerhedsrelaterede** vigtige opdateringer på Microsoft Update, Windows Update, Windows Server Update Services og Software Update Services, som er udgivet på samme dag som oversigten over sikkerhedsopdateringer. Der gives **ikke** information om **ikke-sikkerhedsrelaterede** opdateringer, der er udgivet på andre dage.

#### Sikkerhedsstrategier og community

**Strategier til håndtering af opdateringer**

[Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) giver yderligere oplysninger om Microsofts anbefalinger til bedste fremgangsmåder for anvendelse af sikkerhedsopdateringer.

**Andre sikkerhedsopdateringer**

Opdateringer til andre sikkerhedsproblemer er tilgængelige på følgende placeringer:

  - Der kan hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".
  - Der kan findes opdateringer til forbrugerplatforme på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan hente de sikkerhedsopdateringer, der er gjort tilgængelige på Windows Update denne måned, fra Download Center på Security and Critical Releases ISO CD Image-filer. Yderligere oplysninger finder du i [Microsoft Knowledge Base Article 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Zone Community**

Lær, hvordan du forbedrer sikkerheden og optimerer din it-infrastruktur og diskuterer sikkerhedsemner med andre it-fagfolk i [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164).

#### Tak til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for at hjælpe os i arbejdet med at beskytte kunderne:

  - En anonym forsker, der arbejder for [iDefense VCP](http://idefense.com/), for at have rapporteret et problem, der er beskrevet i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Tom Cross fra [ISS](http://www.iss.net/) for at arbejde sammen med Microsoft om et problem, der er beskrevet i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - En anonym forsker, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for at have rapporteret et problem, der er beskrevet i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Sam Thomas, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Will Dorman fra [CERT/CC](http://www.cert.org/certcc.html) for at have rapporteret et problem, der er beskrevet i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - cocoruder fra [Fortinet Security Research](http://www.fortinet.com/) for at arbejde sammen med Microsoft om et problem, der er beskrevet i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Billy Rios for at have rapporteret et problem, der er beskrevet i [MS07-035](http://go.microsoft.com/fwlink/?linkid=91397).
  - Thomas Lim fra [COSEINC](http://www.coseinc.com/) for at have rapporteret et problem, der er beskrevet i [MS07-031](http://go.microsoft.com/fwlink/?linkid=91396).
  - [SANS ISC](http://isc.sans.org/) for at arbejde sammen med os om et problem, der er beskrevet i [MS07-034](http://go.microsoft.com/fwlink/?linkid=88627).
  - Yosuke Hasegawa fra [WebAppSec JP](https://www.webappsec.jp/) for at have rapporteret et problem, der er beskrevet i [MS07-034](http://go.microsoft.com/fwlink/?linkid=88627).
  - Robbie Sohlman for at have rapporteret et problem, der er beskrevet i [MS07-032](http://go.microsoft.com/fwlink/?linkid=84693).

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis.
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (12. juni 2007): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

