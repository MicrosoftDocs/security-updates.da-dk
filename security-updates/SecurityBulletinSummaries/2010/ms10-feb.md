---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for februar 2010
TOCTitle: MS10-FEB
ms:assetid: ms10-feb
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms10-feb(v=Security.10)
ms:contentKeyID: 61224063
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for februar 2010

Offentliggjort: 9. februar 2010 | Opdateret: 10. februar 2010

**Version:** 1.1

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for februar 2010.

Med udgivelsen af bulletiner for februar 2010 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort 4. februar 2010. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://technet.microsoft.com/security/bulletin/advance).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner 10. februar 2010 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få februar måneds sikkerhedsbulletin-webcast](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032427679&culture=en-us). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og](http://technet.microsoft.com/security/bulletin/summary)webcasts.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=178850">MS10-006</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i SMB-klienten kan give mulighed for fjernudførelse af kode (978251)</strong><br />
<br />
Denne sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Windows. Sårbarheden kan give mulighed for fjernudførelse af kode, hvis en hacker sender et særligt udformet SMB-svar til en SMS-anmodning, der er iværksat af klienten. Hvis en hacker skal udnytte disse sårbarheder, skal vedkommende overbevise brugeren om at starte en SMB-forbindelse til en ondsindet SMB-server.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179067">MS10-007</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Windows Shell-handleren kan tillade fjernudførelse af kode (975713)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows 2000, Windows XP og Windows Server 2003. Øvrige versioner af Windows er ikke berørt af denne sikkerhedsopdatering. Sårbarheden kan muliggøre fjernudførelse af kode, hvis et program, f.eks. en webbrowser, sender specielt udformede data videre til funktionen ShellExecute API via Windows Shell-handleren.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179106">MS10-008</a></td>
<td style="border:1px solid black;"><strong>Samlet sikkerhedsopdatering af kill-bitter for ActiveX (978262)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft-software. Denne sikkerhedsopdatering er klassificeret som Kritisk for alle understøttede versioner af Microsoft Windows 2000 og Windows XP, Alvorlig for alle understøttede versioner af Windows Vista og Windows 7, Moderat for alle understøttede versioner af Windows Server 2003 og Lav for alle understøttede versioner af Windows Server 2008 og Windows Server 2008 R2.<br />
<br />
Denne sårbarhed kan muliggøre fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside, der aktiverer et ActiveX-objekt i Internet Explorer. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Denne opdatering omfatter også killbitter til fire ActiveX-objekter fra tredjepart.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167190">MS10-009</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Windows TCP/IP kan muliggøre fjernudførelse af kode (974145)</strong><br />
<br />
Denne sikkerhedsopdatering løser fire privat rapporterede sårbarheder i Microsoft Windows. De mest alvorlige af disse sårbarheder kan tillade fjernudførelse af kode, hvis særligt udformede pakker sendes til en computer, mens IPv6 er aktiveret. En hacker kan forsøge at udnytte sårbarheden ved at oprette særligt udformede ICMPv6-pakker til et system, hvor IPv6 er aktiveret. Denne sårbarhed kan kun udnyttes, hvis hackeren er on-link.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167321">MS10-013</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft DirectShow kan muliggøre fjernudførelse af kode (977935)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft DirectShow. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet AVI-fil. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=178812">MS10-003</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft Office (MSO) kan muliggøre fjernudførelse af kode (978214)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Office, som kan muliggøre fjernudførelse af kode, når en bruger åbner en særligt udformet Office-fil. En hacker, som har held til at udnytte denne sårbarhed, kan få fuld kontrol over et berørt system. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163639">MS10-004</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Microsoft Office PowerPoint kan muliggøre fjernudførelse af kode (975416)</strong><br />
<br />
Denne sikkerhedsopdatering løser seks privat rapporterede sårbarheder i Microsoft Office PowerPoint. Disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet PowerPoint-fil. Derefter vil det være muligt for hackeren at installere programmer, se, ændre eller slette data, eller oprette nye konti med komplette brugerrettigheder. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179066">MS10-010</a></td>
<td style="border:1px solid black;"><strong>Sårbarhed i Windows Server 2008 Hyper-V kan give mulighed for Denial-of-Service (977894)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Windows Server 2008 Hyper-V og Windows Server 2008 R2 Hyper-V. Sårbarheden kan give mulighed for denial-of-service, hvis en forkert udformet sekvens af maskininstruktioner køres af en godkendt bruger i en af de virtuelle gæstcomputere, der hostes af Hyper-V-serveren. En hacker skal have gyldige logonoplysninger og kunne logge på en virtuel gæstcomputer for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes via fjernadgang eller af anonyme brugere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial-of-Service</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179798">MS10-011</a></td>
<td style="border:1px solid black;"><strong>Sårbarhed i Windows Client/Server Run-time Subsystem kan give mulighed for udvidelse af rettigheder (978037)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows Client/Server Run-time Subsystem (CSRSS) i Microsoft Windows 2000, Windows XP og Windows Server 2003. Øvrige versioner af Windows er ikke berørt. Denne sårbarhed kan give mulighed for udvidelse af rettigheder, hvis en hacker logger på systemet og starter et særligt udformet program, der er designet til at blive ved med at køre, efter at hackeren logger af. En hacker skal have gyldige logonoplysninger og kunne logge på lokalt for at udnytte denne sårbarhed. Sårbarheden kan ikke udnyttes af anonyme brugere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155976">MS10-012</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i SMB-server kan give mulighed for fjernudførelse af kode (971468)</strong><br />
<br />
Denne sikkerhedsopdatering løser flere privat rapporterede sårbarheder i Microsoft Windows. De mest alvorlige af disse sårbarheder kan give mulighed for fjernudførelse af kode, hvis en hacker har oprettet en særligt udformet SMB-pakke og sendt pakken til et påvirket system. De bedste fremgangsmåder for brug af firewall og standardkonfigurationer af firewall kan hjælpe med at beskytte netværk mod angreb, der kommer fra en placering uden for virksomhedsperimeteren, og som vil forsøge at udnytte disse sårbarheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=181196">MS10-014</a></td>
<td style="border:1px solid black;"><strong>Sårbarhed i Kerberos kan give mulighed for Denial-of-Service (977290)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan give mulighed for denial-of-service, hvis en særligt udformet anmodning om fornyelse af brugertilladelse sendes til Windows Kerberos-domænet fra en godkendt bruger på et pålideligt ikke-Windows Kerberos-område. Denial-of-service kan fortsætte, indtil domænecontrolleren genstartes.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Denial-of-Service</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179062">MS10-015</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Windows Kernel kan tillade udvidelse af rettigheder (977165)</strong><br />
<br />
Denne sikkerhedsopdatering løser en offentliggjort og en privat rapporteret sårbarhed i Microsoft Windows. Sårbarhederne kan tillade en udvidelse af rettigheder, hvis en hacker er logget på systemet og har kørt et særligt udformet program. Hvis en hacker skal udnytte begge sårbarheder, skal vedkommende have gyldige logonoplysninger og være i stand til at logge på lokalt. Sårbarhederne kan ikke udnyttes vha. fjernadgang eller af anonyme brugere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=180620">MS10-005</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft Paint kan muliggøre fjernudførelse af kode (978706)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Paint. Sårbarheden kan give mulighed for fjernudførelse af kode, hvis en bruger har fået vist en særligt udformet JPEG-billedfil ved hjælp af Microsoft Paint. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er anført i faldende rækkefølge i forhold til CVE ID's vurderingsniveau for udnyttelse.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=178850">MS10-006</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. SMB-klients race condition</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0017">CVE-2010-0017</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Fjernangrebsvektor kan muliggøre DoS. Lokal angrebsvektor kan muliggøre EoP</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179798">MS10-011</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. lokal udvidelse af CSRSS-rettigheder</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0023">CVE-2010-0023</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Hacker og offer skal logge på den samme konsol</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179067">MS10-007</a></td>
<td style="border:1px solid black;">Sårbarhed ved URL-validering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027">CVE-2010-0027</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163639">MS10-004</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. PowerPoint LinkedSlideAtom-masseoverflow</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0030">CVE-2010-0030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163639">MS10-004</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. PowerPoint OEPlaceholderAtom &quot;placementId&quot;-ugyldig array-indeksering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0031">CVE-2010-0031</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163639">MS10-004</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. brug efter PowerPoint OEPlaceholder Atom Free</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0032">CVE-2010-0032</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163639">MS10-004</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. PowerPoint Viewer TextBytesAtom Record-stakoverflow</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0033">CVE-2010-0033</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Sårbarheden påvirker kun PowerPoint Viewer 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163639">MS10-004</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Office PowerPoint Viewer TextCharsAtom Record-stakoverflow</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0034">CVE-2010-0034</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Sårbarheden påvirker kun PowerPoint Viewer 2003</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155976">MS10-012</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. manglende entropi for SMB NTLM-godkendelse</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0231">CVE-2010-0231</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179062">MS10-015</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Windows Kernel Exception Handler</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0232">CVE-2010-0232</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=178812">MS10-003</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. MSO.DLL-bufferoverflow</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0243">CVE-2010-0243</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167321">MS10-013</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. DirectShow-masseoverflow</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0250">CVE-2010-0250</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Konsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=178850">MS10-006</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. SMB-klientpooldefekt</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0016">CVE-2010-0016</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155976">MS10-012</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. overfloww i SMB-stinavn</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0020">CVE-2010-0020</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155976">MS10-012</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. defekt SMB-hukommelse</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0021">CVE-2010-0021</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=180620">MS10-005</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. heltaloverflow i MS Paint</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0028">CVE-2010-0028</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Succesfuld udnyttelse kræver markant brugerinteraktion</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163639">MS10-004</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. bufferoverflow for filstihåndtering i PowerPoint</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0029">CVE-2010-0029</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179062">MS10-015</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Windows Kernel Double Free</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0233">CVE-2010-0233</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167190">MS10-009</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. ICMPv6 Router Advertisement</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0239">CVE-2010-0239</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Udnyttelse kræver, at hackeren er på samme link som målværten</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167190">MS10-009</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Header MDL-fragmentering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0240">CVE-2010-0240</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Sårbarhed kræver en netværksdriver fra en tredjepart</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167190">MS10-009</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. ICMPv6-routerinformation</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0241">CVE-2010-0241</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Udnyttelse kræver, at hackeren er på samme link som målværten</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=155976">MS10-012</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. SMB Null Pointer</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0022">CVE-2010-0022</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179066">MS10-010</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. validering af Hyper-V-instruktionssæt</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0026">CVE-2010-0026</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Sårbarhed kan tillade en tilstand med udelukkende DoS</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=181196">MS10-014</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Kerberos Null Pointer Dereference</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0035">CVE-2010-0035</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Udelukkende DoS. Udnyttelse er kun mulig på domænecontrollere i en ikke-standardiseret konfiguration</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=167190">MS10-009</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. selektiv TCP-/IP-anerkendelse</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0242">CVE-2010-0242</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Fungerende exploit-kode usandsynlig</td>
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
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="12" style="border:1px solid black;">Microsoft Windows 2000</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178850">
                      <strong>MS10-006</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179067">
                      <strong>MS10-007</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179106">
                      <strong>MS10-008</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167190">
                      <strong>MS10-009</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167321">
                      <strong>MS10-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179066">
                      <strong>MS10-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179798">
                      <strong>MS10-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155976">
                      <strong>MS10-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=181196">
                      <strong>MS10-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179062">
                      <strong>MS10-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=180620">
                      <strong>MS10-005</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
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
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80b49bab-6c2f-48a8-a901-ca3f76e4fe6b">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92234237-a8eb-4ce4-bc5e-cd86feb7dbd3">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=543dc6a7-fa76-4ba9-81e4-25fdf2013548">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba110440-10ce-40a0-884a-8b9afd45a3e3">AVI-filter</a>
                    <br />(KB977914)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16787c93-2c95-4c13-8492-be1db9d18146">Quartz</a><br />(KB975560)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59a8bc19-02bb-4800-bac1-464f59e1cb7b">Quartz i DirectX 9.0</a>[1]<br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=456185b5-57d1-4fa5-a4a9-5b2006ede3ad">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=267ce982-54a0-418f-ad52-e4963610f714">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=56a9afba-a6ee-4fb9-ba85-e51d9f94de27">Microsoft Windows 2000 Server Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed8ac6a5-c8bb-4ed4-8994-810e9a1863c3">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5861705-8f49-45cb-8a92-cf052ccf4134">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="12" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178850">
                      <strong>MS10-006</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179067">
                      <strong>MS10-007</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179106">
                      <strong>MS10-008</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167190">
                      <strong>MS10-009</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167321">
                      <strong>MS10-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179066">
                      <strong>MS10-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179798">
                      <strong>MS10-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155976">
                      <strong>MS10-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=181196">
                      <strong>MS10-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179062">
                      <strong>MS10-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=180620">
                      <strong>MS10-005</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
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
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6c4472e-385c-4412-bda9-c2e615e50713">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8e7bf17-a037-4200-9ae2-2280b19766a4">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7bcf3945-0552-478e-b7f3-bbca97dd1b5d">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a9beb2bd-e5f6-43f9-bbcc-a2afee5e5ceb">AVI-filter</a>
                    <br />(KB977914)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ab53be3-3f42-4e61-a2bc-3ed41d8736ff">Quartz</a><br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9234b40-1b1c-498b-90d4-0bff347b36ee">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f7adee3-e68e-41b3-b835-d84691774f31">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2b348f5-ec8d-4782-bb03-5de550adea77">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b2e70df6-7728-4fc3-8df7-8ddb9ba5202f">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63e15ff0-73b3-46c9-96f8-c18977d35a10">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8d83f30-9cd7-4d6b-b2b9-65d0a483cb9c">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25ef97e8-e76e-44c2-953c-f94cbac552cf">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dedc3010-a989-45f7-b9d4-f7079db3e572">AVI-filter</a>
                    <br />(KB977914)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7543e819-cd36-4e89-9850-60f00c50999d">Quartz</a><br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f83bf7a-e16c-404a-89bd-f65843938299">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91ee57f2-81e5-49bd-bdfc-d3e385efc8a5">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e534d00c-6ddc-4eb3-9464-5db6e90afa3e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8c4acc8-c2f4-41f7-9b32-e7bd791e0155">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="12" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178850">
                      <strong>MS10-006</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179067">
                      <strong>MS10-007</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179106">
                      <strong>MS10-008</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167190">
                      <strong>MS10-009</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167321">
                      <strong>MS10-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179066">
                      <strong>MS10-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179798">
                      <strong>MS10-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155976">
                      <strong>MS10-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=181196">
                      <strong>MS10-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179062">
                      <strong>MS10-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=180620">
                      <strong>MS10-005</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
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
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feb8c145-7c30-45fa-a6f0-8b6453ddd521">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5cb2e203-18fb-4887-a1c9-289d86b8ba11">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29ff72f7-1663-4f35-a794-2dfe3c17b39c">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cc5150d7-070e-4a87-9c02-d050a8cb2204">AVI-filter</a>
                    <br />(KB977914)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=983c5484-6321-4765-97ec-8d42d42d1f70">Quartz</a><br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c8c4eec-255e-41d5-b1e6-f0204edcb46f">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d18cbc4-ac48-458c-8aa3-90708fd854ff">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=738e2fda-96fc-413d-a5c7-74b1fac1d6b3">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=defd8603-ed9b-42f9-a539-2b6a690e9575">Windows Server 2003 Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1efbe73-fc87-4e6a-8b36-81f125a27aec">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=36d88c1b-814c-4371-9ed2-d4576f419fc3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90360537-9311-45e2-8047-9a971f90c3c3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4a97bb7-4f74-4884-9a6e-7a4df9c540fb">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=db13e99b-2f2a-4474-8d6e-271b025bd07f">AVI-filter</a>
                    <br />(KB977914)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7dc20252-6091-407b-befc-c25e8f5d3fb0">Quartz</a><br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de0186f6-27a2-4226-b8eb-f2912710f072">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d63c95e-311a-446f-8852-dffd217a89f6">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8ad539d-8191-4864-977b-ad4e31c04ba0">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9873c962-9d3d-46ef-b54b-2a50696fb6b2">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9143e435-f0d6-464b-9273-4d1f38f8ff3a">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=622442b0-cffe-4fc2-94a8-edff9d71ecd3">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d695ca9f-a1db-4c0f-94b6-7112861c28da">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b84f0be4-6d11-4b07-bb3c-2c76ae9ceea8">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aec66173-e2c6-4c39-8d60-8fbef6d7b764">AVI-filter</a>
                    <br />(KB977914)<br />(Alvorlig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1a7533a-913f-4054-b579-489a257bae5f">Quartz</a><br />(KB975560)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87732f7a-9339-43bc-a4e8-3da849f35b70">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee7f8cc4-f7fd-4dc7-808c-436204ee80cb">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d549c927-add7-4d83-bfc7-15dc35663dfb">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3c21225-8534-4c7f-96b6-20a743dcea74">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee603435-26af-4ab9-9f22-92734346dc0a">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="12" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178850">
                      <strong>MS10-006</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179067">
                      <strong>MS10-007</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179106">
                      <strong>MS10-008</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167190">
                      <strong>MS10-009</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167321">
                      <strong>MS10-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179066">
                      <strong>MS10-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179798">
                      <strong>MS10-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155976">
                      <strong>MS10-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=181196">
                      <strong>MS10-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179062">
                      <strong>MS10-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=180620">
                      <strong>MS10-005</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1902fc93-0f4b-4261-9da3-17d1931daf2e">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c897ddd-f441-41d4-b5b4-d794cfc96e6b">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71f03946-622c-4403-b94f-f6a3de18a8c3">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7130ce0f-df38-4c96-ac54-cdbff35f03e7">Quartz</a>
                    <br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16494dac-553a-4de9-b751-0d6b51cb43f0">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2761c7b4-d472-4f00-949b-af3ebafdc08d">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c2f89b5-a3b3-42cd-857d-923fe8b8f1da">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f349f7aa-d020-4e0d-a35f-518a63ec92df">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=519815fd-707d-476f-9e29-7b03b7a17af5">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de7b7c8f-bd0a-4e13-bd58-d95507a6274b">Quartz</a>
                    <br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cec582b3-e37f-448e-a5c3-6abdcee9e57c">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b40dab-6b4d-434b-9997-12ef70d6bbcc">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="12" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178850">
                      <strong>MS10-006</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179067">
                      <strong>MS10-007</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179106">
                      <strong>MS10-008</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167190">
                      <strong>MS10-009</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167321">
                      <strong>MS10-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179066">
                      <strong>MS10-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179798">
                      <strong>MS10-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155976">
                      <strong>MS10-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=181196">
                      <strong>MS10-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179062">
                      <strong>MS10-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=180620">
                      <strong>MS10-005</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
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
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09e19263-18ba-495e-bcf7-719e957204a7">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a85b1bf-7427-47d0-9e1b-21dbe824a62c">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>**<br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc451228-3de4-427c-b42f-91f204c708b8">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ac0a948-0bdc-4c10-9b88-16a5d7092e47">Quartz</a>**<br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=597b2310-2cd8-4d0f-8248-781eb8b7450a">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75327470-0f14-4cdd-bcb7-64684c61c267">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21e87558-9bd2-4aa9-aaa5-7fd26a5b60e6">Windows Server 2008 til 32-bit-systemer og Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=180c2313-5e3e-4d84-87cd-64048f51e0f6">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fde218c3-90ab-4664-852d-25ca55835054">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>**<br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a889152-5d7c-4a3e-b4f1-c6507b739ca0">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=362fea40-649b-4471-aad7-db29edd0ac10">Quartz</a>**<br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3463a63c-e88a-4036-ab60-f84d4bf4191a">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67119fb6-e517-46f4-ab0b-2351cdc3d670">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d0f8f81-fc10-450a-a653-06f89acba9fa">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b93047d-f2c6-403b-9200-c251898bc1e0">Windows Server 2008 til x64-baserede systemer og Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=614eaf7e-95aa-4f8f-910c-1980e1f14d11">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b6e9451-df38-4626-bb1d-4fc160d7a40e">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1cd1882b-8e55-47ea-a82a-68bb59a500a7">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=effa638b-cfc1-4777-8219-7b433ed5e717">Quartz</a>
                    <br />(KB975560)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f90fc0c8-babe-4224-be07-614ea7ddf102">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd6b234b-8e96-4128-a77a-645a0882996a">Windows Server 2008 til Itanium-baserede systemer og Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="12" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178850">
                      <strong>MS10-006</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179067">
                      <strong>MS10-007</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179106">
                      <strong>MS10-008</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167190">
                      <strong>MS10-009</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167321">
                      <strong>MS10-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179066">
                      <strong>MS10-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179798">
                      <strong>MS10-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155976">
                      <strong>MS10-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=181196">
                      <strong>MS10-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179062">
                      <strong>MS10-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=180620">
                      <strong>MS10-005</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 Beta til 32-bit-systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a589431a-93dc-42cd-a74e-d9c1e3452fef">Windows 7 til 32-bit-systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec6d996f-dffa-45ad-9467-e96a4ac63e5f">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ec49aa2-81df-4e65-80da-6201394c4089">Quartz</a>
                    <br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=122fc003-0651-4ad2-a5c8-a21536defad8">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66f14bb4-40fc-4ae3-9baf-429b7106cd91">Windows 7 til 32-bit-systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows 7 til x64-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c1edcf8-d304-45c4-9818-1cd86383b3fe">Windows 7 til x64-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3265576-04c1-48b1-8ce9-128843c58cf5">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8a2519c-3b89-4987-9473-920adafc78cb">Quartz</a>
                    <br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e096468-db6c-45c6-bee5-eaeaa63500b5">Windows 7 til x64-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="12" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178850">
                      <strong>MS10-006</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179067">
                      <strong>MS10-007</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179106">
                      <strong>MS10-008</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167190">
                      <strong>MS10-009</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=167321">
                      <strong>MS10-013</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179066">
                      <strong>MS10-010</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179798">
                      <strong>MS10-011</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=155976">
                      <strong>MS10-012</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=181196">
                      <strong>MS10-014</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179062">
                      <strong>MS10-015</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=180620">
                      <strong>MS10-005</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
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
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ecb06350-47a7-48eb-825f-3e8f89c5ca8e">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cda31c54-8b81-4185-a623-64480ad4b73c">Windows Server 2008 R2 til x64-baserede systemer</a>**<br />(Lav)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a9811baa-1500-4c73-940b-57f8c5456891">Quartz</a>**<br />(KB975560)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3214b347-d901-4aac-85ce-676e4602de87">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc757b6d-f0f8-4e71-ab6f-1417233eedf9">Windows Server 2008 R2 til x64-baserede systemer</a>*<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=badd6cab-7738-4401-a68c-c15414388601">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43fa4e26-160f-4aa3-a03d-b98a79666a18">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Lav)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ed23bf5-6217-413c-a7ba-eccc82139d68">Quartz</a>
                    <br />(KB975560)<br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5b0b1eb-24f3-47ec-aba1-c1b95400189e">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(Alvorlig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**Bemærkning til MS10-013**

\[1\]Opdateringen til DirectX 9.0 er også gældende for DirectX 9.0a, DirectX 9.0b og DirectX 9.0c på Microsoft Windows 2000.

**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i MSDN-artiklerne [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core til Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i MSDN-artiklerne [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core til Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178812">
                      <strong>MS10-003</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163639">
                      <strong>MS10-004</strong>
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
                <tr><td style="border:1px solid black;">Microsoft Office XP</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47553f45-fa10-40e5-8267-9d42ff560a62">Microsoft Office XP Service Pack 3</a>
                    <br />(KB977896)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cfc697b4-2ceb-4030-86c5-be9bc8bfd07c">Microsoft Office PowerPoint 2002 Service Pack 3</a>
                    <br />(KB973143)<br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2003</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2291ae24-fa39-4ad8-a7d0-12726b68ad96">Microsoft Office PowerPoint 2003 Service Pack 3</a>
                    <br />(KB976881)<br />(Alvorlig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office til Mac</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178812">
                      <strong>MS10-003</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=163639">
                      <strong>MS10-004</strong>
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
                <tr><td style="border:1px solid black;">Microsoft Office 2004 til Mac</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8">Microsoft Office 2004 til Mac</a>
                    [1]
                    <br />(KB979674)<br />(Alvorlig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c985595-00c5-44b8-81c3-59d9967220f8">Microsoft Office 2004 til Mac</a>
                    [1]
                    <br />(KB979674)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkning til Microsoft Office til Mac**

\[1\]Disse opdateringer er identiske pga. den kumulative servicemodel for Microsoft Office 2004 til Mac.

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

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Microsoft Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Yderligere oplysninger, om hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services.](http://go.microsoft.com/fwlink/?linkid=50120)

**Systems Management Server**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere. Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig, se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Få mere at vide om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsoplysninger, på [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brugere kan også bruge SUIT (Security Update Inventory Tool) ved implementering af sikkerhedsopdateringer. Oplysninger om SMS findes på [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Bemærk\!** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til at installere disse opdateringer.

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

  - Damian Frizza fra [Core Security Technologies](http://www.coresecurity.com/) for at rapportere et problem, der er beskrevet i MS10-003
  - Carsten Eiram fra [Secunia](http://secunia.com/) for at have rapporteret et problem, der er beskrevet i MS10-004.
  - Sean Larsson fra [VeriSign iDefense Labs](http://labs.idefense.com/) for at have rapporteret tre problemer, der er beskrevet i MS10-004
  - SkD, der arbejder sammen med [TippingPoints](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem, der er beskrevet i MS10-004
  - Cody Pierce fra [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) for at rapportere et problem, der er beskrevet i MS10-004
  - Tielei Wang fra ICST-ERCIS (Engineering Research Center of Info Security, Institute of Computer Science & Technology, Peking University/Kina), der arbejder sammen med [Secunia](http://secunia.com/), for at rapportere et problem, der er beskrevet i MS10-005
  - Laurent Gaffié fra [stratsec](http://www.stratsec.net/) for at rapportere to problemer, der er beskrevet i MS10-006
  - Brett Moore, der arbejder sammen med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at rapportere et problem, der er beskrevet i MS10-007
  - [Lostmon Lords](http://lostmon.blogspot.com/) for at rapportere et problem, der er beskrevet i MS10-007
  - Shaun Colley fra [NGS Software](http://www.ngssoftware.com/) for at rapportere et problem, der er beskrevet i MS10-008
  - Sumit Gwalani, Drew Hintz, og Neel Mehta fra [Google Security Team](http://www.google.com/) for at rapporte tre problemer, der er beskrevet i MS10-009
  - Jan Bottorff for at rapportere et problem, der er beskrevet i MS10-010
  - Matthew 'j00ru' Jurczyk og Gynvael Coldwind fra [Hispasec](http://www.hispasec.com/) for at rapportere et problem, der er beskrevet i MS10-011
  - Joshua Morin fra [Codenomicon](http://www.codenomicon.com/) for at rapportere et problem, der er beskrevet i MS10-012
  - Florian Rienhardt fra [BSI](http://www.bsi.bund.de/) for at rapportere et problem, der er beskrevet i MS10-012
  - Hernan Ochoa (uafhængig konsulent/forsker i informationssikkerhed) for at rapportere et problem, der er beskrevet i MS10-012
  - En anonym forsker, der samarbejder med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for at have rapporteret et problem, der er beskrevet i MS10-013
  - Tavis Ormandy fra [Google Inc.](http://www.google.com/) for at rapporte et problem, der er beskrevet i MS10-015

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsofts supportpolitik](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger, om hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (9. februar 2010): Oversigt over bulletin offentliggjort.
  - V1.1 (10. februar 2010): Rettede genstartskrav for MS10-005.

*Built at 2014-04-18T01:50:00Z-07:00*

