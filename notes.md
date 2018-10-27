echo 0 > /proc/sys/kernel/yama/ptrace_scope

permanent by setting ptrace_scope to 0 in /etc/sysctl.d/10-ptrace.conf