# tracker-script
tracker script to bulk add new users to trackers

Basically, this is how it works:

1. Populate the projects_OSS.yml file with yaml for each team where name is literally the tracker project name and id is the 7 digit ID from the url.  Each entry is a two line addition like this:

```
- name: CF Infrastructure (Public)
  id: 1488988
```

2. Populate the team file with users.
