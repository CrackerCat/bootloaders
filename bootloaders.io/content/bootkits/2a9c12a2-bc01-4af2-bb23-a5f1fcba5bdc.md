+++

description = ""
title = "2a9c12a2-bc01-4af2-bb23-a5f1fcba5bdc"
weight = 10
displayTitle = "bootmgfw.efi"
+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# bootmgfw.efi ![:inline](/images/twitter_verified.png) 


### Description

This was provided by Microsoft and revoked May-23
- **UUID**: 2a9c12a2-bc01-4af2-bb23-a5f1fcba5bdc
- **Created**: 2023-05-22
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLbootkits/raw/main/bootkits/.bin" "Download" >}}
{{< tip "warning" >}}

{{< /tip >}}

### Commands

```
bcdedit /copy &#34;{current}&#34; /d &#34;LOLDrivers&#34; | {% if ($_ -match &#39;{\S+}&#39;) { bcdedit /set $matches[0] path \windows\temp\bootmgfw.efi } }
```


| Use Case | Privileges | Operating System | 
|:---- | ---- | ---- |
| Persistence |  | 64-bit |



### Detections


{{< block "grid-3" >}}
{{< column >}}
#### YARA 🏹
{{< details "Expand" >}}

{{< /details >}}
{{< /column >}}



{{< column >}}

#### Sigma 🛡️
{{< details "Expand" >}}
{{< button "https://github.com/magicsword-io/LOLbootkits/tree/main/detections/sigma/bootkit_load_win_vuln_bootkits_names.yml" "Names" >}}{{< tip >}}detects loading using name only{{< /tip >}} 


{{< button "https://github.com/magicsword-io/LOLbootkits/tree/main/detections/sigma/bootkit_load_win_vuln_bootkits.yml" "Hashes" >}}{{< tip >}}detects loading using hashes only{{< /tip >}} 

{{< /details >}}

{{< /column >}}


{{< column "mb-2" >}}

#### Sysmon 🔎
{{< details "Expand" >}}
{{< button "https://github.com/magicsword-io/LOLbootkits/tree/main/detections/sysmon/sysmon_config_vulnerable_hashes_block.xml" "Block" >}}{{< tip >}}on hashes{{< /tip >}} 

{{< button "https://github.com/magicsword-io/LOLbootkits/tree/main/detections/sysmon/sysmon_config_vulnerable_hashes.xml" "Alert" >}}{{< tip >}}on hashes{{< /tip >}} 

{{< /details >}}

{{< /column >}}
{{< /block >}}


### Resources
<br>
<li><a href="https://uefi.org/revocationlistfile">https://uefi.org/revocationlistfile</a></li>
<li><a href="https://support.microsoft.com/en-gb/topic/microsoft-guidance-for-applying-secure-boot-dbx-update-kb4575994-e3b9e4cb-a330-b3ba-a602-15083965d9ca">https://support.microsoft.com/en-gb/topic/microsoft-guidance-for-applying-secure-boot-dbx-update-kb4575994-e3b9e4cb-a330-b3ba-a602-15083965d9ca</a></li>
<br>

### CVE

<li><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=Black Lotus Microsoft Windows 8.1">Black Lotus Microsoft Windows 8.1</a></li>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           | bootmgfw.efi |
| MD5                | [](https://www.virustotal.com/gui/file/) |
| SHA1               | [](https://www.virustotal.com/gui/file/) |
| SHA256             | [B15095CBB09505C8354657EF7DF0FA4046F5F9DC74B26EF12A7D83E82A718322](https://www.virustotal.com/gui/file/B15095CBB09505C8354657EF7DF0FA4046F5F9DC74B26EF12A7D83E82A718322) |
| Authentihash MD5   | [](https://www.virustotal.com/gui/search/authentihash%253A) |
| Authentihash SHA1  | [](https://www.virustotal.com/gui/search/authentihash%253A) |
| Authentihash SHA256| [C1547CF902570207A9694B6B8E353FE41419DB6A3802221DDF10FB8F86947804](https://www.virustotal.com/gui/search/authentihash%253AC1547CF902570207A9694B6B8E353FE41419DB6A3802221DDF10FB8F86947804) |


#### Imports
{{< details "Expand" >}}

{{< /details >}}
#### Imports
{{< details "Expand" >}}

{{< /details >}}
#### ImportedFunctions
{{< details "Expand" >}}

{{< /details >}}
#### ExportedFunctions
{{< details "Expand" >}}

{{< /details >}}

#### Signature
{{< details "Expand" >}}

{{< /details >}}
-----



[*source*](https://github.com/magicsword-io/LOLbootkits/tree/main/yaml/2a9c12a2-bc01-4af2-bb23-a5f1fcba5bdc.yaml)

*last_updated:* 2023-07-31








{{< /column >}}
{{< /block >}}
