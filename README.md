# WordPress with Redis Template

This template deploys a high-performance version of [WordPress](https://wordpress.org/) with Redis Object Cache. It uses MariaDB for data storage and Redis for object caching, significantly improving the performance of your WordPress site.

[![Deploy on Zeabur](https://zeabur.com/button.svg)](https://zeabur.com/templates/Y4U42V?referralCode=lcandy2)

## ✨ Features

- WordPress 6.x with PHP 8.3
- MariaDB 11
- Redis Object Cache
- Pre-installed Redis Cache plugin
- Performance optimized configurations

## 💁‍♀️ How to use

1. Click the Zeabur deploy button 👆
2. Set your domain in the configuration
3. Deploy and wait for the services to start
4. Complete WordPress installation through the web interface
5. Activate Redis Object Cache plugin in WordPress admin panel (Plugins > Redis Object Cache > Activate)
6. Verify Redis connection in Settings > Redis

## 🚀 Performance Benefits

- Faster page load times through efficient caching
- Reduced database load
- Better handling of high traffic
- Improved overall site performance
- Enhanced scalability

## ⚙️ Configuration Notes

- WordPress automatically detects and uses MariaDB and Redis
- Redis is configured with optimal caching settings
- MariaDB is optimized for WordPress workloads
- Includes optimized PHP and Apache configurations

## 📝 Resources

- WordPress Docs: https://wordpress.org/documentation/
- Redis Object Cache Plugin: https://wordpress.org/plugins/redis-cache/
- MariaDB Docs: https://mariadb.com/kb/en/documentation/
- Redis Docs: https://redis.io/documentation

## 🔧 Advanced Configuration

The template comes with pre-configured settings optimized for most use cases. If you need to modify:

- Redis memory limit: 256MB by default
- Cache policy: allkeys-lru (Least Recently Used)
- PHP memory limit: 256MB
- Upload file size limit: 20GB