<!-- loio9e1bf57130ef466e8017eab298b40e5e -->

# Mapping Role Collections in the Subaccount

You have arranged roles in role collections, and now want to assign or map these role collections to business users.

How you assign users to their authorizations depends on the type of trust configuration and on whether or not you prefer to maintain the authorizations of invididual users rather in the identity provider or in SAP BTP. The following options are available:

-   Directly assign role collections to users.

-   Map role collections to user groups or other user attributes defined in the identity provider. You initially maintain the mapping between user groups or other user attributes and role collections once in SAP BTP, and maintain group memberships or other attributes of users in the identity provider.


> ### Note:  
> If you’re using the default trust configuration with SAP ID service, you directly assign users to role collections. For more information, see [Default Identity Federation with SAP ID Service in the Cloud Foundry Environment](Default_Identity_Federation_with_SAP_ID_Service_in_the_Cloud_Foundry_Environment_36d21ac.md).
> 
> However, if you’re using a custom trust configuration, for example, with SAP Cloud Identity Services - Identity Authentication, you can use both options. For more information on configuring the trust between your subaccount and a custom identity provider, see [Establish Trust and Federation Between UAA and Identity Authentication](Establish_Trust_and_Federation_Between_UAA_and_Identity_Authentication_161f8f0.md#loio161f8f0cfac64c4fa2d973bc5f08a894).

<a name="loio9e1bf57130ef466e8017eab298b40e5e__table_fmk_5yq_bdb"/>Options for Assignment of Role Collections


<table>
<tr>
<th valign="top">

Trust Configuration



</th>
<th valign="top">

Assignment Options



</th>
</tr>
<tr>
<td valign="top">

Default trust configuration \(SAP ID service\)



</td>
<td valign="top">

 [Assign Users to Role Collections](Assign_Users_to_Role_Collections_c576676.md) 



</td>
</tr>
<tr>
<td valign="top">

Custom trust configuration \(for example: a tenant of the Identity Authentication service\)



</td>
<td valign="top">

-   [Assigning Role Collections to Users or User Groups](Assigning_Role_Collections_to_Users_or_User_Groups_31532c7.md)

-   [Map Role Collections to User Groups](Map_Role_Collections_to_User_Groups_51acfc8.md)

-   [Map Role Collections to User Attributes](Map_Role_Collections_to_User_Attributes_b3fbb1a.md)




</td>
</tr>
</table>

**Related Information**  


[Working with Role Collections](Working_with_Role_Collections_393ea0b.md "You can manage role collections by creating new ones from scratch or by copying an existing one and editing it. You can add or remove roles. You can also add or remove users or user groups to the role collections. This is the assignment or unassignment action. You can drill down all the way to the role definition or to the individual role, user, and user group, and make changes there.")

[Trust and Federation with Identity Providers](Trust_and_Federation_with_Identity_Providers_cb1bc8f.md "When setting up accounts you need to assign users. While we provide you with your first users to get you started, your organization has its own user bases which you want to integrate.")
