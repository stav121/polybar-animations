## Polybar Animations

Collection of varius Polybar animations I've made

To use them, add them as custom modules in your polybar config like that:

    [module/script-name]
    type = custom/script
    exec = ~/path/to/script.py
    interval = 0.25             ;or whatever interval you wish
    label = %output%
