##### How to run

 - `$ cd /tmp && git clone https://github.com/ehime/aws-tagging-tools.git tagging ; cd $_`
 - `$ mkdir -p {output,data,vendor}`
 - `$ composer install`
 - Obtain your owners datafile from me!
 - `$ use ${env} ; php -f runners/${scriptname}-.php`

Your folder should then look like the one below

<img src='assets/dirstruct.png' width=444 height=245 />

##### Scripts

 - [S3 Bucket Runner](https://github.com/ehime/aws-tagging-tools/blob/master/runners/s3-bucket.php)
 - [EC2 Instance Runner](https://github.com/ehime/aws-tagging-tools/blob/master/runners/ec2-instance.php) [](##Does not currently exist)
 - [EC2 Volume Runner](https://github.com/ehime/aws-tagging-tools/blob/master/runners/ec2-volume.php)
 
 
##### Requirements

Scripts require my bash function `Alter`

 - [Alter](https://gist.github.com/ehime/11533e945c4e1eec3e13438592bb00f7)
 - [Composer](https://getcomposer.org/download/)