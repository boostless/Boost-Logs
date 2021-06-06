# esx_socieyt/server/main.lua line 68
```LUA
TriggerEvent('esx_addonaccount:getSharedAccount', society.account, function(account)
			if amount > 0 and account.money >= amount then
				account.removeMoney(amount)
				xPlayer.addMoney(amount)
				xPlayer.showNotification(_U('have_withdrawn', ESX.Math.GroupDigits(amount)))

				local data = {
					['Player'] = xPlayer.source,
					['Log'] = 'society',
					['Title'] = 'Withdrawed society money'
					['Message'] = 'Player has withdrawed money from society: ``' .. societyName .. '``\nAmount: ``' .. amount .. '``'
				}

				TriggerEvent('Boost-Logs:SendLog', data)
			else
				xPlayer.showNotification(_U('invalid_amount'))
			end
end)
```
