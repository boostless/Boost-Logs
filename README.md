# Boost-Logs
 FiveM loging system to webhook
# Usage
```LUA
local data = {
        ['Player'] = nil, -- You need to set source here
        ['Target'] = nil, -- You need to set source here
        ['Log'] = 'default', -- Log name
        ['Title'] = 'Title', -- Title
        ['Message'] = 'Message' -- Message
        ['Color'] = 'blue', -- Set your color here check Config.Colors for available colors
    }

TriggerEvent('Boost-Logs:SendLog', data)
```

