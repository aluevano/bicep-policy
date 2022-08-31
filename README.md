# Azure Policies Deployment - Bicep

[![Update Policy Library](https://github.com/Azure/ALZ-Bicep/actions/workflows/update-policy.yml/badge.svg?branch=main)](https://github.com/Azure/ALZ-Bicep/actions/workflows/update-policy.yml)

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/Azure/ALZ-Bicep?style=flat&logo=github)

![Bicep Logo](docs/wiki/media/bicep-logo.png)

Welcome to the Azure Policy Bicep repo.

Detailed information about how to use, deploy and extend artifacts found in this repo can be found on our Wiki:

- [Home][wiki_home]
- [Deployment Flow][wiki_deployment_flow]
  - [Network Topology: Hub and Spoke][wiki_deployment_flow_hs]
  - [Network Topology: Virtual WAN][wiki_deployment_flow_vwan]
- [How Does ALZ-Bicep Implement Azure Policies?][wiki_policy_deep_dive]
  - [Adding Custom Azure Policy Definitions][wiki_policy_defs]
  - [Assigning Azure Policies][wiki_policy_assignments]
- [Contributing][wiki_contributing]
- [Frequently Asked Questions][wiki_faq]
- [Sample Pipelines][wiki_pipelines]
  - [GitHub Actions][wiki_pipelines_gh]
  - [Azure DevOps][wiki_pipelines_ado]
- [Code Tours][code_tours]

## Overview

The Azure Landing Zones Bicep repo provides an approach for deploying and managing the core platform capabilities of Cloud Adoption Framework Azure Landing Zones conceptual architecture using Bicep.

In its current incarnation each module can be deployed separately via command line but in future releases a more automated approach, via orchestration modules, will be published; but due to current Bicep & ARM limitations this is not possible today.

> Have you seen our page in the Azure Architecture Center here: [Azure landing zones - Bicep modules design considerations][aac_article]

## Getting Started

To get started with ALZ Bicep, please refer to the [Deployment Flow wiki page][wiki_deployment_flow] for:

1. Prerequisites and dependencies for the overall implementation.
2. High-level deployment flow.
3. Links to more detailed instructions on individual modules.

## Support

For support on the artifacts contained in this repository, please refer to [this guide][support_statement] for more details.

 [//]: # (************************)
 [//]: # (INSERT LINK LABELS BELOW)
 [//]: # (************************)

[wiki_home]:                                  https://github.com/Azure/ALZ-Bicep/wiki/home "Wiki - Home"
[wiki_deployment_flow]:                            https://github.com/Azure/ALZ-Bicep/wiki/DeploymentFlow "Wiki - Deployment Flow"
[wiki_deployment_flow_hs]:                            https://github.com/Azure/ALZ-Bicep/wiki/DeploymentFlowHS "Wiki - Deployment Flow - Hub and Spoke"
[wiki_deployment_flow_vwan]:                            https://github.com/Azure/ALZ-Bicep/wiki/DeploymentFlowVWAN "Wiki - Deployment Flow - Virtual WAN"
[wiki_policy_deep_dive]:                        https://github.com/Azure/ALZ-Bicep/wiki/PolicyDeepDive "Wiki - Policy Deep Dive"
[wiki_policy_defs]:                        https://github.com/Azure/ALZ-Bicep/wiki/AddingPolicyDefs "Wiki - Policy Definitions"
[wiki_policy_assignments]:                        https://github.com/Azure/ALZ-Bicep/wiki/AssigningPolicies "Wiki - Policy Assignments"
[support_statement]:                          https://github.com/Azure/ALZ-Bicep/blob/main/SUPPORT.md "Microsoft Support Policy"
[wiki_faq]:                          https://github.com/Azure/ALZ-Bicep/wiki/FAQ "Wiki - FAQs"
[wiki_pipelines]:                          https://github.com/Azure/ALZ-Bicep/wiki/PipelinesOverview "Wiki - Sample Pipelines"
[wiki_pipelines_gh]:                          https://github.com/Azure/ALZ-Bicep/wiki/PipelinesGitHub "Wiki - Sample Pipelines - GitHub Actions"
[wiki_pipelines_ado]:                          https://github.com/Azure/ALZ-Bicep/wiki/PipelinesADO "Wiki - Sample Pipelines - Azure DevOps"
[code_tours]:                                   https://github.com/Azure/ALZ-Bicep/wiki/CodeTour "Wiki - Code tours"
[aac_article]:                                  https://docs.microsoft.com/azure/architecture/landing-zones/bicep/landing-zone-bicep "Azure Architecture Center - Azure landing zones - Bicep modules design considerations"
