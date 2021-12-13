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

To use the library add to your package json in dependecies section as:

    "dependencies": {
        "@zanichelli/gridsystem": "^0.0.3",
    }

Import it in your stylesheet with:

    @import '~@zanichelli/gridsystem/css/grid-system.css';

Install with `yarn install` as usual
