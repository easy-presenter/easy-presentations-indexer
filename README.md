# esay-presentation-indexer

Generates the index for a [easy-presentation](https://github.com/easy-presentations) repository.

This index can by the [easy-presenter](https://easy-presenter.github.io/easy-presenter/)

### required folder structure

```
www.github.com/easy-presentations/[presentation]/
  - pages
      - en
      - de
          - page.md                      # containes the content oh the start page / slide
          - index.md                     # containes the generated index
          - README.md                    # is a combination of page.md + index.md

          - pages/*                      # containes the presentation pages / slides
            - 01_overview                # is presentation topic
              - page.md                  # is the topic front page / slide
              - 01_what_is_wordpress.md  # is a pages / slide
              - 02_any_folder            # is a sub-topic
                - page.md                # is the sub-topic front page / slide
                - 01_nay_slide.md        # is a sub-topic page / slide


                [...] and so on =)

```
