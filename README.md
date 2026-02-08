# zipper
![Platform](https://img.shields.io/badge/Platform-all-blue)
![Supported Versions](https://img.shields.io/badge/Supported%20Versions-12.*-blue)

A simple cross-platform zipping and unzipping module for Omnis Studio, powered by oProcess.

## How to use

Create an object reference, and get the API object from the zipper library
```
Do $modes.$getapiobject('zipper') Returns zipper
```

## Methods

### $zip(pSource, pDestination)

| Name | Type | Required | Description |
|-|-|-|-|
| `pSource` | `Character`  | Yes | Filepath to input file or folder |
| `pDestination` | `Character`  | Yes | Filepath to output zip archive |

### $unzip(pSource, pDestination)

| Name | Type | Required | Description |
|-|-|-|-|
| `pSource` | `Character`  | Yes | Filepath to zip archive |
| `pDestination` | `Character`  | Yes | Filepath to extract the archive to |


