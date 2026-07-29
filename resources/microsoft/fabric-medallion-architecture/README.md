# Microsoft Fabric Medallion Lakehouse Architecture

This folder contains a link/reference entry for official Microsoft Fabric guidance on medallion lakehouse architecture.

**Title:** Understand medallion lakehouse architecture for Fabric with OneLake  
Publisher / original source: Microsoft Learn  
Official guidance: https://learn.microsoft.com/en-us/fabric/onelake/onelake-medallion-lakehouse-architecture  
Microsoft Learn module: https://learn.microsoft.com/en-us/training/modules/describe-medallion-architecture/  
Local copy included: No

## Links

- [Fabric Medallion Lakehouse Architecture](https://learn.microsoft.com/en-us/fabric/onelake/onelake-medallion-lakehouse-architecture)
- [Organize a Fabric Lakehouse Using Medallion Architecture Design](https://learn.microsoft.com/en-us/training/modules/describe-medallion-architecture/)
- [Microsoft Fabric Documentation](https://learn.microsoft.com/en-us/fabric/)
- [Microsoft Fabric Overview](https://learn.microsoft.com/en-us/fabric/fundamentals/microsoft-fabric-overview)

## Why this resource is useful

Microsoft recommends medallion architecture as a Fabric design approach for progressively improving data structure and quality through:

- Bronze: raw source-preserving data
- Silver: validated, standardized and enriched data
- Gold: curated analytical and reporting data

The guidance is useful for understanding layer responsibilities, OneLake and Lakehouse deployment choices, Delta tables, governance boundaries and how Gold data is served for analytics.

This reference directly supports the architecture and documented Fabric adoption path in `fabric-service-operations-analytics`.

## Scope note

A locally tested Bronze/Silver/Gold workflow does not by itself prove execution in a Microsoft Fabric workspace. Fabric-specific claims should remain limited to features that were actually implemented and verified in Fabric.

## License note

No Microsoft documentation is redistributed in this repository. This is a link-only reference entry.
