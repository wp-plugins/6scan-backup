=== 6Scan Backup ===
Contributors: 6Scan
Version: 2.2.9
Tags: backup, automatic backup, cloud, online, secured, restore, recovery
Requires at least: 3.0.0
Tested up to: 3.4.2
Stable tag: trunk

6Scan Backup goes beyond existing backup plugins, easily and automatically creating backups of your site and securely storing them in the cloud.

== Description ==

6Scan Backup automatically backs your site up on a predefined schedule.  Both a file backup and database backup are created, and then securely uploaded to our cloud datacenter.  The backups are encrypted in transit to prevent eavesdropping and data theft.  If you every need to restore your site, just go to your 6Scan Backup dashboard and click the backup you wish to download - multiple recent backups are stored to give you even more control.  Even if your server goes completely offline, our full backup will allow you to restore your site to full functionality on a new server within minutes!

6Scan Backup also includes numerous security features from our 6Scan Security Wordpress plugin to help you protect your site against hackers, such as a free site security scan, login security, threat analytics, and more.

Features:

* Fully automatic backup on a predefined schedule.  Our backup server schedules and initiates the backups to minimize the impact on your server.
* Easy, one-click installation and operation, suitable for all knowledge levels.
* Backs up everything you need to fully restore your site (file backup and database backup).
* Online backup storage, accessible from anywhere and anytime.
* Backups are securely encrypted during upload and download.
* Backup history (you can download multiple recent backups).
* Backups are compressed before upload and download, minimizing their size and download times.
* Professional support standing by to answer any question.
* Additional security features to protect your blog against hackers:
 * Free scan of your site for security vulnerabilities
 * Login security
 * Suspicious traffic analysis
 * And many more!

Let 6Scan handle the backup of your Wordpress site, so you can worry about what really matters to you - your content.  If you have any questions, please feel free to contact us using our [support area](http://6scan.com/support).

== Installation ==

We have made installation and usage of the backup plugin very simple, so anybody can do it!

In order to install 6Scan Backup, please follow these steps:

1. Download and install the 6Scan Backup plugin.
2. Click "Activate" to activate the 6Scan Backup plugin.
3. Confirm your email address is correct, and click Accept to accept our terms of service and continue to your backup dashboard.
4. 6Scan will automatically check for system requirements, and if all prerequisities are met, your first backup of both your files and database will begin automatically.  If there are any technical issues to be resolved, you will see a table with detailed possible solutions.
5. Once a backup is complete, you may click the "Download" button to download it.
6. If at any time you desire to turn off automatic backups, simply uncheck the "automatic backup" checkbox.
7. Make sure to check out our other security features, available on the other tabs of your dashboard.

If you encounter any problems during installation, please visit our [support area](http://6scan.com/support) or email us at support@6scan.com.

== Frequently Asked Questions ==

= How often is my site backed up? =

By default, we perform a full backup of your site once a week.  You may upgrade to daily backups through the link provided on your dashboard.

= How many previous backups are stored in the cloud? =

By default, we store two previous full backups.  You may upgrade to 15 or 30 stored backups through the link provided on your dashboard.  Having more stored backups is useful in case it takes you a few days to notice a problem has surfaced, and you want to restore a backup from up to a full month back.

= What exactly is stored in the backup? =

The backup includes:

* All the files under your web root (this includes your themes, plugins, uploaded images, etc. -- everything on your website).
* A full backup of your database (this includes your users, posts, permissions, settings, etc.).

These two items are all you need to fully restore your site on a clean server.

= Is 6Scan Backup free? =

According to our research, the average Wordpress site takes up 30-40MB compressed (50-70MB uncompressed) for the files, and under 1MB compressed for the database.  6Scan Backup gives you a weekly backup of your files and database, each up to 100MB, absolutely free.  This covers the vast majority of Wordpress sites.

If your site is larger than 100MB, or you require more frequent backups, you may sign up for one of our premium plans, allowing you to backup up to 2GB, with daily backups and up to 30-day backup retention, allowing you to go back in time in case of a problem.

= Can anybody else access my backups? =

Our backups are securely stored such that only you can access your backups, using a special key created for you when you activate the plugin.

= Where and in what format are my backups stored? =

All backups are stored in our secure cloud-based datacenter, as tar.gz archives, a standard format understood by all common archiving programs (such as WinRAR or WinZIP on Windows, and standard utilities bundled with Linux).

= How are the backups transferred? =

Backups are transferred to our datacenter using the industry-standard encrypted HTTPS protocol to prevent eavesdropping and data theft. Backup downloads are also performed using the HTTPS protocol.

= How do I set up storage space for my backups? =

There is nothing to set up!  Storage space is automatically allocated for you when you start your first backup.

= Why do all other backup plugins have a lot of configuration, while you only have one checkbox? =

We're glad you asked!  While other plugins sometimes allow more configuration, we have intentionally made our backup plugin as simple as one checkbox, so that anybody can use it, even if they don't have any experience at all with Wordpress or backup.  We feel that a good backup plugin should do its job automatically, while keeping user interaction to a minimum.  This way, we eliminate the most common errors - wrong configurations - and make sure we can consistently perform backups of your data and keep it available for you for when you really need it.

Our simple interface makes sophisticated configuration impossible, but we believe these options are not necessary for the core feature: keeping you data secure for when you need it, without the hassle.

= What are the system requirements for the backup feature? =

6Scan Backup supports all common Wordpress configurations, and we regularly test it with many large hosting providers.  In the rare case that your system is not compatible, your backup dashboard will explain what needs to be done and provide full instructions.

= What other features besides backup are included with the plugin? =

The plugin also includes other free security features to help you secure your site against hackers, such as free security scanning, login security, threat analysis, and more!  We highly recommend you take advantage of these features to make sure your site is not vulnerable to attack.

= Won't the backups pile up and take all of my website's space? =

No!  Backup data is only stored temporarily on your server during the backup process itself.  As soon as the process is complete, and the backup has been securely transferred to our cloud datacenter, the temporary backup data will be deleted, and will not take up space on your server.

We have also implemented a failsafe mechanism such that even if a backup is interrupted or otherwise fails to complete, the temporary data will be deleted soon afterwards.

= Does 6Scan Backup support Wordpress Multisite? =

As of now we do not support Multisite, but this feature is in development. Stay tuned!

= I have a feature request! =

We are always open to feature requests. Please contact us with a detailed description of your request at our [support area](http://6scan.com/support), and we will consider including it in our plugin.

= I have received an email from the 6Scan Backup plugin. Why? =

Please note that 6Scan Backup also provides optional advanced security features.  One of the features is keeping track of the latest security breaches in Wordpress and your Wordpress plugins.  If a new problem or vulnerability is found, by default we notify you by email.  However, you can always unsubscribe by unchecking the relevant box on your 6Scan Backup dashboard, under the Settings tab.

= Who is 6Scan? =

We are a team of IT and security experts who have decided to bring comprehensive yet easy-to-use backup and security to Wordpress.

== Screenshots ==

1. Your dashboard shows the latest backups (one is in progress), their creation time and download links.

== Changelog ==

= 2.1.4 =
* Initial 6Scan Backup release.

= 2.1.5 = 
* Fixed: under certain configurations, server firewalls could mistake a backup request for a security threat and block it.
* Fixed a bug where some servers would add their html code to scripts' output and confuse the 6Scan Backup plugin.

= 2.2.1 =
* Fixed a bug, where a database backup could fail in certain server configurations.
* Added pure PHP implementation of data signature/verification, to replace openssl functions, if a server does not support it
* Added a workaround for WP_Filesystem initialization. It has sometimes failed, even if Apache process had write access to the required files
* Added a better error description, in case a backup fails. User can see the error summary, if hovering over a question mark.

= 2.2.3 =
* Fixed a bug which could cause backup failure when very large files are being backed up on a slow connection.  The plugin will now attempt to transfer large files in separate chunks with automatic retry in case of failure, to improve the reliability of the backup process.
* Added a few bugfixes to code that was accessing the filesystem, if WP_Filesystem was initialized to non-direct.

= 2.2.4=
* Improved database backup. Vastly reduced RAM (memory) usage while backing up large databases.
* Database backup no longer requires passthru() permissions. The backup itself, as well as compression, is now performed by pure PHP code.
* Improved the file backup process. Several prerequisites have been worked around.

= 2.2.5 =
* Added a few more conditions to database backup, to solve cases where lack of access to certain tables could cause the entire backup process to fail.
* PHP's is_writable() was replaced with a more reliable code. Our tests have shown that this function may sometimes incorrectly return false on files that are indeed writable.

= 2.2.6 =
* Fixed a bug during activation, where certain server configurations could cause 6Scan Backup to fail initialization.
* Added a few security enhancements.

= 2.2.7 =
* Several minor bugfixes.

= 2.2.8 =
* Changed path references from 'direct' access constants (like 'ABSPATH') to their wp_filesystem counterparts (like $wp_filesystem->abspath). This is used to create backups in filesystems, where FTP credentials are required to access the files (Read/write permissions issues)


== Upgrade Notice ==

* Automatic file and database backup
* Online storage of backups
* Increased backup stability
