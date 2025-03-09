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
