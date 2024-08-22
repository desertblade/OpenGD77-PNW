# OpenGD77-PNW
OpenGD77 Codeplug for[PNW Digital](https://pnwdigital.net/) and [SeattleDMR](https://seattledmr.org/). 

I used coordinates mostly from [RepeaterBook](https://www.repeaterbook.com/). This allows GPS equipped radios to calculate distance to the repeaters.

# How to Create Code Plug

Download zip and extract: https://github.com/desertblade/OpenGD77-PNW/archive/refscoordinates/heads/main.zip

In OpenGC77 CPS got to File->CSV-Import CSV and choose PNW-DMR to import DMR repeaters.

Be sure to update **DMR ID and callsign** (double click) and download callsign database (under Extras).

If you want you can then File->CSV-Append CSV and import Simplex-FRS-GMRS-NOAA folder for those channels.

# RepeaterBook Imports

[RepeaterBook](https://www.repeaterbook.com/) supports OpenGD77! 

It's tucked away under Export->Radioddity->OpenGD77 Channels File.

You can then load it in to OpenGD77 CPS using File->CSV-Append CSV.

[RepeaterBook](https://www.repeaterbook.com/) export will be missing longitude/latitude and you will need to create Zones for organization. If you export to CSV the longitude/latitude are there and should be copy/paste of those columns. Be sure to make sure the order is the same!

[RepeaterBook](https://www.repeaterbook.com/) does not include Talkgroups for DMR stations in the export. So the files in this repo are a great start to get basic DMR repeaters from the PNW into your radio.

An alternative you can use  https://github.com/desertblade/OpenGD77-Repeaterbook to generate Channels.csv and Zones from Repeaterbook. 

## Notes
I am using this on a TYT MD-UV390 running the latest OpenGD77.

N7DSB
