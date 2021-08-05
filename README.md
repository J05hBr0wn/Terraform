# terraform
<h1>List of Useful Terraform Commands (That I've Used)</h1>
<h2>Installation on Ubuntu distros</h2>
<h3>sudo apt-get install unzip</h3>

<h3>wget https://releases.hashicorp.com/terraform/1.0.4/terraform_1.0.4_linux_amd64.zip</h3>
# Update wget with correct Terraform Version

<h3>unzip terraform_1.0.4_linux_amd64.zip</h3>

<h3>sudo mv terraform /usr/local/bin</h3>

<h2>Things about Terraform</h2>

<h3>Main Configuration File is main.tf</h3>

<h3>Terraform acts as the current user that is logged in, which means that it should be run with sudo</h3>

<h2>Starting a Terraform Build</h2>

<h3>terraform init</h3> # Initializes the Terraform Configuration from main.tf (prompts the user for a "yes")

<h3>terraform apply</h3> # Applies the initialized configuration/Actually creates the thing

<h2>Useful/Cosmetic Commands</h2>

<h3>terraform fmt</h3> # Formats the file structure syntactically and spatially consistent

<h3>terraform validate</h3> # Validates the file structure configuration

<h3>terraform show</h3> # Shows the current state and configuration of the terraform build in the current directory

<h3>terraform state [list]</h3> # Lists all of the resources of the current Terraform build

	
