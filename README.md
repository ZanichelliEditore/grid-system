# Zanichelli Grid System

## Table of Contents

- [Usage](#Usage)
- [Requirements](#Requirements)
- [Deployment](#Deployment)

## Usage

Simple usage can be:

    ```html
    <div class="container">
      <h3>Mixed</h3>
      <div class="grid">
        <div class="col-xl-6 col-md-4">col-xl-6 col-md-4</div>
        <div class="col-xl-6 col-md-4">col-xl-6 col-md-4</div>
      </div>
      <div class="grid">
        <div class="col-sm-4 col-xl-5">col-sm-4 col-xl-5</div>
        <div class="col-sm-4 col-xl-5">col-sm-4 col-xl-5</div>
      </div>
      <div class="grid">
        <div class="col-md-2 col-xl-6">col-xl-6 col-md-2</div>
        <div class="col-md-2 col-xl-6">col-xl-6 col-md-2</div>
        <div class="col-xl-6 col-md-4 col-xl-2">col-xl-6 col-md-4 col-xl-2</div>
      </div>
    </div>

For other example see example folder

To use the library add to your package json in dependecies section as:

    yarn add @zanichelli/albe-grid-system

Import it in your stylesheet with:

    @import '~@zanichelli/albe-grid-system/css/grid-system.css';
