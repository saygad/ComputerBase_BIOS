#**BIOS设置与系统的优化**
##**整体的性能与B I O S的设置有关**
 * 选择Load Setup Defaults， 将B I O S参数恢复成尽量发挥系统性能的默认值。而Load BIOS
D e f a u l t s则是一种很保守的设置，所以除非系统出现故障，否则不要使用。
 * 启用CPU Internal Cache和External Cache，对于Slot l主板对称为CPU Level 1 Cache 和
CPU Level 2 Cache。这两个项设为E n a b l e d，充分利用C P U资源，加快系统速度
 * Quick Power On Self Te s t：应设为E n a b l e d。该选项可以加快P O S T的速度
 * Boot Up Floppy Seek：设为D i s a b l e d，启动时不检查软驱。
 * Boot Up System Speed设为H i g h。
 * Gate A20 Option选择F a s t。
 * VideO BIOS SHADOW设为E n a b l e d。
 * Auto Configuration设为D i s a b l e d。
 * 使用S D R A M时，在正常运行的情况下， SDRAM RAS- to- CAS Delay，SDRAM RAS
P r e c h a rge Ti m e和SDRAM CAS Latency Ti m e这三个值应越小越好
 * System BIOS Cacheable和Video BIOS Cacheable（视频B I O S缓存）：设成E n a b l e d。该功能将主要B I O S代码复制到随机访问内存（R A M）中。如果打开该功能，系统的性能应该有很大的提高，但该功能也会引起与一些特定显卡或内存的冲突
 * Memory Hole At 15～1 6 M设为D i s a b l e d。
 * Passive Release和Delayed Transaction 设为D i s a b l e d。
 * AGP Aperture Size指定A G P最多使用多少系统内存，设为系统内存总容量。默认值可能
是6 4 M B。增大这个值可能会引起性能的下降或极大的内存占用。试着将该值设成你的内存大小的2 5 %到1 0 0 %，或者根据显卡操作说明书进行设置。
 * IDE HDD Block Mode应设为E n a b l e d，可加快硬盘的传输速度。
 * PIO模式设为Mode 4。
 * PCI/VGA Palette noop（P C I / V G A调色板检测）：disable
 * DRAM Data Integrity Mode（D R A M数据统一模式）：C C内存和N o n -
E C C内存选择Non-ECC
 * Video RAM Cacheable（显卡R A M缓存）：打开该功能将使C P U从显卡的R A M中读取缓存数据。打开该功能通常能改进系统的性能。
