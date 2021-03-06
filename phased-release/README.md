# Akamai Terraform example for the [Phased Release Cloudlet](https://control.akamai.com/wh/CUSTOMER/AKAMAI/en-US/WEBHELP/property-manager/property-manager-help/GUID-EB6ECB59-525C-4253-ACAD-3FAC594B3B12.html). <br>

This version is storing the state in Terraform cloud and will be triggered when pushing changes to GitHub. Terraform cloud is monitoring changes in: 
![image](https://user-images.githubusercontent.com/3455889/151590053-b07d91b1-eb42-4ed8-88a4-2ba073535b8b.png)
So when adding extra rules to your .auto.tfvars file and pushing it to GitHub it will automatically be triggered.

Make sure you have added the Phased Release Cloudlet and [Conditional Origin Group](https://control.akamai.com/wh/CUSTOMER/AKAMAI/en-US/WEBHELP/property-manager/property-manager-help/GUID-57F29FA7-38F9-442B-9872-BE12BCC8A43A.html) behaviors with one or more Conditional Origin Definitions
to you Akamai property configuration. This conditional origin can be used in your Phased Release Cloudlet rules if there is a match on a specific rule.<br>

![image](https://user-images.githubusercontent.com/3455889/151527055-c55540b9-219d-442e-98fb-a931d3dcb8b2.png)
