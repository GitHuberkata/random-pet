# A sample repo which demonstrates the usage of "random-pet" provider

### Prerequisites
- Git
- Terraform CLI
- AWS credentials

### Use Case
The configuration is using `random-pet` resource and generates a new pet name on each apply.
More details on the usage of `random-pet` resource can be found [here](https://registry.terraform.io/providers/hashicorp/random/latest/docs/resources/pet)

### How to use
1. Clone the repo
```
git clone https://github.com/GitHuberkata/random-pet.git
```
2. Navigate to the folder
```
cd random-pet
```
3. Run the following commands
- `terraform init`
- `terraform plan`
- `terraform apply`

Result after terraform apply: the output will print out a different random name every time in the terminal.
