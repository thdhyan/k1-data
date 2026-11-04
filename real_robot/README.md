# real_robot

Part of [k1-data](https://github.com/thdhyan/k1-data).

| File | What it does |
|---|---|
| `bag2edex.py` | Convert a K1 stereo bag (rectified NV12 pair) into a cuVSLAM EDEX folder. Usage: python3 bag2edex.py <bag_dir> <out_dir> [left_topic right_t |
| `check_bag_freshness.py` | Detect stale topics in a rosbag2 bag: present but not actually updating. |
| `check_topics.sh` | Pre-flight: is the rig actually publishing what a map needs? |
| `extract_frames.py` | Extract JPEG frames from a K1 walk bag so the visual data can be eyeballed. |
| `grab_intrinsics.py` | Grab K1 head-camera intrinsics once and save as YAML. |
| `query_cameras.py` | Query A2 for its camera inventory over the Booster DDS interface. |
| `sftp_sync.sh` | Batch, resumable, checksummed file transfer between this workstation and the |
| `verify_bag.py` | Post-hoc bag check: duration, topic coverage, message counts, NaN scan. |
