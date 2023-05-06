---
title: "{{ replace (replaceRE `\d{4}-\d{2}-\d{2}-` "" .Name) "-" " " | title }}"
ref_org: /organizations/myorg.md # required
ref_image: images/myimage.png
url_startgg: https://start.gg/tournament
address: 1234 Local St, Kansas City, MO 64111
start_date: 2020-01-01T19:00:00-0500 # required
end_date: 2020-01-02T00:00:00-0500
---

Description of event.