---
reviewed: 2021/11/27
severity: Awareness
pillar: Operational Excellence
category: Repeatable infrastructure
resource: Virtual Network Gateway
online version: https://azure.github.io/PSRule.Rules.Azure/en/rules/Azure.VNG.Name/
---

# Use valid VNG names

## SYNOPSIS

Virtual Network Gateway (VNG) names should meet naming requirements.

## DESCRIPTION

When naming Azure resources, resource names must meet service requirements.
The requirements for VNG names are:

- Between 1 and 80 characters long.
- Alphanumerics, underscores, periods, and hyphens.
- Start with alphanumeric.
- End alphanumeric or underscore.
- VNG names must be unique within a resource group.

## RECOMMENDATION

Consider using names that meet Virtual Network Gateway (VNG) naming requirements.
Additionally consider naming resources with a standard naming convention.

## NOTES

This rule does not check if VNG names are unique.

## LINKS

- [Repeatable infrastructure](https://learn.microsoft.com/azure/architecture/framework/devops/automation-infrastructure)
- [Naming rules and restrictions for Azure resources](https://docs.microsoft.com/azure/azure-resource-manager/management/resource-name-rules)
- [Azure deployment reference](https://docs.microsoft.com/azure/templates/microsoft.network/virtualnetworkgateways)
- [Recommended abbreviations for Azure resource types](https://docs.microsoft.com/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations)
