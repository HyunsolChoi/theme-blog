---
title: 
type: landing


sections:
  - block: markdown
    content:
      title: 
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: posts.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
      spacing:
        padding: ['35vh', '0', '35vh', '0']

  - block: collection
    content:
      title: <span style="font-weight:bold; text-aligh:center">전체 포스트</span><br><br>
      subtitle: 
      text: 
      count: 0
      filters:
        folders:
          - post
      offset: 0
      order: desc
      page_type: post
    design:
      spacing:
         padding: ['5vh', '50px', '7vh', '50px']
      view: community/custom-compact
      columns: 1
      
  - block: tag_cloud
    content:
      title: <span style="font-weight:bold">태그</span>
      subtitle:
      text: 태그에 따라 분류된 포스트를 확인하실 수 있습니다.
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 0
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 2.0
      font_size_max: 3.5

---
