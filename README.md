# Powershell Code Samples

#### Samples Available:

## Active Directory

#### Get-UsersNotLoggedIn

A small script that utilizes the `Import-PSSession` CMDlet to import the ActiveDirectory module into a terminal server
to see what users from a particular OU haven't logged in.

## Chocolatey Packages

Samples of a couple of packages created that demonstrate how NuSpec requirements work with NuGet packages.  Instructions
are available [here](https://github.com/jebaile7964/PowerShell-Code-Samples/tree/master/Chocolatey%20Packages).

## Desired State Configuration

#### SamplePushConfig

Configures a server with the DNS and DHCP roles, then configures the roles to handle a web farm with 3 web servers, a sql
server, and a caching server.  More information [here](https://github.com/jebaile7964/PowerShell-Code-Samples/tree/master/DSC).

## Software Configuration Management

#### Push-DesktopPackages

Utilizes `New-PSSession` and `Invoke-Command` CMDlets to install Adobe Reader and OpenOffice through the Chocolatey package
manager.  While done in a for loop in this sample, the same process can be done in parallel with a workflow.

#### Create-CloudRDPIcons

Uses .NET classes to create gui elements for use as a tool for junior resources.  It accepts input from a CSV, and some
User input.  After processing, it creates the icons in their respective folders for deployment.

#### Samples to be added:

##DSC
```
Chef Server Configuration
Web Server configuration
VM host configuration
SQL server config
WDS, WSUS configs
```

##Hyper-V
```
create virtual machines and install via lite-touch installation
create pull server, app server, sql server, chefserver, workstation
create hyper-v networking gw script
```
##SQL
Create sql connection to propane

##SCM
Deploy and automate configuration of propane

##AD
```
Create OU, users, and groups
create GPO and link it to an OU
promote domain controller
```

##TFS

##Chef
```
configure dsc pull server
configure linux web server
configure mysql server
configure x86 rdp server
Make sure to demonstrate how to make an LWRP
Install propane
```
