# media-server
To set up a container-based automated plex media server

# To do next
- add environment variables into each container or at least find out if the current approach is enough
- switch to a seperate config directory

# Questions
- What should I be using for hostname - container name (per automation avenue) or the server computer name (per klutchell)?
- figure out what the etc/localtime volume is for
- do I need to add logging <br />
```bash
    e.g. "logging: 
            driver:json-file"
```
- do I need to specify tcp or other type of port
- for hardlinks what needs to be on the same volume? If so, just the media or also the config and/or containers
- What is the proper way to list the path of an external volume?
- Do I need a backup folder for each?

# Notes/Reminders
- 

# sources
https://github.com/automation-avenue/youtube-39-arr-apps-1-click/blob/main/
- starting place

https://github.com/klutchell/mediaserver/blob/master/env.sample
- good environment variable descriptions

