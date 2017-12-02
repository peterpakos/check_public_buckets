# check_public_buckets
Tool to check public S3 buckets

## Python modules
Run the following command to install required Python modules:
```
$ pip install -r requirements.txt
```

## Help
```
$ ./check_public_buckets --help
usage: check_public_buckets [--version] [--help] [--debug] [--verbose]
                            [--quiet] [-p PROFILE]

Python Template

optional arguments:
  --version             show program's version number and exit
  --help                show this help message and exit
  --debug               debugging mode
  --verbose             verbose logging mode
  --quiet               don't log to console
  -p PROFILE, --profile PROFILE
                        profile name (default: default)
```

## Usage
```
$ ./check_public_buckets -p dev
[dev] Public S3 buckets (8/62):
- dmark-bucket (ACL: FULL_CONTROL)
- forkandspade (ACL: READ, WRITE, READ_ACP, WRITE_ACP)
- coolynv2 (ACL: FULL_CONTROL)
- coolynv4 (ACL: FULL_CONTROL)
- coolyvn1 (ACL: FULL_CONTROL)
- milanobucket (ACL: READ, WRITE, READ_ACP, WRITE_ACP)
- virginbucket (ACL: FULL_CONTROL)
- wresttest (ACL: FULL_CONTROL)
```