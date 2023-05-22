---
title: "{{ replace (replaceRE `\d{4}-\d{2}-\d{2}-` "" .Name) "-" " " | title }}" # required
ref_org: magic-pixel # name of the organization running this event
ref_banner: images/myimage.png # relative path from assets, or external URL
ref_icon: images/myicon.png # relative path from assets, or external URL
url_startgg: https://start.gg/tournament # full url to start.gg tournament listing
address: 1234 Local St, Kansas City, MO 64111 # physical location of event
participant_count: 0 # number of participants that attended the event
start_date: 2020-01-01T19:00:00-0500 # required, date of event
end_date: 2020-01-02T00:00:00-0500 # date that event ends 
series: My Event Series # The event series associated with this event (e.g. Magic Pixel Weekly)
sync: false # true only for auto-synced entries
---

Description of event.
