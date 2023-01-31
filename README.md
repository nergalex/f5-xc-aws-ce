# AWS CLOUD CE

Terraform to create F5XC AWS cloud CE

## Usage

- Clone this repo with: `git clone --recurse-submodules https://github.com/cklewar/f5-xc-aws-ce`
- Enter repository directory with: `cd aws cloud ce`
- Obtain F5XC API certificate file from Console and save it to `cert` directory
- Pick and choose from below examples and add mandatory input data and copy data into file `main.py.example`.
- Rename file __main.tf.example__ to __main.tf__ with: `rename main.py.example main.py`
- Initialize with: `terraform init`
- Apply with: `terraform apply -auto-approve` or destroy with: `terraform destroy -auto-approve`

## AWS Cloud CE module usage example

````hcl
````