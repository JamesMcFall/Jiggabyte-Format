Jiggabyte-Format
================

A simple ExpressionEngine plugin to format the file size output (supplied in bytes) from the EE file field type into something more readable.

## Installation
Unzip or clone the plugin directory down. From there installation is as per any other EE plugin. Copy the plugin dir (jiggabyte_format) into __system/expressionengine/third_party/__.

## Usage
Jiggabtye_format only supports the use of a single tag pair.

The below will return "1KB"

    {exp:jiggabyte_format dec="0"}
    1024
    {/exp:jiggabyte_format}

## Parameters
#### Dec
The "dec" parameter lets you optionally specify the number of decimal places you want to have in your returned file size.
By default this value is "2".
