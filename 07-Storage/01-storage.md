

- storage driver
    - We can create the volumns in docker and mount the path in the container
    - notes:
        - there are many storage driver which manage all these option, and when you install docker it will automatically pick the best driver
            - AUFS
            - ZFS
            - BTRFS
            - Device Mapper
            - Overlay
            - Overlay2

- volume driver
    - default plugin is local
    - 