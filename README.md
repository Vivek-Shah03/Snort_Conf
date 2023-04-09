# Snort_Conf

To Check Version:
snort -V

To display all interfaces:
snort -W

To test configuration:
snort -c C:/Snort/etc/snort.conf -T

To run IDS:
snort -i <INTERFACE_INDEX> -c C:/Snort/etc/snort.conf -A console
where, <INTERFACE_INDEX> is index of your HOME_NET IP Interface
