+++

description = ""
title = "d7cc6936-4efd-40a1-bef3-ea4da008ae4c"
weight = 10
displayTitle = "d7cc6936-4efd-40a1-bef3-ea4da008ae4c"
+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# d7cc6936-4efd-40a1-bef3-ea4da008ae4c ![:inline](/images/twitter_verified.png) 


### Description

This was provided by Cumulus Network and revoked Jul-20
- **UUID**: d7cc6936-4efd-40a1-bef3-ea4da008ae4c
- **Created**: 2023-05-22
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLbootkits/raw/main/bootkits/.bin" "Download" >}}
{{< tip "warning" >}}

{{< /tip >}}

### Commands

```
bcdedit /copy &#34;{current}&#34; /d &#34;LOLDrivers&#34; | {% if ($_ -match &#39;{\S+}&#39;) { bcdedit /set $matches[0] path \windows\temp\ } }
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

<li><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-10713">CVE-2020-10713</a></li>
<li><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-14308">CVE-2020-14308</a></li>
<li><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-14309">CVE-2020-14309</a></li>
<li><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-14310">CVE-2020-14310</a></li>
<li><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-14311">CVE-2020-14311</a></li>
<li><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-15705">CVE-2020-15705</a></li>
<li><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-15706">CVE-2020-15706</a></li>
<li><a href="https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-15707">CVE-2020-15707</a></li>

### Known Vulnerable Samples

| Property           | Value |
|:-------------------|:------|
| Filename           |  |
| MD5                | [](https://www.virustotal.com/gui/file/) |
| SHA1               | [](https://www.virustotal.com/gui/file/) |
| SHA256             | [E4FF4E538B4758E8E49010ED16D6D5380417B146F3E8806ACB3AC40611646FDB](https://www.virustotal.com/gui/file/E4FF4E538B4758E8E49010ED16D6D5380417B146F3E8806ACB3AC40611646FDB) |
| Authentihash MD5   | [](https://www.virustotal.com/gui/search/authentihash%253A) |
| Authentihash SHA1  | [](https://www.virustotal.com/gui/search/authentihash%253A) |
| Authentihash SHA256| [EAFF8C85C208BA4D5B6B8046F5D6081747D779BADA7768E649D047FF9B1F660C](https://www.virustotal.com/gui/search/authentihash%253AEAFF8C85C208BA4D5B6B8046F5D6081747D779BADA7768E649D047FF9B1F660C) |


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



[*source*](https://github.com/magicsword-io/LOLbootkits/tree/main/yaml/d7cc6936-4efd-40a1-bef3-ea4da008ae4c.yaml)

*last_updated:* 2023-07-31








{{< /column >}}
{{< /block >}}
