aws-cli
===

## Description
This provides AWS CLI command on DockerHub.

## Requirement
* docker

## Usage
```bash
docker run --rm \
  -e "AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID" \
  -e "AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY" \
  -e "AWS_DEFAULT_REGION=$AWS_DEFAULT_REGION" \
  zdogma/aws-cli ecr get-login
```

## Contribution
1. Fork it ( https://github.com/zdogma/aws-cli/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## Author
<div style="display: flex;">
  <img src="https://avatars3.githubusercontent.com/u/1973683?v=3&s=460" width="45px;" height="45px;" style="margin-right: 10px;">
  <a href="https://github.com/zdogma/" style="align-self: center;">zdogma</a>
</div>
