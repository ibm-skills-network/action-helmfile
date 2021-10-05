# action-helmfile

Configure [helm][], [helmfile][], and the following helm plugins.

- [helm-diff][]
- [helm-secrets][]
- [helm-s3][]
- [helm-git][]

## Usage

Add the following to your workflow

```yml
- name: Configure helm, helmfile, and helm plugins
  uses: ibm-skills-network/action-helmfile@main
```

## Optional Inputs

You may choose to override the installed versions. Visit their GitHub releases page and grab the tag name.

- `helm-version`: helm version.
- `helmfile-version`: helmfile version
- `helm-diff-version`: helm-diff version
- `helm-secrets-version`: helm-secrets version
- `helm-s3-version`: helm-s3 version
- `helm-git-version`: helm-git version

Example

```yml
- name: Configure helm, helmfile, and helm plugins
  uses: ibm-skills-network/action-helmfile@main
  with:
    helmfile-version: "v0.141.0"
    helm-secrets-version: "3.8.0
```

[helm]: https://github.com/helm/helm
[helmfile]: https://github.com/roboll/helmfile
[helm-diff]: https://github.com/databus23/helm-diff
[helm-secrets]: https://github.com/jkroepke/helm-secrets
[helm-s3]: https://github.com/hypnoglow/helm-s3.git
[helm-git]: https://github.com/aslafy-z/helm-git
