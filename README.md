# lux-mechanicjob
Ottos Auto Mechanic Job

This scripts is same as qb-mechanicjob.

Recreated for ottos auto inc.  

All Locations is created for Otto's Autos
based on Gabzv MLO`s https://fivem.gabzv.com/package/5127313

Boss Menu inside Office

Duty on duty laptops or just enter inside mlo. otherwise you can setup job in qb-core/shared/jobs.lua

```lua
    ['ottos'] = {
        label = 'Ottos Auto Inc',
        defaultDuty = true,  -- you can switch this false or leave it true
        offDutyPay = false,
        grades = {
            ['0'] = {
                name = 'Apprentice',
                payment = 100
            },
            ['1'] = {
                name = 'Tow Truck Operator',
                payment = 200
            },
            ['2'] = {
                name = 'Technician',
                payment = 300
            },
            ['3'] = {
                name = 'Manager',
                payment = 500
            },
            ['4'] = {
                name = 'Business Owner',
                isboss = true,  -- accsess to Boss Menu
                payment = 1200
            },
        },
    },
```


