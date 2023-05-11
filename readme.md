## publishing


`npm config set @emolog400:registry https://npm.pkg.github.com`

add `.npmrc`

`
registry=https://npm.pkg.github.com/@emolog400
`

update package.json with 

`
"publishConfig": {
    "registry":"https://npm.pkg.github.com/@emolog400"
},
`

check package name starts with `@emolog`

npm publish


## misc

lerna version --yes --conventional-commits --create-release=github --message "chore(release): %v" --exact


npm login --registry=https://npm.pkg.github.com --scope=@dumidu1998

lerna add package-a --scope=package-b --no-bootstrap

lerna version

lerna version --conventional-commits --create-release=github

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

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

npm config set @dumidu1998:registry https://npm.pkg.github.com

npm config set -- //npm.pkg.github.com/:_authToken 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