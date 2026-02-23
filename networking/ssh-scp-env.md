# ssh, scp, and env variables

## ssh into cloud service
- in aws, get the instance from connect. You need a key
ssh -i "keyName" ec2


## scp file into cloud
scp -i "keyName" fileToTransfer ec2:destination/directory
- the : is necessary

## Environment Variables
env - a list of all enviorment variables
echo $VARIABLE - prints the variable name
export variableName=value - creates an env variable

