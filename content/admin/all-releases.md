---
title: GitHub Enterprise Server release
intro: 'Documentation for the currently supported and previously deprecated versions of {{site.data.variable.product.prodname}}.'
allowTitleToDifferFromFilename: true
version:
  
---

## Currently support

See {data variables.product.prodname}(http://github.com/enterprise) for information about the latest release.

{for supportedRelease in enterpriseServerReleases}
- {data variables.product.prodname }{{supportRelease}}{{supportRelease}})
{endfor}

## Deprecated

Documentation for deprecated versions remains available but is no longer maintained.

{for deprecatedRelease in enterpriseServerReleases.deprecatedReleasesWithNewFormat}
- Enterprise Server {{deprecatedRelease}}(/enterprise-server@{{deprecatedRelease}})


{ for deprecatedReleaseLegacyFormat in enterpriseServerReleases.deprecatedReleasesWithLegacyFormat}
- Enterprise Server {{deprecatedReleaseLegacyFormat}}(/enterprise/{{deprecatedReleaseLegacyFormat}})


## Deprecated developer documentation

Developer documentation for deprecated versions remains available but is no longer maintained.

{for deprecatedDevRelease in enterpriseServerReleases.deprecatedReleasesOnDeveloperSite}
- Enterprise Server {{deprecatedDevRelease}}(http://developer.github.com/enterprise/{{deprecatedDevRelease}})
{endfor}
