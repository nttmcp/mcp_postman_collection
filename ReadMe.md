# Postman Collection for NTT MCP

Postman Collections to support NTT Managed Cloud Platform (MCP)

## Requirements

### Postman
Download and Install Postman

Download Postman at [Postman Download Link](https://www.getpostman.com/downloads/)

### Postman Collection & Environment Variable
Download Postman Collection and Environment variable (Cloud Control REST API.postman_collection.json and MCP-Environment-Variable.postman_environment files) on your local machine via git clone or direct download.

## Basic Setup
- Import both Collection and Environment Variable file in Postman.
- Load Cloud Control Environment variable in Postman. Fill in CloudControl User ID (cc_user) and CloudControl Password (cc_pass) variables.
- Optionally fill in OrgId variable. If not available, Use "Get OrgID" API call to obtain OrgID from "0.Getting Started" folder and Set the OrgID variable with the value obtained.

\***Note**: The Environment Variable file has sample variable names pre-populated for various objects like Networks, Servers, Snapshots, DRS, etc. These variables names could be consumed as required, and new variable names could be created as per user requirement.

## Useful Documentation Links

MCP Cloud Control general Documentation [CloudControl Documentation](https://docs.mcp-services.net)

MCP CloudControl Vendor REST API Documentation [API Documentation](https://docs.mcp-services.net/display/CCD/API+2+-+Documentation+Downloads)

How to use Postman for Cloud Control Postman Collection [How to Documentation](https://docs.mcp-services.net/display/CCD/How+to+Use+a+Postman+Collection+with+CloudControl+REST+API)

## Postman Collection structure

All API calls are organized under current structure. It's based on CloudControl REST documentation for easy navigation (Except 0. Getting Started)
> Getting started Folder has a group of essential API calls from various sections to get familiar with basic CloudControl functions.

| API Calls |
| ------------- |
| 0. Getting Started |
| 1. Infrastructure |
| 2-14. Network |
| &nbsp; &nbsp; &nbsp; 2. Network Domain Management |
| &nbsp; &nbsp; &nbsp; 3. VLAN Management |
| &nbsp; &nbsp; &nbsp; 4. IP Address Management |
| &nbsp; &nbsp; &nbsp; 5. Static Routes  |
| &nbsp; &nbsp; &nbsp; 6. SNAT Exclusion |
| &nbsp; &nbsp; &nbsp; 7. Firewall Policy |
| &nbsp; &nbsp; &nbsp; 8. NAT Rules |
| &nbsp; &nbsp; &nbsp; 9. VIPS - Node Management |
| &nbsp; &nbsp; &nbsp; 10. VIPS - Pool Management  |
| &nbsp; &nbsp; &nbsp; 11. VIPS - Virtual Listener Management |
| &nbsp; &nbsp; &nbsp; 12.VIPS - SSL Offload |
| &nbsp; &nbsp; &nbsp; 13. VIPS - Supporting Functions |
| &nbsp; &nbsp; &nbsp; 14. Network - Security Groups |
| &nbsp; &nbsp; &nbsp; 15. Server |
| 16. Snapshots |
| 17. Cloud Monitoring |
| 18. DRS |
| 19. Server Image API - Image Management |
| 20. Tagging API |
| 21. Accounts |
| 22. User Management |
| 23. Notification - Webhook Management |
| 24. Reports |
|  |
