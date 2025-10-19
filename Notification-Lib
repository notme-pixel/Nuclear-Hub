local Module = {}

function Module:Notification(title, desc, duration)
  pcall(function()
    game.StarterGui:SetCore("SendNotification", {
      Title = title,
      Text = desc,
      Duration = duration,
    })
  end)
end
return Module
