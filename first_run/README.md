# firstrun packer build 

validate json template

    $ packer validate firstrun.json

perform packer build
-pass in keys as variables on the command line

    $ packer build \
    > -var 'aws_access_key=access_key' \
    > -var 'aws_secret_key=secret_access_key' \
    > firstrun.json

Notes

This is the firstrun build from Packer.io
Please see the documentation for full reference

