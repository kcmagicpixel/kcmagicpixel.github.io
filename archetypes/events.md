---
title: "{{ replace (replaceRE `\d{4}-\d{2}-\d{2}-` "" .Name) "-" " " | title }}"
ref_org: /organizations/myorg.md # required
ref_banner: images/myimage.png # relative path from assets, or external URL
ref_icon: images/myicon.png # relative path from assets, or external URL
url_startgg: https://start.gg/tournament # full url to start.gg tournament listing
address: 1234 Local St, Kansas City, MO 64111 # physical location of event
participant_count: 0 # number of participants that attended the event
start_date: 2020-01-01T19:00:00-0500 # required, date of event
end_date: 2020-01-02T00:00:00-0500 # date that event ends (after which it will be moved to "Past Events" page)
sync: false # true only for auto-synced entries
---

Description of event.
