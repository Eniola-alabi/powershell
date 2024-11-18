# Connect to Microsoft Graph
Connect-Graph -Scopes User.ReadBasic.All
Get-MgUser -All | Select DisplayName,Id,UserPrincipalName
