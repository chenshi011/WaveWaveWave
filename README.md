
# WaveWaveWave

WaveWaveWave theme for [Hexo](https://hexo.io/) based on [light](https://github.com/hexojs/hexo-theme-light) theme.

## Demo

[Demo Blog](https://chenshi011.github.io/)

## Install

Execute the following command and modify `theme` in `_config.yml` to `air`.

```
git clone git@github.com:chenshi011/WaveWaveWave.git themes/WaveWaveWave
```

## Update

Execute the following command to update air.

```
cd themes/WaveWaveWave
git pull
```

## Config

Default config:

``` yaml
menu:
  首页: /
  归档: /archives
  订阅: /atom.xml

widgets:
- search
- tag
- recent_posts

excerpt_link: Read More

twitter:
  username:
  show_replies: false
  tweet_count: 5

addthis:
  enable: false
  pubid:
  weibo: true
  linkedin: true
  google: false
  facebook: false
  twitter: false
  pinterest: false

copyright:
  enable: true
  claim: 版权声明：自由转载-非商用-无演绎-保持署名 @ WaveWaveWave
  show_link: true

fancybox: true

google_analytics: 
  enable: true
  siteid: UA-99327274-1

baidu_analytics: 
  enable: true
  siteid: 7937c4861afe48bfd9092b806289df2b

rss: 

comment: gentie
# gentie comment
gentie:
  sourceId: ""
  productKey: "7daf16bb12394ce78d0252179a6adc17"

busuanzi_count:
  # count values only if the other configs are false
  enable: true
  unit: 次
  # custom uv span for the whole site
  site_uv: true
  site_uv_title: 本站访客数
  # custom pv span for the whole site
  site_pv: true
  site_pv_title: 本站总访问量
  # custom pv span for one page only
  page_pv: true

[Hexo]: https://hexo.io/
