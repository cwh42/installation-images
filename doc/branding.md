# How the branding works

**TODO: the whole content of this file is outdated (copied from a file 13 years
old). It should be replaced by a similar file describing how the branding works
nowadays.**

To add a new theme, add a new 'Theme' section to etc/config. Example for theme
'SuSE-SLES':

```
[Theme SuSE-SLES]
yast    = SuSELinux			# yast2 theme: yast2-theme-SuSELinux
splash  = SuSE-SLES			# splash theme: bootsplash-theme-SuSE-SLES
product = SuSE Linux			# product name (for linuxrc)
update  = /linux/suse/<arch>-<ul>	# driver update dir
image   = 96				# memory limit for loading inst-sys: 96 MB
```

- ```<arch>```: replaced with architecture ('i386')
- ```<rel>```:  replaced with release number ('8.2')
- ```<ul>```:   replaced with UL release tag ('ul1')
- ```<sles>```: replaced with SLES release tag ('sles8')
