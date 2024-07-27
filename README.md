# MobileDataWaybar
a Module that shows your [ModemManager](https://github.com/freedesktop/ModemManager) Status in the Waybar


![image](https://github.com/user-attachments/assets/8a5b341f-88c8-405a-8389-065a75cf7513)



## Dependencies

* You need ```ModemManager``` and ```jq```.

* You need ModemManager running.


## Module

```jsonc
      "custom/mobile_data": {
          "exec": "~/.config/waybar/mobiledata.sh",
          "format": "{icon}",
          "tooltip": true,
          "format-icons" : ["","","",""],
          "return-type" : "json"
      },
```

## Font used in the Screenshot

[AdwaitaIconFont](https://github.com/lollar1337/AdwaitaIconFont)


