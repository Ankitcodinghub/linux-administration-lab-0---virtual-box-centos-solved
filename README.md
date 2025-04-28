# linux-administration-lab-0---virtual-box-centos-solved
**TO GET THIS SOLUTION VISIT:** [Linux Administration Lab 0 – Virtual Box & CentOS Solved](https://www.ankitcodinghub.com/product/linux-administration-2-28-22-1209-pm/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119266&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Linux Administration Lab 0 - Virtual Box \u0026amp; CentOS Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Lab 0 – Virtual Box &amp; CentOS

We will be using the minimal version of the CentOS (https://en.wikipedia.org/wiki/CentOS) distribution of Linux for this class. Rather than run this operating system natively (ie. directly on your laptop), we will run it inside a Virtual Machine, sometimes referred to as a VM

(https://en.wikipedia.org/wiki/Virtual_machine) . The advantage of running VMs is that you can experiment, abuse and break your VM without compromising anything else on your laptop. Later in the semester, we will also gain experience running and maintaining VMs using the CS Department’s private Cloud (https://en.wikipedia.org/wiki/Cloud_computing) .

The ability to build, modify and destroy VMs is fundamental to mastering the material in this class. If you already have experience with these concepts, then this assignment should be fairly straightforward. If not, be prepared to spend some time working your way through the process and make sure to ask questions if you get stuck.

For the moment, install VirtualBox, CentOS, and your preferred ssh client using the reference links provided in the Week 1 module.

Once you can access your CentOS VM via ssh, please submit a transcript of the following:

Login in as root

cu-genvpn-tcom-10:~ cjherman$ ssh -p 2222 root@localhost

[root@localhost ~]#

Query the kernel version

Confirm which release of CentOS you’ve installed

https://canvas.colorado.edu/courses/79598/assignments/1241889?module_item_id=3365682 1/2 2/28/22, 12:09 PM Lab 0 – Virtual Box &amp; CentOS

Print out the basic network configuration

[root@localhost ~]# ip addr

1: lo: &lt;LOOPBACK,UP,LOWER_UP&gt; mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1

000

link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00 inet 127.0.0.1/8 scope host lo valid_lft forever preferred_lft forever inet6 ::1/128 scope host valid_lft forever preferred_lft forever

2: enp0s3: &lt;BROADCAST,MULTICAST,UP,LOWER_UP&gt; mtu 1500 qdisc pfifo_fast state UP group de fault qlen 1000 link/ether 08:00:27:b8:e3:bf brd ff:ff:ff:ff:ff:ff inet 10.0.2.15/24 brd 10.0.2.255 scope global noprefixroute dynamic enp0s3 valid_lft 86173sec preferred_lft 86173sec inet6 fe80::27b8:73da:c675:1aa3/64 scope link noprefixroute valid_lft forever preferred_lft forever [root@localhost ~]#

Shutdown the OS and power off your VM

https://canvas.colorado.edu/courses/79598/assignments/1241889?module_item_id=3365682 2/2
