## Getting Started:


###### Description

CA Release Automation and CA Continuous Delivery Automation (formerly known as CA Automic Release Automation) both provide consistent, repeatable and auditable deployments across the Continuous Delivery pipeline.
This Action Pack allows CA Continuous Delivery Automation to manage objects and trigger workflows in CA Release Automation. 
In this way, you do not modify the deployment logic defined in CA Release Automation and you extend it using CA Continuous Delivery Automation.

###### Actions

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
		
###### Compatibility:

1. CA Release Automation 6.5 

###### Prerequisite:

1. Automation Engine should be installed.
2. Automic Package Manager should be installed.
3. ITPA Shared Action Pack should be installed. 
4. PCK.AUTOMIC_RA_REST Action Pack should be installed. 

###### Steps to install action pack source code:

1. Clone the code to your machine.
2. Go to the package directory.
3. Run the command apm upload in the directory which contains package.yml (source/):

Ex. **apm upload -force -u <Name>/<Department> -c <Client-id> -H <Host> -pw <Password> -S AUTOMIC -y -ia -ru**


###### Package/Action Documentation

Please refer to the link for [package documentation](source/ae/DOCUMENTATION/PCK.AUTOMIC_CA_RA.PUB.DOC.xml)

###### Third party licenses:

The third-party library and license document reference.[Third party licenses](source/ae/PCK.AUTOMIC_CA_RA.PUB.LICENSES.xml)

###### Useful References

1. [About Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_AboutPacksandPlugins.htm?Highlight=Action%20packs)
2. [Working with Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_WorkingWith.htm#link10)
3. [Actions and Action Packs](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#_Common/ReleaseHighlights/RH_Plugin_PackageManager.htm?Highlight=Action%20packs)
4. [PACKS Compatibility Mode](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#AWA/Variables/UC_CLIENT_SETTINGS/UC_CLIENT_PACKS_COMPATIBILITY_MODE.htm?Highlight=Action%20packs)
5. [Working with actions](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/AB_WorkingWith.htm#link4)
6. [Installing and Configuring the Action Builder](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/install_configure_plugins_AB.htm?Highlight=Action%20packs)

###### Distribution: 

In the distribution process, we can download the existing or updated action package from the Automation Engine by using the apm build command.
Example: **apm build -y -H AE_HOST -c 106 -u TEST/TEST -pw password -d /directory/ -o zip -v action_pack_name**
			
			
###### Copyright and License: 

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)

###### Questions or Need Help? 

Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
