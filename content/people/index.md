---
title: People
date: 2022-10-24

type: landing

sections:
  - block: markdown
    content:
      title: 
      subtitle: 
      text: |
        <div class="subtitle-text">
          Meet the team
        </div>
    design:
      columns: '1'
      background:
        image: 
          filename: group_picture.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: contain
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: tiny-banner

  - block: people
    content:
      title: 
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Current members
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
      spacing:
        padding: ['20px', '0', '100px', '0']
---