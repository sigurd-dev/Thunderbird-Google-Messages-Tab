# Google Keep Tab
Unofficial Google Messages add-on for Thunderbird, it adds a button that opens a Google Messages tab in Thunderbird.
The [home page](https://addons.thunderbird.net/thunderbird/addon/google-messages-tab) of the extension contains some pictures and reviews.

#### Installing 
Open Thunderbird, go to Tools -> Add-ons -> Extensions, search for Google Messages in the serach box and click on "+ Add to Thunderbird".

#### Installing from sources
Download the repository, zip it, rename it to Google-Messages-Tab.xpi and choose install addon from file in Thunderbird.

In linux the xpi file can be created with the following commands
* `git clone https://github.com/sigurd-dev/Thunderbird-Google-Messages-Tab`
* `cd ./Thunderbird-Google-Messages-Tab`
* `VERSION=$(cat ./manifest.json | jq --raw-output '.version')`
* `zip -r "../Google-Messsages-Tab-${VERSION}-tb.xpi" *`
