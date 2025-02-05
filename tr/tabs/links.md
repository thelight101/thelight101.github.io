---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Bağlantılar"
    info: "Bağlantılarımı Kontrol Et ⬇️"

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Sosyal Medya"
      type: id_socials
      color: "#0f64db"
    - title: "Epic Games"
      type: id_epicgames
      color: "#f54a1b"
    - title: "Projelerim"
      type: id_projects
      color: "#278522"

  list:
    -
    # My Projects
    - type: id_projects
      title: "Projelerim"
      url: "https://thelight101.github.io/tabs/projects.html"
      info: "Projelerim burada listelenmiştir. (Zaten sol tarafta var)"

    # Socials
    - type: id_socials
      title: "Instagram"
      url: "https://www.instagram.com/egemenerendogan/"
      info: "Günlük hayatım, projelerim ve içeriklerim burada! Takip etmeyi unutma."
    - type: id_socials
      title: "Youtube"
      url: "https://www.youtube.com/@TheLlight101"
      info: "Oyun oynanış videoları, canlı yayınlar ve eğlenceli içerikler burada! Topluluğa katılmak için abone ol."
    - type: id_socials
      title: "Twitch"
      url: "https://www.twitch.tv/thelight101"
      info: "Canlı yayınlarda eğlence ve oyun bir arada! Bana katıl ve sohbete dahil ol."
    - type: id_socials
      title: "My Discord Server"
      url: "https://discord.gg/xxW4RG8J2j"
      info: "Topluluğumuza katıl, sohbet et ve etkinlikleri kaçırma!"
    - type: id_socials
      title: "X (Twitter)"
      url: "https://x.com/Light101real"
      info: "Düşüncelerim, güncellemelerim ve anlık paylaşımlar burada. Takip et!"

    # epicgames
    - type: id_epicgames
      title: "The Light Interactive"
      url: "https://dev.epicgames.com/community/profile/organization/XKKM/the-light-interactive"
      info: "The Light Interactive, benim yönettiğim bir Epic Games organizasyonudur."
---
