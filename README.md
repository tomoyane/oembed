oEmbed Spec
===========

These files represent the current oEmbed spec as seen at 
<a href="http://oembed.com">http://oembed.com</a> and any drafts.


## Installation

    cd /var/www/html
    git clone git@github.com:iamcal/oembed.git oembed.com
    ln -s /var/www/html/oembed.com/site.conf /etc/apache2/sites-available/oembed.com.conf
    a2ensite oembed.com
    
    apt-get install -y php-pear php5-dev libyaml-dev
    pecl install yaml
    echo "extension=yaml.so" >> /etc/php5/apache2/php.ini
    
    service apache2 reload
