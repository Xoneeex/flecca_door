    local success = exports['flecca_door']:StartFleecaDoor()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end