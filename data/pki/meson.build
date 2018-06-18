if get_option('gpg')
  install_data([
      'GPG-KEY-Hughski-Limited',
      'GPG-KEY-Linux-Foundation-Firmware',
      'GPG-KEY-Linux-Vendor-Firmware-Service',
    ],
    install_dir : join_paths(get_option('prefix'), 'etc', 'pki', 'fwupd')
  )

  install_data([
      'GPG-KEY-Linux-Foundation-Metadata',
      'GPG-KEY-Linux-Vendor-Firmware-Service',
    ],
    install_dir : join_paths(get_option('prefix'), 'etc', 'pki', 'fwupd-metadata')
  )
endif

if get_option('pkcs7')
  install_data([
      'LVFS-CA.pem',
    ],
    install_dir : join_paths(get_option('prefix'), 'etc', 'pki', 'fwupd')
  )
  install_data([
      'LVFS-CA.pem',
    ],
    install_dir : join_paths(get_option('prefix'), 'etc', 'pki', 'fwupd-metadata')
  )
endif

