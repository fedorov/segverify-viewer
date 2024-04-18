# idc-viewers-sandbox-gha-testing

Repo used to store GitHub actions for the following IDC repositories:
- https://github.com/ImagingDataCommons/ViewersV3
- https://github.com/ImagingDataCommons/ohif-idc-mode
- https://github.com/ImagingDataCommons/ohif-gcp-mode

## GitHub Actions
- **ohif/deploy-v3**: Deploys a preview of [ViewersV3](https://github.com/ImagingDataCommons/ViewersV3)'s master branch
- **ohif/deploy-v3-with-add-ons**: Deploys a preview of [ViewersV3](https://github.com/ImagingDataCommons/ViewersV3)'s master branch already configured with the latest changes from [ohif-gcp-mode](https://github.com/ImagingDataCommons/ohif-gcp-mode) and [ohif-gcp-extension](https://github.com/ImagingDataCommons/ohif-gcp-extension)
- **slim/deploy**: Deploys latest slim 
- **slim/deploy-with-dmv**: Deploys latest slim with latest dicom-microscopy-viewer
