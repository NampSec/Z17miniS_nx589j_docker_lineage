# Z17miniS_nx589j_docker_lineage
Z17miniS_nx589j_docker_lineage
内核源代码： https://github.com/HighwayStar/android_kernel_nubia_msm8976/tree/staging/cm-14.1-nx591j 由于内核版本太老，有几项找不到 根本找不到的三项

CONFIG_CGROUP_BPF：缺少 开启了关联项CONFIG_NETFILTER_XT_MATCH_BPF，
CONFIG_IP_NF_NAT： missing 没有该配置，开启了IPV4_NAT（包括nattype device支持）和IPV6_NAT
CONFIG_OVERLAY_FS： missing 不存在overfs，打了补丁/SYS/FS/未挂载
