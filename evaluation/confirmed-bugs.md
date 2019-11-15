---
fontsize: 8pt
geometry: landscape,margin=0.5in
---

# Confirmed Double Unlock Bugs

|  File                                             | Present in                               | Fixed in                                 |
|---------------------------------------------------|------------------------------------------|------------------------------------------|
| drivers/block/drbd/drbd_main.c                    | b0814361a25cba73a224548843ed92d8ea78715a | 8e9c523016cf9983b295e4bc659183d1fa6ef8e0 |
| fs/ubifs/orphan.c                                 | 7542c6dedbc1caa284ca4cbd6b64f99023ff1b97 | 4dd75b335bc1f10fb1a01b5cd58870d47c13c4e7 | 
| drivers/gpu/drm/nouveau/nouveau_svm.c             | 5fbcf5015db8e9f04a9da6d40322622fa229da54 | de4ee728465f7c0c29241550e083139b2ce9159c |
| fs/btrfs/file.c                                   | 78e03651849fd3e8aa9ab3288bc1d3726c4c6129 | f49aa1de98363b6c5fba4637678d6b0ba3d18065 |
| drivers/staging/wilc1000/wilc_wlan.c              | ca641bae6da977d638458e78cd1487b6160a2718 | fea69916360468e364a4988db25a5afa835f3406 |
| drivers/staging/kpc2000/kpc_dma/fileops.c         | d4c596ebf62760b89ec3d0a2cbc94e2632395eec | c85aa326f5c5cc73bad4381498fd2bda1bb41c27 |
| fs/nfs/client.c                                   | a46126ccc77e764429d63bf958d117f607f4b6c6 | c260121a97a3e4df6536edbc2f26e166eff370ce |
| fs/btrfs/file.c                                   | 2b90883c561ddcc641741c2e4df1f702a4f2acb8 | 8fca955057b9c58467d1b231e43f19c4cf26ae8c |
| drivers/media/dvb-core/dvbdev.c                   | ded716267196862809e5926072adc962a611a1e3 | 122d0e8dd050cc5dc3fb9e9b5f2dee3c5276ce35 |
| mm/memory_hotplug.c                               | 6376360ecbe525a9c17b3d081dfd88ba3e4ed65b | e3df4c6e4836ce93cd5cf92d9cbdeaf4439a0241 |
| sound/soc/codecs/pcm512x.c                        | fd270fca2001bcdac0658eb673c20920baeed86c | 28b698b7342c7d5300cfe217cd77ff7d2a55e03d |
| drivers/target/target_core_user.c                 | 807cf197fc9a3bc156523cb68786a9cb0ec396b4 | f0e89aae609bebd430ce7a96d2f642917d89ca57 |
| drivers/rpmsg/qcom_smd.c                          | fb416f69900773d5a6030c909114099f92d07ab9 | c3388a075c8ac568f892c40bec919ba8ac4077f0 |
| drivers/scsi/aacraid/commsup.c                    | 09624645e1e85df8d68b04de6e0607d696268333 | d844752e1801099f92c178845f56412861a2b4af |
| drivers/staging/rtl8188eu/os_dep/usb_intf.c       | 612e1c94bfe9736cef0a9b86db792fd863be7733 | 23bf40424a0f641ca7ff4225add4aa592086bdd5 |
| block/blk-cgroup.c                                | e0223003e6e141533446d01a92784592a97a8552 | bbb427e342495df1cda10051d0566388697499c0 |

## Results

|  File                                             | Status       | 
|---------------------------------------------------|--------------|
| drivers/block/drbd/drbd_main.c                    | Parser error | 
| fs/ubifs/orphan.c                                 | Detected     | 
| drivers/gpu/drm/nouveau/nouveau_svm.c             | Parser error | 
| fs/btrfs/file.c                                   | Parser error | 
| drivers/staging/wilc1000/wilc_wlan.c              | Parser error | 
| drivers/staging/kpc2000/kpc_dma/fileops.c         | Parser error | 
| fs/nfs/client.c                                   | Parser error | 
| fs/btrfs/file.c                                   | Parser error | 
| drivers/media/dvb-core/dvbdev.c                   | Parser error | 
| mm/memory_hotplug.c                               | Parser error | 
| sound/soc/codecs/pcm512x.c                        | Parser error | 
| drivers/target/target_core_user.c                 | Parser error | 
| drivers/rpmsg/qcom_smd.c                          | Parser error | 
| drivers/scsi/aacraid/commsup.c                    | Parser error | 
| drivers/staging/rtl8188eu/os_dep/usb_intf.c       | Parser error | 
| block/blk-cgroup.c                                | Parser error | 