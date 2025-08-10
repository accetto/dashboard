# CHANGELOG

## Project `accetto/dashboard`

***

### Release 25.08

Added Debian images with [Brave Browser][brave].

### Release 25.05

Project's `CHANGELOG` file has been added and the `README` file updated.

The service *badgen.net*, which was unreachable for some time already, has been replaced by the service [Shields.io][service-shields-io].

Also a new helper script `utils/util-dashboard.sh` has been added.

- Just follow the embedded help to generate temporary helper files named as `scrap_<target_hub>-dashboard.md`.
- Check the helper files and then copy manually their contents into the deployment dashboard files named as `<target_hub>-dashboard.md`.

Usage examples (being inside the `utils`) directory:

```bash
### this will generate a helper file 'scrap_github-dashboard.md'
### copy its contents into the deployment file 'github-dashboard.md'
./util-dashboard.sh github

### output
Wait... Making a new dashboard markdown file 'scrap_github-dashboard.md'... The exiting file will be overwritten.

### this will generate a helper file 'scrap_dockerhub-dashboard.md'
### copy its contents into the deployment file 'dockerhub-dashboard.md'
./util-dashboard.sh dockerhub

### output
Wait... Making a new dashboard markdown file 'scrap_dockerhub-dashboard.md'... The exiting file will be overwritten.
```

### Release 20.10

The first release.

***

[service-shields-io]: https://shields.io/

[brave]: https://brave.com/
