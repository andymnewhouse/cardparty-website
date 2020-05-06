---
title: Home
template: home
view_model: App\ViewModels\AngledHeroCards
sections:
  -
    bard:
      -
        type: paragraph
        content:
          -
            type: text
            marks:
              -
                type: italic
            text: INTRODUCING
      -
        type: set
        attrs:
          values:
            type: image
            image: logo-fire-opal.svg
            width: w-64
            center: false
            frame: false
      -
        type: paragraph
        content:
          -
            type: text
            text: 'Play Progressive Rummy with your friends and family, no matter where they are in the world!'
      -
        type: set
        attrs:
          enabled: false
          values:
            type: buttons
            buttons:
              -
                text: 'Create an Account'
                link: /register
                new_tab: false
                color: btn-red-primary
                size: btn-xl
              -
                text: Login
                link: /login
                new_tab: false
                color: btn-blue-gray-secondary
                size: btn-xl
      -
        type: paragraph
    type: angled_hero
    enabled: true
  -
    uuid: cb195fe9-9038-42ff-90b5-1e81ad8f1fcf
    header: 'Sign up for our newsletter'
    paragraph: 'Stay up to date on progress and be the first to know when we launch!'
    type: newsletter
    enabled: true
  -
    header: 'From the blog'
    paragraph: 'News, tips, and other stuff from Card Party.'
    type: blog
    enabled: true
updated_by: a2a6e7b3-daf1-4e3c-ac03-a05e962d7794
updated_at: 1588731521
id: home
---
