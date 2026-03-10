# Engineering Log: Performance & Stability

## Issue: JVM Instability
- **Symptom:** Frequent server crashes observed during high player count.
- **Root Cause:** Inefficient garbage collection and insufficient heap memory allocation.
- **Resolution:** Implemented Aikar's optimized JVM flags in `docker-compose.yml` to stabilize memory and reduce tick latency.
- **Result:** Server uptime increased by 40%.

## Issue: Storage Constraint
- **Symptom:** 98GB LVM partition limit reached.
- **Root Cause:** Initial partitioning scheme failed to account for long-term world data growth.
- **Resolution:** Executed `lvresize` and `resize2fs` to extend the logical volume into the 800GB available space on the physical volume.
