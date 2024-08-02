# Explore-Security-Options

Instructions
1. Explore BitLocker encryption policies

To implement BitLocker encryption:
Open the Configuration Manager console.
Go to Assets and Compliance > Overview > Endpoint Protection > BitLocker Management.
Click on Create BitLocker Management Control Policy in the ribbon.
Explore settings for creating a policy - particularly, for the Operating System Drive and for Client Management.
For this lab, you DON'T have to finish creating the policy.
Instead, in your writeup, answer the question: What unsafe setting would you have to set to be able to finish creating the policy, and why?
Even if you do finish creating the policy, don't deploy it to your collection. But if you did -- it would not matter. There are two reasons why it would not matter -- what are they?
 

2. Explore Endpoint Protection Policies:

a. Antimalware Policies

In the Configuration Manager console, navigate to Assets and Compliance > Endpoint Protection > Antimalware Policies.
Create a new policy and select your own desired settings for Endpoint Protection, such as enabling or disabling real-time protection, setting the scanning frequency, and specifying the actions to take when malware is detected.
Save the policy.
Right-click on Your Own Collection and select Deploy.
Choose the Endpoint Protection policy and follow the wizard to deploy the policy to the collection.
Monitor the deployment to ensure the policy is successfully applied to the device in the collection.
Once deploying the policy to the collection, check the collection's properties, where a tab shows current deployments.
Also look at the policy, and see the distribution status -- it should show that the content has successfully been deployed on the Distribution Point.
b. Exploit Guard Policies:

In the Configuration Manager console, navigate to Assets and Compliance > Endpoint Protection > Windows Defender Exploit Guard Policies.
Create a new policy and configure the desired Attack Surface Reduction policies. Pick your own policies and describe why you selected the options that you did. You don't have to deploy it.
c. Application Guard Policies

In the Configuration Manager console, navigate to Assets and Compliance > Endpoint Protection > Application Guard Policies.
Create a new policy and configure the desired Application Guard settings, enabling Application Guard, and specifying a URL that should be opened in Application Guard, and setting the level of protection.
Save the policy.
Deploy the policy to Your Own Collection.
NOTE: The policy will NOT work on your lab system. Explain why, and validate your answer with information from an official source.
