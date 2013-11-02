# Favicons

Info: [https://github.com/audreyr/favicon-cheat-sheet](https://github.com/audreyr/favicon-cheat-sheet)


## Basic

	<link rel="shortcut icon" href="/favicon.ico" />

- favicon.ico 16*16
- favicon.ico 32*32


## Android

Android recommended size for multiple resolutions:

	<link rel="shortcut icon" sizes="196x196" href="icon-196x196.png">
	<link rel="icon" sizes="196x196" href="apple-touch-icon.png">


## iOS

	<!-- For iPad with high-resolution Retina display running iOS ≥ 7: -->
	<link rel="apple-touch-icon-precomposed" sizes="152x152" href="/path/to/favicon-152.png">

	<!-- For iPad with high-resolution Retina display running iOS ≤ 6: -->
	<link rel="apple-touch-icon-precomposed" sizes="144x144" href="/path/to/favicon-144.png">

	<!-- For iPhone with high-resolution Retina display running iOS ≥ 7: -->
	<link rel="apple-touch-icon-precomposed" sizes="120x120" href="/path/to/favicon-120.png">

	<!-- For iPhone with high-resolution Retina display running iOS ≤ 6: -->
	<link rel="apple-touch-icon-precomposed" sizes="114x114" href="/path/to/favicon-114.png">

	<!-- For first- and second-generation iPad: -->
	<link rel="apple-touch-icon-precomposed" sizes="72x72" href="/path/to/favicon-72.png">

	<!-- For non-Retina iPhone, iPod Touch, and Android 2.1+ devices: -->
	<link rel="apple-touch-icon-precomposed" href="/path/to/favicon-57.png">

## Touch icon for iOS 2.0+ and Android 2.1+

Optimal create one size for all:

	<link rel="apple-touch-icon-precomposed" href="path/to/favicon-152.png">

- apple-touch-icon.png 152*152
- apple-touch-icon-precomposed.png 152*152

## Windows 8 & IE 9

### IE 10 Metro tile icon (Metro equivalent of apple-touch-icon)

	<meta name="msapplication-TileColor" content="#FFFFFF">
	<meta name="msapplication-TileImage" content="/path/to/favicon-144.png">
	<meta name="application-name" content="name" />

### IE 9:

- Address bar (16x16)
- New Tab page (32x32)
- Taskbar button (32x32)
- Pinned site browser UI (24x24)

Recommended: 16x16, 32x32, 48x48

Optimal: 16x16, 24x24, 32x32, 64x64


## Images

- favicon.ico (16x16, 32x32)
- tileicon.png (144x144)
- apple-touch-icon-precomposed.png (196x196)

