# MageBehat

Behat Integration for Magento + Magento Extensions

## Installation

    composer require kassner/magento-behat-extension:dev-master

## Documentation for Extension Developers
As an extension developer you are able to place your feature descriptions in your extension directory's Test/features folder.

Example:
Hackathon_MageBehatExample1/Test/features/homepage.feature
see https://github.com/fooman/MageBehatExamples

Place a behat context file in your extension directory Test/FeatureContext.php to use an extra context (sub context), which is used only for your extension.

Example:
Hackathon_MageBehatExample1/Test/FeatureContext.php

Example:
[MageAttack] (https://github.com/Schrank/mage-attack)

## Implemented Features
- Magento Frontend
	- Cart 	
	- Checkout 

## Usage
1. Start Selenium2 
		
		java -jar selenium-server-standalone.jar

2. Run Features from Magento root folder

		php -f shell/behat.php

## Ideas
