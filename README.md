# Packer Quickstart

## Validate
<pre>packer validate example.json</pre>

## Build
<pre>
packer build \
    -var 'aws_access_key=YOUR ACCESS KEY' \
    -var 'aws_secret_key=YOUR SECRET KEY' \
    example.json
</pre>
