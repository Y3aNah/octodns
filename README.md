# octodns
This is a repo made to test the use of octdns with github actions leveraging a local runner.

## Download
the following steps were taken to create the runner:
### Create a folder
$ mkdir actions-runner && cd actions-runner
### Download the latest runner package
$ curl -o actions-runner-linux-x64-2.308.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.308.0/actions-runner-linux-x64-2.308.0.tar.gz
### Optional: Validate the hash
$ echo "9f994158d49c5af39f57a65bf1438cbae4968aec1e4fec132dd7992ad57c74fa  actions-runner-linux-x64-2.308.0.tar.gz" | shasum -a 256 -c# Extract the installer
$ tar xzf ./actions-runner-linux-x64-2.308.0.tar.gz

## Configure
# Create the runner and start the configuration experience
$ ./config.sh --url https://github.com/Y3aNah/octodns --token AUUJZKY7GZNND3JFV7CEJLLE5ROKK# Last step, run it!
$ ./run.sh

## tags of runner
'self-hosted', 'Linux', 'X64'
