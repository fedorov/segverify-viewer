# IDC Viewers Sandbox - GitHub Actions Testing

This repository stores and manages GitHub Actions for various Imaging Data Commons (IDC) repositories.

### Associated IDC Repositories:
- [ViewersV3](https://github.com/ImagingDataCommons/ViewersV3)
- [OHIF IDC Mode](https://github.com/ImagingDataCommons/ohif-idc-mode)
- [OHIF GCP Mode](https://github.com/ImagingDataCommons/ohif-gcp-mode)
- [Slim Viewer](https://github.com/ImagingDataCommons/slim)
- [DICOM Microscopy Viewer](https://github.com/ImagingDataCommons/dicom-microscopy-viewer)

## GitHub Actions Overview

This repository contains the following GitHub Actions for automated deployment and testing across IDC repositories:

- **ohif/deploy-v3**  
  Deploys a preview of the [ViewersV3](https://github.com/ImagingDataCommons/ViewersV3) repository’s `master` branch.
  
- **ohif/deploy-v3-with-add-ons**  
  Deploys a preview of the [ViewersV3](https://github.com/ImagingDataCommons/ViewersV3) `master` branch, pre-configured with the latest changes from:
  - [OHIF GCP Mode](https://github.com/ImagingDataCommons/ohif-gcp-mode)
  - [OHIF GCP Extension](https://github.com/ImagingDataCommons/ohif-gcp-extension)
  
- **slim/deploy**  
  Deploys the latest version of [Slim Viewer](https://github.com/ImagingDataCommons/slim).

- **slim/deploy-with-dmv**  
  Deploys the latest version of [Slim Viewer](https://github.com/ImagingDataCommons/slim) along with the latest [DICOM Microscopy Viewer](https://github.com/ImagingDataCommons/dicom-microscopy-viewer).

### Deployment URL
All actions deploy to:  
[https://viewers-sandbox-gha-testing.web.app/](https://viewers-sandbox-gha-testing.web.app/)

---
