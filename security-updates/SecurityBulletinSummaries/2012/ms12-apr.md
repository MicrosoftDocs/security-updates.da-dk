---
title: Oversigt over sikkerhedsbulletiner fra Microsoft for april 2012
TOCTitle: MS12-APR
ms:assetid: ms12-apr
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms12-apr(v=Security.10)
ms:contentKeyID: 61224084
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsbulletiner fra Microsoft for april 2012

Offentliggjort: 10. april 2012 | Opdateret: 26. april 2012

**Version:** 2.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for april 2012.

Med udgivelsen af sikkerhedsbulletiner for april 2012 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 5. april 2012. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål vedr. disse bulletiner den 11. april 2012 kl. 11.00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få april måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499650). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og webcasts](http://go.microsoft.com/fwlink/?linkid=217214).

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td style="border:1px solid black;"><strong>Samlet sikkerhedsopdatering til Internet Explorer (2675157)</strong><br />
<br />
Denne sikkerhedsopdatering løser fem privat rapporterede sårbarheder i Internet Explorer. De mest alvorlige sårbarheder kan give mulighed for fjernudførelse af kode, hvis en bruger får vist en særligt udformet webside via Internet Explorer. En hacker, som det lykkes at udnytte enhver af disse sårbarheder, vil kunne få de samme brugerrettigheder som den nuværende bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238623">MS12-024</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Windows kan tillade fjernudførelse af kode (2653956)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan tillade fjernudførelse af kode, hvis en bruger eller et program kører eller installerer en særligt udformet signeret PE-fil (portable executable - bærbar eksekverbar) på det berørte system.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kræver genstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=242032">MS12-025</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i .NET Framework kan muliggøre fjernudførelse af</strong> <strong>kode (2671605)</strong><br />
<br />
Denne sikkerhedsopdatering løser én privat rapporteret sårbarhed i Microsoft NET Framework. Sårbarheden kan muliggøre fjernudførelse af kode på et klientsystem, hvis en bruger får vist en særligt udformet webside ved brug af en webbrowser, der kører XAML Browser Applications (XBAPs). Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder. Sårbarheden kan derudover muliggøre fjernudførelse af kode på et serversystem, der kører IIS, hvis denne server giver mulighed for behandling af ASP.NET-sider, og det lykkes en hacker at uploade en særligt udformet ASP.NET-side til den pågældende server og køre den, som det f.eks. kan være tilfældet i et webhosting-scenarie. Denne sårbarhed kan også bruges af Windows .NET-programmer til at omgå CAS-restriktioner (Code Access Security). I et webbrowsende angrebsscenarie kan hackeren hoste et websted, der indeholder en webside, som bruges til at udnytte denne sårbarhed. Dertil kommer, at kompromitterede websteder og websteder, der accepterer eller er vært for indhold leveret af brugerne eller reklamer, kan indeholde særligt udformet indhold, som kan udnytte sårbarheden. En hacker kan dog aldrig tvinge brugere til at besøge disse websteder. I stedet er hackeren nødt til at overtale brugerne til at besøge webstedet, typisk ved at få vedkommende at klikke på et link i en e-mail eller i en onlinemeddelelse, som fører brugerne til hackerens websted.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246275">MS12-027</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Windows Common Control kan tillade fjernudførelse af kode (2664258)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat offentliggjort sårbarhed i Windows Common Controls. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger besøger et websted, der indeholder særligt udformet indhold, som er udviklet til at udnytte sårbarheden. En hacker kan imidlertid ikke tvinge brugere til at besøge et sådant websted. I stedet er hackeren nødt til at overtale brugerne til at besøge webstedet, typisk ved at få dem til at klikke på et link i en e-mail eller i en onlinemeddelelse, som fører brugerne til hackerens websted. Den ondsindede fil kan også sendes som en vedhæftet fil, men hackeren er nødt til at overbevise brugeren om at åbne den vedhæftede fil for at kunne udnytte sårbarheden.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft Server-software,<br />
Microsoft-udviklingsværktøjer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238519">MS12-026</a></td>
<td style="border:1px solid black;"><strong>Sårbarheder i Forefront Unified Access Gateway (UAG) kan give mulighed for afsløring af oplysninger (2663860)</strong><br />
<br />
Denne kritiske sikkerhedsopdatering løser to privat rapporterede sårbarheder i Microsoft Forefront Unified Access Gateway (UAG). De mere alvorlige af sårbarhederne kan give mulighed for offentliggørelse af oplysninger, hvis en hacker sender en særligt udformet forespørgsel til UAG-serveren.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Afsløring af oplysninger</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Forefront United Access Gateway</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232498">MS12-028</a></td>
<td style="border:1px solid black;"><strong>En sårbarhed i Microsoft Office kan muliggøre fjernudførelse af kode (2639185)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Office og Microsoft Works. Denne sårbarhed kan give mulighed for fjernudførelse af kode, hvis en bruger åbner en særligt udformet Works-fil. En hacker, som det lykkes at udnytte denne sårbarhed, vil kunne få de samme brugerrettigheder som den nuværende bruger. Brugere, hvis konti er konfigurerede til at have færre brugerrettigheder på systemet, rammes muligvis i mildere grad end brugere, der opererer med administrative brugerrettigheder.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td style="border:1px solid black;">Kan kræve genstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er opført i rækkefølge efter bulletin-id og derefter CVE-id. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

**Hvordan anvender jeg denne tabel?**  

Brug denne tabel til at få kendskab til sandsynligheden for, at udførelse af kode og denial-of-service udnyttes inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Læs alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering af denne måneds opdateringer. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/security/cc998259.aspx).

I nedenstående artikelserier, refererer "Nyeste softwareversion" til den nyeste version af softwareemner, og "Ældre softwareversioner" refererer til alle ældre, understøttede versioner af softwareemner, der findes i "Berørte programmer" eller "Ikke-berørte programmer" i bulletin-tabellerne.

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-id</th>
<th style="border:1px solid black;">Titel på sårbarhed</th>
<th style="border:1px solid black;">CVE ID</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse i den nyeste softwareversion</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse i ældre softwareversioner</th>
<th style="border:1px solid black;">Vurdering af mulighed for udnyttelse af Denial of Service</th>
<th style="border:1px solid black;">Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td style="border:1px solid black;">Sårbarhed i forbindelse med fjernudførelse af kode i Jscript9</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0169">CVE-2012-0169</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td style="border:1px solid black;">Sårbarhed i forbindelse med fjernudførelse af kode i OnReadyStateChange</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0170">CVE-2012-0170</a></td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td style="border:1px solid black;">Sårbarhed i forbindelse med fjernudførelse af kode i SelectAll</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0171">CVE-2012-0171</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td style="border:1px solid black;">Sårbarhed i forbindelse med fjernudførelse af kode for VML Style</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0172">CVE-2012-0172</a></td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238623">MS12-024</a></td>
<td style="border:1px solid black;">Sårbarhed ved validering af signatur for WinVerifyTrust</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0151">CVE-2012-0151</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=242032">MS12-025</a></td>
<td style="border:1px solid black;">Sårbarhed ved .NET Framework Parameter-validering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0163">CVE-2012-0163</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=238519">MS12-026</a></td>
<td style="border:1px solid black;">Ufiltreret adgang til sårbarhed på UAG-standard websted</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0147">CVE-2012-0147</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td style="border:1px solid black;">Er ikke berørt</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette er en sårbarhed vedr. offentliggørelse af oplysninger</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246275">MS12-027</a></td>
<td style="border:1px solid black;">MSCOMCTL.OCX RCE-sårbarhed</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0158">CVE-2012-0158</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Microsoft er opmærksom på begrænsede, målrettede angreb, som forsøger at udnytte denne sårbarhed.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232498">MS12-028</a></td>
<td style="border:1px solid black;">Sårbarhed vedr. Office WPS Converter-heapoverløb</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0177">CVE-2012-0177</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> - Exploit-kode usandsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> -Exploit-kode sandsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Microsoft Office 2007 Service Pack 3 og alle understøttede versioner af Microsoft Office 2010 er ikke berørt.</td>
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
                <tr><th colspan="4" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a490c62-16c4-402a-b2d9-3e8cfb5bcebd">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81b28dd9-87aa-46cc-94c6-2da39d0298db">Internet Explorer 7</a><br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=74ce0e29-046b-4ac3-89a1-b292a177972f">Internet Explorer 8</a><br />(KB2675157)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=575afd20-cee4-4fa9-b781-9f8dfdd41ebe">Windows XP Service Pack 3</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1cfeae57-d4e9-4fff-8956-523e7b71453c">Microsoft .NET Framework 1.0 Service Pack 3</a>
                    <br />(KB2656378)<br />(Kun Media Center Edition 2005 og Tablet PC Edition 2005) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a><br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1b7be43-a32e-456b-8df0-c26cdf187682">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29ec7b06-c7aa-4149-bb2c-25af7d38a6a9">Internet Explorer 7</a><br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=646c6352-4d99-413a-a75b-71289b5d2b25">Internet Explorer 8</a><br />(KB2675157)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=adc31695-1be6-4976-869c-007df8ac8508">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet  </strong>
                    <strong>klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=020e0d68-dd1c-4297-b565-fcc6dcf5f280">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17b0c139-2709-424d-9d17-827af468e858">Internet Explorer 7</a><br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3289a80a-d1b1-4494-bede-03d0be579acf">Internet Explorer 8</a><br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f79c8940-ca31-4ff7-924e-847f5eef7864">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffd26218-e149-44ea-a0b9-f2a1315fce9e">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656376) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=295292d3-01a3-4574-b994-8cdbcf5a0d2e">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04656a93-e958-4764-afe8-27c476855506">Internet Explorer 7</a><br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dff4fb63-b319-49ed-8a9d-6b15e43d5bfd">Internet Explorer 8</a><br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03ebf111-1e7b-4dc2-b84f-a26c6b5f0d58">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09011393-c7d5-4225-9b8e-5a234d4dbcd1">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a5ef0147-595e-43b5-819f-73780fcef10d">Internet Explorer 7</a><br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=734ff97a-7d72-4bfe-9557-7fac91902f8e">Windows Server 2003 med SP2 til Itanium-baserede systemer</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f598cad1-4d1a-40ce-a016-bb58778d5dc0">Internet Explorer 7</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44284277-06a7-405d-9187-8f50a042604d">Internet Explorer 8</a><br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51088164-13b7-4216-90f1-20c92c8b8ca9">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7683919-6d46-4b3e-aa98-1bef20141835">Windows Vista Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2717a997-2066-4a83-ae9b-4611a0851101">Internet Explorer 7</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19684033-ddeb-464f-9a22-f580a9c19f8e">Internet Explorer 8</a><br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbb99aee-aadd-4ec7-9e27-91cb8d90803e">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d9f8a6e-17bd-4ed3-8bc7-d5e3b11ca12a">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e361edd-234b-4053-aa49-278b9fde4d5c">Internet Explorer 7</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6eb6781e-7b38-4679-afbc-4e3bb5747fd8">Internet Explorer 8</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d34d7981-ed63-460d-95e4-e6da1ac41d2f">Internet Explorer 9</a>**<br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c36c20f7-a742-4151-b8f2-85ef80479d06">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60b76a3c-4530-4101-931f-45df621e1eed">Internet Explorer 7</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd657467-a45c-4354-b947-3a3cceb9b690">Internet Explorer 8</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9d773e9-6a2e-45db-8f30-7da0082d909c">Internet Explorer 9</a>**<br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=330cea47-221d-439e-b106-58a146fc28ee">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3235216f-497f-4934-81b8-1eb9929e98c9">Internet Explorer 7</a>
                    <br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ec74522-ec1e-4b3c-bfeb-6a505cc4f11a">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows 7 til 32-bit-systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a58ca0b-fad7-418e-80ae-ca478168f887">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6724be3-ff4b-4dea-95f3-0b13998b6758">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac183b66-0247-4ae5-bda0-e8d0070917c8">Windows 7 til 32-bit-systemer</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656372) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 til 32-bit-systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a58ca0b-fad7-418e-80ae-ca478168f887">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6724be3-ff4b-4dea-95f3-0b13998b6758">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac183b66-0247-4ae5-bda0-e8d0070917c8">Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656373) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows 7 til x64-baserede systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7215f707-c536-4d81-ad66-e7bff592e400">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ff822d0-074a-409c-9174-8100618c6171">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27226e64-266f-499e-8c57-866593fc3430">Windows 7 til x64-baserede systemer</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656372) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 til x64-baserede systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7215f707-c536-4d81-ad66-e7bff592e400">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ff822d0-074a-409c-9174-8100618c6171">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27226e64-266f-499e-8c57-866593fc3430">Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656373) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 til x64-baserede systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=237d94e6-b9b9-4177-81fa-a67df2806b0e">Internet Explorer 8</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d002bfe4-10e9-46d3-a460-06d112201ca5">Internet Explorer 9</a>**<br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">Windows Server 2008 R2 til x64-baserede systemer<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54db1495-31bb-4435-a442-74e484630b8a">*</a><br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>*<br />(KB2656372) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=237d94e6-b9b9-4177-81fa-a67df2806b0e">Internet Explorer 8</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d002bfe4-10e9-46d3-a460-06d112201ca5">Internet Explorer 9</a>**<br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54db1495-31bb-4435-a442-74e484630b8a">Windows Server 2008 R2 til x64-baserede systemer, Service Pack 1</a>*<br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>*<br />(KB2656373) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>*[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7bdba902-0a6e-451e-a29b-6d0a03ff5664">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a4115bf-028b-4dcc-8995-d3341fdf42f2">Windows Server 2008 R2 til Itanium-baserede systemer</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656372) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7bdba902-0a6e-451e-a29b-6d0a03ff5664">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a4115bf-028b-4dcc-8995-d3341fdf42f2">Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656373) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              </table>


**Bemærkninger til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Bemærkninger** **til** **MS12-02** **5**

\[1\] **.NET Framework 4 og .NET Framework 4 Client Profile er berørt.** The .NET Framework version 4 redistributable packages er tilgængelige i to profiler: .NET Framework 4 og .NET Framework 4 Client Profile. .NET Framework 4 Client Profile er et delområde af .NET Framework 4. Sårbarheden nævnt i denne opdatering berører både .NET Framework 4 og .NET Framework 4 Client Profile. For yderligere oplysninger skal du se MSDN-artiklen, [Installation af .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office-pakker og -programmer

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office-pakker og komponenter</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232498">
                      <strong>MS12-028</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft Office 2003 Service Pack 3</a>
                    <br />(Windows Common Controls)<br />(KB2597112) <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2007 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft Office 2007 Service Pack 2</a>
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fbf24cc6-89e1-48dd-bb83-23eed30195e1">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2596871)<br />(Alvorlig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2007 Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft Office 2007 Service Pack 3</a>
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2010 (32-bit-versioner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c9d7bf-c9e0-4e01-8b66-da542332a28b">Microsoft Office 2010 (32-bit-versioner)</a>
                    <br />(Windows Common Controls)<br />(KB2598039) <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2010 Service Pack 1 (32-bit editions)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c9d7bf-c9e0-4e01-8b66-da542332a28b">Microsoft Office 2010 Service Pack 1 (32-bit editions)</a>
                    <br />(Windows Common Controls)<br />(KB2598039) <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office Web Components</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232498">
                      <strong>MS12-028</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2003 Web Components Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft Office 2003 Web Components Service Pack 3</a>
                    <br />(Windows Common Controls)<br />(KB2597112) <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Øvrigt Microsoft Office-software</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232498">
                      <strong>MS12-028</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Works 9</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94e17a66-cf09-4314-89ec-53deadabfa66">Microsoft Works 9</a>
                    <br />(KB2680317) <br />(Alvorlig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Works 6-9 File Converter</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4605f684-6314-4758-adeb-2a8810dfc8d1">Microsoft Works 6-9 File Converter</a>
                    <br />(KB2680326) <br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger til MS12-027**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Microsoft Server-software

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2" style="border:1px solid black;">Microsoft SQL Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft SQL Server 2000 Service Pack 4</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=198f1819-818b-4b2e-a424-4a45729746eb">Microsoft SQL Server 2000 Analysis Services Service Pack 4</a>
                    <br />(KB983807) <br />(Kritisk)<br /><br />GDR-opdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a9d97e8-79e0-4997-88fe-1224707e1b37">Microsoft SQL Server 2000 Service Pack 4</a><br />(KB983808) <br />(Kritisk)<br /><br />QFE-opdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8d0cac2f-f227-4e00-9454-4df62be86407">Microsoft SQL Server 2000 Service Pack 4</a><br />(KB983809) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="2" style="border:1px solid black;">Microsoft SQL Server-komponenter</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SQL Server 2005 til 32-bit-systemer, Service Pack 4</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 til 32-bit-systemer, Service Pack 4</a>
                    [1]
                    <br />(Windows Common Controls)<br />(KB2597112) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SQL Server 2005 til Itanium-baserede systemer, Service Pack 4</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 til Itanium-baserede systemer, Service Pack 4</a>
                    [1]
                    <br />(Windows Common Controls)<br />(KB2597112) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SQL Server 2005 til x64-baserede systemer, Service Pack 4</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 til x64-baserede systemer, Service Pack 4</a>
                    [1]
                    <br />(Windows Common Controls)<br />(KB2597112) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SQL Server 2005 Express Edition med Advanced Services Service Pack 4</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 Express Edition med Advanced Services Service Pack 4</a>
                    [1]
                    <br />(Windows Common Controls)<br />(KB2597112) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SQL Server 2008 til 32-bit-systemer, Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 til 32-bit-systemer, Service Pack 2</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SQL Server 2008 til 32-bit-systemer, Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 til 32-bit-systemer, Service Pack 3</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SQL Server 2008 til x64-baserede systemer, Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 til x64-baserede systemer, Service Pack 2</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SQL Server 2008 til x64-baserede systemer, Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 til x64-baserede systemer, Service Pack 3</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SQL Server 2008 til Itanium-baserede systemer, Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 til Itanium-baserede systemer, Service Pack 2</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SQL Server 2008 til Itanium-baserede systemer, Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 til Itanium-baserede systemer, Service Pack 3</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SQL Server 2008 R2 til 32-bit-systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 til 32-bit-systemer</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SQL Server 2008 R2 til 32-bit-systemer, Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 til 32-bit-systemer, Service Pack 1</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SQL Server 2008 R2 til x64-baserede systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 til x64-baserede systemer</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SQL Server 2008 R2 til x64-baserede systemer, Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 til x64-baserede systemer, Service Pack 1</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SQL Server 2008 R2 til Itanium-baserede systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 til Itanium-baserede systemer</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SQL Server 2008 R2 til Itanium-baserede systemer, Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 til Itanium-baserede systemer, Service Pack 1</a>
                    [2]
                    <br />(Windows Common Controls)<br />(KB2598041) <br />(Kritisk)</td></tr>
              </table>


**Bemærkninge** **r** **til** **MS12-02** **7**

\[1\]Denne opdatering er den samme som KB2597112-opdateringen til Microsoft Office 2003

\[2\]Denne opdatering er den samme som KB2598041-opdateringen til Microsoft Office 2007

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2" style="border:1px solid black;">Microsoft BizTalk Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft BizTalk Server 2002 Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d90b78d2-551b-499b-9bd2-85b40646dbc7">Microsoft BizTalk Server 2002 Service Pack 1</a>
                    <br />(KB2645025) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Commerce Server</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Commerce Server 2002 Service Pack 4</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35de8833-50ae-482d-aa07-497bf68fb38e">Microsoft Commerce Server 2002 Service Pack 4</a>
                    <br />(KB2658674) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Commerce Server 2007, Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f04fb90-8f11-4392-a4bc-800903091f04">Microsoft Commerce Server 2007, Service Pack 2</a>
                    <br />(KB2658677) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Commerce Server 2009</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8998b6b-e9a4-457e-a34f-0458dda81f2f">Microsoft Commerce Server 2009</a>
                    <br />(KB2655547) <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Commerce Server 2009 R2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9221811-8913-412b-ae04-21a55ce7c4c5">Microsoft Commerce Server 2009 R2</a>
                    <br />(KB2658676) <br />(Kritisk)</td></tr>
              </table>


**Bemærkninger til MS12-027**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Udviklingsværktøjer og software fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Visual FoxPro</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Visual FoxPro 8.0 Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a7ff474-f1e0-4c86-9555-64e8e7357890">Microsoft Visual FoxPro 8.0 Service Pack 1</a>
                    <br />(KB2647488) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visual FoxPro 9.0 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=53c0132e-7724-4e94-abe9-e79b76ce35d7">Microsoft Visual FoxPro 9.0 Service Pack 2</a>
                    <br />(KB2647490) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="2" style="border:1px solid black;">Visual Basic</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Visual Basic 6.0 Runtime</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0afe933a-1e62-45c4-910c-ea94b203df5a">Visual Basic 6.0 Runtime</a>
                    <br />(KB2641426) <br />(Kritisk)</td></tr>
              </table>


**Bemærkninger til MS12-027**

Se også andre softwarekategorier under dette afsnit, **Berørte programmer og downloadplaceringer**, for at få flere opdateringsfiler under samme bulletin-id. Denne bulletin omhandler mere end én softwarekategori.

#### Microsoft Remote Access software

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2" style="border:1px solid black;">Microsoft Forefront Unified Access Gateway</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletin-id</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238519">
                      <strong>MS12-026</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet klassifikation</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Forefront Unified Access Gateway</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4b4ecc4-8bc6-43d0-b872-93673e0d9a6f">Microsoft Forefront Unified Access Gateway 2010 Service Pack 1</a>
                    [1]
                    <br />(KB2649261)<br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0f9acab-bfb8-4758-b60d-64e68a84fba0">Microsoft Forefront Unified Access Gateway 2010 Service Pack 1, opdatering 1</a>[1]<br />(KB2649262)<br />(Alvorlig)</td></tr>
              </table>


**Bemærkninger** **til** **MS12-026**

\[1\]Denne opdatering er udelukkende tilgængelig fra Microsoft Download Center.

## Registrerings- og installationsværktøjer og vejledning

**Security Central**

Administrer de software- og sikkerhedsopdateringer, du skal udrulle på din organisations servere, stationære computere og bærbare computere. Yderligere oplysninger finder du i [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) giver yderligere oplysninger om sikkerheden i Microsoft-produkter. Forbrugere kan gå ind på [Sikkerhed hjemme](http://go.microsoft.com/fwlink/?linkid=85102), hvor disse oplysninger også kan findes ved at klikke på "Seneste sikkerhedsopdateringer".

Der kan hentes sikkerhedsopdateringer fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Der kan også hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".

For kunder med Microsoft Office til Mac, kan Microsoft AutoUpdate til Mac hjælpe med til at holde Microsoft-software opdateret. Se [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea) for at få flere oplysninger om brug af Microsoft AutoUpdate til Mac.

Endelig kan sikkerhedsopdateringer hentes fra [Microsoft Update-kataloget](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-kataloget indeholder et søgbart katalog over indhold, der er tilgængeligt via Windows Update og Microsoft Update, herunder sikkerhedsopdateringer, drivere og Service Packs. Ved at søge efter sikkerhedsbulletinnummeret (f.eks. "MS07-036") kan man tilføje alle relevante opdateringer til kurven (herunder forskellige sprog til en opdatering) og downloade til den valgte mappe. Du kan få yderligere oplysninger om Microsoft Update-kataloget ved at se [Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900).

**Vejledning i registrering og implementering**

Microsoft giver vejledning i registrering og implementering af sikkerhedsopdateringer. Denne vejledning indeholder anbefalinger og oplysninger, som it-fagfolk kan bruge til bedre at forstå, hvordan de skal anvende forskellige værktøjer til registrering og implementering af sikkerhedsopdateringer. Yderligere oplysninger finder du i [Microsoft Knowledge Base-artikel 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

MBSA (Microsoft Baseline Security Analyzer) giver administratorer mulighed for at søge på lokale systemer og fjernsystemer efter manglende sikkerhedsopdateringer samt almindelige fejl ved sikkerhedskonfigurationer. Hvis du ønsker yderligere oplysninger om MBSA, kan du besøge webstedet [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Ved hjælp af WSUS (Windows Server Update Services) kan administratorer hurtigt og sikkert implementere de nyeste kritiske opdateringer og sikkerhedsopdateringer til Microsoft Windows 2000-operativsystemer og nyere, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Yderligere oplysninger om, hvordan du implementerer denne sikkerhedsopdatering med Windows Server Update Services, finder du på webstedet [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).

**System Center Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse opgave, det er at levere og administrere opdateringer af it-systemer på tværs af virksomheden. Med Configuration Manager 2007 kan it-administratorer levere opdateringer af Microsoft-produkter til en række enheder, herunder stationære og bærbare computere, servere og mobile enheder.

Den automatiserede sårbarhedsvurdering i Configuration Manager 2007 opdager behov for opdateringer og rapporterer om anbefalede forholdsregler. Software Update Management i Configuration Manager 2007 er bygget på Microsoft Windows Software Update Services (WSUS), en gennemprøvet opdateringsinfrastruktur, der er kendt af it-administratorer verden over. Se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) for at få flere oplysninger om, hvordan administratorer kan bruge Configuration Manager 2007 til at implementere opdateringer. Yderligere oplysninger om Configuration Manager findes i [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) leverer en virksomhedsløsning til styring af opdateringer, som kan konfigureres på mange måder. Med SMS kan administratorer identificere Windows-baserede systemer med behov for sikkerhedsopdateringer og udføre kontrolleret anvendelse af disse opdateringer i hele virksomheden med minimal afbrydelse for slutbrugere.

**Bemærk** System Management Server 2003 er uden for generel support fra den 12. januar 2010. Du kan få yderligere oplysninger om produktlivscyklussen på [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den næste version af SMS, System Center Configuration Manager 2007, er nu tilgængelig; se det tidligere afsnit, **System** Center Configuration Manager 2007.

Yderligere oplysninger om, hvordan administratorer kan bruge SMS 2003 til at implementere sikkerhedsopdateringer, findes i [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Oplysninger om SMS findes på [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Bemærk\!** SMS anvender Microsoft Baseline Security Analyzer til at levere omfattende understøttelse af registrering og implementering af opdatering af sikkerhedsbulletiner. Nogle softwareopdateringer registreres måske ikke af disse værktøjer. Administratorer kan i disse tilfælde bruge funktionerne til udarbejdelse af hardware- og softwareoversigter i SMS for at målrette opdateringer til bestemte systemer. Flere oplysninger om denne procedure kan findes på [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Nogle sikkerhedsopdateringer kræver administrative rettigheder efterfulgt af en genstart af systemet. Administratorer kan bruge Elevated Rights Deployment Tool (fås i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til at installere disse opdateringer.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Opdateringer skriver ofte til de samme filer og registreringsdatabaseindstillinger, der er nødvendige for, at dine programmer kan køre. Dette kan udløse inkompatibilitet og forøge den tid, det tager at implementere sikkerhedsopdateringer. Du kan strømline test og validering af Windows-opdateringer mod installerede programmer med de [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponenter, der følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Opdateringer fra de foregående måneder for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Viser alle nye, reviderede og udgivne opdateringer til Microsoft-produkter udover Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

For at forbedre sikkerhedsbeskyttelsen for kunder giver Microsoft oplysninger om sårbarheder til store leverandører af sikkerhedssoftware før den månedlige udgivelse af sikkerhedsopdateringer. Derefter kan leverandører af sikkerhedssoftware bruge disse oplysninger om sårbarheder til at give opdateret beskyttelse til kunder via deres sikkerhedssoftware eller -enheder, f.eks. antivirus, registreringssystemer til netværksbaseret indtrængen eller forebyggelsessystemer til host-baseret indtrængen. For at afgøre om aktive beskyttelser er tilgængelige fra leverandører af sikkerhedssoftware, skal du gå ind på websteder med aktive beskyttelser, der udbydes af de programpartnere, som er angivet i [Microsoft Active Protections Program (MAPP) Partners](http://go.microsoft.com/fwlink/?linkid=215201).

#### Sikkerhedsstrategier og community

**Strategier til håndtering af opdateringer**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) giver yderligere oplysninger om Microsofts anbefalinger til de bedste fremgangsmåder for anvendelse af sikkerhedsopdateringer.

**Andre sikkerhedsopdateringer**

Opdateringer til andre sikkerhedsproblemer er tilgængelige på følgende placeringer:

  - Der kan hentes sikkerhedsopdateringer i [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Den nemmeste måde at finde dem på er at søge efter nøgleordet "sikkerhedsopdatering".
  - Der kan findes opdateringer til forbrugerplatforme på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan hente de sikkerhedsopdateringer, der er gjort tilgængelige på Windows Update denne måned, fra Download Center på Security and Critical Releases ISO CD Image-filer. Yderligere oplysninger finder du i [Microsoft Knowledge Base-artikel 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Lær, hvordan du forbedrer sikkerheden og optimerer din it-infrastruktur, og diskutér sikkerhedsemner med andre it-fagfolk i [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164).

#### Tak til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for at hjælpe os i arbejdet med at beskytte kunderne:

  - linx2008 fra [AISec](http://www.aisec.cn/) for at have rapporteret et problem, der er beskrevet i MS12-023
  - Roel Spilker fra [TOPdesk](http://www.topdesk.com) for at have rapporteret et problem, der er beskrevet i MS12-023
  - Jose Antonio Vazquez Gonzalez, der samarbejder med [VeriSign iDefense Labs](http://labs.idefense.com), for at rapportere et problem, der er beskrevet i MS12-023
  - En anonym forsker, der samarbejder med [TippingPoints](http://www.tippingpoint.com)[Zero Day Initiative](http://www.zerodayinitiative.com), for at rapportere et problem, der er beskrevet i MS12-023
  - En anonym forsker, der samarbejder med [TippingPoints](http://www.tippingpoint.com)[Zero Day Initiative](http://www.zerodayinitiative.com), for at rapportere et problem, der er beskrevet i MS12-023
  - Masato Kinugawa for at arbejde sammen med os om ændringer ifm. de gennemgribende beskyttelsesforanstaltninger, der er inkluderet i MS12-023
  - Robert Zacek og Igor Glucksmann fra [Avast Software](http://www.avast.com/) for at rapportere et problem, der er beskrevet i MS12-024
  - Vitaliy Toropov, der samarbejder med [VeriSign iDefense Labs](http://labs.idefense.com/), for at rapportere et problem, der er beskrevet i MS12-025
  - Shaun Colley fra [IOActive, Ltd.](http://ioactive.co.uk/) for at rapportere et problem, der er beskrevet i MS12-028

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
  - Sikkerhedsløsninger til professionelle it-fagfolk: [TechNet fejlfinding af og support til sikkerhedsproblemer](http://technet.microsoft.com/security/bb980617.aspx)
  - Vær med til at beskytte din Windows-computer mod virusser og malware: [Løsningscenter til virus og sikkerhed](http://support.microsoft.com/contactus/cu_sc_virsec_master)
  - Lokal support, landeafhængig: [International support](http://support.microsoft.com/common/international.aspx)

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V 1.0 (10. april 2012): Oversigt over bulletin offentliggjort.
  - V 2.0 (26. april 2012): Til MS12-027, tilføjer Service Pack 1-versioner af SQL Server 2008 R2 til den berørte software og præciserer oplysningerne om berørt software, dvs. at opdateringen gælder alle installationer af Microsoft SQL Server 2000 Analysis Services Service Pack 4, da skelnen mellem QFE og GDR ikke er relevant for dette produkt. Disse ændringer er udelukkende til oplysningsformål. Der er ikke foretaget ændringer i sikkerhedsopdateringsfilerne eller i registreringslogikken. Da opdateringerne har været tilgængelige siden den oprindelige udgivelse, behøver kunder, der allerede har installeret opdateringerne, ikke foretage sig noget.

*Built at 2014-04-18T01:50:00Z-07:00*

