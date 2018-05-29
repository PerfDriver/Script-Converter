# Script Converter
Command line tool that converts LoadRunner scripts to a NeoLoad Project.

## Installation

### Requirement
Java 8. ([Download Java](http://www.oracle.com/technetwork/java/javase/downloads/index.html))

### Procedure
1. Download the [latest release](https://github.com/Neotys-Labs/Script-Converter/releases/latest)
2. Unzip in the folder of your choice

## Usage

### Executable
* Windows: script-converter.bat  
* Linux/OSX: script-converter.sh

### Arguments
* source: The source directory of the project to migrate.
* target: The target folder where the generated project will be written.
* project: The name of the converted project.

### Examples
* Windows: .\script-converter.bat -source "C:\LoadRunnerScripts" -target "C:\Users\Documents\NeoLoadProjects\LRConversion" -project "LRConversion"
* Linux/OSX: ./script-converter.sh -source "/home/user/LoadRunnerScripts" -target "/home/user/NeoLoadProjects/LRConversion" -project "LRConversion"

## Coverage

"Web - HTTP/HTML" protocol

### Converted variables
* File Parameter
* Table Parameter
* Custom
* Unique Number

### Functions
* lr_start_transaction / lr_end_transaction
* lr_think_time
* web_reg_find
* web_reg_save_param
* web_url
* web_submit_data
* web_custom_request

### Not Covered
* other functions
* logic (conditions and loops)
* custom C code

## Feedbacks and bugs
Open [an issue](https://github.com/Neotys-Labs/Script-Converter/issues) or contact [Neotys support](https://www.neotys.com/support/contact.html).

## How to contribute
The source code is not available yet. It will be opened soon to contribution.

