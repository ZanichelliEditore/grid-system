# Zanichelli Grid System

## Table of Contents

- [Usage](#Usage)
- [Requirements](#Requirements)
- [Deployment](#Deployment)

## Usage

Simple usage can be:

    <div class="container">
        <div class="grid">
            <div class="col-span-4">col-span-4</div>
            <div class="col-span-4">col-span-4</div>
            <div class="col-span-4">col-span-4</div>
        </div>
        <div class="grid">
            <div class="col-span-6">col-span-6</div>
            <div class="col-span-6">col-span-6</div>
        </div>
    </div>

For other example see example folder

## Requirements

To allow you upload package to gemfury you must add Zanichelli Gemfury repo:
`git remote add fury https://<YOUR-USER>@git.fury.io/zanichelli/grid-system.git`

## Deployment

To deploy the package follow the steps:

- `yarn version`
- `npm pack`
- `git push fury master`

## Importing

Configure your `.npmrc` with gemfury repos, for example:

    always-auth=true
    registry=https://npm-proxy.fury.io/zanichelli/
    //npm-proxy.fury.io/zanichelli/:_authToken=YOURTOKEN

To use the library add to your package json in dependecies section as:

    "dependencies": {
        "gridsystem": "^0.0.3",
    }

Import it in your stylesheet with:

    @import '~gridsystem/css/grid-system.css';

Install with `yarn install` as usual
