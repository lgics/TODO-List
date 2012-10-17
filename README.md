#TO-DO-List

_To-do list for lgics projects_

### Formatting system:

 * _Italics_: Completed but still in testing
 * __Bold__: Current project
 * Normal: Not yet started
 * ___Bold Italics___: Quasi-completion

## Private Notes and Lists

### Rashed's Notes:

 * ___Make Gerrit commit to import LegacyCamera into Gallery2 instead of the standard camera app if building with LegacyCamera.___
 * __Finish Calculator patches for MDPI devices__
 * _Finish old display compatibility system that should fix triple buffering and copybit/gralloc issues_
 * Add link to forum in the Settings via KonstaT's patch
 * Upgrade the kernel
 * _Add old graphics support system to hardware/qcom/display_
 * _Add the USES_LEGACY_GRAPHICS CFLAG into the TripleBuffer common_

### Bytecode's Notes:

 * Make a jb-aokp branch in device and vendor trees

## Public TODO

### Common

 * Update overlays
 * Update headers https://github.com/TheWhisp/android_device_samsung_msm7x27-common/commit/9ab1b742311419a89aed1a3f91b9a8083610aef3

### Kernel

 * Fix the goddamn triple buffering
 * Re-enable ZRAM: https://github.com/KonstaT/zte-kernel-msm7x27/commit/700c6f22aa3d04d00da95f6ec666a0e61293b1c6
 * Try this: https://github.com/TheWhisp/android_kernel_samsung_msm7x27/commit/69c2611b21f6dada102026bda3497ef90c4cadc0
 * Fix battery life even more
 * Import more fixes https://www.codeaurora.org/gitweb/quic/la/?p=kernel/msm.git;a=commit;h=a77eca6cee55531e81e21d83b474563f9c143e77
 * Import fixes in the kernel commited on Sept. 3 on KonstaT's kernel: https://github.com/KonstaT/zte-kernel-msm7x27/commits/jellybean from https://www.codeaurora.org/gitweb/quic/la/?p=kernel/msm.git

#### P500

 * Move global overlays to common folder

#### P505

 * Move global overlays to common folder

#### P506

 * Move global overlays to common folder

#### P509

 * Move global overlays to common folder

### APK Patcher

 * ___Set up server-side (legacydroid.com/apkpatcher)___
 * App management tab (will replace Extras tab)
 * Some form of menu bar
 * Figure out what kind of more tabs to make

#### Launcher

 * __Create launcher__
 * Distribute patcher within launcher

### File Manager

 * Update to use Holo Drawables
 * Update code to ICS and JB standard

