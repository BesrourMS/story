# Story
A simple & clean, Bootstrap blog theme for Pico.

## Installation
Download the story folder, upload it in the themes folder of your pico installation and change the following setting within your config.php:
```sh
 $config['theme'] = 'story';
 $config['pages_order_by'] = 'date';
 $config['pages_order'] = 'desc';
 $config['PicoExcerpt.enabled'] = true;
 $config['excerpt_length'] = 12;
```
For Pico CMS >= 2.0 add to config/config.yml
```sh
 theme: story
``` 
### Home Page & Post Page
To genarate the Home page and the blogposts you can use my index.md & post.md

### Demo : [link](https://freehtml5.co/demos/story/)
