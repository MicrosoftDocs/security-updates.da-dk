---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for november 2007
TOCTitle: MS07-NOV
ms:assetid: ms07-nov
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms07-nov(v=Security.10)
ms:contentKeyID: 61224033
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for november 2007

Offentliggjort: 13. november 2007

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for november 2007.

Med udgivelsen af bulletiner for november 2007 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindelig blev offentliggjort den 8. november 2007. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 14. november 2007 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få november måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344694&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede vigtige opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

#### Resuméer

Denne måneds sikkerhedsbulletiner er opstillet efter vigtighed på følgende måde:

## Kritisk (1)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Sikkerhedsbulletin fra Microsoft MS07-061</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletinens titel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=103190"><strong>En sårbarhed i Windows URI-håndtering kan give mulighed for fjernudførelse af kode (943460)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Resumé</strong></td>
<td style="border:1px solid black;">Denne opdatering løser en offentligt rapporteret sårbarhed. Der findes en sårbarhed, der kan muliggøre fjernudførelse af kode i den måde, hvorpå Windows Shell håndterer særligt udformede URI'er, som overføres dertil. Hvis Windows Shell ikke i tilstrækkelig grad har valideret disse URI'er, kan en hacker udnytte denne sårbarhed til at udføre arbitrær kode. Microsoft har kun identificeret muligheder for at udnytte denne sårbarhed på systemer med Internet Explorer 7. Sårbarheden findes imidlertid i en Windows-fil, Shell32.dll, som findes i alle understøttede udgaver af Windows XP og Windows Server 2003.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver, at maskinen genstartes.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørte programmer</strong></td>
<td style="border:1px solid black;"><strong>Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
</tr>
</tbody>
</table>


## Alvorlig (1)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Sikkerhedsbulletin fra Microsoft MS07-062</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletinens titel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=99391"><strong>En sårbarhed i DNS kan tillade spoofing (forfalskning) (941672)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Resumé</strong></td>
<td style="border:1px solid black;">Denne vigtige sikkerhedsopdatering løser en privat rapporteret sårbarhed. Denne forfalskningssårbarhed findes i Windows DNS-servere og kan gøre det muligt for en hacker at sende særligt udformede svar på DNS-anmodninger og derved forfalske eller omdirigere internettrafik fra legitime steder.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Klassifikation</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">Alvorlig</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Sårbarhedens omfang</strong></td>
<td style="border:1px solid black;">Spoofing (forfalskning)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Registrering</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan registrere, om dit computersystem skal bruge denne opdatering. Opdateringen kræver genstart, med undtagelse af bestemte situationer.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørte programmer</strong></td>
<td style="border:1px solid black;"><strong>Windows.</strong> Du kan finde yderligere oplysninger i afsnittene Berørte programmer og downloadplaceringer.</td>
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
  </tr>
            <tr><td style="border:1px solid black;">
                <strong>Bulletin-id</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=103190">
                  <strong>MS07-061</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=99391">
                  <strong>MS07-062</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">
                <strong>Klassifikation</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Kritisk</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/danmark/sikkerhed/bulletin/klassificering.mspx">
                  <strong>Alvorlig</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="3" style="border:1px solid black;">Windows-operativsystem</th></tr>
          
            <tr><td style="border:1px solid black;">Microsoft Windows 2000 Server Service Pack 4</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c80fcd9b-d0f8-44db-96fc-bf2ead054ff4">Alvorlig</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ba1c2f9-1bde-4e97-b327-21259c5e5104">Kritisk</a>
              </td><td style="border:1px solid black;">
                 
              </td></tr>
            <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ef7fdd7-8887-4c64-a70c-c6ae734d7c5f">Kritisk</a>
              </td><td style="border:1px solid black;">
                <strong> </strong>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 1</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b">Kritisk</a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d">Alvorlig</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5d8a866-2c1f-4035-8325-c1be61a75c3b">Kritisk</a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed8e2cb4-bcd9-40fc-9ad6-46b364d0656d">Alvorlig</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326">Kritisk</a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e">Alvorlig</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf26da08-15b8-4d65-ba12-4cc74c7a1326">Kritisk</a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1323e14-ffa7-4d03-a2a7-9240c192a75e">Alvorlig</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 med SP1 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5">Kritisk</a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6">Alvorlig</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c055f11-3273-4a4c-a33f-bf61ac9ec4c5">Kritisk</a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3ad67de-85ad-452d-a1e0-0af3faf969d6">Alvorlig</a>
              </td></tr>
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

**Bemærk** Efter den 9. oktober 2007 opdateres den MSSecure.XML-fil, der bruges af MBSA 1.2.1, ikke længere. Efter denne dato vil der ikke blive føjet nye sikkerhedsopdateringer til MSSecure.XML-filen, der bruges af MBSA 1.2.1, og der vil ikke blive udgivet nye versioner af Enterprise Scan Tool. Dette berører ikke SUIT (Security Update Inventory Tool) eller ESUIT (Extended Security Update Inventory Tool) til SMS 2.0 og SMS 2003. Yderligere oplysninger finder du på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

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

  - Jesper Johansson for at arbejde sammen med os om et problem, der er beskrevet i MS07-061
  - Carsten H. Eiram fra [Secunia](http://corporate.secunia.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS07-061
  - Aviv Raff fra [Finjan](http://www.finjan.com/) for at arbejde sammen med os om et problem, der er beskrevet i MS07-061
  - Petko Petkov fra [GNUCITIZEN](http://www.gnucitizen.org/) for at have arbejdet sammen med os om et problem, der er beskrevet i MS07-061
  - Alla Berzroutchko fra [Scanit](http://www.scanit.be/) for at have rapporteret et problem, der er beskrevet i MS07-062
  - Amit Klein fra [Trusteer](http://www.trusteer.com/) for at have rapporteret et problem, der er beskrevet i MS07-062

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis.
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (13. november 2007): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

