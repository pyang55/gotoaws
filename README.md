# ec2connect
ec2connect is an interactive CLI tool that you can use to connect to your EC2 instances using the [AWS Systems Manager Session Manager](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager.html):
- No need to exposing SSH to the network
- No SSH key management
- No maintenance of bastion/jump hosts 

## Prerequisites
- [session-manager-plugin](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html) must be installed on your client
- SSM Agent version 2.3.672.0 or later must be installed on the instances you want to connect to through sessions
- An instance profile with proper IAM permissions (e.g AmazonSSMManagedInstanceCore)

## Installing


## License
[MIT](LICENCE)