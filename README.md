## Default Governor
```
SHADE_DEFAULT_GOVERNOR
```

- Allows changing the default governor after boot is completed.
- Default: schedutil

## Maintainer Flag
```
 SHADE_MAINTAINER
```

- Flag that names the Project Shade maintainer.

## Cores Configuration
```
SHADE_LITTLE_CORES
```

- Define all little cores for your device here.
- By default it is configured to 6 cores (0,1,2,3,4,5)
- For now, it is used to configure cpuset, but we plan to expand its functionality in the future!

## CPUSET Configuration
```
SHADE_FOREGROUND_CPUSET
```

- Used to configure the foreground cpuset for your device.
- By default it is configured to 0-6.


```
SHADE_TOP_APP_CPUSET
```

- Used to configure the top-app cpuset for your device.
- By default it is configured to 0-7.
- We recommend setting this to all cores on your device.
