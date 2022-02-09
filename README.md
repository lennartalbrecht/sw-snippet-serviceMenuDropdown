# Shopware 6 re-include Service Menu dropdown
In Shopware 6.4 the service menu dropdown in topbar has been removed and moved to footer for mobile view only. If you want to re-include the dropdown just use the following steps.

## Usage

### Step 1: Twig file 
include following file in your theme:
\views\storefront\layout\header\actions\service-menu-widget.html.twig 
	
### Step 2: Include file wherever wanted
{% sw_include '@Storefront/storefront/layout/header/actions/service-menu-widget.html.twig' %}
Example for include:
\views\storefront\layout\header\header.html.twig

### Step 3: Example scss:
Paste code from example.scss

### Step 4: Compile theme/empty cache
Depending on your environment



