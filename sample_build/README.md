# sample_build

validate json template
    
    $ packer validate example.json

perform packer build
-pass in keys as variables on the command line

    $ packer build \
    > -var 'aws_access_key=access_key' \
    > -var 'aws_secret_key=secret_access_key' \
    > example.json

Notes

This is the example build from Packer.io
Please see the documentation for full reference
