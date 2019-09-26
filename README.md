# Zabbix Template for monitoring Konica Minolta

This template is tested for **Konica Minolta bizhub C308**

**Template Name** Template Printer Konica Minolta bizhub C224e

**GROUP** Printers

## ITEMS
* Cartridge level % - Black	
* Cartridge level % - Cyan	
* Cartridge level % - Developer Cartridge (Black)	
* Cartridge level % - Developer Cartridge (Cyan)	
* Cartridge level % - Developer Cartridge (Magenta)	
* Cartridge level % - Developer Cartridge (Yellow)	
* Cartridge level % - Drum Cartridge (Black)	
* Cartridge level % - Drum Cartridge (Cyan)	
* Cartridge level % - Drum Cartridge (Magenta)	
* Cartridge level % - Drum Cartridge (Yellow)	
* Cartridge level % - Fusing Unit	
* Cartridge level % - Image Transfer Belt Unit	
* Cartridge level % - Magenta	
* Cartridge level % - Ozone Filter	
* Cartridge level % - toner waste box	
* Cartridge level % - Transfer Roller Unit	
* Cartridge level % - Yellow	
* Pages printed - total	
* Printer error state	
* Printer location	
* Printer model	
* Serial number	

## APPLICATIONS
* Consumables level	
* Consumables level %	
* Pages printed	
* Printer information	

## TRIGGERS
* None cartridge toner - Yellow {HOST.NAME}	
* None cartridge toner - Transfer Roller Unit {HOST.NAME}	
* None cartridge toner - Transfer Belt Unit {HOST.NAME}	
* None cartridge toner - Ozone filter {HOST.NAME}	
* None cartridge toner - Magenta {HOST.NAME}	
* None cartridge toner - Fuser Cartridge {HOST.NAME}	
* None cartridge toner - Drum Cartridge Yellow {HOST.NAME}	
* None cartridge toner - Drum Cartridge Magenta {HOST.NAME}	
* None cartridge toner - Drum Cartridge Cyan {HOST.NAME}	
* None cartridge toner - Drum Cartridge Black {HOST.NAME}	
* None cartridge toner - Developer Cartridge Yellow {HOST.NAME}	
* None cartridge toner - Developer Cartridge Magenta {HOST.NAME}	
* None cartridge toner - Developer Cartridge Cyan {HOST.NAME}	
* None cartridge toner - Developer Cartridge Black {HOST.NAME}	
* None cartridge toner - Cyan {HOST.NAME}	
* None cartridge toner - Black {HOST.NAME}	
***
Low cartridge toner - Yellow {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Yellow {HOST.NAME}
***
Low cartridge toner - Transfer Roller Unit {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Transfer Roller Unit {HOST.NAME}
***
Low cartridge toner - Transfer Belt Unit {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Transfer Belt Unit {HOST.NAME}
***
Low cartridge toner - Ozone filter {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Ozone filter {HOST.NAME}
***
Low cartridge toner - Magenta {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Magenta {HOST.NAME}
***
Low cartridge toner - Fuser Cartridge {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Fuser Cartridge {HOST.NAME}
***
Low cartridge toner - Drum Cartridge Yellow {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Drum Cartridge Yellow {HOST.NAME}
***
Low cartridge toner - Drum Cartridge Magenta {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Drum Cartridge Magenta {HOST.NAME}
***
Low cartridge toner - Drum Cartridge Cyan {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Drum Cartridge Cyan {HOST.NAME}
***
Low cartridge toner - Drum Cartridge Black {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Drum Cartridge Black {HOST.NAME}
***
Low cartridge toner - Developer Cartridge Yellow {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Developer Cartridge Yellow {HOST.NAME}
***
Low cartridge toner - Developer Cartridge Magenta {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Developer Cartridge Magenta {HOST.NAME}
***
Low cartridge toner - Developer Cartridge Cyan {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Developer Cartridge Cyan {HOST.NAME}
***
Low cartridge toner - Developer Cartridge Black {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Developer Cartridge Black {HOST.NAME}
***
Low cartridge toner - Cyan {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Cyan {HOST.NAME}
***
Low cartridge toner - Black {HOST.NAME}
Depends on:
Template Printer Konica Minolta bizhub C224e: None cartridge toner - Black {HOST.NAME}
***
Error on Printer {HOST.NAME}	
