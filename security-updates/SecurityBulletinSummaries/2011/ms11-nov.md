---
title: Oversigt over sikkerhedsopdateringer fra Microsoft for november 2011
TOCTitle: MS11-NOV
ms:assetid: ms11-nov
ms:mtpsurl: https://technet.microsoft.com/da-DK/library/ms11-nov(v=Security.10)
ms:contentKeyID: 61224081
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Oversigt over sikkerhedsopdateringer fra Microsoft for november 2011

Offentliggjort: 8. november 2011

**Version:** 1.0

Denne oversigt over bulletiner viser offentliggjorte sikkerhedsbulletiner for november 2011.

Med udgivelsen af sikkerhedsbulletiner for november 2011 erstatter denne oversigt over bulletiner den forhåndsmeddelelse om bulletiner, som oprindeligt blev offentliggjort den 3. november 2011. Yderligere oplysninger om forhåndsmeddelelsen om bulletiner finder du i [Forhåndsmeddelelse om sikkerhedsbulletin fra Microsoft](http://go.microsoft.com/fwlink/?linkid=217213).

Oplysninger om hvordan du kan modtage automatiske meddelelser, når der udsendes sikkerhedsbulletiner fra Microsoft, kan findes her [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft afholder et webcast for at behandle kundernes spørgsmål omkring disse bulletiner den 9. november 2011 kl. 11:00 Pacific Time (USA og Canada). [Tilmeld dig nu for at få november måneds sikkerhedsbulletin-webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487958). Efter denne dato kan man få adgang til dette webcast ved anmodning herom. Flere oplysninger kan fås i [Oversigt over sikkerhedsbulletiner fra Microsoft og webcasts](http://go.microsoft.com/fwlink/?linkid=217214).

Microsoft giver også oplysninger, der kan hjælpe kunder med at prioritere månedlige sikkerhedsopdateringer i forhold til ikke-sikkerhedsrelaterede opdateringer, som udgives samme dag som de månedlige sikkerhedsopdateringer. Se afsnittet **Andre oplysninger**.

### Information om bulletin

## Resuméer

Følgende tabel viser sikkerhedsbulletinerne for denne måned efter vigtighed.

Oplysninger om berørte programmer kan fås i næste afsnit, **Berørte programmer og downloadplaceringer**.

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Bulletinens titel og resumé</th>
<th>Klassifikation og sårbarhedens omfang</th>
<th>Krav om genstart</th>
<th>Berørte programmer</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229071">MS11-083</a></td>
<td><strong>Sårbarheder i TCP/IP kan tillade fjernudførelse af kode (2588516)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en hacker sender en stadig strøm af særligt udformede UDP-pakker til en lukket port på et målsystem.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Fjernudførelse af kode</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229638">MS11-085</a></td>
<td><strong>Sårbarhed i Windows Mail og Windows Meeting Space kan tillade fjernudførelse af kode (2620704)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre fjernudførelse af kode, hvis en bruger åbner en legitim fil (som f.eks. en fil i formatet .eml eller .wcinv), der er placeret i samme netværksmappe som en særligt udformet DLL-fil (Dynamic Link Library). Under åbningen af den legitime fil kan Windows Mail eller Windows Meeting Space forsøge at indlæse DLL-filen og udføre eventuelle koder deri. For at et angreb skal lykkes, skal en bruger besøge en fjernplacering på et filsystem, der ikke er tillid til, eller en WebDAV-deling og åbne en legitim fil (som f.eks. en .eml eller .wcinv-fil) fra denne placering, der derefter indlæses med et sårbart program.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Fjernudførelse af kode</td>
<td>Kan kræve genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229253">MS11-086</a></td>
<td><strong>Sårbarhed i Active Directory kan tillade udvidelse af rettigheder (2630837)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Active Directory, Active Directory Application Mode (ADAM) og Active Directory Lightweight Directory Service (AD LDS). Sårbarheden kan muliggøre udvidelse af rettigheder, hvis et Active Directory er konfigureret til at bruge LDAP over SSL (LDAPS), og en hacker får fat i et tilbagekaldt certifikat, der er tilknyttet en gyldig konto i domænet, og derefter bruger det tilbagekaldte certifikat til at blive godkendt til Active Directory-domænet. Som standard er Active Directory ikke konfigureret til at bruge LDAP over SSL.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Alvorlig</a><br />
Udvidelse af rettigheder</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229245">MS11-084</a></td>
<td><strong>Sårbarhed i Windows-kernetilstandsdrivere kan give mulighed for Denial-of-Service (2617657)</strong><br />
<br />
Denne sikkerhedsopdatering løser en privat rapporteret sårbarhed i Microsoft Windows. Sårbarheden kan muliggøre Denial-of-Service, hvis en bruger åbner en særligt udformet TrueType-fontfil i en vedhæftet fil i en e-mail eller navigerer til en netværksdeling eller WebDAV-placering, der indeholder en særligt udformet TrueType-fontfil. For at et angreb skal lykkes, skal en bruger besøge en fjernplacering på et filsystem, der ikke er tillid til, eller en WebDAV-deling, der indeholder den særligt udformede TrueType-fontfil, eller åbne filen i en vedhæftet fil i en e-mail. En hacker kan dog aldrig tvinge brugere til at udføre disse handlinger. I stedet er hackeren nødt til at overbevise brugerne om at gøre dette, typisk ved at få dem til at klikke på et link i en e-mail eller onlinebesked.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderate</a><br />
Denial of Service</td>
<td>Kræver genstart</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Indeks over mulighed for udnyttelse

Følgende tabel viser en vurdering af udnyttelsesmuligheden for hver af de sårbarheder, der behandles i denne måned. Sårbarhederne er opført i rækkefølge efter bulletin-id og derefter CVE-id. Kun sårbarheder, der har en klassifikation som Kritisk eller Alvorlig i bulletinerne, bliver inkluderet.

**Hvordan anvender jeg denne tabel?**

Brug denne tabel til at få kendskab til sandsynligheden for, at udførelse af kode og denial-of-service udnyttes inden for 30 dage efter udgivelse af sikkerhedsbulletin, for hver af de sikkerhedsopdateringer, du muligvis skal installere. Læs alle vurderinger nedenfor, i overensstemmelse med din specifikke konfiguration for at prioritere din implementering af denne måneds opdateringer. Hvis du ønsker flere oplysninger om, hvad disse klassifikationer betyder, og hvordan de fastlægges, kan du se [Microsoft Indeks for udnyttelse](http://technet.microsoft.com/security/cc998259.aspx).

I nedenstående artikelserier, refererer "Nyeste softwareversion" til den nyeste version af softwareemner, og "Ældre softwareversioner" refererer til alle ældre, understøttede versioner af softwareemner, der findes i "Berørte programmer" eller "Ikke-berørte programmer" i bulletin-tabellerne.

<table>
<thead>
<tr class="header">
<th>Bulletin-id</th>
<th>Titel på sårbarhed</th>
<th>CVE ID</th>
<th>Vurdering af mulighed for udnyttelse af kodeudførelse i nyeste softwareversion</th>
<th>Vurdering af mulighed for udnyttelse af kodeudførelse i ældre softwareversioner</th>
<th>Vurdering af mulighed for udnyttelse af Denial of Service</th>
<th>Vigtige bemærkninger</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229071">MS11-083</a></td>
<td>Sårbarhed vedr. overflow i referencetæller</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2013">CVE-2011-2013</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Inkonsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Inkonsekvent exploit-kode sandsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229638">MS11-085</a></td>
<td>Sårbarhed vedr. usikker indlæsning af Windows Mail-bibliotek</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2016">CVE-2011-2016</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=229253">MS11-086</a></td>
<td>Sårbarhed vedr. omgåelse af godkendelse af LDAPS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2014">CVE-2011-2014</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Konsekvent exploit-kode sandsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
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
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229638">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>Ingen</td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td colspan="2">Ingen</td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>Ikke relevant</td><td>Ikke relevant</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8c7c21c5-677d-4a5d-8f2b-8ca7691b6b00">Active Directory Application Mode (ADAM)</a>
                    <br />(KB2616310) <br />(Alvorlig)</td><td colspan="2">Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>Ikke relevant</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=989cca2d-cce1-4f52-b50e-43152693f240">Active Directory Application Mode (ADAM)</a>
                    <br />(KB2616310) <br />(Alvorlig)</td><td colspan="2">Ikke relevant</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229638">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>Ingen</td><td>Ingen</td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td colspan="2">Ingen</td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>Ikke relevant</td><td>Ikke relevant</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08b27ce7-c32e-41e4-ad04-481c5eab17a7">Active Directory</a>
                    <br />(KB2601626) <br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f116824e-ea48-422d-b284-c9ffa7604bf5">Active Directory Application Mode (ADAM)</a><br />(KB2616310) <br />(Alvorlig)</td><td colspan="2">Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>Ikke relevant</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de5a74f2-2cc8-4677-b495-3a40fe3d6b9e">Active Directory</a>
                    <br />(KB2601626) <br />(Alvorlig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1af1b734-62c7-4e08-91c8-90b6d026da84">Active Directory Application Mode (ADAM)</a><br />(KB2616310) <br />(Alvorlig)</td><td colspan="2">Ikke relevant</td></tr>
                <tr><td>Windows Server 2003 med SP2 til Itanium-baserede systemer</td><td>Ikke relevant</td><td>Ikke relevant</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6168bc67-3d59-450f-bd8a-02d61dabe16b">Active Directory</a>
                    <br />(KB2601626) <br />(Alvorlig)</td><td colspan="2">Ikke relevant</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229638">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td colspan="2">Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc3fe87c-2493-431d-a904-dec9310f6042">Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e08266d8-fffa-40bf-b8f6-10a65ee27524">Windows Vista Service Pack 2</a>
                    <br />(Alvorlig)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bd602cf-ae0d-4790-a5d0-6133fd7d01a0">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2601626) <br />(Alvorlig)</td><td colspan="2">Ikke relevant</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=042c1a8f-834d-4eed-8a59-9e030ccc6d39">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f2365ed-d50e-44d9-b859-1ec54d3b4d38">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Alvorlig)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=783521ad-5c50-4194-a582-4e5a1c9999e7">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2601626) <br />(Alvorlig)</td><td colspan="2">Ikke relevant</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229638">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td colspan="2">Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til 32-bit-systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79382bf2-d2cb-42ea-92dc-64f949353521">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f82dc413-668c-4ca8-a8c8-db74f05346bc">Windows Server 2008 til 32-bit-systemer Service Pack 2</a>**<br />(Moderat)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b5688923-3914-4f6c-8bc9-036fb4870cc6">Active Directory og Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB2601626) <br />(Alvorlig)</td><td colspan="2">Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 til x64-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71ff3a89-d7ad-4dda-9e59-fab54b21bd5d">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06ad5637-56a1-4478-aaa0-063e877503c9">Windows Server 2008 til x64-baserede systemer Service Pack 2</a>**<br />(Moderat)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51f47181-08f6-4de1-80e5-253355675965">Active Directory og Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB2601626) <br />(Alvorlig)</td><td colspan="2">Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 til Itanium-baserede systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1c0cb05-c284-49b1-ae4f-92813fdf520f">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2de5de74-e643-4045-9c22-ff95b0dbcafc">Windows Server 2008 til Itanium-baserede systemer Service Pack 2</a>
                    <br />(Moderat)</td><td colspan="2">Ikke relevant</td><td colspan="2">Ikke relevant</td></tr>
              
                <tr><th colspan="7">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229638">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ddb4c2a-bada-49b0-ad78-e07e7e11ced7">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2307fa93-8e45-4841-a5a9-7e89960712f9">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Lav)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b06f9f55-e3b2-4705-83d0-1b9f5de9d378">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2601626) <br />(Alvorlig)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=156c1bd9-55bc-482c-874b-61998d1ef153">Windows 7 til 32-bit-systemer og Windows 7 til 32-bit-systemer Service Pack 1</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05eef5d7-acf6-46e4-abfc-dc83f0a7cae5">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62603d18-1b21-400c-8eba-202193182960">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Lav)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=790f1d99-96a5-438d-b433-895b692912ce">Active Directory Lightweight Directory Service (AD LDS)</a>
                    <br />(KB2601626) <br />(Alvorlig)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c7db930-5495-43f0-928c-d586ac9e80d0">Windows 7 til x64-baserede systemer og Windows 7 til x64-baserede systemer Service Pack 1</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletin-id</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229071">
                      <strong>MS11-083</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229638">
                      <strong>MS11-085</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229253">
                      <strong>MS11-086</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=229245">
                      <strong>MS11-084</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet klassifikation</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Alvorlig</strong>
                    </a>
                  </td><td colspan="2">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderate</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1																		</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f9f74a6-e984-4aab-837c-ef7286e7305f">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9cf6a22-f9ab-427a-9b16-33c60baaabb5">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>**<br />(Lav)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cc1e99af-fc67-400b-a82c-171f8c4d1ac9">Active Directory og Active Directory Lightweight Directory Service (AD LDS)</a>*<br />(KB2601626) <br />(Alvorlig)</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d810dae-5c52-4155-b5c2-163d27be6e78">Windows Server 2008 R2 til x64-baserede systemer og Windows Server 2008 R2 til x64-baserede systemer Service Pack 1</a>***<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b20bfcbd-a515-4074-b56e-b82539fe5bad">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=012777f5-51f2-4944-91af-a9c79b8081a1">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(Lav)</td><td colspan="2">Ikke relevant</td><td colspan="2">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=395819e2-1028-44b7-ace4-ca754b1a7543">Windows Server 2008 R2 til Itanium-baserede systemer og Windows Server 2008 R2 til Itanium-baserede systemer Service Pack 1																		</a>
                    <br />(Moderat)</td></tr>
              </table>


**Bemærkning** **er** **til Windows Server 2008 og Windows Server 2008 R2**

**\*Serverens hovedinstallation er berørt.** Denne opdatering gælder, med samme klassifikation, for understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, uanset om Server Core-installationsindstillingerne blev anvendt ved installationen. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Serverens hovedinstallation er ikke berørt.** De sårbarheder, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, hvis installationen blev udført ved anvendelse af installationsindstillingen Server Core. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Serverens hovedinstallation er ikke berørt.** Den sårbarhede, denne opdatering drejer sig om, berører ikke understøttede udgaver af Windows Server 2008 eller Windows Server 2008 R2 som anført, når de er installeret vha. installationsindstillingen Server Core - heller ikke selv om filer, der er berørt af disse sårbarheder, findes på systemet. Brugere med berørte filer vil dog stadig blive tilbudt denne opdatering, da opdateringsfilerne er nyere (med højere versionsnumre), end de filer, der aktuelt er på systemet. Yderligere oplysninger om denne installationsindstilling findes i TechNet-artiklerne, [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) (Administration af en server-hovedinstallation) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx) (Servicering af en server-hovedinstallation). Bemærk, at installationsindstillingen Server Core ikke gælder for visse udgaver af Windows Server 2008 og Windows Server 2008 R2. Se [Sammenlign installationsindstillinger for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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

Application Compatibility Toolkit (ACT) indeholder de nødvendige værktøjer og den nødvendige dokumentation til evaluering og reducering af programkompatibilitetsproblemer før implementering af Microsoft Windows Vista, en Windows-opdatering, en Microsoft-sikkerhedsopdatering eller en ny version af Windows Internet Explorer i dit miljø.

### Andre oplysninger

#### Microsoft Windows værktøj til fjernelse af ondsindet software

Microsoft har udgivet en opdateret version af Microsoft Windows værktøj til fjernelse af ondsindet software. Den opdaterede version kan findes på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhedsrelaterede opdateringer på MU, WU og WSUS

Oplysninger om ikke-sikkerhedsrelaterede udgivelser på Windows Update og Microsoft Update findes på:

  - [Microsoft Knowledge Base-artikel 894199](http://support.microsoft.com/kb/894199): Beskrivelse af indholdsændringer i Software Update Services og Windows Server Update Services. Omfatter alt indhold i Windows.
  - [Opdateringer fra de foregående måneder for Windows Server Update Services.](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) Viser alle nye, reviderede og udgivne opdateringer til Microsoft-produkter udover Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

For at forbedre sikkerhedsbeskyttelsen for kunder giver Microsoft oplysninger om sårbarheder til store leverandører af sikkerhedssoftware før den månedlige udgivelse af sikkerhedsopdateringer. Derefter kan leverandører af sikkerhedssoftware bruge disse oplysninger om sårbarheder til at give opdateret beskyttelse til kunder via deres sikkerhedssoftware eller -enheder, f.eks. antivirus, registreringssystemer til netværksbaseret indtrængen eller forebyggelsessystemer til host-baseret indtrængen. For at afgøre, om aktive beskyttelser er tilgængelige fra leverandører af sikkerhedssoftware, skal du gå ind på websites på aktive beskyttelser, der udbydes af de programpartnere, som er angivet i [Microsoft Active Protections Program (MAPP) Partners](http://go.microsoft.com/fwlink/?linkid=215201).

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

  - Will Dorman hos [CERT/CC](http://www.cert.org/) for at rapportere et problem, der er beskrevet i MS11-084
  - Ivan Sanchez hos EvilCode for at rapportere et problem, der er beskrevet i MS11-085
  - Xavier Lassoie og Sébastien Godard hos Autosécurité for at rapportere et problem, der er beskrevet i MS11-086

#### Support

  - De berørte programmer på listen er blevet testet for at kontrollere, hvilke versioner der er berørt. Andre versioner er ude over deres supportlivscyklus. Du kan se supportlivscyklussen for din softwareversion på [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).
  - Kunder i USA og Canada kan få teknisk support fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY (1-866-727-2338). Supportopkald i forbindelse med sikkerhedsopdateringer er gratis. Yderligere oplysninger om dine supportmuligheder finder du på [Microsoft Hjælp og support](http://support.microsoft.com/).
  - Internationale kunder kan få support fra deres lokale Microsoft-afdeling. Support i forbindelse med sikkerhedsopdateringer er gratis. Du kan få yderligere oplysninger om, hvordan du kontakter Microsoft angående support, ved at besøge webstedet [International Help and Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Oplysningerne i Microsoft Knowledge Base leveres, som de er og forefindes, uden nogen form for garanti. Microsoft fraskriver sig enhver form for garanti, det være sig udtrykkelig eller stiltiende, herunder garanti for salgbarhed og egnethed til et bestemt formål. Microsoft Corporation eller Microsofts leverandører kan i intet tilfælde blive holdt ansvarlig for skader, herunder direkte, indirekte, hændelige eller særskilt dokumenterede skader, følgeskader eller driftstab, selvom Microsoft eller Microsofts leverandører er blevet underrettet om muligheden for sådanne skader. I nogle stater er det ikke tilladt at fraskrive sig eller begrænse erstatningsansvar for følgeskader eller hændelige skader, hvorfor ovennævnte begrænsning muligvis ikke gælder for dig.

#### Revisioner

  - V1.0 (8. november 2011): Oversigt over bulletin offentliggjort.

*Built at 2014-04-18T01:50:00Z-07:00*

