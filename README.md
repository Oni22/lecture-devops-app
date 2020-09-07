## How to get Started
- Fork this Repository
- Create a **SSH-Key** with **ssh-keygen -m PEM -t rsa -b 4096**
- [Create a github token](https://docs.cachethq.io/docs/github-oauth-token#:~:text=Generate%20a%20new%20token,list%20of%20tokens%20from%20before.) and save the **git-token** somewhere
- Create Digital Ocean Account + [API Token](https://www.digitalocean.com/docs/apis-clis/api/create-personal-access-token/#:~:text=To%20generate%20a%20personal%20access,the%20Generate%20New%20Token%20button.). Store the **Digital-Ocean API token** somewhere.
- Add the created **SSH-Key** to your digital ocean account under Setting->Secutry. Save the **Fingerprint** somewhere
- Create Kass account remember your **customernumber and password**
- [Install Terraform to your local device](https://learn.hashicorp.com/tutorials/terraform/install-cli)
- Clone this Repo https://github.com/RufusGladiuz/TODO_InfrastructureAsCode.git
- Open a console and navigate to the just cloned repo into the folder Jenkins Job Automation/terraform
- Run the command terraform apply
- The script will now ask you for variables it needs to allocate and set up your server
- do_token -> Is the **Digital-Ocean API Token**
- domain_name -> Is the name you choose for your domain on Kass
- gitHubAccessToken -> Is the **git-token** you created on your git account
- gitHubRepo -> Is the checkout link of the repository you just forked
- kas_password -> Is the password you selected for your kas account
- kas_username -> Is your customernumber for your kas account
- pub_key -> Is the directory to the public key you created
- pvt_key -> Is the directory to the private key you created
- ssh_fingerprint -> Is the SSH-Fingerprint you copyed from digital ocean


