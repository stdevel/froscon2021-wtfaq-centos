class: center, middle

# Aktuelle Entwicklungen

---

## Red Hat lenkt ein

Community reagierte.red[*] ablehnend, lenkte Red Hat ein:

- **Red Hat Developer Subscription** wird erweitert:
  - bis zu 16 Systeme
  - auch ausdrücklich Produktion und Cloud-Nutzung erlaubt
  - kein Support-Anspruch
  - Red Hat Kundenkonto benötigt
- Lösung nur für kleinere Kund:innen anwendbar

.footnote[.red.bold[*] siehe z.B. [folgende Petition](https://www.change.org/p/centos-governing-board-do-not-destroy-centos-by-using-it-as-a-rhel-upstream)]

???

Die Petition erreicht in kurzer Zeit 10.000 Unterschriften

---

## Red Hat lenkt ein

- Neu ist auch die **Developer Subscription for Teams**:
  - bis zu 25.000 Systeme
  - ausschließlich für Entwicklungssysteme
  - Beantragung über **Sales Associate**
  - Gegen **Aufpreis** auch Support
--

- Nur für Kund:innen anwendbar, die **reine Entwicklungsumgebungen** auf CentOS betrieben haben

---

## Forks

.left-column[

Innerhalb weniger Tage entstanden mehrere Projekte:

- [Rocky Linux](https://rockylinux.org/)
- [AlmaLinux](https://almalinux.org/) (*Codename Lenix*)
- [Navy Linux](https://www.navylinux.org/)

Bereits aktive (kommerzielle) Forks:

- [Euro-Linux](https://en.euro-linux.com/)
- [Springdale Linux](https://springdale.math.ias.edu/)

]

.right-column[

![:img Fork CentOS-Meme, 66%](imgs/fork_centos.jpg)

]

???

- Euro-Linux ist ein kommerzielles Derivat einer polnischen Firma
- Springdale Linux ist das Projekt der Princeton Universität, USA (*Institute for Advanced Study and Princeton University in the USA*)

---

## Rocky Linux.red[*]

.left-column75[

- Von **Gregory Kurtzer** erstellter CentOS-Fork
- 100% Bug-kompatibel mit RHEL
- `x86_64` und `aarch64`-Architekturen
- Unabhängige gemeinnützige Organisation (*RESF*), spendenfinanziert
  - Darf laut **Linux Foundation** offiziell den Namen **Linux** tragen

.footnote[.red.bold[*] Rocky McGaugh (†), erstellte die ersten CentOS-Builds]

]

.right-column25[

![:img Rocky Linux-Logo, 100%](imgs/rocky_linux.png)

]

???

- **R**ocky **E**nterprise **S**oftware **F**oundation

---

## Rocky Linux.red[*]

.left-column75[

- [Communitysatzung](https://forums.rockylinux.org/t/community-charter/1933) und [bessere Struktur](https://forums.rockylinux.org/t/organizational-structure/1932) soll Probleme verhindern
- Build-Infrastruktur u.a. auf AWS
- RC erschien Ende April auf Basis von 8.3
- Stabile Version im **Juni 2021** erschienen (*8.4*)

]

.right-column25[

![:img Rocky Linux-Logo, 100%](imgs/rocky_linux.png)

]

???

- **R**ocky **E**nterprise **S**oftware **F**oundation

---

## AlmaLinux.red[*]

.left-column75[

- Von [CloudLinux](https://www.cloudlinux.com/) erstellter RHEL-Fork
  - Distributor und Hoster
  - Hat mit [CloudLinux OS](https://www.cloudlinux.com/all-products/product-overview/cloudlinuxos) schon einen kommerziellen RHEL-Fork erstellt
- 100% Bug-kompatibel mit RHEL
- zuerst `x86_64`-only, mit 8.4 kam auch `aarch64`
- Erstes Release am **30.03.2021**

.footnote[.red.bold[*] lateinisch für Seele]

]

.right-column25[

![:img AlmaLinux-Logo, 100%](imgs/alma_linux.jpg)

]

???

- CloudLinux OS = speziell auf Hosting angepasster Fork mit Eigenentwicklungen (*z.B. Management-Panel-Integration, etc.*)

---

## AlmaLinux

.left-column75[

- Hersteller gibt an jährlich **1 Million USD** in die Entwicklung zu investieren
  - "*Forever free*"
- [Management-Board](https://almalinux.org/foundation/members/) umfasst derzeit 5 Leute
  - CEO [verließ Board](https://blog.cloudlinux.com/why-i-have-decided-to-step-down-from-the-almalinux-os-foundation-board) da "er nicht mehr gebraucht wird"
- [Open Office Hours](https://almalinux.org/blog/almalinux-open-office-hours/) mit Core-Team jeden Montag
- Verschiedene [SIGs](https://wiki.almalinux.org/sigs/) für spezielle Themen (*z.B. Cloud*)
- [Foundation Memberships](https://almalinux.org/foundation/members/) für Mirroring, Sponsoring oder Contributions

]

.right-column25[

![:img AlmaLinux-Logo, 100%](imgs/alma_linux.jpg)

]

---

## Navy Linux

.left-column75[

- Eher unbekanntes Projekt, von **Unixlab**.red[*] gegründet
- verspricht ebenfalls ein 1:1 CentOS-Klon zu sein
- Soll vollständig von einer Community gepflegt werden
  - Derzeit sollen diverse Teams gegründet werden
  - derzeit 4 Core-Mitglieder, ~80 Slack-User
- Seit Juli 2021 existiert die Non-Profit Organization **Navy Foundation**

.footnote[.red.bold[*] unklar, wer dahinter steckt]

]

.right-column25[

![:img Navy Linux-Logo, 100%](imgs/navy_linux.png)

]

???

- Dubios, da keine Informationen über Unixlab
- Delaware Non-Profit Corporation 501c3

---

## Navy Linux

.left-column75[

- Für 8.3 existierten Pakete, aber kein Installer
- Im August erschien das erste stabile [8.4 Release](https://mirror.navylinux.org/navylinux/releases/8.4/)
- derzeit lediglich für `x86_64` verfügbar, `aarch64` und `ppc64le` jedoch [offensichtlich geplant](https://mirror.navylinux.org/selr/releases/8/)
- Zukunft fragwürdig
- Mit **SELR** ist ein EPEL.red[*]-Fork geplant
  - beinhaltet derzeit lediglich spezifische Ceph-, Docker-, Gluster-, NFS Ganesha- und Samba-Versionen

.footnote[.red.bold[*] [Extra Packages for Enterprise Linux](https://fedoraproject.org/wiki/EPEL)]

]

.right-column25[

![:img Navy Linux-Logo, 100%](imgs/navy_linux.png)

]

???

- Dubios, da keine Informationen über Unixlab
- SELR = **S**table **E**nterprise **L**inux **R**epository

---

class: small

## Vergleich

|   | RHEL | Rocky Linux | AlmaLinux | Navy Linux |
| - | ---- | ----------- | --------- | ---------- |
| Architekturen | x86_64, aarch64, s390z, ppc64 | x86_64, aarch64 | x86_64, aarch64 | x86_64 |
| Vagrantbox | Ja | Ja | Ja | Nein |
| Verfügbare Pakete | ~6.300 | ~5.300 | ~ 5.300 | ~6.600 |
| Mirror | unbekannt (CDN) | ~120 | ~170 | 5 |
| Migration | CentOS 7/8, Oracle Linux [ab 8.3](https://bugzilla.redhat.com/show_bug.cgi?id=1944815) | [CentOS 8](https://github.com/rocky-linux/rocky-tools/tree/main/migrate2rocky) | [CentOS, RHEL, Rocky Linux, Oracle Linux](https://github.com/AlmaLinux/almalinux-deploy) | - |
| Support | ja | ja (z.B. CIQ) | ja | unklar |
| Secure Boot | ja | ja | nein | unklar |
| Community | [Customer Portal Community](https://access.redhat.com/community) | [Forum](https://forums.rockylinux.org), [Chat](https://chat.rockylinux.org) | [Discourse](https://almalinux.discourse.group/), [Chat](https://chat.almalinux.org/) | [Chat](https://navylinux.slack.com/) |

---

## Migrationsskripte

Migration nach Rocky Linux:

```shell
# curl -LO https://raw.githubusercontent.com/rocky-linux/rocky-tools/main/
migrate2rocky/migrate2rocky.sh
# bash migrate2rocky.sh -rV
```

Migration nach AlmaLinux:

```shell
# curl -LO https://raw.githubusercontent.com/AlmaLinux/almalinux-deploy/master/
almalinux-deploy.sh
# bash almalinux-deploy.sh
```

---

## AlmaLinux ELevate

- Von der [AlmaLinux-Community entwickeltes Tool](https://almalinux.org/elevate)
- Tool zum Migrieren von CentOS 7 nach EL8:
  - CentOS Stream
  - AlmaLinux / Rocky Linux
  - Oracle Linux 8
- basierend auf [Red Hat LEAPP](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html-single/upgrading_from_rhel_7_to_rhel_8/index)
- Quellcode [auf GitHub verfügbar](https://github.com/AlmaLinux/leapp-repository/tree/almalinux)

---

## Release-Abstände

.left-column[

RHEL 8.4 erschien am 18.05.2021.

- AlmaLinux: 26.05.2021 (**8 Tage**)
  - `aarch64`: 30.06.2021 (**43 Tage**)
- Rocky Linux: 21.06.2021 (**34 Tage**)
- Navy Linux: 01.08.2021 (**75 Tage**)
- CentOS: 03.06.2021 (**16 Tage**)

]

.right-column[

RHEL 8.5 erschien am 09.11.2021.

- AlmaLinux: 11.11.2021 (**2 Tage**)
- Rocky Linux: 18.11.2021 (**7 Tage**)
- CentOS: 26.11.2021 (**15 Tage**)
- Navy Linux: 🤷🏻‍♂️

]

---

## Update-Zyklen

- Den meisten Anwender:innen sind schnell veröffentlichte Patches wichtig
  - Wie **schnell** sind die jeweiligen Forks?
- Auswertung vom *01.06.2021 - 09.12.2021*
--

- Für den Vergleich wurden die folgenden **Quellen** herangezogen:
  - [Red Hat Security Advisories](https://access.redhat.com/security/security-updates/)
  - [Rocky Linux Errata](https://errata.rockylinux.org/)
  - [AlmaLinux Errata](https://errata.almalinux.org/)
- Navy Linux stellt derzeit keine Errata-Informationen zur Verfügung
- Die vollständige tabellarische Auswertung ist hier zu finden: [[klick!]](https://github.com/stdevel/froscon2021-wtfaq-centos/blob/main/errata_drift.xlsx)

???

- Sicherheitsfixes für OS ohne aufpreispflichtige Erweiterungen (*HA, Realtime, Cluster*)

---

![:img Auswertung, 100%](imgs/errata_drift.png)

???

- AlmaLinux liefert sehr schnell
  - offensichtlich kleiner Fehler in den Metadaten
- Rocky Linux hatte anfangs große Probleme zeitnah zu liefern
  - Lücken in Errata

---

## Update-Zyklen

- AlmaLinux liefert im Mittel innerhalb von **2 Tagen** 🚀
- Rocky Linux hatte bis **Mitte Juli** deutliche **Probleme** Patches zeitnah bereitzustellen
  - seitdem werden Patches i.d.r. innerhalb von **17 Tagen** ausgeliefert
  - Errata-Pipeline anscheinend noch [nicht ausgereift](https://forums.rockylinux.org/t/some-errata-missing-in-comparison-with-rhel-and-almalinux/)
  - Messbarkeit, wie "schnell" Rocky Linux liefert ist so leider komplex
- nicht jeder Patch wird von den Forks nachgebaut
  - z.B. Kernel Live-Patching
  - für manche Paket-Upgrades scheinen Patches zu fehlen
