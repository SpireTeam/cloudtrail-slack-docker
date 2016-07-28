Watch CloudTrail and send notifications of every action to an slack channel.

## Installation

```
npm i -g auth0/cloudtrail-slack
```

## Usage

Configure a daemon that runs the following command:

```
SLACK_WEBHOOK=http://your-slack-webhook \
	REGIONS=us-west-1,us-east-1
	cloudtrail-slack
```

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
