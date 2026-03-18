# Era of AI

## Setup
uv tool install specify-cli --from git+https://github.com/github/spec-kit.git

## Initiallize
specify init .

## Constitution
/speckit.constitution /constitution create governing principles and development guidelines, a constitution for a new project that will be an Azure Platform Landing Zone aligned to the [Microsoft Cloud Adoption Framework](https://learn.microsoft.com/azure/cloud-adoption-framework/ready/landing-zone/design-principles?WT.mc_id=AZ-MVP-5004796), using Bicep as the Infrastructure as Code language. The constitution should include principles for modularity, reusability, security, compliance, and best practices for Azure and Bicep development. The principles should be clear, concise, and actionable, providing a solid foundation for the project's architecture and implementation, while also acknowledging the complexity of Day 2 operations.

## Specify
/speckit.specify build an Azure Platform Landing Zone that will be deployed with Azure Bicep and Azure DevOps pipelines. The Landing Zone will use an Azure Firewall, with Hub and Spoke networking _(/16 for the entire region)_ and will be deployed to the East US 2 Azure region. Although not in the scope of the build, we need to make sure that the Platform Landing Zone will easily allow the addition of Application Landing Zones in the future.
