+++

description = ""
title = "bf3c5a6b-8fac-470b-a458-c84e7fed7dc7"
weight = 10
displayTitle = "bf3c5a6b-8fac-470b-a458-c84e7fed7dc7"
+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# bf3c5a6b-8fac-470b-a458-c84e7fed7dc7 ![:inline](/images/twitter_verified.png) 


### Description

This was provided by Intel Corporation and revoked Jul-20
- **UUID**: bf3c5a6b-8fac-470b-a458-c84e7fed7dc7
- **Created**: 2023-05-22
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

{{< button "https://github.com/magicsword-io/LOLDrivers/raw/main/drivers/.bin" "Download" >}}
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
{{< button "https://github.com/magicsword-io/LOLDrivers/tree/main/detections/sigma/driver_load_win_vuln_drivers_names.yml" "Names" >}}{{< tip >}}detects loading using name only{{< /tip >}} 


{{< button "https://github.com/magicsword-io/LOLDrivers/tree/main/detections/sigma/driver_load_win_vuln_drivers.yml" "Hashes" >}}{{< tip >}}detects loading using hashes only{{< /tip >}} 

{{< /details >}}

{{< /column >}}


{{< column "mb-2" >}}

#### Sysmon 🔎
{{< details "Expand" >}}
{{< button "https://github.com/magicsword-io/LOLDrivers/tree/main/detections/sysmon/sysmon_config_vulnerable_hashes_block.xml" "Block" >}}{{< tip >}}on hashes{{< /tip >}} 

{{< button "https://github.com/magicsword-io/LOLDrivers/tree/main/detections/sysmon/sysmon_config_vulnerable_hashes.xml" "Alert" >}}{{< tip >}}on hashes{{< /tip >}} 

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
| SHA256             | [BAE97EFC507382C0BDF7B1E74DBC38C0E31BF65186B7989CD9C7AF29DA27F656](https://www.virustotal.com/gui/file/BAE97EFC507382C0BDF7B1E74DBC38C0E31BF65186B7989CD9C7AF29DA27F656) |
| Authentihash MD5   | [](https://www.virustotal.com/gui/search/authentihash%253A) |
| Authentihash SHA1  | [](https://www.virustotal.com/gui/search/authentihash%253A) |
| Authentihash SHA256| [3A4F74BEAFAE2B9383AD8215D233A6CF3D057FB3C7E213E897BEEF4255FAEE9D](https://www.virustotal.com/gui/search/authentihash%253A3A4F74BEAFAE2B9383AD8215D233A6CF3D057FB3C7E213E897BEEF4255FAEE9D) |


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



[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/bf3c5a6b-8fac-470b-a458-c84e7fed7dc7.yaml)

*last_updated:* 2023-07-22








{{< /column >}}
{{< /block >}}