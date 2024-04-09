# AWS Workshop Documentation

This repository contains documentation of what I learned in the AWS workshop on the AWS provided Control Design Workshop. This README provides an overview of the workshop and key takeaways.


## Workshop Overview

The workshop stages a situation where a company requires enhanced security controls over the 3 tier web app environment. To view the architecture that was implemented [click here](Architecture.png). It is required to implement a NIST 800-53rev5 compliant environment using the security services provided by AWS.


## Key Takeaways

This workshop gave me hands on experience on implementing AWS Config rules which is a service I have never used. I learned that AWS config has two ways of recording those two being continous and periodic. Additonally, you can manually configure an AWS Config Rule to re-evaluate, which is a useful tool to check if a change was correctly implemented. Also, you can apply config rules on all resources, certain resources, and on certain tags on resources (I assumed it was only on all resources).  
To add on, I never had much experience with AWS Systems Manager, but in the workshop I learned how to implement patches using a maintenance window and Patch Manager. 
The last major thing that I grew in was understanding how to write JSON templates or policy documents. By reading through the provided template (which can be found [here](cloudformationtemplate.json)), I learned more about how to write CF templates to provision resources and how to use parameters. In addition to this, there was a section on editing a AWS KMS key policy in order to ensure least privilege access, and reviewing and editing that policy aided my understanding of least privilege and JSON policy documents.


## License

This documentation is licensed under the [MIT License](LICENSE.md).
