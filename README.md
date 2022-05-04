# ZIP Action
```yaml
	-
		name: Zip Files
		uses: aquacloud-dev/action-zip@main
		with:
			files: .next,public
			output: dist.zip

```


<!-- action-docs-description -->
## Description

Zip Folder/Files


<!-- action-docs-description -->

<!-- action-docs-inputs -->
## Inputs

| parameter | description | required | default |
| - | - | - | - |
| files | Files to zip | `true` |  |
| output | Zip filename | `true` |  |



<!-- action-docs-inputs -->

<!-- action-docs-outputs -->
## Outputs

| parameter | description |
| - | - |
| zip_file | Zip file |



<!-- action-docs-outputs -->

<!-- action-docs-runs -->
## Runs

This action is an `composite` action.


<!-- action-docs-runs -->
