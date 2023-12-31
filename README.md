# Schmitz Catz Scoop Awesome Bucket

![Scoop Awesome Bucket](https://img.shields.io/badge/scoop-awesome--bucket-blue?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHRpdGxlPmljZS1jcmVhbTwvdGl0bGU+PHBhdGggZmlsbD0iI2VmZWZlZiIgZD0iTTE3LjUgNi4wNUMxNy4yNSAzLjIyIDE0Ljg5IDEgMTIgMVM2Ljc1IDMuMjIgNi41IDYuMDVDNS4wOSA2LjI4IDQgNy41IDQgOUM0IDEwLjY2IDUuMzQgMTIgNyAxMkwxMiAyMkwxNyAxMkMxOC42NiAxMiAyMCAxMC42NiAyMCA5QzIwIDcuNSAxOC45MSA2LjI4IDE3LjUgNi4wNU0xMiAxNy41M0w4Ljg5IDExLjMxQzguOTUgMTEuMjYgOSAxMS4yMSA5LjA4IDExLjE2QzkuOTMgMTEuNjkgMTAuOTMgMTIgMTIgMTJTMTQuMDcgMTEuNjkgMTQuOTIgMTEuMTZDMTUgMTEuMjEgMTUuMDUgMTEuMjYgMTUuMTEgMTEuMzFMMTIgMTcuNTNaIiAvPjwvc3ZnPg==)
[![Tests](https://github.com/schmitzCatz/awesome-scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/schmitzCatz/awesome-scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/schmitzCatz/awesome-scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/schmitzCatz/awesome-scoop-bucket/actions/workflows/excavator.yml)

Awesome bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## 📚 Additional Applications

| Application               |Manifest               | Link                                                  | Command                                       |
|---                        |---                    |---                                                    |---                                            |
|Orca Slicer                |`orca-slicer`          |<https://github.com/SoftFever/OrcaSlicer>              |```scoop install orca-slicer```                |
|Contextmenumanager         |`contextmenumanager`   |<https://github.com/BluePointLilac/ContextMenuManager> |```scoop install conextmenumanager```          |
|FlipperAnimationManager    |`FlipperAM`            |<https://github.com/Ooggle/FlipperAnimationManager>    |```scoop install flipper-animation-manager```  |

## 🚀 How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add awesome-scoop-bucket https://github.com/schmitzCatz/awesome-scoop-bucket
scoop install scoop-awesome-bucket/<manifestname>
```

## 🤝 How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.

Hash installationfiles on windows:

```pwsh
certutil -hashfile "filename.exe" SHA256
```

Or:

```pwsh
Get-FileHash "filename"
```

## ⚖️ License

 [MIT](https://choosealicense.com/licenses/mit/#)
