# InstaLive-PHP 
A PHP script that allows for you to go live on Instagram with any streaming program that supports RTMP!

Built with [mgp25's amazing Instagram Private API Wrapper for PHP](https://github.com/mgp25/Instagram-API/).

InstaLV is a fork of [JRoy/InstagramLive-PHP](https://github.com/JRoy/InstagramLive-PHP).

# Windows / Linux / Mac
1. Install PHP, Composer, and ffmpeg
2. Edit the `USERNAME` and `PASSWORD` inside of the `config.php` file to your Instagram username/password.
3. Run the `goLive.php` script. (`php goLive.php --dandy`)

# Termux
1. Install Composer :
`curl -sS https://getcomposer.org/installer | php -- --install-dir=/data/data/com.termux/files/usr/bin --filename=composer`
2. Install ffmpeg :
`pkg install ffmpeg`
3. `composer install`
4. Edit the `USERNAME` and `PASSWORD` inside of the `config.php` file to your Instagram username/password.
5. Run the `goLive.php` script. (`php goLive.php --dandy`)
6. Open `127.0.0.1` or `localhost` from your browser.

With `--dandy` mode you can run without OBS, just input `File / URL Path` or `Youtube URL` for media source on Command Line.
