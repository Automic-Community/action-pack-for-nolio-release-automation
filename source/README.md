About action pack:
	CA Release Automation and CA Continuous Delivery Automation (formerly known as CA Automic Release Automation) both provide consistent, repeatable and auditable deployments across the Continuous Delivery pipeline.

	This Action Pack allows CA Continuous Delivery Automation to manage objects and trigger workflows in CA Release Automation. 
	In this way, you do not modify the deployment logic defined in CA Release Automation and you extend it using CA Continuous Delivery Automation.

Available Actions:

	1. Get Applications
	2. Get Application by ID
	3. Create Template Property
	4. Delete Template Property  
	5. Update Template Property
	6. Get Environments
	7. Get Environment by ID
	8. Get Application by ID
	9. Create Artifact Package
   10. Create Deployment Plan 
   11. Create Project
   12. Delete Release
   13. Load Manifest
   14. Load Tokens
   15. Run Deployment Plan
   16. Run Deployments
   17. Stop Deployment
   18. Get Deployment Status
   
	
Supported Platforms:

	1. Oracle JRE 1.7 or later
	2. To run the action on Windows, Apache HTTP server executable httpd must be present on the corresponding agent OS.
	3. To run the action on UNIX, apachectl script must be present on the corresponding agent OS.
	4. Required configuration file(s) for HTTP Server must also be present on agent OS.

Apache HTTP Server Action pack depends on

	- Automation.Engine » AutomationEngine (minimum version Automation.Engine 11.2)
	- Package.ITPA.Shared » PCK.ITPA_SHARED (minimum version Package.ITPA.Shared 1.1)