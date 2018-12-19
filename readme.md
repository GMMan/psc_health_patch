Health and Safety Skipper Patch for PlayStation Classic
=======================================================

This patch skips the health and safety scene when you start your PlayStation
Classic. It does not permanently modify the system.

Usage
-----
1. Copy health_patch.sh to the root of your lolhack USB drive.
2. Add the following lines to the top of `lolhack\lolhack.sh` after `#!/bin/sh`
   (if present):
   ```
   chmod +x /media/health_patch.sh
   /media/health_patch.sh
   ```
3. Use your drive on the console as usual.
