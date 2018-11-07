# kernel-4.19.0V.Varbanovski_lp150.12.22_default

![](https://github.com/nu11secur1ty/kernel-4.19.0V.Varbanovski_lp150.12.22_default/blob/master/Screenshot%20from%202018-10-30%2007-27-47.png)

- commands for All RHEL distributions ;) ae beeee to gluvuta me... ;)
```bash
rpm -ivh kernel-4.19.0V.Varbanovski_lp150.12.22_default-1.x86_64.rpm
rpm -ivh kernel-headers-4.19.0V.Varbanovski_lp150.12.22_default-1.x86_64.rpm
grub2-mkconfig -o /boot/grub2/grub.cfg
telinit 6
```
Original resource: https://github.com/torvalds/linux/tree/master/kernel

nu11secur1ty Resource: https://github.com/nu11secur1ty/linux-4.19


- get clone of kernel:

```bash
git clone https://github.com/nu11secur1ty/linux-4.19.git
```
----------------------------------------------------------------------------------------
- V.Varbanovski ready kernel 4.19.0V.Varbanovski_lp150.12.22_default:

link: https://drive.google.com/drive/folders/1rMeLuGa1rKCGjMz2e9b7f6r6VttnAibn?fbclid=IwAR3uHerc3sZXlMNwKnjGWiZuiXeYtzHYmOK_URm9EsJGAS1fMkXqnAA0Wys

-----------------------------------------------------------------------------------------


***work_on_kernel_11.06.2018*****SUSE**

- Link: https://github.com/nu11secur1ty/kernel-4.19.0V.Varbanovski_lp150.12.22_default/blob/master/work_on_kernel_11.06.2018/modules.md
------------------------------------------------------------------------------------------

- How to uninstall your old kernel:
```bash
rpm -qa | grep kernel
zypper remove kernel-default-4.x.xx-lpxxx.xx.x.x86_64
```
-----------------------------------------------------------------------------------------

- How to compile your own kernel.

HOWT0: https://github.com/nu11secur1ty/Compiling-the-Linux-Kernel-the-SUSE-way
