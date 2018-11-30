---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for december 2009
TOCTitle: MS09-DEC
ms:assetid: ms09-dec
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms09-dec(v=Security.10)
ms:contentKeyID: 61224050
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for december 2009

Offentliggjort: 8. december 2009 | Opdateret: 13. januar 2010

**Version:** 2.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for december 2009.

Med udgivelsen af bulletiner for december 2009 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 3. december 2009. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 9. december 2009 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få december måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407802&culture=en-us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=177727">MS09-071</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Internet Authentication Service kan tillade fjernudførelse af kode (974318)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Windows. De alvorligste af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis beskeder, der modtages af IAS-serveren (Internet Authentication Service), kopieres forkert til hukommelsen ved håndtering af PEAP-godkendelsesforsøg. På Windows Server 2008 er Internet Authentication Service udskiftet med NPS (Network Policy Server). En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Servere, der anvender Internet Authentication Service eller Network Policy Server, påvirkes kun, hvis de anvender PEAP med MS-CHAP v2-godkendelse.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141642">MS09-074</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft Office Project kan muliggøre fjernudførelse af kode (967183)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Office Project. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Project-fil. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a></td>
<td style="border:1px solid black;"><strong>Samlet sikkerhedsopdatering til Internet Explorer (976325)</strong><br />
<br />
Denne sikkerhedsopdatering løser fire privat rapporterede sårbarheder og én offentliggjort sårbarhed i Internet Explorer. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Et ActiveX-objekt, der er opbygget med Microsoft ATL-headere (Active Template Library), kan også give mulighed for fjernudførelse af kode. Denne sårbarhed er blevet beskrevet i Microsoft-sikkerhedsmeddelelse 973882 og sikkerhedsbulletin fra Microsoft MS09-035.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=177555">MS09-069</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Local Security Authority Subsystem Service kan give mulighed for Denial-of-Service (974392)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre Denial-of-Service, hvis en godkendt hacker via fjernadgang sender en særligt udformet ISAKMP-besked, mens den pågældende kommunikerer via IPsec (Internet Protocol security), til LSASS (Local Security Authority Subsystem Service) på et berørt system.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial-of-Service</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163844">MS09-070</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Active Directory Federation Services kan give mulighed for fjernudførelse af kode (971726)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Windows. De mere alvorlige af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en hacker sender en særligt udformet HTTP-anmodning til en ADFS-aktiveret webserver. En hacker skal være en godkendt bruger for at kunne udnytte disse sårbarheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163833">MS09-073</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i tekstkonvertere til WordPad og Office kan muliggøre fjernudførelse af kode (975539)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i tekstkonvertere til Microsoft WordPad og Microsoft Office. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en særligt udformet Word 97-fil åbnes i WordPad eller Microsoft Office Word. En hacker, som har held til at udnytte denne sårbarhed, kan opnå samme rettigheder som brugeren. Brugere, hvis konti er konfigureret til færre rettigheder på systemet, kan være berørt i mindre grad end brugere, der arbejder med administratorrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
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
<th style="border:1px solid black;">Titel på sårbarhed</th>
<th style="border:1px solid black;">CVE ID</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse</th>
<th style="border:1px solid black;">Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=177555">MS09-069</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. overbelastning af ressourcer i LSASS (Local Security Authority Subsystem Service)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3675">CVE-2009-3675</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Sårbarheden muliggør ikke fjernudførelse af kode, men udelukkende denial-of-service som en godkendt hacker med fjernadgang kan forsøge at udnytte.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163844">MS09-070</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. spoofing (forfalskning) af enkelt logon</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2508">CVE-2009-2508</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Sårbarheden muliggør ikke fjernudførelse af kode, kun spoofing.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163844">MS09-070</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. fjernudførelse af kode i ADFS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2509">CVE-2009-2509</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Sårbarheden kan kun udnyttes af en godkendt hacker.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=177727">MS09-071</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt hukommelse i Internet Authentication Service</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2505">CVE-2009-2505</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Begrænset mulighed for fjernudførelse af kode. Det mest sandsynlige resultat er denial-of-service.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=177727">MS09-071</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. omgåelse af godkendelse af MS-CHAP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3677">CVE-2009-3677</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Sårbarheden muliggør ikke fjernudførelse af kode, kun udvidelse af rettigheder som følge af tilsidesættelse af netværksgodkendelse.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. initialisering i ATL COM</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493">CVE-2009-2493</a></td>
<td style="border:1px solid black;">Ingen </td>
<td style="border:1px solid black;">(Denne sårbarhed er allerede blevet tildelt en vurdering under udnyttelsesindekset i <a href="http://technet.microsoft.com/security/bulletin/ms09-jul">oversigten over bulletin for juli</a>. Dette skyldes, at sårbarheden først blev behandlet i <a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a>.)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt, ikke-initialiseret hukommelse</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3671">CVE-2009-3671</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt hukommelse i HTML-objekt</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3672">CVE-2009-3672</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt, ikke-initialiseret hukommelse</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3673">CVE-2009-3673</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt, ikke-initialiseret hukommelse</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3674">CVE-2009-3674</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163833">MS09-073</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt hukommelse for tekstkonverter til WordPad og Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2506">CVE-2009-2506</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141642">MS09-074</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. hukommelsesvalidering i Project</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0102">CVE-2009-0102</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
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
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="6" style="border:1px solid black;">Microsoft Windows 2000</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177727">
                      <strong>MS09-071</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169404">
                      <strong>MS09-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177555">
                      <strong>MS09-069</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163844">
                      <strong>MS09-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163833">
                      <strong>MS09-073</strong>
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
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b02d10d-1abd-4d68-826b-71dad543657a">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0cf37247-505a-4dc2-aad7-c8cb1a63b57a">Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7fb6261c-6895-4f79-be2c-bb110874a19c">Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=560e01db-5f59-4ef1-9406-f5d7e0fd4128">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50936f51-b0a9-4e94-85bf-93f9ad74fdd1">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(KB973904)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="6" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177727">
                      <strong>MS09-071</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169404">
                      <strong>MS09-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177555">
                      <strong>MS09-069</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163844">
                      <strong>MS09-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163833">
                      <strong>MS09-073</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d294be6-19d1-43b5-9c75-f9d30699a2e7">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=facab13f-ea31-4c71-be4c-24e44ded174f">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=def2c038-3b03-4162-a563-a6ebec756f37">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c003629-77bf-4735-bd4a-c37c4386f869">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5448b168-6bf7-4bae-9627-b88d76c4d5c5">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c090c4c2-c277-4d8c-91e1-28286bc5443e">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(KB973904)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17b5206d-61e9-4663-afc7-80e98bf4d618">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a253c19a-c808-4115-8bd0-cf312d396abd">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98a56425-4f88-4f0f-963b-dada8dc0d8f8">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c9af3b5-d015-4025-bbb4-1a5113e9113f">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2bbf515-f81a-436b-947b-cbf2db85fdd9">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b9bf156-cd34-460f-b4ad-571e37f54659">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB973904)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="6" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177727">
                      <strong>MS09-071</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169404">
                      <strong>MS09-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177555">
                      <strong>MS09-069</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163844">
                      <strong>MS09-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163833">
                      <strong>MS09-073</strong>
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
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d49b386-133a-4d51-b6f0-cec0c70ef93e">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6659fc40-71ee-44a9-9656-8d3ee02b5bc0">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7bdba030-e2c6-44ac-bb5f-24ae8ec372a2">Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0dd50357-64f2-4286-86ba-c512e65eed2a">Internet Explorer 8</a><br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a779aae1-7724-4458-94fb-a2343356ecae">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31351b9e-b5bb-4618-990b-1089ea5a3bc2">Windows Server 2003 Service Pack 2</a>
                    [1]
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9678229-2473-4aae-a814-eca9ea556d17">Windows Server 2003 Service Pack 2</a>
                    <br />(KB973904)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a273b47-8a18-4778-9b60-8b560a1ce089">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=287e7921-8aab-42a6-b647-551d0a9adc15">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4de4bbcd-b1b8-4482-8ef7-0d9b4a730e0c">Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e62aba15-5eeb-46a2-a142-bfca94016c55">Internet Explorer 8</a><br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8a9bf12-4ad6-49fd-b2b7-f379dc3309d2">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6eb9d9b-1a43-4b30-a033-19a1db786244">Windows Server 2003 x64 Edition Service Pack 2</a>
                    [2]
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=257facf3-20a1-49e2-ab4c-c1ae67fe05a0">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB973904)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=498f5eeb-d03e-42ee-ad6a-9d6f98c66acb">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ce1a721-0c6a-4775-9407-9633d817d716">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72d44de7-dfc5-4667-a59f-2ee73d0e3708">Internet Explorer 7</a><br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5b003ad-af25-488a-91fb-98835a0bfeac">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a7784ef-5d25-4de1-a293-f742b5a3473d">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(KB973904)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="6" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177727">
                      <strong>MS09-071</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169404">
                      <strong>MS09-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177555">
                      <strong>MS09-069</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163844">
                      <strong>MS09-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163833">
                      <strong>MS09-073</strong>
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
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6">Windows Vista Service Pack 2</a><br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40d26d40-4203-4013-b3f9-912a5b209fbd">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47d5ada1-1d60-4233-bdd3-64918b5e1245">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab">Windows Vista x64 Edition Service Pack 2</a><br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3140527a-aa33-462b-b3a6-bfcd78b5aa0c">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e466b48-422f-4c80-8fdf-ba61111942b1">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="6" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177727">
                      <strong>MS09-071</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169404">
                      <strong>MS09-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177555">
                      <strong>MS09-069</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163844">
                      <strong>MS09-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163833">
                      <strong>MS09-073</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968">Windows Server 2008 til 32 bit-systemer</a>*<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0570536-756e-4fda-883d-f2a3c4ac5bbd">Internet Explorer 7</a>*<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43660133-43e1-41f3-8a82-98c4a739914f">Internet Explorer 8</a>*<br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6715abb-fd93-44ba-9854-2ecc672622da">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b">Windows Server 2008 til x64-baserede systemer</a>*<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0e72d0f1-2ce7-4650-b72c-bb303351aafc">Internet Explorer 7</a>*<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22972970-740f-4c50-93ec-f6d49dd1b360">Internet Explorer 8</a>*<br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d1f5e9e-a7de-4f96-89c8-510fd51f16e7">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89defe77-7e82-4bfa-9693-66c93b930da1">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89defe77-7e82-4bfa-9693-66c93b930da1">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a><br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c7765a2-3117-4dd8-94b4-0060ca16871b">Internet Explorer 7</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="6" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177727">
                      <strong>MS09-071</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169404">
                      <strong>MS09-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177555">
                      <strong>MS09-069</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163844">
                      <strong>MS09-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163833">
                      <strong>MS09-073</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 Beta til 32-bit-systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5af3be0b-2dd2-4039-90e1-2278e9c5aee5">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows 7 til x64-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d9a04c8-a019-4943-8e93-c6bfd77c8960">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="6" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177727">
                      <strong>MS09-071</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169404">
                      <strong>MS09-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=177555">
                      <strong>MS09-069</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163844">
                      <strong>MS09-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163833">
                      <strong>MS09-073</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer </td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bcb38127-787f-49b0-b3fb-62f6a8628d89">Internet Explorer 8</a>*<br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 til Itanium-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c1b96f2-b3c3-4711-a9ad-b2133ea7bf81">Internet Explorer 8</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**Bemærkning til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i MSDN-artiklerne [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core til Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkninger til MS09-070**

\[1\] Påvirkes kun, når der er opdateret med Windows Server 2003 R2, der anvender Active Directory Federation Services.

\[2\] Påvirkes kun, når der er opdateret med Windows Server 2003 R2 x64 Edition, der anvender Active Directory Federation Services.

**Bemærkning til MS09-073**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

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
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141642">
                      <strong>MS09-074</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163833">
                      <strong>MS09-073</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office XP</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc3ec3ba-2cec-43ab-b184-c222794231f2">Microsoft Office XP Service Pack 3</a>
                    <br />(KB975008)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2003</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b4a4126c-b0b3-4db2-b6f5-0e67519c2a5f">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB975051)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Øvrigt Microsoft Office-software</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141642">
                      <strong>MS09-074</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163833">
                      <strong>MS09-073</strong>
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
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Project 2000</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=135c010a-55f4-4385-b67d-96ea06ef881a">Microsoft Project 2000 Service Release 1</a>
                    <br />(KB961083)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Project 2002</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c55ef8fe-8f66-42fc-a298-de6f8886b3e4">Microsoft Project 2002 Service Pack 1</a>
                    <br />(KB961079)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Project 2003</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ea8ca39-f130-439a-92d5-77e9ef050105">Microsoft Office Project 2003 Service Pack 3</a>
                    <br />(KB961082)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Works 8.5</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=807426a1-8b78-4681-a606-dc39f4d7b64a">Microsoft Works 8.5</a>
                    <br />(KB977304)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Converter Pack</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3ff8bb6-d047-42f1-9331-b6df85fff9fd">Microsoft Office Converter Pack</a>
                    <br />(KB974882)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til MS09-073**

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

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

**Systems Management Server**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere. Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig, se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Få mere at vide om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsoplysninger, på [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brugere kan også bruge SUIT (Security Update Inventory Tool) ved implementering af sikkerhedsopdateringer. Oplysninger om SMS findes på [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Bemærk\!** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til at installere disse opdateringer.

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

  - Ryan Smith fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret et problem, der er beskrevet i MS09-072
  - Sam Thomas eshu.co.uk, der arbejder med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS09-072
  - [team509](http://www.team509.com/), der arbejder sammen med [Verisign iDefense Labs](http://labs.idefense.com/), for at have rapporteret et problem, der er beskrevet i MS09-072.
  - En anonym forsker, der samarbejder med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS09-072
  - En anonym forsker, der samarbejder med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret endnu et problem, der er beskrevet i MS09-072
  - Sean Larsson og Jun Mao fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem, der er beskrevet i MS09-073
  - Bing Liu fra [Fortinet's FortiGuard Labs](http://www.fortiguard.com/) for at have rapporteret et problem, der er beskrevet i MS09-074

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (8. december 2009): Oversigt over bulletin offentliggjort.
  - V1.1 (9. december 2009): Opdaterede beskrivelsen for MS09-071 i tabellen Resuméer. Rettede genstartskrav for MS09-073.
  - V2.0 (13. januar 2010): For MS09-073, omdøbt de opdateringer, der tidligere var angivet som **Microsoft Office Word 2002 Service Pack 3 (KB975008)** og **Microsoft Office Word 2003 Service Pack 3 (KB975051)**, til henholdsvis **Microsoft Office XP Service Pack 3 (KB975008)** og **Microsoft Office 2003 Service Pack 3 (KB975051)**.

*Built at 2014-04-18T01:50:00Z-07:00*

