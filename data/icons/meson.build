# Application icons
application_id = 'io.github.tobagin.keysmith'

# Install hicolor icons
icon_sizes = ['16x16', '24x24', '32x32', '48x48', '64x64', '96x96', '128x128', '256x256', '512x512']

foreach size : icon_sizes
  install_data(
    'hicolor' / size / 'apps' / '@0@.png'.format(application_id),
    install_dir: get_option('datadir') / 'icons' / 'hicolor' / size / 'apps'
  )
endforeach

# Note: Scalable and symbolic icons removed as requested