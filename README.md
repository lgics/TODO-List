#TO-DO-List

_To-do list for lgics projects_

## Private Notes and Lists

### Rashed's Notes:

 * Make Gerrit commit to import LegacyCamera into Gallery2 instead of the standard camera app if building with LegacyCamera. Use this for refrence: https://github.com/KonstaT/android_device_zte_blade/commit/76435377d8f4245e6a4a54d59dd3afe43a28bae7#commitcomment-2002434
 * Finish Calculator patches for MDPI and LDPI devices
 * Finish old display compatibility system that should fix triple buffering and copybit/gralloc issues
 * Add link to forum in the Settings via KonstaT's patch
 * Upgrade the kernel
 * Add old graphics support system to hardware/qcom/display
 * Add the USES_LEGACY_GRAPHICS CFLAG into the TripleBuffer common

### Bytecode's Notes:

 * Make a jb-aokp branch in device and vendor trees

## Public TODO

### Common

 * Update overlays
 * Update headers https://github.com/TheWhisp/android_device_samsung_msm7x27-common/commit/9ab1b742311419a89aed1a3f91b9a8083610aef3
 * Fix GPS issues

### Kernel

 * Fix the goddamn triple buffering
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

 * Present _better_ on XDA Forums with tab API and javadocs.
 * Figure out what kind of more tabs to make.
 * Set up server-side (legacydroid.com/apkpatcher)
 * (1.8) App management tab (will replace Extras tab)

### File Manager

 * Update to use Holo Drawables
 * Update code to ICS and JB standard

