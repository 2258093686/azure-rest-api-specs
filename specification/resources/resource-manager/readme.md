# Resource

> see https://aka.ms/autorest

This is the AutoRest configuration file for Resource.

---

## Getting Started

To build the SDK for Resource, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`

---

## Configuration

### Basic Information

These are the global settings for the Resource API.

``` yaml
openapi-type: arm
tag: package-2022-12
```

``` yaml $(package-privatelinks)
tag: package-privatelinks-2020-05
```

``` yaml $(package-features)
tag: package-features-2021-07
```

``` yaml $(package-locks)
tag: package-locks-2020-05
```

``` yaml $(package-policy)
tag: package-policy-2025-03-stable
```

``` yaml $(package-databoundaries)
tag: package-databoundaries-2024-08
```

``` yaml $(package-resources)
tag: package-resources-2025-04
```

``` yaml $(package-subscriptions)
tag: package-subscriptions-2022-12
```

``` yaml $(package-links)
tag: package-links-2016-09
```

``` yaml $(package-managedapplications)
tag: package-managedapplications-2018-06
```

``` yaml $(package-changes)
tag: package-changes-2022-05
```

``` yaml $(package-snapshots)
tag: package-snapshots-2022-11
```

### Tag: package-policy-2025-03-stable

These settings apply only when `--tag=package-policy-2025-03-stable` is specified on the command line.

```yaml $(tag) == 'package-policy-2025-03-stable'
input-file:
  - Microsoft.Authorization/stable/2025-03-01/policyAssignments.json
  - Microsoft.Authorization/stable/2025-03-01/policyDefinitions.json
  - Microsoft.Authorization/stable/2025-03-01/policyDefinitionVersions.json
  - Microsoft.Authorization/stable/2025-03-01/policySetDefinitions.json
  - Microsoft.Authorization/stable/2025-03-01/policySetDefinitionVersions.json
  - Microsoft.Authorization/stable/2025-03-01/policyTokens.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2025-01

These settings apply only when `--tag=package-policy-2025-01` is specified on the command line.

```yaml $(tag) == 'package-policy-2025-01'
input-file:
- Microsoft.Authorization/stable/2025-01-01/policyDefinitions.json
- Microsoft.Authorization/stable/2025-01-01/policyDefinitionVersions.json
- Microsoft.Authorization/stable/2025-01-01/policySetDefinitions.json
- Microsoft.Authorization/stable/2025-01-01/policySetDefinitionVersions.json
- Microsoft.Authorization/stable/2025-01-01/policyAssignments.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2024-12-preview

These settings apply only when `--tag=package-policy-2024-12-preview` is specified on the command line.

```yaml $(tag) == 'package-policy-2024-12-preview'
input-file:
- Microsoft.Authorization/preview/2024-12-01-preview/policyExemptions.json
- Microsoft.Authorization/preview/2024-12-01-preview/policyVariables.json
- Microsoft.Authorization/preview/2024-12-01-preview/policyVariableValues.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2024-05

These settings apply only when `--tag=package-policy-2024-05` is specified on the command line.

```yaml $(tag) == 'package-policy-2024-05'
input-file:
- Microsoft.Authorization/stable/2024-05-01/policyDefinitions.json
- Microsoft.Authorization/stable/2024-05-01/policyDefinitionVersions.json
- Microsoft.Authorization/stable/2024-05-01/policySetDefinitions.json
- Microsoft.Authorization/stable/2024-05-01/policySetDefinitionVersions.json
- Microsoft.Authorization/stable/2024-05-01/policyAssignments.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2024-04

These settings apply only when `--tag=package-policy-2024-04` is specified on the command line.

```yaml $(tag) == 'package-policy-2024-04'
input-file:
  - Microsoft.Authorization/stable/2024-04-01/policyAssignments.json
```


### Tag: package-policy-2023-04

These settings apply only when `--tag=package-policy-2023-04` is specified on the command line.

``` yaml $(tag) == 'package-policy-2023-04'
input-file:
- Microsoft.Authorization/stable/2020-09-01/dataPolicyManifests.json
- Microsoft.Authorization/stable/2023-04-01/policyDefinitions.json
- Microsoft.Authorization/stable/2023-04-01/policyDefinitionVersions.json
- Microsoft.Authorization/stable/2023-04-01/policySetDefinitions.json
- Microsoft.Authorization/stable/2023-04-01/policySetDefinitionVersions.json
- Microsoft.Authorization/stable/2023-04-01/policyAssignments.json
- Microsoft.Authorization/preview/2022-07-01-preview/policyExemptions.json
- Microsoft.Authorization/preview/2022-08-01-preview/policyVariables.json
- Microsoft.Authorization/preview/2022-08-01-preview/policyVariableValues.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2023-04-only

These settings apply only when `--tag=package-policy-2023-04-only` is specified on the command line.

``` yaml $(tag) == 'package-policy-2023-04-only'
input-file:
  - Microsoft.Authorization/stable/2023-04-01/policyDefinitions.json
  - Microsoft.Authorization/stable/2023-04-01/policyDefinitionVersions.json
  - Microsoft.Authorization/stable/2023-04-01/policySetDefinitions.json
  - Microsoft.Authorization/stable/2023-04-01/policySetDefinitionVersions.json
  - Microsoft.Authorization/stable/2023-04-01/policyAssignments.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```


### Tag: package-resources-2023-07

These settings apply only when `--tag=package-resources-2023-07` is specified on the command line.

``` yaml $(tag) == 'package-resources-2023-07'
input-file:
  - Microsoft.Resources/stable/2023-07-01/resources.json
```

### Tag: package-resources-2024-03

These settings apply only when `--tag=package-resources-2024-03` is specified on the command line.

``` yaml $(tag) == 'package-resources-2024-03'
input-file:
  - Microsoft.Resources/stable/2024-03-01/resources.json
```

### Tag: package-resources-2024-07

These settings apply only when `--tag=package-resources-2024-07` is specified on the command line.

``` yaml $(tag) == 'package-resources-2024-07'
input-file:
  - Microsoft.Resources/stable/2024-07-01/resources.json
```

### Tag: package-resources-2024-11

These settings apply only when `--tag=package-resources-2024-11` is specified on the command line.

``` yaml $(tag) == 'package-resources-2024-11'
input-file:
  - Microsoft.Resources/stable/2024-11-01/resources.json
```

### Tag: package-resources-2025-03

These settings apply only when `--tag=package-resources-2025-03` is specified on the command line.

``` yaml $(tag) == 'package-resources-2025-03'
input-file:
  - Microsoft.Resources/stable/2025-03-01/resources.json
```

### Tag: package-resources-2025-04

These settings apply only when `--tag=package-resources-2025-04` is specified on the command line.

``` yaml $(tag) == 'package-resources-2025-04'
input-file:
  - Microsoft.Resources/stable/2025-04-01/resources.json
```

### Tag: package-2022-12

These settings apply only when `--tag=package-2022-12` is specified on the command line.

``` yaml $(tag) == 'package-2022-12'
input-file:
  - Microsoft.Resources/stable/2022-12-01/subscriptions.json
```

### Tag: package-policy-2022-08-preview-only

These settings apply only when `--tag=package-policy-2022-08-preview-only` is specified on the command line.

``` yaml $(tag) == 'package-policy-2022-08-preview-only'
input-file:
- Microsoft.Authorization/preview/2022-08-01-preview/policyVariables.json
- Microsoft.Authorization/preview/2022-08-01-preview/policyVariableValues.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2022-07-preview-only

These settings apply only when `--tag=package-policy-2022-07-preview-only` is specified on the command line.

``` yaml $(tag) == 'package-policy-2022-07-preview-only'
input-file:
- Microsoft.Authorization/preview/2022-07-01-preview/policyExemptions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2022-06-only

These settings apply only when `--tag=package-policy-2022-06-only` is specified on the command line.

``` yaml $(tag) == 'package-policy-2022-06-only'
input-file:
- Microsoft.Authorization/stable/2022-06-01/policyAssignments.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2022-06

These settings apply only when `--tag=package-policy-2022-06` is specified on the command line.

``` yaml $(tag) == 'package-policy-2022-06'
input-file:
- Microsoft.Authorization/stable/2020-09-01/dataPolicyManifests.json
- Microsoft.Authorization/stable/2021-06-01/policyDefinitions.json
- Microsoft.Authorization/stable/2021-06-01/policySetDefinitions.json
- Microsoft.Authorization/stable/2022-06-01/policyAssignments.json
- Microsoft.Authorization/preview/2022-07-01-preview/policyExemptions.json
- Microsoft.Authorization/preview/2022-08-01-preview/policyVariables.json
- Microsoft.Authorization/preview/2022-08-01-preview/policyVariableValues.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-changes-2023-03-01-preview

These settings apply only when `--tag=package-changes-2023-03-01-preview` is specified on the command line.

``` yaml $(tag) == 'package-changes-2023-03-01-preview'
input-file:
- Microsoft.Resources/preview/2023-03-01-preview/changes.json
```

### Tag: package-changes-2023-07-01-preview

These settings apply only when `--tag=package-changes-2023-07-01-preview` is specified on the command line.

``` yaml $(tag) == 'package-changes-2023-07-01-preview'
input-file:
- Microsoft.Resources/preview/2023-07-01-preview/changes.json
```

### Tag: package-changes-2024-06-01-preview

These settings apply only when `--tag=package-changes-2024-06-01-preview` is specified on the command line.

``` yaml $(tag) == 'package-changes-2024-06-01-preview'
input-file:
- Microsoft.Resources/preview/2024-06-01-preview/changes.json
```

### Tag: package-snapshots-2022-11

These settings apply only when `--tag=package-snapshots-2022-11` is specified on the command line.

``` yaml $(tag) == 'package-snapshots-2022-11'
input-file:
- Microsoft.Resources/preview/2022-11-01-preview/snapshots.json
```

### Tag: package-databoundaries-2024-08

These settings apply only when `--tag=package-databoundaries-2024-08` is specified on the command line.

``` yaml $(tag) == 'package-databoundaries-2024-08'
input-file:
  - Microsoft.Resources/stable/2024-08-01/dataBoundaries.json
```

### Tag: package-changes-2022-05

These settings apply only when `--tag=package-changes-2022-05` is specified on the command line.

``` yaml $(tag) == 'package-changes-2022-05'
input-file:
- Microsoft.Resources/stable/2022-05-01/changes.json
```

### Tag: package-changes-2022-03-01-preview

These settings apply only when `--tag=package-changes-2022-03-01-preview` is specified on the command line.

``` yaml $(tag) == 'package-changes-2022-03-01-preview'
input-file:
- Microsoft.Resources/preview/2022-03-01-preview/changes.json
```

### Tag: package-policy-2021-06

These settings apply only when `--tag=package-policy-2021-06` is specified on the command line.

``` yaml $(tag) == 'package-policy-2021-06'
input-file:
- Microsoft.Authorization/stable/2020-09-01/dataPolicyManifests.json
- Microsoft.Authorization/stable/2021-06-01/policyAssignments.json
- Microsoft.Authorization/stable/2021-06-01/policyDefinitions.json
- Microsoft.Authorization/stable/2021-06-01/policySetDefinitions.json
- Microsoft.Authorization/preview/2020-07-01-preview/policyExemptions.json
- Microsoft.Authorization/preview/2022-08-01-preview/policyVariables.json
- Microsoft.Authorization/preview/2022-08-01-preview/policyVariableValues.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2021-06-only

These settings apply only when `--tag=package-policy-2021-06-only` is specified on the command line.

``` yaml $(tag) == 'package-policy-2021-06-only'
input-file:
- Microsoft.Authorization/stable/2021-06-01/policyAssignments.json
- Microsoft.Authorization/stable/2021-06-01/policyDefinitions.json
- Microsoft.Authorization/stable/2021-06-01/policySetDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-privatelinks-2020-05

These settings apply only when `--tag=package-privatelinks-2020-05` is specified on the command line.

``` yaml $(tag) == 'package-privatelinks-2020-05'
input-file:
- Microsoft.Authorization/stable/2020-05-01/privateLinks.json
```

### Tag: package-locks-2020-05

These settings apply only when `--tag=package-locks-2020-05` is specified on the command line.

``` yaml $(tag) == 'package-locks-2020-05'
input-file:
- Microsoft.Authorization/stable/2020-05-01/locks.json
```

### Tag: package-resources-2022-09

These settings apply only when `--tag=package-resources-2022-09` is specified on the command line.

``` yaml $(tag) == 'package-resources-2022-09'
input-file:
- Microsoft.Resources/stable/2022-09-01/resources.json
```

### Tag: package-policy-2020-09

These settings apply only when `--tag=package-policy-2020-09` is specified on the command line.

``` yaml $(tag) == 'package-policy-2020-09'
input-file:
- Microsoft.Authorization/stable/2020-09-01/dataPolicyManifests.json
- Microsoft.Authorization/stable/2020-09-01/policyAssignments.json
- Microsoft.Authorization/stable/2020-09-01/policyDefinitions.json
- Microsoft.Authorization/stable/2020-09-01/policySetDefinitions.json
- Microsoft.Authorization/preview/2020-07-01-preview/policyExemptions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2020-09-only

These settings apply only when `--tag=package-policy-2020-09-only` is specified on the command line.

``` yaml $(tag) == 'package-policy-2020-09-only'
input-file:
- Microsoft.Authorization/stable/2020-09-01/dataPolicyManifests.json
- Microsoft.Authorization/stable/2020-09-01/policyAssignments.json
- Microsoft.Authorization/stable/2020-09-01/policyDefinitions.json
- Microsoft.Authorization/stable/2020-09-01/policySetDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-locks-2017-04

These settings apply only when `--tag=package-locks-2017-04` is specified on the command line.

``` yaml $(tag) == 'package-locks-2017-04'
input-file:
- Microsoft.Authorization/stable/2017-04-01/locks.json
```

### Tag: package-preview-2020-08

These settings apply only when `--tag=package-preview-2020-08` is specified on the command line.

``` yaml $(tag) == 'package-preview-2020-08'
input-file:
  - Microsoft.Solutions/preview/2020-08-21-preview/managedapplications.json
```

### Tag: package-subscriptions-2022-12

These settings apply only when `--tag=package-subscriptions-2022-12` is specified on the command line.

``` yaml $(tag) == 'package-subscriptions-2022-12'
input-file:
- Microsoft.Resources/stable/2022-12-01/subscriptions.json
```

### Tag: package-subscriptions-2021-01

These settings apply only when `--tag=package-subscriptions-2021-01` is specified on the command line.

``` yaml $(tag) == 'package-subscriptions-2021-01'
input-file:
- Microsoft.Resources/stable/2021-01-01/subscriptions.json
```



### Tag: package-features-2021-07

These settings apply only when `--tag=package-features-2021-07` is specified on the command line.

``` yaml $(tag) == 'package-features-2021-07'
input-file:
- Microsoft.Features/stable/2021-07-01/features.json
- Microsoft.Features/stable/2021-07-01/SubscriptionFeatureRegistration.json

# Needed when there is more than one input file
override-info:
  title: FeatureClient
```

### Tag: package-features-2015-12

These settings apply only when `--tag=package-features-2015-12` is specified on the command line.

``` yaml $(tag) == 'package-features-2015-12'
input-file:
- Microsoft.Features/stable/2015-12-01/features.json
```

### Tag: package-locks-2016-09

These settings apply only when `--tag=package-locks-2016-09` is specified on the command line.

``` yaml $(tag) == 'package-locks-2016-09'
input-file:
- Microsoft.Authorization/stable/2016-09-01/locks.json
```

### Tag: package-locks-2015-01

These settings apply only when `--tag=package-locks-2015-01` is specified on the command line.

``` yaml $(tag) == 'package-locks-2015-01'
input-file:
- Microsoft.Authorization/stable/2015-01-01/locks.json
```

### Tag: package-policy-2020-03

These settings apply only when `--tag=package-policy-2020-03` is specified on the command line.

``` yaml $(tag) == 'package-policy-2020-03'
input-file:
- Microsoft.Authorization/stable/2020-03-01/policyAssignments.json
- Microsoft.Authorization/stable/2020-03-01/policyDefinitions.json
- Microsoft.Authorization/stable/2020-03-01/policySetDefinitions.json
- Microsoft.Authorization/preview/2020-07-01-preview/policyExemptions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2020-07-preview-only

These settings apply only when `--tag=package-policy-2020-07-preview-only` is specified on the command line.

``` yaml $(tag) == 'package-policy-2020-07-preview-only'
input-file:
- Microsoft.Authorization/preview/2020-07-01-preview/policyExemptions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2019-09

These settings apply only when `--tag=package-policy-2019-09` is specified on the command line.

``` yaml $(tag) == 'package-policy-2019-09'
input-file:
- Microsoft.Authorization/stable/2019-09-01/policyAssignments.json
- Microsoft.Authorization/stable/2019-09-01/policyDefinitions.json
- Microsoft.Authorization/stable/2019-09-01/policySetDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2019-06

These settings apply only when `--tag=package-policy-2019-06` is specified on the command line.

``` yaml $(tag) == 'package-policy-2019-06'
input-file:
- Microsoft.Authorization/stable/2019-06-01/policyAssignments.json
- Microsoft.Authorization/stable/2019-06-01/policyDefinitions.json
- Microsoft.Authorization/stable/2019-06-01/policySetDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2019-01

These settings apply only when `--tag=package-policy-2019-01` is specified on the command line.

``` yaml $(tag) == 'package-policy-2019-01'
input-file:
- Microsoft.Authorization/stable/2019-01-01/policyAssignments.json
- Microsoft.Authorization/stable/2019-01-01/policyDefinitions.json
- Microsoft.Authorization/stable/2019-01-01/policySetDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2018-05

These settings apply only when `--tag=package-policy-2018-05` is specified on the command line.

``` yaml $(tag) == 'package-policy-2018-05'
input-file:
- Microsoft.Authorization/stable/2018-05-01/policyAssignments.json
- Microsoft.Authorization/stable/2018-05-01/policyDefinitions.json
- Microsoft.Authorization/stable/2018-05-01/policySetDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2018-03

These settings apply only when `--tag=package-policy-2018-03` is specified on the command line.

``` yaml $(tag) == 'package-policy-2018-03'
input-file:
- Microsoft.Authorization/stable/2018-03-01/policyAssignments.json
- Microsoft.Authorization/stable/2018-03-01/policyDefinitions.json
- Microsoft.Authorization/stable/2018-03-01/policySetDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2017-06

These settings apply only when `--tag=package-policy-2017-06` is specified on the command line.

``` yaml $(tag) == 'package-policy-2017-06'
input-file:
- Microsoft.Authorization/preview/2017-06-01-preview/policyAssignments.json
- Microsoft.Authorization/preview/2017-06-01-preview/policySetDefinitions.json
- Microsoft.Authorization/stable/2016-12-01/policyDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-pure-policy-2017-06

These settings apply only when `--tag=package-pure-policy-2017-06` is specified on the command line.

``` yaml $(tag) == 'package-pure-policy-2017-06'
input-file:
- Microsoft.Authorization/preview/2017-06-01-preview/policyAssignments.json
- Microsoft.Authorization/preview/2017-06-01-preview/policySetDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2017-06-preview-only

These settings apply only when `--tag=package-policy-2017-06-preview-only` is specified on the command line.

``` yaml $(tag) == 'package-policy-2017-06-preview-only'
input-file:
- Microsoft.Authorization/preview/2017-06-01-preview/policyAssignments.json
- Microsoft.Authorization/preview/2017-06-01-preview/policySetDefinitions.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```







### Tag: package-policy-2016-12

These settings apply only when `--tag=package-policy-2016-12` is specified on the command line.

``` yaml $(tag) == 'package-policy-2016-12'
input-file:
- Microsoft.Authorization/stable/2016-12-01/policyDefinitions.json
- Microsoft.Authorization/stable/2016-12-01/policyAssignments.json

# Needed when there is more than one input file
override-info:
  title: PolicyClient
```

### Tag: package-policy-2016-04

These settings apply only when `--tag=package-policy-2016-04` is specified on the command line.

``` yaml $(tag) == 'package-policy-2016-04'
input-file:
- Microsoft.Authorization/stable/2016-04-01/policy.json
```

### Tag: package-policy-2015-10

These settings apply only when `--tag=package-policy-2015-10` is specified on the command line.

``` yaml $(tag) == 'package-policy-2015-10'
input-file:
- Microsoft.Authorization/preview/2015-10-01-preview/policy.json
```

### Tag: package-resources-2021-04

These settings apply only when `--tag=package-resources-2021-04` is specified on the command line.

``` yaml $(tag) == 'package-resources-2021-04'
input-file:
- Microsoft.Resources/stable/2021-04-01/resources.json
```

### Tag: package-resources-2021-01

These settings apply only when `--tag=package-resources-2021-01` is specified on the command line.

``` yaml $(tag) == 'package-resources-2021-01'
input-file:
- Microsoft.Resources/stable/2021-01-01/resources.json
```

### Tag: package-resources-2020-10

These settings apply only when `--tag=package-resources-2020-10` is specified on the command line.

``` yaml $(tag) == 'package-resources-2020-10'
input-file:
  - Microsoft.Resources/stable/2020-10-01/resources.json
```

### Tag: package-resources-2020-08

These settings apply only when `--tag=package-resources-2020-08` is specified on the command line.

``` yaml $(tag) == 'package-resources-2020-08'
input-file:
  - Microsoft.Resources/stable/2020-08-01/resources.json
```

### Tag: package-resources-2020-06

These settings apply only when `--tag=package-resources-2020-06` is specified on the command line.

``` yaml $(tag) == 'package-resources-2020-06'
input-file:
- Microsoft.Resources/stable/2020-06-01/resources.json
```

### Tag: package-resources-2019-10

These settings apply only when `--tag=package-resources-2019-10` is specified on the command line.

``` yaml $(tag) == 'package-resources-2019-10'
input-file:
- Microsoft.Resources/stable/2019-10-01/resources.json
```

### Tag: package-resources-2019-08

These settings apply only when `--tag=package-resources-2019-08` is specified on the command line.

``` yaml $(tag) == 'package-resources-2019-08'
input-file:
- Microsoft.Resources/stable/2019-08-01/resources.json
```

### Tag: package-resources-2019-07

These settings apply only when `--tag=package-resources-2019-07` is specified on the command line.

``` yaml $(tag) == 'package-resources-2019-07'
input-file:
- Microsoft.Resources/stable/2019-07-01/resources.json
```

### Tag: package-resources-2019-0510

These settings apply only when `--tag=package-resources-2019-0510` is specified on the command line.

``` yaml $(tag) == 'package-resources-2019-0510'
input-file:
- Microsoft.Resources/stable/2019-05-10/resources.json
```

### Tag: package-resources-2019-05

These settings apply only when `--tag=package-resources-2019-05` is specified on the command line.

``` yaml $(tag) == 'package-resources-2019-05'
input-file:
- Microsoft.Resources/stable/2019-05-01/resources.json
```

### Tag: package-resources-2019-03

These settings apply only when `--tag=package-resources-2019-03` is specified on the command line.

``` yaml $(tag) == 'package-resources-2019-03'
input-file:
- Microsoft.Resources/stable/2019-03-01/resources.json
```

### Tag: package-resources-2018-05

These settings apply only when `--tag=package-resources-2018-05` is specified on the command line.

``` yaml $(tag) == 'package-resources-2018-05'
input-file:
- Microsoft.Resources/stable/2018-05-01/resources.json
```

### Tag: package-resources-2018-02

These settings apply only when `--tag=package-resources-2018-02` is specified on the command line.

``` yaml $(tag) == 'package-resources-2018-02'
input-file:
- Microsoft.Resources/stable/2018-02-01/resources.json
```

### Tag: package-resources-2017-05

These settings apply only when `--tag=package-resources-2017-05` is specified on the command line.

``` yaml $(tag) == 'package-resources-2017-05'
input-file:
- Microsoft.Resources/stable/2017-05-10/resources.json
```

### Tag: package-resources-2016-09

These settings apply only when `--tag=package-resources-2016-09` is specified on the command line.

``` yaml $(tag) == 'package-resources-2016-09'
input-file:
- Microsoft.Resources/stable/2016-09-01/resources.json
```

### Tag: package-resources-2016-07

These settings apply only when `--tag=package-resources-2016-07` is specified on the command line.

``` yaml $(tag) == 'package-resources-2016-07'
input-file:
- Microsoft.Resources/stable/2016-07-01/resources.json
```

### Tag: package-resources-2016-02

These settings apply only when `--tag=package-resources-2016-02` is specified on the command line.

``` yaml $(tag) == 'package-resources-2016-02'
input-file:
- Microsoft.Resources/stable/2016-02-01/resources.json
```

### Tag: package-resources-2015-11

These settings apply only when `--tag=package-resources-2015-11` is specified on the command line.

``` yaml $(tag) == 'package-resources-2015-11'
input-file:
- Microsoft.Resources/stable/2015-11-01/resources.json
```

### Tag: package-subscriptions-2020-01

These settings apply only when `--tag=package-subscriptions-2020-01` is specified on the command line.

``` yaml $(tag) == 'package-subscriptions-2020-01'
input-file:
  - Microsoft.Resources/stable/2020-01-01/subscriptions.json
```

### Tag: package-subscriptions-2019-11

These settings apply only when `--tag=package-subscriptions-2019-11` is specified on the command line.

``` yaml $(tag) == 'package-subscriptions-2019-11'
input-file:
- Microsoft.Resources/stable/2019-11-01/subscriptions.json
```

### Tag: package-subscriptions-2019-06

These settings apply only when `--tag=package-subscriptions-2019-06` is specified on the command line.

``` yaml $(tag) == 'package-subscriptions-2019-06'
input-file:
- Microsoft.Resources/stable/2019-06-01/subscriptions.json
```

### Tag: package-subscriptions-2018-06

These settings apply only when `--tag=package-subscriptions-2018-06` is specified on the command line.

``` yaml $(tag) == 'package-subscriptions-2018-06'
input-file:
- Microsoft.Resources/stable/2018-06-01/subscriptions.json
```

### Tag: package-subscriptions-2016-06

These settings apply only when `--tag=package-subscriptions-2016-06` is specified on the command line.

``` yaml $(tag) == 'package-subscriptions-2016-06'
input-file:
- Microsoft.Resources/stable/2016-06-01/subscriptions.json
```

### Tag: package-subscriptions-2015-11

These settings apply only when `--tag=package-subscriptions-2015-11` is specified on the command line.

``` yaml $(tag) == 'package-subscriptions-2015-11'
input-file:
- Microsoft.Resources/stable/2015-11-01/subscriptions.json
```

### Tag: package-links-2016-09

These settings apply only when `--tag=package-links-2016-09` is specified on the command line.

``` yaml $(tag) == 'package-links-2016-09'
input-file:
- Microsoft.Resources/stable/2016-09-01/links.json
```

### Tag: package-managedapplications-2019-07

These settings apply only when `--tag=package-managedapplications-2019-07` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2019-07'
input-file:
- Microsoft.Solutions/stable/2019-07-01/managedapplications.json
```

### Tag: package-managedapplications-2018-06

These settings apply only when `--tag=package-managedapplications-2018-06` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2018-06'
input-file:
- Microsoft.Solutions/stable/2018-06-01/managedapplications.json
```

### Tag: package-managedapplications-2017-09

These settings apply only when `--tag=package-managedapplications-2017-09` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2017-09'
input-file:
- Microsoft.Solutions/stable/2017-09-01/managedapplications.json
```

### Tag: package-managedapplications-2016-09

These settings apply only when `--tag=package-managedapplications-2016-09` is specified on the command line.

``` yaml $(tag) == 'package-managedapplications-2016-09'
input-file:
- Microsoft.Solutions/preview/2016-09-01-preview/managedapplications.json
```

### Tag: profile-hybrid-2019-03-01

These settings apply only when `--tag=profile-hybrid-2019-03-01` is specified on the command line.
Creating this tag to pick proper resources from the hybrid profile.

``` yaml $(tag) == 'profile-hybrid-2019-03-01'
input-file:
- Microsoft.Authorization/stable/2016-09-01/locks.json
- Microsoft.Authorization/stable/2016-12-01/policyDefinitions.json
- Microsoft.Authorization/stable/2016-12-01/policyAssignments.json
- Microsoft.Resources/stable/2016-06-01/subscriptions.json
- Microsoft.Resources/stable/2018-05-01/resources.json

override-info:
  title: PolicyClient
```

## Suppression

``` yaml
directive:
  - suppress: UniqueResourcePaths
    from: policySetDefinitions.json
    reason: policy set definition under an extension resource with Microsoft.Management
  - suppress: UniqueResourcePaths
    from: resources.json
    where: $.paths
    reason: route definitions under an extension resource with Microsoft.Management
  - suppress: UniqueResourcePaths
    from: policyDefinitions.json
    reason: policy definition under an extension resource with Microsoft.Management
  - suppress: UniqueResourcePaths
    from: policyAssignments.json
    reason: policy assignment under an extension resource with Microsoft.Management
  - suppress: UniqueResourcePaths
    from: policyExemptions.json
    where: $.paths
    reason: policy exemption under an extension resource with Microsoft.Management
  - suppress: OperationsAPIImplementation
    from: policyAssignments.json
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: OperationsAPIImplementation
    from: privateLinks.json
    where: $.paths
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: OperationsAPIImplementation
    from: policyDefinitions.json
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: OperationsAPIImplementation
    from: policyDefinitionVersions.json
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: OperationsAPIImplementation
    from: policySetDefinitions.json
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: OperationsAPIImplementation
    from: policySetDefinitionVersions.json
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: OperationsAPIImplementation
    from: policyExemptions.json
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: OperationsAPIImplementation
    from: policyVariables.json
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: OperationsAPIImplementation
    from: policyVariableValues.json
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: BodyTopLevelProperties
    from: policyAssignments.json
    reason: Currently systemData is not allowed. Lint bug - collection GET result contains value and nextLink properties.
  - suppress: BodyTopLevelProperties
    from: policyDefinitions.json
    reason: Currently systemData is not allowed. Lint bug - collection GET result contains value and nextLink properties.
  - suppress: BodyTopLevelProperties
    from: policyDefinitionVersions.json
    reason: Currently systemData is not allowed. Lint bug - collection GET result contains value and nextLink properties.
  - suppress: BodyTopLevelProperties
    from: policySetDefinitions.json
    reason: Currently systemData is not allowed. Lint bug - collection GET result contains value and nextLink properties.
  - suppress: BodyTopLevelProperties
    from: policySetDefinitionVersions.json
    reason: Currently systemData is not allowed. Lint bug - collection GET result contains value and nextLink properties.
  - suppress: BodyTopLevelProperties
    from: policyExemptions.json
    where: $.definitions.PolicyExemption.properties
    reason: Currently systemData is not allowed
  - suppress: BodyTopLevelProperties
    from: resources.json
    where: $.definitions.ResourceGroup.properties
    reason: managedBy is a top level property
  - suppress: BodyTopLevelProperties
    from: resources.json
    where: $.definitions.GenericResource.properties
    reason: managedBy is a top level property
  - suppress: BodyTopLevelProperties
    from: resources.json
    where: $.definitions.GenericResourceExpanded.properties
    reason: 'createdTime,changedTime & provisioningState are top-level properties'
  - suppress: BodyTopLevelProperties
    from: resources.json
    where: $.definitions.TagDetails.properties
    reason: TagDetails is a top level property
  - suppress: BodyTopLevelProperties
    from: resources.json
    where: $.definitions.TagValue.properties
    reason: TagValue is a top level property
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.TagValue
    reason: TagValue will be deprecated soon
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.TagDetails
    reason: TagDetails will be deprecated soon
  - suppress: XmsResourceInPutResponse
    from: resources.json
    where: '$.paths["/subscriptions/{subscriptionId}/tagNames/{tagName}"].put'
    reason: TagDetails is not an Azure resource
  - suppress: BodyTopLevelProperties
    from: managedapplications.json
    where: $.definitions.Appliance.properties
    reason: managedBy is a top level property
  - suppress: BodyTopLevelProperties
    from: managedapplications.json
    where: $.definitions.ApplianceDefinition.properties
    reason: managedBy is a top level property
  - suppress: BodyTopLevelProperties
    from: managedapplications.json
    where: $.definitions.AppliancePatchable.properties
    reason: managedBy is a top level property
  - suppress: BodyTopLevelProperties
    from: managedapplications.json
    where: $.definitions.GenericResource.properties
    reason: managedBy is a top level property
  - suppress: OperationsAPIImplementation
    where: $.paths
    from: dataPolicyManifests.json
    reason: operation APIs for Microsoft.Authorization are to be defined in RBAC swagger
  - suppress: EnumInsteadOfBoolean
    where: $.definitions.DataManifestCustomResourceFunctionDefinition.properties.allowCustomProperties
    from: dataPolicyManifests.json
    reason: 'This property can only have two values. '
  - suppress: EnumInsteadOfBoolean
    where: $.definitions.DataPolicyManifestProperties.properties.isBuiltInOnly
    from: dataPolicyManifests.json
    reason: 'This property can only have two values. '
  - suppress: PageableOperation
    where: '$.paths["/providers/Microsoft.Authorization/dataPolicyManifests"].get'
    from: dataPolicyManifests.json
    reason: Pagination not supported. The size of the result list is pretty limited
  - suppress: DescriptionAndTitleMissing
    where: $.definitions.AliasPathMetadata
    from: resources.json
    reason: This was already checked in - not my code
  - suppress: TopLevelResourcesListByResourceGroup
    from: policyDefinitions.json
    reason: Policy definitions are a proxy resource that is only usable on subscriptions or management groups
  - suppress: TopLevelResourcesListByResourceGroup
    from: policyVariables.json
    reason: Policy variables are a proxy resource that is only usable on subscriptions or management groups
  - suppress: TopLevelResourcesListByResourceGroup
    from: policyVariableValues.json
    reason: Policy variable values are a proxy resource that is only usable on subscriptions or management groups
  - suppress: TopLevelResourcesListByResourceGroup
    from: policySetDefinitions.json
    reason: Policy set definitions are a proxy resource that is only usable on subscriptions or management groups
  - suppress: RequiredReadOnlySystemData
    from: privateLinks.json
    reason: We do not yet support system data
  - from: SubscriptionFeatureRegistration.json
    suppress: R4009
    reason: Currently systemData is not allowed
  - from: Subscriptions.json
    suppress: OperationsAPIImplementation
    reason: 'Duplicate Operations API causes generation issues'
  - suppress: TopLevelResourcesListByResourceGroup
    from: privateLinks.json
    reason: The resource is managed in a management group level (instead of inside a resource group)
  - suppress: TopLevelResourcesListBySubscription
    from: changes.json
    reason: We will be pushing customers to use Azure Resource Graph for those at scale scenarios.
  - from: changes.json
    suppress: OperationsAPIImplementation
    where: $.paths
    reason: 'Duplicate Operations API causes generation issues'
  - from: snapshots.json
    suppress: OperationsAPIImplementation
    where: $.paths
    reason: 'Duplicate Operations API causes generation issues'
  - suppress: TopLevelResourcesListBySubscription
    from: snapshots.json
    reason: We will be pushing customers to use Azure Resource Graph for those at scale scenarios.
  - suppress: RequiredReadOnlySystemData
    from: changes.json
    reason: System Metadata from a change resource perspective is irrelevant
  - suppress: ResourceNameRestriction
    from: changes.json
    reason: change resources cannot be created or named by end users
  - from: changes.json
    suppress: OperationsAPIImplementation
    reason: Duplicate Operations API causes generation issues
  - from: resources.json
    suppress: R4009
    where:
      - '$.paths["/{scope}/providers/Microsoft.Resources/tags/default"].put'
      - '$.paths["/{scope}/providers/Microsoft.Resources/tags/default"].patch'
      - '$.paths["/{scope}/providers/Microsoft.Resources/tags/default"].get'
    reason: The tags API does not support system data
  - suppress: XMS_EXAMPLE_NOTFOUND_ERROR
    where: $.paths
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: LRO_RESPONSE_HEADER
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: OperationsApiResponseSchema
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: OperationsApiSchemaUsesCommonTypes
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: NoDuplicatePathsForScopeParameter
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: LroLocationHeader
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: LroErrorContent
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: NoErrorCodeResponses
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: PutRequestResponseSchemeArm
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: PutResponseSchemaDescription
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: PostOperationAsyncResponseValidation
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: MissingXmsErrorResponse
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: PathForPutOperation
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: PathResourceProviderMatchNamespace
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: ParametersOrder
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: SyncPostReturn
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: PathContainsResourceType
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: OperationIdNounVerb
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: PathForResourceAction
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: UnSupportedPatchProperties
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: LroPostReturn
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: ProvisioningStateSpecifiedForLROPut
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: ProvisioningStateSpecifiedForLROPatch
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: SubscriptionsAndResourceGroupCasing
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: ResourceNameRestriction
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: ConsistentPatchProperties
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: GetCollectionOnlyHasValueAndNextLink
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: MissingTypeObject
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: TrackedResourcePatchOperation
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: IntegerTypeMustHaveFormat
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: BodyTopLevelProperties
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: TopLevelResourcesListBySubscription
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: XmsParameterLocation
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: PathForTrackedResourceTypes
    from: resources.json
    reason: Not a tracked resource type. Cannot change anything due to design philosophy in ARM.
  - suppress: PathForTrackedResourceTypes
    from: policyAssignments.json
    reason: Not a tracked resource type. The API has never been changed since inception. Would be a breaking change.
  - suppress: PostResponseCodes
    from: resources.json
    reason: Breaking change in order to change the API response code.
  - suppress: TenantLevelAPIsNotAllowed
    from: resources.json
    reason: Tenant level API's are allowed as an exception in ARM repo. It is a breaking change to modify it.
  - suppress: TenantLevelAPIsNotAllowed
    from: policyDefinitions.json
    reason: Linter rule limitation. The API has always supported management group scope.
  - suppress: TenantLevelAPIsNotAllowed
    from: policyDefinitionVersions.json
    reason: Linter rule limitation. The API has always supported management group scope.
  - suppress: TenantLevelAPIsNotAllowed
    from: policySetDefinitions.json
    reason: Linter rule limitation. The API has always supported management group scope.
  - suppress: TenantLevelAPIsNotAllowed
    from: policySetDefinitionVersions.json
    reason: Linter rule limitation. The API has always supported management group scope.
  - suppress: TenantLevelAPIsNotAllowed
    from: policyAssignments.json
    reason: Linter rule limitation. The API has always supported management group scope.
  - suppress: TenantLevelAPIsNotAllowed
    from: policyExemptions.json
    reason: Linter rule limitation. The API has always supported management group scope.
  - suppress: TenantLevelAPIsNotAllowed
    from: policyVariables.json
    reason: Linter rule limitation. The API has always supported management group scope.
  - suppress: TenantLevelAPIsNotAllowed
    from: policyVariableValues.json
    reason: Linter rule limitation. The API has always supported management group scope.
  - suppress: XmsPageableForListCalls
    from: resources.json
    reason: Shared swagger with other teams. We cannot make changes to the API as we don't own it.
  - suppress: EvenSegmentedPathForPutOperation
    from: resources.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: EvenSegmentedPathForPutOperation
    from: policyAssignments.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: DeleteResponseCodes
    from: resources.json
    reason: Breaking change in order to change the API response code.
  - suppress: PutResponseCodes
    from: resources.json
    reason: Breaking change in order to change the API response code.
  - suppress: PutResponseCodes
    from: policyDefinitions.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: PutResponseCodes
    from: policySetDefinitions.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: PutResponseCodes
    from: policyAssignments.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: AvoidAdditionalProperties
    from: resources.json
    reason: Breaking change in order to change the property names for multiple API's. Will fix in the future.
  - suppress: AvoidAdditionalProperties
    from: changes.json
    reason: "Change properties including the dictionary of individual property changes are dynamic types. where clause is not working on all parent fields using this property bag, hence we're suppressing the entire file for now."
  - suppress: AvoidAdditionalProperties
    from: policyDefinitions.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: AvoidAdditionalProperties
    from: policyDefinitionVersions.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: AvoidAdditionalProperties
    from: policySetDefinitions.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: AvoidAdditionalProperties
    from: policySetDefinitionVersions.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: AvoidAdditionalProperties
    from: policyAssignments.json
    reason: Linter rule limitation. The API has never been changed since inception. Would be a breaking change.
  - suppress: XmsExamplesRequired
    from: resources.json
    reason: Xms Examples required is a pre-existing lint error. Not related to this version release. Will fix in the future.
  - suppress: RequiredReadOnlySystemData
    from: resources.json
    reason: Pre-existing lint error. Not related to this version release. Will fix in the future
  - suppress: PathForPutOperation
    from: policyDefinitions.json
    reason: Policy definitions can be created at management group or subscriptions
  - suppress: PathForPutOperation
    from: policySetDefinitions.json
    reason: Policy sets can be created at management group or subscriptions
  - suppress: PathForPutOperation
    from: policyAssignments.json
    reason: Policy assignments can be created at management group or subscriptions
  - suppress: PathForPutOperation
    from: policyDefinitionVersions.json
    reason: Policy definition versions can be created at management group or subscriptions
  - suppress: PathForPutOperation
    from: policySetDefinitionVersions.json
    reason: Policy set versions can be created at management group or subscriptions
  - suppress: DeleteResponseBodyEmpty
    from: policyAssignments.json
    reason: Policy assignment body is returned on delete and this must match API
  - suppress: RequestSchemaForTrackedResourcesMustHaveTags
    from: policyAssignments.json
    reason: Policy assignments are not tracked resources
  - suppress: RepeatedPathInfo
    from: policyAssignments.json
    reason: Service requires the scope to be in the body
  - suppress: PutResponseSchemaDescription
    from: policyAssignments.json
    reason: Service only returns 201 on all successful PUTs
  - suppress: PutResponseSchemaDescription
    from: policyDefinitions.json
    reason: Service only returns 201 on all successful PUTs
  - suppress: PutResponseSchemaDescription
    from: policySetDefinitions.json
    reason: Service only returns 201 on all successful PUTs
  - suppress: UnSupportedPatchProperties
    from: policyAssignments.json
    reason: The location property represents the user-assigned identity location and is changeable for policy assignments
  - suppress: PathContainsResourceType
    from: policyAssignments.json
    reason: The policy assignment id does contain the resource type
  - suppress: ResourceNameRestriction
    from: policyDefinitionVersions.json
    reason: Using common types for management group name
  - suppress: ResourceNameRestriction
    from: policySetDefinitionVersions.json
    reason: Using common types for management group name
  - suppress: ResourceNameRestriction
    from: policyExemptions.json
    reason: Using common types for management group name
  - suppress: ResourceNameRestriction
    from: policyVariables.json
    reason: Using common types for management group name
  - suppress: ResourceNameRestriction
    from: policyVariableValues.json
    reason: Using common types for management group name
  - suppress: TenantLevelAPIsNotAllowed
    from: dataBoundaries.json
    reason: "Have approval from the PAS team."
  - suppress: GetCollectionResponseSchema
    from: dataBoundaries.json
    reason: "Do not have any list calls."
  - suppress: ParametersInPointGet
    from: policyAssignments.json
    reason: "This is for specific properties that require extra processing to produce so only want to return on demand."
  - suppress: ParametersInPointGet
    from: policySetDefinitions.json
    reason: "This is for specific properties that require extra processing to produce so only want to return on demand."
  - suppress: ParametersInPointGet
    from: policySetDefinitionVersions.json
    reason: "This is for specific properties that require extra processing to produce so only want to return on demand."
  - suppress: TrackedExtensionResourcesAreNotAllowed
    from: policyAssignments.json
    reason: "Policy assignments can have a manged identity associated with them. This requires a location."
  - suppress: TrackedExtensionResourcesAreNotAllowed
    from: resources.json
    reason: "The deployments resource type is ProxyOnly."
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.Provider
    reason: "Historically some properties have not been returned for this model and reviewer said OK to suppress."
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.ProviderListResult
    reason: "Historically some properties have not been returned for this model and reviewer said OK to suppress."
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.ProviderResourceTypeListResult
    reason: "Historically some properties have not been returned for this model and reviewer said OK to suppress."
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.TagsListResult
    reason: "Historically some properties have not been returned for this model and reviewer said OK to suppress."
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.DeploymentOperation
    reason: "Historically some properties have not been returned for this model and reviewer said OK to suppress."
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.DeploymentOperationsListResult
    reason: "Historically some properties have not been returned for this model and reviewer said OK to suppress."
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.OperationListResult
    reason: "Historically some properties have not been returned for this model and reviewer said OK to suppress."
  - suppress: RequiredPropertiesMissingInResourceModel
    from: resources.json
    where: $.definitions.ProviderPermissionListResult
    reason: "Historically some properties have not been returned for this model and reviewer said OK to suppress."
  - suppress: OperationsAPIImplementation
    from: Microsoft.Resources/stable/2016-02-01/resources.json
    reason: Pre-existing lint error.
  - suppress: OperationsAPIImplementation
    from: Microsoft.Resources/stable/2016-07-01/resources.json
    reason: Pre-existing lint error.
  - suppress: OperationsAPIImplementation
    from: Microsoft.Resources/stable/2016-09-01/resources.json
    reason: Pre-existing lint error.
  - suppress: OperationsAPIImplementation
    from: Microsoft.Resources/stable/2017-05-10/resources.json
    reason: Pre-existing lint error.
  - suppress: OperationsAPIImplementation
    from: Microsoft.Resources/stable/2018-02-01/resources.json
    reason: Pre-existing lint error.
```

---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-net
  - repo: azure-sdk-for-python
  - repo: azure-sdk-for-java
  - repo: azure-sdk-for-go
  - repo: azure-sdk-for-node
  - repo: azure-sdk-for-js
  - repo: azure-resource-manager-schemas
  - repo: azure-powershell
```

## Python

See configuration in [readme.python.md](./readme.python.md)

## Go

See configuration in [readme.go.md](./readme.go.md)

## Java

See configuration in [readme.java.md](./readme.java.md)

# Validation

Since this RP has no unique default package, iterate over all of them for validation:

``` yaml $(validation)
batch:
  - package-features: true
  - package-locks: true
  - package-policy: true
  - package-resources: true
  - package-subscriptions: true
  - package-links: true
  - package-managedapplications: true
  - package-changes: true
  - package-snapshots: true
```