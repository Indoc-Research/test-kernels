# Multi-Kernel Jupyter Environment Example

This repository demonstrates how to set up multiple ipykernels using repo2docker.

**Kernels Provided:**
- Python (base)
- Python (envA)
- R (base)

**How to Use:**
1. Push this repository to GitHub.
2. Run:
   ```
   repo2docker https://github.com/<yourusername>/my-multi-kernel-repo
   ```
3. Once built, open the Jupyter environment. You should see all three kernels available in the Notebook kernel selector.
