# Active Directory & Okta Integration Project

## Project Description
This project focuses on integrating Active Directory (AD) with Okta to enable secure user provisioning and authentication. The implementation ensures seamless synchronization of user data, automated group assignments, and efficient identity management.

## Key Features
- **AD Integration with Okta**: Configured secure user provisioning and authentication.
- **Okta AD Agent Deployment**: Installed and deployed on a Windows Server 2022 virtual machine.
- **User Provisioning Workflows**: Enabled scheduled user imports and Just-in-Time (JIT) provisioning.
- **Attribute Mappings & Profile Sourcing**: Ensured accurate synchronization of user data.
- **Automated Group Assignments**: Utilized Okta Expression Language to map users based on attributes like department.
- **Security Group Synchronization**: Allowed controlled access management between AD and Okta.
- **User Import & Validation**: Conducted manual and automated imports, ensuring provisioning accuracy.
- **Deactivation Policies**: Managed inactive AD users effectively within Okta.
- **Issue Troubleshooting**: Resolved user import and group rule issues for seamless synchronization.
- **Automated Provisioning Workflow**: Reduced manual intervention and improved identity management efficiency.

## Technical Specifications
- **Programming Language(s)**: PowerShell (for automation), JSON (for Okta configurations)
- **Framework(s)**: Okta API, Okta Expression Language
- **Database**: Active Directory
- **Deployment Environment**: Windows Server 2022, Okta Cloud Platform

## Development Roadmap
### Phase 1: Initial Integration Setup
- **Milestone 1**: Deploy Okta AD Agent on Windows Server 2022
- **Milestone 2**: Configure attribute mappings and user provisioning workflows

### Phase 2: Automation and Optimization
- **Milestone 3**: Implement automated group assignments and security group synchronization
- **Milestone 4**: Develop and refine an automated provisioning workflow

## Important Considerations
- **Key Challenges**:
  - Ensuring seamless synchronization between AD and Okta
  - Managing attribute conflicts and profile sourcing complexities
  - Troubleshooting user import and provisioning issues

- **Design Decisions**:
  - Use of Okta Expression Language for dynamic user group assignments
  - Implementation of automated deactivation policies to maintain security compliance
  - Optimization of provisioning workflows to reduce manual overhead

### Documentation & Resources
- [Okta Active Directory Integration Guide](https://help.okta.com/en/prod/Content/Topics/Directory/ad-overview.htm)
- [Okta Expression Language Documentation](https://developer.okta.com/docs/reference/okta-expression-language/)
- [Microsoft Active Directory Overview](https://docs.microsoft.com/en-us/windows-server/identity/active-directory-domain-services)

This document will be updated regularly to reflect progress and changes.

