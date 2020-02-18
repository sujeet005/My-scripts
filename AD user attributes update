# My-scripts
#To update the AD user attributes:
####################################
Import-Module ActiveDirectory  
$Users = Import-csv <Mention the path to import the csv file>  
foreach ($User in $Users)  
  { 
Set-ADUser $User.SAM -Manager $User.Manager -Department $User.Department -Title $User.Title -Office $User.Office -Description $User.Description -StreetAddress $User.StreetAddress -Company $User.Company
# To output the result in the .txt file. 
$results | Out-File <Mention the path to export the result .txt file> -Append
###############################################END#####################################

