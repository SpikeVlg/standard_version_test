# standard_version_test
npx standard-version --dry-run=true
npx standard-version --dry-run=true --prerelease=develop --skip.changelog=true --skip.tag=true --skip.commit=true
npx standard-version --dry-run=true --prerelease=develop --skip.changelog --skip.tag --skip.commit --skip.bump


## Getting current vertsion
npx standard-version --dry-run=true --prerelease=develop --skip.changelog --skip.tag --skip.commit

√ bumping version in package.json from 1.1.0-develop.0 to 1.1.0-develop.1
√ bumping version in package-lock.json from 1.1.0-develop.0 to 1.1.0-develop.1

Or:
npx standard-version --dry-run=true --prerelease=develop --skip.bump --skip.changelog  --skip.commit
√ tagging release v1.1.0-feature.0

## Create locally changelog without commiting. 
npx standard-version --dry-run=false --prerelease=develop --skip.tag=true --skip.commit=true

Also bump version in package.json and package-lock.json
Upgrade version based on package.json


# Change log:
should be in master branch only


test