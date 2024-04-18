# Setup Velero

Install a specific version of velero binary on the runner.

## Example

Acceptable values are any semantic version string like v1.13.2 Use this action in workflow to define which version of velero will be used.

```yaml
- name: Setup velero
  uses: skifahrer/setup-velero@v1
  with:
     version: 'v1.13.2' 
```

> [!NOTE]
> Velero versions can be found here: https://github.com/vmware-tanzu/velero/releases

## Contributing

This project welcomes contributions and suggestions. 

## Support

setup-velero is an open source project that is not covered by any support policy. [Please search open issues here](https://github.com/skifahrer/setup-velero/issues), and if your issue isn't already represented please [open a new one](https://github.com/skifahrer/setup-velero/issues/new/choose). The project maintainers will respond to the best of their abilities.