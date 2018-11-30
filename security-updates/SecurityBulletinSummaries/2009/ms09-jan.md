---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for januar 2009
TOCTitle: MS09-JAN
ms:assetid: ms09-jan
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms09-jan(v=Security.10)
ms:contentKeyID: 61224052
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for januar 2009

Offentliggjort: 13. januar 2009

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for januar 2009.

Med udgivelsen af bulletiner for januar 2009 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 8. januar 2009. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 14. januar 2009 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få januar måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395120). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132991">MS09-001</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i SMB kan give mulighed for fjernudførelse af kode (958687)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i Microsoft Server Message Block (SMB) Protocol. Disse sårbarheder kan muliggøre fjernudførelse af kode på berørte systemer. En hacker, som har held til at udnytte disse sårbarheder, kan installere programmer, se, ændre eller slette data eller oprette nye konti med komplette brugerrettigheder. De bedste fremgangsmåder for brug af firewalls og standardkonfigurationer af firewalls kan hjælpe med at beskytte netværk mod angreb, der kommer fra en placering uden for virksomhedsperimeteren. De bedste fremgangsmåder anbefaler, at systemer med forbindelse til internettet har mindst mulig antal åbne porte.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/danmark/technet/sikkerhed/bulletin/klassificering.mspx">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<th style="border:1px solid black;">Bulletinens titel</th>
<th style="border:1px solid black;">CVE ID</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse</th>
<th style="border:1px solid black;">Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132991">MS09-001</a></td>
<td style="border:1px solid black;">Sårbarheder i SMB kan give mulighed for fjernudførelse af kode (958687)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4114">CVE-2008-4114</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er kun en sårbarhed med Denial-of-Service.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132991">MS09-001</a></td>
<td style="border:1px solid black;">Sårbarheder i SMB kan give mulighed for fjernudførelse af kode (958687)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4834">CVE-2008-4834</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er en sårbarhed i forbindelse med fjernudførelse af kode, men fungerende exploit-kode er usandsynlig. Yderligere oplysninger finder du under bloggen Microsoft Security Vulnerability Research &amp; Defense, <a href="http://blogs.technet.com/swi/archive/2009/01/09/ms09-001-prioritizing-the-deployment-of-the-smb-bulletin.aspx">Prioritizing the deployment of the SMB bulletin</a>.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132991">MS09-001</a></td>
<td style="border:1px solid black;">Sårbarheder i SMB kan give mulighed for fjernudførelse af kode (958687)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4835">CVE-2008-4835</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er en sårbarhed i forbindelse med fjernudførelse af kode, men fungerende exploit-kode er usandsynlig. Yderligere oplysninger finder du under bloggen Microsoft Security Vulnerability Research &amp; Defense, <a href="http://blogs.technet.com/swi/archive/2009/01/09/ms09-001-prioritizing-the-deployment-of-the-smb-bulletin.aspx">Prioritizing the deployment of the SMB bulletin</a>.</td>
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
  </tr>
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Windows 2000</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132991">
                      <strong>MS09-001</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/danmark/technet/sikkerhed/bulletin/klassificering.mspx">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0678d14-c1b5-457a-8222-8e7682760ed4">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td></tr>
              
                <tr><th colspan="2" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132991">
                      <strong>MS09-001</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/danmark/technet/sikkerhed/bulletin/klassificering.mspx">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eeafcdc5-df39-4b29-b6f1-7d32b64761e1">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26898401-f669-4542-ad93-199ed1fe9a2a">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td></tr>
              
                <tr><th colspan="2" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132991">
                      <strong>MS09-001</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/danmark/technet/sikkerhed/bulletin/klassificering.mspx">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=588ca8e8-38a9-47ed-9c41-09aaf1022e49">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee59441c-1e8f-4425-ae8d-dec14e7f13fb">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=caec9321-fa5b-42f0-9f26-61f673fe6eef">Windows Server 2003 med SP1 til Itanium-baserede systemer og Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td></tr>
              
                <tr><th colspan="2" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132991">
                      <strong>MS09-001</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/danmark/technet/sikkerhed/bulletin/klassificering.mspx">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Vista og Windows Vista Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9179c463-c10a-452a-990f-b7e37cdd889b">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b26952e-b59d-4b0f-a52d-025e45ecd233">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="2" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132991">
                      <strong>MS09-001</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/danmark/technet/sikkerhed/bulletin/klassificering.mspx">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til 32 bit-systemer                    </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7245b411-7c9e-41e5-9841-4c586336086c">Windows Server 2008 til 32 bit-systemer</a>*<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a241eaad-95a0-442b-978f-f21a6f0c7db4">Windows Server 2008 til x64-baserede systemer</a>*<br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab7c7015-20bb-4a0c-977a-969f4e2a5189">Windows Server 2008 for Itanium-baserede systemer</a>
                    <br />(Moderat)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008**

**\*Windows Server 2008 - serverens hovedinstallation er berørt.** For understøttede udgaver af Windows Server 2008 gælder denne opdatering med den samme klassifikation, uanset om Windows Server 2008 blev installeret ved anvendelse af installationsindstillingen Server Core eller ej. Se [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) for flere oplysninger om denne installationsindstilling. Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
  - [Nye, reviderede og offentliggjorte opdateringer til Microsoft-produkter ud over Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

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

  - En anonym forsker, der samarbejder med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS09-001
  - En anonym forsker, der samarbejder med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret endnu et problem, der er beskrevet i MS09-001

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis.
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (13. januar 2009): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

