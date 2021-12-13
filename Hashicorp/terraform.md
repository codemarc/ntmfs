---
marp: true
author: Marc J. Greenberg
size: 4:3
theme: gaia
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---
<!-- _paginate: false -->

<style>
  h1 {font-size:34pt;}  
  p {font-size:14pt}
  h2 {font-size:20pt;margin-top:-6px;}  
</style>
<style scoped>  
  h2 {font-size:20pt;margin-top:5em;}  
  h3 {font-size:20pt;}  
  .spacy {font-size:18pt;margin-top:5em;}
</style>

# HashiCorp Terraform

<hr/>

<span class="spacy">12/12/2021</span>

## Marc J. <span style="color:darkgreen;">Green</span>berg

### marc@codemarc.net

---
<style scoped>
  p {font-size:18pt}
</style>

# Infrastructure as Code

Infrastructure as Code (IaC) is the management of infrastructure (networks, virtual machines, load balancers, and connection topology) in a descriptive model, using a version control same versioning as the Dev team uses for source code.

Each public cloud has defined a way to script resource management

[Azure Resource Manager][s1r1]  
[Aws CloudFormation][s1r2]
[Google Cloud Deployment Manager][s1r3]

Hashicorp Terraform is an open-source tool for provisioning and managing cloud infrastructure.

Terraform is the tool that aggrigates IaC in front of a public cloud native solution. So lean 1 and use for all.

---
<style scoped>
  code {
    font-size: 13pt;
    color: black;
    background:#ffffff;
    border: 1px solid black;
  }  
</style>

# Get Started - AWS

I am starting by following the tutorial: [aws-get-started][s2r1]

```bash
# Install Terraform using homebrew
$ brew tap hashicorp/tap
$ brew install hashicorp/tap/terraform
$ terraform -help

Usage: terraform [global options] <subcommand> [args]

The available commands for execution are listed below.
The primary workflow commands are given first, followed by
less common or more advanced commands.

Main commands:
  init          Prepare your working directory for other commands
  validate      Check whether the configuration is valid
  plan          Show changes required by the current   .
  .
  .

```

---
<style scoped>
  code {
    font-size: 13pt;
    color: black;
    background:#ffffff;
    border: 1px solid black;
  }  
</style>

# Get Started - Build/Change/Destroy

Visit the [ec2 console][s4r1]

```bash
# commands that were used in build
aws configure
terraform init
terraform fmt
terraform validate
terraform apply
terraform show
terraform state list

# commands that were used in Change
terraform apply

# commands that were used in Destroy
terraform destroy

# commands that were used in Destroy
terraform apply -var "instance_name=YetAnotherName"
 
```

---

 [ ] 1st set of tuts complete

<!-- REFERENCES -->

[s1r1]: https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview

[s1r2]: https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview

[s2r1]: https://learn.hashicorp.com/collections/terraform/aws-get-started


[s1r3]:https://cloud.google.com/deployment-manager/docs

[s4r1]:https://console.aws.amazon.com/ec2/v2/home?region=us-west-2#Instances:sort=instanceId

