This repository hosues all of the Azure policies that I've created

VM_Encrypted_Disk_Policy.json
This policy checks all disks for encryption and audits the results
VM_Encrypted_Disk_Function.json
This function works off the audited VM's from the VM_Encrypted_Disk_Policy and remediates any effected disks with the key vault specified in their resource group