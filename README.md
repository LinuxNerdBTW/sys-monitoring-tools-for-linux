## Linux Monitoring Tools Every SysAdmin Should Know About

A good system administrator can do wonders with the built-in monitoring tools that come with most Linux distributions. But in order to make the most out of what Linux has to offer, you first need to know where you can find all these tools. Some of the most important sysadmin tools are available right off the bat when you first install Linux and can be accessed via the Terminal while others come in the form of open-source software, custom scripts or third-party applications that need to be installed manually.

If you’re in charge of only one or two servers you can get away with using just a handful of monitoring tools to keep an eye on things. If you’re responsible for a sizeable network of systems, on the other hand, you may need a veritable arsenal of tools to make sure that everything is running as smooth as silk. That might sound a bit intimidating if you’re new to system administration but don’t worry because we’re here to help.

We know that being a sysadmin is a difficult job that comes with great responsibility and that’s why we put together a comprehensive list of monitoring tools that will make that job a lot easier for you. We also went ahead and sorted them by category so feel free to jump ahead to the one you’re most interested in. Without further ado, let’s start things off with one of the most well-known categories.

## 1. Command Line Tools

Every Linux user should be at least somewhat familiar with command-line tools and since you’re reading this article, we’ll just go ahead and assume that you already know your away around the Terminal. The tools we’re going to cover in this section are great for monitoring and analyzing processes that directly impact the performance of individual Linux systems (as opposed to networks), though some of them do have other uses as well.
Top – Monitors Process Activity

## Top
This is the go-to command for many system administrators who need a quick overview of the threads and processes currently running on their system. The tool is available by default with most Linux distros so there’s no need to install anything in order to access it. All you need to do is fire up the command in the Terminal and you’ll immediately be greeted by a list of processes that updates in real-time. You can order the list by things like CPU or memory usage. The tool also shows you how long each process has been running for as well as some other useful bits of info like buffer size, process PID, and more.

## Htop – Interactive Process Viewer
Htop is an open-source project that aims to improve upon the regular “Top” command in pretty much every way. The tool comes with a cleaner and more intuitive user interface, built-in commands, cross-platform support, and more. Htop is a fully interactive process manager that’s also available as a fully portable application on FreeBSD, MacOS X, and of course various Linux distributions. The only catch here is that Htop requires ncurses in order to run, so you’ll first need to install the programming library if you don’t already have it.

## Atop – Advanced System and Process Monitor
Atop is a solid alternative to Atop that also comes with a few extra features, like daily system logging. This feature is great for keeping track of the performance and resource consumption of various processes over long periods of time. Similar to Htop, this tool is interactive and gives you detailed information in real-time about the performance of memory, disks, network, and CPUs. Even more helpful is the fact that Atop also highlights resources that have reached a critical load and indicates the processes that are responsible for it.

## Mytop – A Top Clone for MySQL
This one is pretty straightforward. Mytop works similar to all the other tools we’ve covered so far but instead of monitoring processes and resources, it focuses on all things related to MySQL. You can use the tool to monitor threads, performance, databases, queries, and more. Mytop hasn’t received any new updates in quite a while but you shouldn’t have any issues running it on most Linux distributions and even some versions of Windows.

## Iotop – Linux I/O Monitor
By now I’m sure you’ve noticed a pattern with these tools. They all look and function pretty similar to the standard “Top” command but each of them focuses on a different part of the system. In the case of Iotop, the tool monitors I/O usage data and sorts it by processes and threads. You can use it to check things like disk read and write times, how much time processes spend swapping or waiting on I/O, and more.

## PowerTOP – Power Management Monitor
If you’re looking for a good tool for diagnosing issues with power management and power consumption look no further than PowerTOP. A really neat feature of this tool is that it lets you play around with power management settings and configure them for optimal efficiency. Some Linux distributions come with optimized power settings by default so it’s possible you may not need to use that feature but it’s still nice to have that option available to you nevertheless.

## FTPtop – Easily Monitor Active FTP Sessions
Monitoring numerous simultaneous FTP connections can be a bit of a hassle, especially if you’re administering a busy network. That’s where FTPtop comes in. The tool displays the current status of all FTP sessions on your network in real time and in an easy to digest, constantly updating format similar to that of standard Top. There are quite a few useful options here, including the ability to show or hide sessions that are authenticating, sessions that are downloading, uploading, idle, and more.

## Apachetop – Web Server Monitor
While there are better tools out there for monitoring the performance of web servers, Apachetop can still come in handy thanks to its simplicity. Like all the other tools we’ve discussed in this section, Apachetop can quickly be installed via the Terminal and displays important information related to web servers in a clean and easy to read manner. Apachetop is largely based on Mytop and works on any Unix system that has LWP, Perl, and Term::ReadKey installed.

## Monit – All-in-One Monitoring Solution
Monit isn’t exclusively a command line-based tool because it also has a web interface, but you can interact with it via the Terminal, which is why we wanted to include it in this section. As far as its capabilities are concerned, Monit is an open-source management and monitoring solution that can do a little bit of everything. The tool monitors everything from files and programs to FTP connections, resource usage, and more. In addition to simply monitoring processes, the tool can also take action, including restarting programs that use too many resources and sending you an alert message in case of a DDoS attack.

## 2. Server Infrastructure Monitoring Tools
An experienced sysadmin should be able to set up a server without any problems but monitoring what goes on every day on said server is a different matter altogether. Luckily, there are plenty of great tools out there that simplify the process. This section is dedicated entirely to those very tools

## Vmstat – Virtual Memory Statistics
Vmstat is a tool that analyzes and creates reports about everything that’s related to system memory. This includes processes, CPU activity, paging, I/O blocks, and more. The main goal of Wmstat is to help administrators identify potential system bottlenecks. The very first report created by the tool only provides average memory usage statistics since the system’s last reboot. You’ll need to fire up the tool a couple of additional times to get more accurate results.

## Glances – An Eye on Your System
This aptly named cross-platform monitoring utility aims to cram as many system statistic as possible into a single interface. Glances keeps track of everything ranging from memory and CPU to folders, processes, network, Wi-Fi, I/O, and so much more. The tool’s layout can look a bit intimidating if you’re a novice because there’s so much data to comb through, however, veterans will surely appreciate this “at a glance” view of their server. Glances is a Python-based tool that runs on most Linux distributions and can be accessed either via the Terminal or the web-based UI.

## Ichinga – Advanced Server Infrastructure Monitoring
Ichinga is a very efficient monitoring engine that can help sysadmins keep tabs on servers, clouds, and even entire data centers. The information can be accessed via a well-designed web interface that comes with many grouping and filtering options. Ichinga is a configurable and fully scalable solution that offers both a free version and several paid plans. The premium version of the software is mainly aimed at companies and big enterprises, with flexible prices depending on the scale of the project.

## SysUsage – Sysstat and Sar Grapher
A Perl-based tool compatible with most Unix platforms, SysUsage is another server monitoring solution that periodically generates reports in the form of graphs. The tool uses Sar to monitor server activity and is primarily used by sysadmins for performance analysis and to help with resource management. SysUsage is an open-source project that you can download for free and comes with support for a handful of plugins that allow the tool to also monitor things like MySQL processes and Varnish connections.

## Cacti – Network Graphing Solution
Cacti acts as a frontend to RRDTool that can create graphs in a MySQL database. Some of its key features include advanced graph templating, fast poller, multiple methods of acquiring system data, user management tools, and more. Cacti comes equipped with an intuitive user interface and can handle everything from simple server setups to highly complex networks. Cacti receives constant updates to this day but has quite a few requirements, such as RRDTool, PHP, MySQL, net-snmp, and a web server that supports PHP.

## RRDtool – High Performance Graphing System
We can’t talk about Cacti without also bringing up RRDtool, a powerful data logging and graphing utility for analyzing time-series data. RRDtool has excellent integration with SHELL scripts, various TCL applications, and programming languages like Python, Perl, Ruby, and more. The tool can be very helpful when used by itself but its true value comes from its impressive integration capabilities.

## Linux Process Explorer – Windows-inspired Process Manager
Linux Process Explorer isn’t quite the Unix equivalent of Windows’ Task Manager but it comes pretty close. The tool features a rather similar user interface with multiple tabs for monitoring things like performance, TCP/IP connections, threads, strings, security, and more. Among other things, the tool is capable of monitoring TCP/IP traffic figures for every single process, which is a fairly rare feature. If you’re looking for a Linux monitoring tool that makes you feel like you’re actually using Windows, this is pretty much as good as it gets.

## Monitorix – Lightweight System Monitoring Tool
Monitorix is a tool designed to help sysadmins make the most out of small servers. Despite its compact size, the tool is actually quite powerful as it can be used to monitor a wide range of services, processes, system resources, and even works on embedded devices. Monitorix consists of only two main components – a collector and a CGI script – and comes with its own HTTP server. While you can use Monitorix on many GNU/Linux distributions, the tool was specifically designed for Fedora, Red Hat, and CentOS systems.

## Linux Dash – Web Dashboard for Monitoring Linux Servers
Linux Dash is a very neat server monitoring tool that takes pride in its simplicity. This is primarily a web-based application that can be a bit tricky to offload into the background of your system. If you can get past the rather complicated installation process, however, you’ll find that Linux Dash itself is actually an easy to use tool that gives you a lot of useful information about CPU usage, RAM load, network traffic, Docker and more, all in real-time.

## Wireshark – Extremely Popular Protocol Analyzer
Wireshark is a well-known network protocol analyzer used by countless commercial enterprises, educational institutions, and government agencies all over the world. The tool has been around for well over two decades and comes with a very impressive list of features. Some of the highlights include live capture and offline analysis, deep inspection of hundreds of protocols, rich VoIP analysis, powerful display filters, cross-platform compatibility, and so much more.

## Nmap – Network-wide Security Scanner
If you’re worried about the security of your server or network we highly recommend checking out Nmap, an open-source network discovery and security auditing tool. Nmap is primarily used for identifying the hosts, services, firewalls, and operating systems available on your network. Whether you’re looking to scan a single machine or a huge network of thousands of systems, you can rely on Nmap to get the job done. The tool is so reliable that it was named “Security Product of the Year” by several reputable publications and was even featured in at least twelve movies, including The Matrix Reloaded.

## Munin – Resource Monitoring Tool
Munin (“memory”), named after one of Odin’s two ravens, is a plug-and-play resource monitoring tool that surveys all your systems and remembers everything it analyzes. The resulting data is presented in the form of graphs via an intuitive web user interface. Sysadmins can use Munin to monitor both system performance and network performance, but its main feature is the ability to alert the administrator whenever something kills the server’s performance.

## 3. Network Monitoring Tools
While the previous section contained a mixed bag of useful tools, here we’re going to focus exclusively on utilities that allow you to monitor traffic, bandwidth usage, and any other aspect of your network you may want to keep an eye on.

## EtherApe – A Graphical Network Monitor
EtherApe is a network monitoring tool that comes with a neat graphical interface. The UI gives you an easy to read visual representation of network traffic, complete with different colors for the various nodes and links. EtherApe supports a wide variety of packet types, protocols, and encapsulation formats. Among other things, you can use EtherApe not just to look at the overall traffic passing through the network but also at the end to end IP and port to port TCP.

## Ethtool – Utility for Controlling Network Drivers and Hardware
The name pretty much tells you everything you need to know about this one. Ethtool is your go-to utility for monitoring and controlling Ethernet-based drivers and hardware. The tool shows you device statistics, diagnostic information, and gives you more control over your network in general. Some of the things you can control with Ethtool include hardware offload features like checksum, auto-negotiation, duplex, interrupt moderation, queue selection for multi-queue devices and more.

## NetHogs – Great Traffic Organizer
Most network monitoring tools tend to group bandwidth traffic by subnet or protocol, which can be very useful in many situations. However, breaking things down by process can also come in handy and that’s exactly what NetHogs does. The tool makes it very easy to identify any processes that are eating up more bandwidth than they should and, if necessary, quickly shut them down.

## Darkstat – Portable Network Statistics
Darkstat is a small but very efficient tool that calculates usage statistics and captures network traffic. The tool is portable, supports IPv6, and is very good at compiling detailed reports, which it serves over HTTP. Among other things, Darkstat can serve traffic graphs, reports about individual hosts, and other important information related to your network. The tool should run on any UNIX-based system that has libpcap installed.

## Justniffer – Network TCP Packet Sniffer
If you’re need a good sysadmin tool that can analyze network protocols, sniff TCP packets, and create customized logs, look no further than Justniffer. This interactive utility can be used to trace TCP traffic from live networks along with previously saved capture files. Justniffer is primarily used to monitor low-level protocol issues and correct the flow of TCP/IP traffic.

## Collectl – Jack-of-all-Trades Performance Monitor
Collectl focuses on collecting performance data that tries to combine the functionality of popular tools like Top, Iostat, and Vmstat into one package. While most monitoring tools take a more specialized approach, often focusing on a certain aspect of the system, Collectl monitors everything from network statistics and resource statistics to processes, inodes, sockets, and more.

## DTrace – Performance Analysis and Troubleshooting Tool
DTrace is a very useful open-source tool that comes pre-installed with MacOS, FreeBSD, and certain Linux distributions. This comprehensive tool can be used to monitor all types of device drivers and software including web servers, databases, and operating system kernel. DTrace dynamically patches live running instructions with instrumentation code and comes with a specialized language for writing scripts and one-liners. The utility is quite complex and intimidating for newcomers but provides invaluable support to sysadmins who manage to master it.

## Ntopng – Web-based Traffic Analysis and Flow Collection
Designed as a successor to Ntop, this utility probes and monitors network traffic using a variety of methods. Ntopng comes with a sleek web-based user interface and plenty of great features, such as the ability to sort network traffic according to IP address, port, protocol, and more. You can also use Ntopng to view real-time network traffic and active hosts, created reports about network metrics, geolocate hosts, discover application protocols, and store persistent traffic statistics, among other things.

## BandwidthD – Comprehensive TCP/IP Monitoring and Graphs
BandwidthD is a very popular sysadmin monitoring tool that’s primarily used to track TCP/IP network subnets. The tool monitors subnet activity and creates comprehensive graphs that give you a detailed look at everything that’s happening on your network. The graphs produced by BandwidthD can come in the form of either static HTML pages or dynamic PHP pages, depending on user preference. If you go with the second option you’ll be able to filter, search, and interact in a few other ways with the generated reports.

## Ngrep – Network Grep
Ngrep works similar to the command line utility grep, with the only difference being that this tool is meant for network monitoring and analysis. You can also look at Ngrep as being similar to tcpdump in terms of functionality. Ngrep has many uses, including basic packet sniffing, processing PCAP dump files, debugging interactions between protocols like HTTP, FTP, DNS, SMTP, and more.

## MRTG – Multi Router Traffic Grapher
MRTG is a free piece of software that monitors router activity and uses the collected data to create graphs, much like BandwidthD and some of the other tools we’ve discussed earlier. The tool may seem pretty simple at first glance, however, it can be used to monitor a lot more than just routers. MRTG can collect data and create graphs on all types of network devices and the tool is even slowly expanding into IoT territory. There’s even a fairly lengthy book by Steve Shipway that covers everything you can do with MRTG so make sure to check it out if you want to learn more about this amazing utility.

## Whowatch – Watch Logged in Users in Real Time
Whowatch is one of the best tools out there for monitoring in real-time the activity of users that are logged onto your network. The utility gives sysadmins detailed information about each user, including their login name, host, and type of connection. In addition, Whowatch also shows the process accessed by users and gives administrators the option to instantly terminate any of them with the simple press of a button.

## IPTraf – IP Network Monitoring Software
Another robust network monitoring solution we recommend checking out goes by the name of IPTraf. This compact CLI-based tool collects information from active TCP connections and provides detailed statistics about network traffic. The tool supports all the popular protocols you might expect, including IP, TCP and UDP, along with various network interfaces like Ethernet, FDDI, SLIP, synchronous PPP, and many others.

## Webmin – Web-based SysAdmin Monitoring Tool
Webmin makes setting up user accounts, DNS, file sharing and Apache an absolute breezing by proving sysadmins an easy to work with web-based interface. With this tool you no longer have to worry about manually editing configuration files because you can monitor and manage your network locally or remotely using any web browser. You can get even more out of Webmin by attaching various modules that enhance its capabilities. Unlike some of the other tools on this list, Webmin is constantly being updated and improve to this day, with new updates coming out almost on a monthly basis.

## TCPDump – Network Packet Analyzer
TCPDump is a powerful packet analyzer that runs on pretty much any Linux distribution you can think of. The tool is used to monitor network traffic and capture TCP/IP packets that match a specific expression provided by the sysadmin. The resulting data can be saved for later analysis and exported to an external file. TCPDump doesn’t have any special requirements with the exception of libpcap, which you probably already have installed on your machine.

## Observium – Network Monitoring Platform
Observium is a popular auto-discovering network monitoring solution that runs on a wide array of operating systems and can support many types of devices. This is a very sleek tool that comes with a modern interface that you can access from any web browser. The Professional and Enterprise versions of Observium are fairly expensive compared to similar tools, however, there is a free version that comes with certain drawbacks but can be used for an unlimited amount of time.

## SmokePing – Network Latency Monitor
If you find yourself having issues with network latency you may want to try finding the source of the problem with SmokePing. Not only does the tool keep track of all the latency on your network but it also creates interactive graphs and lets you visualize things better. SmokePing comes with a built-in configurable alerting system and features several optional plugins that expand the tool’s capabilities in a variety of ways.

## 4. Log Monitoring Tools
Monitoring network and server infrastructure in real-time can help sysadmins identify and potentially fix a lot of issues, but sometimes you may not be able to notice a problem until it’s already too late. While often discouraging, you can take the opportunity to check system logs to see what caused the problem so you can prevent it from happening again in the future.

## Logwatch – Customizable Log Analysis System
Logwatch is a very efficient open-source log analysis solution that breaks down and analyzes system logs with remarkable speed. The tool takes the resulting data and creates detailed analysis reports about system areas specified by the administrator. Logwatch is more than capable of managing large quantities of log files and extracting essential data from them, effectively reducing your workload by a fairly significant amount.

## GoAccess – Real-Time Web Log Analyzer
GoAccess is a very fast log analyzer that can be accessed either via the Terminal or a web browser. While the web-based interface is a nice addition, the tool was primarily designed to be used in conjugation with the Terminal. GoAccess supports most weblog formats, including Apache, CloudFront, Nginx, Elastic Load Balancing, Amazon S3, and more. As far as its other capabilities are concerned, the tool gives you statistics about top visitors, geolocation, HTTP, and 404 errors, among other things. The only dependency you have to worry about with GoAcess is ncurses.

## Swatch – Simple Log Watcher
Swatch is quite similar to Logwatch in terms of functionality and was initially designed to only monitor log files created by Unix-based systems. The tool has been improved over the years to be able to monitor all types of logs. Unlike Logwatch, Swatch’s main selling point isn’t the ability to generate reports but rather the fact that it sends you real-time notifications whenever it identifies any sort of issues with your logs. Swatch was eventually renamed to Simple Log Watcher but many veteran sysadmins still refer to it by its original name.

## MultiTail – Monitor Log Files in Multiple Windows
The basic gist of MultiTail is that it allows sysadmins to create separate windows for each log file they want to monitor while also being able to merge several of said windows into one. You can assign a different color to each window in order to make the data easier to read. In addition, the tool comes with interactive menus that can be used to add or delete windows, edit regular expressions, and more.

## Sarg – Squid Analysis Report Generator
Sarg is a simple tool that performs a very valuable function. The proxy log analyzer can help you see where your users are going on the internet and gives you helpful information about their browsing habits. Not just that but the tool also keeps tabs on IP addresses, bytes, the specific times a user visited certain websites, and more. Sarg generates HTML reports that contain all this information.
