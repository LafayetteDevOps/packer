# example build

validate json template

    $ packer validate basic.json

perform packer build
-pass in keys as variables on the command line

    $ packer build \
    > -var 'aws_access_key=access_key' \
    > -var 'aws_secret_key=secret_access_key' \
    > basic.json

Notes

This is an extension of the example build from Packer.io
Please see the documentation for full reference
