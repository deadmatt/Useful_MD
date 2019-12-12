# Useful_MD
Personal Scrapbook Handy Hints for AWS etc

# MD Cheatsheet
[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet]

# AWS Guides
Source: [https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-profiles.html]

## Named Profiles

Important

The credentials file uses a different naming format than the CLI config file for named profiles. Include the prefix word "profile" only when configuring a named profile in the config file. Do not use the word profile when creating an entry in the credentials file.

~/.aws/credentials
~/.aws/config


$ export AWS_PROFILE=user1

Setting the environment variable changes the default profile until the end of your shell session, or until you set the variable to a different value. You can make environment variables persistent across future sessions by putting them in your shell's startup script. For more information, see Environment Variables To Configure the AWS CLI.






