# esay-presentation-indexer

Generates the index for a [easy-presentation](https://github.com/easy-presentations) repository.

This index can by the [easy-presenter](https://easy-presenter.github.io/easy-presenter/)

### required folder structure

```
www.github.com/easy-presentations/[presentation]/
  - pages
      - en
      - de
          - page.md                      # containes the content of the start page / slide
          - index.md                     # containes the generated index
          - README.md                    # is a combination of page.md + index.md

          - pages/*                      # containes the presentation pages / slides
            - 01_overview                # is a topic
              - page.md                  # is a topic front page / slide
              - 01_what_is_wordpress.md  # is a topic pages / slide
              - 02_any_folder            # is a sub-topic
                - page.md                # is a sub-topic front page / slide
                - 01_nay_slide.md        # is a sub-topic page / slide


                [...] and so on =)

```
