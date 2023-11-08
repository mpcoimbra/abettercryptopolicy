# abettercryptopolicy
This is just an enhancement for RHEL-based distros crypto-policies.

This crypto-policy applies to Red Hat based distros. Anything else is at your own risk.

In order to use this policy:

RHEL/OEL/Rocky/Alma/CentOS 8 and 9:
- Download content from this repo;
- Place ENHANCED.pol under /usr/share/crypto-policies/policies/
- run: update-crypto-policies --set ENHANCED
- reboot your system.

RHEL/OEL/CentOS 7:
- Download content from this repo;
- do: cat OEL7_Hardening >> /etc/ssh/sshd_config
- systemctl restart sshd

RHEL/OEL/CentOS 6:
- Download content from this repo;
- do: cat OEL6_Hardening >> /etc/ssh/sshd_config
- systemctl restart sshd


