---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for december 2010
TOCTitle: MS10-DEC
ms:assetid: ms10-dec
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms10-dec(v=Security.10)
ms:contentKeyID: 61224062
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for december 2010

Offentliggjort: 14. december 2010

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for december 2010.

Med udgivelsen af sikkerhedsbulletiner for december 2010 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 9. december 2010. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 15. december 2010 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få december måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454444&eventcategory=4&culture=en-us&countrycode=us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td style="border:1px solid black;"><strong>Samlet sikkerhedsopdatering til Internet Explorer (2416400)</strong><br />
<br />
Denne sikkerhedsopdatering løser fire privat rapporterede sårbarheder og tre offentliggjorte sårbarheder i Internet Explorer. De mest alvorlige sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside via Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i OpenType Font (OFT)-driver kan tillade fjernudførelse af kode (2296199)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i Windows OTF-driveren (Open Type Font), som kunne tillade fjernudførelse af kode. En hacker kan hoste et særligt udformet OpenType-skrifttype på en netværksshare. Den berørte kontrolsti aktiveres derefter, når brugeren navigerer til delingen i Windows Explorer, og den særligt udformede skrifttype kan overtage kontrollen med et berørt system fuldstændigt. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203463">MS10-092</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Opgavestyring kan give mulighed for udvidelse af rettigheder (2305420)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Windows Opgavestyring. Sårbarhederne kan tillade en udvidelse af rettigheder, hvis en hacker er logget på et berørt system og har kørt et særligt udformet program. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes via fjernadgang eller af anonyme brugere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206698">MS10-093</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Windows Movie Maker kan muliggøre fjernudførelse af kode (2424434)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Windows Movie Maker. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en hacker overtale en bruger til at åbne en legitim Windows Movie Maker-fil, der er placeret i samme netværk som en særligt udformet biblioteksfil. For at et angreb skal lykkes, skal en bruger besøge en fjernplacering på et filsystem, der ikke er tillid til, eller en WebDAV-deling og åbne et dokument fra denne placering, der derefter indlæses med et sårbart program.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206699">MS10-094</a></td>
<td style="border:1px solid black;"><strong>Sårbarhed i Windows Media Encoder kan muliggøre fjernudførelse af kode (2447961)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Windows Media Encoder Sårbarheden kan muliggøre fjernudførelse af kode, hvis en hacker overtale en bruger til at åbne en legitim Windows Media Profile-fil (.prx), der er placeret i samme netværk som en særligt udformet biblioteksfil. For at et angreb skal lykkes, skal en bruger besøge en fjernplacering på et filsystem, der ikke er tillid til, eller en WebDAV-deling og åbne et dokument fra denne placering, der derefter indlæses med et sårbart program.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206683">MS10-095</a></td>
<td style="border:1px solid black;"><strong>Sårbarhed i Microsoft Windows kan muliggøre fjernudførelse af kode (2385678)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger åbner en filtype som f.eks. .eml og .rss (Windows Live Mail) eller .wpost (Microsoft Live Writer), der er placeret i den samme netværksmappe som en særligt udformet biblioteksfil. For at et angreb skal lykkes, skal en bruger besøge en fjernplacering på et filsystem, der ikke er tillid til, eller en WebDAV-deling og åbne et dokument fra denne placering, der derefter indlæses med et sårbart program.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206738">MS10-096</a></td>
<td style="border:1px solid black;"><strong>Sårbarhed i Windows Adressekartotek kan muliggøre fjernudførelse af kode (2423089)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Windows Adressekartotek. Sårbarheden kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Windows Adressekartotek-fil, der er placeret i den samme netværksmappe som en særligt udformet biblioteksfil. For at et angreb skal lykkes, skal en bruger besøge en fjernplacering på et filsystem, der ikke er tillid til, eller en WebDAV-deling og åbne et dokument fra denne placering, der derefter indlæses med et sårbart program.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206689">MS10-097</a></td>
<td style="border:1px solid black;"><strong>Usikker indlæsning af bibliotek i Internet Connection Signup Wizard kan tillade fjernudførelse af kode (2443105)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed i Internet Connection Signup Wizard for Microsoft Windows. Denne sikkerhedsopdatering er klassificeret som Alvorlig for alle understøttede versioner af Windows XP og Windows Server 2003. Alle understøttede versioner af Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er ikke berørt af sårbarheden.<br />
<br />
Sårbarheden kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet .ins- eller .isp-fil, der er placeret i den samme netværksmappe som en særligt udformet biblioteksfil. For at et angreb skal lykkes, skal en bruger besøge en fjernplacering på et filsystem, der ikke er tillid til, eller en WebDAV-deling og åbne et dokument fra denne placering, der derefter indlæses med et sårbart program.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Windows-kernetilstandsdrivere kan muliggøre udvidelse af rettigheder (2436673)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort sårbarhed og flere privat rapporterede sårbarheder i Microsoft Windows. Sårbarhederne kan tillade en udvidelse af rettigheder, hvis en hacker er logget på lokalt og har kørt et særligt udformet program. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte disse sårbarheder. Sårbarhederne kan ikke udnyttes vha. fjernadgang eller af anonyme brugere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206365">MS10-099</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i routing og fjernadgang kan muliggøre udvidelse af rettigheder (2440591)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Routing and Remote Access NDProxy-komponenten i Microsoft Windows. Denne sikkerhedsopdatering er klassificeret som Alvorlig for alle understøttede versioner af Windows XP og Windows Server 2003. Alle understøttede versioner af Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er ikke berørt af sårbarheden.<br />
<br />
Sårbarheden kan muliggøre en udvidelse af rettigheder, hvis en hacker logger på et berørt system og har kørt et særligt udformet program. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes via fjernadgang eller af anonyme brugere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204906">MS10-100</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Consent User Interface kan muliggøre udvidelse af rettigheder (2442962)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Consent User Interface (UI). Sårbarheden kan muliggøre udvidelse af rettigheder, hvis en hacker kører et særligt udformet program på et berørt system. En hacker skal have gyldige logonoplysninger og SeImpersonatePrivilege samt kunne logge på lokalt for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes via fjernadgang eller af anonyme brugere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201319">MS10-101</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Windows-tjenesten Netlogon kan muliggøre Denial-of-Service (2207559)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i tjenesten Netlogon RPC på berørte versioner af Windows Server, som er konfigureret til at fungere som domænecontrollere. Sårbarheden kan muliggøre Denial-of-Service, hvis en hacker sender en særligt udformet RPC-pakke til grænsefladen for tjenesten Netlogon RPC på et berørt system. En hacker skal have administratorrettigheder på en computer, der er tilknyttet det samme domæne som den berørte domænecontroller, for at udnytte denne sårbarhed.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial-of-Service</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=205309">MS10-102</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Hyper-V kan muliggøre Denial-of-Service (2345316)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows Server 2008 Hyper-V og Windows Server 2008 R2 Hyper-V. Sårbarheden kan give mulighed for denial-of-service, hvis en særligt udformet pakke sendes til VMBus af en godkendt bruger i en af de virtuelle gæstcomputere, der hostes af Hyper-V-serveren. En hacker skal have gyldige logonoplysninger og være i stand til at sende særligt udformet indhold fra en virtuel gæstcomputer for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes via fjernadgang eller af anonyme brugere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial-of-Service</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft Office Publisher kan muliggøre fjernudførelse af kode (2292970)</strong><br />
<br />
Denne sikkerhedsopdatering løser fem privat rapporterede sårbarheder i Microsoft Publisher, som kan muliggøre fjernudførelse af kode, når en bruger åbner en særligt udformet Publisher-fil. En hacker, som har held til at udnytte disse sårbarheder, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206469">MS10-104</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft SharePoint kan muliggøre fjernudførelse af kode (2455005)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft SharePoint. Sårbarheden kan muliggøre fjernudførelse af kode i sikkerhedskontekst af en gæstebruger, hvis en hacker har sendt en særligt udformet SOAP-anmodning til startertjenesten for dokumentkonverteringer i et SharePoint-servermiljø, der bruger belastningsjusteringstjenesten for dokumentkonverteringer. Som standard er belastningsjusteringstjenesten for dokumentkonverteringer og startertjenesten for dokumentkonverteringer ikke aktiveret i Microsoft Office SharePoint Server 2007.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft Office Graphics Filters kan muliggøre fjernudførelse af kode (968095)</strong><br />
<br />
Denne sikkerhedsopdatering løser syv privat rapporterede sårbarheder i Microsoft Office. Sårbarhederne kan muliggøre fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet billedfil med Microsoft Office. En hacker, som det lykkes at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den lokale bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204624">MS10-106</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft Exchange Server kan give mulighed for Denial-of-Service (2407132)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Exchange Server. Sårbarheden kan muliggøre denial-of-service, hvis en godkendt hacker sender en særligt udformet netværksmeddelelse til en computer, der kører Exchange-tjenesten. De bedste fremgangsmåder for brug af firewalls og standardkonfigurationer af firewalls kan hjælpe med at beskytte netværk mod angreb, der kommer fra en placering uden for virksomhedsperimeteren. De bedste fremgangsmåder anbefaler, at systemer med forbindelse til internettet har mindst mulig antal åbne porte.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Denial-of-Service</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er anført i faldende rækkefølge i forhold til CVE ID's vurderingsniveau for udnyttelse. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende størrelsesværdi for heapdefekt i pubconv.dll</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2569">CVE-2010-2569</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. heapoverløb i pubconv.dll</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2570">CVE-2010-2570</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206689">MS10-097</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende usikker indlæsning af bibliotek i Internet Connection Signup Wizard</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3144">CVE-2010-3144</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed er blevet offentliggjort</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206738">MS10-096</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende usikker indlæsning af bibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3147">CVE-2010-3147</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed er blevet offentliggjort</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203463">MS10-092</a></td>
<td style="border:1px solid black;">Sårbarhed i Opgavestyring</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3338">CVE-2010-3338</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver udnyttet i Internet-økosystemet.</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt hukommelse i HTML-objekt</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3340">CVE-2010-3340</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt hukommelse i HTML-objekt</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3343">CVE-2010-3343</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt hukommelse i HTML-element</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3345">CVE-2010-3345</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt hukommelse i HTML-element</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3346">CVE-2010-3346</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Win32k-bufferoverflow</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3939">CVE-2010-3939</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed er blevet offentliggjort</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Win32k PFE Pointer Double Free</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3940">CVE-2010-3940</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. markørsammenkædning i Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3943">CVE-2010-3943</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt hukommelse i Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3944">CVE-2010-3944</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende bufferoverløb for FlashPix-billedkonverteringsprogram</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3951">CVE-2010-3951</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. OpenType Font Double Free</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3957">CVE-2010-3957</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. OpenType CMAP-tabel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3959">CVE-2010-3959</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204906">MS10-100</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. repræsentation i Consent UI</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3961">CVE-2010-3961</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt, ikke-initialiseret hukommelse</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3962">CVE-2010-3962</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed bliver i øjeblikket udnyttet i Internet-økosystemet</strong></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206365">MS10-099</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. bufferoverflow for NDProxy-kerne</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3963">CVE-2010-3963</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206469">MS10-104</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. forkert udformet anmodning om udførelse af kode</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3964">CVE-2010-3964</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206699">MS10-094</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende usikker indlæsning af bibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3965">CVE-2010-3965</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed er blevet offentliggjort</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206683">MS10-095</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende usikker indlæsning af BranchCache-bibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3966">CVE-2010-3966</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206698">MS10-093</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende usikker indlæsning af bibliotek</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3967">CVE-2010-3967</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><strong>Denne sårbarhed er blevet offentliggjort</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td style="border:1px solid black;">Defekt hukommelse på grund af ugyldigt indeks til matrix i Pubconv.dll</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2571">CVE-2010-2571</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Win32k Double Free</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3941">CVE-2010-3941</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende Win32k WriteAV</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3942">CVE-2010-3942</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende bufferoverløb for CGM-billedkonverteringsprogram</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3945">CVE-2010-3945</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende heltalsoverløb for PICT-billedkonverteringsprogram</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3946">CVE-2010-3946</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende heapoverløb for TIFF-billedkonverteringsprogram</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3947">CVE-2010-3947</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende bufferoverløb for TIFF-billedkonverteringsprogram</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3949">CVE-2010-3949</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende defekt hukommelse i TIFF-billedkonverteringsprogram</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3950">CVE-2010-3950</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende heapdefekt for FlashPix-billedkonverteringsprogram</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3952">CVE-2010-3952</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt hukommelse ved array-indeksering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3955">CVE-2010-3955</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td style="border:1px solid black;">Sårbarhed vedrørende OpenType Font-indeks</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3956">CVE-2010-3956</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201319">MS10-101</a></td>
<td style="border:1px solid black;">DOS-sårbarhed vedr. fjernelse af reference til Null i Netlogon RPC</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2742">CVE-2010-2742</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er kun en Denial-of-Service-sårbarhed</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204624">MS10-106</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. uendelig løkke i Exchange Server</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3937">CVE-2010-3937</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er kun en Denial-of-Service-sårbarhed</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt Microsoft Publisher-hukommelse</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3954">CVE-2010-3954</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=205309">MS10-102</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Hyper-V VMBus</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3960">CVE-2010-3960</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Dette er kun en Denial-of-Service-sårbarhed</td>
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
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="14" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
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
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6031d98a-cd0f-4dd8-80b6-70a7167e9e55">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=922a0835-7f69-4e37-a9f7-c64e976e3513">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a55b8029-9499-4219-99b7-65c30b0b864a">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdef3358-ad3e-40a6-9ba5-3be220a56a65">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1">Windows Media Encoder 9 x86</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46baa431-126c-4fa5-9a7b-525008e2817d">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa9a1aac-b9c5-4d4e-9083-a080ad4ccc6f">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb9d1657-5beb-4372-b74c-a612a6fff5a8">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d0ae558-a4f2-4048-b5fd-ba072ca35e48">Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d3a5678-77f8-4ebc-8775-aedd25ef0eb8">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7c826b0-4aac-41ce-b297-6b6e11105c14">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5207bf5-7e58-4001-aa8f-f9a4b2c037d8">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=070fef8e-ba09-40f4-abaa-9cebf08983c3">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d">Windows Media Encoder 9 x86</a>
                    <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75">Windows Media Encoder 9 x64</a><br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9ce9d62-2eaa-48d8-bb6d-ea137e63d077">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6dabc306-c858-46b1-815c-cd8d011ff62e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f277ae4-4f85-4c8a-bfc5-dcdc8afed133">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=238bb885-eae6-464a-bb3d-679025f1cb50">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="14" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
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
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f1f41fb-368a-42e6-8d17-fca83b64f57b">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a3b57d26-5551-4785-86cf-41b532d78979">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f5a3677-0990-4702-bf08-af64cf12cb6c">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b70334c-490d-446c-988a-a88a75595fd4">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1">Windows Media Encoder 9 x86</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0b2837c-019b-419b-954d-5bdc71a3a332">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8fa2cfa4-a01d-4910-b69f-736aeb585bab">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aa39f59-2177-459f-9b8a-9543330d48ec">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c87af292-a068-4089-aab8-115c18b4b024">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad843b97-2f6e-4406-a17a-627b7db8a926">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a9f56a0-230a-4dde-94da-f051ebf51f47">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b0d2a3a-7fed-4d48-9ec5-8558000e51bb">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e134e5d-84fb-432b-99b1-593b1be5d5a4">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08328e82-b012-4ea5-bf89-becb4881084f">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d">Windows Media Encoder 9 x86</a>
                    <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75">Windows Media Encoder 9 x64</a><br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c5cb600-9a39-40a0-be42-1593b1e0b97d">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17b0b340-73b2-42a7-9d86-1297c63dcc2b">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bca61d61-d5cf-49a4-ab99-b61e50e8f619">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e17b8878-d065-49cc-bdba-0f24cdf35ea3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b0a06e7-0ae5-41f4-9ff5-d524fc0afbfa">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c1cf126-604c-4f70-bbe8-aa4d145eb68f">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96884bfa-00c8-4263-9936-d7c054919dd3">Internet Explorer 7</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=15588d6a-f576-4e3d-95e8-d422af8a94de">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9abc8270-f3ac-474d-9ebc-410aaa6262cc">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04a178cc-1afd-4e47-8cab-05e402e5a568">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4fce129d-2b4e-4a66-af27-bbbde1e65ba1">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad896d80-167f-4e8f-a448-cac93516f4d0">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c0c2850-e81d-4347-aeb3-47036caa7c1b">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="14" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
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
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=897351de-9697-4954-aa7e-169e980b932c">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bebf0df0-5ebe-44b4-9ace-b3085a993e58">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ddb8a06-c9cc-4d33-b6d1-22dbda2d871f">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48f10251-34d8-4149-b4b2-bf3ec28f5846">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55141a02-3ad3-4691-98b9-80dd8ecb14c5">Movie Maker 2,6</a>
                    [1]
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8a57950-43cd-486f-bd97-70b0ad360a0b">Windows Media Encoder 9 x86</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1c7f1b5-e054-4cd6-857d-2ab0a2fe9f62">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b824d3b9-2ce1-4abc-ae06-68aef1250be9">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85265a23-5094-4007-8d33-f402cabd1664">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=171c02f9-f7d2-42f2-ba31-4c819a43784a">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=837b6056-af04-4aed-8afe-cc392770a590">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a245f3c-ffb6-4ccd-956c-e7d1231fca30">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=099ccc5f-b92f-4d06-bcb5-92e35c49f613">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b078136-a492-4a2e-939d-82799f774d82">Movie Maker 2,6</a>
                    [1]
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f98c3b96-acb5-49f1-be42-3dd44d316408">Windows Media Encoder 9 x86</a>
                    <br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1054088-f484-4f44-ba0e-5cbd21773c0c">Windows Media Encoder 9 x64</a><br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73624b68-a69d-4517-b971-f0b7d2ccc9d6">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4c42cfe-b7f2-4436-919e-4bd305a3439a">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63c7257a-16bf-4108-80b9-9dfe53528348">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="14" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
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
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3785f3b-64c6-46a4-8e3a-9b9448124a8f">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98183a76-5642-4e19-b488-029eb7ed3942">Internet Explorer 8</a>**<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87149ec2-74a8-4dea-b7e3-873558e0103e">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bdc9564a-4091-4cde-963a-239513db6c17">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a4ea028f-edfc-4237-8325-7ece11fcf437">Windows Media Encoder 9 x86</a>**<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=118f528f-bd05-49c2-a4a4-78314cd00992">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2 </a>**<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e2f572a-4169-47f2-a872-5466997122ed">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14e079a8-01a4-47c9-bd47-f5c9a6ca070a">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2 </a>**<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6793f75b-cdf4-42ef-a53e-a1acb5b662d1">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b81aae5-6034-4c83-b5d2-e7e472435284">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d47b457d-e995-4a7e-9bfa-eebab9b3a729">Internet Explorer 8</a>**<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=523a47d3-771d-471a-889b-16311c276a00">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dff39bfe-0799-4912-ae22-392562178ae6">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f468d2b5-f02c-4691-9fb5-a7f69752f126">Windows Media Encoder 9 x86</a>**<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=533d91d8-0291-421e-9701-3bd86d18bc45">Windows Media Encoder 9 x64</a>**<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77e288fb-b51f-4f57-baac-1443d8fbd37b">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>**<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09a4b646-989d-43ef-a3e8-64af8b380a14">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6baf92b7-a336-45f2-a1ba-c00c34dfb76f">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>**<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85add876-ca5a-4a92-984e-188a72e349fc">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c06bbc-6e84-4cf1-89f0-c0d34cfffaed">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ddafaaf-84a0-4325-b06f-4aac7cd61274">Internet Explorer 7</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=959146ee-0e70-4e56-9012-72ed59aeb24b">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf341a35-32ea-4ff7-aca9-1a4683c100ee">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82f71194-6f1f-4f43-8752-4bf5e5f94a93">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46522323-837e-4a74-9cf0-45f69343e776">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a4b23d4-f68e-4d5b-8814-d9247145f164">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="14" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows 7 Beta til 32-bit-systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c288fe87-b113-4615-9b02-5e388bcb5241">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ff590db8-4264-42ba-9e07-88d100e1c4f5">Windows 7 til 32-bit-systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf85cdb6-58c7-4144-82f6-f01a6a4f9c3a">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75591d37-2cb8-4cdf-acbb-89cd0d1a9290">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e8ad5cd-af27-4f00-9378-ad778b8ee7b3">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa7de2e4-ba48-4d58-b034-05349f0eb920">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7c7d57a-d031-46a3-9613-eae2b9cb6401">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 til x64-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2cf4ac70-88b4-4840-9895-2bcf119312a7">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ea4e339-9db2-4b99-b567-80ee55ecdf92">Windows 7 til x64-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0597018d-39f5-4ca9-b437-63d9e68f264d">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a0c4dd0-98b4-4e7a-99ed-22b9d9f76cd1">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35a3e821-b463-411c-858b-d01eb5aed42b">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b21db627-91c2-4ebf-b7c0-38ac58ae5b6c">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e52c36f5-637b-4928-83d0-27514c6cc384">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="14" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
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
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 til x64-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99a91ba7-035b-4717-ada5-c1ad6645db64">Internet Explorer 8</a>**<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e52f7869-474a-44c8-a102-e766c576fc01">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28c832fb-4937-4652-8799-eab6c76d05fb">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f58a765f-cea9-456d-b0ab-bfc70b109cbf">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e2c95f6-9381-4484-b11b-814ab9138118">Windows Server 2008 R2 til x64-baserede systemer</a>**<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d417ebce-7841-4bbb-8abc-b15ef5f4b733">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b823a7aa-0eb9-42dd-bf56-8907d94b314a">Windows Server 2008 R2 til x64-baserede systemer</a>**<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7307afd-84a0-434e-9658-bf9f8ae4b938">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39b7abc7-65a4-4dfd-92ba-c638e3de1118">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c26de145-94b8-404a-b946-744988fab83b">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a21d061a-794a-4012-b3cd-c67445c074f5">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ad64d5c-2d81-4ac8-934e-8917b2fcf961">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13a9f838-ac07-43dc-9aee-a77207998e1e">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb4211f3-1082-4245-8f03-7cbac90e9a31">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7eeac1bb-9f86-4ea5-b30f-980d52be5044">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66b2506d-80e0-4e32-86e6-0908ef56ae90">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkninger til MS10-093**

\[1\]Windows Movie Maker 2.6 er en valgfri download, der kan installeres på de anførte operativsystemer.

#### Micorsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office-pakker og komponenter</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=198156">
                      <strong>MS10-103</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147425">
                      <strong>MS10-105</strong>
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
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f540692c-e404-4383-8937-4d6a36475da5">Microsoft Publisher 2002 Service Pack 3</a>
                    <br />(KB2284692)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=724d0ad6-ba5f-4dbf-b280-3fb36335d33b">Microsoft Office XP Service Pack 3</a>
                    <br />(KB2289162)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e600de65-3e9d-4e37-8906-8b7091ff523e">Microsoft Publisher 2003 Service Pack 3</a>
                    <br />(KB2284695)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=976857e9-77fc-4667-88ca-7637e57536cd">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB2289163)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2007 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79275011-bdc1-446a-8ea6-56fc31bd9c35">Microsoft Publisher 2007 Service Pack 2</a>
                    <br />(KB2284697)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=676eeed6-f2b7-4265-afc7-a82ffdbeb290">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2288931)<br />(Ingen alvorlighedsklassifikation[1])</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2010 (32-bit-versioner)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99e18990-75e9-497e-9b4f-5d7ef8656ab2">Microsoft Publisher 2010 (32-bit-versioner)</a>
                    <br />(KB2409055)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6d644494-b530-4b37-bc37-8a8a7edefe53">Microsoft Office 2010 (32-bit-versioner)</a>
                    <br />(KB2289078)<br />(Ingen alvorlighedsklassifikation[1])</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2010 (64-bit-versioner)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b27ee11-e563-4152-9691-25eec1ee9966">Microsoft Publisher 2010 (64-bit-versioner)</a>
                    <br />(KB2409055)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58e54779-aa8f-41b3-9993-8cec12c49082">Microsoft Office 2010 (64-bit-versioner)</a>
                    <br />(KB2289078)<br />(Ingen alvorlighedsklassifikation[1])</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Anden Office Software</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=198156">
                      <strong>MS10-103</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147425">
                      <strong>MS10-105</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Converter Pack</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dcded2ee-0673-4afe-abe6-04941a2ad306">Microsoft Office Converter Pack</a>
                    <br />(KB2456849)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Works 9</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=10f6f330-05d8-4b60-9ebb-822a7321ac0f">Microsoft Works 9</a>
                    <br />(KB2431831)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til MS10-105**

\[1\]Klassifikationer gælder ikke for denne opdatering, idet sårbarhederne, der er beskrevet i denne bulletin, ikke påvirker denne software. Som en gennemgribende forholdsregel til beskyttelse mod eventuelle nye vektorer, der identificeres i fremtiden, anbefaler Microsoft imidlertid, at kunder, der har denne software, anvender denne sikkerhedsopdatering.

#### Microsoft Server-software

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="3" style="border:1px solid black;">Microsoft SharePoint Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206469">
                      <strong>MS10-104</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204624">
                      <strong>MS10-106</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bit versioner)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c8fb9f9-7920-43ea-b618-e26dc3360c60">Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bit versioner)</a>
                    <br />(KB2433089)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 Service Pack 2 (64-bit versioner)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db09280-24bd-42e0-9ae3-02c9bf3e8ee3">Microsoft Office SharePoint Server 2007 Service Pack 2 (64-bit versioner)</a>
                    <br />(KB2433089)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Exchange Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206469">
                      <strong>MS10-104</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204624">
                      <strong>MS10-106</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Exchange Server 2007 Service Pack 2 til x64-baserede systemer</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b983156-9e9f-4d29-9e9b-2369747e3b62">Microsoft Exchange Server 2007 Service Pack 2 til x64-baserede systemer</a>
                    <br />(KB2407132)<br />(Moderat)</td></tr>
              </table>


## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

For kunder med Microsoft Office til Mac, kan Microsoft AutoUpdate til Mac hjælpe med til at holde Microsoft-software opdateret. Se [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) for at få flere oplysninger om brug af Microsoft AutoUpdate til Mac

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Vejledning i registrering og implementering**

Microsoft giver vejledning i registrering og implementering af sikkerhedsopdateringer. Denne vejledning indeholder anbefalinger og oplysninger, som it-fagfolk kan bruge til bedre at forstå, hvordan de skal anvende forskellige værktøjer til registrering og implementering af sikkerhedsopdateringer. Yderligere oplysninger finder du i [Microsoft Knowledge Base-artiklen 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) giver administratorer mulighed for at søge på lokale systemer og fjernsystemer efter manglende sikkerhedsopdateringer samt almindelige fejl ved sikkerhedskonfigurationer. Hvis du ønsker yderligere oplysninger om MBSA, kan du besøge webstedet [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Microsoft Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

**SystemCenter Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse opgave, det er at levere og administrere opdateringer af it-systemer på tværs af virksomheden. Med Configuration Manager 2007 kan it-administratorer levere opdateringer af Microsoft-produkter til en række enheder, herunder stationære og bærbare computere, servere og mobile enheder.

Den automatiserede sårbarhedsvurdering i Configuration Manager 2007 opdager behov for opdateringer og rapporterer om anbefalede forholdsregler. Software Update Management i Configuration Manager 2007 er bygget på Microsoft Windows Software Update Services (WSUS), en gennemprøvet opdateringsinfrastruktur, der er kendt af it-administratorer verden over. Se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) for at få flere oplysninger om, hvordan administratorer kan bruge Configuration Manager 2007 til at implementere opdateringer. Yderligere oplysninger om Configuration Manager findes i [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere.

**Bemærk** System Management Server 2003 er uden for generel support fra 12. januar 2010. Du kan få yderligere oplysninger om produktlivscyklussen på . Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig; se det tidligere afsnit, **SystemCenter Configuration Manager 2007**.

Yderligere oplysninger om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsopdateringer, findes i [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Oplysninger om SMS findes på [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Bemærk** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til at installere disse opdateringer.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Opdateringer skriver ofte til de samme filer og registreringsdatabaseindstillinger, der er nødvendige for, at dine programmer kan køre. Dette kan udløse inkompatibilitet og forøge den tid, det tager at implementere sikkerhedsopdateringer. Du kan strømline test og validering af Windows-opdateringer mod installerede programmer med de [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponenter, der følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Microsoft Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede vigtige opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Opdateringer fra de foregående måneder for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Viser alle nye, reviderede og udgivne opdateringer til Microsoft-produkter udover Microsoft Windows.

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

  - Aniway fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem, der er beskrevet i MS10-090
  - Nicolas Joly fra [VUPEN Vulnerability Research Team](http://www.vupen.com/) for at rapportere et problem beskrevet i MS10-090
  - Stephen Fewer, der samarbejder med [Tipping Point](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS10-090
  - [Peter Vreugdenhi](http://vreugdenhilresearch.nl/), der samarbejder med [TippingPoint's](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS10-090
  - [Yosuke Hasegawa](http://utf-8.jp/) for at arbejde sammen med os om et problem, der er beskrevet i MS10-090
  - Jose Antonio Vazquez Gonzalez fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at rapportere et problem beskrevet i MS10-090
  - Marc Schoenefeld fra [Red Hat Security Response Team](https://www.redhat.com/security/team/), der samarbejder med [Opera Security Team](http://www.opera.com/security/), for at rapportere et problem, der er beskrevet i MS10-091
  - Marc Schoenefeld fra [Red Hat Security Response Team](https://www.redhat.com/security/team/) for at have rapporteret et problem, der er beskrevet i MS10-091
  - Paul-Kenji Cahier Furuya for at rapportere et problem, der er beskrevet i MS10-091
  - Sergey Golovanov, Alexander Gostev, Maxim Golovkin og Alexey Monastyrsky fra [Kaspersky Lab](http://usa.kaspersky.com/) og Vitaly Kiktenko og Alexander Saprykin fra [Design and Test Lab](http://www.dnt-lab.com/) for at have rapporteret et problem, der er beskrevet i MS10-092
  - Liam O Murchu fra [Symantec](http://www.symantec.com/index.jsp) for at rapportere et problem beskrevet i MS10-092
  - Alexandr Matrosov, Eugene Rodionov, Juraj Malcho og David Harley fra [ESET](http://www.eset.com/) for at rapportere et problem, der er beskrevet i MS10-092
  - Haifei Li fra [Fortinet’s FortiGuard Labs](http://www.fortiguard.com/) for at have rapporteret et problem, der er beskrevet i MS10-095
  - Simon Raner fra [ACROS Security](http://www.acrossecurity.com/) for at have rapporteret et problem, der er beskrevet i MS10-096
  - HD Moore fra [Rapid7](http://www.rapid7.com/) for at rapportere et problem beskrevet i MS10-096
  - Muhaimin Dzulfakar fra [NGSSoftware](http://www.ngssoftware.com/) for at have rapporteret et problem, der er beskrevet i MS10-096
  - Muhaimin Dzulfakar fra [NGSSoftware](http://www.ngssoftware.com/) for at rapportere et problem, der er beskrevet i MS10-097
  - Tarjei Mandt fra [Norman](http://www.norman.com/) for at rapportere et problem, der er beskrevet i MS10-098
  - Stéfan Le Berre fra [Sysdream](http://www.sysdream.com/) for at rapportere et problem, der er beskrevet i MS10-098
  - Honggang Ren fra [Fortinet’s FortiGuard Labs](http://www.fortiguard.com/) for at rapportere et problem, der er beskrevet i MS10-099
  - Cesar Cerrudo fra [Argeniss](http://www.argeniss.com/) for at rapportere et problem, der er beskrevet i MS10-100
  - Matthias Dieter Wallnöfer og Andrew Bartlett fra The Samba Team for at rapportere et problem, der er beskrevet i MS10-101
  - [HP](http://www.hp.com/) og [techit](http://www.techit.de/) for at rapportere et problem, der er beskrevet i MS10-102
  - Chaouki Bekrar fra [VUPEN Vulnerability Research Team](http://www.vupen.com/) for at rapportere fem problemer, der er beskrevet i MS10-103
  - Oleksandr Mirosh, der samarbejder med [TippingPoint's](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem, der er beskrevet i MS10-104
  - Yamata Li fra [Palo Alto Networks](http://www.paloaltonetworks.com/) for at rapportere et problem, der er beskrevet i MS10-105
  - Alin Rad Pop fra [Secunia Research](http://secunia.com/) for at rapportere et problem, der er beskrevet i MS10-105
  - Carsten Eiram fra [Secunia Research](http://secunia.com/) for at rapportere tre problemer, der er beskrevet i MS10-105.
  - Dyon Balding fra [Secunia Research](http://secunia.com/) for at rapportere to problemer, der er beskrevet i MS10-105.
  - Oleksandr Mirosh, der samarbejder med [TippingPoint's](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem, der er beskrevet i MS10-106

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (14. december 2010): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

