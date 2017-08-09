### Fuse Kernel Source Code For Android One 1st Gen (sprout)
 
#### Features:-
 * ThunderSonic Sound Control Engine
 * ThunderCharge Fast Charge Driver (enabled by default)(AC and USB current increased to 1000mA)
 * ThunderPlug CPU Hotplug replacement
 * WiFi Power management control
 * Full GPU control
 * power: wakeup: add wakelock toggles
 * DoubleTap2Wake and Sweep2Wake
 * Dynamic Fsync Control
 * Improved filesystem mounting flags - NOATIME and NODIRATIME
 * ThunderQuake Engine 1.0 - Vibration Intensity Controller for MTK vibrators
 * Huge update to kernel.org mainline 3.10.89
 * init.d support
 * Automatic busybox installation
 * Disabled Gentle fair sleepers
 * Enabled arch power
 * Optimizations to SLUB memory allocator
 * Patches to block and mm to significantly improve ssd IO performance.
 * Dynamic entropy setting based on usage
 * Dynamic management of dirty page writebacks
 * block: Added SIO IOScheduler
 * block: Add BFQ IOScheduler
 * block: Add fiops scheduler
 * cpufreq: ThunderX power saving CPU governor
 * fs: added Samsung's F2FS support
 * Reduce logger device RAM allocation to 128K
 * Set MM Linux read ahead size to 256K
 * Patches from upstream to optimize memory writeback
 * Disabled CRC check in MMC for 30% extra performance with IO
 * Reduced VFS cache pressure for better battery
 * Optimized square root algorithm
 * Governors enabled: ondemand, interactive
 * Speedup /proc/net/unix interface access
 * Mali GPU cache Optimizations
 * Mali: Increase L2 cache max read size
 * Mali: Disable state tracking
 * Mali: Reduce GPU utilization timeout
 * Mali: increase kernel memory buffer size
 * Aggressive multicore power savings
 * ARM: Cortex A7 compiler optimizations
 * MTK: removed HUGE HUGE trail of stupid MTK kernel logging
 * ARM: Removed various debug traces

#### ThunderX : A CPU Governor
ThunderX is a power saving CPU governor based on SmartAssv2 optimized for Mediatek SoCs. Use this with ThunderPlug with following settings for Max power savings. This will slightly affect the UI smoothness.

  * Hotplug Threshold: 85%
  * Touch Boost: Off
  * Laziness: 750ms
  * Endurance Mode: Dual Core
  
 Note: NEVER use hotplug CPU governor with thunderplug
 
 #### Special Thanks
   * Google for Kernel Source && Android :p
   * Linus Torvalds(For the kernel initiative)
   * Varun Chitre (For his ThunderZap Kernel source )
   * Sandeep Sethi (For always help and support me)
   * Kunal Kene
   * And every one who helped me :)
   

