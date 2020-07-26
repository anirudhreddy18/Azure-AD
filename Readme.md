Azure AD
  is Microsoft's cloud based idenity & IAM.
  modern: OAuth,OpenId Connector,SAML
  support users, devices & applications.
  internet scale & globally available
  secure(information protection, intrusion detection) & resiliant.
  lets you manage internal(sync on premise AD users) & external users
  manage first party(apps i write for my org) & third party(vendor apps).
  
  Azure AD connector to sync on premises users in to cloud.
  Users can sign into AD & AD provides them authentication to all apps(web, mobile, js etc)
  Create a tenant(azure ad instance)
  
  User authentication
   Interactive logon
   Create/Manage in AzureAD or import on premises users(using Azure AD connector)
   RBAC
   Users will be assigned roles(similar to policies in AWS)
   Users can be added to groups(but cannot assign roles to groups)
 
 App Management
   Single Tenant -> only for your organization
   Multi Tenant -> people other than org will be using them.
   Enterprise apps -> Dropbox in an org (but sign in using Azure AD) service now 
   public client -> single Page Apps
   Confidential client -> running on our server (web APIS)
