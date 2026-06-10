# fme-bootcamp-resources
Resources and demo files from the FME Bootcamp by Consortech.
This folder contains all the material from the FME Bootcamp hosted by Consortech on June 4th 2026.

There are three main files:
- The package containing the workspaces, data, and data virtualization configuration shown during the bootcamp. It does NOT include the MCP 
configuration as there is currently no way of exporting that into a project.
- A text file containing all the descriptions for the MCP Server tool to recreate it manually. To setup the MCP Server, go into the MCP Server 
tab, and create a new MCP Server. Add a title and description, and then create a tool. Give it a name, copy and paste the tool description 
in the correct field, and then choose "MCP_energy_consumption.fmw" as the associated workspace. In the parameters tab, you can then copy and 
paste the descriptions for each of the parameters. Be sure to uncheck the "Use Default" box. You can also uncheck the "Use as Tool Parameter"
checkbox for the Dataset_MCP Parameter (it should be the last one). 
- The encryption key to be able to import the project on your own FME Flow instance. 

IMPORTANT: if you use this encryption key to upload the project, please make sure to do so in an exploratory FME Flow environment, to avoid impacting production environments or going against your governance rules.
